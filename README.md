# Useful-Source
#### MongoDB (mongoose) 32 bit version error

######Error
 "exception in initAndListen: 28663 Cannot start server. The default storage engine 'wiredTiger' is not available with this build of mongod. Please specify a different storage engine explicitly, e.g. --storageEngine=mmapv1., terminating"
 
######Solve
 in command line type>
 > mongod.exe --storageEngine = mmapv1

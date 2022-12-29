#Codertech.Mongo.StackExchangeMongo


 This Package it replacement for Redis Cache for ABP io project. Created using Redis cache and open source code.
 need these app setting in side you json file to configure.
 
   "MongoDbCache": {
    "ConnectionString": "mongodb://localhost:27017",
    "DatabaseName": "MongoCache",
    "CollectionName": "appcache",
    "ExpiredScanInterval": "20"
  }
  
  Add dependency to  CoderTechCachingStackExchangeMongoModule inside your application module

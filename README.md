# key-value-datastore
This is a key-value data store that supports basic Create-Read-Delete operations and has a optional time to live property for key-value pairs.  

## Dependencies
1.Install Libraries (os, json,time)  
2.The working directory must conatin 4 empty json files ({}) named (pairs,ttlpairs,start_time,time_allowed)  
    pairs        : Contains the key-value pairs in json format  
    ttlpairs     : stores the key- value pairs with time-to-live property.  
    start_time   : stores start time of all the pairs with ttl property.  Bug
    time_allowed : stores the time allowed before deletion of the key-value pairs with ttl property. 

## To use this as Module
1.Copy the file to directory where you will import this.  
2.Use Import main_freshworks to import the module.  
3.Use the main funtion and it will prompt to set working directory or will use default directory.  
  The main function will prompt user to enter choices (create/read/delete/end). 
  
### Limitation.
 The time to live property is only valid if the program continues to run : if you exit the program and restart to read the key is not found.

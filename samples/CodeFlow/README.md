# Command Line Usage                                               
                                                                   
Start the authorization server from its directory.                 
```                                                                
cd AuthorizationServer                                             
dotnet run -f netcoreapp2.0 --server.urls="http://localhost:54540" 
```                                                                
                                                                   
Then, run the client application from its directory.               
```                                                                
cd ClientApp                                                       
dotnet run -f netcoreapp2.0 --server.urls="http://localhost:53507"                                                      
```

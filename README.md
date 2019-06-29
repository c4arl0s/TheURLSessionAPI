# TheURLSessionAPI

- The URLSession API is a collection of classes that use a request to communicate with a server in a number of ways. 
- The URLSessionTask class is responsible for communicating with a server. 

## The URLSession class is responsible for creating tasks that match a given configuration.

- The class that communicates with the web service is an instance of URLSessionTask.

- There are three kinds of tasks: data tasks, download tasks, and upload tasks. 

1. URLSessionDataTask retrieves data from the server and returns it as Data in memory.
2. URLSessionDownloadTask retrieves data from the server and returns it as a file saved to the filesystem.
3. URLSessionUploadTask sends data to the server.

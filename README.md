# TheURLSessionAPI

- The URLSession API is a collection of classes that use a request to communicate with a server in a number of ways. 
- The URLSessionTask class is responsible for communicating with a server. 

## The URLSession class is responsible for creating tasks that match a given configuration.

- The class that communicates with the web service is an instance of URLSessionTask.

- There are three kinds of tasks: data tasks, download tasks, and upload tasks. 

1. URLSessionDataTask retrieves data from the server and returns it as Data in memory.
2. URLSessionDownloadTask retrieves data from the server and returns it as a file saved to the filesystem.
3. URLSessionUploadTask sends data to the server.

# The properties on URLRequest:

- allHTTPHeaderFields
- allowsCellularAccess
- cachePolicy
- httpMethod
- timeoutInterval

## allHTTPHeaderFields

A dictionary of metadata about the HTTP transaction, including character encoding and how the server should handle caching.

## allowsCellularAccess

A Boolean that represents whether a request is allowed to use cellular data

## cachePolicy

The property that determines whether and how the local cache should be used

## httpMethod

the request method; the default is GET, and other values are POST, PUT, and DELETE

## timeoutInterval

The maximum duration a connection to the server will be attempted for.

# URLSessionTask

The class that communicates with the web service is an instance of URLSessionTask.

- There are three kinds of tasks:

1. URLSessionDataTask
2. URLSessionDownloadTask
3. URLSessionUploadTask

## 1. URLSessionDataTask

Retrieves data from the server and returns it as Data in memory.

## 2. URLSessionDownloadTask

Retrieves data from the server and returns it as a file saved to the filesystem.

## 3. URLSessionUploadTask

Sends data to the server.

# URLSession acts as a factory for URLSessionTask instances.

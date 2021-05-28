
# CRUD


## In your own words, describe what each group of status code represents:

100’s =These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. 

200’s =These are the success codes. They tell the client that its request was accepted. In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.

300’s =These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore. This can have multiple reasons, be temporary or permanent, but the client has to issue a request to the new location.

400’s =These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc. A client is sending incorrect input and should confirm the input parameters are correct before retrying the request.

500’s =These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server. 

## What is a status code 202?

+ Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available.

## What is a status code 308?

+ Like the 202 code but using a Location header field in response to informing the client about the location of the created resource or an endpoint that lets the client check for the status of the creation process. Some clients follow the status codes of the Redirect-class automatically. This code is usually only used for POST requests.


What code would you use if an update didn’t return data to a client?

+ An update can be implemented with an HTTP PUT or PATCH method. The difference lies in the amount of data the client has to send to the backend.

+ PUT requires the client to send an entire representation of a resource to update it. (Replace the old one with the new one)

+ PATCH requires the client only send parts of the representation of the resource to update it. (Add, update or delete these parts in the old version)


## What is the ‘Forbidden’ status code?

+ 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.
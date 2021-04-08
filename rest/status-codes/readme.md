# REST API RESPONSE STATUS CODES

- **200 OK** – The request has succeeded.
- **201 Created** – The request has succeeded and a new resource has been created as a result. This is typically the response sent after POST requests, or some PUT requests.
- **204 No Content** – There is no content to send for this request, but the headers may be useful. The user-agent may update its cached headers for this resource with the new ones.
- **400 Bad Request** – This means that client-side input fails validation.
- **401 Unauthorized** – This means the user isn’t not authorized to access a resource. It usually returns when the user isn’t authenticated.
- **403 Forbidden** – This means the user is authenticated, but it’s not allowed to access a resource.
- **404 Not Found** – This indicates that a resource is not found.
- **500 Internal server error** – This is a generic server error. It probably shouldn’t be thrown explicitly.
- **502 Bad Gateway** – This indicates an invalid response from an upstream server.
- **503 Service Unavailable** – This indicates that something unexpected happened on server side (It can be anything like server overload, some parts of the system failed, etc.).

For more status refer - [HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)

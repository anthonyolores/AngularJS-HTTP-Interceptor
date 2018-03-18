# AngularJS 1.6.X HTTP Interceptor

By using an the HTTP interceptor it will add another layer of validation before sending the request to the server. It's handy because the validation will be executed in all HTTP calls of your project without doing it per call. So it's useful for global validation of HTTP calls.

Example for request, if it passes a wrong parameter you can redirect the client to a global error page before sending the request to the server. And for response, if the response object has missing data then you can show a message before the client's logic receives it and just redirect to an response error page.

see [AngularJS $HTTP Interceptor](https://docs.angularjs.org/api/ng/service/$http#interceptors)

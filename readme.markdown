# OWIN Components Registry
In order to add or update components listed on this page, please edit the [readme.markdown file](https://github.com/owin-middleware/Registry/blob/master/readme.markdown) using GitHub's browser-based editor and submit the proposed changes. 

## Middleware

### Security
* [Microsoft.Owin.Security](http://www.nuget.org/packages/Microsoft.Owin.Security/) - Base types for authentication middleware.
* [Microsoft.Owin.Security.OAuth](http://www.nuget.org/packages/Microsoft.Owin.Security.OAuth/) - A standard OAuth 2.0 authentication workflow.
* [Microsoft.Owin.Security.Cookies](http://www.nuget.org/packages/Microsoft.Owin.Security.Cookies/) - Cookie or forms based authentication.
* [Microsoft.Owin.Security.Google](http://www.nuget.org/packages/Microsoft.Owin.Security.Google/) - Google's OpenId and OAuth 2.0 authentication workflows.
* [Microsoft.Owin.Security.MicrosoftAccount](http://www.nuget.org/packages/Microsoft.Owin.Security.MicrosoftAccount/) - Microsoft Account authentication workflow.
* [Microsoft.Owin.Security.Facebook](http://www.nuget.org/packages/Microsoft.Owin.Security.Facebook/) - Facebook's OAuth 2.0 authentication workflow.
* [Microsoft.Owin.Security.Twitter](http://www.nuget.org/packages/Microsoft.Owin.Security.Twitter/) - Twitter's OAuth 2.0 authentication workflow.
* [Microsoft.Owin.Security.Jwt](http://www.nuget.org/packages/Microsoft.Owin.Security.Jwt/) - APIs to protect and validate JSON Web Tokens.
* [Microsoft.Owin.Security.ActiveDirectory](http://www.nuget.org/packages/Microsoft.Owin.Security.ActiveDirectory/) - ActiveDirectory based authentication.
* [Thinktecture.IdentityModel.Owin.BasicAuthentication] (http://www.nuget.org/packages/Thinktecture.IdentityModel.Owin.BasicAuthentication/) - HTTP Basic Authentication
* [Thinktecture.IdentityModel.Owin.ClaimsTransformation] (http://www.nuget.org/packages/Thinktecture.IdentityModel.Owin.ClaimsTransformation/) - Claims transformation
* [Thinktecture.IdentityModel.Owin.ClientCertificates] (http://www.nuget.org/packages/Thinktecture.IdentityModel.Owin.ClientCertificates/) - X.509 client certificate authentication
* [Thinktecture.IdentityModel.Owin.RequireSsl] (http://www.nuget.org/packages/Thinktecture.IdentityModel.Owin.RequireSsl/) - Require SSL and client certificates
* [Thinktecture.IdentityModel.Owin.ScopeValidation] (http://www.nuget.org/packages/Thinktecture.IdentityModel.Owin.ScopeValidation/) - Scope-based token validation for OAuth2 and OpenID Connect
* [Thinktecture.IdentityModel.Hawk] (http://www.nuget.org/packages/Thinktecture.IdentityModel.Hawk/) - Implementation of the Hawk authentication scheme
* [NWebsec.Owin] (https://www.nuget.org/packages/NWebsec.Owin/) - HTTP security headers

### Routing
* [Superscribe.Owin](http://superscribe.org/) - Routing as middleware

### Other
* [Microsoft.Owin.Diagnostics](http://www.nuget.org/packages/Microsoft.Owin.Diagnostics/) - An error page and welcome page to assist in developing OWIN-based applications.
* [Microsoft.Owin.StaticFiles](http://www.nuget.org/packages/Microsoft.Owin.StaticFiles/) - Handle requests for file based resources such as files and directories.
* [Microsoft.Owin.Cors](http://www.nuget.org/packages/Microsoft.Owin.Cors/) - Handles Cross Origin Resource Sharing requests.
* [Owin.Limits](http://www.nuget.org/packages/Owin.Limits/) - Apply limits (MaxBandwidth, MaxConcurrentRequests, ConnectionTimeout) to an OWIN pipeline.
* [Owin.RequiresHttps](https://www.nuget.org/packages/Owin.RequiresHttps/) - Determines if requests are HTTPS and provides options for routing if not or 401 response.
* [Owin.SiteMapping](http://www.nuget.org/packages/Owin.SiteMapping/) - Partition of an OWIN application by host header and port number.
* [DotNetDoodle.Owin.Dependencies](https://github.com/DotNetDoodle/DotNetDoodle.Owin.Dependencies) - An IoC container adapter into OWIN pipeline

## Servers and Hosts
* [Microsoft.Owin.Host.SystemWeb](http://www.nuget.org/packages/Microsoft.Owin.Host.SystemWeb/) - Enables OWIN-based applications to run on IIS in the ASP.NET request pipeline.
* [Microsoft.Owin.Host.IIS](http://www.nuget.org/packages/Microsoft.Owin.Host.IIS/) - Enables running an OWIN pipeline directly on top of IIS without ASP.NET.
* [Microsoft.Owin.Host.HttpListener](http://www.nuget.org/packages/Microsoft.Owin.Host.HttpListener/) - OWIN server built on the .NET Framework's HttpListener class used for self-hosting.
* [Nowin](https://github.com/Bobris/Nowin) - Owin Web Server in pure .NET used for self-hosting.
* [Microsoft.Owin.Hosting](http://www.nuget.org/packages/Microsoft.Owin.Hosting/) - APIs to load and run an OWIN pipeline and server in self-host applications.
* [Microsoft.Owin.Testing](http://www.nuget.org/packages/Microsoft.Owin.Testing/) - APIs to load and run an OWIN pipeline in memory for testing purposes.

## Frameworks
* [ASP.NET Web API](http://www.asp.net/web-api) - A framework for building HTTP-based APIs
* [ASP.NET SignalR](http://www.asp.net/signalr) - A framework for building bi-directional, real-time Web functionality
* [Nancy](http://nancyfx.org) - A lightweight framework for building Web applications
* [FubuMVC](http://mvc.fubu-project.org) - A “Front Controller” pattern-style MVC framework designed for use in web applications built on ASP.NET
* [Simple.Web](https://github.com/markrendle/Simple.Web) - A lightweight, object-oriented (Model-View-Handler) framework for modern web development in .NET
* [duovia-http](https://github.com/duovia/duovia-http) - A lightweight OWIN-based services library
* [Microsoft.Owin](http://www.nuget.org/packages/Microsoft.Owin/) - APIs to help implement OWIN middleware and construct pipelines.

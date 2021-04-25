## Spring Security

#### Spring Security is a bunch of servlet filters that help you add authentication and authorization to your web application.

#### Authentication : if you are running a typical web application, you need your users to authenticate. That means your application needs to verify if the user is who he claims to be, typically done with a username and password check.

#### Authentication Manager: is the core for the Spring security authentication process. AuthenticationManager is the API that defines how Spring Security’s Filters perform authentication.

### FilterChains

#### For example, an incoming HTTP request would : ​

#### First, go through a LoginMethodFilter…​

#### Then, go through an AuthenticationFilter…​

#### Then, go through an AuthorizationFilter…​

#### Finally, hit your servlet.

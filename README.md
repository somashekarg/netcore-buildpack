# .NET Core 2.x Buildpack for Heroku with Heroku Postgres
## by Softtrends LLC

This Buidpack can be used to compile and deploy ASP.Net Core Application, ASP.Net Core MVC Application to Heroku. It will pull the .NET Core dependencies from Microsoft, build a .NET Core Application and deploy it to the Heroku Platform by provisioning a free version of Heroku Postgres. You should use Visual Studio 2017 for best compatibility. Any tool from Visual Studio Code to the fully-featured Visual Studio Enterprise is supported.

# References

.NET Core [Learn what's new](https://docs.microsoft.com/en-us/dotnet/core/)<br/>
ASP.NET Core [Learn what's new](https://go.microsoft.com/fwlink/?LinkId=518016)<br/>
Visual Studio [Learn and download](https://www.visualstudio.com/)<br/>
Heroku Buildpacks [How to use](https://devcenter.heroku.com/articles/buildpacks#setting-a-buildpack-on-an-application)
<br/>
            
# Example
In order to see the buildpack in action, you can click on the button below which will deploy a sample ASP.Net MVC application with Postgres database support to heroku and you can see the build and deployment logs as the application gets deployed for you. This application was developed using Visual Studio 2017. 
<br/>
<br/>
<a href="https://heroku.com/deploy?template=https://github.com/heroku-softtrends/dotnetcore2.postgres.sample/tree/master">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
<br/>
<br/>
Sample Application source code is also available [Sample](https://github.com/heroku-softtrends/dotnetcore2.postgres.sample/tree/master)


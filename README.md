# SimpleWebApp
Simple [ASP.NET Core 2.0](https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-2.1) Web App (with [Razor Pages](https://docs.microsoft.com/en-us/aspnet/core/mvc/razor-pages/?view=aspnetcore-2.1&tabs=visual-studio)!) to demonstrate using inside a container. Since it's developed using Core 2.0, we are able to target both Windows containers as well as Linux containers. Once deployed, we are executing a simple statement inside the in order to get the machine name:


```
<h4>@Environment.MachineName</h4>
```

![Machine Name](simplewebapp/docs/machinename.png)

The Dockerfile and code is ready to be pulled down. If you'd like to pull a Linux image from docker hub, you can access the image [here](https://hub.docker.com/r/ckriutz/simplewebapp/).

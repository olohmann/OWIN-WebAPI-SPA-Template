# OWIN-WebAPI-SPA-Template

> A Visual Studio Extension containing a project template for simple OWIN-based ASP.NET WebAPI projects.

## Background
A custom C# web project template that is inspired by NodeJS. It is based completely on OWIN and Web API 2.2. It uses an OWIN middleware for static file handling and does not rely on IIS at all (the default is OWIN host). This has some nice side effects like being able to declare a specific folder in the project where all my static content (i.e. the SPA) resides. There are no JavaScript libraries or frameworks included in the template. It provides you a skeleton that can be extended with modules from NuGet or Bower to your needs.

## Warnings

* Think twice before using the template for production. Static file handling is most likely not the fastet via the OWIN middleware.
* OWIN is an evolutionary step towards ASP.NET 5 (ASP.NET vNext). Once ASP.NET 5 comes into RTM, jump on that.

## Links

* [Blog Post](http://www.oliver-lohmann.me/a-very-basic-asp-net-web-api-single-page-application-template/)
* [Visual Studio Gallery](https://visualstudiogallery.msdn.microsoft.com/e376f2f7-4412-4b75-8ccf-818c45adafe5)

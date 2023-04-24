![Jekyll](https://user-images.githubusercontent.com/2342458/227201223-77cd42ef-ef91-405d-ad46-c491f6dbda27.png)
# Kinsta - Hello World - Static Site With Jekyll

An example of how to deploy a static site built with Jekyll on Kinsta App Hosting services.

---
Kinsta is a developer-centric cloud host / PaaS. We’re striving to make it easier for you to share your web projects with your users. Focus on coding and building, and we’ll take care of deployment and provide fast, scalable hosting. + 24/7 expert-only support.

- [Start your free trial](https://kinsta.com/signup/?product_type=app-db)
- [Application Hosting](https://kinsta.com/application-hosting)
- [Database Hosting](https://kinsta.com/database-hosting)

## Dependency Management

Kinsta automatically installs dependencies defined in your `Gemfile` file during the deployment process.

## Web Server Setup

### Port

Kinsta automatically sets the `PORT` environment variable. You should **not** define it yourself and you should **not** hard-code it into the application.

### Start Command

When deploying an application, Kinsta automatically creates a web process based on the content of `Procfile` as the entry point.

## Deployment Lifecycle

Whenever a deployment is initiated (through creating an application or re-deploying due to an incoming commit) the `bundle install` command is run.

## What is Jekyll
Jekyll is an open-source static site generator that uses text written in your favorite markup language to produce a customized static site without the need for a database. More information is available on the [Jekyll](https://jekyllrb.com/) website.

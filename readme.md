![](https://user-images.githubusercontent.com/2342458/194169079-aa12e92d-87fd-4da4-9afd-93de44874dae.png)
# Kinsta - Hello World - Static Site With Jekyll 🚀

An example of how to deploy a static site built with Jekyll on Kinsta App Hosting services.

---
Kinsta is a developer-centric cloud host / PaaS. We’re striving to make it easier for you to share your web projects with your users. Focus on coding and building, and we’ll take care of deployment and provide fast, scalable hosting. + 24/7 expert-only support.

- [Start your free trial](https://kinsta.com/signup/?product_type=app-db)
- [Application Hosting](https://kinsta.com/application-hosting)
- [Database Hosting](https://kinsta.com/database-hosting)

## Dependency Management

During the deployment process, Kinsta will automatically install dependencies defined in your `package.json` file.

## Web Server Setup

### Port

Kinsta automatically sets the `PORT` environment variable. You should **not** define it yourself and you should **not** hard-code it into the application.

### Start Command

When deploying an application Kinsta will automatically create a web process based on the content of `Procfile` as the entry point.

## Deployment Lifecycle

Whenever a deployment is initiated (through creating an application or re-deploying due to an incoming commit) the `bundle install` command is run.

## What is Jekyll
**Jekyll** is a static site generator. It takes text written in your favorite markup language and uses layouts to create a static website. You can tweak the site’s look and feel, URLs, the data displayed on the page, and more.

More info on the [Jekyll](https://jekyllrb.com/) website.

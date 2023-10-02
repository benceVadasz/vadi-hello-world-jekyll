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

# Heroku


## Getting Started on Heroku with Node.js


1. Set up: In this step you’ll install the Heroku Command Line Interface (CLI). You use the CLI to manage and scale your applications, provision add-ons, view your application logs, and run your application locally.
2. Prepare the app: In this step, you will prepare a sample application that’s ready to be deployed to Heroku.
3. Deploy the app: In this step you will deploy the app to Heroku. Create an app on Heroku, which  prepares  Heroku to receive your source code.
4. View logs: Heroku treats logs as streams of time-ordered events aggregated from the output streams of all your app and Heroku components, providing a single channel for all of the events. View information about your running app using one of the logging commands, heroku logs --tail.
5. Define a Procfile: Use a Procfile, a text file in the root directory of your application, to explicitly declare what command should be executed to start your app.
6. Scale the appRight now, your app is running on a single web dyno. Think of a dyno as a lightweight container that runs the command specified in the Procfile. You can check how many dynos are running using the ps command.
7. Declare app dependencies: Heroku recognizes an app as Node.js by the existence of a package.json file in the root directory. For your own apps, you can create one by running npm init --yes. The demo app you deployed already has a package.json
8. Run the app locally: Now start your application locally using the heroku local command.
9. Push local changes
10. Provision add-ons: Add-ons are third-party cloud services that provide out-of-the-box additional services for your application, from persistence through logging to monitoring and more. By default, Heroku stores 1500 lines of logs from your application. However, it makes the full log stream available as a service
11. Start a console
12. Define config vars: Heroku lets you externalize configuration - storing data such as encryption keys or external resource addresses in config vars.
13. Provision a database: The add-on marketplace has a large number of data stores, from Redis and MongoDB providers, to Postgres and MySQL. In this step, you will add a free Heroku Postgres Starter Tier dev database to your app.
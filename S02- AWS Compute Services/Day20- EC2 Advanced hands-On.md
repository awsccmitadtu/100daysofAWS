# Deploying a Rails App on AWS with Capistrano and RDS

This guide will walk you through deploying a Ruby on Rails application to an AWS EC2 instance using Capistrano while utilizing AWS RDS for your production database.

[Article Link](https://medium.com/@KerrySheldon/ec2-exercise-1-6-deploy-a-rails-app-to-an-ec2-instance-using-capistrano-3485238e4a4a)

## Overview

In this exercise, you'll go through the following steps:

1. **Provision an AWS RDS Postgres Database:** Set up a PostgreSQL database on AWS RDS.

2. **Create an EC2 Instance:** Launch an EC2 instance with Ubuntu Server 16.04.

3. **Create a Rails App and Configure Capistrano:** Generate a Rails app, configure Capistrano for deployment, and set up environment variables.

4. **Configure the EC2 Instance:** Prepare the EC2 instance by installing essential software, Ruby, Node.js, and Passenger and Nginx for serving the app.

5. **Add a Deployment User and Configure GitHub Credentials:** Create a deployment user on the EC2 instance, set up SSH keys, and configure GitHub credentials.

6. **Deploy the App using Capistrano:** Deploy your Rails app using Capistrano and enjoy the results!

## Note: 
This exercise may involve some advanced steps, but stay patient—your efforts will be well worth it in the end!

## If above Exercises seems overwhelming Don't Worry we have your Back
[Watch this for EC2 Exercises-1](https://youtu.be/mETfcK3NUCE?si=JL3FgGQT2Qwvdqvh)
[Watch this for EC2 Exercises-2](https://youtu.be/z9VpUHO7XQ8?si=BnhAtF1jXAt1gKhu)

Feel free to reach out if you have any questions or encounter any issues during the exercise. Happy deploying!

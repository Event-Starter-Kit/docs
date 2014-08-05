# Event Starter Kit

![Logo](assets/Logo-gray-small.png)

Event Starter Kit (ESK from now on) is born out of the **[Web European Conference](http://webnextconf.eu)** by [Ugo Lattanzi](http://tostring.it) and [Simone Chiaretta](http://codeclimber.net.nz/).


The idea is to create something that helps people to organize a conference with minimal effort. 
In our case, the conference is a tech conference, but of course, you can use ESK for all kinds of conference.

## Features

A good conference requires some tech stuff:

* **Launch page**;
* **Website**;
* **Blog for news**;
* **Mobile apps** (iOS, Android and Windows Phone);

### Launch page

Basically this is a web page where you can put some basic information about the event and the user can subscribe to the mailing list to be kept updated.

### Website

This is the next step after the launch page. It contains all the information you need for the conference, for example: 

* Call for papers;
* Voting;
* Registration;
* Newsletter / mailing list;
* Waiting list;
* Sponsor pages;
* Agenda;
* Lots of other features;

Of course, the website is responsive.

### Blog

It's a basic blog, maybe a bit 'geek' but very powerful. The idea is to offer a place where you can post your news and updates about the event.

### Mobile app

We are planning to create an app that includes everything your delegates will need during the event, for example session voting, agenda and so on.

## Tech stuff

### Server side code
The API and website are built on top of [NodeJs](http://nodejs.org) so you can host ESK on both Windows or Linux servers.

### Hosting

Of course you can host your website wherever you like, but in the repository you will find a script to deploy the website on [Microsoft Azure](https://azure.microsoft.com) using only Git.

### Database
We are using [MongoDb](mongodb.org) because it is free and really powerful.

For the blog we would recommend [Github Pages](https://pages.github.com/), also free.

### Mobile Code

The app is built using [Xamarin](https://xamarin.com), so you can easily modify the app and deploy your code on the most popular mobile operating systems (iOS, Android and Windows Phone).

## Social integration

There are several cool services on the web that are leaders for specific functions.
We think it is helpful use them directly from ESK so we implemented:

* [Twitter](http://www.twitter.com) (for login/registration and sharing)
* [Facebook](http://www.facebook.com) (for login/registration and sharing)
* [Github](http://github.com) (for login, because we are nerds);
* [Mailchimp](http://mailchimp.com/) (for mailing list and newsletters);
* [Eventbrite](https://www.eventbrite.com/) (for event registration)
* [Disqus](http://disqus.com) (for comments)
* [Slideshare](http://www.slideshare.net/) (for presentation slides)
* [Vimeo](http://vimeo.com) (for video sessions)
* [Paypal](http://paypal.com) (for donations)

## How to use it

Unfortunately, right now ESK is not ready except for the launch page and the blog. But of course you can collaborate to complete this important and ambitious project.

Contact [Ugo Lattanzi](http://tostring.it) or [Simone Chiaretta](http://codeclimber.net.nz/) or create a PR for one of our repositories:

* [Launch page](https://github.com/Event-Starter-Kit/lauch-site)
* [Blog](https://github.com/Event-Starter-Kit/blog)
* [Website](https://github.com/Event-Starter-Kit/website)
* [Mobile](https://github.com/Event-Starter-Kit/xamarin-mobile-app)

We bought the HTML template from [themeforest.net](themeforest.net) so you have to buy the license (less than $20 USD) or replace the HTML with your own.











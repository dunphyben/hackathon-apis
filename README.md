# hackathon-apis

### Note:
We are currently putting the finishing touches on the official hackathon repository. Please use this document for the time being to upload the information for your APIs. Fork this repo and commit changes based upon the template below.  
  
You can also communicate with hackers directly in the Discord group, and in your specific sponsor channel. The discord invite link is here: https://discord.gg/5zFX4ac

# APIs
Listed here are the APIs for your use.
* Browse the APIs here. Visit docs etc.
* Meet with the API sponsors at the hackathon, particularly on Saturday morning
* Communicate with the API sponsors via their dedicated Discord channel.



# Netlify
Netlify automates deployment for your frontend, serving your apps and sites over our custom global Content Delivery Network. You won't need server-side rendering with our integrated [prerendering](https://www.netlify.com/docs/prerendering), [proxy redirects](https://www.netlify.com/docs/redirects), [form handling](https://www.netlify.com/docs/form-handling), [user authentication](https://www.netlify.com/docs/identity), [serverless Lambda functions](https://www.netlify.com/docs/functions), and more.

### Purpose
Developers everywhere are using the [JAMstack](https://jamstackconf.com/what-is-jamstack) approach to connect blazing fast frontends to a growing array of microservice APIs. There are lots of advantages to this, but sometimes you need to run a bit of server-side code. It's not worth running a whole server for, and that approach doesn't scale well, anyway. Serverless functions services like AWS Lambda are perfect for this, and Netlify's [new functions add-on](https://www.netlify.com/blog/2018/03/20/netlifys-aws-lambda-functions-bring-the-backend-to-your-frontend-workflow/) makes it easy to deploy, test, and access your Lambda functions right alongside the rest of your app.

### Challenges
<!-- We are looking for the most interesting app using Netlify's integrated Lambda [functions](https://www.netlify.com/docs/functions).

To be eligible for the prize, your app must be deployed to Netlify, and use at least one Lambda function. -->

### Docs
https://www.netlify.com/docs/


### Video tutorial


### Presentation slides
<!-- Find links to all the docs!
http://hack2018.netlify.com -->

### Prizes


***



# Fauna
#### Quick Description
Cloud database with generous free plan and distributed ACID transactions for global data integrity. Get started easily and scale to worldwide success.

### Purpose
Stores transactional data like account balances, user profiles, social media content, shopping cart orders, etc. 

##### API endpoint:
Install with the netlify command line tool after you have linked your checkout to your app, by running `netlify addons:create fauna` and you can access your database with environment variables like this:

```js
const client = new faunadb.Client({
  secret: process.env.FAUNADB_SERVER_SECRET
});
```

### Challenges

A common pattern with Single Page Apps is for the browser to query a cloud database directly. FaunaDB access control supports apps like this. A [demo app using the Netlify Identity service and login widget to authenticate with FaunaDB is available here.](https://github.com/fauna/netlify-faunadb-todomvc) Follow the eight steps in the README and you'll be ready to build your own app.

### Docs

The [FaunaDB Query API docs](https://app.fauna.com/documentation/reference/queryapi) are a good reference.

For [getting started with the data model, this tutorial is good.](https://app.fauna.com/documentation/howto/crud) And when you log into fauna.com (not required to get started) you can [learn more about the Fauna Shell and other tools here.](https://app.fauna.com/account)

### Video tutorial

I'll walk through these steps live during the Hackathon keynote.

### Presentation slides

Coming soon.

### Prizes

1st: Apple Watch
2nd: Oculus Go standalone VR headset
3rd: $100 iTunes Gift card


***

# Formspree
#### Quick Description


### Purpose


##### API endpoint:


### Challenges


### Docs


### Video tutorial


### Presentation slides


### Prizes


***

# Clarifai
#### Quick Description


### Purpose


##### API endpoint:


### Challenges


### Docs


### Video tutorial


### Prizes


***


# Hasura
#### Quick Description
<!-- Hasura provides instant backend APIs for your frontend, a simple `git push` to deploy your app and GraphQL APIs on PostgreSQL without any set up. -->


### Purpose
<!-- Almost every dynamic Web or Mobile App requires an API to talk to the Database, Authentication for User Identity, some form of File Management and an easy way to deploy.

Hasura makes your development fast with
* Instant Backend APIs for Database (GraphQL / HTTP JSON over PostgreSQL)
* Authentication APIs for multiple providers with a ready to use UI Kit.
* Filestore APIs to manage file uploads and retreival.

Imagine all of these APIs with permissions / access control defined by you for your application. And just doing a `git push hasura master` to deploy your app.

Hasura has quickstart projects so that you don't have to setup the initial project structure / boilerplate code. Head over to [Hasura Hub](https://hasura.io/hub) for cloning a boilerplate of your choice. For example - [hello-react](https://hasura.io/hub/projects/hasura/hello-react). This will be a ready to deploy project which will give you a hasura-app.io domain for your project, HTTPS enabled, HTTP/2 - gzip supported API Gateway so that its production ready. -->


#### API Endpoint:

### Challenges


### Docs
<!-- - [Getting Started Hasura](https://docs.hasura.io/0.15/manual/getting-started/index.html)
- [Database](https://docs.hasura.io/0.15/manual/data/index.html)
- [Authentication](https://docs.hasura.io/0.15/manual/auth/index.html) -->


### Video tutorial
<!-- - [Introduction to Hasura Data APIs](https://vimeo.com/246571798)
- [GraphQL APIs over PostgreSQL](https://storage.googleapis.com/hasura-io-assets/website-graphQL-preview.mp4) -->


### Prizes


***

# Pilon
#### Quick Description


### Purpose


##### API endpoint:


### Challenges


### Docs


### Video tutorial


### Prizes

***

# Overall Winners
#### The top 6 teams will present to a panel of judges including representatives from freeCodeCamp, Netlify, Formspree, and Fauna.
Note: "Overall" winners are separate from the "API winners". Each API sponsor will have their own challenges and prizes.

### Prizes
* TBA

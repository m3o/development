# Hiring

Micro is a globally distributed technology company focused on building developer first focused tools to simplify 
microservice development. We're actively hiring in a global and remote fashion.

If you're interested in being hired join the **#hiring** channel on [slack](https://micro.mu/slack/) or [email us](hello@micro.mu).

## Roles

We're currently hiring for two roles

- Software engineer - focused on the open source side continuing the development of micro and go-micro
- Services engineer - building microservices to power the platform and network

## Apply

Our hiring process is fairly straight forward:

- Get in touch via Email or Slack
  * Tell us why you want to work for micro
  * Tell us one thing missing from micro 
  * Tell us where you can contribute the most
- Provide us links to github/linkedin, etc
- Provide any other info you think is relevant
- Do the code test and send it in upfront

## Interview

We'll do the following:

- Give you a microservice related code test
- Talk with you on slack or jump on a call for 20 mins
- Follow up with online coding/architecture interviews
- Schedule video calls with individual team members

## Code Test 

Build a food popup recommendation service consisting of three microservices which can be searched by geolocation, name or keyword.
The solution should allow new popup locations to be stored and expired, searched via location or keyword and hold reviews.

Service breakdown may be as follows:

- Place service - to store the place, name and keywords/tags
- Review service - to store reviews associated with a place
- Geolocation service - which tracks the location of places and allows it to be searched

The solution should use go-micro. Demonstrate how it can be interacted with via the micro toolkit (api, web ui, cli)

# Time to take some REST!

Very excited to start our engineering blog! We are starting a series called the #EngineeringExplained where we will be sharing video and blog posts demystifying a lot of these technology topics.
Without further ado, let’s talk about REST.

## What’s REST?
Wikipedia defines REST as,
> “Representational state transfer (REST) is a software architectural style that uses a subset of HTTP.
> It is commonly used to create interactive applications that use Web services…”

You can think of REST as the web service that powers the internet. Up until a few years, REST was the dominating technology that tied the Internet together. 
But as the Internet evolved, with more and more users, and more global distribution of information, other technologies like GRPC & Websockets (more on this in a future post) have become popular choices for buidling scalable systems, supporting high throughput!
Now back to REST, there are few things about it, we’d like to highlight, a few important characteristics of REST systems below,
- Client-Server Architecture: Anything happening in the Internet has a user, who wishes to perform an action, such as interacting with a system, say your news feed, weather etc. In this example, the user(or more specifically his/her’s device) is the Client. The system being interacted with, the news site or the weather app, is “hosted” on a server. The interaction b/w the Client and Server happens via the HTTP protocol
- Statelessness: REST does not belong to anyone state, it belongs to all of us :). Jokes aside .. Wikipedia says

> “In a client–server interaction, the state is made up of intrinsic state and extrinsic state. Intrinsic state, called resource state, is stored on the
> server… Extrinsic state, called application state, is stored on each client and consists of information that is dependent on the server’s context…”

Woah, a lot of fancy words, let’s unpack that! Statelessness means the server does not store any information about the client’s request.
Every HTTP request happens in complete isolation. When the client makes an HTTP request, it includes all information necessary for the server to fulfill that request.
- Cacheability: This means that in REST the intermediaries involved in the request-response model, can cache the information! To give another analogy, when you visit a website for the first time, have you noticed the site takes a couple to load? Subsequent visits to this website, are much faster! This is because of caching! Static resources which are requested as part of a client-server interaction can be cached at various intermediaries, making the response times quicker on any subsequent requests from Client to Server
There is more, but we’d stop here and you can learn about all facets of REST from this [wiki link](https://en.wikipedia.org/wiki/Representational_state_transfer).

## Testing a REST system
Now coming to the original intent of the article, we wanted to share an awesome video created by [Jose Lopez](https://github.com/jllopez) from A.E. about how you’d test a REST API with automation! He has started a series of videos on his youtube channel on how you’d start with testing a Rest API.
> Building a Python RestAPI Test Automation Framework — [Part 1/6: Building the project’s foundation](https://www.youtube.com/channel/UC-iTbHAUoCyDTfBAKMdUVAg)

Bravo Jose !! This is great content and an amazing start to A.E’s digital content journey.

We are really fortunate to you have you on board at A.E and we look forward to more contributions from you!

---
title: Hello World!
publish_date: 2023-02-08
---

# How does the web work?

An Introduction to Web Development.

## Web Toolkit

In this series of blog posts we will be going over many tools that we would come across learning web development, and let's keep adding it to our web toolkit.

#### **Web browser:** 

This is the application through which you can access the internet, i.e., all your websites

#### **Websites:** 

All your websites, web applications, or whatever you want to call, they are all basically at the end of the day just plain old html pages. These are wrapped, beautified, framework-ified, but all of these websites that your browser shows you, are just still HTML pages. (I know this is kind of vague but if you stick with me till the end of this document, we can see what these HTML pages are and how each website has several HTML pages which can be accessed. For now, we can just think of websites as bunch of HTML pages, each with it's own link)

#### **Server:** 

So, we know what a browser is and what makes up the websites, so all these files of a website needs to be stored somewhere on another computer from which we can access from, that computer is known as a server. 

## **Workings of the Web:** 

To put it simply it's just a request and response, expanding on this, 

We users, through our web browsers, request a website that's stored on a server somewhere, and we get back a response in our browser i.e, we get back the HTML files we requested for, and that's the response. This repeats whenever we start clicking links on the received HTML page, this sends new requests to the server, and we get back the newly requested HTML pages.

Examples:

**Accessing google:** You open the browser and try to access google, by typing in google.com domain, what happens here is that the web browser will process your string and creates a request, and sends it to the server(where the website is hosted). Then this server processes this request, and returns a response(a HTML document) i.e., the homepage for the google website.

**Searching on google:** Whenever you search anything in google.com and hit enter, the browser (which is also know as the client) in this case will process your string and construct a request, and sends it to the server(This server is setup by google). Then this server processes this request, and returns a response(a HTML document) with all the results for the search query. A similar thing is done when you access a link from this page, and it would again start a request-response protocol between the web browser and the server. This protocol is called HTTP Protocol. The server and the browser communicate with each other using this HTTP Protocol. 

Another thing to observe is how the server is also processing the google's search query to fetch the best results for the given query. So along with serving html documents, server also processes other code to perform other tasks related to the web application.

[![A lecture Slide from Adv Web Dev b](/images/lecture_image_webdev.png "by Dr. Yuan Wang")]()

#### More on HTTP Protocol

HTTP Protocol is stateless. This basically means, each request is independent of any other request between the server and the client. Like the server doesn't remember the client who sent the first google.com domain request, it doesn't treat this client specially like remembering that they asked for this domain, they might search something, let me wait for them to get back, NO, this is not how the client server relation works, every request response HTTP protocol is independent. [HTTP is stateless, but not sessionless](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview#http_is_stateless_but_not_sessionless), however we will not go into sessions now. Very soon, we will go into sessions when we start working with web applications.

**Links:**

HTTP Definition : https://developer.mozilla.org/en-US/docs/Web/HTTP
HTTP Overview : https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview

From the workings of the web, we can also update on what the web browser does, what the web server does.

**Web browser** renders the HTML documents, it unwraps all the complexities of how the HTML document is wrapped, and shows up this beautiful UI that the user interacts with.

**Web server** also needs to do some program logic to handle these HTML files we were discussing of. So the server is made up of some program logic, and HTML documents. (Again, as we go into detail and inner workings, you will have a much better idea on this program logic part)

---
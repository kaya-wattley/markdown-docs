

# Postman API Testing



### Overview

Postman is an API platform that can be utilized to build and use APIs. Though Postman's API building features are incredibly interesting and fun to play with, these docs will only focus on using and testing APIs built using node. If you would like a more wholistic and in-depth understanding, you should definitely take a look at the Postman documentation. They are masterfully written in a way that makes them enjoyable to read through, and easy to to understand. You can find Postman's docs here: https://learning.postman.com/docs/getting-started/introduction/.



### First Things First

Before diving into setting up a Postman testing environment, there are few concepts that need to be addressed first. Make sure to look through the information below before proceeding through these notes. First things first though, take a look at this Installation guide to help get Postman up and running on your local machine: https://learning.postman.com/docs/getting-started/installation-and-updates/.



### What is an API?

An Application Programming Interface, or **API** for short, serves as a means for two applications to communicate with one another. A popular example would be logging into an application such as Facebook from a mobile application. When you go through the login process, a request is sent to the Facebook API from your phone to retrieve your account and information related to it. That request is then sent to one of Facebook's servers to access that information so that it can be sent back to the mobile app.



#### API Requests

As mentioned above, an API is used as a means to communicate to an application's server from another application. This communication is done via requests/calls, that represents the action that is to be done on the server-side data. One would make a request to the API, which will then invoke an action on an application's server. Below are the different types of HTTP methods used when making an API request with a brief description:

- **GET** request(s) retrieves data from an API.
- **POST** request(s) sends new data to an API.
- **PATCH** and **PUT** request(s) update existing data.
- **DELETE** request(s) removes existing data.



### End of Section

This marks the end of this section. Assuming that you've followed the installation instructions from Postman's documentation, you're now ready to set up a testing environment. Check out the next section for more information regarding that.
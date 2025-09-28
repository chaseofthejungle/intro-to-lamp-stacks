# Intro to Lamp Stacks Overview Guide

**TODO:** A brief introductory guide to LAMP stacks for open source web apps.

<hr />

## 1. What is a LAMP Stack?

LAMP stacks are integrated suites of technologies for gosting dynamic websites and web apps. In short, they are bundles of four core open-source software components:

1) **Linux** (providing an Operating System, as a fountain).
2) **Apache** (as a web server, handling incoming data requests and serving up web page data).
3) **MySQL** (for database purposes, storing and keeping web asset data organized)
4) A **server-side scripting language** (such as Python, PHP, or Perl... all beginning with 'P', hence the 'P' in 'LAMP'... to process server-side code and generate the dynamic content that will be sent back to the client--that is to say, a user's web browser).

<hr />

## 2. Why These Four Technologies?

To put in succinctly: because they interface together to get the job done. It's a logical pipeline, and it works a high level:

* The *Linux* operating system provides provides a *base layer* for the integrated suite of 'LAMP' technologies. By being open-source, highly secure, customizable, and highly stable (although the extent of this is dependent upon distribution/distro), Linux is an excellent OS option for web server deployment.

* *Apache* (also open-source, like the other 'LAMP' components) delegates web data requests from clients (users' web browsers) to relevant apps (or, alternatively, it serves static data files). It integrates seamlessly with Linux, provides modular control mechanisms, and can perform even at highly scalable traffic levels.

* *MySQL*, as a Relational Database Management System (RDBMS), is used for creating, reading, updating, and deleting ('CRUD' operations) data. For 'LAMP' apps, this is web app data that needs to be organized by such constructs as content and user data. LAMP (Apache) web servers rely on MySQL to serve them the data that need to be fed to clients.

* *Server-side scripting languages*, such as Python, PHP, and Perl, generate dynamic web content by running code, interfacing with MySQL to fetch data, and then formatting the data into HyperText Markup Language (HTML) to be rendered by the client (web browser). 

<hr />

## 3. How Does a LAMP Stack Operate?

This can be summarized as five sequential steps:

1) A *user's web browser* sends out a data request for a web page that will be served by an *Apache web server*. 
2) Should this request be for a dynamic page, Apache will then send this request to a *server-side scripting language's script* (the Python, PHP, or Perl code). 
3) The server-side scripting language runs its code (and might send a request to the *MySQL database* if it needs to retrieve data from it). 
4) The server-side script puts the data and code together, to generate an *HTML page*. 
5) The *Apache server* then sends the HTML page back to the *client (user's browser)* so that it can be displayed/used.

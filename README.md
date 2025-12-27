# Intro to LAMP Stacks Overview Guide

**Description/Overview:** Although various philosophies for developing and deploying dynamic web applications are in popular use today, LAMP stack development provides a zero-to-low cost full-stack solution (both the front-end user side and back-end server side) that can be readily and cohesively customized in both granular and holistic ways.

#### Table of Contents

1. [What is a LAMP Stack?](#lamp)
2. [Why These Four Technologies?](#four)
3. [How Does a LAMP Stack Operate?](#operate)
4. [A Note on MEAN and MERN Stack Development](#meanmern) 
5. [Supplemental Resources](#supplemental)

<hr />

## 1. <a name="lamp">What is a LAMP Stack?</a>

LAMP stacks are integrated suites of technologies for hosting dynamic websites and web apps. In short, they are bundles of four core open-source (freely available to all and potentially maintained by anyone and any community) software components:

| Component | Role |
| :---: | :---: |
| [**Linux**](https://www.linux.org/) | Provides an Operating System, which serves as the stack foundation. |
| [**Apache**](https://www.apache.org/) | Supports web servers, handling incoming data requests and serving up web page data. |
| [**MySQL**](https://www.mysql.com/) | For database purposes, storing and keeping web asset data organized. |
| A **Server-Side Scripting Language** (such as [**P**ython](https://www.python.org/), [**P**HP](https://www.php.net/), or [**P**erl](https://www.perl.org/)) | Processes server-side code and generate the dynamic content that will be sent back to the client--that is to say, a user's web browser). |

<hr />

## 2. <a name="four">Why These Four Technologies?</a>

These four technologies integrate cohesively and holistically to get the job of full-stack web development done in a low-to-no cost manner. LAMP stack development provides a logical and highly efficient pipeline:

* The *Linux* operating system provides provides a *base layer* for the integrated suite of 'LAMP' technologies. By being open-source, highly secure, customizable, and highly stable (although the extent of this is dependent upon distribution/distro), Linux is an excellent OS option for web server deployment.

* *Apache* (also open-source, like the other 'LAMP' components) delegates web data requests from clients (users' web browsers) to relevant apps (or, alternatively, it serves static data files). It integrates seamlessly with Linux, provides modular control mechanisms, and can perform even at highly scalable traffic levels.

* *MySQL*, as a Relational Database Management System (RDBMS), is used for creating, reading, updating, and deleting ('CRUD' operations) data. For 'LAMP' apps, this is web app data that needs to be organized by such constructs as content and user data. LAMP (Apache) web servers rely on MySQL to serve them the data that need to be fed to clients.

* *Server-side scripting languages*, such as Python, PHP, and Perl, generate dynamic web content by running code, interfacing with MySQL to fetch data, and then formatting the data into HyperText Markup Language (HTML) to be rendered by the client (web browser). 

<hr />

## 3. <a name="operate">How Does a LAMP Stack Operate?</a>

The operations of LAMP stacks can be generalized as five sequential steps:

1) A *user's web browser* sends out a data request for a web page that will be served by an *Apache web server*. 
2) Should this request be for a dynamic page, Apache will then send this request to a *server-side scripting language's script* (the Python, PHP, or Perl code). 
3) The server-side scripting language runs its code (and might send a request to the *MySQL database* if it needs to retrieve data from it). 
4) The server-side script puts the data and code together, to generate an *HTML page*. 
5) The *Apache server* then sends the HTML page back to the *client (user's browser)* so that it can be displayed/used.

<hr />

## <a name="meanmern">4. A Note on MEAN and MERN Stack Development</a>

For information on two other popular stacks for developing web apps, check out the [Intro to MERN and MEAN Stack Development Overview Guide](https://github.com/chaseofthejungle/intro-to-mern-and-mean-stack).

<hr />

## <a name="supplemental">5. Supplemental Resources</a>

* *[Apache HTTP Server Project Official Website](https://httpd.apache.org/)*
* *[MySQL Official Website](https://www.mysql.com/)*
* *[Intro to SQL Overview Guide](https://github.com/chaseofthejungle/intro-to-sql)*

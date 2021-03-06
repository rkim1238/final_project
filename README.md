# INST 377 final_project
# Evening 1: Tammy Dam, Tanishq Kaushik, Rachel Kim, Alicia Wang, and Robert York

Residential and Commercial Permits in PG County

We will be using the "Residential and Commercial Permits (July 2013 to Present)" dataset from PG county
(https://data.princegeorgescountymd.gov/Urban-Planning/Residential-and-Commercial-Permits-July-2013-to-Pr/weik-ttee). This 
provides a fulll list of residential and commericial permits that we will use to help new/prospective business owners find an
area in PG County that is best suited to start their specific business. This helps users find the least amount of competitors 
by cross referencing permit types and cities. 

# Heroku Link

https://pg-permits-final-project.herokuapp.com/index.html

# Target Browsers
Our application is built to be adaptable on browers and mobile devices. Bulma is compatible with recent versions of Chrome, Edge, Firefox, Opera, and Safari. So far, we have tested our application on Chrome using Windows, iOS, and Android. The current versions are listed:

* Chrome (Version 81.0.4044.129) on Windows 10 (Version 10.0.17763 Build 17763)
* Chrome (Version 81.0.4044.124) on iOS 13.3.1
* Chrome (Version 81.0.4044.117) on Android (Version 10.0)

# User Manual Link

https://github.com/TammyDam/final_project/blob/master/docs/user.md

# Developer Manual 

## Installation and Dependencies

### Bulma Installation
Bulma is a modern CSS framework based on [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes).

#### NPM

```sh
npm install bulma
```

**or**

#### Import
After installation, you can import the CSS file into your project using this snippet:

```sh
import 'bulma/css/bulma.css'
```

### Dependencies

The `npm` dependencies included in `package.json` are:

* babel-cli, babel-core, babel-node, babel-present-env for compiling ES6 JavaScript files


## Running The Application on Server
Open your terminal or command line and type in 'npm start' to run your server files

## Testing 
Go to Heroku to run the website to see the output. If it does not work then right click the website and inspect its issues.

## API


## Known Bugs

## Future Development

1. Create a mobile application
2. Solve other information problems such as:
*  The effect of the 2008-2013 recession
    * Basis of different months
    * How many permits were issued
    * What types of permits were issued
* The effect of the outgoing COVID-19 pandemic from January 2020-April 2020
    * If permit sales were effected
        * Filter by city
    * What types of permits were issued


The audience of this document is future developers who will take over your system.
They know technical terms and have general knowledge about web applications, but do not have knowledge about your system design.
You need to provide a technical document so that future developers can start setting up the application on their local machines, and keep working on the system development after you leave the team.
Your Developer Manual covers:
How to install your application and all dependencies
How to run your application on a server
How to run any tests you have written for your software
The API for your server application - all GET, POST, PUT, etc endpoints, and what they each do
A clear set of expectations around known bugs and a road-map for future development.

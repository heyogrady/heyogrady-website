Setup
=====

Here's what we did to create this site using the Gumby Framework

**Prerequisites:**
* Ruby >2.0.0
* npm

Install Compass
---------------

* Run `gem install compass`

Install Claymate
----------------

Claymate is a CLI (command-line interface) for setting up a new Gumby project.

* Run `npm install -g claymate`

**Note:**
At this point I was getting an which contained something similar to this:

```sh
No compatible version found: bower-config@'>=0.2.0 <0.3.0'
```

The solution was to install the following:

```sh
npm install -g npm@1
```

Create a new empty Gumby project
--------------------------------

* Create a new directory for our project:
  
  ```sh
  mkdir heyogrady-website
  ```

* Enter this directory

  ```sh
  cd heyogrady-website
  ```

* Install Gumby

  ```sh
  claymate install
  ```


[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Yo, man, let's learn Yeoman

![Yeoman logo](http://blog.teamtreehouse.com/wp-content/uploads/2014/01/yeoman-logo.png)

> The fastest way to get started is to use generator-generator,
> a Yeoman generator to generate a Yeoman generator.

## Objectives

By the end of this, developers should be able to:

1.   Explain what Yeoman is and why it is useful
2.   Find Yeoman generators to help kickstart new projects
3.   Use yo from the command line

## Yeoman gets you going in no time

Yeoman is a scaffolding tool for modern web apps.
Similar to the generators included in Rails, Yeoman helps you avoid writing boilerplate code by creating it for you.

The Yeoman workflow consists of three tools:

1.  Yo, the **command line tool** which is used to run generators to scaffold a new web app
2.  a **build system** (such as Gulp or Grunt) which is used build, preview and test your project
3.  a **package manager** used for dependency management. NPM and Bower are popular.

## Demo: Generating a Web App

During this demonstration I will show how to scaffold a web app using Yeoman.
If you wish use the following commands to follow along.

### Install Dependencies

```bash
npm install --global yo gulp-cli bower
```

### Install the Generator

```bash
npm install --global generator-webapp
```

Make a new directory for your web app.

Run ```yo webapp``` to scaffold your application.

Run ```gulp serve``` to preview and watch for changes

## Lab: Yeoman Generators

Explore available [Yeoman generators](http://yeoman.io/generators/) and discuss how they would be useful when
creating a new project.

## Additional Resources

-   [Yeoman Documentation](http://yeoman.io)
-   [Creating a Generator Guide](http://yeoman.io/authoring/)
    section.

## [License](LICENSE)

1.  All content is licensed under a CC­BY­NC­SA 4.0 license.
1.  All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.

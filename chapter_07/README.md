# Chapter 7
## Forms and Authentication handling in Angular 2

**Warning:** Our *Angular 2 Essentials* book, encompassing the code examples available here, is still in Alpha state and therefore the samples provided herein may be subject to change without prior notice.

## Installation

Clone the repository, move to the folder containing the source file for this chapter and install the NPM dependencies by executing the following:

```javascript
$ git clone https://github.com/deeleman/angular2-essentials.git
$ cd angular2-essentials/chapter_07
$ npm install
```
You will need TypeScript to be available globally to proceed. Please refer to the book for further instructions.

## Description

As significant as rendering data, editing data is paramount in all modern web applications. Here we will learn to retrieve the end users’ input in our Angular 2 applications by means of interactive forms that implement data validation and form-specific directives to help digest and process the information entered.

Moreover, ensuring that specific areas of your web application stay away from malicious eyes is part of the daily due diligence of any web developer nowadays. We will follow up on this chapter with the application we’ve been building up to now but will proceed to secure with username and password protection all sensible pages allowing users to publish data.

### Topics covered

We will learn how to create HTML forms wrapped inside Angular 2 components and render them with specific routes, introducing the concepts of Control objects, ControlGroup modules and the FormBuilder wrapper. This chapter will also provide deep insights on how to implement user input validation, two data-binding between input forms and rendered data and custom interaction between DOM elements based on user input.

This chapter also taps into one of the most common and sensible tasks of modern web development, so we will leverage all the knowledge obtained over the previous chapters to overview the usual steps required when protecting areas of a site such as creating login forms, exchanging login data and security tokens between mock authentication data services and stores, restricting access to pages by means of our own RouterOutlet and handling state across page views.

### Skills learned

* Leveraging the FormBuilder module to create user input forms.
* Understand the ControlGroup and Control modules and objects.
* Provide form validation with built-in and custom Angular 2 validators.
* Linking DOM items by means of Angular 2 references
* Provide two-way data-binding in user input and other DOM elements.
* Securing areas and pages of our application with password protection
* Leverage RouterOutlet to intercept additional routing handlers.
* Recap on form processing to handle user validation and authentication.
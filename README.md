# \<arduino-connection\>

![Polymer 2 badged](https://img.shields.io/badge/Polymer-2.x-green.svg)
[![Build Status](https://travis-ci.org/HAlejandro88/arduino-component.svg?branch=master)](https://travis-ci.org/HAlejandro88/arduino-component)

 ### Properties
     
    |   Properties           Value                      Description
    | ---------------|------------------|---------------------------------------------------|
    |      url       |       ""         |    define la url for request of the arduino
    |     lcd        |       ""         |    define the paragraph to write on the lcd
      
      
 ### Events
     
    |        Event                             Descriptionof event
    |-------------------|--------------------------------------------------------------------|
    |    led-change      |changes the element of the arduino selected, in this case led-red  |
    |    led-change      |changes the element of the arduino selected, in this case led-green|
    |   lcd-clicked      |print on the lcd screen what you wrote in the text field    

### Styles
     
      
    Name                   |       Type        |             Use in case
---------------------------|-------------------|---------------------------------------------------|
`  --arduino-led1-style    |       Mixin       |     change  style for led1 `                      |
`  --arduino-led2-style    |        Mixin      |     change  style for led2 `                      |
` --arduino-element-style  |       Mixin       |   change style for lcd `                          |
` --button--background-size|      var          | change style for background-size in the conteiner                                                      elemnts `                                         |


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.


# Build a loading button with Angular

## Description
Using an angular controller and directives, build a tabbed interface. Clicking on a new tab should change the contents in the viewable area.


## Objectives

### Learning Objectives

After completing this assignment, you should…

* Understand how show and hide content.
* Know how to put basic angular expressions within directives.


### Performance Objectives

After completing this assignment, you be able to effectively use

* ng-show
* ng-click

## Details

### Deliverables

* A repo containing at least:
  * `index.html`
  * `scripts/controllers.js`
  * `bower.json`

### Requirements

* No JSHint warnings or errors


## Normal Mode
Replicate the following behavior using angular.
![Example](/tabs.gif)

## Hard Mode
Modify your code so that the currently selected tab is highlighted - denoting which piece of content you are viewing.


## Notes

Hints: create two variables on your controller scope called $scope.buttonText and $scope.isLoading. Use ng-bind to bind your buttonText to the button and ng-disabled to controll whether or not the button is disabled. You can use $timeout to reset the button back to its regular state after 4 seconds.

## Additional Resources

* You can use [angular-template](https://github.com/TIY-Austin-Front-End-Engineering/angular-template) to get started.

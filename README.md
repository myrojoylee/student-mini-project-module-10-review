# Student Mini Project, Module 10 Review

## Description

- Task List

  - [x] It's done when I have created a `Component` class that takes in children, which defaults to an empty array if not provided.

  - [ ] It's done when a `render()` method is placed on the `Component` class that throws an error saying `Child class must implement render() method.`

  - [ ] It's done when a `renderInnerHTML()` method is placed on the `Component` class that loops over the children and converts any that aren't strings to strings by calling their `render()` method.

  - [ ] It's done when I have created a `Header` class that inherits from the `Component` class.

  - [ ] It's done when a `render()` method is placed on the `Header` class that returns a string of HTML following this format: `<header class="header"><h1>Todo Today</h1><p>{DATE_HERE}</p></header>`.

  - [ ] It's done when I have created a `TaskListItem` class that inherits from the `Component` class.

  - It's done when the `TaskListItem` class passes children to its parent class and sets a `priority` property.

  - It's done when a `render()` method is placed on the `TaskListItem` class and returns a string of HTML following this format: `<li class="tasks-item">{INNER_HTML}</li>`.

  - [ ] It's done when the `render()` method on the `TaskListItem` class optionally places a class name `tasks-item-priority` if the `priority` property is `true`.

  - [ ] It's done when I have tested the wildcard route by visiting any non-existent path, like `http://localhost/test`.

  - [ ] It's done when I have created a `TaskList` class that inherits from the `Component` class.

  - vIt's done when the `TaskList` class passes children to its parent class.

  - [ ] It's done when a `render()` method is placed on the `TaskList` class and returns a string of HTML following this format: `<ul class="tasks">{INNER_HTML}</ul>`.

  - [ ] It's done when I have created a testing suite for the `Component` class to verify that `render()` throws an error when called directly.

  - It's done when I have created a testing suite for the `Header` class to verify the header renders correctly with the date.

  - It's done when I have created a testing suite for the `TaskListItem` class that verifies that the list item renders correctly.

  - It's done when the `TaskListItem` class testing suite also verifies that a priority task renders correctly.

  - It's done when I have created a testing suite for the `TaskList` class that verifies the unordered list with tasks renders correctly.

  - It's done when I have modified the `createDocument()` method on `document.js` to create a new `Header` class and to add `TaskListItems` to a `TaskList` class.

  - It's done when the `return` of the `createDocument()` method is modified to include the newly created `Header`, `TaskList`, and `TaskListItems` classes.

## Installation

## Usage

## Testing

## License

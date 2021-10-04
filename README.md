# Getting started with Angular

Building a basic e-commerce site with a catalog, shopping cart, and check-out form.

## Prerequisites

To get the most out of this tutorial you should already have a basic understanding of the following.

* [HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML "Learning HTML: Guides and tutorials")
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript "JavaScript")
* [TypeScript](https://www.typescriptlang.org/ "The TypeScript language")


{@a components}
## Take a tour of the example application

You build Angular applications with components.
Components define areas of responsibility in the UI that let you reuse sets of UI functionality.

A component consists of three things:

* **A component class** that handles data and functionality.
* **An HTML template** that determines the UI.
* **Component-specific styles** that define the look and feel.

This guide demonstrates building an application with the following components.

* `<app-root>`&mdash;the first component to load and the container for the other components.
* `<app-top-bar>`&mdash;the store name and checkout button.
* `<app-product-list>`&mdash;the product list.
* `<app-product-alerts>`&mdash;a component that contains the application's alerts.

<div class="lightbox">
  <img src="https://angular.io/generated/images/guide/start/app-components.png" alt="Online store with three components">
</div>



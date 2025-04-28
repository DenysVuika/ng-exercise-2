# Angular Exercise 2

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.9.

## Tasks

### Part 1

- have a quick overview of the project structure
- start the application
- integrate [Angular Material](https://material.angular.io/) components with the project
- integrate [Material Theming](https://material.angular.io/guide/theming#using-a-pre-built-theme) for the components
- integrate the [Toolbar](https://material.angular.io/components/toolbar/overview) component to the app home page
- integrate the [Tabs](https://material.angular.io/components/tabs/overview) component that takes the main content

### Part 2

- add a new [Button](https://material.angular.io/components/button/overview) to the application toolbar, with the `Notify` caption and `Send Notification` [Tooltip](https://material.angular.io/components/tooltip/overview)
- introduce a new Angular service `NotificationService` as `src/app/services/notification.service.ts`
- provide a public method to display a simple [Snackbar](https://material.angular.io/components/snack-bar/overview) with the provided message
- inject the `NotificationService` into the main application component
- for the click handler of the `Notify` button, invoke your custom `NotificationService` to display the notification message.

### Part 3

- run application unit tests
- create a unit test for the `NotificationService` to cover the sending messages functionality

## Resources

### Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

### Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

### Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

### Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

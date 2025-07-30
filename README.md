# TasktrackerAngular

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 20.1.3. It is currently hosted through GitHub Pages for static access, and utilizes localStorage on the user's device to dynamically save and load task lists.

## How to create a list

Opening the app starts on the All Lists view. Click "Add a new list" to enter the tasklist view. You will be prompted with three potential inputs:
- "Back to all lists", which returns you to the All Lists view
- "Add a title", a text input to name your current tasklist
- A + button to add a task to the list
Fill in a title for your list and then click + to start adding tasks to your list!

## Task management

Each task has its own title and optional description field. Name the task in its title field, and then add any extra notes about the task or a list of subtasks in the description text input below.

To delete a task, press the trash can icon.

Each task can have four statuses, selectable from a dropdown on the left:
- To Do, for tasks not started yet
- In Progress, for tasks that are started but not complete
- On Hold, for tasks that cannot be started yet
- Completed, for finished tasks

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

Additionally, to automatically deploy to github pages, install [angular-cli-ghpages](https://www.npmjs.com/package/angular-cli-ghpages) via npm and then run 
```bash
ng deploy --base-href=/tasktracker_angular/
```

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

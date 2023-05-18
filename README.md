## Description

A simple TODO app, in the form of a Vue SPA.

## Run the project
To start the app, run

```bash
yarn serve
```

To run unit tests, run

```bash
yarn test:unit
```

## Running the Application Using the Docker Container

```bash
docker run -it -p 8080:80 --rm --name todo-app-1 moemad711/todo-app-34ml
```

## Details

**Main Features:**

1. Creating new tasks
2. Editing tasks
3. Marking a task as complete
4. Marking a task as not complete
5. Deleting a task

**Extra features:**

The App also incorporates a few extra features, that were on the "nice to have" side:

1. List deleted tasks (trash bucket)
2. Un-delete items from trash
3. Delete items permanently from bucket
4. Dedicated page for deleted items via Vue Router
4. Re-order tasks via Drag n Drop
5. Edit tasks
6. Persist tasks between refreshes via Local Storage





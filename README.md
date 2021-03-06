# Task Manager

This task manager is a tool that serves to list the tasks that you will be performing. This is a really useful function for the daily lives of people and companies to manage tasks over time. And that's what this tool is for.

## Setup

To execute the project, it will be necessary to install the dependencies by typing the following command in the terminal:

```bash
npm install
```

Then, create a file called **.env** and copy the contents of the file **.env.exemple**, which already exists in the project, to it. Then type the following command in the terminal:

```bash
adonis key:generate
```

Finally, type the following command in the terminal to start the server:

```bash
adonis serve
```

The system is ready to be used on the route:

[http://localhost:3333/tasks](http://localhost:3333/tasks)

## Features

The project has the common characteristics of a CRUD, namely:

* Create a new task;
* Update a task;
* Delete a task;
* List all tasks;

## License

MIT

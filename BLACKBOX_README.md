This is a basic TODO app built with HTML, CSS, and JavaScript. It allows users to add tasks, edit tasks, and delete tasks.

To run the app, clone the repository and open it in your code editor. Then, open the terminal and run the following command:

```
npm install
```

This will install the dependencies needed to run the app. Once the dependencies have been installed, run the following command to start the app:

```
npm start
```

The app will be available at http://localhost:5501.

## The HTML

The HTML for the app is very simple. It consists of a header, a main section, and a footer. The header contains the title of the app, and the main section contains the form for adding tasks, the list of tasks, and the buttons for editing and deleting tasks. The footer contains a copyright notice.

Here is the code for the HTML:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TODO App</title>
    <link rel="stylesheet" href="main.css">
</head>
<body>
    <header>
        <h1>TODO App</h1>
    </header>

    <main>
        <section class="task-list">
            <h2>Tasks</h2>

            <div id="tasks">
                <!-- <div class="task">
                    <div class="content">
                        <input 
                        type="text"
                        class="text"
                        value="My Shiny Task"
                        readonly
                        >
                    </div>
                    <div class="actions">
                        <button class="edit">Edit</button>
                        <button class="delete">Delete</button>
                    </div>
                </div> -->

            </div>

        </section>
    </main>

    <footer>
        <p>Copyright 2023 Sameer Singh</
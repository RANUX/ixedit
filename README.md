#### This is fork from https://github.com/perchouli/ixedit

ixedit
======

IxEdit is a JavaScript-based interaction design tool for the web. With IxEdit, designers can practice DOM-scripting without coding to change, add, move, or transform elements dynamically on your web pages. Especially, IxEdit must be useful to try various interactions rapidly in the prototyping phase of your web application.

Very useful for study jQuery and jQuery-UI.

### The project is compatible with those browsers.

- Firefox 12.0+
- IE8+
- Chrome 19.0.1084.46+
- Safari 6.0.3+

### Install


### Usage

- Open the `index.html` file inside of a web browser.
- if you installed python, run

After clone

```
> python server.py
```

And access `http://127.0.0.1:8000` with Chrome or Safari


### Basic operation flow

1. Click “New” button in the list view to open the edit view to make a new interaction.
2. In the action edit area, specify an event and target element(s) as the trigger of interaction.
3. In the reaction edit area, specify a command and its parameters. You can make multiple reactions for one action.
4. Click “Done” button to save the interaction you created. IxEdit Dialog switches back to the list view.

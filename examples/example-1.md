## Configure

### Properties

To customize pass an object with one or more of the following properties to `mole.config()` either programmatically or using a file named `mole.config.js`.


- #### `theme` optional
    The location of your theme data.

    **Type**: String

---

- #### `model` optional
    Can be either a `named model`, a `dir` or a `path` to a js file which exports a callback. When a dir is used it will look for files or sub directories who's name matches a named output. An array can be used to specify multiple models.

    **Type**: String

---

- #### `template`
    Can be either a named template, a dir, or a path to a js file which exports a function or template string, or a njk file which contains Nunjucks template code. When a dir is used it will look for sub directories who's name matches a named output and then look for file names matching a top level key inside data. Failing this it will look for files who's name matches a named output inside the directory. Additionally you may wish to name a file index and that will be used instead. An array can be used to specify multiple templates.

    **Type**: String, Array


---

- #### `output`
    An object with properties specifying where and how to process the output. You can specify a different `template` or `model` for each output. Create a named output by surrounding it in a key. An array can be used to specify multiple outputs.

    **Type**: Object


### Methods

- #### `mole.config()`

    Set the configuration

    **Type**: String, Object

---

- #### `mole.theme()`

    Set or update the theme data

    **Type**: String, Object

---

- #### `mole.create()`

    Create a model or template

    **Type**: Type, Name, Callback

---

- #### `mole.render()`

	Returns an array of rendered templates

---

- #### `mole.build()`

    Builds the output files and writes them to disk
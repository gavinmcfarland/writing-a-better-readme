# Documenting Code Examples

- [General Best Practices](#general-best-practices)
- [Advanced Usage of Your Project](#advanced-usage-of-your-project)

## General Best Practices

### Provide working examples

You can do this by creating an `examples` folder that contain working examples of your project in use, each with their own readmes.

### Use code snippets that work

This way users of your project can copy and paste the examples to see them working. This includes making sure code is valid and free from typos, except for code which has been shortened for brevity.

### Include contextual examples

After explaining how to use your library it's useful to provide an example, so users of your library can see it in context.

### Reference filenames

When referencing code that relates to a specific file add a comment or label to show the name of the file.

__config.js__
```js
{
    id: 2,
    name: config
}
```

### Provide context for shortened code

If the code is only a snippet of a code from a larger context, provide some explanation to help the user and help demonstrate this using an ellipsis.

```json
"scripts": {
    "start": "node index.js"
},

...

"dependencies": {
    "react": "^5.0.0",
    "postcss": "^7.0.0
}
```

### Avoid command line prompts before statements

__Don't do this__

```
$ npm install myproject
```

This makes it difficult for users to copy and paste your code.


## Advanced Usage of Your Project

People with different skill and knowlegde will likely be trying to use your project and not everyone may be familiar with the style of notation you are using.
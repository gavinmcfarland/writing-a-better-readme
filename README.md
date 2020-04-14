# Best Practices For Documenting APIs

> This is a work in progress of best practices and may be missing sections or content.

Below are some guidelines to help you better document and demonstrate your API.

- [Structing Your Documentation](#structing-your-documentation)
    - [Explaining It's Usage](#explaining-its-usage)
    - [Common Heading Names](#common-heading-names)
    <!-- - [Context and Dependencies]() -->
    - [Writing Content](#writing-content)
- [Providing Code Examples](#providing-code-examples)
- [Advanced Usage of Your Project](#advanced-usage-of-your-project)

## Structuring Your Documentation

There are some key areas you should cover in your documentation.

- A description of what your library does
- Why your library is important or different
- Installation instructions, or how to set up your library
- How to use your library or an example
- Advanced instructions or detailed documentation on how to configure your library
- If your documentation is particular big or comlex, then consider adding a table of contents, or splitting your documnentation up

### Explaining It's Usage

When explaining it's usage try to follow an example which the user can follow. If necessary use numbering or lists to show the order of which to follow the instructions.

### Common Heading Names

Below are some examples of common heading names used by other repos.

```
Getting Started, Quickstart, Usage, Example, Features,
Install, Installation, Setup, Configure
Options, API, Config, Methods, Development
```

### Writing Content

Try to keep your readme file concise and well structured. Use images when appropriate to help explain or draw attention to your documentation.

## Providing Code Examples

1. Provide real working examples where possible. You can do this by creating a folder called `examples` that contain different examples of your project being used with their own READMEs.
2. Provide code examples that work. This way users of your project can copy and paste the examples to see them working. This includes making sure code is valid and free from typos.
2. After showing how to use your library it's useful to provide an example so users of your library can see an example in context.
3. When referencing code that relates to a specific file add a comment or title to show the name of the file
    ```js
    // config.js

    {
        id: 2,
        name: config
    }
    ```
4. If the code is only a snippet of a code from a larger context, provide some explanation to help the user and help demonstrate this using an ellipsis.
    ```json
    // package.json

    "scripts": {
        "start": "node index.js"
    },

    ...

    "dependencies": {
        "react": "^5.0.0",
        "postcss": "^7.0.0
    }
    ```
5. Avoid including a command like prompt `$` before statements as this makes it difficult for users to copy and paste your code.


## Advanced Usage of Your Project

People with different skill and knowlegde will likely be trying to use your project and not everyone may be familiar with the style of notation you are using.
# Guidelines for Documenting Open Source Projects

Below are guidelines to help you better document and demonstrate your repo, project, library or framework.

- [Structing Your Documentation](#structing-your-documentation)
    - [Summarising Your Project](#describing-your-project)
    - [Explaining It's Usage](#explaining-its-usage)
    - [Describing the Installation](#describing-the-installation)
    - [Writing Good Copy](#writing-good-copy)
    - [What to Include in the Header](#what-to-inlcude-in-the-header)
    - [Common Heading Names](#common-heading-names)
- [Documenting Code Examples](#documenting-code-examples)
    - [Use Code Snippets that Work](#use-code-snippets-that-work)
    - [Provide Working Examples](#provide-working-examples)
    - [Include Contextual Examples](#include-contextual-examples)
    - [Reference Filenames](#reference-filenames)
    - [Provide Context for Shortened Code](#provide-context-for-shortened-code)
    - [Avoid Command Line Prompts](#avoid-command-line-prompts)
- [Contributing to these guidelines]()

## Structuring Your Documentation

There are key sections you should cover in your documentation, but in no particular order.

- A description of what your library does and how
- How to use your project or an example
- Installation instructions, or how to set up your project
- Why your library is important or different
- Advanced instructions on how to customize it or use it's API

If your documentation is big or comlex, then consider adding a table of contents, or splitting your documnentation up.

### Describing Your Project

Provide a brief summary of what your project does and how it does it. If it's an extension of an existing framework, like a plugin let the user know this, it will help them understand how to integrate your project into their own.

### Explaining It's Usage

When explaining it's usage try to follow an example which the user can follow. If necessary use numbering or lists to show the order of which to follow the instructions.

### Describing the Installation

Try to keep the instructions for installing or setting up your project as simple and as concise as possible. Make it easy for your users to get your project up and running. If you can, it's helpful to provide a way for them to know it's working.

### Writing Good Copy

Try to keep your readme file concise and well structured. Avoid using long sentences. Use images when appropriate to help explain or draw attention to your documentation.

### What to Include in the Header

You can include badges/shields which let users know at a glance certain information about your project. This can include, what platform it works on, what features it supports, and if it belongs to a framework.

### Common Heading Names

Below are some common heading names used by other repos.

- Usage
- Getting Started
- Quickstart
- Example
- Features
- Install
- Installation
- Setup
- Configure
- Options
- API
- Properties
- Methods
- Development
- Feedback

## Documenting Code Examples

### Use Code Snippets That Work

This way users of your project can copy and paste the examples to see them working. This includes making sure code is valid and free from typos, except for code which has been shortened for brevity.

### Provide Working Examples

You can do this by creating an `examples` folder that contain working examples of your project in use, each with their own readmes.

### Include Contextual Examples

After explaining how to use your library it's useful to provide an example, so users of your library can see it in context.

### Reference Filenames

When referencing code that relates to a specific file add a comment or label to show the name of the file.

__config.js__
```js
{
    id: 2,
    name: config
}
```

### Provide Context for Shortened Code

If the code is only a snippet of a code from a larger context, provide some explanation to help the user and help demonstrate code has been shortened using an ellipsis.

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

### Avoid Command Line Prompts

__Don't do this__

```
$ npm install myproject
```

This makes it difficult for users to copy and paste your code.

## Contributing to These Guidelines

I encourage contributions to these guidelines. If you feel something is incorrect, missing or could be better; please submit an issue with your comments.
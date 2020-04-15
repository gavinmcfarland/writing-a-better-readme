
- Different types of notations and what they mean
- Differences between ES5 and ES6 syntax
- Common types of projects, ie plugins, instances, libraries, config driven
- Common installation methods for repos, installing locally, installing globally, using a bundler.


### Optional Values

The following notion is used to show that a value is optional by placing it inside square brackets `[]`. Often contained inside the square brackets is a comma deliminating the next value in the array `[, length]`.

```
[width[, length]]
```

### Placeholders
Placeholders are used commonly to show an example of when the user should replace the placeholder with a valuee of their own. They often come in the form of `{}`, `{{}}` or `<>` and sometimes `[]` or `$`. These should be careful not be confused with template placeholders where the value will be replaced by the frameworks or templating engine.

### CSS specification

CSS uses a notation to explain the specification. https://www.w3.org/TR/css-values-4/#comb-any

- `[]` Brackets ([ ]) are for grouping.
- `|` A bar (|) separates two or more alternatives: exactly one of them must occur.
- `||` A double bar (||) separates two or more options: one or more of them must occur, in any order.
- `* ` An asterisk (*) indicates that the preceding type, word, or group occurs zero or more times.
- `+` A plus (+) indicates that the preceding type, word, or group occurs one or more times.
- `?` A question mark (?) indicates that the preceding type, word, or group is optional (occurs zero or one times).
- `{1}` A single number in curly braces ({A}) indicates that the preceding type, word, or group occurs A times.
- `{1,10}` A comma-separated pair of numbers in curly braces ({A,B}) indicates that the preceding type, word, or group occurs at least A and at most B times. The B may be omitted ({A,}) to indicate that there must be at least A repetitions, with no upper bound on the number of repetitions.
- `#` A hash mark (#) indicates that the preceding type, word, or group occurs one or more times, separated by comma tokens (which may optionally be surrounded by white space and/or comments). It may optionally be followed by the curly brace forms, above, to indicate precisely how many times the repetition occurs, like <length>#{1,4}.
- `!` An exclamation point (!) after a group indicates that the group is required and must produce at least one value; even if the grammar of the items within the group would otherwise allow the entire contents to be omitted, at least one component value must not be omitted.


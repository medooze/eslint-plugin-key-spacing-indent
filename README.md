# eslint-plugin-key-spacing-indent

key-spacing-indent

## Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-key-spacing-indent`:

```sh
npm install eslint-plugin-key-spacing-indent --save-dev
```

## Usage

Add `key-spacing-indent` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "key-spacing-indent"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "key-spacing-indent/rule-name": 2
    }
}
```

## Rules

<!-- begin auto-generated rules list -->

🔧 Automatically fixable by the [`--fix` CLI option](https://eslint.org/docs/user-guide/command-line-interface#--fix).

| Name                                                   | Description                                                                     | 🔧 |
| :----------------------------------------------------- | :------------------------------------------------------------------------------ | :- |
| [key-spacing-indent](docs/rules/key-spacing-indent.md) | Enforce consistent spacing between keys and values in object literal properties | 🔧 |

<!-- end auto-generated rules list -->



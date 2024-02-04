# textlint-rule-front-matter



## Install

Install with [npm](https://www.npmjs.com/):

    npm install textlint-rule-front-matter

## Usage

Via `.textlintrc.json`(Recommended)

```json
{
    "rules": {
        "front-matter": true
    }
}
```

Via CLI

```
textlint --rule front-matter README.md
```

### Build

Builds source codes for publish to the `lib` folder.
You can write ES2015+ source codes in `src/` folder.

    npm run build

### Tests

Run test code in `test` folder.
Test textlint rule by [textlint-tester](https://github.com/textlint/textlint-tester).

    npm test

## License

MIT © 

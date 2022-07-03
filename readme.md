# alfred-polyglot [![npm](https://img.shields.io/npm/v/alfred-polyglot.svg)](https://npmjs.org/package/alfred-polyglot)

> Translate text using Google Translate in Alfred

![Preview gif](media/preview.gif)

[Alfred forum thread](https://www.alfredforum.com/topic/11235-polyglot-yet-another-google-translate-workflow/)

## Install

```bash
npm install --global alfred-polyglot
```

*Requires [Node.js](https://nodejs.org) 7.6+ and the Alfred [Powerpack](https://www.alfredapp.com/powerpack/).*

## Setup

1. Set the default language text will get translated to if `to` parameter is not specified.

    ```plain
    trans !set default-language (language)
    ```

1. Remove the default translate workflow. Navigate to Alfred Preferences → Features → Web Search and search for “translate”, and unset the tickbox under “Enabled”.

## Usage

```plain
trans (text) [from (language)] [to (language)]
```

The output will be the translated form of `text`. Both `from` and `to` parameters are optional, and can be used anywhere in input.

## Examples

![1](media/1.png)

![2](media/2.png)

![3](media/3.png)

![4](media/4.png)

## License

MIT © [nikersify](https://nikerino.com)

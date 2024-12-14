# tampermonkey-i18n

This repo contains Tampermonkey's locale files

## get it

You can get Tampermonkey here: http://tampermonkey.net

## contribute

If you want to contribute, then this [userscript](https://gist.github.com/derjanb/5592ff3b7cdc4feabba5/raw/tampermonkey_translation_support.user.js) might help you:

After installing the script, you will see a button <kbd>Adjust to English translation</kbd> at the button bar of each `message.json` file. After clicking this button, the page will be replaced by the current locale file, plus all missing translations. Missing translations will be wrapped by angle bracket like this:

```json
  "Dont_ask_again": {
     "message": ">>>Don't ask again<<<"
  },
```

After translating the missing content, you can either create a pull request or just send me the translation to kontakt at tampermonkey.net


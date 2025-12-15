vim-cheat-sheet
===============

Yet another vim cheat sheet.

[http://vim.rtorr.com/](http://vim.rtorr.com/)

[:heart: Sponsor](https://github.com/sponsors/rtorr)

## Set up for development

1. Start app.
    ```sh
    npm ci
    npm start
    ```
2. Open http://localhost:3000/ in browser.
3. Edit [sheet.hbs](/views/partials/sheet.hbs) as desired (e.g. add new commands).
4. Reload page in browser (<kbd>Ctrl+r</kbd>) to generate the locales entries in English [en_us.json](/locales/en_us.json).
5. Stop the app (optional).
6. Describe the added commands in English [en_us.json](/locales/en_us.json) and move them to the corresponding position, equally as in [sheet.hbs](/views/partials/sheet.hbs).
7. Run `node postinstall.js` to copy the English entries to all other locales.
8. Translate all languages you know.
9. Commit.

CheatSheets
1.Bash-https://devhints.io/bash
2.Regular-https://www.gnu.org/software/sed/manual/html_node/sed-regular-expressions.html#sed-regular-expressions
3.SED-https://quickref.me/sed.html
4.SED2-https://gist.github.com/ssstonebraker/6140154
5.AWK-https://quickref.me/awk.html

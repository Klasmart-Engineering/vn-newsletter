#HOW TO RUN PROJECT

cd /tools
- run `npm install`
- run `grunt dev` to start
- run `grunt build` to build


#HOW TO ADD A MODULE

Use this command and update data-attribute

`<!-- @import partials/module_name.html data={"attribute_name": "attribute_content"} -->`

#HOW TO CREATE A NEWSLETTER

Create a new file with this format -> `YY/MM` + `lang` + `.html`

Example: `202106-vi.html`

Add modules that you need and `grunt build` to use it.
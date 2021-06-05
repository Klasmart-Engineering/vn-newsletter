# How to run

Install `grunt`

```
$ npm install -g grunt-cli
```

Install project

```
$ npm install
$ grunt dev # to start
$ grunt build # to build
```

# How to add a module

Use this command and update data-attribute

```
<!-- @import partials/module_name.html data={"attribute_name": "attribute_content"} -->
```

# How to create a newsletter

Create a new file with this format -> `YY/MM` + `lang` + `.html`

Example: `202106-vi.html`

Add modules that you need and `grunt build` to use it.

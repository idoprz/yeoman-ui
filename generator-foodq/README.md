# Sample Yeoman Generator for Yowiz
[Yowiz](https://github.wdf.sap.corp/i034929/yowiz) is a graphical user interface for running Yeoman generators. It runs as a [Visual Studio Code extension](https://code.visualstudio.com/api), or as a standalone web application for *development* purposes.

This repo contains a sample Yeoman generator that includes different Yeoman capabilities, including different Inquirer [prompt types](https://github.com/SBoudrias/Inquirer.js/blob/master/README.md#prompt-types), [question properties](https://github.com/SBoudrias/Inquirer.js/blob/master/README.md#question).

Specifically, it includes dynamic questions (`message`, `when()`, `validate()`, etc.). It also includes a sub-generator, prompts with multiple questions and metadata for Yowiz (`getPrompts()`).

## Running Locally
In the terminal type:
```sh
# install yeoman
npm install -g yo
# install dependencies of this generator
npm install
# make this generator available locally
npm link
# run this generator
yo foodq
```

# Running in Yowiz
See the [Yowiz readme](https://github.wdf.sap.corp/i034929/yowiz/blob/master/ext/README.md).

# Original extension
This extension has been forked from [vladeck's TSLint extension](https://github.com/vladeck/TSLint).
Only the version for VS 2017 has been kept.

# What is it?

Visual Studio 2017 extension for linting **Typescript** files using `tslint`.

![TSLint](TSLint/Resources/preview.png)

# How does it work?

When `.ts` is opened or saved, locally installed `tslint` is run in the background and
code in the editor is underlined (marked) based on the `tslint` findings. Hovering over the underline
gives additional info in the form of a tooltip and warnings and errors are listed in the **Error List**.

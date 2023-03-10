<div align="center">
  <h1 align="center">Console Buddy — VSCode Extension (Snippets)</h1>
  <p align="center">
    ✨ A Snippet Extension that provides a collection of <a href="https://developer.mozilla.org/en-US/docs/Web/API/console">Web Console API</a> snippets that allows you to quickly generated logging preference!
  </p>
</div>

<p align="center">    
    <img src="https://img.shields.io/github/package-json/v/shiftEscape/console-buddy" />
    <img src="https://img.shields.io/github/license/shiftEscape/console-buddy" />
</p>

## Usage Demo

![demo-console-buddy](https://user-images.githubusercontent.com/2888535/218301804-27619fdf-07c6-41d4-be1f-112a9c6be538.gif)

## List of Snippet Prefixes

Below is a list of all available snippets and the triggers of each one. The (`→`) means the `TAB` key.

| Trigger  | Resulting Snippet — Description                                                                                                                                                |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `!cl→`   | `` console.log(`Check your log here`); `` — Plain text logging preference<br/><br/>Options: (`log`, `error`, `info`, `warn`, `table`, `count`, `countReset`)                   |
| `!clp→`  | `` console.log(`LOG >>>`, var_name); ``<br/>String prefix logging preference                                                                                                   |
| `!clv→`  | `console.log(var_name);`<br/>Variable logging preference                                                                                                                       |
| `!clo→`  | `console.log({ var_name });`<br/>Object format logging preference                                                                                                              |
| `!cltm→` | `console.time(); ` or `console.timeEnd();`<br/>A timer you can use to track how long an operation takes                                                                        |
| `!cltr→` | `console.trace();`<br/>Outputs a stack trace into console                                                                                                                      |
| `!clg→`  | `console.group();` or `console.groupCollapsed();`<br/>Creates a new inline group in the console, causing any subsequent console messages to be indented by an additional level |
| `!cla→`  | `console.assert();`<br/>Writes an error message to the console if the assertion is false. If the assertion is true, nothing happens                                            |
| `!cld→`  | `console.dir();`<br/>Displays an interactive list of the properties of the specified JavaScript object                                                                         |

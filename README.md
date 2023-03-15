<h1>Go Google Translate API🌎</h1>
<p>This Go project allows users to translate text from a source language to a target language using the Google Translate API.</p>
<h3>How it works🛠️</h3>
The project uses the Google Translate API to translate text. The user can provide the source language, target language, and the desired text either as variables or as "flags". The project accepts the flags/variables from the user and then parses them using `main.go`. If there are no flags sent by the user, an error message will be shown, and the terminal will display the default options on how to interact with the tool.

If there are flags/variables passed by the user, they will be sent to `cli.go` which will make a request to the Google Translate API with the provided data. The Google Translate API will process the data (nested data) and return the translated text as output.

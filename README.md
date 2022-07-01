In this project we are taking the source language, target language and the desired text sending them as variables or as "flags"
to the Google Translate API getting back the output/translated text.

How it's done :

Main.go accepts the flags from the user and then parses them.
If there are no flags sent by the user an error will be shown and the terminal will show the defaults on how to interact with the tool.
If there are flags/variables passed by the user they will be sent to cli.go which will make a request to the Google Translate API with the data.
Google Translate gets the data, processes it(nested data) and sends out the output.

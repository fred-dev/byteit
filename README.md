# byteit

openFrameworks and web code for *Byte Me!* (2019), an interactive classroom theatre show about online privacy by Maas theater en dans and Wat We Doen ([maastd.nl](https://www.maastd.nl/nl/agenda/byte-me/)). It played 103 times between February and May 2019.

A server app shows questions to the audience and the phones/browsers in the room poll it for the current question; the operator switches questions with the number keys. Originally written by [dickreckard](https://github.com/dickreckard/byteit); this is a fork.

## Notes


* proposed JSON formats in datastructure.json

* currently working by calling the get-text method every second, and changing question displayed based on the response from the server.

* everything used in the client side is in the end of the html page for now, later will be moved in a js. 

* json file of the questions loaded from /data/js/questions.json.

* in the server window, pressing '1' changes to the first question, '2' the second, etc.


## Build

Addons: `ofxHTTP`, `ofxJSONRPC`, `ofxIO`, `ofxMediaType`, `ofxNetworkUtils`, `ofxSSLManager`, `ofxPoco` (or [ofxPocoHeaders](https://github.com/fred-dev/ofxPocoHeaders)). Generate the project with projectGenerator.

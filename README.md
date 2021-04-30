# AHS
AHS D3 Implementation

1) To create a Tableau Extension, start by cloning a sample that ressembles your use case the most from : https://github.com/tableau/js-api-samples 

2) With node on your computer, use npm to install "connect" and "serve-static"

3) In .TREX file change url to http://localhost:8080/
4) start server: node server.js

5) Launch Tableau in debug mode with cmd: "C:\Program Files\Tableau\Tableau 2020.4\bin\tableau.exe" --remote-debugging-port=8696
Note that 2020.4 must be replaced with desired version

6) To get a log of your extension, open chrome, and view: http://localhost:8696/

7) Getting data from Tableau Workbook: 
Option 1: https://tableau.github.io/extensions-api/docs/trex_getdata.html “Get Data from the Dashboard”
Option 2: https://tableau.github.io/extensions-api/docs/trex_getdata.html “Get Data from a Worksheet”

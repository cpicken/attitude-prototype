# attitude-prototype

This prototype uses the three.js library created mrdoob.

Link to three.js github repo: https://github.com/mrdoob/three.js


Link to three.js website: https://threejs.org/


#To run:

1. Download the files into a single folder
2. Run "python -m SimpleHTTPServer" in command line from the folder that contains the files
3. Open a browser and navigate to localhost:8000 
4. Click on "prototype.html" to run the prototype


####Note: it isn't required to use the command "python -m SimpleHTTPServer". All that is required is to run a webserver.

####To shutdown the server if running the "python -m SimpleHTTPServer" command
1. From the terminal running the server, press "ctrl + z"
2. Enter "ps -fA | grep python"
3. Enter "kill <proc_id>" where <proc_id> is the id of the process running the python -m SimpleHTTPServer command
4. Enter "fg"

This probably isn't the best/cleanest way to close the server, but it works.


# Pasteboard
Pasteboard is my redesigned and renamed update to PasteShack, a web app for easy image uploading. The live version is available at [http://pasteboard.co](http://pasteboard.co), and a development version that's running the code
from the dev branch is up at [http://dev.pasteboard.co](http://dev.pasteboard.co).

MIT Licensed (http://www.opensource.org/licenses/mit-license.php)   
Copyright 2012, Joel Besada

## Running Locally
__Step 1:__ Install [Node](http://nodejs.org/) and [Node Package Manager](https://npmjs.org/).   
__Step 2:__ Run the following commands in the terminal   
``` 
git clone https://github.com/JoelBesada/pasteboard.git   
cd pasteboard
git checkout dev
npm install
./run_local
```
__Step 3 (Optional):__ Edit the example files in the _/auth_ folder with your credentials and rename them according to
the instructions inside the files. You can still run the app without doing this, but certain functions will be missing.

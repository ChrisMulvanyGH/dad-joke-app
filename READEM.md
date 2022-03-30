

1. Testing Instructions
-----------------------

 - Create your project directory (root directory)
 - Within the project directory create two more directories:
	- src
	- dist
 - In the 'src' directory create a file called 'index.js' and have a simple console.log(123);
 - In the 'dist' directory create a file called 'index.html' and link to the above '../src/index.js' file
 - Click on 'Go Live' in Visual Code, press f12 in the browser and make sure you can see '123' in the browser console.
 - This means that your site and temporary server are working correctly.

2. Setup Dad Jokes Project
--------------------------

 - In the terminal type 'npm init -y'  This creates the default 'package.json' file.
 - In the terminal type 'npm i -D webpack webpack-cli'  Installs webpack and the webpack-cli also saves dependencies in 'package.json'
 - In the 'package.json' file under "scripts" delete the '"test": "echo \"Error: no test specified\" && exit 1"' line.
 - Instead of the above tests line add this line: '"build": "webpack --mode production"'.
 - In the terminal type 'npm run build'

The basic structure of the project is built.  You can download the files for this project at: https://github.com/bradtraversy/webpack-starter


3. Get Working On Webpack
-------------------------

 - In the root folder create a file named: 'webpack.config.js'.
 - This is going to be built using the 'Common.js' syntax.
 - Follow the video to input the code or copy from the Github repository
 - In the 'package.json' file make sure to remove '--mode production' as the mode will be set within the 'webpack.config.js' file.

Resources
---------
 - Video: https://www.youtube.com/watch?v=IZGNcSuwBZs
 - Github Repository: https://github.com/bradtraversy/webpack-starter
 





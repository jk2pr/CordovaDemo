This is a Simple Cordova Application to shows you how to create a JS/HTML Cordova application and deploy them to 
various native mobile platforms using the cordova command-line interface (CLI). For detailed reference on Cordova command-line,

Cordova command-line tool is distributed as an npm package.

Befor going ahead, Please make sure you install sdk, gradle and jdk and set path for thease in Environment variable of your system, so cordva can find easily. Now I am skipping steps to download sdk, gradle and jdk.

To install the cordova command-line tool, follow these steps:
1. Download and install Node.js. On installation you should be able to invoke node and npm on your command line.
2. Install the cordova module using npm utility of Node.js. The cordova module will automatically be downloaded by the npm utility.
on Windows platform your can use below commmand 

        C:\>npm install -g cordova
      
Go to the directory where you maintain your source code, and create a cordova project:
3. Once cordova install sucessfully you can create a new cordova application go to cordova folder and create new cordova project
   
         cordova create hello com.jk.hello HelloWorld
   
   
   This will creates the required directory structure for your cordova app. By default, the cordova create script generates a skeletal web-based application whose home page is the project's www/index.html file.

4. Now go to project folder and add android platform like this

         cordova platform add android
    
5. Once sucessfully added android platform you can build the project by using below command

          cordova build
    
6. SDKs for mobile platforms often come bundled with emulators that execute a device image, so that you can launch the app from the home screen and see how it interacts with many platform features. Run a command such as the following to rebuild the app and view it within a specific platform's emulator:
  
         cordova emulate android
    
  Alernativly if you have android device connected you can run directly through command 
  
      cordova run android
      
      

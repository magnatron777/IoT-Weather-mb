# Weather Station by Magnus Bell

## an IoT project

![Yellow-Umbrella](public/assets/yellow-umbrella.png)

### Development Roadmap

- [x] Setup repos - GitHub
- [x] setup ESP32 - Arduino IDE
- [x] Install dependencies - aREST.h and DHT.h 
- [x] Test ESP32 - get json data via wifi
- [x] Initialize Node.js environment
- [x] setup server.js with express
- [ ] set index route and views
- [ ] link ESP32 to Node app with fetch

### Initializing a Node.js Environment

Photo of esp 32:

![image000000](https://github.com/magnatron777/IoT-Weather-mb/assets/140573452/75a327c7-421d-4802-b3ac-2df8925a45c9)

The parts of my esp32 that I am using are the temperature sensor, 3 colour wires, and the cpu board.
IoT relates to my project in the modern way of how simple devices like a weather sensor can help everbody around the world. Aurdino firmware is amazing for making helpful IoT creations like mine as it has easy access and is simple to use. To install the audino firmware you have to download the app from the web and start it from your desktop, Vscode is also used and is also downloaded from the web. To setup the board and code there is lots of good tutorials online that can give you a good idea. 

Resources used: 
Vscode
Arduino
Esp32
Temperature sensor
CPU
Wires

My serial port number was: 6900

1. Ensure that Node.js and NPM are installed on your system:
    > node --version

    > npm --version

2. In terminal, inside the project directory:
    > npm init -y

3. This will add a package.json file

4. Install dependencies
    > npm install express ejs express-ejs-layouts

5. Install development dependencies
    > npm install --save-dev dotenv nodemon


### Initializing a Node.js Environment

1. Ensure that Node.js and NPM are installed on your system:
    > node --version

    > npm --version

2. In terminal, inside the project directory:
    > npm init -y

3. This will add a package.json file

4. Install dependencies
    > npm install express ejs express-ejs-layouts

5. Install development dependencies
    > npm install --save-dev dotenv nodemon

### Worklog and Commits

Date | Commit Message | Version
:-----|:----------------:|:--------:
25.08.23 | initial setup | 0.1.0

### References

- [Web Page Layouts](https://www.youtube.com/watch?v=3C_22eBWpjg)
- [JS Native Fetch](https://www.youtube.com/watch?v=MBqS1kYzwTc)


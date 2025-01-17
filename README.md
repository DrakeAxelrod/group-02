# group-02

This is an official labour of love! We, the development team, hope you get to enjoy just how flexible and compatible this library is! With the information provided in this file, you should be able to utilize the library and software to its full potential, or push it beyond! Good luck, and thanks for checking it out!

Here is a link to an introduction video for the system [Group 2 Demo Video](https://www.youtube.com/watch?v=ILusqXsdHHQ&ab_channel=DrakeAxelrod).

## Contents
- [Description](#description)
- [Justification](#justification)
- [Resources](#resources-used)
- [Developers "get started" guide](#Developers-get-started-guide)
- [User get started guide](#User-get-started-guide)
- [User Manual](#user-manual)
- [Development Team](#development-team)
- [Special Thanks](#special-thanks)

## Description
Smartbil by SaucyCorp is more than just a car. It's an experience. 

Smartbil Can be controlled in multiple ways, which leads to a higher degree of accessibility. As of the latest release, the car can be controlled by: 
- Keyboard
- Joystick
- Discord bot

Smartbil is a multi-tiered system with both an emulator and a website. The emulator is developed by students from the University of Gothenburg.
The website works by launching a local server and a javascript/react page. It proceeds to wait for a connection from the emulator, and then proceeds to create a new camera within the emulator, in first person view, and proceeds to stream the new camera to the website.

Smartbil is extremely flexible, and currently hosts 3 stock maps. To read how to create your own maps, or download pre-made maps created by other users, please refer to (INSERT LINK WHEN OTHER BRANCH IS LINKED).

For further information, please refer to the [wiki](https://github.com/DIT112-V21/group-02/wiki).

## Justification
This project is primarily used as a business tool to display the capabilities and limitations of the Smartcar library, this can also be used to showcase the capabilities of the emulator and the software behind it. It also showcases how the software, library and emulator can be accessed and controlled using external environments.
It also demonstrates the usage of the sensors, primary to the development of smarter cars and automatic driving services.

There is an element of fun and games within the Smartbil program, however. Featuring 3 maps upon release. These map choices tests the library in three different and unique scenarios, which will hopefully lead to the development of a more flexible, reliable library. This development process also explores how flexible and compatible the library really is, leading to a better development of the library itself by placing it in realistic practical scenarios instead of an isolated bubble.

## Development Process

This project was developed with an agile development process, which means that the team used multiple development techniques such as:
- Team was dealt up into smaller, more cohesive teams with specific issues and areas.
- Continually developing solutions to problems and improving upon solutions already developed beforehand.
- Continually improving and creating new features.
- Flexibility and adaptability within the development process.

The SMCE Godot emulator is created by The University of Gothenburg using the C# programming language. For more information on and documentation about the emulator, kindly refer to [the emulator's GitHub repo](https://github.com/ItJustWorksTM/smce-gd "SMCE GitHub page").

The maps are created using models created by the development team and obtained from various websites. Kindly check the resources used page for licensing and referrals to used models.

The functionalities and features present within the software were programming using various programming languages, but primarily Gdscipt, C# and python.

The website is developed using both Javascript and react languages.

## Resources Used
- [SMCE](https://github.com/ItJustWorksTM/smce-gd "SMCE github page")
- [Arduino IDE](https://www.arduino.cc/en/software "Arduino")
- [Android development platform](https://developer.android.com/studio "Android studio homepage")
- [Python](https://www.python.org/ "Python home page")
- [React]()
- [Smartcar Library](https://www.arduinolibraries.info/libraries/smartcar-shield "Smartcar Library")
- [Godot Engine](https://godotengine.org/ "Godot main page")
- [Blender](https://www.blender.org/ "Blender")
- [Road models: City map](https://sketchfab.com/3d-models/low-poly-modular-roads-free-asset-pack-d202f189bd5e46bb984eaa25398e200f)

## Developers get started guide
To start off with make sure you have the resources needed to work with this. For the resources used please refer to the "Resources used" section.

Firstly make sure you go and install the latest version of SMCE at [smce_gd](https://github.com/ItJustWorksTM/smce-gd) and clone the repository [group-2](https://github.com/DIT112-V21/group-02) and open the project with an IDE of your choice. 
For information on how to install the SMCE refer to: https://github.com/ItJustWorksTM/smce-gd/wiki#setup-with-prebuilts.

In order to run the website you will need [Node.js](https://nodejs.org/en/). Once you have installed [Node.js](https://nodejs.org/en/) to get started you will need to run "npm install" from the smartcar-frontend dir, in addition to running npm install from the server dir. Once you have installed the appropriate node packages in order to start the website, and the backend you will need to run "npm start" in both server, and smartcar_frontend. These two portions of the project are written in javascript via the react framework.

If you want to tinker with the python code you will need to install python 3.7.7, and pipenv. You will then need to create a virutal environment for the python portion of the code. Once you have the necessary packages installed from the piplock file you can run main from the console by typing "python main.py" from the python directory. If you want to work on the discord bot specifically you will need to create a discord developer account and get a token so that you can interact with the discord API.

Finally if you are interested in working on the godot side of the project, you will need to install [godot](https://godotengine.org/) and you will need to fork the [smce_gd](https://github.com/ItJustWorksTM/smce-gd) repository or download the zip file from the github repository page.
It is recommended that you create a new folder inside of the [smce_gd] project, that you downloaded via the zip file or forked from the repository. This folder is where you can keep the [group-2](https://github.com/DIT112-V21/group-02) projects mods seperate from the rest of the [smce_gd](https://github.com/ItJustWorksTM/smce-gd) project. 
    For information on how to create a mod please refer to : https://github.com/ItJustWorksTM/smce-gd/wiki/Modding.
The reason that you need to put the mods inside of the [smce_gd](https://github.com/ItJustWorksTM/smce-gd) project, is because some of the code within the mods expects to modify or interact with code that is in [smce_gd] once you package the mod for use with smce_gd then it becomes self sustained within the parameters of the [smce_gd] mods capabilities.
The resources used for the maps and and some of the cars are not included in the [group-2](https://github.com/DIT112-V21/group-02) for space purposes but all of the logic and code is, therefore you will have to find and/or create your own models. 

## User get started guide
Thank you for your interest in our project. To be able to try it out there are a few things you need to install and set up.

First of all you need to install the SMCE from [SMCE](https://github.com/ItJustWorksTM/smce-gd) 
Follow the instructions on the github page. 

To clone the project use the guide in the following link [Cloning a repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository).


If you installed the SMCE correctly, wou would find a godot folder in your %appdata% directory. Godot\app_userdata\SMCE\mods here you will paste in the mods from the project.

From the root folder go to group-02\godot-resources\mods in these folders you will find pck files. Copy them and paste them within the mods folder in SMCE.

From your node terminal navigate to group-02\smartcar_frontend.
If this is your first start up type in npm install followed py npm start.

## Using 
First you have to go to the website type in your name and submit


Then you are in the main menu:
Here you have some options
- Race
- Practice
- Monster Run
- Leaderboard
- Race Times

Choose the race option for a race against 3 bots, "Practice" to drive around the city map and "Monster Run" to play the chasing map.
Lets go to race that's why we	are here right?
So in the smce you choose the map you want to use in the world.  There will be the default playground, Race Against The Machines, MonsterMap and city map.
In the emulator, you should select the map you want to play. It should be the same as the button you clicked, to avoid any misunderstandings between the emulator and website.

Have you made your choice?

Awesome! 

Now you can enjoy the race from the website. control the car with w, a, s, d or the arrow keys.
Good luck!

If there is any further questions about how you use the system, please read the user manual.


## User Manual
__Welcome to the SmartBil system!__

Our goal is to bring you a fun and engaging racing experience, where you can compete with other people in a time where meeting in person is compromised. Along with this, why not put your own skill to the test and improve it? 
Before all that fun though, here’s a guide on how to get started and how to get the most out of our app! 
To start:

1. Start smce and compile sketch 
2. cd smartcar_frontend npm start

After inputting your cool username and hitting the start button you’re greeted with this page.

![Main Menu](/images/menu.PNG)

As you can see in the menu, the smartbil features 3 different game modes. So let’s go over them briefly:
 
__Racing map__ - Bring out the competitive side of yourself! In a time-trial manner race against bot cars and get the best possible time!

![Race Map](/images/racemap.PNG)

__Practice map__ - Perfect to get the hang of the controls in an environment that lets you roam freely. Enjoy the open city-scape and get good!

Please note that the practice map is not included in the main download, and can be downloaded for this [link](https://drive.google.com/file/d/1PTJmyR1Mk6qqpBGV2MGduzahe1sYhC9O/view?usp=sharing).

![Practice Map](/images/citymap.PNG)

__Monster map__ - For all you horror game fans! We bring you a hair-raising adventure through a dark dungeon with a monster chasing you. Try to survive and drive away for as long as possible before your health has depleted and the monster wins!

![Horror Map](/images/horrormap.PNG)

Now let’s go over the controls for the car:

__Joystick__ - The app features a joystick for that authentic gaming feel, and this is featured both on mobile and desktop but will offer a better experience on mobile with a touch-screen. Just simply point the joystick in the direction you want to go and the car will follow.

__Keyboard__ - You can also choose to control the car with the arrow keys as well as WASD if you would like, this is recommended for desktop usage. 

__Discord__ - The app also features controlling of the car via a Discord bot! This does require some setting up though, here’s how:

1. Create a developer discord account and generate a token (this token will allow interaction with Discord API which is needed to invite to discord)
2. Add the token to the Discord python code as environment variable
3. Run script for main Discord bot
4. Invite the bot to a server (this is obtained from the aforementioned developer guide)
5. Type .help to see all the commands for running.

Next up we have different _difficulties_ to choose from, here’s what they all mean:

__Easy__ - Drive around with boosts on full power and on full speed

__Medium__ - Boosts have less power and is slightly slower than easy

__Hard__ - Boosts have been completely taken away and drive is slower

__BossMode__ - No boosts and slower

__Extreme__ - Once again, drive slower. Now boosts send you backwards, meaning it takes some skill to avoid them in order to get a good time.

To change difficulty, go to the main menu and click the dropdown and simply choose the difficulty you want, then choose a map.

Next up we have the _leaderboard_, this is where you can compare your times recorded in the different maps with your friends. Try to make it to the top! (and then gain bragging rights amongst your friends).

![Leaderboard](/images/leaderboard.PNG)
 
You can also view all your own recorded times in the separate _Race Times_ page.

![Times](/images/times.PNG)

You can anytime just go backwards in your browser to go back to the home screen.

Thank you again for choosing our smartbil system!

## Software Architecture

![Software Architecture](https://github.com/DIT112-V21/group-02/blob/master/VroomArchitecture.png)

## Development team
Upon meeting any problems/bugs, kindly contact any one of us on these emails here.

- Jonatan Andersson                 gusganlgjo@student.gu.se
- Drake Joseph Emanuel Axelrod      gusaxedr@student.gu.se
- Vernita Gouws                     gusgouve@student.gu.se
- Mohammad Eyass Haj                gushajmo@student.gu.se
- Axel Lindmark                     guslindmax@student.gu.se
- Klara Svensson                    gussvekla@student.gu.se

## Special thanks
Special thanks go to:
- All the hardworking people at GU and Chalmers that make this whole program possible!
- GitHub for streamlining project organization
- Everyone on Sketchfab for inspiration and actual models!
- You!


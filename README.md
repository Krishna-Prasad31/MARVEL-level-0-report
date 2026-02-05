

# Task 2: API
API(Application Programming interface) , API is a set of rules that governs the communication of frontend and backend in a website.For this task i made a **Weather Application**.Here the user gets an input component where they can enter a city name *for example: Bangalore*, when the user clicks enter, the webiste sends a request to the **OpenWeather** server and communicates with the server where it obatins realtime data about the weather and sends it back to the website in a json format. The json file which contains the data is then displayed Using *DOM Manipulation* and then displayed on the website.
For this website I used HTML, CSS and JavaScript
![website](https://i.postimg.cc/j2sR6WgN/image.png)
[code](https://github.com/Krishna-Prasad31/weather-app)

# Task 3: Working with GitHub
As part of this task, I explored the given GitHub repository to understand its structure, commits, issues, pull requests, and GitHub Actions workflow. I identified a logical error in the add function of the Python code, corrected it in my fork, and committed the changes. I reviewed the existing GitHub Actions configuration and observed that the workflow is triggered on pull request events.I created a new branch, made a minimal valid change, and opened a pull request to demonstrate the contribution workflow. This pull request successfully triggered GitHub Actions, thereby completing the task and providing hands-on experience with collaborative development and CI workflows on GitHub.
![website](https://i.postimg.cc/52mn7dQv/Screenshot-(438).png)
![website](https://i.postimg.cc/yNbhtV1J/Screenshot-(439).png)



# Task 4: Get familiar with the command line on ubuntu
To complete this task, I used **WSL (Windows Subsystem for Linux)** to run Linux commands in a Windows environment. Since I had prior experience using *Windows PowerShell*, the command-line interface was not unfamiliar to me; however, the commands themselves were different. Through this task, I learned several basic Linux commands that are commonly used, such as `mkdir`, `cd`, `touch`, `cat`, and `chmod`.

## The subtasks were:
- Create a folder named test.
- cd into that folder.
- Create a blank file without using any text editor.
- create 2600 folders in this folder where each folder is named like . For example, M90 or B56.
- concatenate two text files containing any random text and display them on the terminal.

| Task | Command |
|------|---------|
| Create folder | `mkdir test`|
| Change directory | `cd test` |
| Create Blank File | `touch empty` |
| Create n folders | `for i in {1....2600}; do mkdir M$i; done`|
| Concatenate files | `cat file1.txt file2.txt` |

![website](https://i.postimg.cc/MKfLDpSj/Screenshot-(391).png)

# Task 6: The Matrix Puzzle — Decode with NumPy & Reveal the Image

**Python** has a huge variety of libraries. **NumPy** and **Matpotlib** are two very useful libraries widely used for various applications having to deal with number system and data visualization.

## NumPy(Numerical Python):
- Used for numerical and scientific computing
- Efficient data structures to handle large arrays and matrices
- Includes functions to perform mathematical operations on the data
- Improves computational speed by using optimized, low-level implementations and by supporting operations on entire arrays without explicit loops.

## Matplotlib:
  - It allows users to create various types of plots such as line graphs, bar charts, histograms, etc
  - Helps in representing numerical data graphically making it easier to analyze patterns.

This task had a scrambled matrix , and my job was to reorder the matrix using NumPy operations and then reveal the image using Matplotlib.

![website](https://i.postimg.cc/cJRKHHsK/Screenshot-(400).png)
![website](https://i.postimg.cc/tJT72NF1/Screenshot-(403).png)

### Operations used:
- `arr.shape` = returns the number of rows and columns of the matrix.
- `arr.size` = returns the total number of elements peresent in the arary.
- `arr.reshape()` = changes the shape of an array.
- `imshow()` = displays data as an image
- `show()` = displays the plot

In the end a **smiley face** was revealed

# TASK 7: Create a Portfolio Webpage
The portfolio website was developed to showcase my skills, projects and my tech backgoud in a structured and visually appealing manner. The portfolio webiste helps me present my works and projects to the recuiter, peers and collaborators in a single paltform.

I used HTML, CSS and React JS to develop my portfolio website
![website](https://i.postimg.cc/mDPR6Lm8/Screenshot-(440).png)
![website](https://github.com/Krishna-Prasad31/MARVEL-level-0-report/blob/main/Screenshot%20(441).png?raw=true)
![website](https://github.com/Krishna-Prasad31/MARVEL-level-0-report/blob/main/Screenshot%20(442).png?raw=true)
![website](https://github.com/Krishna-Prasad31/MARVEL-level-0-report/blob/main/Screenshot%20(443).png?raw=true)
[GitHub Repository](https://github.com/Krishna-Prasad31/Personal-portfolio)

# TASK 9: Tinkercad

Tinkercad is an online simulation platform that allows users to design and test electronic circuits virtually. In this task, the objective was to get familiar with the Tinkercad environment and understand how basic electronic components work together through simulation. The task mainly focused on using an ultrasonic sensor along with a servo motor to create a simple radar-like object detection system.

**Components used:**

- Arduino UNO
- LED display
- Ultrasonic sensor
- Connecting wires

**Ultrasonic sensor:**

An ultrasonic sensor is an electronic device used to measure distance by using high-frequency sound waves. It works by emitting ultrasonic pulses and measuring the time taken for the sound waves to reflect back from an object. Using this time delay and the speed of sound, the distance between the sensor and the object is calculated.

Ultrasonic sensors are used in obstacle detection, Robotic assistance , parking assistance system and many other applications.

![website](https://i.postimg.cc/76ZDJzyS/Screenshot-(451).png)
![website](https://i.postimg.cc/nhfJYgJp/Screenshot-(452).png)
![website](https://i.postimg.cc/pr5wKYcf/Screenshot-(453).png)




# Task 10: Speed Control of DC Motor
In this task the main components used were Arduino UNO, L298N and a working motor.
- The Arduino UNO generates a PWM(pulse width modulation), this changes the duty cycle in the software.
- Th L298N receives a steady flow of 12V voltage from the power supply
- We vary the duty cycle of the PWM signal generated by the Arduino to control the effective voltage applied to the motor.
- The PWM is sent to the ENA pin of the L298N , according to the PWM the L298N swithces the motor supply **ON** and **OFF**.
- This action varies the voltage to the motor thus affecting its speed.
![Speed changing](https://i.postimg.cc/cH4qr5dW/IMG-5853-JPG.jpg)
[YouTube link](https://youtu.be/yBS88l1xOc8)

# TASK 11: LED Toggle Using ESP32
In this task we have to toggle LED using a webserver. For this task we mainly use ESP32, arduino code editor, LEDs, wires and resistors(220Ω).

**ESP32 :** It is a small powerful microcontroller with WiFi and Bluetooth, it also controlls the harware components. It runs code faster than arduino uno and is cheap. It is used in many IoT applications.

Connections are made as shown in the circuit diagram
![ESP32](https://microdigisoft.com/wp-content/uploads/2021/08/ESP32-1_bb-768x1506.jpg.webp)

A wired connection between ESP32 and the Arduino IDE in the PC is established using a USB-A to micro USB cable. the required code is written in the IDE and is compiled and then uploaded into the ESP32 which is firmly connected to the other components through the GIPO pins. When the uploading of the code is completed an IP address will be generated in the IDE and in any browser you can enter that IP address and get access to the web server which toggles the LEDs.

![Website](https://i.postimg.cc/x1zvL6qH/IMG-5874-JPG.jpg)
![Website](https://i.postimg.cc/ZRR0xqjg/IMG-5875-JPG.jpg)
![Website](https://i.postimg.cc/Qt9Krt5N/IMG-5876-JPG.jpg)

# TASK 12: Soldering Prerequisites
Soldering Prerequisites involved learning about the soldering equipment available in the laboratory, including the soldering iron, solder wire, soldering wick, and flux, and understanding their proper usage. Basic soldering was performed on a perf board. The procedure included placing components correctly, applying flux, heating the joint using a soldering iron, and forming proper solder joints while following necessary safety precautions. This task helped in gaining hands-on experience with soldering techniques and understanding the importance of correct equipment handling and supervision in electronics laboratory work.

![website](https://i.postimg.cc/g0DrFhnj/IMG-5884-JPG.jpg)
![website](https://i.postimg.cc/B6bSrwrK/IMG-5885-JPG.jpg)

# TASK 13: 555 Astable Multivibrator (60% Duty Cycle)
A 555 timer IC was designed and configured in astable mode to generate a continuous square wave output with a duty cycle of approximately 60%. In astable operation, the 555 timer does not require any external triggering and continuously switches between HIGH and LOW states, making it suitable for waveform generation.

| Components | Quantity |
|------------|----------|
| 555 timer IC | 1 |
| Resistors Ra = 10 KΩ | 1 |
| Resistors Rb = 20 KΩ | 1 |
| Capacitor C = 10 µF | 2 |
| Bread board | 1 |
| DC Power supply | 1 |
| Connecting wires | as per requirement |


The duty cycle of the astable multivibrator depends on the values of resistors **Ra** and **Rb** and capacitor **C1, C2**.

$$
\text{Duty Cycle} = \frac{R_A + R_B}{R_A + 2R_B} \times 100
$$

$$
\text{Duty Cycle} = \frac{30}{50} \times 100 = 60\%
$$

![website](https://i.postimg.cc/tC6Bd3rz/tim47.webp)

The circuit connections were made as shown in the above circuit diagram. The DC power supply was connected to the IC and then using the probes the output waveform was observed on the digital CRO screen by connecting the probes across the output and ground.
The waveform was an expected square wave.

![website](https://i.postimg.cc/nrPNsnh9/IMG-5896-JPG.jpg)
[YouTube Link](https://youtu.be/McGIs_mJHJM)

# TASK 14: Karnaugh Maps and Deriving the Logic Circuit
The Objective of this task is to design a *Burglar Alarm Circuit* based on two input conditions

1. Status of the door (is opened or not)
2. Status of the key (pressed or not pressed)
   
Using Karnaugh maps, the logic condition for activating the alarm is derived and implemented using simple logic gates.

The system consists of two inputs and one output.

**Door**:

- A = 1 : door is open
- A = 0 : door is closed

**Keys**:

- B = 1 : Key Pressed
- B = 0 : Key not pressed

**Alarm**:

- C = 1 : ON
- C = 0 : OFF

| A | B | C |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 1(🚨) |
| 1 | 1 | 0 |

**K-map**:

![website](https://i.postimg.cc/9XG3xV2m/Screenshot-2026-02-03-230531.png)

**The Logic Circuit**:

![website](https://i.postimg.cc/brHw8tth/image.png)

# TASK 18: Sad servers - "Like LeetCode for Linux"

Sad servers is a training ground to test your linux troubleshooting skills, it provides a wide range of problems to solve for every difficulty level. The best part of Sad sevres is that you dont get a lot of time to think and find the solution, there is a time limit after which the connection gets closed, this makes solving the problems challenging under pressure.

For the task Sad server called "Command line murders". In this Sad server we have to find the murderer using the "CLUE" which were available. Using the clues we use various commands on various directories and files to finally findout the murderer.

For this task i used commands like:

- `ls` - list files and directories
- `cd` - to navigate between directories
- `cat`, `less` - to read file contents
- `grep` - to search for specific patterns in files
etc...

![website](https://i.postimg.cc/VkqsCTs5/Screenshot-(419).png)
![website](https://i.postimg.cc/h4mVYD2h/Screenshot-(420).png)
![website](https://i.postimg.cc/mrFrrDz9/Screenshot-(421).png)
![website](https://i.postimg.cc/qqB02MRq/Screenshot-(422).png)

Finally after a couple of trial and error I successfully found out he Murderer.

# **TASK 15: Active Participation:**

I particpated in an intra college event called Impetus 25.0. It was organised by the IEEE UVCE club . IEEE conducted various competition during Impetus , i joined in two competitions called as
1. **Synthetic Intelligence:** It was an event where the organisers give you a problem statement and you with the help of AI we have to find the most practical solution to the problem statement. Even though i didnt win it i had great fun attending it and got to learn more about good prompting.
2. **BrainBids 2.0**: It was a general quiz competition where you are given points and you put your points at stake to get more points for answering correctly Ultimately Qualifying for subsequent rounds.

    **Certificate**:
   ![BrainBids](https://github.com/Krishna-Prasad31/MARVEL-level-0-report/blob/main/Screenshot%202026-02-05%20223018.png?raw=true)

I also did a JavaScript course from Infosys Springboard. This course helped me to use javascript in web development and its diverse application in web dev, as it is considered as the *brain* of web development

**Certificate**
![JavaScript](https://github.com/Krishna-Prasad31/MARVEL-level-0-report/blob/main/Screenshot%20(450).png?raw=true)

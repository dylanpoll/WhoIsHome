# Update
I have a much better deployment setup and re written code that was based off this project in my cloud controller repo. 


In the above mentioned repo the python application instead reports to a database overwritting entrees and logging times and handles hiccups with network device hangups by running a strike count over time to compensate for nmap not seeing activity on the network at the time of running the code.
It also has a react component that I made that pulls from the database and shows if the person in question is home or not among other things.


WhoIsHome.py re write : https://github.com/dylanpoll/cloud-management-system/blob/main/whoishomescript.py
React component : https://github.com/dylanpoll/cloud-management-system/blob/main/src/pages/whoIsHome.js


# Original WhoIsHome Post
Valencia Tech Clubs embedded systems divisions github

the Who Is home project does the following:

runs a python script that checks for the mac addresses of devices connected to your network. it uses Nmap for this.
  it runs those addresses against a list of addresses and if the address listed is present it sends a char to an arduino by using serial communications. 
 
 the arduino controls a LED strip and when it recieves a char it has an associated color for that device and it lights the LEDs for that person based on them being present. 



our divisions subsite
https://sites.google.com/view/valencia-robotics

our clubs site
https://sites.google.com/view/valenciatechclub

the Python Script was provided by : Jonathan De La Cruz

https://www.linkedin.com/in/jonathandelacruz96/

the Arduino Script and walk through and setup of the home lab was done by : Dylan Poll

https://www.linkedin.com/in/dylan-poll-4a324a1a2/

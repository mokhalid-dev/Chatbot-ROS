# Chatbot-ROS

A simple AI Chatbot using AIML (Artificial Intelligence Markup Language) which can be integrated to a social robot.

This project is about building a chatbot like siri with which we can  ask social questions and the bot will give you an appropriate answer. The chatbot uses AIML for this purpose. AIML stands for Artificial Intelligence Modelling Language. AIML is an XML based markup language meant to create artificial intelligent applications. AIML makes it possible to create human interfaces while keeping the implementation simple to program, easy to understand and highly maintainable. 

# RUNNING THE PROJECT 

Download all the files in this repository and make sure that ROS,pyAIML and sound_play packages are installed properly on your local system. I used ROS Melodic ,Ubuntu 18.04 for this project.Once you ensure that all these prerequisites are satisfied , you may need to make some changes to the .launch files. Change the path to data directory properly.Also don't forget to use 'catkin_make' and source commands. 

* After creating the launch file, change its permission using the following command:
     
        $ sudo chmod +x *.launch

* Use the following command to start interacting with the AIML interpreter:
       
        $ roslaunch ros_aiml start_chat.launch

* For Text to speech engine, execute 

        $ start_tts_chat.launch

* For Speech recognition, execute

	$ start_speech_chat.launch 

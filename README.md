# schedule_discord_bot
discord bot to automate class assignment and channel creation, with some fun features

Assigns discord roles to people based on the classes they are taking during a particular semester. If there are more than certain number of people taking some class on the server separate channel will be created only accessible to those taking the class. Helps connecting students with their peers taking same classes. Students use server for group studying and reaching out for help to classmates. 40 active members and counting!

To run bot include the bot's token under TOKEN.py saved in const folder. Then "python3 main.py"

Info on some of the commands, all need to have "?" in front:

  beginsemester      Only for Admin use, deletes the @member role from everyone to force everyone into class assignment
  
  classes            To assign class roles. After "?classes" include all the classes in text format following 4 letter 4 digits notation.
  
  classroles         Sends a list with class roles statistics.
  
  endofsemester      Deletes all class related channels and reports statistics on number of messages sent in each class.
  
  jailsmn            Used to send random person to jail for 1-48 hours. In jail you lose identity as all messages are reposted by bot with original one being deleted.
  
  help               Shows this info       
  
  logstudents        Updates log json file with all students. Needed in case bot missbehaves and deletes roles from people.
  
  major              To assign a major. Follow "?major" by the abbreviation of ones major
  
  online             Sends a message to a chat.
  
  reminder           Reminder is in development.
  
  reportstudents     Prints latest log json file with all students.
  
  restartandpull     Pulls updated code from github and restarts bot.

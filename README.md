# Carebot
NPR's Carebot is designed for collecting metric data of stories' performence, for details, visit Carebot's GitHub page:https://github.com/thecarebot/carebot and its blog: https://thecarebot.github.io/
The codes are configured based on IJNet information, but can be changed for any website which has Google Analytics inside terminal.
The Carebot application is currently hosted on Amazon Web Services, please see Oren for login information.
# Note
After the CarebotTracker code added to IJNet, users can ask more information via the Slack's #apptesting channel, such as the "hello" command for summary data, see the link for details: https://thecarebot.github.io/getting-started-with-Carebot/
# Instruction
Please follow the steps below for making changes to Carebot or simply wake her up.
-- ssh ubuntu@54.88.85.11    password: please ask Oren
-- cd carebot  (your folder name)
-- source carebot/bin/activate
-- source dev.env
-- nohup python carebot.py  (this step is to make carebot less “sleepy,” to stop the bot later, use command “ ps -ef ” to view    all running processes and choose our python carebot.py process’s PID to kill it. For example: kill #####

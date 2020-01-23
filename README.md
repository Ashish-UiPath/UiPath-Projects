*Jira_Twitter Integration Process Overview*

Create a project in JIRA with Kanban view option.
In the board there will be there Lists
 

   To do
   In Progress
   Done
    
    Each tasks that are created in Todo will be having a title and the description.

 
 The title will be of specific format.
 
 NEWFOLLOWER_<TWITTER_USERNAME>
 
 Ex. NEWFOLLOWER_zathvarun
 
 Task of the bot: 
 

    The bot should keep listening to the To do list and look for new issues/tasks.
    When identified a new tasks, it should open it and extract the information and move the task to in progress.
    With the extracted username it should go to the twitter website and enter the username name get the profile information.
    Take a screenshot of the profile page and attach it to the JIRA tasks and comment the profile information like tweets count, followers count and following count in the same task.
    Finally move the task to done.

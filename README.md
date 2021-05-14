# python_scripts
Here are just a bunch of scripts I like to write in notebooks to show customers step by step how they can use python and snowflake to get what they need.
## Scripts in this folder
I will be adding to this periodically, but the idea is feel free to make a copy of the script tweak it to your customer's need and share it with them.
- Test Clone Workflow notebook - One of my customers wanted to find a good way to compare databases within the same account and be able to update clones on a regular cadence based on changes in their prod evironment.  After speak with Jeremiah Hensen, he recommended leveraging the information schema.  I wrote a simple script to show you can compare information schemas easily within a python notebook.  If the customer wanted they can set up emails to notify users within the notebook.  (Mine doesn't have that because I didn't have time to finish prior to showing the customer - work in progress here). This script will also work across accounts, you will just have to change the connection strings and names of databases you decide to compare.
## Contributions/Feedback
If you want to help make these scripts better, I would love to collaborate.  Please be sure to test the code before sharing with customers!  I'm @katy.haynie on Slack.  Free free to reach out.

Thanks!

Katy

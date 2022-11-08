Thank you for purchasing the External Security Bot w/ Source. If you need any assistance setting up the bot. Please create a ticket. Setup is somewhat difficult and easy but you can definitely do it.

INSTRUCTIONS:

WINDOWS: 

1. Download File. 
2. Extract to a Folder.
3. Open the Auth/config.json
4. Create a Discord Application at https://discord.com/developers/applications
5. Turn on all Intents (Presencee, Server Members, and Message Content)
6. Paste the TOKEN into the TOKEN Category in the config.json.
7. Configure any other settings in the config.json
8. Make sure you paste your MAIN GUILDID into the MAINGUILDID field. 
9. ALLGUILDID is all the department/external discords.
10. Invite the bot to all discords and move the role that the bot creates to the top of every role. (Which should be the name of the bot)
11. Create a role and move it to the top under the role that the bot created. Also Fill in the PERMISSION_ROLE_NAME with that role name.
12. Just read the MISC CONFIG STUFF.
13. Create a Moongoose database. https://account.mongodb.com/account/
14. Run the INSTALLERPART1.bat
15. Run the INSTALLERPART2.bat
16. open a command prompt and run this command. pm2 start src/index.js

LINUX:

1. Download File. 
2. Extract to /home/external-security-bot
3. Open the Auth/config.json
4. Create a Discord Application at https://discord.com/developers/applications
5. Turn on all Intents (Presencee, Server Members, and Message Content)
6. Paste the TOKEN into the TOKEN Category in the config.json.
7. Configure any other settings in the config.json
8. Make sure you paste your MAIN GUILDID into the MAINGUILDID field. 
9. ALLGUILDID is all the department/external discords.
10. Invite the bot to all discords and move the role that the bot creates to the top of every role. (Which should be the name of the bot)
11. Create a role and move it to the top under the role that the bot created. Also Fill in the PERMISSION_ROLE_NAME with that role name.
12. Just read the MISC CONFIG STUFF.
13. Create a Moongoose database. 
14. cd into the directory.
15. npm install 
15. npm install -g pm2
16. pm2 start src/index.js
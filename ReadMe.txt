========= How to setup the Edu-bot Env ==========
1. Download the botpress (Windows version) from the shared folder. You can also download it from botpress.com, but each version has slight difference. It is 
   recommended to use this to avoid any inconsistency:
   botpress-nightly-2020-12-27-win-x64.zip
   
2. Extract the download file at your local file system.

3. Go the the expanded folder, and kickoff botpress by running bp.exe. 

4. You should now be able to open the bp server via any browswer http://localhost:3000/. Register your user.

5. Download the Edu-bot from the shared folder:
   bot_edubot1_1616552751471.tgz

6. Within the botpress console (http://localhost:3000/), and you can create a new bot -> import, and select the file downloaded. The Edu-bot will be loaded
   to your local server.

7. Download website sources PUBLISHED.zip from this shared folder. 
      
8. Go into your botpress folder in your file system, then goto \data\assets\modules\channel-web\, and unzip PUBLISHED.zip here.

9. Now, you should be able to access the demo website at http://localhost:3000/assets/modules/channel-web/PUBLISHED/Home.html

Please note: 
  In a real world deployment, you will need to modify \data\assets\modules\channel-web\PUBLISHED\Home.html to change
  chatbot config's host to be the BP hosting server domain name or ip address.

 //━━━━━━━━━━━━━━━[ ᴄᴏᴍᴍᴀɴᴅ ᴛᴇʀᴍᴜx ]━━━━━━━━━━━━━━━\\
 $ pkg upgrade && pkg update
 $ pkg install nodejs
 $ pkg install yarn
 $ pkg install git
 $ pkg install libwebp
 $ pkg install ffmpeg
 $ pkg install imagemagick
 $ termux-setup-storage
 
 # TERMUX
 $ cd /sdcard/CyberMd
 $ yarn
 $ npm start

 # RUN PM2
 $ cd /sdcard/CyberMd
 $ yarn
 $ npm i pm2 -g
 $ pm2 start index.js
 $ pm2 save
 $ pm2 monit 
 //━━━━━━━━━━━━━━━[ ᴜᴘʟᴏᴀᴅ ᴛᴏ ʜᴇʀᴏᴋᴜ ]━━━━━━━━━━━━━━━\\
 $ pkg update
 $ pkg upgrade
 $ pkg install yarn
 $ pkg install git
 $ termux-setup-storage
 $ npm i -g heroku
 $ heroku login
 $ cd /sdcard/CyberMd
 $ heroku git:clone -a backupte 
 $ git add .
 $ git commit -m "namafile"
 $ git push heroku master
 
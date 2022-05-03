# Instructions to install youtube-dl on Windows as simple as possible
1. [Download youtube-dl.exe](https://ytdl-org.github.io/youtube-dl/download.html)
2. Create a new folder and title it youtube-dl then throw youtube-dl.exe into that folder
3. [Download ffmpeg build](https://ffmpeg.org/download.html)
4. Inside the build compressed folder go to bin folder and move all files in there to the youtube-dl folder
5. Move Youtube-dl folder to whatever path you wish
6. Open the terminal and go to the youtube-dl folder
7. Copy the whole path of the youtube-dl folder and paste it into System:Advanced system settings:Environment Variables... At the System Variables below click on Path variable and paste the path
8. Create a new folder youtube-dl in the directory user:AppData:Roaming and create a new txt document config.txt in it
9. In the config.txt type: 
-f mp4
-f best
-o "Paste whatever directory you wish to store downloaded videos" For example: F:/Obrabotka/%(title)s.%(ext)s
--no-mtime

### downloading ytdl-explorer

**Go to notthebee Wolfgang repository**

1. [Download the ZIP archive of this repository](https://github.com/notthebee/ytdl-explorer/archive/refs/heads/main.zip)
2. Unpack the archive
3. Double-click on the ytdl.reg file and confirm adding the keys to the registry
4. Copy the video link, go to the folder where you want to download it
5. Right click on the empty space and choose your option
6. Voilà!

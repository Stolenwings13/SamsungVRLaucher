# SamsungVRLaucher
Launch SamsungVR to play http(s) mp4 videos

This is a simple html script that launches SamsungVR (newer version of MilkVR) to play http or https mp4 video on Samsung GearVR.
In conjunction with ES File Explorer or Solid Explorer, you can play any mp4 videos shared on the network with SamsungVR (not just the ones shared with DLNA or UPnP, which are supported by SamsungVR natively). Any network share type supported by ES File Explorer and Solid Explorer will work, including SMB, FTP, SFTP(SSH), Google Drive, Dropbox, OneDrive, WebDav, Yandex, Owncloud, Box, SugarSync, MediaFire, and more.


To use it (assuming GearVR is set up and SamsungVR is installed):
1. Download this html file onto your Samsung device.
2. Navigate to the folder containing the downloaded html file with My File (Samsung native file explorer) or any other file explorer.
3. Open the html file with a browser (Chrome is suggested).
4. Enter the mp4 video's http or https address. (SamsungVR will not work with http address that needs authentication, not even including the authentication info in the link like this: https://username@password:www.example.com/sample.mp4)
5. Choose the appropriate 2D or 3D video type. If you don't know which type to choose, pick one in the drop-down menu and a picture explaining the chosen video type will appear.
6. After entering the video address and choosing the appropriate video type, press "Start SamsungVR" button at the bottom.
7. Put your Samsung device in GearVR and enjoy!


To use it to play video on your network share:
1. Follow the above procedure up to step 3.
2. On your Samsung device, open ES File Explorer or Solid Explorer and navigate to the network share location containing the video.
3. Click on the video and open it with a video player that shows the video address. (For example in MX Player, after the video starts player, click on the 3 dots on upper right to access the menu, click on "Tools" then "Properties", the video address is shown under "Path".)
4. Copy the video address shown in the media player of your choice.
5. Without exiting the video player nor the file explorer, bring up the browser with the html script loaded, paste in the video link.
6. Follow the above procedure starting at step 5.

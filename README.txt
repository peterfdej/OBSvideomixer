OBSvideomixer can be used as a remote scene controle for OBS.
It uses the OBS-websocket plugin by Palakis.
I used the code of OBSvisionmixer (https://github.com/illusdidi/illusdidi.github.io) and
OBSliveTally (https://github.com/lebaston100/OBSliveTally) as an example (thx).

For use download this repositary and run index.html in your browser.
Connect to the IP address of the PC where OBS is running. The default port is 4444.
It is recommended to use a password for the OBS-websocket API.

For using the "Start Replay" button, confugure OBS for replay and name the scene for showing the saved replay buffer "Replay". When the scene with the name "Replay" exists, the button appears. Pressing this button will save the replay buffer (when replay buffer is running), wait for 2 seconds for saving the file and transitions the scene "Replay" to "Program".
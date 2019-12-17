
![](/img/cover.jpg)


# quickstart (Closed beta instructions)

Download Tycoon Beta Installer:
[Download](https://github.com/yvovonBerg/CGTS_Downloads/releases/download/1.0.0/TycoonBuildDeploy.zip)

1. Extract the zipfile somewhere where you can easily find it back.

2. Make a new Unreal Engine project.

3. Start TycoonBuildLauncher.exe

![](/img/tycoonbuilddeploy.PNG)

4. Select the Unreal project root folder. (This is the folder where the .uproject lives)

5. Enter the closed beta license key. (Can't find your key? Check your beta welcome email, or raise an issue at the service center: [Tycoon Service Center](https://
tycoon.atlassian.net/servicedesk/customer/portals)) or press submit bug.

6. Make that Unreal is not running.

7. Click "install build".

8. Confirm that you can see a 'TycoonTool' directory in the /Plugins directory of your Unreal project.

9. Launch the project.

10. Check that Tycoon is visible in the "Plugins" menu.

![](/img/TycoonInstalled.PNG)

11. Open the "Modes" panel -> Window -> Editor Modes.

12. Select the Tycoon icon.

![](/img/Tycoontopui.PNG)


# Known issues with Tycoon Beta

1. Source mesh must be facing the Y axis. (When preparing your mesh in your DDC application)

2. Only one material index is supported for track pieces.

3. Material instances in Unreal Engine are not supported currently.

4. Tycoon piece is not being rebuilt automatically after saving the map / Help my track is gone after saving:
Click "Update Track" to fix this.

5. Closed beta only: Track does not working after shipping. Will be fixed after closed beta.

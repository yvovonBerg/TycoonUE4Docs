
![](/img/cover.jpg)


# Quickstart (Closed beta instructions)

Download Tycoon Beta Installer:
Current build of Tycoon is made for UE4 4.23.

[Download](https://github.com/yvovonBerg/CGTS_Downloads/releases)

1. Extract the zipfile somewhere where you can easily find it back.

2. Make a new Unreal Engine project.

3. Start TycoonBuildLauncher.exe

![](/img/tycoonbuilddeploy.PNG)

4. Select the Unreal project root folder. (This is the folder where the .uproject lives)

5. Enter the closed beta license key. 
> Can't find your key? Check your beta welcome email, or raise an issue at the service center:  
Go to [Tycoon Service Center](https://tycoon.atlassian.net/servicedesk/customer/portals) or press submit bug.

6. Make sure that Unreal is not running.

7. Click "install build".

8. Confirm that you can see a 'TycoonTool' directory in the /Plugins directory of your Unreal project.

9. Launch the project.

10. Check that Tycoon is visible in the "Plugins" menu.

![](/img/TycoonInstalled.PNG)

11. Open the "Modes" panel -> Window -> Editor Modes.

12. Select the Tycoon icon.

![](/img/Tycoontopui.PNG)


# Known issues with Tycoon Beta

Source mesh must be facing the Y axis. (When preparing your mesh in your DDC application)

Only one material index is supported for track pieces.

Material instances in Unreal Engine are not supported currently.

Closed beta only: Track does not working after shipping. Will be fixed after closed beta.

Saving spline presets is not supported yet, however you can still add existing presets to spline based tracks.

Rotating the TycoonMain actor causes the spline to deform incorrectly, -> remove any rotation from the actor to resolve this for now.

Spline mesh deforms incorrectly in some 90+ degree turns -> adjust the spline length to resolve this for now.

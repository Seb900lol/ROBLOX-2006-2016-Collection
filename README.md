# HELP
Manual Actions
Create a player: game.Players:CreateLocalPlayer(0)

Load your player's character: game.Players.LocalPlayer:LoadCharacter()

Run the game: game:GetService("RunService"):Run()

IMPORTANT: Antivirus Disclaimer
Some users have been reporting that their antivirus programs are flagging this as malicious. This is due to the current antivirus ecosystem flagging effectively everything that isn't signed code as malicious if it performs any activities that are deemed as such, even if those actions are non-malicious (such as writing to the Windows registry, writing files in the background, or downloading any data on the network).
Roblox unfortunately did not sign the executable when this was compiled in March of 2007, hence why these warnings are appearing. This should be cleared once the executable is submitted for manual analysis, but for now you'll need to make an exception if any sort of anti-virus alarm is raised.

IN SUMMARY, this is a misdiagnosis and there should be nothing to worry about. But please do make sure to heed some of the security warnings listed below.

Requirements
For this to execute correctly, you need to make sure your system has the Microsoft Visual C++ 2005 Service Pack installed. This pack was standard in most older systems, but newer systems are no longer bundled with it.

You can find it here:
https://www.microsoft.com/en-us/download/details.aspx?id=26347

(Note: You will need the x86 pack. It may also help to have the x64 pack as well.)

WARNING: DO NOT CONNECT TO UNTRUSTED SERVERS
This build does support hosting and connecting to servers, but there's a non-zero chance this build has exploitable bugs that can be used for remote code execution on your machine.

If you do try and take advantage of the multiplayer functionality in this build, make sure you only connect to servers that are trustworthy. Otherwise it isn't worth doing.

A publicly shared server >>IN PARTICULAR<< is very likely dangerous to connect to. Even if the server host isn't doing anything malicious, a malicious client could connect to the game and potentially exploit some buffer overflow in the network protocol to perform remote code execution on your machine. Private servers where every participant is known and trustworthy are probably okay, but just remember to be careful!

You have been warned, be smart and have fun :)!

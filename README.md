 **IMPORTANT  - 9/6/2019 These instructions are NEWER than the video. Please read them and disregard the video. When I get a chance to make a new video I will update.**

Thank you for taking the time to keep your Zune alive. Sadly, due to the scarcity of parts for all Zunes, Wye Oak Mobile Device Repair can no longer accept Zune's for repair. This an unfortunate development since as far as we know, we were the last company to do repairs. 

With the above in mind, I set out to find a way that would be easiest for anyone to update their working Zune. I needed to find a method with the fewest amount of steps possible so that those who are not very tech savy, the process would be approachable and encouraging. Below are the step my step methodology to achieve that goal. If you are downloading from GitHub using git, you will not need to unzip.

1) If you do not have the Zune Manager installed, please install it. 
2) As administrator, open the file **C:\Windows\System32\drivers\etc\hosts** in Notepad.
3) Append the line below to it and save the file:
    **127.0.0.1 resources.zune.net**

4) **Skip this step if you are using git to clone the project** - Unzip the file zunefirmare-upgrade-master.zip to a directory of your choice. If you leave it to the default, most unzip managers will use the file name as the directory where it will unpack it to. 

5) Go to that directory where the files were unzipped to. Inside it there is a file named "mongoose-free-6.9.exe". Double click on that executable. IMPORTANT, if your firewall asks to allow access, make certain that the option for Public is unchecked and PRIVATE is checked.

6) Now open your web browser and go to http://resources.zune.net 
7) You should now see a directory with the Zune firmare update files in it. If you do not see that, please go back to step 1) and make sure each step has been performed properly.
8) At this point you can now connect your Zune to your PC and update it. 
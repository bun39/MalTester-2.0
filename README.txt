To run a malware test similar to The PC Security Channel's malex.py script, put this executable in the same directory as your malware samples, and double click it to run. DO NOT DOUBLE CLICK ANY MALWARE! The executable will be run, parse the directory (not subfolders) for executables, test them to see if your AV solution detects and blocks them, and log the results to MalTester2-log.txt in the same directory as everything else.

Make sure that this program is run as administrator, otherwise there may be bugs.

THIS PROGRAM IS DESIGNED TO EXECUTE MALWARE AND DETERMINE HOW GOOD AN ANTIMALWARE SOLUTION'S DETECTION IS! PLEASE DO NOT RUN THIS PROGRAM IF YOU DO NOT KNOW WHAT YOU ARE DOING! I TAKE NO RESPONSIBILITY FOR INFECTED MACHINES!

Note that some AV solutions may detect this program as malware due to the software protection I have used to deter reverse engineering of the code by newbies. If this is the case, make sure you whitelist this program.

Current version is 2.0. Version 1.0 was private. I have decided to release version 2.0 to the public to encourage awareness and to allow security researchers to partially automate the AV testing process.
# windebloater

**WARNING: I DO NOT TAKE RESPONSIBILITY FOR WHAT MAY HAPPEN TO YOUR SYSTEM. THIS IS AT YOUR OWN RISK.**

Out of the box, Windows 10 (and 11) are EXTREMELY bloated operating systems. Processes such as advertising and telemetry are known to slow down your system, and Windows also comes with useless apps as well, many of which are sponsored. These scripts, forked from [ChrisTitusTech's win10script repository](https://github.com/ChrisTitusTech/win10script) and tweaked by Kapilesh Pennichetty, will debloat your system so that you can enjoy a fast, seamless computing experience with Windows.

To run:

The script to run is windebloater.ps1 if you are on the master branch, or win10debloat.ps1 if you are on the downstream branch.

- Open Powershell as Administrator
- Navigate to the directory where the script is stored
- Set the Execution Policy to unrestricted
- Run the script, and select your desired apps and debloat options. Wait until the script finishes before closing the window.
- Restart your computer
- Open Powershell as Admin
- Restrict the execution policy for security.

Tweaks from this script may need to be re-run after each feature update, as feature updates tend to reinstall bloatware and reset other settings that this script disables, such as telemetry. Feature updates happen every six months, starting at the beginning of the year.

Enjoy your speedy Windows experience!

## For Contributors

First off, thank you so much for contributing to this project! Your Pull Requests and Issues are welcomed, and I look forward to working with you.

This repo has two branches: the master branch and the downstream branch. Y'all are welcome to contribute to both.

- master: My personal script with modifications for my workflow. Isn't as aggressive as the original script or the downstream branch. Aims to provide a speedy experience for the general user with lots of preconfigured settings.

- downstream: Branch that contributes to ChrisTitusTech's original repository. Any contributions made here will be put in a PR to the original repo. More aggressive than the master branch, and aims to be a base template to be modified by the user.

Again, thank you for your contributions and happy coding!

## README From [Original Repo (win10script)](https://github.com/ChrisTitusTech/win10script)
This is the Ultimate Windows 10 Script from a creation from multiple debloat scripts and gists from github. I am building the script out to be a swiss army knife to help setup new machines and tweak existing ones saving time for all. 

### My Additions

- Dark Mode
- One Command to launch and run
- Winget Install
- O&O Shutup10 CFG and Run
- Added Install Programs
- Full GUI Implementation

For complete details check out https://christitus.com/debloat-windows-10-2020/

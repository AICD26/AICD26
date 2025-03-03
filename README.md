- 👋 Hi, I’m @AICD26
- 👀 I’m interested in RedHat solutions for System Administrator.
- 🌱 I’m currently learning a lot about RedHat 7 and RedHat 8. Vmware. Bash scripting.
- 💞️ I’m looking to collaborate on: RedHat 7 and RedHat 8. Vmware. Bash scripting.
- 📫 How to reach me Github

Hello everyone!
I'm a System Administrator in a Linux RedHat 7 and RedHat 8 VDI (Virtual Desktop Infrastructure) Environment. I have some experience with some Linux Distros like (Debian, Suse, Fedora, Rasbian, Mint, Ubuntu, RedHat)

As said I'm System Admin that also mean I have some knowledge about programming. So, Programming languages I know from more to less: Bash, Powershell, MySQL, Python) also some web develop languages: HTML, CSS, Javascript, PHP.
With that said, I began working with Redhat OS few months ago (More accurate with RedHat 7.9) and I have to look for creative solutions for some tasks that in other OS would be easy. Currently I'm migrating some machines to RedHat 8.10 from RedHat 7.9.
I wrote some scripts in Bash to manage:
- All in One IDM Ipa client uninstall/install, autofs mount points, conectivity check, complete logging, robust script (fail proof).
- Network device config script. A vlan specific config with a hostname random assignation for VDI template Deployment.
- PKI workaround script which checks the PCSCD daemon, wake up if its dead. If woke up, check if its ok or need a restart. Everything with logging.
- USB Driver compile script. Not much to say here, it compiles the USB driver.
- Nvidia Driver compile script. As the USB driver compile. It compiles the Nvidia driver.
- Connection check: This one contain a list of machines you want to check connectivity with. Sends a Ping to each one and returns the answer. Also allow to run some commands in selected machines if needed.
- Poweroff: This one is based on the Connection Check one. It has a list of machines you may want to poweroff at some point.
- Ipa password change with no privilege needed. A script that allows users to change their own password in a IPA environment.

 I write script solutions in Bash mainly. In this case, for RedHat 7.9 and 8.10 problems I find in my daily routine.

 The most recent script I'm trying to write is for the login screen of RedHat 8.10. The idea is to allow IDM (IPA) users to change their expired password from the login screen since GDM can't manage that situations.

Required requirements:

- VPS/VDS/Any PC with the ability to open a port on Windows
- > 2 CPU cores
- > 1.5GB RAM

It is also necessary to take into account that all logs that come to the panel will be stored on this server,
therefore, disk space must also be chosen with a margin.

Launch Instructions:

1) unpack the Panel folder to any Windows directory
(preferably a folder, not an .exe, as it will create working files in the current directory)

2) try to run RisePro_Server.exe

2.1) if you get any error (very rarely) then you don't have VC++ libraries installed:
  - go to the Tools folder from the archive and install VC_redist.x86.exe and VC_redist.x64.exe
  - run RisePro_Server.exe again

On a successful console, the working ports of the server will be written

3) install ChromeSetup.exe from the Tools folder in the archive (if there is any other browser, then it is not necessary)

4) go to the browser and go to http://localhost:8081/

5) log in with your RisePro data

After the first successful authorization, we can enter the panel from any other PC at http://IP SERVER:8081/
(when the Allow External Access checkbox is enabled in the panel settings)
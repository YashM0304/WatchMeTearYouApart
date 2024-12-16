# WatchMeTearYouApart

The malware program (Downloader) works by first downloading a secondary payload (a
shutdown program) from the internet (GitHub) and saving it in the Startup folder to ensure it
executes on system reboot. Once the secondary payload is executed on system startup, it
enables the necessary privileges to shut down the system, displays a misleading message box
to the user, and then forces the system to shut down.

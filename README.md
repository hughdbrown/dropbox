# Running Dropbox as a service on linux
1. Install Dropbox from [https://www.dropbox.com/en/install?os=lnx](instructions).
2. Copy `etc/init.d/dropbox` to `/etc/init.d/`
3. Edit `/etc/init.d/dropbox` so that it uses the correct user (default is hughdbrown)
4. Start Dropbox service: `sudo service dropbox start`
5. Confirm that it is running: `sudo service dropbox status`


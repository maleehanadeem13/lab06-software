# apt update vs apt upgrade
sudo apt update only downloads the newest list of packages from the repositories. It installs nothing.
sudo apt upgrade actually downloads and installs the newer versions of the packages already on the server.
Update is like checking the Play Store for updates, and upgrade is like pressing "Update all".
Always run update first, because upgrade uses the list that update downloaded.

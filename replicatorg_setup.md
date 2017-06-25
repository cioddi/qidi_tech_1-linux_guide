# Install java runtime environment
# The apt-get commands are intendet to be used on distributions that utilize the apt package management system and will slightliy differ for other distros
sudo apt-get install openjdk-8-jre

# Install python and python-tk
sudo apt-get install python-tk python2.7

# Download replicatorg from one of these mirrors (one that appears trustworthy) since the download link on the original site is down
# or search the web for replicatorg-0040-linux.tgz since the official mirror appears to be down
# http://www.filewatcher.com/m/replicatorg-0040-linux.tgz.45962287-0.html

# Unpack the archive and cd into the directory
# Make file replicatorg executable using chmod
chmod +x replicatorg

# Now start replicatorg and slice your models according to the documentation
# If you run into errors try starting it again if they reproduce please document and send them to me
# It is possible that I have had some dependencies already installed
./replicatorg
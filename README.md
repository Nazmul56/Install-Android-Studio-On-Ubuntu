Install-Android-Studio-On-Ubuntu
================================
# Install JRE & JDK
<pre>
Install JRE - 7 or upper virsion from Software Center
Install JDK - 7 or upper virsion form Software Center
</pre>
OR
<pre>
sudo apt-add-repository ppa:webupd8team/java
sudo apt-get update
sudo apt-get install oracle-java8-installer
</pre>
# Check Java Version
<pre>
javac -version  (For JRE)
java -version    (For JDK)
</pre>
# For "Unable to run mksdcard SDK tool."(ubuntu 14.04)
<pre>
sudo apt-get install lib32z1 lib32ncurses5 lib32bz2-1.0 lib32stdc++6
</pre>
# Download All Android Studio Package(For Linux Package)
From here
http://developer.android.com/sdk/index.html
# Unzip & Save 
Unzip Downloaded Zip file &
Save it on Home Directory.

# Run this command
<pre>
cd /home/USER_Name/android-studio/bin
sudo chmod 777 -R studio.sh
./studio.sh
</pre>
# Add Github in Android Studio
<pre>
Go to
File > Setting > Version Controll > Github 

Fill : Username and Password.

</pre>

# Install Git Using this Command
<pre>
sudo apt-get install git
</pre>
# Enabel VCS 
<pre>
Go to VCS > Enable VCS >> Select git from box Press OK 
</pre>
# Now Github is Connected .
# To Download Old source code
<pre>
Go to VCS > Checkout from Version Controll > Github > "Here Set your github username: and Password: "

Set Android Master Password: and Confirm it. 

Select your repository  press OK.
</pre>
# Share on Github 
<pre>
Go to VCS > Import into Version Controll > "Select" Share on Gtihub .

Comite , Push .
</pre>
# SATA Details
<pre>
https://www.cyberciti.biz/faq/linux-command-to-find-sata-harddisk-link-speed/
</pre>

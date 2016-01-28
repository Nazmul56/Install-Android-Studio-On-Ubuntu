Install-Android-Studio-On-Ubuntu
================================
####Install JRE & JDK
<pre>
Install JRE - 7 or upper virsion from Software Center
Install JDK - 7 or upper virsion form Software Center
</pre>
####OR
<pre>
sudo apt-add-repository ppa:webupd8team/java
sudo apt-get update
sudo apt-get install oracle-java8-installer
</pre>
#####Check Java Version
<pre>
javac -version  (For JRE)
java -version    (For JDK)
</pre>
### For "Unable to run mksdcard SDK tool."(ubuntu 14.04)

<pre>
sudo apt-get install lib32z1 lib32ncurses5 lib32bz2-1.0 lib32stdc++6
</pre>

####Download All Android Studio Package(For Linux Package)
From here
http://developer.android.com/sdk/index.html

####Unzip & Save 
Unzip Downloaded Zip file &
Save it on Home Directory.

####Run this command

<pre>
cd /home/USER_Name/android-studio/bin
sudo chmod 777 -R studio.sh

./studio.sh




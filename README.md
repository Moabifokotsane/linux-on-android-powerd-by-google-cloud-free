# linux-on-android-powerd-by-google-cloud-free
Good day, this is a simple and fun respiratory of how to run google cloud powerd linux operating system on android device 2022. 

# Requirements 
1. Google Cloud Console with project (register account here : https://console.cloud.google.com/freetrial ) 
2. Android Terminal (Get yours here: https://play.google.com/store/apps/details?id=com.termux) 
3. Python running on Android 
4. Curl 
5. Google Cloud SDK 


# Steps 
1. Open the Termux app then type in : 
```bash 
apt upgrade 
```
Lets install python : 
```bash 
pkg install python 
```
Lets install curl :
```bash
pkg install curl
```
Now we download Google Cloud SDK : 

```bash 
curl -O https://dl.google.com/dl/cloudsdk/channels/rapid/downloads/google-cloud-cli-394.0.0-linux-x86.tar.gz
```
Lets extract Google Cloud SDK :
```bash
tar -xf google-cloud-cli-394.0.0-linux-x86.tar.gz
```
Now install Google Cloud SDK on your android : 
```bash 
./google-cloud-sdk/install.sh
```
If you want to send anonymous usage statistics to help improve the gcloud CLI, answer Y when prompted.
enable command completion, answer Y when prompted.

# Run 
To run Google cloud SDK 

```bash 
./google-cloud-sdk/bin/gcloud init
```

To Log into Gooogle Cloud Shell : 
```bash
gcloud cloud-shell ssh
```

# Summary
Its important to note that with android Termux there are a lot of Linux limitations which may include being non-Root (You are limited to run commands) , 
With the limitation you may face the inability to let alone install shell apps such as Metasploit & other apps or services you may want to run in a
typical linux system. 
You get to enjoy Google Cloud Privilages and services on your android device such as High internet speeds for your VM just to mention a few good rewards of getting this set up on your android device. 
You may beg to differ and ask why not download the GC app from playstore, well the app has a few bugs that can hold you back when working on a project. The app is good for Cloud monitoring with its API faced UI that brings all resource monitoring to your device which is good. but this is for current Termux users who always run into difficulties because of the platform. 

# Follow 
Follow for more interesting ideas and respiratories that may be of use to you and simplified to precision. 


# ivw
Interaction in Virtual Worlds

If you have gotten this far, it is assumed you have thes files checked out into
this working directory:

```
  README.md
  Vagrantfile
```
To get started, do:
```
	vagrant up
```
Lots of output will follow, including a lengthy download and install. When it finishes,
you will be able to log into the IVW machine with:
```
	vagrant ssh
```
This should bring up a control panel with some icons. You'll want to click the headphones
icon to launch the Virtual World services (Stanford CoreNLP parser, Parser Wrapper,
OpenSim server, and Kaldi speech recognizer).

Next up, you'll want to click the icon that brings up the MonoDevelop IDE, and in it
open and run the IVW solution.

Please refer to this [README](http://speech-kitchen.org/ivw-readme-2/) for extensive details
on setting up and running.

NOTE: Substitute 'vagrant' for 'mario' whenever referring to user id or home folder.
Know that the vagrant password is the same as the userid. ;)

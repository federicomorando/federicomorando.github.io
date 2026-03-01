---
title: "Legacy: favourite"
draft: true
---

1298718375, 3




(50, 50, 1, 'Software', '<p>

Questa pagina &egrave; e sar&agrave; scritta solo in italiano, semplicemente 
perch&egrave; ci sono gi&agrave; fin troppe ottime pagine su questi temi in 
inglese...



<ul><li>https://addons.mozilla.org/collection/muras</li>

<li>https://addons.mozilla.org/collection/muras-firefox</li></ul>

https://addons.mozilla.org/en-US/firefox/collection/muras





<ul><li>Audio/video editing:

<ul><li>to check: jokosher</li>

<li>to check (for webcam): cheese</li></ul></li></ul>

 






<ul><li>video editing:

<ul><li>PiTiVi</li>

<li>...</li></ul></li></ul>



<ul><li>compare directories:

<ul><li>dirdiff</li>

<li>Meld</li></ul></li></ul>



<p>gnome-schedule</p>



<p>To mount a remote folder accessible through SSH, you can use sshfs (together with fuse-utils, which should be already installed in the system).

<ul><li>sshfs#my-remote-user@my-remote-host:/home/my-remote-user /my-local-filesystem
emotefs fuse user,noauto 0 0</li></ul></p>





<strong>Massy page, but I use it frequently for reference ;-)</strong>



vsftp (<a href="/ftp-server">installation comments</a>)





OCR & PDF
=============

* tesseract-ocr tesseract-ocr-ita tesseract-ocr-eng tesseract-ocr-fra tesseract-ocr-spa
* gocr (meno performante di tesseract, ma forse più customizzabile... da approfondire...)
* GUI sperimentate con soddisfazione: gscan2pdf (Ubuntu Repository)
* GUI sperimentate, ma che non hanno entusiasmato: gImageReader (GTK GUI, v. 0.8.1), OCRFeeder (GTK GUI, v. 0.6.6)

Password manager e simili
=========================

* [KeePassX](http://www.keepassx.org/): raccomandato.







<h2>Some favorite (K)ubuntu packages.</h2>

<ol>

<li>Repositories</li>

<ul>

<li>Skype<BR>Simply add the following line to your sources.list file (usually /etc/apt/sources.list):

"deb http://download.skype.com/linux
epos/debian/ stable non-free"

Now you can use apt-get update to sync to latest repository and then apt-get install skype to install Skype.</li>



<li>OpenOffice: deb http://ppa.launchpad.net/openoffice-pkgs/ubuntu intrepid main</li>

</ul>

</ol>



<h2>Photography related stuff</h2>

<li>autopano-sift</li>

<li>hugin</li>



Graphics:

<li>gimp</li>

<li>inkscape</li>











<h2>Internet</h2>

<li>"firefox-3.0"</li>



<li>"thunderbird"</li>

<li>"lightning-extension"</li>





"ekiga"





Multimedia:

mozilla-plugin-vlc





moonlight-plugin-mozilla and related packages





<h2>Office and the like:</h2>

<li>openoffice.org</li>

<li>freemind</li>



<h2>Games</h2>

<ul>

<li>frozen-bubble</li>

<li>lbreakout2</li>

<li>pathological</li>

<li>pacman</li>

<li>pingus</li>

<li>wormux</li>

<li>wesnoth</li>

</ul>



Cellar phone managerment (through Bluetooth):

<li><a href="http://www.gammu.org/">gammu</a>;</li>

<li><a href="http://wammu.eu/">wammu</a> (Gammu GUI);</li>

<li>gMobileMedia for files (to try).</li>

<li>Funambol.com and Gnokii.org (to try synchronization).</li>





Scientific and academic
=======================

### gretl ###
Econometric package

### jabref ###

Reference manager


<h2>LaTeX and BibTeX</h2>

<ul>

<li>texmaker</li>

<li>lyx</li>

<li>kile</li>

<li>openoffice.org-writer2latex</li>

</ul>





<li>"mono-common"</li>



<li>"netcat"</li>



<li>"pandora"</li>









System
======


* gparted

* grsync



Instant Messenging
==================

* pidgin

















"solarwolf"

"strigi-client"

"tomboy"

"udev"




Trying to compare these:

<li>Rawstudio can read and convert RAW-images from many different cameras,

including Nikon and Canon. Rawstudio uses dcraw.</li>

<li>UFRaw is a standalone tool to import raw data from high-end digital cameras.</li>

<li><a href="http://www.rawtherapee.com/">Raw Therapee</a> (???)</li>

DigiKam and Krita

Video
=====

* vlc



Stuff you should get rid off, yet...
====================================

* VirtualBox

* Wine

### Stuff I run with Wine ###

CombineZ (CombineZP is the latest version I used)
To install in Wine:
	$ msiexec /i CombineZP.msi
	$ wine ''/home/muras/.wine/drive_c/Program Files/CombineZP/CombineZP.exe''

Copy in System32 the two missing DLLs that are in this folder (copied from Windows System32).
WMASF.DLL
WMVCORE.DLL
You should have installed the wine-gecko package. (Otherwise, try to open the help file from within the program: Wine should ask you to install Gecko. Agree.)



* ttf-mscorefonts-installer

### Proprietary stuff ###

* skype
* DropBox: per chi volesse entrare nel tunnel dando una mano al sottoscritto
<p>If you want to create a DropBox account on the basis of my description of the service, please use the following link, <a href="https://www.getdropbox.com
eferrals/NTE1ODEyNjg5">https://www.getdropbox.com
eferrals/NTE1ODEyNjg5</a>, so that I can get a few additional MB of storage (and you too!).</p>











grsync

GTK+ frontend for rsync

simple graphical interface using GTK2 for the rsync command line program.

luckybackup includes also a GUI for chron





Things to try:

<li><a href="http://www.virtualbox.org/">VirtualBox</a>: x86 virtualization product under GNU GPL.</li>

<li><a href="http://audacity.sourceforge.net/">Audacity</a>: </li>

<li>pdftk (e <a href="http://www.paehl.de/pdf/gui_pdftk.html">guipdftk</a> o http://itextpdf.sourceforge.net/ o simili) [syntax to concatenate: "pdftk file1.pdf file2.pdf cat output newFile.pdf": more info here: http://linux.com/archive/feature/53701 OR http://www.accesspdf.com/pdftk/] </li>



<h2>Stuff (also) for Windows</h2>

<p>SSH client</p>

<a href="http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html">PuTTY</a>





<a href="https://federicomorando.net/en/tricks">Tips & Trics</a>





https://help.ubuntu.com/community/Drupal







rolldice

for instance, to roll 3d6 seeing all the separate results:

rolldice -s 3d6







<h3>Potentially useful proprietary stuff</h3>

http://www.gnurou.org/blog/2008/09/09/finally_real_pdf_annotating_under_linux<br>

<a href="http://www.docu-track.com/home/prod_user/PDF-XChange_Tools/pdfx_viewer">PDF-XChange Viewer</a><br />

(xournal is a nice software, but the output is not very portable...)




Nice tips&tricks
----------------

Per convertire una serie di immagini:

mkdir smaller

for img in `ls *.jpg`; do   convert -sample 50%x50% $img ./smaller/$img; done




* tiff2pdf

	tiff2pdf -o mail.pdf mail.tiff</p>





<p>epub readers: FBReader, calibre</p>



* inkskape is able to convert from bitmap from vector...
  To trace bitmap to vector, you may also try <http://vectormagic.com>, if you''re lazy.





<strong>fstab</strong>

	# /etc/fstab: static file system information.
	#
	# <file system> <mount point>   <type>  <options>       <dump>  <pass>
	proc /proc proc defaults 0 0
	# /dev/sda8
	UUID=02cede4a-2f08-43b1-a4ea-80bda57240be / ext3 nouser,relatime,errors=remount-ro,atime,auto,rw,dev,exec,suid 0 1
	# /dev/sda9
	UUID=24550b19-551c-4b62-a6bf-51a384a01937 none swap sw 0 0
	/dev/scd0 /media/cdrom0 udf,iso9660 user,utf8,atime,noauto,rw,dev,exec,suid 0 0
	
	/dev/sda2 /media/ACER auto nouser,atime,auto,ro,nodev,noexec,nosuid 0 0
	/dev/sda5 /home/muras/Disco_dati vfat user,fmask=0111,dmask=0000   0   0
	/dev/sda6 /home/muras/Documents auto users,atime,auto,rw,nodev,noexec,nosuid 0 0
	/dev/sda7 /media/BAK auto users,atime,auto,rw,nodev,noexec,nosuid 0 0

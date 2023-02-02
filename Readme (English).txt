What is MegaDownloader?
MegaDownloader is a download client for MEGA.CO.NZ, allowing you to easily download files from MEGA.CO.NZ

Is an official app?
It is a standalone unofficial application. Its use is free and there is no charge for using it or download it.

Why MegaDownloader?
* Fast: You can download multiple files simultaneously with multiple connections per file, squeezing the bandwidth.
* Lightweight: Takes up less than 2MB and consumes little resources. It doesn't create  giant temporary files. Just uses a small buffer in memory and stores the file directly in disk.
* Secure: MegaDownloader does not show ads or banners when using it. It doesn't collect information from user. Only connects to MEGA.CO.NZ to download the files, and periodically checks for updates. Nothing else. And sensitive internal information is stored locally encrypted using DPAPI and AES.
* Simple: Its interface is simple to use: add links and start downloading. That's all!
* Complete: It allows pausing, stopping and resuming file downloads. It enqueues files, grouping them by packages, automatically decompresses RAR/Zip/7z files, detects links from the clipboard, can limit the download speed, is multilingual, can be controlled from the phone / remotely with its integrated web server, can be configured to automatically start or shut down the PC when finish, can reconnect in case of error, etc. Ah, and you can watch videos online via streaming ;)


What requirements does it have?
You must use Windows XP SP3 or higher (Vista, Windows 7, Windows 8, etc) and have installed. NET 3.5 or higher.
It also works on Mac with Parallels, considering that you install. NET 3.5 or higher.

How does it decrypt files?
The decryption is made on the fly, while downloading, so no extra resources are used (RAM or disk).

How do I start downloading?
First you must start the program and wait for it to load.
Then you have to add links to download.
You can click on the "Add links" button, or copy them to the clipboard - MegaDownloader will detect them!
Then, just add one or more links and put them in the queue. 
Once in the queue, you might check the status:
- Stopped: Connections are closed and download is stopped.
- Downloading: The queue items are being downloaded in order.
- Paused: The connections are open but the files are not being downloaded. When it returns to the state 'Downloading' it will immediately start downloading.

How do I configure the program? There are many options!
You can use the default settings, without touching anything, to begin downloading. When the setup screen appears, click Yes, and that's all!
The only option you have to look a bit is the default download path (where the file is saved). The default path is Windows Desktop. If you do not specify a default path, you will have to enter it every time you download something.

How I can see the  remaining time?
By default, some columns are not shown. Right click on the column header of the list of downloads, select the columns to show or hide.

I can not change the size of the name column!
This column is automatically resized by the size of other columns. Therefore you should modify the other columns to resize the name column. This is done to avoid horizontal scrolling.

How I can translate the application into another language?
A more complete tutorial will be made soon. 
Basically you have to create a new file in the internal configuration path, under the Language directory, copying another file (it is recommended to use as a basis en-US.xml). You have to put the language code in the format ISO 639 + ISO 3166. Then you have to edit the XML and change, first, the code and name of the language, then the translation (keeping the 'id' attribute of each node). Ready!
Next time you start the program, you will be able to change the language from the configuration screen (if the language code is correct and exists).

The antivirus tells me MegaDownloader contains a virus or a Trojan!!
MegaDownloader is safe. It is compressed using MPRESS to minimize its size. Some viruses also use MPRESS so they are more difficult to detect; for that reason some antivirus mark as dangerous any compressed file in this way - a false positive!
You can use an HTTP sniffer like Fiddler to see what does MegaDownloader in the background, and check that apart from connecting with MEGA to download files and check the latest version, it doesn't make strange connections or send personal information of any kind.  
You can also download and examine the source code.
MegaDownloader is 100% secure.

Hmmm the English translation is not good...
English is not my first tongue so any correction is welcome!

Which license does MegaDownloader use?
The usage license is free, the program is provided "as is", there is no warranty or condition of any kind (express or implied).
Modification is not allowed. Its usage with profit purposes is not allowed. You can redistribute it freely, but only under the condition of not modifying it, and maintaining all its information (authors, acknowledgments, etc.). 
It is not allowed to redistribute it supplanting the authorship or removing information from the authors.
If you do not agree to this license, do not use the program.
This is a short summary, the program comes with a full license, please check it before use.

I love the app! How I can thank you?
Any comments are welcome (you can find my contact in the program under "Help / About"). Constructive criticism if welcome too (but not destructive). If you like to see a new feature implemented, tell me and see if I can develop it.
And you are more than welcome to make a donation using PayPal ;) http://goo.gl/17JQk
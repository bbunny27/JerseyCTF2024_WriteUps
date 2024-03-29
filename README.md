# JerseyCTF2024_WriteUps
<h4>My CTF team the Cyberhawks competed in the JerseyCTF this year. We had a really good time and learned a lot. I was out forensics specialist however the whole team helped out everywhere. The following are the write-ups of the challenges I solved.</h4>
<br>
<h4>Substitute-Detail-Torrent(Forensics)</h4>
<p>Challenge: We've been given a file and need to figure out what url it was downloaded from.</p><br>
<p>How I solved: This is an unfamiliar file type to me as it is a .wim file titled Blob.wim.</p>
<p>To start I tried to open is using my notepad on my host machine (windows 10). When you do this, you see the flag!</p>
<img src="https://github.com/bbunny27/JerseyCTF2024_WriteUps/assets/143891068/eca23141-9d6f-4c51-9e39-bd569b32579d">
<p>The flag is jctf{https://www.NTFS/File/Metadata}</p>
<br>
<h4>Groovy(Forensics)</h4>
<p>Challenge: You know you're getting old when you hear the music these kids are putting out and all you think is "no thank you."Anyway, I'm too old for this or maybe I need some cybernetic ears or something. Maybe you'll like these groovy tunes.</p>
<br>
<p>We get a file titled sick_jams_dude.wav that plays some seemingly home recorded music, with a weird beeping noise. After deciding that this isn't morse code, I put it into audacity to look for any weird patterns in the audio waves.</p>
<img src="https://github.com/bbunny27/JerseyCTF2024_WriteUps/blob/main/sickjamsaudacity.PNG">
<p>Hmm. Nothing weird, is there another view of the file?</p>
<img src"https://github.com/bbunny27/JerseyCTF2024_WriteUps/blob/main/sickjamsflag.PNG">
<p>Bingo! The flag is jctf{wav1ng_fr0m_th3_futur3}</p>
<h4>Rescue-Mission(Forensics)</h4>
<p>Challenge: Linux really lets you do anything... when messing around with my new install, I managed to delete my bootloader! Now I can't get in when I had an important file on my desktop... at least I virtualized it, maybe you can get the data out of it?</p>
<p>I definitely didn't do this one the intended way. However, I still think it's interesting. In this problem we get a .vdi file which acts as a virtual machine virtual disk. It has no bootloader, so we cannot boot into the virtual machine to access the files of the machine. However, if we attach it to an already existing virtual machine, we can view the files!</p>
<img src="https://github.com/bbunny27/JerseyCTF2024_WriteUps/assets/143891068/5d258b42-12ae-4850-bdb9-018138e82fbc">
<p>Lets load up my kali machine and give it a look!</p>
<img src="https://github.com/bbunny27/JerseyCTF2024_WriteUps/assets/143891068/9853b21c-3b36-4741-a826-c1853287bc27">
<p>I navigate to the desktop of the file system where I find this png. Looks Like I got it!</p>



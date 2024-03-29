# JerseyCTF2024_WriteUps
<h4>My CTF team the Cyberhawks competed in the JerseyCTF this year. We had a really good time and learned a lot. I was out forensics specialist however the whole team helped out everywhere. The following are the write-ups of the challenges I solved.</h4>
<br>
<h4>Substitute-Detail-Torrent(Forensics)</h4>
<p>Challenge: We've been given a file and need to figure out what url it was downloaded from.</p><br>
<p>How I solved: This is an unfamiliar file type to me as it is a .wim file titled Blob.wim.</p>
<p>To start I tried to open is using my notepad on my host machine (windows 10). When you do this, you see the flag!</p>
<img src="https://github.com/bbunny27/JerseyCTF2024_WriteUps/assets/143891068/eca23141-9d6f-4c51-9e39-bd569b32579d">
<p>jctf{https://www.NTFS/File/Metadata}</p>
<br>
<h4>Groovy(Forensics)</h4>
<p>Challenge: You know you're getting old when you hear the music these kids are putting out and all you think is "no thank you."Anyway, I'm too old for this or maybe I need some cybernetic ears or something. Maybe you'll like these groovy tunes.</p>
<br>
<p>We get a file titled sick_jams_dude.wav that plays some seemingly home recorded music, with a weird beeping noise. After deciding that this isn't morse code, I put it into audacity to look for any weird patterns in the audio waves.</p>
<img src="https://github.com/bbunny27/JerseyCTF2024_WriteUps/blob/main/sickjamsaudacity.PNG">
<p>Hmm. Nothing weird, is there a way t</p>

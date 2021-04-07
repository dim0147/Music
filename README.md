#Environment variable
 ##ffmpeg
	D:\SOFTWARE\yt-dl\ffmpeg\bin
 ##youtube-dl
	D:\SOFTWARE\yt-dl

#Command
 # Download with URL file(Enter each URL)
    youtube-dl -a=download.txt -o "Videos/%(title)s.%(ext)s"

 # Download
    youtube-dl --download-archive archive.txt -x --audio-format "mp3" -o "%(title)s.%(ext)s" "https://www.youtube.com/playlist?list=PLfHSQCX5CTGwk7XURGRFZX6cehtUT_Yez"
	
#Phone ZIP Download
https://codeload.github.com/dim0147/Music/zip/refs/heads/master

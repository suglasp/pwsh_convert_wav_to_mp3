
wave (*.wav) to *.mp3 sound converter
-------------------------------------

Used for the Fallout sfx conversion kit. See project https://github.com/suglasp/fallout4_fallout76_sfx_conversionkit .

This is a wrapper script that uses ffmpeg.exe behind the scenes to convert in bulk wave files to mp3.
You can target a folder, and the scripts will convert any wave file (also in subfolders) to a mp3.

Setup:
Download convert_wav_to_mp3.ps1 to a folder.
create a subfolder (in the same root folder where you put convert_wav_to_mp3.ps1) with the name "ffmpeg".
Download ffmpeg for Windows from https://ffmpeg.org/download.html#build-windows and extract to folder "ffmpeg".

Usage:
Start Powershell (works in Powershell 7 to on Windows).
Run .\convert_wav_to_mp3.ps1 -CustomDir <path_to_target_folder>

If a .wav file is seen, it will convert it to mp3 and place the new file next to the wav file.
In case a mp3 file with the same name as the wav file exists, the script will skip the file and notify you.

Pieter a.k.a. Suglasp

MoviePlayer sub gen and sub translate

Opens File, it autoamticly opens installed movieplayer that runs with python, pute it or let it play it opens any movie mkv mp4 etc, choose AI model small.en
Then Trnslate after AI: choose subtitle langue, you can choose all languges that Google translate provides.
It uses contex, that means if they speak instead of translate from word by word it batches and entire meaning and giving an more precise trasnlation
Press AI OFFICAL-STYLE SUBTITLES, now it takes 2-3 minutes and it have auto generated very precis subtitles also translate into your prefered languge

Thats it

Install

Download latest Python from,  https://www.python.org/downloads/  
choose prefred 32x/64x etc

Download
https://github.com/mpvnet-player/mpv.net/releases?utm_source=chatgpt.com choose mpv.net-x64-setup.exe

Download 
ffmpeg-git-essentials.7z from https://www.gyan.dev/ffmpeg/builds/?utm_source=chatgpt.com
extract ffmpeg.exe ffplay.exe ffprobe.exe into C:\FFMPEG

So create a folder in C: called FFMPEG and put all exes in there
add to path with included .bat files  a.bat b.bat c.bat
 
INSTALL VISUAL C++ RUNTIME
Download 
https://aka.ms/vs/17/release/vc_redist.x64.exe?utm_source=chatgpt.com


INSTALL CUDA (OPTIONAL BUT RECOMMENDED)

Your script has CUDA detection paths built in.

If you want GPU subtitle generation:

Download CUDA 12.1:

NVIDIA CUDA Toolkit 12.1

Install default settings.

Download
https://developer.nvidia.com/cuda-12-1-0-download-archive?utm_source=chatgpt.com

pip install in CMD
Open CMD
type/copy paste

Copy then righclick on CMD window to paste anything you have copied

pip install PyQt6 faster-whisper ctranslate2 huggingface_hub sentencepiece av numpy

pip uninstall torch -y
pip install torch --index-url https://download.pytorch.org/whl/cu121

pip install nvidia-cublas-cu12 nvidia-cudnn-cu12

pip install orjson
pip install pywin32

Open the script and play any file auto generated subtitle and translated into any suported languge by Google

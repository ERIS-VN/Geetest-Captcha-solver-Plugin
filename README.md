# Geetest-Captcha-solver-Plugin
A plugin for geetest captcha 

To use:

use pyinstaller to compile Gee.py into an exe.

use Ruri's Shell plugin to access it from OB.

Make sure to have ffmpeg.exe,ffplay.exe,ffprobe.exe in the same folder as Gee.exe

Example (LoliScript):

SHELL Gee.exe" "f2ae6cadcf7886856696502e1d55e00c https://www.ebay.com/distil_r_captcha_challenge" -> VAR "GeeResult" 

pass the gt token and url as arguments.

## USEFUL FFMPEG ONE LINERS
 ```
 $ ffmpeg -i # RETURNS FILE INFORMATION
 ```
### Ignore Angled Brackets(<>)
 ```
 $ ffmpeg -i <input.format> -c copy <output.format> # CONVERT INPUT FILE TO SPECIFIED
OUTPUT FORMAT
 ```
 ```
 $ ffmpeg -i <input.format> -acodec mp3 -vcodec copy <output.format> # CONVERT
AUDIO CODEC OF INPUT FILE TO SPECIFIED AUDIO CODEC
 ```

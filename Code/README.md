## COMMANDS TO RUN THE CODE

### To generate Text-based captcha -
/generate.py --width 128 --height 64 --length 4 --symbols symbols.txt --count 500  --output-dir training_data

### To generate Audio-based captcha -
/audioGenerate.py --length 4 --symbols symbols.txt --count 100000 --output-dir audio_data

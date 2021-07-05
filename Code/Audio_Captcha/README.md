## To generate Audio Captcha
python generate-audio-captcha.py --length 4 --symbols symbols.txt --count 3200 --output-dir training-images

## To train the model
python train.py --width 128 --height 64 --length 4 --symbols symbols.txt --batch-size 4 --epochs 2 --output-model first --train-dataset training_data --validate-dataset validation_data

## To make predictions
python classify.py  --model-name first --captcha-dir validation_data/ --output output.txt --symbols symbols.txt

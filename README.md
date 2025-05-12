# How to run this model?

0. (Optional) create your virtual enviornment
```bash
python3.10 -m venv venv
source venv/bin/activate
```

1. Install dependencies
```bash
pip install requirements.txt
git clone https://github.com/tensorflow/models.git
cd models/research/audioset/yamnet
# Download data file into same directory as code.
curl -O https://storage.googleapis.com/audioset/yamnet.h5
```

2. Run inference on your wav file (or something)
```bash
cd /Users/evaoffutt/Desktop/yamnet-working-real
python models/research/audioset/yamnet/inference.py 5_4_recording.wav
```
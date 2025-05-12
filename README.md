# How to run this model?

0. (Optional) create your virtual enviornment
```bash
python3.10 -m venv venv
source venv/bin/activate
```

1. Install dependencies
```bash
pip install requirements.txt
```

2. Run inference on your wav file (or something)
```bash
python models/research/audioset/yamnet/inference.py 5_4_recording.wav
```
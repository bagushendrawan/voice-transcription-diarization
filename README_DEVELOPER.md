# Developer Setup

## Install dependencies

```bash
conda create -n voice_transcribe python=3.11
conda activate voice_transcribe
pip install -c constraints.txt -r requirements.txt
```

Ensure `ffmpeg` is installed on the host before running the pipeline:

```bash
sudo apt install ffmpeg
```

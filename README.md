# 🧠 AI Image Enhancer using Real-ESRGAN

A Python-based image enhancement tool powered by [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) — upscale blurry, low-res photos into stunning HD in a single command.

---

## ✨ Features

- 📷 Enhance & upscale images using AI (Real-ESRGAN)
- 🖼️ Supports JPG, PNG, WebP
- ⚡ GPU acceleration (if available)
- 💾 Save enhanced images in a separate folder
- 🐍 Simple Python script, no UI fluff

---

## 🔧 Requirements

- Python 3.8+
- Pytorch + CUDA (for GPU)
- `real-esrgan` package or repo clone
- Pillow, OpenCV (optional for preview)

---

## 🚀 Installation

### 1. Clone Real-ESRGAN

```bash
git clone https://github.com/xinntao/Real-ESRGAN.git
cd Real-ESRGAN
pip install -r requirements.txt
python setup.py develop
```
### 2. Download pretrained model
```bash
python scripts/download_pretrained_models.py RealESRGAN_x4plus
```
### 3. Use your enhancer script
If your script is something like enhance.py, just run:
```bash
python enhance.py --input path/to/image.jpg --output results/
```
## 🧠 How It Works
Real-ESRGAN uses deep generative networks to restore lost image details — especially effective on:
- Old / low-res photos
- Anime / artwork
- Screenshots / compressed images


## 📁 Folder Structure
```bash
├── enhance.py
├── results/
├── inputs/
├── models/
└── README.md
```

##✍️ Author
Kartik Singh
📧 [14kartiksingh@gmail.com]
🌐 mistercoderz.com

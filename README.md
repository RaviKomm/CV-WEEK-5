# CV-WEEK-5
# Week 5 Assignment: Applications of Neural Networks for Vision Tasks

## 📌 Objective
This project explores advanced applications of deep learning in computer vision using PyTorch and Hugging Face. It covers:

- ✅ Image captioning using Recurrent Neural Networks (BLIP)
- ✅ Image captioning with attention using Transformer-based models (ViT-GPT2)
- ✅ Visualization with image gradients (saliency maps)
- ✅ Artistic style transfer using VGG-based perceptual loss

---

## 🛠️ Tools & Libraries Used

- **Python**
- **PyTorch** (`torch`, `torchvision`)
- **Transformers** (`transformers`, Hugging Face models)
- **OpenCV & Pillow**
- **Matplotlib** (for visualization)
- **Requests** (to fetch online images)

---

## 📂 File Structure

```
.
├── image_captioning.py         # RNN-based image captioning (BLIP)
├── attention_captioning.py     # Transformer + Attention-based captioning
├── image_gradients.py          # Saliency map visualization
├── style_transfer.py           # Neural style transfer using VGG19
├── README.md                   # Project overview and instructions
```

---

## 🧪 How to Run

### 1. Install Dependencies
```bash
pip install torch torchvision transformers matplotlib pillow requests
```

### 2. Run Any Script
Each script runs standalone. Just open and execute:
```bash
python image_captioning.py
```

---

## 📸 Sample Outputs

### 🖋️ Image Captioning
- **BLIP:** `"a dog lying on a rocky shore near mountains"`
- **ViT-GPT2:** `"a white dog laying by a mountain lake"`

### 🔥 Saliency Map
Visualizes which pixels influence the classification decision of a ResNet18 model.

### 🎨 Style Transfer
Applies Picasso-style brushstrokes to your photo using VGG19 features.

---

## 🚀 Credits
- Hugging Face for BLIP and ViT-GPT2 models
- PyTorch & TorchVision
- Open-source image resources (Unsplash, PyTorch tutorials)

---

## 🎥 Submission Instructions
- ✅ Push code to GitHub
- ✅ Export this project as `.zip`
- ✅ Record a short video walkthrough explaining each part

---

> Feel free to modify any section to reflect your screenshots, results, or captions. Happy presenting!

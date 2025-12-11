# Automated Food Identification & Calorie Estimation

This project uses a **Convolutional Neural Network (CNN)** to identify food from an image and estimate its calorie content.  
Instead of manually entering what you ate, a user can upload a picture and get:

- Predicted food type  
- Estimated calories for that image

The work was done as an academic project on applying deep learning to health and nutrition.

---

## 🔍 Motivation

Traditional calorie-tracking apps have a few problems:

- You have to **type everything** you eat.
- Portion sizes are often **guessed**, so numbers are unreliable.
- The process is slow, so most people stop using the app.

The idea here is simple:

> **Take a photo → model recognises the food → model estimates calories.**

---

## 🧠 System Overview

The pipeline is broken into these blocks:

1. **User uploads food image**
2. **Pre-processing**
   - Resize, normalize, optionally augment
3. **Deep Learning Model**
   - Image acquisition  
   - Food recognition  
   - Food detection / segmentation (conceptual)  
   - Food weight / portion recognition
4. **Estimation**
   - Map prediction + features to a calorie estimate

> Make sure this image is saved as `images/system_architecture.png`.

![System architecture – deep learning pipeline](images/system_architecture.png)

---

## 📂 Repository Structure

```text
.
├─ Amlproject_food_and_calorie.ipynb   # Jupyter notebook with full workflow
├─ Presentation.pptx                   # Project presentation
├─ images/
│  ├─ output_cabbage.png              # Cabbage prediction screenshot
│  ├─ output_eggplant.png             # Eggplant prediction screenshot
│  └─ system_architecture.png         # Architecture diagram
└─ README.md




---

### Quick checklist for you

1. Create `images/` folder in the repo.
2. Save your three screenshots as:
   - `images/output_cabbage.png`
   - `images/output_eggplant.png`
   - `images/system_architecture.png`
3. Add this `README.md`.
4. Commit + push.

If you want, send me your GitHub repo link after pushing and I can suggest a short, human project description for the repo as well.

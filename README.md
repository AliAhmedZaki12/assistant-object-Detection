#  Intelligent Object Detection & Arabic Voice Description

A smart vision system that detects objects in images, generates descriptive text, translates it into Arabic, and produces real-time Arabic speech output. The project combines advanced object detection, neural translation, and text-to-speech models into a unified interactive interface powered by **Gradio**.

---

##  Features

* High-accuracy object detection using **DETR ResNet-101**.
* Automatic description generation based on detected objects.
* English-to-Arabic translation using **OPUS-MT** models.
* Arabic text-to-speech powered by **MMS-TTS**.
* Clean interactive UI with image upload or URL input.
* Real-time visualization with bounding-boxes and detailed outputs.

---

## 🛠️ Tech Stack

* **Python**
* **Hugging Face Transformers**
* **DETR (facebook/detr-resnet-101)**
* **OPUS-MT Translation (Helsinki-NLP)**
* **MMS TTS Arabic (facebook/mms-tts-ara)**
* **Gradio UI**
* **PIL / Matplotlib / NumPy**

---

## 📦 Installation

```bash
pip install transformers gradio timm inflect pillow requests matplotlib numpy
```

---

## 🖼️ How It Works

1. Load image from upload or URL.
2. Run DETR object detection.
3. Filter predictions based on confidence threshold.
4. Draw bounding boxes on the image.
5. Generate an English textual description.
6. Translate it to Arabic.
7. Convert Arabic text into speech.
8. Display all results in the Gradio interface.

---




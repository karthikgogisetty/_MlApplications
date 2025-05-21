### For: YOLOv8 & Explainability Notebooks

```markdown
# 📸 YOLOv8 & Explainability Study

This folder contains exploratory notebooks focused on computer vision model behavior — particularly using YOLOv8 for object detection and applying interpretability tools like Grad-CAM or SHAP to understand what the model "sees."

---

## 📄 Contents

| File                     | Description |
|-------------------------|-------------|
| `yolov8_exp.ipynb`      | Runs YOLOv8 object detection on sample images. Includes inference visualization and optional confidence threshold tuning. |
| `yolo_explainability.ipynb` | Applies visual explanation techniques (Grad-CAM, SHAP overlays, etc.) on YOLOv8 predictions to demystify the model's decision-making. |

---

## 🧠 Concepts Covered

- Object detection with pretrained YOLOv8 (via Ultralytics)
- Custom image input and bounding box rendering
- Grad-CAM overlays on detected objects
- SHAP-based interpretability (image classification-focused)
- Discussion on feature importance and model trustworthiness

---

## 🚀 To Run

Install required dependencies:

```bash
pip install ultralytics opencv-python matplotlib shap
```
## 🎯 Project Overview

- **Drone Platform**: Hexacopter with Raspberry Pi 4B
- **Camera**: Arducam 64MP 
- **Flight Height**: 2 meters above ground
- **Detection Target**: Landmines in various terrain conditions
- **Model**: YOLOv8 optimized for aerial imagery

## 📁 Project Structure

```
yolo_dataset/
├── data/                      
│   ├── train/
│   ├── val/
│   └── test/
```

## 📊 Dataset Information

- **Total Images**: 268 labeled images
- **Classes**: 1 (landmine)
- **Format**: YOLO (normalized bounding boxes)
- **Train/Val/Test Split**: 70%/20%/10%

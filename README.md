# 🎣 Fish Species Detection with YOLOv5  

Detect various fish species in dynamic aquatic environments using **YOLOv5**. This project helps in ecological monitoring and sustainable marine resource management.  

---

## 💡 Project Idea  
- Real-time detection of multiple fish species.  
- Behavior analysis without human intervention.  
- Support for marine biodiversity research.  

---

## 🧰 Technologies Used  
- **YOLOv5** (Object Detection)  
- **PyTorch** (Model Training)  
- **Roboflow** (Image Annotation)  
- **OpenCV**, **NumPy**, **Pandas** (Data Processing)  

---

## ✅ Prerequisites  
- Python 3.7+  
- GPU (optional but recommended)  
- Required Libraries: `PyTorch`, `OpenCV`, `NumPy`, `Pandas`, `Matplotlib`, `Tqdm`  

---

## 🚀 Installation  
```bash
# Clone the repository  
git clone https://github.com/your-username/FishSpeciesDetection-YOLOv5.git  
cd FishSpeciesDetection-YOLOv5  

# Install dependencies  
pip install -r requirements.txt

## 🏋️ Training the Model  
To train the YOLOv5 model on your custom fish species dataset:  
```bash
python train.py --img 640 --batch 16 --epochs 100 --data data.yaml --cfg models/yolov5s.yaml --weights yolov5s.pt --name fish_detection



📊 Monitoring Training with TensorBoard
To monitor the training process, launch TensorBoard to visualize training metrics:

bash
Copy
Edit
# Launch TensorBoard  
tensorboard --logdir runs/train/fish_detection

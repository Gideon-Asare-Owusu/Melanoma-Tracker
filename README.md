# Melanoma Detection and Tracking 
This project detects melanoma cells captured by a Prophesee neuromorphic camera using background subtraction and contour detection. A customized centroid tracking algorithm tracks detected cells, addressing key challenges in medical imaging, including cell splitting, disappearance and reappearance, and merging followed by later separation.

---

## Features  
- Detects melanoma cells in microscopy video frames  
- Tracks cell movement using a centroid tracking algorithm  
- Handles cell splitting, merging, and reappearance  
- Processes videos from a Prophesee neuromorphic camera  
- Generates an output video with detected cells and tracking IDs

- Detects melanoma cells in microscopy video frames.  
- Tracks cell movement using a centroid tracking algorithm.  
- Handles cell splitting, merging, and reappearance.  
- Processes videos from a Prophesee neuromorphic camera.  
- Generates an output video with detected cells and tracking IDs.  

 
## Demo  
🔗 [Watch the Demo](https://github.com/Gideon-Asare-Owusu/Melonama-Tracker/blob/main/Examples/H-Stacked%20Video.mp4)  


### Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Gideon-Asare-Owusu/Melanoma-Tracker.git
cd Melanoma-Tracker
```

### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```
### 3️⃣ Run Code Locally (Jupyter Notebook) 
```bash
jupyter notebook
```
Note: Ensure that your environment has all the required dependencies as listed in requirements.txt. If you face issues, check the Python version or any OS-specific dependencies.

## Project Structure  
```bash
Melanoma-Tracker/  
│── ML-Melanoma.ipynb               # Main processing notebook  
│── tracker.py                      # Object tracking module  
│── centroidtracker.py              # Centroid tracking helper  
│── ML-Melanoma.avi                 # Sample input video  
│── ML-Melanoma Output.mp4          # Processed output video  
│── requirements.txt                # List of dependencies  
│── README.md                       # Documentation  
```

## Contact  
For inquiries, reach out to:  
📧 **Email:** [asaresonjunior@gmail.com]  
🔗 **LinkedIn:** [Gideon Asare Owusu]  


# **CNN model for helping self-driving vehicles identify and follow traffic rules.**

**It works in the following way.
Convolutional Neural Network to teach the traffic symbols (images ) to the model.
After learning, it uses vision to detect symbols and identify if they are traffic symbols that must be followed as per law.


---

## **Getting Started**

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/AdityaAVG/CNN_for_self_driving.git
    ```
2. **Navigate to the Project Directory**:
    ```bash
    cd CNN_for_self_driving
    ```
3. **Set Up a Virtual Environment** (recommended to avoid dependency issues):
    #### **For Linux and macOS**:
```bash
python3 -m venv venv
source venv/bin/activate
```
### For windows
```bash
venv\Scripts\activate
```
4. **Install the Required Libraries**:
    ```bash
  pip install numpy pandas matplotlib torch pillow torchvision
    ```
5. **Run the Application**:

## **Running on Google Colab**

To run this project on Google Colab, follow these steps:

### **Step 1: Open Google Colab**
1. Go to [Google Colab](https://colab.research.google.com/).
2. Sign in with your Google account.

### **Step 2: Clone the GitHub Repository**
In a new Colab notebook, run the following command to clone the repository:

```python
!git clone https://github.com/AdityaAVG/CNN_for_self_driving.git
```

### **Step 3: Navigate to the repository**
```python
import os
os.chdir('/content/voice_doc')
```
#Install dependencies
```bash
!pip install numpy pandas matplotlib torch pillow torchvision
```
#Run



---

## **Tech Stack**

- **Python**: Core language for data processing and application building.
- **Torch-vision**: For Computer Vison  
- **Pandas**: Handles data manipulation and feature storage.
- **Matplotlib**: Used for visualizing the date like printing image in RGB or grey scale.
- **Gradio**: Provides an interactive user interface to record and process audio.
- **PyTorch**: Imported for potential future deep learning models.

---

---

## **Dataset**

The dataset used for training is the gtsrb-german-traffic-sign, which contains traffic signal images in the Test and Train folder. You can find it on Kaggle.

---

## **Future Improvements**
Improve the scope of the model by providing and training it on more data. Also, make the model smart enough to think and decide on traffic signals. One such possibility is using the OpenAI O1 model to do so.

---
## **Reference for Dataset**

/kaggle/input/gtsrb-german-traffic-sign](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

## **Contributing**

Contributions are welcome! Please fork this repository and submit a pull request if you'd like to improve the project. Or just reach out to me for collaborating and try to improve it. Scope for improvement is always there.

---

## **License**

This project is licensed under the Apache License.

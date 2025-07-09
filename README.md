# Advanced Machine Learning [22AML154]

This repository contains my personal learning and implementation practice for **Advanced Machine Learning** laboratory experiments.

---

## 📚 Reference Material

This work is based on the open-source repository by Aurélien Géron:  
🔗 [Hands-On Machine Learning 3rd Edition](https://github.com/ageron/handson-ml3)

Some implementations have been adapted and simplified for individual exploration and better understanding during self-study.

---

## ⚙️ Setup Instructions

To run the experiments, use the **Anaconda Data Science platform** for smooth package management.

### 📦 Required Packages

#### 🔧 Keras Tuner
- Conda:
  ```bash
  conda install conda-forge::keras-tuner
Pip:

bash
Copy
Edit
pip install keras-tuner
🔧 TensorFlow
Conda:

bash
Copy
Edit
conda install conda-forge::tensorflow
Pip:

bash
Copy
Edit
pip install tensorflow
🔧 TensorBoard
Conda:

bash
Copy
Edit
conda install conda-forge::tensorboard
Pip:

bash
Copy
Edit
pip install tensorboard
🧪 Using TensorBoard in Jupyter Notebook
After installation, load TensorBoard directly in the notebook:

python
Copy
Edit
%load_ext tensorboard
%tensorboard --logdir <logdir>
💡 Alternative Way (If inline loading doesn't work)
Open Command Prompt and run:

bash
Copy
Edit
pip show tensorboard
Copy the Location: path and append:

bash
Copy
Edit
/tensorboard/main.py
Run the full command:

bash
Copy
Edit
python <copied_location>/tensorboard/main.py --logdir <logdir>
Open the generated TensorBoard URL in your browser.

✍️ Notes
This project is part of my learning journey in AIML, and is meant to enhance my understanding of:

Hyperparameter tuning

Deep learning workflows

Model evaluation & visualization

Real-time logging with TensorBoard

🙋‍♀️ Author
Deekshitha Bhairav
Beginner AIML Engineer & ML Enthusiast 🌱
📍3nd Semester, B.E. AIML  
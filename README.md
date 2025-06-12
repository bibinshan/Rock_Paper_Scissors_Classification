


## 📘 `README.md` for GitHub

```markdown
# 🧠 Rock Paper Scissors Classification Web App

A simple Flask web application that serves a trained deep learning model to classify images as rock, paper, or scissors. Built with TensorFlow, Flask, and HTML.

---

## 🚀 Features

- ✅ Image classification using a trained CNN model
- ✅ Flask-based backend
- ✅ Simple web frontend (`index.html`)
- ✅ Ready for deployment

---

## 📁 Project Structure

```

rock\_paper\_scissors/
│
├── app.py              # Flask application
├── templates/
│   └── index.html      # Web UI template
├── static/             # (optional) CSS/JS files
├── model/
│   └── model.h5        # Trained model (not pushed to GitHub)
├── RPC.ipynb           # Model training notebook
├── requirements.txt    # Required Python packages
└── README.md           # Project documentation

````

---

## 🔧 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
````

### 2. Create virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Flask app

```bash
python app.py
```

Then open your browser at:

```
http://127.0.0.1:5000/
```

---

## 🧠 Model

The model was trained using a CNN to classify hand gesture images (rock, paper, scissors). See [`RPC.ipynb`](RPC.ipynb) for training details.

> ⚠️ The `.h5` model file is not pushed to GitHub due to size limits. You may need to place it in the correct directory if your app uses it.

---

## 📦 Dependencies

Make sure the following packages are installed (included in `requirements.txt`):

* Flask
* TensorFlow
* Pillow
* NumPy

Generate this file by running:

```bash
pip freeze > requirements.txt
```

---


## 🤝 Contributions

Pull requests are welcome! Feel free to open an issue or submit a feature request.

---


## 📬 Contact

Made with ❤️ by [Bibin Shan Puthuvana](https://github.com/bibinshan)

```


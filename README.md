# 🖋️ Pentograph Demo

## 📖 Project Overview

Welcome to the **Pentograph Demo**! This project demonstrates how to leverage machine learning models for specialized tasks. Inside, you'll find a Jupyter notebook that walks through the process of using a pre-trained model (`best.pt`) to make predictions.

## 🛠️ Installation Instructions

Follow these steps to set up the project on your local machine:

1. **📥 Clone the Repository:**

   ```bash
   git clone https://github.com/aj-das-research/pentograph_demo.git
   cd pentograph_demo
   ```

2. **📦 Install Dependencies:**

   Make sure you have Python 3.7+ installed. Then, install the necessary packages:

   ```bash
   pip install -r requirements.txt
   ```

   If a `requirements.txt` file isn't provided, install the dependencies manually.

3. **🔍 Download or Prepare the Model:**

   The `best.pt` model file is already included. If you need to train or update the model, ensure it’s saved with the correct name in the root directory.

## 🚀 Usage Guide

The primary demonstration is in the Jupyter notebook `pentograph_demo.ipynb`. To get started:

1. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

2. **Open and Run the Notebook:**

   Navigate to `pentograph_demo.ipynb` in your browser and follow the steps to load the model and make predictions.

## 🧠 Model Information

The `best.pt` file is a pre-trained PyTorch model designed for this demo. You can load and use it with the following code snippet:

```python
import torch

model = torch.load('best.pt')
model.eval()
```

More details and usage examples are provided in the `pentograph_demo.ipynb` notebook.

## 📋 Dependencies

The project depends on the following key packages:

- 🐍 Python 3.7+
- 🔥 PyTorch
- 📓 Jupyter Notebook

You may need additional packages depending on the notebook's content.

## 📜 License

This project is licensed under the MIT License. For more details, see the [LICENSE](LICENSE) file.

## 🤝 Contributing

We welcome contributions! If you'd like to help improve this project, please fork the repository and submit a pull request with your changes.

## 📧 Contact Information

For questions or support, feel free to reach out:

- **Name**: Abhijit Das
- **Email**: [aj.das.research@gmail.com](mailto:aj.das.research@gmail.com)
- **GitHub**: [aj-das-research](https://github.com/aj-das-research)

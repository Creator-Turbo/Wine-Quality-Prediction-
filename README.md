# Wine Quality Prediction

### Table of Contents
- [Demo](#demo)
- [Overview](#overview)
- [Motivation](#motivation)
- [Technical Aspect](#technical-aspect)
- [Installation](#installation)
- [Run](#run)
- [Directory Tree](#directory-tree)
- [To Do](#to-do)
- [Bug / Feature Request](#bug--feature-request)
- [Technologies Used](#technologies-used)
- [Team](#team)
- [License](#license)
- [Credits](#credits)

---
## Demo
This project predicts the quality of wine based on its physicochemical properties using machine learning models.<br>
**Link to Demo:** [comming-soon](#) 





![Wine Quality Prediction](https://datamagiclab.com/wp-content/uploads/2023/08/red-wine-quality-prediction.webp)

---

## Overview
The Wine Quality Prediction project applies machine learning techniques to classify wine quality based on chemical attributes. The dataset consists of various physicochemical properties of wine samples, such as acidity, alcohol content, and density, which are used to predict their quality.

Key Features:

- Uses Supervised Machine Learning for classification.

- Exploratory Data Analysis (EDA) to understand wine properties.

- Hyperparameter tuning to improve model accuracy.
---

## Motivation

Wine quality assessment is traditionally performed by expert tasters, making it subjective and time-consuming. The aim of this project is to automate the quality evaluation process using machine learning techniques, ensuring consistency and efficiency.


---

## Technical Aspect

### Data Processing & Feature Engineering

Pandas & NumPy for data manipulation.

 Seaborn & Matplotlib for visualization.


2️⃣ Model Training & Evaluation

- Scikit-Learn for implementing ML models.

- Random Forest, Decision Tree, SVM, and Logistic Regression.

- Hyperparameter tuning using GridSearchCV.

3️⃣ Backend & Web Framework

- Flask – Web API for wine quality prediction.

- FastAPI (Planned) – Future upgrade for performance.

4️⃣ Frontend

- HTML + CSS + JavaScript – Web-based UI.

- Streamlit (Planned) – Interactive UI for real-time predictions.



---

## Installation
The Code is written in Python 3.10. Install the required packages and libraries by running:

```bash
pip install -r requirements.txt
```

## Run
To run the Flask web app locally:

```bash
python app.py
```


## Directory Tree 
```
📂 project-root
├── 📂 .gthub
├── 📂 config
├── 📂 research
├── 📂 src
├── 📂 static
├── 📂 templates
├── 📄 .gitignore
├── 📄 app.py
├── 📄 Dockerfile
├── 📄 LICENSE
├── 📄 main.py
├── 📄 params.yaml
├── 📄 README.md
├── 📄 requirements.txt
├── 📄 schema.yaml
├── 📄 setup.py
└── 📄 template.py
```

## To Do

- Enhance feature engineering techniques.

- Improve model accuracy with advanced algorithms.

- Deploy the project on a server for real-time use.


## Bug / Feature Request
If you encounter any bugs or want to request a new feature, please open an issue on GitHub. Contributions are welcome!

## Technologies Used
- Python 3.10 🐍 – Core programming language
- Scikit-Learn 🤖 – ML model training & evaluation
- Pandas & NumPy 📊 – Data manipulation
- Matplotlib & Seaborn 📈 – Data visualization
- Flask 🧩 – Web framework for building the chatbot API
- HTML 🖥️ – Structure for the chatbot's user interface
- CSS 🎨 – Styling for an enhanced user experience
- JavaScript ⚡ – Interactive and dynamic UI functionality






![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/260px-Scikit_learn_logo_small.svg.png" width=170>](https://scikit-learn.org/stable/)
[<img target="_blank" src="https://miro.medium.com/v2/resize:fit:720/format:webp/0*RWkQ0Fziw792xa0S" width=170>](https://pandas.pydata.org/docs/)
[<img target="_blank" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSDzf1RMK1iHKjAswDiqbFB8f3by6mLO89eir-Q4LJioPuq9yOrhvpw2d3Ms1u8NLlzsMQ&usqp=CAU" width=250 height="166">](https://matplotlib.org/stable/index.html) 

[<img target="_blank" src="https://icon2.cleanpng.com/20180829/okc/kisspng-flask-python-web-framework-representational-state-flask-stickker-1713946755581.webp" width=170>](https://flask.palletsprojects.com/en/stable/) 
[<img target="_blank" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQEc9A_S6BPxCDRp5WjMFEfXrpCu1ya2OO-Lw&s" width=170>](https://developer.mozilla.org/en-US/docs/Web/HTML) 
[<img target="_blank" src="https://cdn-icons-png.flaticon.com/512/919/919826.png" width=170>](https://developer.mozilla.org/en-US/docs/Web/CSS) 



---

## Team
This project was developed by:
[![Bablu kumar pandey](https://github.com/Creator-Turbo/images-/blob/main/resized_image.png?raw=true)](ressume_link) |
-|

**Bablu Kumar Pandey**

- [GitHub](https://github.com/Creator-Turbo)  
- [LinkedIn](https://www.linkedin.com/in/bablu-kumar-pandey-313764286/)
- **Personal Website**: [My Portfolio](https://creator-turbo.github.io/Creator-Turbo-Portfolio-website/)

## License

This project is licensed under the [MIT License](LICENSE).

You are free to use, modify, and distribute this software under the terms of the MIT License. For more details, see the [LICENSE](LICENSE) file included in this repository.

## Credits

Special thanks to the contributors of open-source machine learning frameworks and datasets that made this project possible.

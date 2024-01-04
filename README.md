# Heart Stroke Classification_Machine Learning

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![Build Status](https://travis-ci.org/upymake/enforce-pep8.svg?branch=master)](https://travis-ci.org/upymake/enforce-pep8)
[![PEP8](https://img.shields.io/badge/code%20style-pep8-green.svg)](https://www.python.org/dev/peps/pep-0008/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE.md)  

[![EO principles respected here](https://www.elegantobjects.org/badge.svg)](https://www.elegantobjects.org)
[![PyPI version shields.io](https://img.shields.io/pypi/v/enforce-pep8.svg)](https://pypi.python.org/pypi/enforce-pep8/)
[![PyPI pyversions](https://img.shields.io/pypi/pyversions/enforce-pep8.svg)](https://pypi.python.org/pypi/enforce-pep8/)
[![CodeFactor](https://www.codefactor.io/repository/github/upymake/enforce-pep8/badge)](https://www.codefactor.io/repository/github/upymake/enforce-pep8)
[![PyPi downloads](https://img.shields.io/pypi/dm/enforce-pep8.svg)](https://pypi.python.org/pypi/enforce-pep8)
[![Downloads](https://pepy.tech/badge/enforce-pep8)](https://pepy.tech/project/enforce-pep8)

</br></br>
Heart Stroke classification using Machine learning, is very basic classification problem which helps understand basic concept of Machine Learning for beginners. </br></br>
Independent variables for classification are as follows:</br>

* Age
* Glucose
* BMI
* Others

Algorithm used for classify the type of flowers are:

- Dicision tree classifier
- K nearest classifier
- SVM
- Logistic Regression

## Requirement

To install this package, [python3](https://www.python.org/), [pip](https://pypi.org/project/pip/), and [virtual environment](https://docs.python.org/3/library/venv.html) are required.

For Windows users: </br>
[Install python3 and pip](https://phoenixnap.com/kb/how-to-install-python-3-windows)</br>
[Install virtual environment](https://programwithus.com/learn-to-code/Pip-and-virtualenv-on-Windows/)

For Linux users:

```
sudo apt-get update
sudo apt-get install python python3-pip
sudo pip3 install stroke_env
```

## Installation

Navigate to the cloned directory.

```bash
cd heartstroke_classification
```

Create [virtual environment](https://docs.python.org/3/tutorial/venv.html) for Python.

```bash
python -m venv tutorial-env
```

For Linux users:

```bash
python3 -m venv tutorial-env
```

Here, **tutorial-env** is the name of the virtual environment, you can name it as you like.

Activate virtual environment by the following command: </br>
To activate on windows:

```bash
Scripts\activate
```

On Linux based on OS:

```bash
. tutorial-env/bin/activate
```

Install pip packages from requirements.txt

```bash
pip install -r requirements.txt
```

## Run

On Windows run:

```bash
python app.py
```

On Linux run:

```bash
python3 app.py
```

## Data Set

The dataset is downloaded from [stroke Data Set.](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://github.com/Vaaceph/iris-flower-classification/blob/master/LICENSE.md)
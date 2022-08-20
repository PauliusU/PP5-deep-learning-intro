# PP5 deep learning

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PauliusU/PP5-deep-learning-intro/blob/master/PP5_deep_learning_intro.ipynb)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/PauliusU/PP5-deep-learning-intro/blob/master/LICENSE)

Practical Project 4 (PP4) for Artificial Intelligence studies to solidify **deep learning** basics by practicing.

## Usage

### Automatic launch

1. To run in browser click on [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PauliusU/PP5-deep-learning-intro/blob/master/PP5_deep_learning_intro.ipynb) badge.
2. (Or) To launch locally on Windows just **run automatic setup script** in `Git Bash`:

```bash
bash <(curl -s https://raw.githubusercontent.com/PauliusU/PP5-deep-learning-intro/master/setup.sh)
```

### Manual launch

1. Clone this repo:

```bash
git clone https://github.com/PauliusU/PP5-deep-learning-intro.git
```

2. Navigate into project:

```bash
cd PP5-deep-learning-intro/
```

3. Ensure pipenv is installed:

```bash
pip install --upgrade pipenv --user
```

4. Install dependencies:

```bash
pipenv install
```

5. Run project:

```bash
pipenv run jupyter notebook PP5_deep_learning_intro.ipynb
```

## Requirements

- [ ] Find whichever dataset you want for polynomial multiple regression or non-linearly separable classification (you can use/generate the same scikit/python dataset or find real one).
- [ ] Train & tune a deep neural network using two frameworks (choose from TF/keras, pytorch, fast.ai).
- [ ] Describe in a few sentences (not fewer than 5) which framework you liked best and why.
- [ ] Provide the results as a collab notebook or github link with notebook for easy verification.

Bonus: Include decision boundary / regression line plotting.


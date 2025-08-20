# CS 5324 - Machine Learning In Python

This repository contains all of my coursework, projects, and notes for **CS 5324: Machine Learning in Python**.
This repo will store my progress throughout the semester, including assignments, hands-on coding exercises, and larger projects.

---

## How To Use

### 1. Build the Docker Image

Use the following command to build docker image:

```bash
docker build -t cs5324 .
```


### 2. Start The Container

Use the following command to start the container:

```bash
docker run --rm -it -p 8888:8888 -v "$PWD":/workspace cs5324
```


### 3. Accessing The Notebook

Open the link `http://127.0.0.1:8888/?token=...` in a browser. This opens the frontend of the jupyter server created by the container. You can now simply use jupyter notebooks as if it ran on your own machine.


### 4. Stopping The Container



----

## Repository Structure  

```bash
CS5324-Machine-Learning/
├── assignments/
├── projects/
├── notes/
├── datasets/
└── utils/
```

## Topics Covered

- Table Data & Visualization
- Dimensionality & Images
- Linear Classification
- Basic Neural Networks
- Deep Learning Basics
- Convolutional Neural Networks
- Sequential Networks

## Tech Stack

- Language: Python3
- Libraries: NumPy, Pandas, Matplotlib, Scikit-Learn, Seaborn, TensorFlow
- Tools: Jupyter Notebook, Docker, Github


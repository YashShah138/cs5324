# CS 5324 - Machine Learning In Python

This repository contains all of my coursework, projects, and notes for **CS 5324: Machine Learning in Python**.
This repo will store my progress throughout the semester, including assignments, hands-on coding exercises, and larger projects.

---

## How To Use

### 1. Build the Docker Image

Build the image (from the repo root, where the Dockerfile and docker-compose.yml are located):

```bash
docker compose build
```


### 2. Start The Container

Start Jupyter with:

```bash
docker compose up
```

This will:

- Map port 8888 in the container to localhost:8888
- Mount your project repo (cs5324/) into /workspace inside the container
- Start Jupyter Notebook with `/workspace` as its root, so you’ll see:

```bash
assignments/
projects/
notes/
datasets/
```


### 3. Accessing The Notebook

After startup, the terminal will print a URL like: `http://127.0.0.1:8888/?token=...`.

Open it in your browser. You can now create and run your notebooks.


### 4. Stopping The Container

To stop Jupyter:

- Hit `ctrl + c` in the terminal running `docker compose up`, then run: 
  - `docker compose down`


### 5. Restarting The Container
To restart the container, just run the following command:

```bash
docker compose up
```

The notebooks, data, and code are stored on your host machine (cs5324/) and will persist between runs.


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

1. Table Data & Visualization
2. Dimensionality & Images
3. Linear Classification
4. Basic Neural Networks
5. Deep Learning Basics
6. Convolutional Neural Networks
7. Sequential Networks

## Tech Stack

- Language: Python3
- Libraries: NumPy, Pandas, Matplotlib, Scikit-Learn, Seaborn, TensorFlow
- Tools: Jupyter Notebook, Docker, Github


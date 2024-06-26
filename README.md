# Quickstart Guide

Download the train dataset from [here](https://www.kaggle.com/datasets/oddrationale/mnist-in-csv?select=mnist_train.csv).

## Step 1

Once cloned place the .csv into the datasets folder.

```bash
git clone https://github.com/Seena-02/ScratchNN-MNIST
```

## Step 2

We will primarily use [anaconda](https://www.anaconda.com/download) to manage all packages and dependencies. Create a new conda environment and activate it by running the following commands

```bash
# Create Anaconda Env
conda create -n "mnist-nn"

# Activate Env
conda activate mnist-nn
```

## Step 3

Install the following dependencies.

```bash
# Install Dependencies
bash requirements.sh
```

## Step 4

Run it from inside src folder!

```bash
pyhton3 main.py
```

## The Math

![notes](assets/nn.png)
Recreated from [here](https://www.youtube.com/watch?v=w8yWXqWQYmU&t=732s).

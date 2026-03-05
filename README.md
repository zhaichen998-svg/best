# Installation Instructions for Windows + CUDA (GTX 1650 4GB) and PyCharm

## Step 1: Create a Virtual Environment
Use the following command to create a virtual environment:
```
pip install virtualenv
virtualenv venv
```

## Step 2: Activate the Virtual Environment
On Windows, activate the virtual environment using:
```
venv\Scripts\activate
```

## Step 3: Install PyTorch
Visit the [official PyTorch selector](https://pytorch.org/get-started/locally/) to get the correct installation command for your system configuration. You can use the following example command:
```
pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu102
```

## Step 4: Install Other Dependencies
Install the remaining requirements using:
```
pip install -r requirements.txt
```

## Step 5: Set Configuration Paths
Ensure that you set the correct configuration paths for your project.

## Step 6: Run the Training Script
You can start training by running:
```
python train.py --config configs/default.yaml
```

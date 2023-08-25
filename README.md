# Anti-Spoof Face Recognition Based Attendance System

PYTHON=3.10.12

This repository contains the code and resources for an Anti-Spoof Face Recognition Attendance System. The system uses computer vision techniques to prevent spoofing attempts during face recognition, ensuring the accuracy and security of attendance records.

## Features

- Real-time face recognition using the `face-recognition` Python library.
- Integration of the Silent Face Anti-Spoofing model for enhanced security.
- User-friendly graphical user interface (GUI) created using the `tkinter` library.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Running the System](#running-the-system)
  - [Adding New Users](#adding-new-users)
  - [Generating Reports](#generating-reports)

## Getting Started

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/junaid-o/CV-11-AttendanceSytsem_AntiSpoofing.git
   cd CV-11-AttendanceSytsem_AntiSpoofing
   ```

2. [Silent-Face-Anti-Spoofing](https://github.com/minivision-ai/Silent-Face-Anti-Spoofing) model weights and other resources are already present in the above reposioy you need not to clone it separately.

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Running the System

1. Navigate to the project directory.

2. Run the main application:

   ```bash
   python main.py
   ```

### Adding New Users

- From Tkinter app window click on `Register User`

### Generating Reports

- A log file be automatically generated about the logins and logout

```
CV-11-AttendanceSytsem_AntiSpoofing
├─ .git
├─ .gitignore
├─ LICENSE
├─ log.txt
├─ main.py
├─ README.md
├─ requiremets.txt
├─ saved_logs
│  ├─ jobs
│  │  └─ Anti_Spoofing_1_80x80
│  │     └─ Aug25_14-04-55
│  └─ snapshot
│     └─ Anti_Spoofing_1_80x80
├─ Silent-Face-Anti-Spoofing-master
│  ├─ datasets
│  │  └─ README.md
│  ├─ images
│  │  ├─ demo.gif
│  │  ├─ framework.jpg
│  │  ├─ logo.jpg
│  │  ├─ patch_demo.png
│  │  ├─ sample
│  ├─ my_test.py
│  ├─ README.md
│  ├─ README_EN.md
│  ├─ requirements.txt
│  ├─ resources
│  │  ├─ anti_spoof_models
│  │  │  ├─ 2.7_80x80_MiniFASNetV2.pth
│  │  │  └─ 4_0_0_80x80_MiniFASNetV1SE.pth
│  │  └─ detection_model
│  │     ├─ deploy.prototxt
│  │     └─ Widerface-RetinaFace.caffemodel
│  ├─ saved_logs
│  │  └─ jobs
│  │     └─ Anti_Spoofing_1_80x80
│  │        └─ Jul08_12-51-18
│  │           └─ events.out.tfevents.1594183888.old01
│  ├─ setup.py
│  ├─ src
│  │  ├─ anti_spoof_predict.py
│  │  ├─ data_io
│  │  │  ├─ dataset_folder.py
│  │  │  ├─ dataset_loader.py
│  │  │  ├─ functional.py
│  │  │  └─ transform.py
│  │  ├─ default_config.py
│  │  ├─ generate_patches.py
│  │  ├─ train_main.py
│  │  └─ utility.py
│  └─ train.py
└─ util.py

```
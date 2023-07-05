# Density-Based Traffic Timer Estimation



This project aims to dynamically allocate timers for each junction based on vehicle density, using the YOLOv4 algorithm for vehicle detection.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/chinta-sunil-varma/Hackathon.git
```

2. Navigate to the project directory:

```bash
cd Hackathon
```


3. Download the pre-trained YOLOv4 weights(if those are not working in the specified rar file):

```bash
https://github.com/AlexeyAB/darknet
```

## Usage

1. Start the Django server:

```bash
python manage.py runserver
```


## Features

- Dynamic allocation of timers for each junction based on vehicle density.
- Vehicle detection using the YOLOv4 algorithm.

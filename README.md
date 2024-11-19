# Python Mobile Store Application

## Overview

This Python application simulates a mobile store where users can interact with a catalog of mobile phones, including Samsung and iPhone models. Users can select mobile brands, view details of different models, and choose different configurations based on color, variant, RAM, battery, camera, processor, display size, and more. The program also includes a loop to handle multiple user interactions and gives the option to exit the store.

## Features

- **Mobile Catalog**: Includes Samsung and iPhone models with various configurations.
- **Model Details**: Displays details such as color, variant, RAM, battery, camera, processor, display, and price for each mobile model.
- **Configuration Selection**: Users can select different configurations for the mobile model they are interested in (e.g., color, variant, RAM, etc.).
- **Input Validation**: Ensures that users select only valid options for each configuration.
- **Interactive Flow**: Repeats the process to allow the user to view other models or configurations.

## Models Available

- **Samsung**: 
  - Samsung 20
  - Samsung 22
  - Samsung 24
- **iPhone**:
  - iPhone 15
  - iPhone 15 Plus
  - iPhone 15 Pro Max

## Requirements

- Python 3.x
- No external libraries are required for running the application.

## Installation

1. Clone this repository or download the files to your local machine.
2. Make sure you have Python 3.x installed. You can check by running:
 ```bash
 python --version
 ```
3. Navigate to the directory where the script is located:
 ```bash
 path/to/your/directory
 ```
4. Run the script using Python:
```bash
python mobile_store.py
```

## Sample Interaction
```bash
welcome to python store

do u want a phone?(yes/no): yes

great we have samsung and iphone
select 1 brand (samsung/iphone): samsung

here are the models: samsung20, samsung22, samsung24
Enter mobile model name: samsung20

colour: white
great

varient: 128gb
great

ram: 8gb
great

battary: 4000mh
great

camera: duel camera
great

processor: helio
great

display: 6.2
great

screen size: 6.1
great

weight: 165g
great

charger box: including in the box
great

thank you for your purchase! we hope you love it
```

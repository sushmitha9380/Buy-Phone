# Buy-Phone
This Python application simulates a Buy-Phone where users can interact with a catalog of Buy phones, including Samsung and iPhone models. Users can select Phone brands, view details of different models, and choose different configurations based on color, variant, RAM, battery, camera, processor, display size, and more. The program also includes a loop to handle multiple user interactions and gives the option to exit the store.

Features
Mobile Catalog: Includes Samsung and iPhone models with various configurations.
Model Details: Displays details such as color, variant, RAM, battery, camera, processor, display, and price for each mobile model.
Configuration Selection: Users can select different configurations for the mobile model they are interested in (e.g., color, variant, RAM, etc.).
Input Validation: Ensures that users select only valid options for each configuration.
Interactive Flow: Repeats the process to allow the user to view other models or configurations.
Models Available
Samsung:
Samsung 20
Samsung 22
Samsung 24
iPhone:
iPhone 15
iPhone 15 Plus
iPhone 15 Pro Max
Requirements
Python 3.x
No external libraries are required for running the application.
Installation
Clone this repository or download the files to your local machine.

Make sure you have Python 3.x installed. You can check by running:

bash
Copy code
python --version
or

bash
Copy code
python3 --version
Navigate to the directory where the script is located:

bash
Copy code
cd path/to/your/directory
Run the script using Python:

bash
Copy code
python mobile_store.py
or if you're using Python 3:

bash
Copy code
python3 mobile_store.py
How to Use
Start the application: When you run the script, you will be greeted with a welcome message and asked if you want to purchase a phone. Type yes to proceed or no to exit.
Select Brand: If you choose to buy a phone, you can choose between Samsung or iPhone models.
View Model Details: After selecting a brand, you'll be shown the available models, and you can select a model to see detailed specifications such as color, variant, RAM, battery, processor, display, weight, and price.
Choose Configurations: For each model, you'll be prompted to choose from available configurations (color, variant, RAM, battery, etc.).
Exit: You can exit the application at any time by choosing the exit option.
Sample Interaction
text
Copy code
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
Error Handling
Invalid Input: If an invalid input is provided (e.g., selecting a non-existing model, color, or variant), the program will prompt the user to select again. After three failed attempts, the user will be informed that the option is closed.
Exiting the Store: The user can exit the application at any point by choosing the exit option.
Contributing
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
License
This project is open source and available under the MIT License.

This README should provide a clear guide for users and developers interacting with the project on GitHub. You can further customize it based on additional features or changes to the application.




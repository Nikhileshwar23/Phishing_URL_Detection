# Phishing_URL_Detection

In the project Phishing URL Detection we use URLs from the login page in both classes because we consider it is much more representative of a real case scenario and we demonstrate that existing techniques obtain a high false-positive rate when tested with URLs from legitimate login pages. Additionally, we use datasets from different years to show how models decrease their accuracy over time by training a base model with old datasets and testing it with recent URLs. Also, we perform a frequency analysis over current phishing domains to identify different techniques carried out by phishers in their campaigns.![image](https://github.com/Nikhileshwar23/Phishing_URL_Detection/assets/101661622/c1a65fd3-217f-478a-9c0f-068508cf86ae)


## Dependencies

The project requires the following dependencies to be installed:\
Python 3\
XAMPP CONTROL PANEL\
SQLite


You can run the program by:
```bash
python manage.py runserver

```
## Usage

Start the xampp server and import the database file.\
Then open the file in command prompt and the type the prompt to run the application. 

## Screenshots

 User Login page
![Screenshot 2023-09-08 162630](https://github.com/Nikhileshwar23/Phishing_URL_Detection/assets/101661622/c55f7677-4001-4f33-9478-aae358f24d6f)

Url detection
![Screenshot 2023-09-08 162512](https://github.com/Nikhileshwar23/Phishing_URL_Detection/assets/101661622/5e1a209b-5a91-47ee-b871-0d270a4fd025)

Trained dataset result
![Screenshot 2023-09-08 162839](https://github.com/Nikhileshwar23/Phishing_URL_Detection/assets/101661622/3eeb09a0-5949-4245-89b4-e3bbe7f74f31)


## License
This project is licensed under the MIT License - see the 'LICENSE' file for details.
[MIT](https://choosealicense.com/licenses/mit/)

# CH-Detector
CH-Detector is a Python script that utilizes the phonenumbers library to determine the location and service provider of a given phone number. It uses the geocoder module to identify the country associated with the phone number and the carrier module to determine the service provider.

# Prerequisites
Python 3.x
phonenumbers library
Installation
Ensure you have Python 3.x installed on your system. You can download the latest version from the official Python website: https://www.python.org/downloads/

Install the phonenumbers library by executing the following command in your terminal or command prompt:

# Copy code
`pip install phonenumbers`
# Usage
Open the script CH-Detector.py in a text editor or Python IDE of your choice.

# Modify the number variable in the script to the phone number you want to analyze. Ensure the phone number is in the international format.

# Run the script using the following command:

Copy code
python CH-Detector.py
The script will output the country associated with the phone number and the service provider.

# Example
Let's assume you want to analyze the phone number "+14155552671". After modifying the number variable in the script to this value, you would run the script, and the output would be:
-------------------------------------------------------------------------------------------------------------|
Copy code                                                                                                    | 
Country: United States                                                                                       | 
Service Provider: T-Mobile                                                                                    |
This indicates that the phone number belongs to the United States, and the service provider is T-Mobile.      | 
---------------------------------------------------------------------------------------------------------------
# License
This project is under GNU stands for (General Public License)

# Disclaimer
The accuracy of the results obtained by CH-Detector depends on the data provided by the phonenumbers library. While the library aims to provide accurate information, it may not always be precise or up to date. Use the results at your own discretion.

Please note that CH-Detector does not perform any validation or verification of phone numbers. It relies solely on the provided phone number and the data available in the phonenumbers library.

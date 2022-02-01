# Fintech-Finder

![eth_image](Resources/eth_image.png)


This is an Ethereum based digital wallet capable of sending and receiving digital assets to Fintech professionals for services rendered. I have built a streamlit.io Webb App that demonstrates the working code of an application called Fintech Finder. The user is able to choose a Fintech professional that they are interested in hiring, choose the number of hours that they want to contract out, then send the professional wages in the form of Ether. The webb app provides a validated transaction hash upon verification that the amount of Ether was sent sucessfully.


## Technologies

This project uses Python 3.7 with the following packages and libraries:

- Streamlit

- web3

- typing

- dataclasses

- os

- requests

- dotenv

- bip44


## Installation Guide

The Fintech-Finder web app was built with Python 3.7. If the User wants to interact with the app, change settings, include new features, ect. Please install the following:  To get started using this application please go to [Python Download](https://www.python.org/downloads/) and select the version for your operating system. Then install the following libraries and packages.

``` sudo apt install python3-pip ```. This will install the pip that will make it easier to install the libraries.

``` pip install web3 ```

``` pip install streamlit ```

``` pip install typing ```

``` pip install dataclasses ```

``` pip install requests ```

``` pip install python-dotenv ```

``` pip install bip44 ```

``` pip install os-sys ```


## Usage

The file of interest is labeled ``` fintech_finder.py ``` . To run the web app first install the necessary packages. Then clone the repository to you local computer and navigate to the working folder via the terminal. The command to run the web app is ``` streamlit run fintech_finder.py ```. 


## Contributors

Stephen Thomas @ stephenthomas43@gmail.com

[Trilogy Education Services](https://www.trilogyed.com/)

[UC Berkeley Extension ](https://extension.berkeley.edu/)



## License 

MIT


# Preview of Web App
---

## Streamlit Web App with Sent Transaction verification

![streamlit_image](Resources/streamlit_image.png)

## Demo of Ganache Sender Account

![account_image](Resources/account_image.png)

## Demo of Ganache Sender Account Contract Call 

![transaction_image](Resources/transaction_image.png)

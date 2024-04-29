# BizCardX_Extracting_Business_Card_Data_with_OCR

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# About Project(BizCardX) :

            The application is a useful tool for businesses and individuals who need to manage business card information efficiently.

            Application contains a simple and intuitive user interface that guides users through the process of uploading the business card image and extracting its information. 

            The extracted information is displayed in a clean and organized manner. 

            The application also allows users to save the extracted information into a database along with the uploaded business card image.

            Also, the application allows users to read, update and delete the business card data from the database.


# Pre-Requisite  :

                  1) Python: Install Python

                  2) MySQL: Install MySQL database server and client on your system.


# Installation : 

                  Install all required packages from requirements.txt file using command: "pip install -r requirements.txt".


# Libraries Used :

1)  import streamlit as st
2)  from streamlit_option_menu import option_menu
3)  import pandas as pd
4)  import time
5)  import mysql.connector
6)  import os
7)  from streamlit_modal import Modal
8)  import base64
9)  from PIL import Image
10) import io
11) import easyocr
12) import re


# Usage :

                  1. To start the app, run command:   "streamlit run bizcardx.py".
                  2. The business card can be UPLOADED, EXTRACTED and saved to the database from "Upload" section.
                  3. From the "View" section, users can view, edit and delete the extracted business cards data.


# Features:

1. "Streamlit app" : Using "Streamlit" application to create a "simple UI" where users can manage business card information efficiently.
2. "Image-Text Extraction : Using "Easyocr" to extract data from the 'Business card'.
3. "Preprocessing extracted data" : Using "Python" to 'clean' and 'preprocess' extracted text to get required information.
4. "Migrate Data to a SQL Data Warehouse" : Insert the transformed data into a "MySQL" database for efficient storage and retrieval.
5. "Query the SQL data warehouse" : Using SQL queries, to retrieve the extracted data, so that the users can 'view', 'edit/update/modify' and 'delete' the "data" (as per requirements).

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

NAME : HARI YOGESH RAM B

BATCH : MDTM017

COURSE : DATA SCIENCE

CREDITS : GUVI

MAIL-ID : hariyogeshram882@gmail.com

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

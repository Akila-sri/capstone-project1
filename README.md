# capstone-project1
Youtube Dataharvesting and warehousing using python, MySQL and Streamlit

#Process
 1. Retrieval of channel,video and comment data from youtube using Youtube API.
 2. Storage of data in MySQL database
 3. Based on Query, analysis of data from databases

#Technologies used
  1.python
  2.MySQL
  3.streamlit

#Required libraries
import pandas as pd
from googleapiclient.discovery import build
import streamlit as st
import datetime
import mysql.connector
import isodate



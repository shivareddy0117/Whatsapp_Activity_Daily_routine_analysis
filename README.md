WhatsApp Activity and Sleep Analysis
====================================

Overview
--------

This project involves analyzing personal WhatsApp chat data to extract insights into daily routines. Specifically, it focuses on tracking when messages are sent, sleep patterns, dinner times, and more. The aim is to understand personal habits better and see how they correlate with communication times.

Data Extraction
---------------

The data is extracted from exported WhatsApp chats. Key points of interest include:
-----------------------------------------------------------------------------------

*   **Message Time:** Identifying the time messages are sent to understand communication patterns.
*   **Sleep Data:** Tracking when I go to sleep and wake up to analyze sleep duration.
*   **Dinner Time:** Recording dinner times to see how eating habits align with sleep patterns.

Features
--------

*   **Time to Message:** Calculates the time taken from waking up to sending the first message of the day.
*   **Sleep Duration:** Measures how long I sleep each night by subtracting the time I fall asleep from the time I wake up.

Tools Used
----------

*   **Python:** For data cleaning, transformation, and analysis.
*   **Pandas:** Utilized for DataFrame manipulation and time series data handling.
*   **Matplotlib:** For generating visual representations of the data.

Setup
-----

To run this project, ensure you have Python installed along with Pandas and Matplotlib. You can install the necessary libraries using pip:

bash

Copy code

`pip install pandas matplotlib`

Usage
-----

To analyze your own WhatsApp chat data:

1.  Export your WhatsApp chat to a text file.
2.  Place the chat file in the same directory as the scripts.
3.  Run the script `analysis.py` to perform data extraction and analysis.

Example Analysis
----------------

*   Plots the daily wake-up times and the first message sent to see how quickly after waking a message is sent.
*   Analyzes sleep duration over time to identify any trends or irregularities.

Contributing
------------

Feel free to fork the repository and submit pull requests. You can also open an issue if you find any bugs or have suggestions for additional metrics to analyze. If you are interested in contributing and require access to the actual `chatlog.txt` for a more detailed analysis, please request the file directly. Note that due to the personal nature of the data, it is not shared publicly but may be available upon request for serious contributions.

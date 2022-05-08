# Telegram-Data-Exploration
This repository contains all the data from my CSS project about theTelegram data, in which I've downloaded messages from different chats and analyzed it. 

# Firstly, you have to download the data and get your credentials.
1. Install dependencies: pip install -r requirements.txt
2. Get your credentials https://my.telegram.org/apps
3. Set credentials in config/config.json
4. Download '0_download_dialogs_list.py' and '1_download_dialogs_data.py'
5. Download dialogues data python 1_download_dialogs_data.py --dialogs_ids -1 --dialog_msg_limit 100000 // message limit is 100000
6. Download all dialogues python 0_download_dialogs_list.py --dialogs_limit -1 
7. Specify where you saved 'dialogs_data_all.csv' and 'dialogs_users_all.csv' in 'my_research.ipynb'
DIALOGS_MERGED_DATA_ALL_PATH = "/your path/dialogs_data_all.csv"
DIALOGS_MERGED_DATA_USERS_ALL_PATH = "/your path/dialogs_users_all.csv"

# Secondly, you have to create your new notebook in Jupiter Notebook and import all necessary tools.
This are the tools I've used in py analysis:
1. import pandas as pd
2. import numpy as np
3. import seaborn as sns
4. import matplotlib.pyplot as plt
5. from datetime import datetime as dt
6. from nltk.corpus import stopwords
7. import plotly.express as px

#Thridly, just create the questions and try to solve them!
You can analyze nearly everything:
1. Which types of chats you have?
2. Where you are the most active?
3. With whom you talk the most? (people)
4. With whom you talk the most? (by gender)
5. Your activness in different periods of day, week, season, year?
6. Activness of your interlocutors in different periods of day, week, season, year?
7. Topics you discuss the most?
8. Which data ou send/recieve/ forward the most?
9. What are the longes/shortest messages?
10. Which things you forwarded more times than others?
11. Stickers you use/recieve?
12. Word you/your interlocutors use the most?
13. Types of messages you send/receive the most? (exclamatory/question/affirmative sentences)

Those were only exampels what you can analyze, just use your imagination and try to solve the question that came to your haead!

# Moreover, after you did some exploration try to think what you can improve.
As for me, I'd like to improve analysis of users by gender, analysis of the most popular topics and analysis of messages by different parameters, for instance, by topics.

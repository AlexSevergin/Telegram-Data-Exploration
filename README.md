# Telegram-Data-Exploration
This repository contains all the data from my CSS project about theTelegram data, in which I've downloaded messages from different chats and analyzed it. 

## Firstly, you have to download the data and get your credentials.
1. Install dependencies: pip install -r requirements.txt
2. Get your credentials https://my.telegram.org/apps
3. Set credentials in config/config.json
4. Download '0_download_dialogs_list.py' and '1_download_dialogs_data.py'
5. Download dialogues data python 1_download_dialogs_data.py --dialogs_ids -1 --dialog_msg_limit 100000 // message limit is 100000
6. Download all dialogues python 0_download_dialogs_list.py --dialogs_limit -1 
7. Specify where you saved 'dialogs_data_all.csv' and 'dialogs_users_all.csv' in 'my_research.ipynb'
DIALOGS_MERGED_DATA_ALL_PATH = "/your path/dialogs_data_all.csv"
DIALOGS_MERGED_DATA_USERS_ALL_PATH = "/your path/dialogs_users_all.csv"

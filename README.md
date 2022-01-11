<p align="center"><img src="https://img.shields.io/badge/Version-3.1-brightgreen"></p>
<p align="center">

</p>
<p align="center">
  Telegram Group Scrapper
</p>
<p align="center">
</p>

---

## • API Setup
* Go to http://my.telegram.org  and log in.
* Click on API development tools and fill the required fields.
* put app name you want & select other in platform Example :
* copy "api_id" & "api_hash" after clicking create app ( will be used in setup.py )

## How To Install? (Only for Termux!):

$ `pkg install git python -y`

$ `git clone https://github.com/Wahyu213/Scraper`

$ `cd Scraper`

$ `chmod +x * && python3 setup.py`

## To Genrate User Data:

$ `python3 scraper.py`

- (`members.csv` is default if you changed name use it)
- Send Bulk SMS To Collected Data

$ `python3 smsbot.py members.csv` [Optional]

- Add users to your group

$ `python3 adder.py `

#### Or,

$ `python3 add2group.py members.csv`

- If you need more help <a href="https://t.me/OkaeriUserbot"><img src="https://img.shields.io/badge/Join-Telegram%20Group-blue.svg?logo=telegram"></a>
---


# Telegram to VK
Just a reposter

# Features
1. New post comes to telegram channel
2. Reposts to your vk

## Setup
1. `git clone https://github.com/AcademAI/telegram2vkontakte` 
2. Fill in the `.env` file with values

2 options from here:

### Via console:
```
pip install -r requirements.txt
python main.py
```

### Via Docker:
```
docker build --tag tg2vk . 
docker run tg2vk
```

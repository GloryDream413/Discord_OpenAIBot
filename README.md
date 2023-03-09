# Discord bot
```
pip install -r requirements.txt
```
### dev mode
```
python3 bot_openai.py
```
### product mode
```
pm2 start bot_openai.py --name bot_openai.py --interpreter python3
```
pm2 stop bot_openai.py
```
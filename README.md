# VCBOT
Fully working VC (user)Bot, based on py-tgcalls and py-tgcalls-wrapper with minimal [features](#TODO).   


## Deploying
* To heroku:   
![Deploy](http://heroku.com/deploy?template=https://github.com/xditya/VCBot)   

* Local machine/VPS:   
git clone https://github.com/xditya/VCBot   
pip install -r requirements.txt   
apt-get install ffmpeg   
touch .env && nano .env, fill in the vars as in [.env.sample](./.env.sample)   
python bot.py   

## SESSION
Either run [sessiongen.py](./sessiongen.py) locally or run it on repl.it by clicking here.
## Commands:   
- !on - Check if the (user)bot is online.   
- !help - Help message.   
- !stream - Either give a youtube URL or reply to a telegram file to play it.   
- !pause - Pause the stream.   
- !resume - Yes, resume.

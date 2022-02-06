
### Deploy to Heroku
- Get your `API_ID` and `API_HASH` from [here](https://my.telegram.org/)
- Get your Bot Token from [@BotFather](https://t.me/BotFather)

**Note:** By default the bot uses the default heroku-20 stack.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Kenzhu02/NewRobot)

### Traditional

- Install Python v3.7 or later from [Python's Website](https://python.org)
- Install virtualenv using `python3 -m pip -U install virtualenv`.
- **Fork** or Clone the project using `git clone https://github.com/DivideProjects/Alita_Robot.git`
- Create Virtualenv using: `virtualenv venv`
- Install the requirements using `python3 -m pip install -r requirements.txt`
- Fill in all the variables in *Development* class, not *Config* class. **Sudo, Dev, Whitelist** users are optional!!
- Change to virtualenv shell by using:
  `. venv/bin/activate` (Linux)
  `venv\Scripts\activate` (Windows)
- Run the bot using `python3 -m alita`

### Docker

- Clone the repo and enter into it
- Install [Docker](https://www.docker.com/)
- Fill in the `sample.env` file and rename it to `main.env`.
- Build the docker image using: `docker build -t alita_robot:latest .` (The dot '.' at last is necessary!)
- Run the command `docker run --env-file main.env alita_robot`


If all works well, bot should send message to the **MESSAGE_DUMP** Group!


## Contributing to the project

- Make sure your PR works and doesn't break anything.
- You must join the support group.
- Make sure it passes test using `make test`.


## Special Thanks to
- [AmanoTeam](https://github.com/AmanoTeam/) for [EduuRobot](https://github.com/AmanoTeam/EduuRobot) as that helped me make the translation engine.
- [Dan](https://github.com/delivrance) for his [Pyrogram](https://github.com/pyrogram/pyrogram) library
- [Paul Larsen](https://github.com/PaulSonOfLars) for his Original Marie Source Code.
- Everyone else who inspired me to make this project, more names can be seen on commits!


### Copyright & License

* Copyright (C) 2020-2021 by [Divkix](https://github.com/Divkix) ❤️️
* Licensed under the terms of the [GNU AFFERO GENERAL PUBLIC LICENSE Version 3, 29 June 2007](https://github.com/DivideProjects/Alita_Robot/blob/master/LICENSE)

## Powered By

[![DivideProjects](https://img.shields.io/badge/Divide-Projects-green?style=for-the-badge&logo=appveyor)](https://t.me/DivideProjectsDiscussion)

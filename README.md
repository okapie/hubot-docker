# hubot-docker

This project is to work Hubot on Docker.

Before building a docker container, you need to set up .hubot-docker.env in your local.

Specify secret variables in .hubot-docker.env.
```
export HUBOT_SLACK_TOKEN={Your HUBOT_SLACK_TOKEN}
export HUBOT_SLACK_TEAM={Your HUBOT_SLACK_TEAM}
export HUBOT_SLACK_BOTNAME={Your HUBOT_SLACK_BOTNAME}
export HUBOT_HEROKU_KEEPALIVE_URL={Your HUBOT_HEROKU_KEEPALIVE_URL}
```

To work Hubot, try to run the following command.
```
docker-compose up -d hubot
```

You'll get a response from `hubot-sushi` when you send `How are you?` to `hubot-sushi` on your slack.

Hubot works on Docker if `hubot-sushi` replies `I'm fine, thank you.` or `I’m all right.` or `Not bad.`

<img src="https://user-images.githubusercontent.com/5210367/33420773-2a44b592-d5f3-11e7-8422-7c925c4a5d16.png" width="300px">

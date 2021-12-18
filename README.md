# Forward_2.0

* Bot to forward messages from one channel to other without admin permission in source channel.
* Can be used for both private and Public channels.
* Bot Index message from channel and saves to database, further forwards and deletes each messages from database.Use of database was to Remove duplicacy of files.
* For Private channels User account is used to copy messages, hence will be slow, to avoid ban.
* For Public Channels Bot is used to forward , Thanks to [DⱥℝkAngel](https://github.com/Jijinr) for his [Frwdit](https://github.com/Jijinr/Frwdit).

### Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/subinps/Forward_2.0)
### Deploy to Railway
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2FRudster-Modz%2FForward_2.0&envs=API_HASH%2CAPI_ID%2CBOT_TOKEN%2CBOT_USERNAME%2CCOLLECTION_NAME%2CDATABASE_NAME%2CDATABASE_URI%2COWNER_ID%2CSESSION%2CTO_CHANNEL&API_HASHDesc=Get+this+value+from+https%3A%2F%2Fmy.telegram.org+or+%40UseTGXBot&API_IDDesc=Get+this+value+from+https%3A%2F%2Fmy.telegram.org+or+%40UseTGXBot&BOT_TOKENDesc=Your+bot+token+from+%40BotFather&BOT_USERNAMEDesc=Username+of+your+Bot+without+%40+%2C+Only+give+if+you+want+auto+starts+forwarding+when+heroku+restarts&COLLECTION_NAMEDesc=Database+Collection+Name&DATABASE_NAMEDesc=Database+cluster+name&DATABASE_URIDesc=Get+this+from+cloud.mongodb.com&OWNER_IDDesc=Enter+Your+Telegram+id&SESSIONDesc=Pyrogram+string+Session+https%3A%2F%2Frepl.it%2F%40subinps%2FgetStringName&TO_CHANNELDesc=Enter+Your+channel+Id+must+add+Eg%3A-+-100xxxxxxxxx&COLLECTION_NAMEDefault=Forward_data&DATABASE_NAMEDefault=Cluster0&referralCode=Rudster)


### Variables

* `API_HASH` API Hash from my.telegram.org
* `API_ID` API ID from my.telegram.org
* `BOT_TOKEN` Bot token from @BotFather
* `OWNER_ID` Telegram Id of Owner.
* `TO_CHANNEL` Channel ID of channel to which messages are forwarded eg:- -100xxxxxxxx
* `SESSION` Pyrogram session string Generate From here [![GenerateStringName](https://img.shields.io/badge/repl.it-generateStringName-yellowgreen)](https://replit.com/@Rudster-Modz/getStringName#main.py)
* `DATABASE_URI` Database uri from [MongoDB](https://cloud.mongodb.com/)
* `DATABASE_NAME` Database Cluster name
* `COLLECTION_NAME` Database Collection name.


### Credits
* [DⱥℝkAngel](https://github.com/Jijinr) for his [Frwdit](https://github.com/Jijinr/Frwdit)
* [Rahul](https://github.com/rahulps1000) for his [ForwardBot](https://github.com/rahulps1000/ForwardBot)


# MouamleCommunicationBot
A java telegram Communication bot 



#Installation
```sh
sudo add-apt-repository ppa:webupd8team/java -y && sudo apt-get update && sudo apt-get install oracle-java8-installer -y
```
###Edit the config and then 
```sh
git clone https://github.com/Mouamle/MouamleCommunicationBot.git
cd MouamleCommunicationBot
chmod 777 start.sh
./start.sh
```

#in config.lua
```lua
return 
{
	
	MToken = "", -- this is a token you take from @Mouamle or @IlulI go ask them for one :D 
	
	token = "", -- the bot token
	username = "", -- the bot username
	yourId = "", -- your id
	groupId = "", -- your support group id
	BanMessage = "*You were banned*",
	unBanMessage = "*You were released*",
	
	WelcomeMessage =  -- Welcome message
	[[
	*Welcome* <username> i'm a CommunicationBot
	`I will send the messages back and forth between you and my owner`
	]],
	SentNotification = "Message Sent"
}
```

#For help contact 
[@Mouamle](https://telegram.me/Mouamle)

[@IlulI](https://telegram.me/IlulI)

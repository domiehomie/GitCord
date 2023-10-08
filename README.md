# GitCord
Discord bot that replies to your messages with information about Issues and Pull Requests.

> [!NOTE]
> This project has been discontinued. Currently a running version is up and you can invite it using [this URL](https://discord.com/api/oauth2/authorize?client_id=966357004924887060&permissions=8&scope=bot), although it may be shut down at any moment.

## Runnning yourself
Change [this line](https://github.com/mufinlive/GitCord/blob/4d3e343142a96f1f249788579b8650e3421b413b/src/main/java/live/mufin/gitcord/Gitcord.java#L27) to whatever mode you want to use; `DEV`, `PROD` or `DEFAULT`. Then copy [the info file](https://github.com/mufinlive/GitCord/blob/master/src/main/resources/info.properties) into `info(-dev/-prod).properties`. Then build the project with `mvn package` and run the jar with `java -jar target/gitcord-1.x.jar`.

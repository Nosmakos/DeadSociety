
# DeadSociety - Zombie Apocalypse Minecraft Plugin


Found a problem? Use the issues tab above to raise an issue. Please include all the information requested in the issue template, unless you're certain it's not relevant. Otherwise, contact me on discord.

## Information

• Placeholders - ([PlaceholderAPI](https://github.com/PlaceholderAPI/PlaceholderAPI/wiki/Placeholders#plugin))
 
  > /papi ecloud download Player | /papi ecloud download DeadSociety
   
 Gives you various placeholders for the player, that triggers the action and also returns information about the specified plugin.
 
 ```
  • %deadsociety_player_kills% 
  • %deadsociety_walker_kills% 
  • %deadsociety_player_deaths% 
  • %deadsociety_kd_ratio%
  • %deadsociety_player_thirst%
```

## Adding DeadSociety as a gradle/maven/sbt/leiningen dependency

Apparently there's this neat thing called JitPack  that makes a public maven repo for public Github repos on the fly. According to it, this is all you need to do to add this to your maven project:

	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
	

	<dependency>
	    <groupId>com.github.Nosmakos</groupId>
	    <artifactId>DeadSociety</artifactId>
	    <version>-SNAPSHOT</version>
	</dependency>
	
	
Replace <version> number with this number: [![](https://jitpack.io/v/Nosmakos/DeadSociety.svg)](https://jitpack.io/#Nosmakos/DeadSociety)

You can also add it to gradle/sbt/leiningen projects: https://jitpack.io/#Nosmakos/DeadSociety

[Development API](https://github.com/Nosmakos/DeadSociety/wiki/Development-API)

## Support

• [Discord Support](https://discordapp.com/invite/9v7BsVv)
• [Spigot Discussion](https://www.spigotmc.org/threads/283082/)
• [Issues Tracker](https://github.com/Nosmakos/DeadSociety/issues)

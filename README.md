### Discord.py Bot Template
Here follows a simple, very basic bot template for discord.py. Do not use this template if you are going to make a huge bot, but only use this template for very small to small sized discord.py bots. This template uses a non-standard way to make a new command. It is also a tiny bit more lightweigt since you do not have to import discord, but just a very tiny amount.<br>
```python
from discord.ext.commands import Bot as bot; bot = bot(command_prefix = '')

@bot.event
async def on_ready():
	print('Bot is ready.')

@bot.command(name = '.ping')
async def new_command(ctx):
	await ctx.send('pong')

bot.run('token')
```
### Code Showcase
Here you can see the code in action.<br>

<img src="https://camo.githubusercontent.com/2d3a0683511bdeb44515f42d072c4330caedcf30587bdb0a5a8aea4d8530d451/68747470733a2f2f66696c6562696e2e6e65742f683030346339676a6b366163376462782f67656e6572616c2d476f6f676c652d4368726f6d652d323032312d30352d32322d31392d32372d35392e676966" width="600px">

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

<img src="https://cdn.discordapp.com/attachments/734337167848898574/845720174870265886/general-Google-Chrome-2021-05-22-19-27-59.gif" width="600px">

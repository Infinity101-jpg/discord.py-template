### Discord.py Bot Template
Here follows a simple, very basic bot template for discord.py. Do not use this template if you are going to make a huge bot. Rather, only use this template for small to medium sized discord.py bots.

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


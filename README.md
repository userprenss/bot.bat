bot.bat
const Discord = require('discord.js');
const client = new Discord.Client();

client.on('ready', () => {
  console.log(`Bot Sunucunuza Giriş Yaptı ${client.user.tag}!`);
});

client.on('message', msg => {
  if (msg.content === 'sa') {
    msg.reply('Aleyküm Selam Hoşgeldin!');
  }
});

});


client.on('message', msg => {
  if (msg.content === 'sa') {
    msg.reply('Aleyküm Selam Hoşgeldin!');
  }
});


client.login('2T8j7Os69JxO2QV95gyCdi9q_JXmG_Yw');

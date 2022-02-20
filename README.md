# memes.spain
Npm que da memes en español
## Instalación
```sh
npm i memes.spain
```
## Uso
```js
const memes = require("memes.spain");
const meme = memes.Memes();
```
##Ejemplo
```js
const memes = require("memes.spain");
const meme = memes.Memes();

const embed = new Discord.MessageEmbed()
  .setTitle("Meme")
  .setColor(0xFF0000)
  .setImage(meme)
  .setFooter({text: `Creado por fjfh#4348 | Solicitado por ${message.member.displayName}`})
  .setTimestamp()
  
message.channel.send({ embeds: [embed] })
```

# UwUMusic
This is my bot music


* [Requirements](#requirements)
* [Starting-app](#starting-app)


## Requirements:

- [Node](https://nodejs.org/en/) - Version 16 or higher
- [NPM](https://www.npmjs.com/)
- [FFMPEG](https://www.ffmpeg.org/)

### Installation:

```bash
# Clone the repository
git clone https://github.com/Jorisouuu/UwUMusic
# Enter into the directory
cd UwUMusic/
# Install the modules
npm install
```

## Required permissions:

**Important:** Make sure that your bot has the `applications.commands` application scope enabled, which can be found under the `OAuth2` tap on the [developer portal](https://discord.com/developers/applications/)

### Configuration

After cloning the project and installing all modules, you need to add your Discord token in the config.json file.

## Starting-app:

```bash
node index.js
```
or use pm2 
```bash
npm install pm2
```
```bash
pm2 start index.js
```

## Deploying commands:

Before you can use the bots slash command you first need to add them to your Discord server. You can use the `!deploy` command to do so.
After deploying the commands you should be able to see and access them by typing a slash


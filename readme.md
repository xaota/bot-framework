roadmap
```javascript
const framework = new BotFramework();
const config    = framework.config(path);
const bot       = new Bot(config);
bot.integrations(framework.integrations);
bot.launch();
```

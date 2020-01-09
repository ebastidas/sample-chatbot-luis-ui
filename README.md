# sample-chatbot-luis-ui

---

### Install (frontend) bot

1. Create bot:

  Follow:

  https://docs.microsoft.com/en-us/azure/bot-service/nodejs/bot-builder-nodejs-recognize-intent-luis?view=azure-bot-service-3.0

  If needed "Microsoft App ID and Password":

  https://docs.microsoft.com/en-us/azure/bot-service/bot-service-resources-bot-framework-faq?view=azure-bot-service-4.0#i-need-to-manually-create-my-app-registration-how-do-i-create-my-own-app-registration


2. Get your bot service secret key

  https://docs.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-webchat?view=azure-bot-service-3.0#get-your-bot-secret-key

3. Change your Direct Line token secret in the file `src/app/app.component.ts` on the variable `AZURE_BOT_SERVICE_SECRET`

4. Install Webchat demo (this repo) and run it.

---

A simple web-chat port in Angular example

### Instructions to startup

-   Change the tokens, secrets, ids, etc. in the `src/app/app.component.ts` file for the webchat to actually send data.
-   Run `npm install` to install the repo dependencies.
-   Run `npm install -g @angular/cli` to install the Angular CLI tool globally for convenience.
-   Run `ng serve` with CWD on the root of the project.

### Angular versions

-   This repo has multiple release tags. Each one corresponds to an different version of Angular or WebChat.
-   Check the [CHANGELOG](./CHANGELOG.md) file for more information on each release version.

---

Check also, the official Webchat demo (+ customizable with React): https://github.com/microsoft/BotFramework-WebChat#how-to-use

Recognize intents and entities with LUIS: https://docs.microsoft.com/en-us/azure/bot-service/nodejs/bot-builder-nodejs-recognize-intent-luis?view=azure-bot-service-3.0

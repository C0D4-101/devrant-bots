# Unofficial devRant Bot Code of Conduct

This is a document for ethical and community approved practices when creating a [devRant](https://devrant.com) bot.

When creating a bot for devRant there is several key pitfalls that can be encountered, either by accident or through malicious intent. This is intended as a governing set of principals to validate your bot will be welcomed to the devRant community.

---

<br />


## Governing Principles
- The bot should disclose it is a bot in the User Profile on devRant.
- The bot should disclose its owner in the User Profile on devRant.
- The bot must not be used to create additional accounts or bots.
- The bot owner must be a human being of the planet earth inside the milky way galaxy.
- The bot should only make use of the devRant API.

    - For Reference See: [Unofficial devRant API Documentation](https://devrantapi.docs.apiary.io/)

- The bot must not influence the updoots (++ score) of any user.
- The bot must not be used for advertising purposes.
- The bot should not comment on any rant unless triggered from a Human user via a Mention.
- The bot must ignore all known bots including its self.
    
    - see the [README](https://github.com/C0D4-101/devrant-bots/blob/master/README.MD) for the current list of known bots.
    - The bot must be added to the [devRant-Bots](https://github.com/C0D4-101/devrant-bots/) repo before going live.
- The bot should respond with a Comment to the same rant that it was triggered from and mention the user whom triggered the bot.

    For example:

    ``` 
    @user 

    insert comment here 
    ```
- The bot should not post a rant more than once per day.
- The bot can comment and rant with images, See [devRant Rules](https://devrant.com/rules) for acceptable content.

---

<br />

## API Usage
You may not use the API in any way to:
- Scrape devRant Data without explicit permission
- Flood devRant with excess comments / rants
- retain data any longer than necessary for the operation of your specific application.

---


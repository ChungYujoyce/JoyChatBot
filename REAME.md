#### Settings
Geanerate an [OpenAI API key](https://beta.openai.com/account/api-keys
)
- Click Create new secret key

Create [Discord Application](https://discord.com/developers/applications) 

1. Need to create a discord server if you don't have one

2. Build a Discord bot under the application
    - Navigate to `Bot` Tab and click `Add Bot`
    - Navigate to `OAuth2`, URL Generator:
      - `SCOPES`: select bot
      - `BOT PERMISSION`: select Administrator
      - `GENERATED URL`: copy this url
    - Navigate to `OAuth2`, General:
      - `AUTHORIZATION METHOD`:
        - `CUSTOM URL`: paste the one you just copied (We will need it later so put it some where safe)
    - Save all Changes
    
3. Go to `Bot` again
    - Turn `MESSAGE CONTENT INTENT` ON 
    - Click `Resent token` to get the token
    - Store the token to `.env` under the `DISCORD_BOT_TOKEN`
    - Save all Changes

4. Open a tab in your browser and paste the `CUSTOM URL` you just created and click `ADD TO SERVER`, select a server you want to use.

You can now see the chatbot showing in your discord server!

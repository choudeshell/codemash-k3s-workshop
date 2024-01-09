## Subject: Re: New App

Hello! Thanks for opening up the app. Looks like we are running into some issues. Can you configure it to increase the app logging to `Debug`? The config is in `appsettings.json` -- the config should be:

```json
{
  "Logging": {
    "LogLevel": {
      "Default": "Debug"
    }
  }
}

```
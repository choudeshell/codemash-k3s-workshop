## Subject: Re: New App

Hello! The team solved the issue. Looks like we are running into issues with scaling. The team broke out background processing to an API. Just update the config and point the API to another set of instances for the same app. We are taking care of all the heavy lifting. Thanks!

```json
{
    "Logging": {
    "LogLevel": {
        "Default": "Information"
    }      
    },
    "API":"{url}"
}

```



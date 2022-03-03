<script src="https://kit.fontawesome.com/b6dbfc57a8.js" crossorigin="anonymous"></script>
<div style="text-align:center;">
    <h1>Configuration</h1>
    <p>Easy and simple configuration for the bot</p>
</div>

------

## Introduction

Throughout this section, we will go through the different configuration options for the bot.

Also, you will find many different symbols throughout this documentation. You can find what these mean below.

|            **Symbol**           |      **Meaning**      |
|---------------------------------|-----------------------|
| Anything surrounded in `<>` | <span style="text-decoration:underline;">Required</span> argument    |
| Anything surrounded in `[]` | <span style="text-decoration:underline;">Optional</span> argument    |

> <i class="fa-solid fa-info"></i> - Information
>
> There will not be a lot of these symbols popping up. But they are good to know

------

## Configuration Files

In the main file that you downloaded, you will see a folder that is named `config`. In that folder, you will find 2 files. One that is named `config.yml` and one named `token.yml`

> <i class="fa-solid fa-info"></i> - Information
>
> The directory being talked about should look like this:
>
>  📁 config
>
>   🧾 config.yml
>
>   🧾 token.yml

In the ["Getting Started"](https://modinator.tk/docs/getting-started) section, you already went over everything that was needed for the `token.yml` file, but now we will be moving onto everything that is in the `config.yml`

## Configuration Options

Here are the configuration option available for the bot.

Each section will be clearly shown in the `config.yml` file.

**Anything that has `Editable` next to it is configurable by you!!**

### Bot Config

<span style="text-decoration:underline;">Bot Activity</span>

| Option | Description                     | Special Requirements                             |
|--------|---------------------------------|--------------------------------------------------|
| `type` | The type of status the bot has    | **MUST** be `WACHING`, `PLAYING`, or `LISTENING` |
| `name` | The "content" of the bots status | N/A                                              |

<span style="text-decoration:underline;">Server Config

| Option    | Description                        | Special Requirements |
|-----------|------------------------------------|----------------------|
| `id`      | The ID of the server the bot is in | Must keep the `[]`   |
| `ownerid` | The ID of the owner of the bot     | N/A                  |

### Channel Config

All values must be the **ID** of the channel

<span style="text-decoration:underline;">Channel Config</span>

| Option        | Description                                |
|---------------|--------------------------------------------|
| `kickLogs`    | The channel where all logs of a kick go    |
| `banLogs`     | The channel where all logs of a ban go     |
| `unbanLogs`   | The channel where all logs of an unban go  |
| `warnLogs`    | The channel where all logs of a warn go    |
| `muteLogs`    | The channel where all logs of a mute go    |
| `purgeLogs`   | The channel where all logs of a purge go   |
| `timeoutLogs` | The channel where all logs of a timeout go |
| `embedLogs`   | The channel where all logs of an embed go  |

### Role Permissions

All values must be the **ID** of the role 

<span style="text-decoration:underline;">Role Permission Config</span>

| Option        | Description                                     |
|---------------|-------------------------------------------------|
| `kickRole`    | The role that has permission to kick            |
| `banRole`     | The role that has permission to ban             |
| `unbanRole`   | The role that has permission to unban           |
| `warnRole`    | The role that has permission to warn            |
| `muteRole`    | The role that has permission to mute            |
| `mutedRole`   | The role that is given to someone that is muted |
| `purgeRole`   | The role that has permission to purge           |
| `timeoutRole` | The role that has permission to timeout         |
| `embedRole`   | The role that has permission to embed a message |

### Embed Config

<span style="text-decoration:underline;">Footer</span>

| Option   | Description                           |
|----------|---------------------------------------|
| `footer` | The footer at the bottom of any embed |

<span style="text-decoration:underline;">Colors</span>

All value **MUST** start with a `0x` followed by the hex of what the color is.</br>
i.e: 0xFFFFFF

| Option        | Description                                                   |
|---------------|---------------------------------------------------------------|
| `success`     | The color that the embed is when something successful happens |
| `error`       | The color that the embed is when an error is displayed        |
| `logs`        | The color that the embed is when logs are posted              |
| `information` | The color that the embed is when information is posted        |
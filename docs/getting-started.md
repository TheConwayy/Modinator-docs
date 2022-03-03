<script src="https://kit.fontawesome.com/b6dbfc57a8.js" crossorigin="anonymous"></script>
<h1 style="text-align: center;">Getting Started</h1>
<p style="text-align: center;">A simple, easy introduction to Modinator!</p>

----

## Pre-requisites

***Please keep in mind that this bot is self hosted. It is highly recommended you buy a VPS or something alike to host the bot***

To host this bot, you will have to have the following on your PC and/or hosting service:

- [NodeJS](https://nodejs.org/en/) v16 + *([Download Link](https://nodejs.org/dist/v16.14.0/node-v16.14.0-x64.msi))*
- Some sort of text editor such as [VSCode](https://code.visualstudio.com/) or [Notepad++](https://notepad-plus-plus.org/downloads/)


You will also need the following NPM packages:

  - [TypeScript](https://www.typescriptlang.org) @ latest
  - [Discord.JS](https://discord.js.org/#/) @ v13 +
  - [file-system (fs)](https://www.npmjs.com/package/file-system) @ latest
  - [js-yaml](https://www.npmjs.com/package/js-yaml) @ latest
  - [WOKCommands](https://docs.wornoffkeys.com) @ latest
  - [yaml](https://www.npmjs.com/package/yaml) @ latest

_There is a tutorial on how to download all of this below_

-----

## Installation

To install Modinator and all of the packages it requires to run, please follow the steps below.

### Step 1 - Setup

There is some setup that is involved with the bot.

First, you are going to unzip the `.zip` file that was given to you upon purchase.

> <i class="fa-solid fa-info"></i> - Suggestion
>
> _Something such as "7zip" would be recommended for ease of use. However it is not required_

After the file is un-zipped, you should have a folder named "Modinator" that has files like this:

```
📁 commands
   📁 help (this will have files in it)
   📁 moderation (this will have files in it)
   📁 util  (this will have files in it)
📁 config
   🧾 config.yml
   🧾 token.yml
🧾 index.ts
🧾 package.json
```

We will now move onto installing packages

-----

### Step 2 - Installing Packages

First, you will want to open up you command prompt.
To do this you will want to hold `WIN+R`. This will open up a little box in the bottom left of your screen.

In there you will want to type `cmd`

> <i class="fa-solid fa-camera"></i> - Screenshot for reference
>
> <img src="https://i.imgur.com/KwN0gTy.png">

You should then see your command prompt open up

> <i class="fa-solid fa-camera"></i> - Screenshot for reference
>
> <img src="https://i.imgur.com/KWzGuX8.png">

When you see this, you will want to copy and paste this command into the command prompt.

`cd <path to folder with the "index.ts" file>`

> <i class="fa-solid fa-info"></i> - Useful Tip
>
> You can just copy the path at the top of the file explorer.

Now you will want to copy the following commands into the command prompt.


```
npm install -g typescript@latest

npm install discord.js@13.6.0

npm install fs

npm install yaml

npm install wokcommands@latest

npm install js-yaml
```

> <i class="fa-solid fa-info"></i> - Each line is a separate command

------

### Step 3 - Getting your token

To get you token to run the bot, you will need to head to [this](https:/discord.com/developers) (https:/discord.com/developers) website.

From there, you will want to click on the blue "New Application" button.

> <i class="fa-solid fa-camera"></i> - Screenshot for reference
>
> <img src="https://i.imgur.com/GLn6CdD.png">

You will then be greeted by a prompt that says "CREATE AN APPLICATION" with an input for the name of the application. **This will be the name of the bot**.

Once you have entered a name, click the next "Create" button.

You will then be greeted by the application management page *(that is not the official name just what I like to call it)*

If you would like to add an "about me" to the bot, you can do so by writing it in the "Description" box

> <i class="fa-solid fa-camera"></i> - Screenshot for reference
>
> <img src="https://i.imgur.com/KSG8FwP.png">

From there, you will want to click the button that says "Bot" on the left side-bar.

Then you will want to click on "Add Bot"

> <i class="fa-solid fa-camera"></i> - Screenshot for reference
>
> <img src="https://i.imgur.com/iid7YeW.png">

This will then bring you to the bot management page.

Here, you can change the icon and name of the bot if you so desire.

This is also the place where you will be setting up intents.

> <i class="fa-solid fa-camera"></i> - Screenshot for reference
>
> <img src="https://i.imgur.com/xAtoeRP.png">

Then from there, you are going to click on the "Copy" button that is right below the "Click to Reveal Token" link.

You are then going to open your `token.yml` file

> <i class="fa-solid fa-info"></i> - It should be in this directory
>
> ```
> 📁 config
>    🧾 token.yml
> ```

You are then going to paste the token right after the `token:`

> <i class="fa-solid fa-camera"></i> - Screenshot for reference
>
> <img src="https://i.imgur.com/VWcZfte.png">

Then you are done! You can no head on over and get started with the installation!
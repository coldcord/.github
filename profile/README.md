# Coldcord

Coldcord is an organization to post userplugins for vencord.

Vencord avatar inspired the Coldcord avatar design

Credit to Royyan Wijaya for the ice cube icon desgin

> # ⚠️ Installing anything from here is not officially supported.
>
> If you don't understand these instructions, installing unofficial plugins is not for you.
> Do not ask for help in <a style="color:color-mix( in oklab, hsl(235 calc(1 * 86.2%) 88.6% / 1) 100%, black 0% );background:color-mix( in oklab, hsl(235 calc(1 * 85.6%) 64.7% / 0.3) 100%, hsl(0 0% 0% / 0.3) 0% );text-decoration: none;" href="https://discord.com/channels/1015060230222131221/1026515880080842772" target="_blank">🏥-vencord-support-🏥</a>.
> Instead, ask for help in the thread of the plugin(s) you're using.

## First Time Setup

Vencord is not modular, so you have to build from source to add custom plugins.
Follow this guide for getting set up: https://docs.vencord.dev/installing/custom-plugins/

## How to install a plugin

1. Direct your terminal to the `userplugins` folder, e.g. `cd src/userplugins`. If you're confused, read the guide above
2. Each plugin post will contain a GitHub repo link, like `https://github.com/PluginAuthor/CoolPlugin`. Copy it
3. Inside your terminal, run

```sh
git clone https://github.com/...
```

## How to update plugins

You will have to make sure to keep up with the latest changes to fix issues and get new features. You can update a plugin by directing your terminal to its folder (`cd src/userplugins/coolPlugin`) and running:

```sh
git pull
```


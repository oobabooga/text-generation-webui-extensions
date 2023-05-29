# text-generation-webui-extensions

This is a directory of extensions for https://github.com/oobabooga/text-generation-webui

If you create your own extension, you are welcome to submit it to this list in a PR.

## long_term_memory
A sophisticated extension that creates a long term memory for bots in chat mode. 

https://github.com/wawawario2/long_term_memory

## complex_memory
A KoboldAI-like memory extension. You create memories that are injected into the context of the conversation, for prompting based on keywords. 

https://github.com/theubie/complex_memory

## EdgeGPT
Extension for Text Generation Webui based on EdgeGPT by acheong08, for a quick Internet access for your bot.

https://github.com/GiusTex/EdgeGPT

## telegram_bot
Provides a cai-chat like telegram bot interface. 

https://github.com/innightwolfsleep/text-generation-webui-telegram_bot

## oobabot

Another Discord bot, with both command-line and GUI modes.  Easy setup, lots of config options, and customizable characters!

- [**`oobabot`**](https://github.com/chrisrude/oobabot) -- command-line mode, uses Oobabooga's API module

- [**`oobabot-plugin`**](https://github.com/chrisrude/oobabot-plugin) -- GUI mode, runs inside of Oobabooga itself

<details>
<summary>
Oobabot Screenshots!
</summary>

| Config UI   | In Action! |
| ----------- | ----------- |
| ![image](https://raw.githubusercontent.com/chrisrude/oobabot-plugin/main/docs/oobabot-plugin.png) | ![image](https://raw.githubusercontent.com/chrisrude/oobabot/main/docs/zombietaytay.png)|

</details>

https://github.com/chrisrude/oobabot-plugin

## bark_tts
A simple implementation of Suno-AI's Bark Text-To-Speech with implicit multi-language and simple sound effect support.

https://github.com/minemo/text-generation-webui-barktts

## sd_api_pictures_tag_injection
An expanded version of the included sd_api_pictures extension that features injecting character tags or arbitrary tags upon detection of specific strings into SD side prompt. Greatly improves character self-image stability and allows dynamic usage of LORAs.

https://github.com/GuizzyQC/sd_api_pictures_tag_injection

## code_syntax_highlight
An extension that adds syntax highlighting to code snippets.

<details>
  <summary>Click to show preview</summary>
  <br>

  ![preview-1](https://www.davg25.com/file/github-media/text-generation-webui-code_syntax_highlight/demo1.png)

</details>

https://github.com/DavG25/text-generation-webui-code_syntax_highlight

## multi_translate
An expanded version of the google_translate extension, that provide more translation options (more engines, save options to file, functionality to toggle on/off translations on the fly).

https://github.com/janvarev/multi_translate

## api_advanced

An expanded version of api extension.
1. Provide Kobold-like interface (the same way as "api" classic extension)
2. **Provide advanced logic to auto-translate income prompts:**
    - You need to use multi_translate extension: https://github.com/janvarev/multi_translate
    - Set up param `'is_advanced_translation': True`, (set by default)
    - ...see the details in console
      - Due to advanced logic script splits income prompt by lines, and **cache translation results**
      - **Text quality feature:** when it generate English response, it cache it too (so you don't do double-translation English->UserLang->English next time) 

https://github.com/janvarev/api_advanced

## discord_bot
Discord integration for the oobabooga's text-generation-webui (Inspired by DavG25's plugin)

Currently it only sends any response from the chatbot to a discord Webhook of your choosing

Simply create a Webhook in Discord following this tutorial and paste the webhook URL under the chat box that will show after the plugin is enabled.

<details>
  <summary>Click to show preview</summary>
  <br>
  
  ![preview-2](https://user-images.githubusercontent.com/45816945/234896222-532ef597-3e26-48cc-8af2-7df33d471e1b.png)![image](https://user-images.githubusercontent.com/45816945/234899114-09381d3d-3deb-4f1f-8328-2567755cfe40.png)


</details>

https://github.com/ChobPT/text-generation-webui-discord_bot

## webui_langchain_agent
https://github.com/ChobPT/oobaboogas-webui-langchain_agent/

oobaboogas-webui-langchain_agent
Creates an Langchain Agent which uses the WebUI's API and Wikipedia to work and do something for you

Tested to be barely working, I learned python a couple of weeks ago, bear with me.

Needs ´api´ and ´no_stream´ enabled.
<details>
  <summary>Click to show preview</summary>
  <br>

  ![preview-1](https://user-images.githubusercontent.com/45816945/236649969-0d4fbab3-15e9-4cf0-88d0-71419e77d1cb.png)

</details>

## UI Tweaks
Adds options to keep tabs on page (sticky tabs) and to move extensions into a hidden sidebar. Reduces the need for scrolling up and down. 

<details>
  <summary>Click to show preview</summary>
  <br>

  ![preview-1](https://github.com/xanthousm/text-gen-webui-ui_tweaks/assets/70198941/c5998420-9607-43d1-865f-65ec0f449ec2)

</details>

#### Sidebar options:
- Open sidebar on startup
- Dynamic height (shrink to fit)
- Custom width

Restart interface to apply setting changes. Save settings by editing params in scipt.py or using settings.json

https://github.com/xanthousm/text-gen-webui-ui_tweaks

## dynamic_context
A simple extension that replaces {{time}} and {{date}} on the current character's context with the current time and date respectively.
Also adds time context (and optionally date) to the last prompt to add extra context to the AI response.

https://github.com/elPatrixF/dynamic_context

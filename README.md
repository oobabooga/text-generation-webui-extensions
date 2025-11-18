# text-generation-webui-extensions

This is a directory of extensions for <https://github.com/oobabooga/text-generation-webui>

If you create your own extension, you are welcome to submit it to this list in a PR.



## LLM_Web_search

Give your local LLM the ability to search the web by outputting a user-defined command. The model decides
when to use the command and what to search.

<https://github.com/mamei16/LLM_Web_search>

## ad_discordbot (altoiddealer's discordbot)

A discord bot for text and image generation, with an extreme level of customization and advanced features.

- **Chat history management** - per-channel histories; auto-load on startup; resettable per channel
- **Advanced "Tags" System** - dynamically modify bot behavior (trigger custom responses, modify settings, swap characters/models, etc)
- **Image generation** - A1111/Forge/ReForge (ComfyUI planned); advanced settings handling; ControlNet & ReActor integration
- **Extensive TTS Support** - (alltalk_tts, kokoro_tts, coqui_tts, etc.); ***per-character*** voices; ***voice channel integration***
- **Slash Commands** - switch characters, change models, advanced image/text options, etc
- **Layered Settings Framework** - global, user-specific, character-based customizations; option to post real-time updates to dedicated channels
- **Context Menu Superpowers** - Right-click Regenerate, Edit, or Hide messages (even in deep history!)
- **More extra features** - Automatic model swapping, Dynamic Prompting, Starboard, etc.

<details>
<summary>
A few screenshots
</summary>
<img width="623" alt="Dynamic Prompting" src="https://github.com/user-attachments/assets/b15b8483-ef87-46f4-be37-ec70b1c9b992" />
<img width="416" alt="ContextCommands" src="https://github.com/user-attachments/assets/a39db2ba-b14a-494e-b848-cce528231d11" />
<img width="511" alt="controlnet" src="https://github.com/user-attachments/assets/e829895b-c993-449c-b7e7-6b17c2d29079" />
</details>

<https://github.com/altoiddealer/ad_discordbot>

## telegram_bot

Provides a cai-chat like telegram bot interface.

<https://github.com/innightwolfsleep/text-generation-webui-telegram_bot>

## Memoir+

Memoir+ a persona extension for Text Gen Web UI. Memoir+ adds short and long term memories, emotional polarity tracking. Later versions will include function calling. This plugin gives your personified agent the ability to have a past and present through the injection of memories created by the Ego persona.

<https://github.com/brucepro/Memoir>

## context-progress-bar-text-generation-webui

Adds a real-time progress bar below the chat input field that shows how much of the available context window is filled. 

https://github.com/mamei16/context-progress-bar-text-generation-webui

## AutoSave

An auto save extension for text generated with the oobabooga WebUI.

If you've ever lost a great response or forgot to copy and save your perfect prompt, AutoSave is for you!

100% local saving

<https://github.com/ill13/AutoSave/>

## Diffusion_TTS

Realistic TTS, close to 11-Labs quality but locally run, using a faster and better quality TorToiSe autoregressive model.

<https://github.com/SicariusSicariiStuff/Diffusion_TTS>

## SKDV's ComfyUI Image Generation

<p align="center">
	<img src="https://raw.githubusercontent.com/SkinnyDevi/skdv_comfyui/refs/heads/master/docs/logos.png" height="110px" alt="ComfyUI"/>
</p>

>This extension provides image generation from ComfyUI inside oobabooga's text generation webui.

>**Disclaimer**: this extension is in no way, shape or form associated with ComfyUI or SillyTavern.

### General features
- Customize any image parameters for ComfyUI generation:
	- Model
	- VAE
	- Resolution presets (with individual width & height)
	- Sampler
	- Scheduler
	- Steps
	- CFG Scale
	- Fixed and random seeds
- Generation buttons directly from the chat tab
- Generate image prompts from your text messages using your text models

### Roleplaying parameters
- Add quality parameters that apply to all characters
- Add custom prompts for different characters

### Workflows
- Import your custom workflows (API format workflows)
  - Use SillyTavern's custom variables to send to ComfyUI from WebUI!
- Send your avatar image to the workflow
- Send the character's avatar image to the workflow
- Workflow code editor (basic)

### Settings and Quality of Life
- Automatic model unloading for WebUI and ComfyUI models to save VRAM
- Extension updater
- Edit prompts before generating

<br/>

<details>
 <summary>Click to preview the interface</summary>
 <br/>

#### Extended hover menu actions
![Extended hover menu actions](https://raw.githubusercontent.com/SkinnyDevi/skdv_comfyui/master/docs/hover-menu-buttons.png)

#### Custom character prompts in chat
![Custom character prompts in chat](https://raw.githubusercontent.com/SkinnyDevi/skdv_comfyui/master/docs/character-prompts.png)

#### Generation parameters
![Generation parameters](https://raw.githubusercontent.com/SkinnyDevi/skdv_comfyui/master/docs/generation-parameters.png)

#### Shared character prompts
![Shared character prompts](https://raw.githubusercontent.com/SkinnyDevi/skdv_comfyui/master/docs/shared-character-prompts.png)

#### Image Prompt Editor
![Image Prompt Editor](https://raw.githubusercontent.com/SkinnyDevi/skdv_comfyui/master/docs/image-prompt-editor.png)

#### Workflow editor
![Workflow editor](https://raw.githubusercontent.com/SkinnyDevi/skdv_comfyui/master/docs/workflow-editor.png)

</details>

<https://github.com/SkinnyDevi/skdv_comfyui>

## SKDV Integrated TavernUI Characters

This extension features a character searcher, downloader and manager for any TavernAI
cards.

### General features

- Main page recent and random cards, as well as random categories upon main page launch
- Card filtering with text search, NSFW blocking\* and category filtering
- Card downloading
- Offline card manager
- Search and delete downloaded cards

\*_Disclaimer: As TavernAI is a community supported character database, characters may often be mis-categorized, or may be NSFW when they are marked as not being NSFW._

<details>
 <summary>Click to preview the interface</summary>
 <br/>

Main extension page with recent and random cards
![MainSection](https://raw.githubusercontent.com/SkinnyDevi/webui_tavernai_charas/master/docs/main-online.png)
Search online TavernAI cards
![CardSearcher](https://raw.githubusercontent.com/SkinnyDevi/webui_tavernai_charas/master/docs/main-searcher.png)
Advanced search filtering with card categories
![SearcherCategories](https://raw.githubusercontent.com/SkinnyDevi/webui_tavernai_charas/master/docs/searcher-categories.png)
Manage your offline cards
![offlineCardManager](https://raw.githubusercontent.com/SkinnyDevi/webui_tavernai_charas/master/docs/offline-cards.png)

</details>

<https://github.com/SkinnyDevi/webui_tavernai_charas>

## Playground for Writers

This extension provides an independent advanced notebook that will be always present from the top tab. It has many features not found in the notebook:

- Two independent Notebooks A and B that are always present, regardless of the mode
- Inline instruct (abilty to ask question or give task from within the text itself)
- Select and Insert - generate text in the middle of your text
- Perma Memory, Summarization, Paraphrasing
- LoRA-Rama - shows LoRA checkpoints and ability to switch between them
- LoRA scaling (experimental) - adjust LoRA impact using a sclider

<https://github.com/FartyPants/Playground>

## Virtual Lora

State of the Art Lora Management - Custom Collections, Checkpoints, Notes & Detailed Info

If you're anything like me (and if you've made 500 LORAs, chances are you are), a decent management system becomes _essential_. This allows you to set up multiple LORA 'collections', each containing one or more virtually named subfolders into which you can sort all those adapters you've been building for weeks; and add any notes about the LORAs or checkpoints. You can of course apply the LORAs or any of the checkpoints directly. It's a finer grained enhancement than Playground's Lora-rama, but it will be concentrating solely on LORAs and nothing else.

<https://github.com/FartyPants/VirtualLora>

## Twinbook

This extension combines chat and notebook in a very clever way. It's based on my above extension (Playground) but very streamlined for only Generation/Continue but with a little twist. You are in full control of both sides - the instruction side (left) and the result side (right) allowing you to steer LLM in the middle of text (or even sentence) by simply changing the instructions on left and clicking Continue on right.
For more trips how to use it, read the README

<https://github.com/FartyPants/Twinbook>

## AllTalk v2 TTS

Multi-engine TTS system with tight integration into Text-generation-webui.

- Integration with [Text-generation-webui](https://github.com/erew123/alltalk_tts/wiki/Text%E2%80%90generation%E2%80%90webui-Remote-Extension)
- Multiple TTS engine support:
    - Coqui XTTS TTS **(voice cloning)**
    - F5 TTS **(voice cloning)** 
    - Coqui VITS TTS
    - Piper TTS
    - Parler TTS
    - Other TTS engines [can be coded in](https://github.com/erew123/alltalk_tts/wiki/Guide-to-Integrating-New-TTS-Engines-into-AllTalk)
- Retrieval-based Voice Conversion [(RVC) pipeline](https://github.com/erew123/alltalk_tts/wiki/RVC-(Retrieval%E2%80%90based-Voice-Conversion))
- Customizable settings for each TTS engine
- Gradio web interface for easy management [Screenshots](https://github.com/erew123/alltalk_tts/discussions/237)
- Narrator function for using different voices for characters and narration
- Audio Transcoding to multiple formats (mp3, opus, etc.)
- Built-in documentation throughout
- Detailed [Github Wiki](https://github.com/erew123/alltalk_tts/wiki)
- [Quickstart guide](https://github.com/erew123/alltalk_tts/wiki/AllTalk-V2-QuickStart-Guide)
- **And much more**.....

Link to [AllTalk V2 GitHub](https://github.com/erew123/alltalk_tts/tree/alltalkbeta?tab=readme-ov-file#alltalk-tts-v2)

## Text To TTS WebUI

An extension that enables connecting to [TTS WebUI](https://github.com/rsxdalv/tts-webui) for narration. Requires TTS WebUI to
be installed, connects locally via OpenAI style `/v1/audio/speech/` endpoint.
Currently supports Kokoro TTS and ChatterBox TTS.

<https://github.com/rsxdalv/text-to-tts-webui>

## Emotivoice_RVC_TTS

An extension from yhyu13 with rvc custom voice

<https://github.com/okazaki10/Emotivoice_RVC_TTS>

## Kokoro TTS

TTS with Kokoro v1

- 26 Different voices to choose from

<https://github.com/h43lb1t0/KokoroTtsTexGernerationWebui>

## GPT-SoVITS_TTS

Extension to perform TTS using [GPT-SoVits](https://github.com/RVC-Boss/GPT-SoVITS), it utilizes its api_v2.

<https://github.com/marcos33998/GPT-SoVITS_TTS>

## FPreloader

An essential extension for extensions developers - it will reload your extensions without the need to reboot web ui

<https://github.com/FartyPants/FPreloader>

## LibreTranslate

Offline translate using the LibreTranslate local server.

<https://github.com/brucepro/LibreTranslate-extension-for-text-generation-webui>

## jsonformer

Force the output of your model to conform to a specified JSON schema. Works even for small models that usually cannot produce well-formed JSON.

<https://github.com/hallucinate-games/oobabooga-jsonformer-plugin>

## complex_memory

A KoboldAI-like memory extension. You create memories that are injected into the context of the conversation, for prompting based on keywords.

<https://github.com/theubie/complex_memory>

## google_translate_plus

Improved version of the built-in google_translate extension.

### Features

- Preserve paragraphs by replacing `\n` with `@` before and after translation
- Ability to translate large texts by splitting text longer than 1500 characters into several parts before translation
- Does not translate text fragments between `~`. For example, the text `Он сказал ~"Привет"~` will be translated as `He said "Привет"`

<https://github.com/Vasyanator/google_translate_plus>

## Lucid_Vision

This extension enhances the capabilities of textgen-webui by integrating advanced vision models, allowing users to have contextualized conversations about images with their favorite language models; and allowing direct communication with vision models.

<https://github.com/RandomInternetPreson/Lucid_Vision>

## LucidWebSearch

A web search extension for Oobabooga's text-generation-webui (now with nouget OCR model support).

This extension allows you and your LLM to explore and perform research on the internet together. It uses google chrome as the web browser, and optionally, can use nouget's OCR models which can read complex mathematical and scientific equations/symbols via optical character recognition.

<https://github.com/RandomInternetPreson/LucidWebSearch>

## code_syntax_highlight

<img alt="Code Syntax Highlight extension for oobabooga text-generation-webui" src="https://www.davg25.com/file/github-media/text-generation-webui-code_syntax_highlight/extension-header-1.png" width="750" title="Code Syntax Highlight extension">

An extension that adds syntax highlighting to code snippets, along with a toggleable copy-to-clipboard button and a performance mode for minimal impact on CPU usage.

Supports all interface modes and both light and dark themes.

<details>
  <summary>Click here to show preview images</summary>
  <br>
  
  | <img alt="Code Syntax Highlight extension for oobabooga text-generation-webui" src="https://www.davg25.com/file/github-media/text-generation-webui-code_syntax_highlight/extension-preview-1.png" width="100%" title="Code Syntax Highlight extension"> |
  | :----------------------------------------: |
  | <img alt="Code Syntax Highlight extension for oobabooga text-generation-webui" src="https://www.davg25.com/file/github-media/text-generation-webui-code_syntax_highlight/extension-preview-2.png" width="100%" title="Code Syntax Highlight extension"> |

</details>

<https://github.com/DavG25/text-generation-webui-code_syntax_highlight>

## web_rag

Web RAG -- Retrieval-Augmented Generation from Web content. Retrieves web data using the Links browser in command-line mode (must be installed on your machine). For Manual retrieval, specify the full URL. For Auto-RAG, the prompt is converted to a query and embedded in a URL (set up in UI).

<https://github.com/Anglebrackets/web_rag>

## stable_diffusion

Integrates image generation capabilities using Stable Diffusion.  
Requires a separate stable-diffusion-webui (AUTOMATIC1111) instance with enabled API.

**Features**

- Highly customizable
- Well documented
- Supports face swapping using SD FaceSwapLab extension, no need for loras when you want consistent characters

<https://github.com/Trojaner/text-generation-webui-stable_diffusion>

## SpeakLocal

A TTS extension that uses your host's native TTS engine for speech generation. 100% local, low resource usage, and no word limit. Primary use case is accessing your _text-generation-webui_ instance with a mobile device while conserving bandwidth with high token responses.

<https://github.com/ill13/SpeakLocal/>

## Chatbot Clinic

An extension designed to accelerate development of chatbot characters.
You can configure multiple versions of the same character, each
with its own context and generation parameters. Then you can chat with
all of them simultaneously, and vote on which replies you like best.
The results are displayed in a detailed statistics view.

<details>
<summary>Click to preview the interface</summary>
<br/>

### Configure as many chatbots as you like

![Step 1](https://github.com/p-e-w/chatbot_clinic/assets/2702526/cd6a0495-44ac-4eec-924b-622476b9fee7)

### Chat with all of them simultaneously

![Step 2](https://github.com/p-e-w/chatbot_clinic/assets/2702526/1a3e85a4-d563-4a01-a5b7-1f8e52ef4218)

### See which one you voted for the most

![Step 3](https://github.com/p-e-w/chatbot_clinic/assets/2702526/ff66b718-7c3e-4fad-a11a-bd19865da782)

</details>

<https://github.com/p-e-w/chatbot_clinic>

## sd_api_pictures_tag_injection

An expanded version of the included sd_api_pictures extension that features injecting character tags or arbitrary tags upon detection of specific strings into SD side prompt. Greatly improves character self-image stability and allows dynamic usage of LORAs.

<https://github.com/GuizzyQC/sd_api_pictures_tag_injection>

## Model Ducking

Model Ducking allows the currently loaded model to automatically unload itself immediately after a prompt is processed, thereby freeing up VRAM for use in other programs. It automatically reloads the last model upon sending another prompt.

<https://github.com/BoredBrownBear/text-generation-webui-model_ducking>

## More translators

This extension adds a lot more translators to choose from, including Baidu, Google, Bing, DeepL and so on.  
Need to run `pip install --upgrade translators` first.

<https://github.com/Touch-Night/more_translators>

## llm_steer-oobabooga

Steer LLM outputs towards a certain topic/subject and enhance response capabilities using activation engineering by adding steering vectors, now in oobabooga text generation webui!

<https://github.com/Hellisotherpeople/llm_steer-oobabooga/tree/main>

## piper_tts

An extension for using [Piper](https://github.com/rhasspy/piper) text-to-speech (TTS) model for fast voice generation. The main objective is to provide a user-friendly experience for text generation with audio. This TTS system allows multiple languages, with quality-voices and fast synthesis (much faster than real-time).

<https://github.com/tijo95/piper_tts>

## edge_tts

A simple implentation of Microsoft's free online TTS service using the [edge_tts](https://github.com/rany2/edge-tts) python library. Now supports RVC!

<https://github.com/BuffMcBigHuge/text-generation-webui-edge-tts>

## CodeRunner

Make a code execution environment available to your LLM.
This extension uses thebe and a jupyter server to run code on.

<https://github.com/xr4dsh/CodeRunner>

## Ooba_Dieroller

A super simple extension that reads dice notation (eg. "2d6") from input text, and rolls a random result accordingly, feeding that into the prompt.
Features support for modifiers (eg. "2d6+4") and advantage/disadvantage.

<https://github.com/TheInvisibleMage/ooba_dieroller>

## Emotivoice_TTS

A simple extension that can make model's output text-to-speach by Emotivoice (Chinese-English Bilingual by NetEase).

This model is super fast, usually cost only <0.2 sec for a ~20 words sentence on 3090 with ~1GB VRAM occupation.

<https://github.com/yhyu13/Emotivoice_TTS>

## Session_Manager

UI for saving/loading data and parameters between sessions, periodic autosaving

<https://github.com/bekkayya/session_manager/>

## XTTSv2

A variant of the coqui_tts extension in the main repository. Both use the XTTSv2 model, but this one has a "narrator" feature for text written \*between asterisks\*.

<https://github.com/kanttouchthis/text_generation_webui_xtts>

## Echoproof

Injects recent conversation history into the negative prompt with the goal of minimizing the LLM's tendency to fixate on a single word, phrase, or sentence structure. Provides controls for optimizing the results.

<https://github.com/ThereforeGames/echoproof>

## bark_tts

A simple implementation of Suno-AI's Bark Text-To-Speech with implicit multi-language and simple sound effect support.

The owner of the original extension has not had the time to maintain it. I have forked it to make it compatible with the current state of Oobabooga's textgen-webui and have improved/modified the text output that the AI reads to prevent errors with special character recognition.

(forked from the original and no longer maintained <https://github.com/minemo/text-generation-webui-barktts>)

<https://github.com/RandomInternetPreson/text-generation-webui-barktts>

## bark_tts

A simple implementation of Suno-AI's Bark Text-To-Speech with implicit multi-language and simple sound effect support.

<https://github.com/minemo/text-generation-webui-barktts>

## voicevox_tts

A simple extension that can make model's output text-to-speach by voicevox.
It also can make model's output auto translate to Japanese before it process by voicevox.
[VOICEVOX/voicevox_engine](https://github.com/VOICEVOX/voicevox_engine#%E3%83%80%E3%82%A6%E3%83%B3%E3%83%AD%E3%83%BC%E3%83%89) is needed.

<https://github.com/asadfgglie/voicevox_tts>

## EdgeGPT

Extension for Text Generation Webui based on EdgeGPT by acheong08, for a quick Internet access for your bot.

<https://github.com/GiusTex/EdgeGPT>

## UI Tweaks

Adds options to keep tabs on page (sticky tabs) and to move extensions into a hidden sidebar. Reduces the need for scrolling up and down.

<details>
  <summary>Click to show preview</summary>
  <br>

![preview-1](https://github.com/xanthousm/text-gen-webui-ui_tweaks/assets/70198941/c5998420-9607-43d1-865f-65ec0f449ec2)

</details>

#### Sidebar options

- Open sidebar on startup
- Dynamic height (shrink to fit)
- Custom width

Restart interface to apply setting changes. Save settings by editing params in scipt.py or using settings.json

<https://github.com/xanthousm/text-gen-webui-ui_tweaks>

## webui_langchain_agent

oobaboogas-webui-langchain_agent
Creates an Langchain Agent which uses the WebUI's API and Wikipedia to work and do something for you

Tested to be barely working, I learned python a couple of weeks ago, bear with me.

Needs `api` and `no_stream` enabled.

<details>
  <summary>Click to show preview</summary>
  <br>

![preview-1](https://user-images.githubusercontent.com/45816945/236649969-0d4fbab3-15e9-4cf0-88d0-71419e77d1cb.png)

</details>

<https://github.com/ChobPT/oobaboogas-webui-langchain_agent/>

## deepl_translator

A simple extension input and output translation by the deepl

<https://github.com/SnowMasaya/text-generation-webui/tree/deepl/extensions/deepl_translate>

## oobabot

Another Discord bot, with both command-line and GUI modes. Easy setup, lots of config options, and customizable characters!

- [**`oobabot`**](https://github.com/chrisrude/oobabot) -- command-line mode, uses Oobabooga's API module

- [**`oobabot-plugin`**](https://github.com/chrisrude/oobabot-plugin) -- GUI mode, runs inside of Oobabooga itself

<details>
<summary>
Oobabot Screenshots!
</summary>

| Config UI                                                                                         | In Action!                                                                               |
| ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| ![image](https://raw.githubusercontent.com/chrisrude/oobabot-plugin/main/docs/oobabot-plugin.png) | ![image](https://raw.githubusercontent.com/chrisrude/oobabot/main/docs/zombietaytay.png) |

</details>

<https://github.com/chrisrude/oobabot-plugin>

## long_term_memory

A sophisticated extension that creates a long term memory for bots in chat mode.

<https://github.com/wawawario2/long_term_memory>

## webui-autonomics

Adjust text generation parameters dynamically to better mirror emotional tone.

<details>
  <summary>Click to show preview</summary>
  <br>

![autonomic2](https://user-images.githubusercontent.com/108030031/232086809-57398b01-1412-4955-81f0-4adf21ba48c4.png)

</details>

<https://github.com/dibrale/webui-autonomics>

## Guidance API

An extension that goes with [guidance](https://github.com/microsoft/guidance/pull/221) in order to enable guidance to be used when generating text
for schemaful data

<https://github.com/danikhan632/guidance_api>

## dynamic_context

A simple extension that replaces {{time}} and {{date}} on the current character's context with the current time and date respectively.
Also adds time context (and optionally date) to the last prompt to add extra context to the AI response.

<https://github.com/elPatrixF/dynamic_context>

## api_advanced

An expanded version of api extension.

1. Provide Kobold-like interface (the same way as "api" classic extension)
2. **Provide advanced logic to auto-translate income prompts:**
   - You need to use multi_translate extension: <https://github.com/janvarev/multi_translate>
   - Set up param `'is_advanced_translation': True`, (set by default)
   - ...see the details in console
     - Due to advanced logic script splits income prompt by lines, and **cache translation results**
     - **Text quality feature:** when it generate English response, it cache it too (so you don't do double-translation English->UserLang->English next time)

<https://github.com/janvarev/api_advanced>

## multi_translate

An expanded version of the google_translate extension, that provide more translation options (more engines, save options to file, functionality to toggle on/off translations on the fly).

<https://github.com/janvarev/multi_translate>

## discord_bot

Discord integration for the oobabooga's text-generation-webui (Inspired by DavG25's plugin)

Currently it only sends any response from the chatbot to a discord Webhook of your choosing

Simply create a Webhook in Discord following this tutorial and paste the webhook URL under the chat box that will show after the plugin is enabled.

<details>
  <summary>Click to show preview</summary>
  <br>
  
  ![preview-2](https://user-images.githubusercontent.com/45816945/234896222-532ef597-3e26-48cc-8af2-7df33d471e1b.png)![image](https://user-images.githubusercontent.com/45816945/234899114-09381d3d-3deb-4f1f-8328-2567755cfe40.png)

</details>

<https://github.com/ChobPT/text-generation-webui-discord_bot>


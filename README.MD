# Awesome [AI-Horde](https://aihorde.net) resources

For information about the AI Horde, see [aihorde.net](https://aihorde.net). For official Haidra repos, see [haidra-org](https://github.com/haidra-org)

## Clients

### Apps

|Name|Description|Platform|Notes|
|--|---------|--|--|
|[Haidra-Org/Lucid-Creations](https://github.com/Haidra-Org/Lucid-Creations)|A simple client to create Stable Diffusion images without any dependencies or hardware requirements|Desktop (Native)|Official Stable Horde client supporting all image generation features as well as image ratings|
|[Haidra-Org/AI-Horde-CLI](https://github.com/Haidra-Org/AI-Horde-CLI)|python script integrating with the AI Horde via a command line interface|Desktop/CLI|Official Stable Horde client supporting all image generation features|
|[amiantos/aislingeach](https://github.com/amiantos/aislingeach)|Aislingeach is an iOS app for the Stable Horde, a crowdsourced distributed cluster of image generation workers|iOS||
|[amiantos/ealain](https://github.com/amiantos/ealain)|Ealain is a macOS screensaver that displays abstract, bauhaus style art generated with Stable Diffusion|MacOS||
|[aqualxx/stable-ui](https://github.com/aqualxx/stable-ui)|🔥 A frontend for generating images with Stable Diffusion through Stable Horde.|Web|Does not support all features of the Horde (Loras, SDXL). Still popular. Another UI is recommended. Try ArtBot or Lucid Creations!|
|[Efreak/stable-ui](https://github.com/Efreak/stable-ui)|🔥 A frontend for generating images with Stable Diffusion through Stable Horde|Web|A fork of aqualxx/stable-ui (above) adding support for SDXL. two images will be generated for every image requested if model is SDXL. Defaults to 1024x1024. Not recommended unless you're desperate for stable-ui's interface. Go use ArtBot instead!|
|[daveschumaker/artbot-for-stable-diffusion](https://github.com/daveschumaker/artbot-for-stable-diffusion)|A front end GUI for interacting with the Stable Horde / Stable Diffusion distributed cluster|Web|The best client 🥰|
|[Jokimax/OpenStableDiffusion](https://github.com/Jokimax/OpenStableDiffusion)|A simple android app for generating stable diffusion images using AI horde|Android||
|[LostRuins/lite.koboldai.net](https://github.com/LostRuins/lite.koboldai.net)|A zero dependency web UI for KoboldAI Horde|Web|
|[ndahlquist/stable-horde-flutter](https://github.com/ndahlquist/stable-horde-flutter)|~~An Android+iOS app for the Stable Horde~~|~~Android, iOS~~|This app is currently broken, and looking for a new maintainer|

### Plugins

|Name|Description|
|--|------|

### Bots

|Name|Description|Links|
|--|-------|--|
|[Haidra-Org/mastodon-ai-horde-generate](https://github.com/Haidra-Org/mastodon-ai-horde-generate)|A mastodon bot generating stable diffusion images as replies||
|[Haidra-Org/reddit-stable-horde-generate](https://github.com/Haidra-Org/reddit-stable-horde-generate)|A Reddit bot generating stable diffusion images as replies||
|[AceBeaker2/StableHorde-LemonBot](https://github.com/AceBeaker2/StableHorde-LemonBot)|A feature-packed multi-model text2image discord bot!||
|[Enerv/ai-horde-discord-bot](https://github.com/Enerv/ai-horde-discord-bot)|Discord bot written in Node.js adapted to the Pygmalion 6B model and integrated with the AI Horde endpoint gateway.||
|[OpenReplicant/DiscordPrototype](https://github.com/OpenReplicant/DiscordPrototype)|Prototype Discord bot integrating Kobold Horde LLM with Stable Horde diffusion & captioning. Intent recognition for advanced features, starter project.||
|[Pudzill/HordeTalk---KoboldAI-Horde-Chatbot](https://github.com/Pudzill/HordeTalk---KoboldAI-Horde-Chatbot)|Terminal chatbot. Powered by KoboldAI Horde.||
|[ZeldaFan0225/AI_Horde_Discord](https://github.com/ZeldaFan0225/AI_Horde_Discord)|A discord bot to interact with https://stablehorde.net||
|CraiyonArt Bot|Telegram bot|[![join telegram](https://img.shields.io/endpoint?label=CraiyonArtBot&style=flat-square&url=https%3A%2F%2Fmogyo.ro%2Fquart-apis%2Ftgmembercount%3Fchat_id%3CraiyonArtBot)](https://t.me/CraiyonArtBot)|
|[HarrisonVanderbyl/WriterBot](https://github.com/harrisonvanderbyl/WriterBot)|Discord bot|[website](https://harrisonvanderbyl.github.io/WriterBot/)|
|[TuringAI-Team/turing-bot](https://github.com/MrlolDev/turing-bot)|A discord bot for use the most popular game changing AIs. *Archived*|[![discord](https://dcbadge.vercel.app/api/server/uJDg2SxR8C?style=plastic)](https://dsc.gg/turing)

### Worker projects

|Name|Description|
|--|-------|
|[Haidra-Org/Simple-AI-Horde-Colab](https://github.com/Haidra-Org/Simple-AI-Horde-Colab)<br>[![colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/db0/Simple-AI-Horde-Colab/blob/main/The_Simple_Stable_Horde_Colab.ipynb)|Google Colab notebook for running a free Stable Horde worker|
|[Dynamedia|/ai-horde-notebook](https://github.com/Dynamedia/ai-horde-notebook)|Jupyter notebook for AI Horde dreamer workers|
|[Dynamedia/ai-horde-paperspace](https://github.com/Dynamedia/ai-horde-paperspace)<br>[![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://console.paperspace.com/github/Dynamedia/ai-horde-paperspace?machine=Free-GPU)|Paperspace notebook environment with Dockerfile for the image|
|[natanjunges/stable-diffusion-webui-stable-horde](https://github.com/natanjunges/stable-diffusion-webui-stable-horde)|Stable Horde client for AUTOMATIC1111's Stable Diffusion Web UI|
|[sdwebui-w-horde/sd-webui-stable-horde-worker](https://github.com/sdwebui-w-horde/sd-webui-stable-horde-worker)|Stable Horde Unofficial Worker Bridge as Stable Diffusion WebUI (AUTOMATIC1111) Extension|
|[ai-dock/ai-horde-dreamer](https://github.com/ai-dock/ai-horde-dreamer)<br>[![Docker Hub](https://img.shields.io/docker/pulls/dynamedia/ai-horde-dreamer)](https://hub.docker.com/r/dynamedia/ai-horde-dreamer)<br>[Vast.ai](https://cloud.vast.ai/?ref=62897&template_id=c967379624d5b34217274ebf4a422d94)|Docker image for AI Horde dreamer (Stable Diffusion) |
|[hordeautowebbridge/hordeautowebbridge.github.io](https://github.com/hordeautowebbridge/hordeautowebbridge.github.io)<br>[hordeautowebbridge.github.io](https://hordeautowebbridge.github.io)|A no-install JS web based Stable Horde Worker to bridge Automatic1111 API with Stable Horde API.|

## Other

### Resources to be used in developing AI Horde integrations

|Name|Description|
|--|-------|
|[Haidra-Org/AI-Horde-Styles](https://github.com/Haidra-Org/AI-Horde-Styles)|Styles to use to enhance Stable Horde prompts in various tools|
|[Haidra-Org/AI-Horde-Worker](https://github.com/Haidra-Org/AI-Horde-Worker)|This repo turns your PC into a AI Horde worker node|
|[Haidra-Org/horde-model-reference](https://github.com/Haidra-Org/horde-model-reference)|This package provides some tools to help manage the model metadata which AI-Horde uses|
|[Haidra-Org/AI-Horde-text-model-reference](https://github.com/Haidra-Org/AI-Horde-text-model-reference)|A refeference of text models that can be used in the AI Horde|
|[Haidra-Org/AI-Horde-Godot-Addon](https://github.com/Haidra-Org/AI-Horde-Godot-Addon)|A Godot addon for using Stable Horde|
|[Haidra-Org/AI-Horde-image-model-reference](https://github.com/Haidra-Org/AI-Horde-image-model-reference)|
|[Haidra-Org/horde-sdk](https://github.com/Haidra-Org/horde-sdk)|*A python sdk for creating workers and clients (requesting, generating, and rating images). Tazlin needs an official description for it. Seems to be in active development.*|
|[Nik77x/HordeWatcher](https://github.com/Nik77x/HordeWatcher)|little app to see all the people sharing their pcs in the koboldAI horde.|
|[Pudzill/StableHorde-text-template-py](https://github.com/Pudzill/StableHorde-text-template-py)|Bulky template for generating text with StableHorde. text_generation.py|
|[The-Free-MRE-Foundation/images](https://github.com/The-Free-MRE-Foundation/images)|Text to image MRE powered by Craiyon (dalle-mini) and Stable Horde (Credit to BenG)|
|[timius100/StableHordeAPI.py](https://github.com/timius100/StableHordeAPI.py)<br>[![PyPI](https://badge.fury.io/py/stablehordeapi.py.svg?branch=main&kill_cache=1)](https://badge.fury.io/py/stablehordeapi.py)|Simple Stable Horde API python wrapper|
|[ZeldaFan0225/ai_horde](https://github.com/ZeldaFan0225/ai_horde)<br>[![npm link](https://img.shields.io/npm/v/@zeldafan0225/ai_horde.svg?maxAge=3600&style=flat&logo=npm&color=ff5540)](https://www.npmjs.com/package/@zeldafan0225/ai_horde)|A package to interact with the stable horde API|
|[jan-oratowski/StableHorde.Api](https://github.com/jan-oratowski/StableHorde.Api)|C# Stable Horde API|
|[jozsefsallai/node-stablehorde](https://github.com/jozsefsallai/node-stablehorde)<br>[![npm link](https://img.shields.io/npm/v/stablehorde.svg?maxAge=3600&style=flat&logo=npm&color=ff5540)](https://www.npmjs.com/package/stablehorde)|Unofficial Node.js API client for Stable Horde. *Very old. I suggest checking out [ZeldaFan0225/ai_horde](https://github.com/ZeldaFan0225/ai_horde) instead*|
|[kevin51jiang/unified-diffusion](https://github.com/kevin51jiang/unified-diffusion)|Stable Diffusion for Unity, running on Stable Horde|
|[db0/KoboldAI-Horde-Bridge](https://github.com/db0/KoboldAI-Horde-Bridge)|Turns KoboldAI into a crowdsourced distributed cluster|
|[recrudesce/stablehordeapi](https://github.com/recrudesce/stablehordeapi)|Hopefully an library to interact with Stable Horde|
|[tijszwinkels/ChatGPT-KoboldAI-horde-proxy](https://github.com/tijszwinkels/ChatGPT-KoboldAI-horde-proxy)|OpenAI Completion / Chat Completion compatible API for the language models running on the open and free KoboldAI Horde|

### Resources used internally by AI Horde

|Name|Description|
|--|-------|
|[Haidra-Org/AI-Horde](https://github.com/Haidra-Org/AI-Horde)|A crowdsourced distributed cluster for AI art and text generation|
|[Haidra-Org/hordelib](https://github.com/Haidra-Org/hordelib)<br>[![PyPI](https://badge.fury.io/py/hordelib.svg?branch=main&kill_cache=1)](https://badge.fury.io/py/hordelib)|A wrapper around ComfyUI to allow use by the AI Horde.|
|[Haidra-Org/AI-Horde-Discord](https://github.com/Haidra-Org/AI-Horde-Discord)|A discord bot to interact with https://stablehorde.net. You'll likely want ZeldaFan's bot instead(?)|
|[Haidra-Org/Haidra-Web](https://github.com/Haidra-Org/Haidra-Web)|HTML / CSS front-end for Haidra info and landing page |
|[Haidra-Org/.github](https://github.com/Haidra-Org/.github)|???|

### Miscellaneous projects

These may or may not even be AI-Horde related tools. They mostly have no descriptions. Commentary in *italics*.

|Name|Description|
|--|-------|
|[sdwebui-w-horde/horde-models](https://github.com/sdwebui-w-horde/horde-models)|Stable Horde Supported Model References<br>*??? Not the official horde model reference*|
|[AesSedai/horde-control-tower](https://github.com/AesSedai/horde-control-tower)|Horde Control Tower is an open source AI Horde moderation utility|
|[Breadcord-Toasts/StableHorde](https://github.com/Breadcord-Toasts/StableHorde)|*Appears to be a discord integration*|
|[CazCzw/StableHordeUnity](https://github.com/CazCzw/StableHordeUnity)|*A single .cs file.*|
|[JamDon2/ai-horde-bot](https://github.com/JamDon2/ai-horde-bot)|*An (old?) discord bot. I **think** this was replaced with [ZeldaFan0225/AI_Horde_Discord](https://github.com/ZeldaFan0225/AI_Horde_Discord)*|
|[JamDon2/stable-horde-api](https://github.com/JamDon2/stable-horde-api)|*An (old?) javascript api for interacting with the Horde. I **think** this was replaced with [ZeldaFan0225/ai_horde](https://github.com/ZeldaFan0225/ai_horde)*|
|[JamDon2/stable-horde-next](https://github.com/JamDon2/stable-horde-next)|*Appears to be a very old Horde frontend. The link in the readme does not work.*|
|[KyuubiYoru/StableHordeProxy](https://github.com/KyuubiYoru/StableHordeProxy)|*A C# project of unknowm use*|
|[Seikho/ai-horde](https://github.com/Seikho/ai-horde)|Stable Horde Request library|
|[VilotStar/StableHorder](https://github.com/VilotStar/StableHorder)|*Looks like a rust project for requesting images*||
|[XiuruJin/AI-Horde](https://github.com/XiuruJin/AI-Horde)|*Shows up in github search, but doesnt exost???*|
|[gerardosantacruz/Stable-Horde-App-BasicDemo](https://github.com/gerardosantacruz/Stable-Horde-App-BasicDemo)|*Very old. No documentation.*|

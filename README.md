<hr>
<p align="center">
  <a href="https://imgbb.com/">
    <img src="https://i.ibb.co/JWKnvdBV/voice2gpt.png" alt="icon-128" border="0">
  </a>
</p>
<hr>

# voice2gpt: Multi-function GPT TTS and Speech-To-Text extension (formerly talkgpt)

Forked and updated with contributions from community, now compatible with the latest OpenAI models, extension will be gradually improved.

--------------------------

<p>
  <strong>voice2gpt</strong> is a Google Chrome and Microsoft Edge extension that allows users to talk with the ChatGPT AI using their voice (speech recognition) and listen to the bot's answers with a voice (text-to-speech), rather than just by typing. This extension is a fork based on the original <strong>TalkToGPT</strong> extension by C-Nedelcu. 

  With voice2gpt, users can speak to the AI and receive spoken responses, making the interaction feel more natural and conversational. It offers the experience of having your own personal assistant, similar to Iron Man's Jarvis. Beyond entertainment, it's a valuable tool for helping the elderly and people with disabilities interact with ChatGPT. 

We now support <strong>ElevenLabs API</strong> integration, enabling users to create custom voices for text-to-speech! You can select which <strong>ElevenLabs</strong> model produces the speech, for example <em>Eleven Flash&nbsp;2.5</em> for low latency or <em>Eleven Multilingual&nbsp;V2</em> for higher quality output.

  Once started, voice2gpt displays a menu on the top-right corner of the page where users can access settings (such as voice, language, and more), skip the current message, toggle voice recognition on or off, and toggle text-to-speech on or off.

  The settings menu can be seen below. Settings are saved in a cookie and reloaded automatically each time you activate the script.
</p>

<hr>

![111111](https://i.ibb.co/WxrgcLC/111111.png)


# How to install

A of 07/07/2024 the extension is available on Chrome Web Store, just install it from here: 

[voice2gpt Extension (click here to download)](https://chromewebstore.google.com/detail/voice2gpt/ddfdbpdndbanjaffmoapdpmgnhbcigfl?authuser=8&hl=es-419)

Manual Installation:
1. Go to releases and download latest .zip
2. Extract the .zip file in a folder somewhere, move chrome-extension folder (this is the folder you will use to install the extension)
3. Follow this tutorial to install the extension in Chrome/Edge in dev mode: https://webkul.com/blog/how-to-install-the-unpacked-extension-in-chrome/

# FAQ

**Q: Which web browsers are supported?** A: This extension is designed for Google Chrome and Microsoft Edge, desktop version only. The extension will not work in any other web browser, especially not mobile browsers, because these browsers do not support the necessary APIs for speech recognition and speech synthesis.

**Q: Can you make it speak faster or in a different voice or language?** A: Yes, use the settings menu. You can select a variety of settings among which the speech rate, voice type, and language.

**Q: What is the purpose of this project?**
A: Originally, it was mostly a fun proof of concept. This AI is mind-bogglingly intelligent and I had a deep desire to converse with it orally, to make it more interesting. Surely OpenAI themselves will make a proper voice-controlled version of ChatGPT in the future, at which point my project will be rendered useless. For now, it seems to be helping people with disabilities / visually impaired people, so I'm going to be actively working on the project for as long as I can, as a form of contribution to society.

**Q: Is it safe to use?**
A: Yes, it's simple javascript code that will execute only in the context of the ChatGPT webpage. It doesn't request any particular permissions, and it is fully open source. As soon as you navigate away from ChatGPT, everything is cleared, except for the addon settings.

**Q: Will it always work?**
A: it might not work indefinitely, and here's why. The code is based on the current HTML structure of the ChatGPT page. If OpenAI change the HTML code, this project will likely stop working. I will probably keep updating it to maintain compatibility, but I'm not sure I'll be doing that forever. If you want to contribute to the project you are more than welcome to submit your own changes through Github.

**Q: I have an error or a problem...**
A: Feel free to update the javascript yourself and propose changes on Github, or simply report the issue if you aren't a programmer.

**Q: Can I make changes to your code?**
A: Yes, feel free to make changes, and do whatever you want, commit, fork, just have fun.

**Q: How do I know what languages are supported?**
A: this is entirely based on the web browser APIs (Google Chrome, Microsoft Edge), so you need to ask Google or Microsoft, as I cannot provide an up-to-date answer. I've only tested it with English, French, and Chinese. The languages in the settings menu are the same ones found on the Google and Edge demos.



    

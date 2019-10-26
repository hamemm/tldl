## tl;dl - keyword extracting application for text, audio and video

Too Long Didn't Listen is an application for automatic keyword/keyphrase extraction from video, audio and text. 

- Since Mathematica does not have integrated video support, the audio extraction from video is performed using external API (YoutubeDL). 
- Audio is transcribed using [SpeechRecognize](https://reference.wolfram.com/language/ref/SpeechRecognize.html). 
- Keyword extraction form text is based on [TextRank algorithm](https://www.aclweb.org/anthology/W04-3252.pdf).

### Built with:
* Wolfram Mathematica 12.0
* [Youtube DL](https://github.com/ytdl-org/youtube-dl)

Winner of [Wolfram Hackathon 2019](https://www.wolfram.com/events/technology-conference-am/2019/hackathon.en.html).

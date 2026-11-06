# My Deer Friend Nokotan

Deer, oh deer. Absolute cinema.

## Available formats
|Name|Description|Status|
|-|-|-|
|`shikairo-days.ass`|Anime opening theme|In progress|
|`futari-no-honey-fixed-font.ass`|Anime ending theme|Pending|

## Source used
- Audio: Official CD
    - Alternative: YouTube Music ([OP](https://music.youtube.com/watch?v=r4AmRaKoJAE), [ED](https://music.youtube.com/watch?v=wgrjPSNZYno))
- Japanese lyrics: Official CD jacket image
- Romaji transliteration: [Fajar from UtaTime](https://www.utatime.com/global/lyrics/shika-bu/shikairo-days/#Romaji)
- English translations:
    - YouDeer fansub group (extracted as op-eng-youdeer.txt)
    - [Thae Rin from UtaTime](https://www.utatime.com/global/lyrics/shika-bu/shikairo-days/#English)

## Font selection
Coming soon!

## How to view the subtitles?
- Add the audio file to this project
    Due to obvious reasons, you will have to find your own song source. Anything based on the CD release will work, as long they're in an audio codec that your player can handle.
    - Which is anything today. Players are pretty good. May I suggest mpv?
- Download fonts as defined in `Font Selection`.
    - You will need these later in MKVToolNix
    - Noto Sans JP download is straight from GitHub due to specificity that is this project was built on Linux and they have a different font name compared to Windows.
        - DO NOT SKIP THIS STEP FOR NOTO SANS JP. BUILT IN WINDOWS FONTS DO NOT WORK.
- Extract the fonts to this project directory.
    TODO(chong601): _**create a scratch directory so those files aren't tracked.**_ You will fuck one of the project by uploading copyrighted stuff at some point. Be warned. Past Chong wrote this with 1h of sleep on a fucking Sunday has warned you._
- Install MKVToolNix. You will need this for every project released here.
- Load the `kxs-op-2997.mp4`, the song file and the subtitle file.
    <img style="width: 854px; height: 480px" src="images/mkvtoolnix-first.png"></img>
- Click on Attachments and drag the fonts into the "Attachments to add".
    <img style="width: 854px; height: 480px" src="images/mkvtoolnix-second.png"></img>
    - For Noto Sans, you would want to have the Bold added at minimum (NotoSansCJKjp-Bold.otf) 
        The screenshot is wrong and I assumed it's correct. (.ttc (TrueType Collections) files are not 100% universally supported, only TrueType Font (.ttf) and OpenType Font (.otf) are well supported)
- Click "Start Multiplexing"
- The generated files will be in the path specified in Destination file in Input tab.
- Open the files in a supported player and enjoy the jank. And my regrets not rechecking this work. It's permanent. `original` and `fixed-font` versions are permanently broken by choice of yours truly.

## Screenshots

Coming soon!
# ASSubtitles

Because IT gets a bit boring at times. Or vexing. So we do subtitles. For the senerity of Not Doing IT™

##  OK. WTF is ASSubtitles?

As the project repository says. **AS**S **Subtitles**. A repository of all of my subtitle works between August 2025 until about January 2026 where my productivity falls down the cliff and frustration grows to the peak of "4h travel on public transport sucks".

ASS as in the freaking format: **A**dvanced **S**ub**S**tation Alpha. Or **ASS**A. Or **ASS** 4+. Depends on which one you prefer.

Yes. The file extension is .ass. Deal with it™.

And yes, you're viewing the subtitle as the "video". All video files included are either dark/black background, or has at least the anime series logo as the background. It's a non-negotiable condition: video is needed, else there's nothing to draw to.

Think of this repo as a very roundabout .lrc file. For songs. But with _animations_. I love animations.

## WHY. WHY DO YOU DO This.
Few things
- Curiousity (a huge factor of it is)
- My slight sadness towards the current state of fansubs (it's a dying art)
- The format name is just hilarious to explain to a lay person.

### Curiousity
It started with Lycoris Recoil binge in end of July 2025. Where a single 1m30 OP is 35 MB of .ass.

\> 30k of lines. Just for some subtle animations. And INSANE animations.

Another reason is because some fansubs has rather opinionate ways on some stuff mainly maintaining Japanese honorifics, or to outright replace them to Westen honorifics instead. And minor translation style choices (kebab vs kabob kinda thing.)

### Fansub groups are dying. Even since 2010.
Many fansub groups have went away (harder) since the advent of online streaming services exist. They're already under threat because of the harsh reality of fansubs: the bar is high that not many fansub groups survive when other groups are doing much better (big teams, great translation quality and consistency).

Bad fansub groups die early.

A few still stuck around:
- Good Job! Media (GJM). They're truly a Schrodinger's Fansub group.
- Kaleido-subs (unofficially called Stalleido. Aptly named)
- Chihiro-Fansubs
- SubsPlease, from the ashes of HorribleSubs, the go-to for current anime season releases

Others have went away:
- UTW (they're ONLY focusing on Fate series, likely infinitely sleeping)
- Coalgirls. The releaser of FAT releases.
- Doki Fansubs. Arguably my most picked fansub group, Chihiro-Fansubs are the 2nd one. 
    Allegedly was working with a new anime production company and is working on official translations (holo/hologfx is one of them), but no news after years of no updates. Some managed MangaDex (mainly ixlone). Rest are unknown. RIP.
- HorribleSubs. Gone after 2020 for no good reason. SubsPlease took over though!

Fansubs still deliver though: better encodes, better translations, better enganement, quality over speed (for the most part)


## Help wanted.

I am not perfect. Like what humans are typically known for.

All subtitle files are qualified except genesis subtitle version for kxs OAD OP.

Timing improvements, Japanese Romanizations and English translations are welcome. Even styling, but that will be added as a separate subtitles if it diverges too much.

In other words: I want to preserve the original styling, but that shouldn't limit your creativity to make it nicer!

To contribute, create a pull request (heavily encouraged) or an issue with the changes (handled when time permits). You will be credited in the README.

## Project catalog

Coming soon! They will be populated based on what's coming out of my pipeline (preferably from the first project in August 2025 first.)

|Song/Album name|Anime series (if applicable)|Project inception date|Status|Subtitle style "Version"|
|-|-|-|-|-|
|Futari no Honey Boy|Kiss x Sis (OVA)|2026-08-04|Done|Jank.|

## Player support matrix

#### Short answer
mpv. That's the officially sanctioned supported player of choice (read: every fansub groups out there use this because yes).

For the prpose of my subtitles:
- MPC-HC (clsid2) version is OK
    - Some projects do have issues with subtitles missing when panning is done with embedded subtitles. Drag-and-drop the files after the video is loaded fixes that.
        No idea why this works, but that's happend to two projects I work on so far.
- VLC desktop variants are OK
    - Mobile version is hot garbage. Don't use them (for now, Android ones have broken secondary/primary animations. No idea if iOS have the same issue)
- Heard PotPlayer works fine
- Most Android video players will fail this. Hard-sub them manually.
    - Handbrake and mpv handles them fine. mpv is the first choice (see above)

#### Longer explanation
While most players out there supports ASS format, no players out there are identical.

##### OK. What's the actual support

##### MPC-HC
MPC-HC has their own libass version that is handled through Internal Video Renderer (IVR) and their variants and those handles subtitles in slightly different ways. **libass** must be enabled in the Output setting. Non-libass subtitle presentation is _weird_.

VSFilter is an alternative. In fact it's the _official_ standard (especially the OG VSFilter). libass is an "almost VSFilter 1:1 implementation" that is cross-platform while VSFilter is Windows-only.

Some project has an issue where panning the video will immediately lose the current-presented lines, including legends and background color.
- Workarounds: Drag and drop the files into the player. DO NOT rename them as the same name as the video, that triggers the exact same issue as if you're embedding it in.
At least what I remember from memory.

TODO(chong601): Add some explanations on some weird quirks you have seen so far.

# License

This is complicated.

### Third-party sources
- Varies. Details are in LICENSE.third-party.md (coming soon)
- Lyrics, composition, anything of musical is owned by respective music right societies/record albums/artists. All rights reserved.
- Transliterations/translations are owned by the respective locations that I used from. License varies. They're linked in the repos as needed and are annotated as needed.

### Anything by me
- Licensed under WTFPL. Full details are in LICENSE.txt
- Applies to subtitle file, design, transitions, coloring, timing, code, jank, regrets, translations/Romanizations by me (Full transparency: May include Claude assistance where applicable)


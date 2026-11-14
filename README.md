<img src="icon.png" width="96" alt="">

# Podcast Recorder

A podcast recorder that runs entirely in your web browser. No install, no account, and your audio never leaves your computer.

**▶ Use it here: https://harleyloft47-king.github.io/podcast-recorder/**

Open the link in Chrome, Edge, Firefox or Safari, click **Enable microphone**, allow the mic, and press **Record**.

## Features

- **Lossless recording** to 16-bit WAV, saved in the browser as you go, so a crash or closed tab doesn't lose a take
- **MP3 export** for publishing (96 kbps mono / 128 kbps stereo)
- **✨ Polish:** one click to reach podcast loudness (−16 LUFS stereo / −19 LUFS mono), gentle compression, a −1 dB peak limiter, and silence trimmed from the start and end. Creates a new take and keeps the original.
- **✂ Trim:** drag handles on a waveform to cut the start and end
- **Soundboard:** 14 built-in sounds (intro and outro themes, transition whoosh, sting, applause, drumroll + crash, ba-dum-tss, air horn, correct-answer ding, wrong-answer buzzer, sad trombone, record scratch, crickets, ta-da) plus your own sounds. Rename, replace or delete pads; keys 1–0 play the first ten; everything you play is recorded. The built-in sounds are synthesized in the browser, so they're original and free to use on your show
- **Co-host mic:** record two USB mics on separate tracks (plus a soundboard track), then download each person's track or a mix
- **Markers** (press M) that export as an Audacity labels file
- **Notes** for each take: show notes, guest names, links
- **3-2-1 countdown**, **length goal** with a chime, **headphone monitoring**, and live level meters with a clip light

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| Space | Record / pause / resume |
| M | Drop a marker |
| S | Stop and save the take |
| 1–9, 0 | Play soundboard pads 1–10 |

## Tips

- Wear headphones when using the soundboard or "Hear myself", so the mic doesn't pick the sound up again.
- Aim for level-meter peaks between −12 and −6 dB.
- Takes are stored in your browser for this site. Download the ones you want to keep, especially before clearing browsing data.
- MP3 export loads an encoder ([lamejs](https://github.com/zhuker/lamejs)) from a CDN the first time it's used, so it needs an internet connection.

## Run it offline

`index.html` is the whole app. Download it and open it in a browser.

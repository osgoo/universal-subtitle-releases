# Universal Subtitle: offline AI subtitle generator for Windows

Universal Subtitle is a Windows desktop app that turns your own video or audio
files into subtitles with Whisper speech recognition running on your PC. You
can review and fix the cues, translate them, export SRT or VTT, or burn the
subtitles into an MP4.

**[Download the latest Windows installer](https://github.com/osgoo/universal-subtitle-releases/releases/latest)**
· [Website](https://universal-subtitle-founding-alpha-20260731.jojojojo87786556.chatgpt.site/)
· [2-minute demo](https://www.youtube.com/watch?v=0g25mTNIvac)
· Microsoft Store: search "Universal Subtitle"
· [Pay what you want](https://buy.polar.sh/polar_cl_DrwP2bKjQOiEoyFX7tn4q5P7NWzkgYKlCQUIH09oIvE)

## What it does

- **Transcribe locally.** Speech recognition uses Whisper on your own computer.
  Your media is not uploaded for transcription. The speech model is downloaded
  once on first use; after that, transcription works without internet.
- **Review and edit.** Fix text and timing, split or merge cues, and play the
  video next to the subtitle list.
- **Translate (optional).** Translate subtitles with your own Gemini API key.
  Only subtitle text is sent to the provider you choose, and you pay that
  provider directly.
- **Export.** Save original, translated or bilingual SRT/VTT files, or burn
  subtitles into a hard-subtitled MP4.
- **Stay updated.** The app checks this repository for new versions and
  installs signed updates from inside the app.

## Who it is for

YouTubers, podcasters, teachers, course creators, translators and anyone who
needs subtitle files for their own videos without a monthly subscription or
uploading media to a cloud service.

## Install

1. Download `Universal.Subtitle_<version>_x64-setup.exe` from
   [Releases](https://github.com/osgoo/universal-subtitle-releases/releases/latest).
2. Run it. Windows SmartScreen may warn because the installer is new and not
   yet code-signed with a Windows certificate; choose **More info → Run anyway**
   if you trust this source.
3. Open Universal Subtitle, import a video, and press **Transcribe**.

Requirements: 64-bit Windows. A faster computer shortens transcription time;
long videos on older laptops can take a while.

## Price

Universal Subtitle is in early alpha and is **pay what you want, from $0**.
Paying is optional and supports development.

## Status and limits

- Early alpha: expect rough edges and quick changes.
- Transcription accuracy depends on audio quality and language; always review
  the result before publishing.
- Translation is not offline; it uses the provider and key you choose.
- Use it only on media you own or are allowed to subtitle.

## Release files

Each release contains the Windows installer, its update signature (`.sig`)
and `latest.json`, which the app's built-in updater reads. The application
source code is not published in this repository.

## Feedback

Questions and bug reports: email universalsubtitle@gmail.com.

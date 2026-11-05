# OpenFilm community skills

Skills for [OpenFilm](https://github.com/openfilm/openfilm) that are not among the ten official ones, and agent video
skills people use alongside it. OpenFilm's own Discover page lists only the official ten; this list is for the rest.
[中文](README.zh-CN.md)

## Add one

In OpenFilm, open Skills, choose **Add a skill** and paste the link from the table. A link to a folder inside a repository
(`.../tree/main/<folder>`) works too. From a terminal: `npx openfilm skill add <link>`. A skill added to OpenFilm is on
in every project; you can turn it off in Skills.

## Made for OpenFilm

Each one follows OpenFilm's [skill rules](https://github.com/openfilm/skills/blob/main/SPEC.md): a short brief, and a
script only where it gives the agent something it cannot get another way.

| Skill | What it makes | Needs | Licence |
| --- | --- | --- | --- |
| [web-demo](https://github.com/WEBGRS/openfilm-web-demo) | A demo of a web product filmed from a list of steps, filmed again after each release with the edit kept; voice-over follows its step; the same take as a written guide | Chrome or Edge, FFmpeg | MIT |
| [app-demo](https://github.com/WEBGRS/openfilm-app-demo) | A demo of a Windows program filmed while you work it, with a smooth pointer and a camera that moves in on each click | Windows 10 or 11, FFmpeg 8 | MIT |
| [preview-first](https://github.com/WEBGRS/openfilm-preview-first) | The whole film as placeholder cards within minutes, then pictures, then sound, each after you approve; paid use counted before it is spent | nothing | MIT |
| [talking-head](https://github.com/WEBGRS/openfilm-talking-head) | A talking-to-camera recording without the ums, stumbles and dead air, cut only in pauses, with key words, a name card and a cover | a transcription service in OpenFilm | MIT |
| [dub](https://github.com/WEBGRS/openfilm-dub) | A voiced film in another language: the voice-over said again, text and subtitles translated, every picture still on its word | a voice-over service with voices in that language | MIT |
| [footage-cut](https://github.com/WEBGRS/openfilm-footage-cut) | A film cut from your own clips, each shot chosen for what is being said, to your narration or the story in the footage; its script logs a folder of clips shot by shot | FFmpeg; a transcription service for clips with speech | MIT |
| [beat-cut](https://github.com/WEBGRS/openfilm-beat-cut) | A film cut to its music: every change on a beat, scene changes on the bars, the best shot where the music lifts; its script measures the music and checks every cut in frames from the nearest beat | FFmpeg | MIT |
| [borrow-style](https://github.com/WEBGRS/openfilm-borrow-style) | Your own footage in the packaging of a film you like (its pace, cuts, colour, captions and sound) with none of its content, and that packaging saved as your own house-style skill | FFmpeg | MIT |
| [reframe](https://github.com/WEBGRS/openfilm-reframe) | Landscape footage re-framed for a vertical, square or 4:5 film: each shot cropped onto what matters in it, the crop following the subject only when it moves; its script measures every shot and draws the crop for checking | FFmpeg | MIT |
| [case-film](https://github.com/WEBGRS/openfilm-case-film/tree/main/skills/case-film) | A narrated documentary about a real case: every line on real footage or documents, with names, dates, chats and maps drawn in; one case.json is the shot list | FFmpeg; a Tianditu key (or another tile source) for maps | MIT |
| [film-check](https://github.com/WEBGRS/openfilm-case-film/tree/main/skills/film-check) | Not a film: every frame and every second of sound of a finished film checked for flashes, jumped frames, frozen stretches, black frames, clicks, covered words and soft pictures, each with its time | FFmpeg; Chrome or Chromium for covered words | MIT |
| [video spec template](https://github.com/WEBGRS/openfilm-skill-template) | Not a film: blank templates for writing your own rules (rhythm, pictures, subtitles, sound) and a series (opening, closing and subtitle look copied into every episode) as skills, and a filled-in explainer example | nothing | MIT |

Not a skill, but made for OpenFilm: [local-voice](https://github.com/WEBGRS/openfilm-local-voice), voice-over made on
your own computer (Kokoro voices, and Qwen3-TTS for higher quality or your own voice) with timed subtitles. Add it in
Settings → Providers → Custom services.

## Other agent video skills

These are general agent skills, not written for OpenFilm. Each makes its own video (or its own pages and code); in
OpenFilm, what it makes becomes a clip of your film. They are listed because people in the OpenFilm community use them.
Read each licence before you publish what you make with it.

| Skill | What it makes | Built on | Licence |
| --- | --- | --- | --- |
| [video-shotcraft](https://github.com/Vincentwei1021/video-shotcraft) | Product promo films from a web project: real page captures, shot cards, cuts on the beat | Remotion | Apache-2.0; its README notes that companies may need a paid Remotion licence |
| [xilo-opus-video](https://github.com/Kianzzz/xilo-opus-video/tree/main/skills/xilo-opus-video) | Three plans for a video with a preview each, then the chosen one built as a code page and rendered to MP4 | Canvas, WebGL, Three.js, Remotion and others | MIT |
| [lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar/tree/main/plugin/skills/lemo-opuscar) | Short films made in code in one of its library's styles, or one you make yourself; explainers from real material and films cut from archive footage | its own frame-by-frame renderer | MIT for code and docs; demo films CC BY 4.0, except three demo voice tracks |
| [huashu-art-motion](https://github.com/alchaincyf/huashu-art-motion) | Art and science-explainer animation in 36 styles; the brief is in Chinese | Python, Playwright | MIT, except its character art, stroke data and fonts |
| [dashi-animationstyle](https://github.com/chuspeeism/dashi-animationstyle) | 15 to 60 seconds of your Chinese voice recording made into a 1080p video with subtitles, in one of 7 drawn styles | Canvas, headless Chrome | MIT, except the example recording |
| [wtt-code-animation-studio](https://github.com/WaterDJiang/Wattter_openSkills/tree/main/wattter_skills/wtt-code-animation-studio) | An idea, article or script turned into a Chinese script, a storyboard, editable source and a video with sound | Canvas or p5.js | No licence file; the repository's README says CC BY-NC-SA 4.0, non-commercial |

Not a skill: [mg-styles-15](https://github.com/Vincentwei1021/mg-styles-15), fifteen 10-second motion-design films,
each with its full prompt and source, to paste into an agent. MIT.

Licences and requirements were read from each repository on 2026-10-30.

## Suggest one

Open an issue or a pull request with the link. A skill is listed when its repository is public, has a SKILL.md an
agent can read, and says under what licence it can be used.

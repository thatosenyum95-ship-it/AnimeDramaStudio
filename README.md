# AnimeDramaStudio — Story to Video 3D

Browser-based story-to-video studio inspired by the workflow of TubeTube, implemented without AI or AI APIs.

## Workflow
1. Paste a story, dialogue, or song lyrics.
2. Generate a storyboard locally by splitting paragraphs/sentences into scenes.
3. Pick a visual theme, 3D character, environment, movement, camera and subtitles for each scene.
4. Upload music or recorded narration.
5. Preview the full sequence and export a single video via browser MediaRecorder.
6. Save/load project settings as JSON.

## Included
- Stylized primitive 3D characters: Aisyah (hijab), Haru, and Miko the cat.
- 3D environments: sakura garden, classroom, night city, sunset hills.
- Basic motion presets and subtitle overlays.
- Browser text-to-speech for dialog preview.
- Music/narration upload.
- WebM/MP4 export where supported by the browser.
- Local JSON project save/load.

## Live website
https://thatosenyum95-ship-it.github.io/AnimeDramaStudio/

## Important limitations
- No AI or AI APIs are used. The storyboard is generated with text splitting rules, and visuals use prebuilt Three.js geometry; it does not generate new AI images or AI video.
- The character models are simple stylized prototypes, not professional anime rigs.
- Three.js loads from a CDN, so internet access is needed. WebGL is required.
- Text-to-speech is preview only. To include spoken narration in the exported video, upload a narration recording.
- Export format depends on MediaRecorder support; WebM is more commonly supported than MP4.
- Audio files are not embedded in the saved JSON project; reselect audio when reopening.

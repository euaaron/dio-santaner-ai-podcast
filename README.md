<div align="center">
    <img src="./assets/images/Podcast_Logo.png" width="96px" />
</div>
<div align="center">
    <small>Universia - Fundamentos de IA Generativa, apresenta:</small>
    <h1>The AI Podcast Challenge</h1>
</div>

This is a repo containing files for the AI Podcast challenge from "Universia - Fundamentos de IA Generativa", a DIO/Santander bootcamp.

## Image Generation

To start I generated a couple images using Nano Banana on [Google AI Studio](https://aistudio.google.com/). You can see all the process and result at [Image Generation](./ImageGenerationPrompts.md) section, in a separated file.

## Script Generation

Then I generated a script using GPT-5 on [Microsoft Copilot](https://copilot.microsoft.com/).

## Speach Generation

Finally I went to Google AI Studio again but now at the `/generate-speech` endpoint, pasted the script and added `Read aloud in podcast interview style.` on top of it. Then I edited Voice settings, renaming Speaker 1 to Aaron and Speaker 2 to Luana, using Fenrir and Sulafat voices.

The result was a rich informative podcast in Brazilian Portuguese, with great dictaction.

<audio controls>
    <source src="./assets/audio/PodCraft_Piloto.wav" type="audio/wav"/>
    Your browser does not support the audio element.
</audio>

## Post Production

After generating the dialog, I Googled some royalty free music based on Minecraft, downloaded, mixed everything on CapCut and saved as `.mp3`, finally creating a professional grade Podcast episode.

<audio controls>
    <source src="./assets/audio/Podcraft.mp3" type="audio/mp3"/>
    Your browser does not support the audio element.
</audio>

---

Made by [Aaron Carneiro](https://github.com/euaaron) with AI.

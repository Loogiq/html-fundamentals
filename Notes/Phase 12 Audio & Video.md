PHASE 12 — AUDIO & VIDEO

161. "<audio>"

Function: Embeds audio content in a webpage.
Example:

<audio controls src="audio.mp3"></audio>

162. "<video>"

Function: Embeds video content in a webpage.
Example:

<video controls src="video.mp4"></video>

163. "<source>"

Function: Provides alternative media sources for "<audio>" or "<video>".
Logic: The browser can choose a supported source.
Example:

<video controls>
    <source src="video.mp4" type="video/mp4">
    <source src="video.webm" type="video/webm">
</video>

164. "controls"

Function: Displays built-in playback controls for audio or video.
Example:

<video controls src="video.mp4"></video>

165. "autoplay"

Function: Tells the browser to start media automatically.
Example:

<video autoplay muted src="video.mp4"></video>

166. "loop"

Function: Makes audio or video restart automatically after it ends.
Example:

<audio controls loop src="audio.mp3"></audio>

167. "muted"

Function: Starts audio or video without sound.
Example:

<video controls muted src="video.mp4"></video>

168. "poster"

Function: Specifies an image displayed before a video starts.
Example:

<video controls poster="thumbnail.jpg" src="video.mp4"></video>

169. "<track>"

Function: Adds timed text such as subtitles or captions to audio/video.
Example:

<video controls src="video.mp4">
    <track src="subtitles.vtt" kind="subtitles" srclang="en">
</video>

170. Media Accessibility

Function: Makes audio and video content accessible to more users.
Logic: Provide captions, subtitles, transcripts, and meaningful controls when appropriate.
Example:

<video controls>
    <source src="lesson.mp4" type="video/mp4">
    <track src="english.vtt" kind="subtitles" srclang="en" label="English">
</video>
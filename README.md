# Simple Spectrogram

A live spectrogram 

### quick notes

When Safari and FF simultaneously run the app, Safari's microphone seems to be much more sensitive. Then when I exit Safari, the same sensitivity appears in FF. If testing between Chrome and Firefox, they seem to share just fine.

Safari canvas context globalCompositeOperation seems to behave slightly differently in "copy" mode

If you attempt to create an audioContext, but not in an event handler, Firefox will work, Chrome will warn, Safari will silently fail.

on iOS, if you navigate away and back, the stream stops and the page has to be refreshed, even though the stream is still active (even showing the microphone icon in top left)
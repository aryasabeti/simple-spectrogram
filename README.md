When Safari and FF simultaneously run the app, Safari's microphone seems to be much more sensitive. Then when I exit Safari, the same sensitivity appears in FF. If testing between Chrome and Firefox, they seem to share just fine.

Safari canvas context globalCompositeOperation seems to behave slightly differently in "copy" mode used in a previous implementation.

Because permission is regulated through audio context, we have to create our audio context in response to user gesture even though we're listening (and have to ask for permission anyway), not autoplaying.

If you attempt to create an audioContext outside of the above mechanism, Firefox will work, Chrome will warn, Safari will silently fail.

There are a few different ways to draw to canvas. This is something I'd like to learn more about.

The Mel scale is interesting and useful, though I don't fully understand the methodology right now.

on iOS, if you navigate away and back, the stream stops and the page has to be refreshed, even though the stream is still active (even showing the microphone icon in top left)
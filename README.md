# yt_shorts_to_videos
My first chrome extension: it redirect youtube shorts to youtube normal video with that same video
# Installation
1. Go to `Code` and download files with `git clone` OR `Download ZIP` and unzip the file
2. In your favourite chrome-base browser type in `chrome://extensions`
3. Check on `Developer mode`
4. Click `Load unpacked`
5. Select the directory you just download
# How it work
In [rules_1.json](rules_1.json) when URL visited match `condition.regexFilter` it redirect to `action.redirect.regexSubstitution` value.
In this case, it get whatever is after `https://www.youtube.com/shorts/` and put it after `https://www.youtube.com/watch?v=`

# obs-youtube-shorts-player
This is a simple html script that plays and shuffles videos / shorts from a YouTube playlist in OBS. The main usage is for BRB or Starting Soon scenes, when you want to automatically play some of your clips.

Did you ever want some reusable video content for your BRB / Starting Soon scenes in your stream? I created a little solution for this, an automatic video player for YouTube playlists. I personally use it to shuffle through all of my shorts, and the viewers love it. It is a win-win situation if you anyways create shorts on YouTube, as you can use them directly on your stream without needing to download any local files etc.

Instructions:

Open the file in a text editor (If you cannot find how to do this, try literally right click, open with... and choose text editor) and change the playlist id to your playlist. The id is the ending of your playlist URL. For example: https://www.youtube.com/playlist?list=PLgIDB87U34NcKPcsLTxtu1GmLhZ6AfQ1u is my shorts playlist. The id would be: 'PLgIDB87U34NcKPcsLTxtu1GmLhZ6AfQ1u'

Add a new browser source to OBS. Click "Local file" and browse for your downloaded and edited "random-short - public.html". Set width and height according to your needs (I use 600x1000) and tick control audio via OBS. That lets you adjust the volume of the clips later easier. Also tick "Shutdown source when not visible" and "Refresh browser when scene becomes active".

That's it! You should have a working player now and can adjust the audio with its own meter. Enjoy and let me know if you like this!

More Info:

This is by no means a perfect solution, but it replaced my local file clip folder perfectly. It also keeps being up to date without any effort, as all you need to do is adding your shorts to the playlist on upload.

There is still currently a bit of jank because of how YouTube handles the embedded video player. You can see the title and a bit of a darkening of the screen when a new short loads. You can try to crop it out, but honestly it often gives nice context to the clips having the title there for a second, so I didn't bother fixing this.

You can probably make some nice border for the player in your scene to make it look even better (something I still need to do lol).

For any further questions about this, let me know! If you like this kind of stream tech help, consider leaving me a little sub on YT or supporting elsewhere, I will try to publish more of my coded stream setup in the near future so others do not need to struggle so much as I did. Have a wonderful week yall!

More info with screenshots etc. here: https://www.patreon.com/posts/137291568

# SmashWiiUDoublesOverlayStep1
Step 1 of a project to create a dynamically editable overlay for Super Smash Bros. Wii U Doubles usable for any tournament streamer using HTML, JavaScript, CSS and C#.

**How to use in Open Broadcaster Software (OBS Studio):**
- Add a new Browser source to your scene.

![alt img](https://imgur.com/xAvWiY0.png)

- Check the Local file checkbox and click Browse.

![alt img](https://imgur.com/yF0RGmH.png)

- Select gameOverlay.html of this project.
- Set the resolution and framerate. (1920 x 1080 at 60 frames per second recommended)
- Check Refresh browser when scene becomes active checkbox.

![alt img](https://imgur.com/rIepH9D.png)

You are now ready to stream with the overlay.

As the streamed set(s) progress, you can update the overlay by changing:

- 

at the bottom of styles.css

At this step, the overlay doesn't dynamically update whenever the css is altered, you have to move back and forward between the scene with the overlay and another scene to show an updated overlay.

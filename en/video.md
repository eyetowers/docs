# Video

The video page displays live camera views for the chosen unit. Depending on your display size, you
can pick how many cameras should be displayed on a single page ranging between 1 and 16 (1). To
stwitch between pages, use either keyboard or controls with arrows (2).

![Video](../_media/video_overview.png)

Every camera has a header (3) with its name and information about stream quality:

- Bandwidth in Kb per second, `kbps`.
- Number of frames per second, `fps`.
- Camera serial number.
- State/type of the stream, ideally `H264` in green.

Additional camera detail are displayed after hover on the camera name: resolution, camera
manufacturer and model.

The right side of the header contains buttons for extended camera controls. Some of these are
inactive if the camera does not support the particular functionality or if the user is missing the
required permissions.

Left to right these are:

- Enter [video archive](#video-archive) (4).
- Show the camera in the fullscreen mode (5). Note that some iOS devices do not support fullscreen
  mode for web pages.
- Show advanced camera configuration options (6), e.g., preset use and configuration, IR light, etc.
- Show PTZ controls, arrow buttons and a virtual joystick (7).
- Temporarily lock the camera on the page (8). When switching between pages, the locked camera(s)
  stay on the current view and only the rest of the cameras get replaced.

Click in the view of any camera moves it into a large popup window, closed by another click in it.

## Video Archive

The video archive mode offers synchronous playback of recording from multiple cameras at the same
time.

The playback time can be chosen using a calendar (1) or via a graphical timeline (2). You can pick
the resolution/scale of the timeline between 10 minutes and a whole day (9). To jump by the whole
timeline range forward or backward, use buttons (3) and (7), respectively. For small 30 second jumps
use buttons (4) and (6). The button (5) pauses and resumes playback. Control (8) sets playback speed
ranging from 1/2x slowdown to 32x speedup. Last, button (10) exits the video archive mode and
switches all cameras back into the live view.

![Video Archive](../_media/recording_overview.png)

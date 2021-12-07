**Disclaimer: This is not yet close to an even started project. I just made a Git Repo out of it, so that I will not lose those notes and maybe if someone volunteers to help with that we can get in touch. And of cause also to get comments on that.**

# ZoomWM

This is a Mindmap/Markdown of a Linux window manager based on zooming.

For an easier understanding. Think of a collaborative whiteboard. Like miro or sketchtogether.

## Features

- Zoom in/out
- Scale windows with zoom (allows different zoomed/sized windows)
- Infinite scrollable and zoomable canvas
- Allow the creation of fenced scopes
  - Similar to a virtual desktop/workspace (eg. in GNOME). Allows stores the view position and zoom in an area
  - Windows inside still can be scaled
  - If windows are too big or would hang out of the scope, the overflow should be visible in the overview (outside the scope)
- Zoom is done trough a modifier key (eg. Meta) and scrolling
  - On touchpad pinch zoom should be a thing, without modifier (if possible)
- Moving around the desktop is done via modifier + scrollwheel click + mouse movement
  - On touchpad 3 finger dragging should jump in (without modifier again)
- The focussed window should always be visible
  - When moved away from the window, the focus leaves
  - If clicked on the window the focus is raised again, moving the view to the window
    - Decide if the zoom should be adjusted or not to fit the window on the full screen/make the window fill the screen
      - Make it a setting?
- ~~Concentrate on Wayland as it allows touchpad gestures~~
  - X11 does it as well and implementing on X11 is easier as the separation of the Xserver and Xclients is more modular
- View spanning over all monitors or each monitor has its own view?
  - Setting maybe?
  - When each monitor has its own view, how does overlapping views behave?
  - As we're already at handling independent monitors; how about multi mouse/keyboard setups?
- Build a sketch mode, so you can draw on your canvas?
  - This is becoming a hilarious mess
  - If this project works out I will never again say, that something is impossible
- Intend to have multi-seat setups
  - Nope, it's currently (as I'm writing this) christmas time, not 1st of April!
- Actually X11 is built so that it can support multi-seat setups and have multiple mice and keyboards attached. Its not **that** crazy. I mean .. it is crazy .. but not **that** crazy



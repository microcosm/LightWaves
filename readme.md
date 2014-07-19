Light Waves
===========
This repo is to pull together some visual experiments from a couple of years ago into a triptych/canvas projection-mapping context, and to see where it goes from there.

The patches run in vvvv45beta27.2, which as of this writing can be [downloaded here](http://vvvv.org/blog/vvvv45beta27.2). I haven't tested them with newer software yet.

Make sure you also install the [addon pack](http://vvvv.org/blog/addons45beta27.201).

Usage
-----
- Launch root.v4p
- In the Render subwindow, right-click the 'design view' renderer
- Use the Camera controls to navigate
- Back in root, right-click PanelTransform to position the quads in space

Camera Usage
------------
This uses [Camera &#40;Transform Softimage&#41;](http://vvvv.org/documentation/camera-&#40;transform-softimage&#41;), so you can use these standard controls:
- press **r** to reset viewport
- press **o** and hold while dragging to orbit
- press **z** and hold while dragging to...
  - left mousebutton: pan
  - right mousebutton: zoom
- press **p** and hold while dragging to dolly
  - left mousebutton: slow
  - right mousebutton: fast
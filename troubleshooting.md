---
layout: default
title: Troubleshooting
nav_order: 6
permalink: /troubleshooting/
---
# Troubleshooting

### The projector screen does not show ink

Check that the projector window is open and positioned on the intended display. Finish the stroke: if the live preview is not available for your particular pen hardware, the final native stroke may still synchronise after pen-up.

### I cannot draw with the mouse

In Settings, select **Mouse** or **Pen & Mouse** under ink input mode, save the change and reopen the lecturer window if necessary.

### Imported PowerPoint slides look different

Enable the PowerPoint-rendered background option under Board settings if desktop PowerPoint is installed. Complex fonts, effects or animations may render differently with the Open XML fallback.

### Where did the replay controls go?

`ShowReplayMode=false` hides replay functions intentionally. Slides are shown fully and the normal slide navigation remains available. To enable replay, set it to `true` in `appsettings.json` and restart.

### No save dialog appears when closing

A save prompt is displayed only when there are unsaved lecture changes.

### A newly created slide does not repeat shapes from the previous slide

This is intentional: it inherits the background only.

### Is the app certified to work with every stylus?

Native ink and input device behaviour depend on the Windows environment and drivers. Test your teaching hardware before a lecture.

---
layout: default
title: PowerPoint & replay
nav_order: 5
permalink: /powerpoint/
---
# PowerPoint & replay

Select **Open PowerPoint** and choose a `.pptx` file. Tabulexa prepares the presentation's static background, images, shapes and text for its display. When supported and enabled, original PowerPoint rendering provides additional fidelity; the built-in Open XML renderer is the fallback.

## Default: complete slides

`ShowReplayMode` is **false by default**. In that mode, Tabulexa displays complete slide content immediately. Replay-specific **Previous / Next** controls, replay settings and clickable replay actions are hidden or disabled. Standard slide navigation remains available.

## Optional replay

Advanced deployments can set `ShowReplayMode` to `true` in the application's `appsettings.json`. This restores independent animated ink replay groups, lecturer-only guides, replay navigation and supported presentation-remote/Spotlight replay actions. Restart the application after changing the setting.

The app's standard navigation remains distinct from replay navigation.

## New blank slides

If you extend an imported presentation with a blank slide, the new page inherits only its **background**, not slide-local objects, annotations or replay groups.

## Saving

When leaving the lecturer board with changes, choose **Save**, **Save As**, **Don't Save**, or **Cancel**. Saving annotations to PPTX is supported; save-and-reload testing is recommended for important teaching material.

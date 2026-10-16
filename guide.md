---
layout: default
title: Full user guide
nav_order: 3
permalink: /guide/
---

> **Replay setting:** In current builds, `ShowReplayMode` defaults to `false`. When disabled, full slide content appears immediately and replay-specific controls and settings are hidden. Slide navigation is still available.

# Tabulexa — User Guide

**A digital board for teaching with handwriting, PowerPoint slides and a projector.**

Tabulexa lets you write directly on a lecture board or on imported PowerPoint slides. Your students can follow the presentation on a separate projector screen while you control the lesson from your own display.

## 1. Getting started

When Tabulexa opens, choose one of the options on the start page:

- **New board** — start with an empty board. Choose its background and aspect ratio, then select **Start blank board**.
- **Open PowerPoint** — select **Browse files** and open a `.pptx` presentation.
- **Recent presentations** — reopen one of your three most recently opened presentations.
- **Settings** — adjust your pens, board, pointer, replay and appearance preferences.

When you open a PowerPoint file, Tabulexa may briefly display a loading screen while it prepares the slides.

## 2. Writing on the board

Choose a pen from the toolbar and write directly on the lecturer board. You can use a stylus, a mouse, or both, depending on your input settings.

The available input modes are:

| Mode | What it does |
| --- | --- |
| **Pen** | Draw with a stylus. |
| **Mouse** | Draw with the mouse. |
| **Pen & Mouse** | Draw with either device. This is the default. |
| **Hand** | Move around the board without drawing; use the mouse wheel to zoom. |

You can configure up to three pens, with different colours and widths, in **Settings → Pens**. The additional pen buttons also offer colour and width options by right-clicking them.

**Tip:** Choose **Hand** when you want to pan or zoom instead of leaving ink marks. If you change the input mode in Settings, reopen the lecturer window to apply the change.

## 3. Showing your board to students

Select **Projector** in the lecturer toolbar to show or close the separate student window. Place that window on the display connected to your projector or classroom screen.

The projector displays the lesson content, without the lecturer-only replay previews.

**Live handwriting:** In the current live-preview version, students can see a developing pen or mouse stroke while you draw, instead of waiting until you lift the pen. When the stroke finishes, Tabulexa replaces the temporary preview with the completed ink stroke. Stylus behaviour can depend on the device and driver.

If the projector window is open but students cannot see it, check your Windows multiple-display arrangement and ensure the student window is on the intended screen.

## 4. Working with PowerPoint

Open a `.pptx` file from the start page. Tabulexa prepares the slide backgrounds and static content for display. Where supported, it also keeps recognised animated ink groups separate so that they can be revealed during the lecture.

Use the toolbar controls:

- **Next** — with replay enabled, reveal the next replay group before advancing; with replay disabled, navigate directly to the next slide.
- **Previous** — with replay enabled, reverse a replay step; with replay disabled, navigate directly to the previous slide.
- **Slide arrows / slide number** — move between or choose slides directly.

Tabulexa has a separate setting under **Settings → Board → Use PowerPoint-rendered background image**. When enabled, it uses desktop Microsoft PowerPoint to render static slide content, including master/layout backgrounds. Without that rendering path, Tabulexa uses its built-in Open XML renderer, which may not match PowerPoint as closely for complex slide designs.

**Note:** Some unusual PowerPoint features or animations may not import exactly as they appear in PowerPoint itself.

## 5. Adding writing space

You can continue into a newly created blank slide when working through a lecture. When a blank slide is added after an imported PowerPoint slide, Tabulexa carries over the **background only** — not that slide's text, pictures, shapes, animations or handwritten notes.

This gives you extra space for an explanation without duplicating the original slide content.

## 6. Using the projector pointer

Tabulexa can display a pointer on the student screen, helping you highlight something while teaching.

Open **Settings → Pointer** to choose whether to show the pointer, its style, colour and size. Available styles include **Disc**, **Ball**, **Cross** and **Meteor**. Meteor adds a fading trail.

The pointer is separate from handwriting: use it to draw attention to part of a slide without adding permanent ink.

## 7. Full screen

Select **Full screen** in the lecturer toolbar, or press **F11**, to change the lecturer-window full-screen state. Use the same control again to return.

## 8. Saving your work

Tabulexa can save lecture annotations with a PowerPoint presentation. When you choose **Home** or close the lecturer window **after making changes**, Tabulexa asks what to do:

| Option | Result |
| --- | --- |
| **Save** | Save to the current destination; if there is no destination yet, choose one. |
| **Save As…** | Choose a destination and file name. |
| **Don't Save** | Leave without saving the unsaved changes. |
| **Cancel** | Stay on the current board. |

If you have made no changes, Tabulexa does not need to show this prompt.

**Tip:** At the end of a lecture, save your annotated presentation and reopen it to check that the handwritten notes are present.

## 9. Personalising Tabulexa

From the start page, open **Settings**:

| Settings section | You can adjust |
| --- | --- |
| **Appearance** | App theme, status bar, drawing input mode and presentation remote options. |
| **Pens** | Number of pens, colours and widths. |
| **Board** | Default board background, aspect ratio and PowerPoint background rendering. |
| **Pointer** | Student-screen pointer visibility, style, colour and size. |
| **Replay** | Lecturer-side previews of unreplayed ink groups (visible only when `ShowReplayMode` is enabled). |

Select **Save settings** to retain your choices. Some changes require reopening the lecturer window or presentation.

## 10. Common questions

### Why can't I draw with the mouse?
Check **Settings → Appearance → InkCanvas input mode**. Select **Mouse** or **Pen & Mouse**, save the setting and reopen the lecturer window.

### Why is handwriting not visible on the projector?
First check that the **Projector** window is open and located on the correct Windows display. Try finishing a stroke: the completed ink should be transferred even if your device does not provide a live preview.

### Why does my imported slide look different from PowerPoint?
Check **Settings → Board → Use PowerPoint-rendered background image**. This mode requires a compatible desktop PowerPoint installation to render slides through PowerPoint; otherwise, the built-in renderer is used.

### Will adding a blank slide copy all the objects from my previous slide?
No. New blank slides inherit the background only.

### What if I select Home by mistake?
If you have unsaved work, select **Cancel** in the save prompt to remain on your board.

---

*This guide applies to Tabulexa Board 3.0.1.0. Some features depend on Windows hardware, PowerPoint availability and presentation content.*

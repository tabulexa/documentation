---
layout: single
author_profile: false
classes: wide
title: Usage
permalink: /usage.html

---

## <br> Getting started

Tabulexa Board supports two ways of teaching:

- **New board:** Start with an empty board, choose a background and write freely during your lecture. You can save your board and handwriting as a PowerPoint presentation.
- **PowerPoint presentation:** Open an existing `.pptx` file, display your slides and add handwritten explanations. You can also reveal prepared content step by step using Replay mode.

In both cases, you work in the lecturer window, while students see a separate projector window.


## Creating a new board

To start with an empty board:

1. Select **New board** on the start page.
2. Choose a background pattern and an aspect ratio. The aspect ratio of the detected projector display is selected by default.
3. Click **Start blank board**.
4. Open the projector window when you are ready to present.
5. Use the pen tools to write or draw on the board.

Use the previous and next page buttons to navigate or create additional pages. When you finish, return to the start page or close the application. Tabulexa Board will ask whether you want to save your changes as a PowerPoint file.

![Creating a new board]({{ "/assets/images/newboard.png" | relative_url }})

## Opening a PowerPoint presentation

You can use Tabulexa Board with an existing PowerPoint presentation.

1. On the start page, select **Browse files** under **Open PowerPoint**.
2. Choose your .pptx file.
3. Navigate between slides using the toolbar.
4. Add handwritten notes or drawings wherever needed.
5. Open the projector window to show the presentation to students.

Tabulexa Board uses the aspect ratio of the original PowerPoint slides. You can also add new pages during your presentation. When you finish, you will be prompted to save your changes.

## Writing and drawing

Choose a pen from the toolbar to write directly on the lecturer board. You can use a stylus, a mouse or both.

The drawing input mode can be changed in Settings → Appearance.

| Input mode | Description |
| --- | --- |
| **Pen** | Draw using a stylus. |
| **Mouse** | Draw using the mouse. |
| **Pen & Mouse** | Draw using either device. This is the default setting. |
| **Hand** | Move around the board without drawing. Use the mouse wheel to zoom. |

You can configure up to three pens with different colours and widths in Settings → Pens. For additional pen options, right-click a pen button on the toolbar.

## Using the projector window

Tabulexa Board provides separate views for lecturers and students.

The **lecturer window** contains your writing tools, navigation buttons and other controls. You can zoom in and move around the board to write comfortably.

The **projector window** shows students the full slide or board without lecturer-only controls. Your handwriting appears as you write.

To use it:

1. Connect your projector, external monitor or classroom display.
2. In Windows display settings, choose **Extend these displays**.
3. Open Tabulexa Board and select **Projector** in the toolbar.
4. Check that the projector window appears on the correct display.

If several displays are connected, pressing the Projector button repeatedly can cycle between them.

![Tabulexa Board toolbar]({{ "/assets/images/buttons.png" | relative_url }})

## Navigating slides

Use the toolbar to move through your presentation.

- **Next:** Move to the next slide, or reveal the next prepared group when Replay mode is enabled.
- **Previous:** Return to the previous slide, or reverse a replay step.
- **Slide arrows and slide number:** Navigate directly between slides.

When Replay mode is disabled, all slide content is shown normally.

## Replaying prepared content

Replay mode lets you reveal prepared PowerPoint content one step at a time. This can be useful for equations, diagrams and longer explanations.

To prepare replay content:

1. Open your presentation in Microsoft PowerPoint.
2. Draw or select the ink strokes or objects you want to reveal together.
3. Group related strokes or objects.
4. Apply an animation, such as Replay or Appear, to each group.
5. Save the presentation and open it in Tabulexa Board.
6. Enable Replay mode in Tabulexa Board when you want to use the prepared animations.

When Replay mode is active, supported unrevealed ink groups appear in light grey on the lecturer board. You can reveal these groups by clicking their preview boxes or using the replay navigation buttons. Students see the content as it is revealed.

Not every PowerPoint animation is supported. For predictable results, use simple animations on grouped ink strokes or objects.

![Replay of grouped ink strokes]({{ "/assets/images/ReplayMode.png" | relative_url }})

## PowerPoint rendering

Tabulexa Board can display PowerPoint slides using its built-in renderer or, when available, Microsoft PowerPoint itself. 

For the closest match to the original presentation, enable **Use PowerPoint-rendered background image** in the board settings. This uses a local Microsoft PowerPoint installation to render the slide content. Without this option, Tabulexa Board uses its built-in Open XML renderer. Complex diagrams, fonts or effects may appear slightly different from PowerPoint.

## Using the projector pointer

The projector pointer helps you highlight content on the student screen without drawing permanent marks. Open Settings → Pointer to change its appearance.

Available pointer styles:

- **Disc:** A simple circular pointer.
- **Ball:** A rounded pointer.
- **Cross:** A cross-shaped pointer.
- **Meteor:** A pointer with a fading trail.

You can adjust the pointer's colour, size and visibility.

## Saving your work

Tabulexa Board can save your presentation and handwritten annotations as a PowerPoint `.pptx` file. 

When you return to the start page or close the presentation, the application prompts you to save unsaved changes. For boards created from scratch, Tabulexa Board creates a new PowerPoint file containing the pages, board backgrounds and handwriting.

## Personalising Tabulexa Board

Select Settings on the start page to customise how the application works.

| Settings section | What you can change |
| --- | --- |
| **Appearance** | Light or dark theme, input mode, status bar and presentation remote settings. |
| **Pens** | Number of pens, pen colours and widths. |
| **Board** | Default background, aspect ratio and PowerPoint rendering. |
| **Pointer** | Pointer style, colour, size and visibility. |
| **Replay** | Replay settings and lecturer-side previews of unrevealed ink groups. |

Select **Save settings** to keep your changes. Some settings may require you to reopen the presentation.

---

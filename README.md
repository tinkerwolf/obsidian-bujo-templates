# BuJo with Obsidian Notes
#### Bullet Journal Templates for Obsidian writing application

[Obsidian](https://obsidian.me) "is the private and flexible writing app that adapts to the way you think"

BuJo, or [Bullet Journal](https://bulletjournal.com/) as it's called, "is a mindfulness practice designed as a productivity system". 

Everyone has their own way of tracking tasks and managing information, but I think everyone can also use a bit of help from time to time. I've been a long term user of the BuJo system of notetaking and a short time user of Obsidian. In my short time with Obsidian I've found the paring of it and the BuJo methed to be outsdanding. I reached this point by reading what others have done and experimintation, and now that I have the system working for me I think some of this could be a good starting point for others.

I welcome questions, feedback, and additions.

## The basics of BuJo templating

BuJo can be as complicated or as simple as you would like, I aim for the simpler side of a writer and engineer. Someone seeking the colorful and more artistic of BuJo likely won't find Obsidian to be the right place for their work.

**The System**
- Future Log
    - High level year calendar
    - A quick point of reference when looking forward
    - Does not compete with your Google (or other) calendar
- Monthly Log (optional for many)
    - Events and Tasks
- Weekly Log
    - Key tasks and times to remember
- Daily Log
    - Tasks, events, tracking, and notes
- Collections
    - Catagorized groups of information

**The Templates**
- New Day.md
    - List of tasks that are overdue
    - List of tasks due today or scheduled for the week
    - Day's Events
    - Day's Notes
- New Month Calendar.md
    - Very simple list view of the month with important references
    - Complements, does not attempt to replace, a traditional digital calendar
- New Month Tasks.md
    - All of your tasks organized in one place
    - Seperate views of everything overdue, everything in a good status, and everything done or canceled
    - List of 'bad' tasks - ones still without any type of schedule
- New Collection.md
    - A general template for breakouts from the daily notes
- New Project or Goal.md
    - Not BuJo specifically, part of general mindfulness and planning
    - Asking questions that help you think about the topic


## Setup and Use

1. Start by copying the entire Templates folder into your Obsidian Vault, if you already have a template directory only copy over the markdown files.
1. Launch Obsidian
1. Open settings and select **Core Plugins** under *Options*
1. Verify that **Daily Notes** and **Templates** are enabled in the plugin list
1. Select **Templates** under *Core Plugins* in the left menu
    1. Enter the name of your template folder in the **Template folder location** field.  It should autocomplete as you enter the name.
    1. The other fields can be left as default
1. Select **Daily Notes** under *Core Plugins* in the left menu
    * By default new daily notes are all at the same bottom level as all other files. Basic BuJo keeps the basic flow in a timeline like you are writing in a book. You can leave this as the default, but I recommend having the system create a year / month directory structure for you
    1. Set Date Format to be ```YYYY/MM/YYYY-MM-DD```
    1. Click on the Template File Location box and select *Templates/New Day*
    1. If you want to always open Obsidian to the current date, enable *Open daily note on startup*
    1. The other fields can be left as default
1. Select **Community Plugins** under *Options* in the left menu
    1. If you have not installed any community plugins Obsidian will prompt you to turn off restrictions, do so to continue
    1. Click the **Browse** button next to *Community Plugins*
    1. Search for, install, and enable the following plugins:
        * Calendar by Liam Cain
        * Day Planner by James Lynch continued by Ivan Lednev
        * Periodic Notes by Liam Cain
        * Tasks by Martin Schenck and Clare Macrae
        * Templater by SilentVoid
    1. When done close the browse window
1. Select **Calendar** under *Community Plugins* in the left menu
    1. Enable **Confirm before creating new note**
        * You can turn this off later, but it is good to have on or you can end up with many unused files.
1. Select **Day Planner** under *Community Plugins* in the left menu
    1. Enable **Center the Pointer in the Timeline View**
        * This will ensure the timeline is showing where you are in your day
    1. Set **Start Hour** to a time that is appropriate for you
    1. Set **Planner Headline** to ```Today's Timeline```
    1. Enable **Colorful Timeline**
        * This will make the timeline stand out better
1. Select **Periodic Notes** under *Community Plugins* in the left menu
    1. Enable **Daily Notes**
        1. Set **Format** to ```YYYY/MM/YYYY-MM-DD```
        1. Set **Daily Note Template** to ``Templates/New Day.md```
        1. Leave **Node Folder** blank
    1. Enable **Weekly Notes** 
        1. Set **Format** to ```YYYY/MM/YYYY-[W]WW```
        1. Set **Weekly Note Template** to ``Templates/New Week.md```
    1. Enable **Monthly Notes** 
        1. Set **Format** to ```YYYY/MM/YYYY-MM [Calendar]```
        1. Set **Weekly Note Template** to ``Templates/New Month Calendar.md```
1. Select **Tasks** under *Community Plugins* in the left menu
    1. Enable **Set done date on every completed task**
1. Select **Templater** under *Community Plugins* in the left menu
   1. Set **Template folder Location** to ``Templates```
1. Close settings, you are ready to go

# Contents
Getting Started 11

DaVinci Resolve Interface
1 Introduction to DaVinci Resolve  14
2 Using the DaVinci Resolve User Interface  56
Setup and Workflows
3 Managing Projects and Project Libraries  75
4 System and User Preferences  96
5 DaVinci Control Panels Setup  130
6 Project Settings  137
7 Camera Raw Settings  165
8 Improving Performance, Proxies, and the Render Cache  191
9 Data Levels, Color Management, and ACES  219
10 HDR Setup and Grading  253
11 Image Sizing and Resolution Independence 282
12 Data Burn-In  297
13 Frame.io and Dropbox Replay Integration  303
14 Resolve Live  312
15 Stereoscopic Workflows  320
16 Using Variables and Keywords  343
Ingest and Organize Media
17 Using the Media Page 350
18 Adding and Organizing Media with the Media Pool  368
19 Using Clip Metadata  408
20 Using the Inspector in the Media Page  423
21 Syncing Audio and Video  437
22 Modifying Clips and Clip Attributes  444
23 Using Scene Detection 457
24 Ingesting From Tape  465
25 Capturing From the Cintel Film Scanner  473
Contents
3
The Cut Page
26 Using the Cut Page  497
27 Importing and Organizing Media in the Cut Page  516
28 Fast Editing in the Cut Page  542
29 Trimming in the Cut Page  578
30 Using the Inspector in the Cut Page  597
31 Video and Audio Effects in the Cut Page  619
32 Quick Export 650
Edit
33 Using the Edit Page 654
34 Creating and Working with Timelines 697
35 Preparing Clips for Editing and Viewer Playback 720
36 Editing Basics  743
37 Using the Inspector in the Edit Page  773
38 Modifying Clips in the Timeline  795
39 Three- and Four-Point Editing  818
40 Text Based Editing  847
41 Marking and Finding Clips in the Timeline  863
42 Multicam Editing  889
43 Take Selectors, Compound Clips, and Nested Timelines  904
44 Trimming 915
45 Working with Audio in the Edit Page 949
46 Media Management  993
Editing Effects and Transitions
47 Editing, Adding, and Copying Effects and Filters  1002
48 Using Transitions  1017
49 Titles, Generators, and Stills  1037
50 Compositing and Transforms in the Timeline  1053
51 Speed Effects  1070
52 Subtitles and Closed Captioning  1083
53 Keyframing Effects  1103
54 VFX Connect  1121
Contents
INTRO
MEDIA
CUT
EDIT
FUSION
COLOR
FAIRLIGHT
DELIVER
MENU
4
Import and Conform Projects
55 Preparing Timelines for Import and Comparison  1130
56 Conforming and Relinking Clips 1144
57 Creating Digital Dailies for Round Trip Workflows  1170
58 Conforming XML Files  1177
59 Conforming AAF Files  1182
60 Conforming EDL Files  1196
61 Conforming OTIO Files  1202
62 Conforming ADL Files  1207
Fusion Fundamentals
63 Introduction to Compositing in Fusion  1210
64 Exploring the Fusion Interface  1216
65 Getting Clips into Fusion  1265
66 Rendering Using Saver Nodes 1292
67 Working in the Node Editor  1316
68 Node Groups, Macros, and Fusion Templates  1366
69 Using Viewers 1389
70 Editing Parameters in the Inspector  1432
71 Animating in Fusion’s Keyframes Editor  1458
72 Animating in Fusion’s Spline Editor  1476
73 Animating with Motion Paths  1508
74 Using Modifiers, Expressions, and Custom Controls  1526
75 Preferences 1538
76 Controlling Image Processing and Resolution  1587
77 Managing Color for Visual Effects  1598
78 Understanding Image Channels  1611
79 Compositing Layers in Fusion  1647
80 Rotoscoping with Masks  1672
81 Paint  1696
82 Using the Tracker Node  1724
83 Planar Tracking 1760
84 Using Open FX, Resolve FX, and Fuse Plugins  1767
85 3D Compositing Basics  1772
Contents
INTRO
MEDIA
CUT
EDIT
FUSION
COLOR
FAIRLIGHT
DELIVER
MENU
5
86 3D Camera Tracking  1827
87 Particle Systems  1845
88 Optical Flow and Stereoscopic Nodes  1854
Fusion Page Effects
89 3D Nodes  1867
90 3D Light Nodes  1985
91 3D Material Nodes  2004
92 3D Texture Nodes  2033
93 Blur Nodes  2058
94 Color Nodes  2083
95 Composite Nodes  2158
96 Deep Image Nodes  2178
97 Deep Pixel Nodes  2197
98 Effect Nodes 2213
99 Film Nodes  2250
100 Filter Nodes  2269
101 Flow Nodes  2286
102 Flow Organizational Nodes  2289
103 Fuses 2294
104 Generator Nodes  2296
105 I/O Nodes 2336
106 Layer Nodes  2363
107 LUT Nodes  2377
108 Mask Nodes  2386
109 Matte Nodes  2427
110 Metadata Nodes  2498
111 Miscellaneous Nodes  2506
112 Optical Flow  2545
113 Paint Node 2565
114 Particle Nodes  2575
115 Position Nodes  2635
116 Resolve Connect  2654
117 Shape Nodes  2660
118 Stereo Nodes  2700
Contents
INTRO
MEDIA
CUT
EDIT
FUSION
COLOR
FAIRLIGHT
DELIVER
MENU
6
119 Tracking Nodes  2732
120 Transform Nodes  2788
121 USD Nodes  2816
122 VR Nodes  2869
123 Warp Nodes  2880
124 Modifiers  2910
Color
125 Introduction to Color Grading  2953
126 Using the Color Page  2965
127 Viewers, Monitoring, and Video Scopes  2983
128 Color Page Timeline and Lightbox 3023
129 Automated Grading Commands and Imported Grades  3038
130 Camera Raw Palette  3052
131 Primaries Palette  3058
132 HDR Palette  3077
133 Primary Grading Controls  3101
134 Curves  3107
135 ColorSlice  3128
136 Color Warper  3135
137 Secondary Qualifiers 3157
138 Secondary Windows  3185
139 Magic Mask  3201
140 Motion Tracking Windows  3229
141 Using the Gallery 3256
142 Grade Management  3273
143 Node Editing Basics 3308
144 Image Processing Order of Operations  3329
145 Serial, Parallel, and Layer Nodes  3332
146 Combining Keys and Using Mattes  3340
147 Channel Splitting and Image Compositing  3365
148 Keyframing in the Color Page  3380
149 Copying and Importing Grades Using ColorTrace  3395
150 Using LUTs  3405
Contents
INTRO
MEDIA
CUT
EDIT
FUSION
COLOR
FAIRLIGHT
DELIVER
MENU
7
Color Page Effects
151 Using Open FX and Resolve FX 3416
152 Sizing and Image Stabilization  3429
153 The Motion Effects and Blur Palettes  3445
Resolve FX Overview
154 Resolve FX  3458
155 Resolve FX Blur 3461
156 Resolve FX Color  3467
157 Resolve FX Film Emulation  3480
158 Resolve FX Generate  3494
159 Resolve FX Key  3496
160 Resolve FX Light 3509
161 Resolve FX OpenColorIO  3521
162 Resolve FX Refine  3524
163 Resolve FX Revival  3550
164 Resolve FX Sharpen  3572
165 Resolve FX Stylize  3576
166 Resolve FX Temporal  3599
167 Resolve FX Texture  3603
168 Resolve FX Transform  3614
169 Resolve FX Warp  3653
Fairlight
170 Using the Fairlight Page 3663
171 Setting Up Tracks, Busses, and Patching  3719
172 Transport Controls, Timeline Navigation, and Markers  3743
173 Recording  3752
```
174 ADR (Automated Dialog Replacement)  3762
```
175 Editing Basics in the Fairlight Page  3772
176 The Fairlight Inspector 3823
177 Mixing in the Fairlight Page  3843
178 Mix Automation  3892
179 Track Groups  3916
180 Audio Effects  3922
Contents
INTRO
MEDIA
CUT
EDIT
FUSION
COLOR
FAIRLIGHT
DELIVER
MENU
8
181 Fairlight FX  3935
182 Audio Meters and Audio Monitoring  3978
183 Signal Flow Diagrams 3991
184 Immersive Audio Workflows  3993
Deliver
185 Delivery Effects Processing  4019
186 Using the Deliver Page 4024
187 Rendering Media  4033
188 Delivering DCP and IMF 4067
189 Delivering to Tape  4082
190 Exporting Timelines to Other Applications  4090
Blackmagic Cloud
191 Blackmagic Cloud Project Server  4102
192 Blackmagic Cloud Storage  4112
193 Blackmagic Cloud Presentations  4126
194 Blackmagic Cloud Organizations  4138
195 Live Sync  4150
Project Libraries, Collaborative, and Remote Workflows
196 Managing Project Libraries and Project Servers  4158
197 Collaborative Workflow 4178
198 Remote Grading and Remote Monitor 4193
Advanced Workflows
199 Workflow Integrations  4203
200 Creating DCTL LUTs  4210
201 TCP Protocol for DaVinci Resolve Transport Control  4215
Menu Descriptions
DaVinci Resolve  4220
File  4221
Edit  4222
Trim  4223
Timeline  4224
Contents
INTRO
MEDIA
CUT
EDIT
FUSION
COLOR
FAIRLIGHT
DELIVER
MENU
9
Clip  4225
Mark  4226
View  4227
Playback  4228
Fusion  4229
Color  4230
Fairlight  4231
Workspace  4232
Help  4233
Contents
INTRO
MEDIA
CUT
EDIT
FUSION
COLOR
FAIRLIGHT
DELIVER
MENU
10
DaVinci Resolve 20
Getting Started
When you install DaVinci Resolve and then open it for the first time, there are a few things you’re going
to want to know before you begin learning how to work.
Automatic DaVinci Resolve Updates
To make it easier to ensure you’re using the latest version of DaVinci Resolve, you can now
choose DaVinci Resolve > Check For Updates to notify you of new versions and download them
when available.
Why Is This Manual So Big?
Over the years, DaVinci Resolve has evolved to encompass professional editing, compositing, and
audio mixing tools and workflows in addition to the grading tools that were the original core of
DaVinci Resolve. Each one of these domains of functionality is incredibly deep. Consequently, the
documentation has grown with each new page, tool, and parameter that’s been added, to make life
easier and to solve the countless problems that can emerge during the postproduction process.
While it is regretted that this user manual contains such a staggeringly overwhelming amount of
```
information, our emphasis has always been to ensure that (hopefully) every control and workflow
```
you encounter in DaVinci Resolve is explained somewhere within the contents of these pages.
```
Consequently, we hope that you find the hyperlinked table of contents (TOC) and search functionality
```
of your preferred PDF browser helpful in finding the information you need, along with context and tips
to help you get the most out of the tools provided.
11DaVinci Resolve 20 Getting Started
INTRO
Navigation Guide
```
For ease of use navigating this manual, each table of contents (TOC) listed on this manual are
```
hyperlinked, and by clicking on each title or page number, you will be taken to the appropriate
part of the manual. On the right hand side of each page includes a hyperlink tab. As you hover the
pointer over the tab and by clicking on the tab you will be taken to main TOC page.
Chapter 131
Primaries Palette
This chapter focuses on the core color adjustments that you’ll be making tocreate “primary” corrections that alter the overall color and contrast of the imageusing both the Lift/Gamma/Gain adjustments in the Wheels and Bars modes of
the Primaries palette, and the Shadow/Midtone/Highlight/Offset controls in theLog mode, both of which have traditionally formed the foundation of most grades.
Contents
Introduction to the Primaries Palette  3059HDR Grading With the Primaries Palette 3060Which Do I Start With, the Primaries or HDR Palette? 3060
Shared Controls in the Primaries Palette 3060Switching Between Primaries Tools 3060Color Balance Controls  3061
Master Wheels 3061Numeric Parameters  3062Shared Adjustment Controls  3062
Auto Correction  3064Reset Controls  3064Color Wheels and Bars  3065
3-Way Master Wheel Adjustments  3066Offset Color and Master Controls  3067Color Bars Mode  3068
Log Wheels Mode  3068Using the Log Mode Controls to Grade Log-Encoded Media  3069Using the Log Mode Controls to Stylize Normalized Media  3071
Adjusting the Default Tone Ranges in Log Mode  3073Adjusting Contrast in Log Mode  3073Log Offset Color and Master Controls 3073
Offset and Printer Points  3074Adjusting Printer Points in the Bars Mode  3074Adjusting Printer Points Via Keyboard Shortcuts 3075
Printer Light Step Project Settings  3076
3058Color | Chapter 131 Primaries Palette
COLOR
Saving and Wiping Stills in the Gallery and TimelineThe Gallery on the Color page provides fast access to stills that you’ve saved from various clips in theTimeline. While the dedicated Gallery page provides a more comprehensive interface for browsing
presaved “looks,” as well as for importing stills from other projects, you can save, organize, andbrowse stills directly within the Gallery of the Color page.Stills are saved in the DPX file format. Once you’ve saved one or more stills, you can set up split
screen wipes in the Viewer, which will be mirrored to your external display.
Stills from the Gallery can be compared to the current shot, making it easier to match grades.This section provides an abbreviated summary of still store and split screen functionality to get you
started quickly.To save a still, do one of the following:
```
 Choose Color > Stills > Grab Still (Option-Command-G). Right-click on the Viewer and choose Grab Still.
```
```
To wipe a still, do one of the following: Select a still in the Gallery, and click the Image Wipe button on the top Viewer toolbar. Choose Color > Stills > Play Still (Command-W), or right-click in the Viewer and choose Toggle Wipe.
```
 Double-click a still in the Gallery.To adjust a wipe in the Viewer, do one of the following:
 Drag the pointer within the Viewer to move the wipe.
2999Color | Chapter 127 Viewers, Monitoring, and Video Scopes
COLOR
Hyperlink Tab
Section Name
COLOR
Color
CONTENTS
125 Introduction to Color Grading  2953126 Using the Color Page  2965
127 Viewers, Monitoring,and Video Scopes  2983128 Color Page Timeline
and Lightbox  3023129 Automated Grading Commandsand Imported Grades  3038
130 Camera Raw Palette  3052131 Primaries Palette  3058
132 HDR Palette  3077133 Primary Grading Controls  3101
134 Curves  3107135 ColorSlice  3128
136 Color Warper  3135137 Secondary Qualifiers  3157
138 Secondary Windows  3185
139 Magic Mask  3201140 Motion Tracking Windows  3229
141 Using the Gallery  3256142 Grade Management  3273
143 Node Editing Basics  3308144 Image ProcessingOrder of Operations  3329
145 Serial, Parallel,and Layer Nodes  3332146 Combining Keys
and Using Mattes  3340147 Channel Splittingand Image Compositing  3365
148 Keyframing in the Color Page  3380149 Copying and ImportingGrades Using ColorTrace  3395
150 Using LUTs  3405
119 Tracking Nodes  2732120 Transform Nodes  2788
121 USD Nodes  2816122 VR Nodes  2869
123 Warp Nodes  2880124 Modifiers  2910
Color125 Introduction to Color Grading  2953
126 Using the Color Page  2965127 Viewers, Monitoring, and Video Scopes  2983
128 Color Page Timeline and Lightbox 3023129 Automated Grading Commands and Imported Grades  3038
130 Camera Raw Palette  3052131 Primaries Palette  3058
132 HDR Palette  3077133 Primary Grading Controls  3101
134 Curves  3107135 ColorSlice  3128
136 Color Warper  3135137 Secondary Qualifiers  3157
138 Secondary Windows  3185139 Magic Mask  3201
140 Motion Tracking Windows  3229141 Using the Gallery 3256
142 Grade Management  3273143 Node Editing Basics  3308
144 Image Processing Order of Operations  3329145 Serial, Parallel, and Layer Nodes  3332
146 Combining Keys and Using Mattes  3340147 Channel Splitting and Image Compositing  3365
148 Keyframing in the Color Page  3380149 Copying and Importing Grades Using ColorTrace  3395
150 Using LUTs  3405
Contents
INTRO
MEDIA
CUT
EDIT
FUSION
COLOR
FAIRLIGHT
DELIVER
MENU
7
Section Page Main TOC
Page NumberChapter Number
Chapter Page
Page Number
Chapter Name
12DaVinci Resolve 20 Getting Started
INTROINTRO
DaVinci Resolve
Interface
CONTENTS
1 Introduction to DaVinci Resolve  14
2 Using the DaVinci Resolve User Interface  56
Chapter 1
Introduction to
DaVinci Resolve
DaVinci Resolve integrates editing, compositing and motion graphics,
color correction, audio recording and mixing, and finishing within a single,
easy to learn application. The editing, compositing, grading, and audio tools
found in DaVinci Resolve should be immediately familiar to experienced artists
who’ve used other applications, but they’re also approachable to folks who are
new to post-production.
Additionally, dedicated tools available for on-set workflows integrate tasks such as media duplication,
shot and metadata organization, and on-location look management into a complete toolset that lets
you smoothly segue from the camera original media being acquired in the field to the organization and
use of that media in a wide variety of post-production workflows with DaVinci Resolve at their heart.
In particular, the tight integration in DaVinci Resolve means that you can freely move from one task to
the next of your project’s workflow without skipping a beat, making it easy to back up and organize a
shoot’s media before immediately diving into editing, while switching over to add a quick composite
or to color-correct clips in the middle of your editing spree, and then getting right back to cutting,
with a bit of mixing to make sure things sound right, all without needing to export projects or launch
other applications.
And you can go further, using the collaborative features of DaVinci Resolve to enable multiple artists,
for example an editor, a colorist, and assistants, to work together on the same timeline simultaneously,
for the ultimate integrated workflow.
Of course, no post-production professional works in a vacuum, and DaVinci Resolve makes it easy to
work with other facilities by importing projects and exporting project exchange formats and rendered
or managed media among applications such as Apple’s Final Cut Pro X, Adobe’s Premiere Pro, Avid’s
Media Composer and Pro Tools, Autodesk’s Flame Premium, and many other applications via robust
support of XML, AAF, and EDL import and export workflows.
```
This chapter introduces the DaVinci Resolve user interface (UI), explaining where to find each group
```
of features, and how the highly focused and tightly integrated Media, Edit, Fusion, Color, Fairlight,
and Deliver pages work together to let you pursue nearly any post-production workflow you can
imagine. After this brief tour, the rest of Part 1 of this manual provides much more in-depth information
about project management, preferences, project settings, and other topics of general interest for
getting started.
14DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Contents
The Project Manager  16
Preferences and Project Settings  17
Individual Preferences
and Settings Based on Login  17
Preferences  17
System Preferences  18
User Preferences  19
Project Settings 20
Switching Among Pages 21
Minimizing the Resolve Page Bar 21
Switching Pages Using Keyboard Shortcuts  21
Hide Pages You Don’t Use  21
Hide Page Navigation Altogether  22
The Media Page  22
The Media Storage Browser  23
Viewer 23
Media Pool 24
Metadata Editor  25
Audio Panel  25
The Cut Page  26
The Media Pool  26
The Viewer  27
Audio Meter  28
The Timeline  28
The Edit Page  29
The Media Pool  30
Effects Library Browsing 30
Edit Index  31
Source/Offline and Timeline Viewers  32
Inspector  33
Toolbar  33
Timeline  33
Floating Timecode Window  34
Motion Graphics and
Visual Effects in DaVinci Resolve  34
VFX Connect  35
The Fusion Page  36
The Work Area 36
Viewers  37
Toolbar  37
Effects Library  38
Node Editor  38
Inspector  39
Thumbnail Timeline 40
Media Pool  40
Status Bar 41
The Console  41
The Color Page  42
Viewer 42
Gallery  43
Node Editor  44
Timeline  44
Left Palettes  45
Center Palettes  45
Keyframe Editor  46
The Fairlight Page  47
The Audio Timeline  47
Toolbar  49
Mixer  49
Dedicated Channel Strip Controls  49
The Monitoring Panel  51
Floating Timecode Window  52
The Deliver Page  52
The Render Settings List  53
The Deliver Page Timeline  53
The Viewer  54
The Render Queue 55
15DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Project Manager
For most users, Project Manager is the first window you’ll see when you open DaVinci Resolve.
The Project Manager is a centralized interface for managing all projects belonging to the user
who’s currently logged in, whose name appears at the upper right-hand corner in a project title
bar. The Project Manager is also the place where you import and export projects to and from
DaVinci Resolve, whether you’re moving projects around from user to user, or moving projects from
one DaVinci Resolve workstation to another. Finally, the Project Manager also lets you organize
the project libraries that are used to manage everything in DaVinci Resolve using the Project
Library sidebar.
To open any project, double-click it. To create a new project, double-click the Untitled Project icon,
or click the New Project button.
The Project Manager shows all projects belonging to the current user.
For more information about the Project Manager, see Chapter 3, “Managing Projects and
Project Libraries.”
16DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Preferences and Project Settings
Once you open a project, you have the option of adjusting the System and User Preferences that
govern the installation of DaVinci Resolve on your workstation, and the Project Settings governing the
currently open project. When you first install DaVinci Resolve, the most important of these settings are
selected via the installer’s on boarding questions. However, if you’re opening DaVinci Resolve for the
first time, you should probably check these settings to make sure they’re optimal for your system.
Individual Preferences and Settings Based on Login
As of DaVinci Resolve 16, there are individual preferences and settings for each login account on a
given computer. This means that multiple artists can each have their own login, and DaVinci Resolve
will maintain separate workspace layouts and preference states for each artist, depending on who’s
logged in.
Preferences
The Preferences window, divided into System preferences and User preferences panels, lets you set
up the overall environment of your DaVinci workstation, choosing what hardware to use with DaVinci
Resolve and what user interface settings you prefer as you work.
The DaVinci Resolve preferences let you set up your environment
17DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
A quick overview of the most important System and User preferences appears below, with
guidance about the first settings you should adjust when you first set DaVinci Resolve up on
your workstation. However, for a comprehensive overview and for more information,
see Chapter 4, “System and User Preferences.”
System Preferences
The System preferences let you configure the hardware DaVinci Resolve works with. If you have a
system that doesn’t change very often, then you may only rarely use the Preferences window. On the
other hand, if you’re working with a mobile system with changing video interfaces, control panels, and
scratch volumes, then you may use this window more frequently.
```
NOTE: Whenever you change certain core System Settings in the Preferences, you may have
```
to quit and restart DaVinci Resolve for those changes to take effect.
Memory and GPU
Lets you choose various options governing how to use the GPUs attached to your computer, and
how to configure Viewers in different pages. This panel also provides an overview, for reference,
of all hardware and computer characteristics that are relevant to DaVinci Resolve running smoothly,
including a listing of installed GPUs.
Media Storage
This is a list within which you define the scratch disk used by your system. The first volume in this list
is where Gallery stills and cache files are stored, so you want to make sure that you choose the fastest
storage volume that’s connected.
Decode Options
These settings let you select various hardware options for decoding RAW files and H.264/H.265. It
```
also lets you choose to use the easy DCP decoder and the ability to refresh growing any files (files that
```
```
are in the process of being written) in the Media Pool.
```
Video and Audio I/O
The preferences in this panel let you choose which video and audio Capture and Monitor interfaces
you want DaVinci Resolve to use on your workstation. If you have multiple Blackmagic Design
I/O interfaces connected to your computer, you can choose between them.
Video Plugins
If you have any third-party Open FX plugins installed, you can see them and enable/disable
them here.
Audio Plugins
If you have any third-party VST plugins installed, you can see them and enable/disable them here.
Control Panels
```
Lets you choose and configure (if necessary) a control panel that’s connected for use during grading in
```
DaVinci Resolve.
18DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
General
Lets you choose from a variety of settings that modify DaVinci Resolve’s behavior. The LUT Locations
section lets you point DaVinci Resolve to any external folders containing LUTs for use in your project.
Internet Accounts
The Internet Accounts panel serves as a login manager for the Blackmagic Cloud and other social
media sites.
Advanced
This tab is used for special DaVinci Resolve configurations and SAN parameters that are applicable to
older file systems.
User Preferences
User preferences govern the setup of the user interface in DaVinci Resolve, letting you customize
it to work the way you like.
UI Settings
A Language drop-down menu at the top lets you specify which language the DaVinci Resolve user
interface displays. DaVinci Resolve currently supports English, Chinese, Japanese, and Spanish,
Portuguese, French, Russian, Thai, Vietnamese, and Korean. Additional checkboxes let you choose
options for which project to open during startup, and how to configure the Viewers that appear in
every page of DaVinci Resolve.
Project Save and Load
This panel contains the all-important auto-save controls, including the Live Save option that enables
Resolve to incrementally save your changes as you work.
Editing
Numerous controls in this panel let you customize the editing experience in the Edit page, including
default settings to use when making new timelines, and general settings that govern standard effects
durations and trim behaviors.
Color
These controls let you customize the grading experience in the Color page, with options controlling
video scope display, the look of UI overlays, and other color-specific functions.
Fairlight
These controls let you customize the editing experience in the Fairlight page with options controlling
video offset, automation, and general settings.
Playback Settings
These controls let you customize how DaVinci Resolves handles video playback. If your playback is
too slow, adjusting these settings may help.
Control Panels
These controls let you customize the settings of your connected control surface.
Metadata
These controls let you customize the Metadata Presets.
19DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Project Settings
Once you’ve created a project, all project-specific settings are found in the Project Settings window.
To open the Project Settings window, just click the gear button at the bottom right on any page.
Project Manager and
Project Settings buttons
The Project Settings open in the middle of the screen, divided into a series of panels which can be
selected from a sidebar to the left. Each panel contains a collection of related settings that affects
some category of DaVinci Resolve functionality. To open a panel of settings, simply click its name in
the sidebar at the left.
The Project Settings show all project-specific settings and attributes.
20DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Master Settings define the principal attributes of a project, such as the timeline resolution,
timeline frame rate, color science, and bit depth. Image Scaling settings define how clips that
don’t match the timeline resolution are scaled to fit. There are other panels for Color Management,
Camera Raw, Capture and Playback, etc.
For more information about Project Settings, see Chapter 4, “System and User Preferences.”
Switching Among Pages
Buttons for switching pages appear at the bottom of the UI.
DaVinci Resolve is divided into seven main pages of functionality, each of which facilitates a different
specialization of a typical post production workflow, and each of which can be accessed using buttons
at the very bottom of the DaVinci Resolve interface. These buttons are organized in order of workflow,
and they’re always available, letting you quickly switch between importing media, fast editing, detailed
editing, compositing, grading, audio mixing, and outputting your project in a structured manner.
Minimizing the Resolve Page Bar
If you right-click anywhere within the Resolve Page bar at the bottom of the DaVinci Resolve UI,
two options appear in a contextual menu: “Show Icons and Labels” and “ Show Icons Only.” If you
show icons only, the Resolve Page bar at the bottom takes less room.
The Page bar showing icons only, to save space
Switching Pages Using Keyboard Shortcuts
You can also switch pages using the following keyboard shortcuts, which can be referenced from the
Workspace > Switch to Page submenu.
Hide Pages You Don’t Use
You can leave the page navigation bar showing and just hide the buttons of specific pages.
For example:
 If you like the quick navigation of this bar but there are pages you simply don’t want to use
 If you’re setting up a DaVinci Resolve workstation for an artist making specific contributions to a
```
project, and you want to hide easy access to pages of functionality they won’t (or shouldn’t) be
```
```
using; this can be especially useful in collaborative workflow projects
```
You can disable/re-enable each page’s buttons using the Workspace > Show Page submenu.
Effects and adjustments that have been applied on hidden pages continue to affect the current
project, they’re only hidden, and you can still navigate to them using the Workspace > Switch to Page
submenu commands or keyboard shortcuts.
21DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Hide Page Navigation Altogether
If you’re an artist that only uses a single page of the DaVinci Resolve experience, or if you want more
screen real estate to work with given your existing computer display’s limited resolution, you can
choose Workspace > Show Page Navigation to hide the page navigation bar at the bottom of the
DaVinci Resolve user interface. While this bar is closed, you can still navigate to other pages using the
Workspace > Switch to Page submenu commands or keyboard shortcuts.
To toggle the Show Page Navigation function:
Check Workspace > Show Page Navigation.
With this interface element hidden, you can use keyboard shortcuts to access the individual
```
pages (Shift - 2 through 8), Project manager (Shift - 1), and Project settings (Shift - 9). You can
```
also access these functions from DaVinci Resolve’s main menu bar.
The Media Page
The Media page is the primary interface for clip import, media management, and clip organization in
DaVinci Resolve. It’s central to the way DaVinci Resolve works that the source media used by a project
is organized separately from the project data that you import and manage in the Edit page. In this way,
you can manage and update the clips used by timelines in the current project with ease, switching
between offline and online media, reorganizing clips, and troubleshooting any problems that occur.
Media page
The Media page also contains much of the core functionality that will be used for on-set workflows,
and in the ingest, organizational, and sound-syncing steps of digital dailies workflows. This chapter
covers most of the functionality found in the Media page, including functions in detail that are
referenced throughout this manual.
22DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Media page is divided into six different areas, designed to make it easy to find, select, and work
with media in your project. Much of the functionality and most of the commands are found within the
contextual menus that appear when you right-click clips in the Library, File Browser, or Media Pool.
For more information on using the Media page, see Chapter 17, “Using the Media Page.”
The Media Storage Browser
The Media Storage browser shows a list of all volumes that are currently available to your Resolve
workstation. It’s used to locate media that you want to import manually into your project.
Media Storage with scrubbable Clip view
Viewer
Clips that you select in any area of the Media page show their contents in the Viewer. A jog bar
appears at the bottom, letting you drag the playhead directly with the pointer, while a jog control
between the mode drop-down and transport controls lets you move through a long clip more
slowly. The full width of the jog bar represents the full duration of the clip in the Viewer. The current
position of the playhead is shown in the timecode field at the upper right-hand corner of the Viewer.
Simple transport controls appear underneath the jog bar, letting you Jump to First Frame, Play/Stop,
and Jump to Last Frame. Audio levels can be adjusted by right-clicking on the speaker icon and
dragging the slider.
You can also put the Viewer into Cinema Viewer mode by choosing Workspace > Viewer Mode >
```
Cinema Viewer (Command-F), so that it fills the entire screen. This command toggles Cinema Viewer
```
mode on and off.
If you have two monitors connected to your computer, you can make the Viewer fill one entire screen
and keep the Resolve UI in the other monitor by choosing Workspace > Full Screen Viewer On, and
selecting the display you wish to use for the Viewer.
23DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Media page Viewer
Media Pool
The Media Pool contains all of the video, audio, and still image media that you import into the current
project. It also contains any media that’s automatically imported along with timelines that have been
imported into DaVinci Resolve. Ordinarily, all media imported into a project goes into the Master bin,
however the Media Pool can be organized into as many user-definable bins as you like, depending
on your needs. Media can be freely moved from one bin to another from within the Media Pool. The
Media Pool also appears on the Edit, Fusion, Color, and Fairlight pages, making it possible to browse
and open clips and timelines everywhere they’re relevant.
Media Pool showing the selected bins’ clips
24DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Metadata Editor
When you select a clip in any area of the Media page, its metadata is displayed within the Metadata
Editor. If you select multiple clips, only the last clip’s information appears. The Metadata Editor’s header
contains uneditable information about the selected clip, including the file name, directory, duration,
frame rate, resolution, and codec.
A series of editable fields within the Metadata Editor lets you review and edit the different metadata
items that are available. A drop-down menu at the upper right of the Metadata Editor lets you choose
from many different sets of metadata fields and checkboxes, each grouped for a specific task
or workflow.
Clip Metadata Editor Audio Meters exposed
Audio Panel
The Audio panel can be put into one of two modes via a pair of buttons above the audio meters.
In the default Meters mode, Audio Meters are displayed that show the levels of audio in clips you’re
playing. In Waveform mode, you can load audio clips side by side with video clips opened in the
Viewer in order to sync them together manually. The Audio panel can also be hidden.
25DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Cut Page
The Cut page is a focused environment for fast editing. It’s useful in situations where you need
to quickly cut a news segment, build an episode of web content, edit a straightforward program,
experiment with multiple arrangements of a scene, or put together a first assembly edit.
The Cut page is also a good introductory editing interface for people who are new to editing, as it
presents a streamlined set of tools that are fast to learn and simple to use. Whatever your background,
you’ll find the Cut page to be a valuable addition to your editing experience in DaVinci Resolve.
The default workspace of the Cut page consists of the Media Pool, a single Viewer, and the Timeline
area. These three regions let you quickly import and organize clips, edit clips, and even export the
result, all from within the Cut page.
The Cut page
For more information on the Cut page, see Chapter 26, “Using the Cut Page.”
The Media Pool
The Media Pool appears in the Cut page as well, and contains all video clips, audio clips, graphics,
and other media that you import into your project. You can create Bins with which to organize all of this
media, to make it easier to find what you need quickly. These bins are opened via the bin drop-down
at the upper left-hand corner.
Each piece of media you import, whether it’s video, audio, or graphics, appears as an individual clip,
and they can be selected, scrubbed for fast viewing, reorganized into bins, opened into the Viewer for
playback, or edited into a timeline using the edit buttons or via drag and drop.
Owing to the Cut page’s mission to make editing faster, the Media Pool has different options for
```
viewing (such as the Strip view) and customizing.
```
26DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Strip View mode
The Viewer
The Viewer lets you see clips from the Media Pool or clips in the Timeline play, and has numerous
controls to control what you see and how things play.
The single Viewer in the Cut page
The Viewer has four mode options. Which option is currently in use can be seen, and switched, by four
buttons in the upper left-hand corner of the Viewer.
The Viewer modes buttons
27DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
```
The Different options are entered automatically by various actions (from left to right):
```
 You can double-click any clip to open it into the Viewer as a Source Clip.
 You can view an entire bin full of clips in the Source Tape.
 You can play your edited program in the Timeline.
 You can see all of your synced material at the same time in the Multi Source Viewer.
Clicking the Tools button in the lower left of the Viewer reveals an effects toolbar that you can use
to add and edit clip effects, right within the Viewer with no Inspector needed. The Tools button
reveals a variety of controls over sizing, cropping, audio, speed effects, stabilization, dynamic zoom,
and compositing.
The Tools bar shown opened
Audio Meter
An audio meter to the right of the Viewer shows you a graphical representation of the audio levels
playing in the current clip or in the Timeline as you play through the Viewer, via animated vertical bars
that are tinted to indicate how loud the levels are.
The Timeline
The word “timeline” refers both to an edited sequence of clips which constitutes a program that is
stored in the Media Pool, and to the area of the Cut page interface where you can open this sequence
of clips to see its contents, and for playback and editing.
For the Cut page user, the timeline is divided into an Upper Timeline at the top, and a larger and more
detailed Timeline Editor showing a zoomed in portion of the timeline around the playhead at the
bottom. Working together, these two views of your edited sequence make it possible to navigate your
entire project and cut in great detail.
The Timeline of the Cut page, comprising the Upper Timeline and the zoomed in Lower Timeline
Three icons at the upper left-hand corner of the Timeline lets you choose a variety of timeline tasks.
They are composed of Timeline Options, Timeline Actions, and Edit Actions.
The Timeline is divided into multiple tracks, with each track capable of holding a sequence of clips in
order to create a program. The main tracks, which are labeled numerically, combine a clip’s video and
audio into a single item in the Timeline, for simplicity. Editing the In or Out point of a clip edits the video
and audio together.
28DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Action icons
in the Cut page
Video+Audio tracks
in the Cut page Timeline
```
TIP: In the Edit page, Video+Audio clips are presented as separated Video and Audio items
```
on different tracks. When you open the Fairlight page, audio is presented on tracks with
lanes, where each audio channel can be seen. In this way, each page gives you different sets
of controls over the contents of the timeline that are appropriate for each page.
The Edit Page
The Edit page exposes a source-record style NLE that incorporates many specialized features for both
creative editing and finishing. The Edit page is divided into three main regions: the browsers found at
the left, the Viewers at the top, and the Timeline at the bottom, all of which work together to let you
import, edit, and trim timelines with a flexible variety of tools and methods.
The Edit page
For more information on the Edit page, see Chapter 33, “Using the Edit Page.”
29DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Media Pool
As with everywhere else it appears in DaVinci Resolve, the Media Pool lets you organize and peruse
all of the media and timelines in a project. DaVinci Resolve projects may contain one or more edited
```
timelines (sometimes called a sequence in other applications).
```
The Media Pool in the Edit page is identical to that shown on the Media, Fusion, Color, and Fairlight
pages, and shows you all of the source clips and timelines that are available for editing. A Bin list at the
left shows a hierarchical list of folders that you can use to organize your media.
By default, the Media Pool has a single bin, named “Master,” but you can add more bins as necessary
to organize your clips, opening any of them to expose their contents with a single click. The Bin list can
be hidden or shown via the button at the upper-left of the Media Pool. A browser to the right shows
the contents of the currently selected bin.
The Media Pool in Thumbnail mode
Effects Library Browsing
The Effects Library contains a folder with the different Video Transitions, Title Effects, Generators, and
Filters that are available for editing in the Timeline. The Effects Library has two panels, a Toolbox panel
that contains the default Transitions, Titles, and Generators that Resolve comes with, and an OpenFX
panel that contains any OpenFX transitions and generators you might have installed on your system.
30DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Effects Library
Edit Index
Clicking the Index button opens the Edit Index. By default, this shows an EDL-style list view of all the
edit events in the current timeline. Whichever timeline is selected in the Timeline list displays its events
```
here; each clip and transition is shown as an individual event, each of which contains multiple columns
```
of information. If you re-edit a timeline, your changes are automatically reflected in this list.
Edit Index List shown open
31DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Source/Offline and Timeline Viewers
The Source Viewer lets you view individual clips from the Media Pool to prepare them for editing.
Meanwhile, the Timeline Viewer shows the frame at the position of the playhead in the Timeline. You
can select either viewer by clicking, and the name of the viewer that currently has focus appears in
orange. The color shown in the Source Viewer usually reflects that of the original source media, while
the Timeline Viewer shows whatever grading you’ve done in the Color page.
Source and Timeline Viewers
If you want to change the Edit page layout to hide the Source Viewer, you can choose Workspace >
Single Viewer Mode to hide the Source Viewer and instead use just a single viewer to contextually
display either a selected Source Clip or the current frame of the Timeline.
Single Viewer mode
In Single Viewer mode, whatever you select in the Media Pool or Timeline determines which controls
appear in the Viewer, which lets you do nearly everything you can do with two simultaneously
open viewers.
You can also put either the Source or Timeline Viewers into Cinema Viewer mode by choosing
```
Workspace > Viewer Mode > Cinema Viewer (Command-F), causing whichever viewer is currently
```
selected to fill the entire screen. This command toggles Cinema Viewer mode on and off.
32DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Inspector
The Inspector can be opened to let you customize compositing, transform, and cropping parameters
for clips, as well as clip-specific retime and scaling options. Furthermore, the Inspector lets you edit
the parameters of transitions, titles, and generators used in the Timeline, in order to customize their
effect. Ordinarily, the Inspector opens alongside the Source and Timeline Viewers, but on smaller
displays, opening the Inspector switches the Edit page to a single-viewer mode, showing you the
Timeline item that you’re inspecting alongside the Inspector with that clip’s parameters.
The Inspector, opened and showing a clip’s parameters
Toolbar
Eleven buttons starting from the left, running along the top of the Timeline, let you choose different
tools for performing various editing functions.
Buttons in the toolbar
Timeline
The Timeline shows whichever timeline you’ve double-clicked in the Timelines browser. It’s the
workspace where you either edit programs together from scratch, or import sequences from other
applications to work on inside of Resolve. You can only have one Timeline open at a time.
The Timeline is divided into audio and video tracks, each of which has a series of header controls
at the left that let you choose destination tracks for editing, name tracks, and turn tracks on and off,
among other things. The appearance of the Timeline can be customized using the Timeline View
Options drop-down in the toolbar.
33DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
An edited timeline
Floating Timecode Window
A timecode window is available from the Workspace menu on every page, including the Edit page.
Choosing this option displays a floating timecode window that shows the timecode of the Viewer
or Timeline that currently has focus. This window is resizable so you can make the timecode larger
or smaller.
A new floating timecode window is available
Motion Graphics and
Visual Effects in DaVinci Resolve
To begin with, DaVinci Resolve has a wealth of effects in both the Edit and Color pages for creating
titles, transforming and animating clips, compositing and creating transparency effects, cutting mattes,
applying filters, image stabilization, lens dewarping, and so on.
Then of course there’s the Fusion page, which adds considerably more powerful VFX and motion
graphics capabilities via its node-based interface and deep toolset of effects nodes, keyframing and
curve editing controls, and 2D and 3D compositing features.
34DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
To use DaVinci Resolve to the best effect, it’s prudent to begin to think of the Edit, Fusion, and
Color pages as complementary sets of controls.
```
• For editors, the Fusion and Color pages are really just two giant inspectors; one filled with
```
every compositing tool you could hope to use, and the other filled with every control for
color and visual adjustment you could want, each of which are only one click away.
• For compositing artists, the Edit page can be considered a robust shot management
interface as well as an opportunity to do VFX work that’s deeply integrated with the edit of
the program you’re working on.
• For colorists, the Edit page is a refined environment for dealing with conform issues and
taking care of myriad finishing tasks quickly and easily, that itself is only one click away.
For more information on the effects that are available in DaVinci Resolve, see the
chapters available within Part 6, “Editing Effects and Transitions” and Part 11, “Color
Page Effects”.
VFX Connect
As robust as the built-in compositing capabilities of DaVinci Resolve now are, when you run into
instances where the various capabilities found in the Edit, Fusion, and Color pages aren’t enough to
achieve the effect you require, you can use the VFX Connect features of DaVinci Resolve to send one
or more clips from the Edit page Timeline to Blackmagic Fusion, the powerful node-based compositing
application from Blackmagic Design, in order to do more robust compositing and effects work there.
Furthermore, the VFX Connect feature can also be used to round-trip media to and render results from
third-party applications such as The Foundry’s Nuke, Autodesk Flame, or Blender.
The New VFX Connect Clip dialo
This is a simple round-trip operation that lets you send clips from the DaVinci Resolve timeline to
Fusion or another application, where you’ll add effects and do whatever work needs to be done
before rendering a finished effect file that, if properly named, will automatically appear back in your
timeline. When you use VFX Connect with Blackmagic Fusion, a project file is automatically generated
and the render path is automatically named for automatic linking from the DaVinci Resolve timeline.
If you use this feature with third-party applications, you’ll need to set up the naming of your rendered
effect file manually.
For more information, see Chapter 63, “Introduction to Compositing in Fusion.”
35DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Fusion Page
The Fusion page is intended, eventually, to be a feature-complete integration of Blackmagic Design
Fusion, a powerful 2D and 3D compositing application with over thirty years of evolution serving
the film and broadcast industry, creating effects that have been seen in countless films and
television series.
Merged right into DaVinci Resolve with a newly updated user interface, the Fusion page makes it
possible to jump immediately from editing right into compositing, with no need to export media, relink
files, or launch another application to get your work done. Everything you need now lives right inside
DaVinci Resolve.
The Fusion page showing Viewers, the Node Editor, and the Inspector
For more information on using the Fusion page, see Chapter 63, “Introduction to Compositing
in Fusion.”
The Work Area
You’ll probably not see this term used much, in favor of the specific panels within the work area that
you’ll be using, but the area referred to as the Work Area is the region at the bottom half of the Fusion
page UI, within which you can expose the three main panels used to construct compositions and edit
animations in the Fusion page. These are the Node Editor, the Spline Editor, and the Keyframes Editor.
By default, the Node Editor is the first thing you’ll see, and the main area you’ll be working within, but it
can sit side by side with the Spline Editor and Keyframes Editor as necessary, and you can make more
horizontal room on your display for these three panels by putting the Effects Library and Inspector into
half-height mode, if necessary.
36DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Work Area showing the Node Editor, the Spline Editor, and Keyframes Editor
Viewers
The Viewer Area area encompasses the Time Ruler and transport controls. The Time Ruler is the
principal “timeline” of the Fusion page, which focuses exclusively on the current composition you’re
working on and may consist of one clip or several. This area can be set to display either one or two
viewers at the top of the Fusion page, chosen via the Viewer button at the far right of the Viewer title
bar. Each viewer can show a single node’s output from anywhere in the node tree. You assign which
node is displayed in which viewer. This makes it easy to load separate nodes into each viewer for
comparison. For example, you can load a Keyer node into the left Viewer and the final composite into
the right Viewer, so you can see the image you’re adjusting and the final result at the same time.
Dual viewers let you edit an upstream node in one while seeing its effect on the overall composition in the other
Ordinarily, each viewer shows 2D nodes from your composition as a single image. However, when
you’re viewing a 3D node, you have the option to set that viewer to one of several 3D views, including
a perspective view that gives you a repositionable stage on which to arrange the elements of the
world you’re creating, or a quad view that lets you see your composition from four angles, making
it easier to arrange and edit objects and layers within the XYZ axes of the 3D space in which
you’re working.
Toolbar
The toolbar, located underneath the Time Ruler, contains buttons that let you quickly add commonly
used nodes to the Node Editor. Clicking any of these buttons adds that node after the currently
selected node in the node tree, or adds an unconnected instance of that node if no nodes
are selected.
The toolbar has buttons for adding commonly used nodes to the Node Editor
37DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The toolbar is divided into six sections that group commonly used nodes together.
As you hover the pointer over any button, a tooltip shows you that node’s name.
Effects Library
The Effects Library on the Fusion page shows all of the nodes and effects that are available in the
Fusion page, including effects that come with DaVinci Resolve and third-party OFX, if available. While
the toolbar shows many of the most common nodes you’ll be using in any composite, the Effects
Library contains every single tool available in the Fusion page, organized by category, with each node
ready to be quickly added to the Node Editor. Suffice it to say there are many, many more nodes
available in the Effects Library than on the toolbar, spanning a wide range of uses.
The Effects Library with Tools open
Node Editor
The Node Editor is the heart of the Fusion page, because it’s where you build the tree of nodes that
makes up each composition. Each node you add to the node tree adds a specific operation that
creates one effect, whether it’s blurring the image, adjusting color, painting strokes, drawing and
adding a mask, extracting a key, creating text, or compositing two images into one.
38DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Node Editor displaying a node tree creating a composition
Inspector
The Inspector is a panel on the right side of the Fusion page that you use to display and manipulate
the parameters of one or more selected nodes. When a node is selected in the Node Editor, its
parameters and settings appear in the Inspector, ready for you to modify. The Fusion Inspector is
divided into two panels. The Tools panel shows you the parameters of selected nodes.
The Modifiers panel shows you different things for different nodes. For all nodes, it shows you
the controls for Modifiers, or adjustable expressions, that you’ve added to specific parameters to
automatically animate them in different ways.
The Inspector shows parameters
from one or more selected nodes
Nodes with different tabs expand the Controls,
Transform, and Settings parameters
39DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Additionally, many nodes expose multiple tabs’ worth of controls in the Inspector,
seen as icons at the top of the parameter section for each node. Click any tab to
expose that set of controls.
Thumbnail Timeline
Hidden by default, the Thumbnail timeline can be opened by clicking the Clips button in the UI Toolbar
and appears underneath the Node Editor when it’s open. The Thumbnail timeline shows you every
clip in the current Timeline, giving you a way to navigate from one clip to another when working on
multiple compositions in your project and providing an interface for creating and switching among
multiple versions of compositions and resetting the current composition, when necessary.
The Thumbnail timeline lets you navigate the Timeline and manage versions of compositions
Media Pool
In the Fusion page, the Media Pool continues to serve its purpose as the repository of all media you’ve
imported into your project. This makes it easy to add additional clips to your compositions simply by
dragging the clip you want from the Media Pool into the Node Editor. The media you add appears as a
new MediaIn node in your composition, ready to be integrated into your node tree however you need.
The Media Pool in Thumbnail mode showing video clips
40DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Status Bar
The status bar at the bottom of the Fusion page, immediately above the Resolve Page bar, shows
you a variety of up-to-date information about things you’re selecting and what’s happening in the
Fusion page.
For example, hovering the pointer over any node displays information about that node in the
```
status bar (as well as in a floating tooltip), while the currently achieved frame rate appears
```
whenever you initiate playback, and the percentage of the RAM cache that’s used appears at
all times. Other information, updates, and warnings appears in this area as you work.
The status bar under the Node Editor showing you
information about a node under the pointer and a floating tooltip
The Console
The console, available by choosing Workspace > Console, is a window in which you can see the error,
log, script, and input messages that may explain something the Fusion page is trying to do in greater
detail. The console is also where you can read FusionScript outputs or input FusionScripts directly.
```
Occasionally, the status bar (described above) will display a badge to let you know there’s a message
```
in the console you might be interested in. The badge will indicate if the message is an error, log,
or script message.
The Console window
41DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Color Page
The Color page is where you color correct, or grade, your program. It has all of the controls available
for manipulating color and contrast, reducing noise, creating limited secondary color corrections,
building image effects of different kinds, adjusting clip geometry, and making many other corrective
and stylistic adjustments. The Color page is divided into seven main areas that work together to let
you build a grade.
For more detailed information about the Color page, see Chapter 124, “Using the Color Page.”
The Color page
Viewer
The Viewer shows the frame at the current position of the playhead in the Timeline. The contents
of the Viewer are almost always output to video via whichever I/O interface you have connected.
At the top of the Viewer is a header that displays the Project and Timeline names, as well as a Viewer
Timecode display that shows the source timecode of each clip by default. The Timeline name is also
```
a drop-down display that lets you switch to any other timeline in the project. A jog bar (sometimes
```
```
referred to as a scrubber bar) underneath the image lets you drag the playhead across the entire
```
duration of the clip, while transport controls underneath that let you control playback. A toolbar at the
top provides controls governing Image Wipes, Split-Screen controls, and Highlight display. Additional
controls let you turn audio playback on and off, or adjust them by right-clicking on the speaker icon
and dragging the slider. You can also choose which onscreen controls are currently displayed.
42DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Viewer with transport controls
You can also put the Viewer into Cinema Viewer mode by choosing Workspace > Viewer Mode >
```
Cinema Viewer (Command-F), so that it fills the entire screen. This command toggles Cinema Viewer
```
```
mode on and off. Two other modes, Enhanced Viewer (Option-F) and Full Screen Viewer (Shift-F), are
```
available to provide more working area for tasks such as window positioning and rotoscoping.
Gallery
The Gallery is used for storing still frames to use as reference when comparing clips to one another.
```
Each still frame also stores that clip’s grade so you can copy it later; stills and grades are stored
```
together. A button lets you open up the Album browser, used for organizing your stills. At the top of the
Gallery, Memories let you store grade information that you can apply using a control panel or keyboard
shortcuts. You can also open a larger Gallery window within the Color page that provides more room
for organizing your saved stills and grades.
For more information on the Gallery page, see Chapter 141, “Using the Gallery.”
The Gallery has Memories, stills saved in albums, and your PowerGrades
43DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Node Editor
```
The Node Editor is where you assemble one or more individual corrections (nodes) together to create
```
```
multi-correction grades (seen as node trees). This is a powerful way of assembling grades, since
```
different combinations of nodes let you create different corrections and very specific adjustments by
reordering operations, combining keys, or changing the layer order of different adjustments.
For more information about the Node Editor, see Chapter 143, “Node Editing Basics.”
Node Editor to construct your grade processing signal flow
Timeline
The Timeline in the Color page reflects the contents of the Timeline in the Edit page, but has a
different appearance that’s tailored to the requirements of the colorist. However, the content is
identical, and changes made to the Timeline in the Edit page are immediately seen in the Color page
as you switch back and forth. The Color page Timeline provides several ways of navigating the clips in
your project, as well as keeping track of what has been done to which clips.
The Color page Timeline
44DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Timeline is divided into three parts, each of which shows different information and provides
differing controls. A Timeline Ruler at the top lets you scrub the playhead across multiple clips,
and can be zoomed out enough to show every clip in your entire program. Underneath, the Mini-
```
Timeline (which can be opened or closed via a button at the right of the palette bar) shows a small
```
representation of the Timeline in the Edit page wherein each clip is as long as its actual duration.
At the bottom of the Timeline is the Thumbnail timeline, in which each clip is represented by a single
frame. The currently selected clip is outlined in orange, and information appears above and below
each thumbnail such as each clip’s source timecode, clip number and track number, version name,
whether it’s been graded, whether it’s been tracked, if it’s been flagged, and so on.
Left Palettes
A series of palettes at the bottom left of the Color page provide access to different sets of grading
tools, used principally for manipulating color, contrast, and raw media format settings. Each individual
palette is opened by clicking the corresponding icon at the top of the Palette panel.
Left palette selection buttons in the top bar
```
The available palettes are the Camera Raw palette (for making metadata adjustments to raw media
```
```
formats), the Color Match palette (for creating automatic grades by sampling on-camera color charts),
```
```
the Color Wheels (graphical color balance controls and master wheels or sliders for adjusting YRGB
```
```
Lift/Gamma/Gain), HDR Grade for enhanced High Dynamic Range grading, the RGB Mixer (for mixing
```
```
color channels into one another), and the Motion Effects palette (with controls for noise reduction and
```
```
artificial motion blur).
```
Center Palettes
At 1920x1080 resolution or higher, a second set of palettes is organized at the bottom center of the
Color page. These palettes span a wide range of functionality, and the adjustments you make with
them can be combined with those made using the Color palettes.
Center palette selection buttons
45DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
```
NOTE: At lower resolutions, the Left and Center palettes are merged to fit the
```
DaVinci Resolve interface into a smaller area.
The eight available Center palettes include the Curves palette, the Color Warper palette, the Qualifiers
palette, the Windows palette, the Tracker palette, the Magic Mask palette, the Blur palette, the Key
palette, the Sizing palette, and the Stereoscopic 3D palette.
Keyframe Editor
The Keyframe Editor provides an interface for animating Color, Sizing, and Stereo Format adjustments
over time. Each node in the Node Editor corresponds to a track in the Keyframe Editor, which lets you
animate each node’s adjustments independently.
Keyframe Editor displaying dynamic grade changes
Furthermore, each node’s track can be opened up to reveal parameter groups, so that you
can animate subsets of an individual node’s functions independently of other functions within
the same node.
46DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Fairlight Page
In single monitor mode, the Fairlight page is an optimized look at the audio tracks of your project, with
an expanded mixer and custom monitoring controls that make it easy to evaluate and adjust the levels
of your program in order to create a smooth and harmonious mix.
Fairlight page
About Audio Monitoring and Audio Input
The audio processing throughout DaVinci Resolve, including on the Fairlight page and
audio processing using Fairlight FX plugins, is equally compatible with all platforms that
DaVinci Resolve runs on, including macOS, Windows, and Linux.
DaVinci Resolve supports audio monitoring using:
• The audio of a supported Blackmagic Design I/O device such as an UltraStudio or Decklink.
• Your macOS, Windows, or Linux workstation’s on-board audio.
• Any Core Audio compatible, Windows compatible, or Advanced Linux Sound
```
Architecture (ALSA)-supported third-party audio interface.
```
• The Fairlight Audio Accelerator, MADI Upgrade, and Fairlight Audio Interface.
DaVinci Resolve supports audio input using the embedded audio on an incoming
SDI video feed when capturing incoming A/V source, via system audio and also via the
Fairlight Audio Accelerator, MADI Upgrade, and Fairlight Audio Interface.
The Audio Timeline
The heart of the Fairlight page, the Audio Timeline presents the audio channels and tracks of the
currently selected timeline differently than the Edit page does, in a one-channel-per-track format that’s
optimized for audio mixing and sweetening. The Audio page Timeline cannot be closed.
47DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Audio Timeline
Audio layering in a mono audio track
The Fairlight page of DaVinci Resolve supports multiple audio tracks, and each audio track may
contain multiple lanes. The clips edited into the Timeline appear within each track, with the recorded
channels within each clip occupying as many lanes as that clip has available. At the left of each track is
a header area that contains a number of controls.
The Fairlight page differs in another unique respect from the Edit page Timeline, in that it supports
audio layering. Audio layering is a special audio editing mode that lets you superimpose multiple audio
clips in the same track, and whatever audio clip is on top dictates which audio will play. In a way, when
audio layering is enabled, superimposed audio clips are treated the same as superimposed video clips
```
that all have opacity set to 100%, with clips on top obscuring (or muting) clips underneath.
```
Turning on Track Layers opens up space to edit more audio into each track
48DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Audio layering is incredibly useful for any situation where you’re combining pieces of multiple takes
together to create a single VO, audio vocal track, or dramatic performance, as you can choose which
pieces to prioritize via their superimposed position in the track, while you’re preserving the other takes
underneath in case you want them later.
```
TIP: Track Layering can be used on the Edit page as well.
```
Toolbar
The toolbar has buttons that let you choose modes of audio-specific functionality and other buttons
that let you execute commands, such as placing markers and flags.
Buttons in the Fairlight page toolbar
Mixer
The Audio Mixer provides a set of graphical controls
you can use to assign track channels to output
channels, adjust EQ and Dynamics, set levels and
record automation, pan stereo and surround audio, and
mute and solo tracks, all while you continue to edit.
The Audio Mixer exposes a set of channel strips with
controls that correspond to the tracks in the Timeline,
one for each track, plus a Master strip corresponding
to the Master audio track in the Timeline, that lets you
choose the number of audio channels to output, and
also lets you adjust the overall level of the mix.
Dedicated Channel Strip Controls
The Mixer also has a series of dedicated channel strip
controls that add powerful mastering capabilities to
DaVinci Resolve. These include:
 EQ
 Dynamic
 Pan
The Audio Mixer, with
channel strips corresponding
to the tracks in the Timeline
49DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
```
EQ: Double-clicking exposes a four-band parametric equalizer with additional Hi and Lo Pass
```
filters, that has both graphical and numeric controls for tuning the frequencies of the audio on
each track. You can select from among four types of EQ filtering from the Equalizer Type drop-
```
down menu, with options for Earth (the default), Air, Ice, and Fire. Each band has controls for the
```
```
filter type (Bell, Lo-Shelf, Hi-Shelf, Notch), Frequency, Gain, and Q-factor (sharpness of the band).
```
The channel strip EQ window
```
Dynamics: Double-clicking exposes a set of dynamics controls with compressor, limiter, and
```
expander or gate sections. The Equalizer button at the upper left-hand corner lets you turn all
EQ on and off. The first section can be switched between working as an Expander or a Gate,
with attendant Threshold/Range/Ratio and Attack/Hold/Release controls. The second section
provides Compressor controls, while the third section provides Limiter controls. These controls
may be used either singly or in concert to manage the dynamics of the audio on that track.
The channel strip Dynamics control window
50DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
```
Pan: A pan control compatible with stereo and surround panning. You can drag within this
```
control to adjust pan, or you can double-click to expose a Pan window. What controls are
available in the Pan window depend on the mapping of the audio track, but both stereo and
surround panning controls are available, with corresponding numeric controls.
The Pan control window
The Monitoring Panel
The Monitoring panel shows all of the audio meters corresponding to the tracks in the Timeline, as well
as the Master Output meter, Control Room meters, and a video viewer.
The Monitoring panel
At left, a row of audio meters corresponds to the channel strips of the Mixer, one meter for every audio
track in the Timeline. To the right of these, all buses appear, showing you meters for the Mains and
```
Subs (submixes) you’re using to mix down your show. Farther to the right of these, a set of Control
```
Room meters show you the monitored output and loudness meters for a precise analysis of your mix’s
perceived loudness.
Finally, a small viewer to the right of the Monitoring panel shows the frame of video at the position of
the playhead. This viewer can be undocked via a button at the lower right-hand corner.
51DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Floating Timecode Window
A timecode window is available from the Workspace menu on every page, including the Fairlight page.
Choosing this option displays a floating timecode window that shows the timecode of the Viewer
or Timeline that currently has focus. This window is resizable so you can make the timecode larger
or smaller.
A new floating timecode window is available
The Deliver Page
Once you’ve finished grading your project, you need to either render it, or output it to tape to deliver it
to your client. This is where the Deliver page comes in. The Deliver page can be used both to output
digital deliverables, or to output tape, depending on which mode you enable. Either way, the Deliver
page is divided into five areas of functionality, each of which lets you set up a different part of a render
or output to tape.
The Deliver page is set up to let you queue a series of individual jobs, each of which can have different
settings, or be set up to render different parts of the Timeline. In this way, you can output multiple
deliverables, or re-render multiple areas of a timeline, as your needs require.
The Deliver page
52DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
For more information about using the Deliver page, see Chapter 186, “Using the Deliver Page.”
The Render Settings List
The Render Settings list contains the customizable settings that affect how media is rendered out of
DaVinci Resolve.
These settings are covered in more detail later in “Output Scaling.” The Render Settings you can
choose from for outputting from DaVinci Resolve appear in three panels, separating the Video, Audio,
and File information-based settings in a logical fashion. By default, this list shows only the most
important criteria necessary for defining a render. However, additional controls can be exposed by
clicking the “Advanced settings” disclosure triangle at the bottom of each group of settings.
Render settings
The Deliver Page Timeline
The Timeline mirrors the Timeline seen in the Color page. You can use the Timeline in the Deliver
page to turn off tracks with clips you don’t want to include in the operation, define the range of clips
you want to render or output to tape, and to choose which versions for each clip you want to output.
You also have the option of switching the Deliver page Timeline to look like the Color page Timeline
instead, if that’s what you’re more comfortable with.
53DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Deliver page’s Thumbnail and Mini-Timeline match the Color page
The Deliver page Timeline also has the Timeline Filter drop-down at the right-hand side of the toolbar.
Using this drop-down to filter the contents of the Timeline lets you restrict the range of media you
want to output in different ways. For example, if you’ve already rendered a timeline, but you’ve since
made some changes, you can use the “Show Modified Clips” option to display only the clips that have
changed within a particular timeframe. Another possibility is to choose the “Show Unrendered Clips”
option to show all clips that have not yet been rendered.
The Viewer
When rendering file-based media, the Viewer shows you exactly how the media being output will
look using the current settings, and the transport controls move the playhead throughout the current
Timeline. Audio levels can be adjusted by right-clicking on the speaker icon,and dragging the slider.
When outputting to tape, the Viewer shows you the tape output so you can set up insert or assembly
edit points, and the transport controls move the tape in the deck if device control is enabled. You
can also put the Viewer into Cinema Viewer mode by choosing Workspace > Viewer Mode > Cinema
```
Viewer (Command-F), so that it fills the entire screen. This command toggles Cinema Viewer mode
```
on and off.
Deliver page Viewer
54DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
The Render Queue
The Render Queue is a list of all the jobs you’ve queued up for file-based rendering. Each job can
have an individualized range of clips and render settings, which you can use to render multiple
sections or clips of a timeline, the same timeline output to multiple formats, or multiple timelines.
The Render Queue also has the option to show either just the jobs within the current project, or jobs
queued up and saved within all projects for the current user.
The Render Queue displays all jobs
55DaVinci Resolve Interface | Chapter 1 Introduction to DaVinci Resolve
INTRO
Chapter 2
Using the
DaVinci Resolve
User Interface
This chapter provides an overview of the various unspoken conventions and
```
interaction methods employed by the DaVinci Resolve graphical user interface (GUI).
```
These include how the various buttons of your mouse, pen and tablet, or trackpad are used by different
windows and interface widgets, how commands are distributed throughout the application using the
menu bar, contextual menus, and option menus, and how to interact with fields and other controls.
While many of these conventions overlap with common user interface conventions found in the file system
of your platform of choice, and with other media applications, some of these are unique to DaVinci Resolve,
so this chapter is worth reviewing even if you consider yourself an expert user of other applications.
Contents
Basic Documentation Terminology  57
What Is the “UI” or “GUI”  57
What Is “the Pointer”  57
About Keyboard Shortcuts  57
Customizing the DaVinci Resolve Interface  57
Working Full Screen vs.
Within a Floating Window  57
Panels and Panel Focus 57
Showing and Hiding Panels
Using the Interface Toolbar  58
Showing and Hiding Panels in
the Workspace Submenu  59
Adjusting the Size of Different Panels  59
Using Single- vs. Dual-Monitor Layouts 61
Using the Full Screen
Timeline Option in the Edit Page  62
```
Video Clean Feed (Studio Version Only)  63
```
Saving Custom Screen Layouts  63
Resetting to the Default Layout  63
Undocking Specific Panels of the Interface 63
DaVinci Resolve User Interface Conventions 65
Contextual Menus 65
Drop-Down Menus  66
Adjusting Parameters  67
Using a Mouse or Other Input Device  68
Mouse, Trackpad, and Tablet Behaviors  69
Timeline Scroll Behavior  69
Viewer Behavior  70
Keyboard Shortcuts  71
Undo and Redo in DaVinci Resolve  72
56DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
Basic Documentation Terminology
Here is a brief word about some of the basic terminology used in this manual for brand new users.
What Is the “UI” or “GUI”
In this documentation, UI refers to “user interface,” while GUI refers to “graphical user interface.”
This refers to the windows, screens, and controls that let you create in DaVinci Resolve. If you didn’t
know this, don’t be embarrassed, you’d be surprised how many times this question gets asked.
What Is “the Pointer”
Whenever this documentation refers to “the pointer,” the reference is to the on-screen arrow you use
to click on elements of the user interface, which is controlled by the mouse, trackpad, pen and tablet,
trackball, or any other device you may be using. Because there are so many different ways to control
computers, simply referring to “the mouse” is inaccurate.
About Keyboard Shortcuts
This manual presents all keyboard shortcuts using the macOS conventions of the Command key
and the Option key. For compatibility with Windows and Linux, the Control key in macOS is not
```
used by default for any keyboard shortcuts (although it can be assigned if you customize your
```
```
keyboard shortcuts).
```
All keyboard shortcuts that use the Option key in macOS use the ALT key in Windows and Linux,
and all keyboard shortcuts that use the Command key in macOS use the Control key in Windows
and Linux.
Customizing the DaVinci Resolve Interface
While the DaVinci Resolve interface may not seem very customizable at first, there are actually many
ways in which you can tailor the panels found within each page to your specific needs.
Working Full Screen vs. Within a Floating Window
Depending on how you like to work, you can choose to work with DaVinci Resolve in a floating window
with a title bar that can be resized, moved, minimized, and used alongside other windows. Or, you can
choose Workspace > Full Screen to put DaVinci Resolve into Full Screen mode, where the title bar
disappears and DaVinci Resolve takes up the full dimensions of your computer display.
Editors may prefer to work within a window if they’re working among multiple applications.
Colorists and mixers may prefer Full Screen mode as it hides the light-colored title bar that some find
distracting and provides a tiny bit more screen real estate for the rest of the application.
Panels and Panel Focus
Each page of DaVinci Resolve consists of multiple panels. Each panel contains all the controls and
information necessary for a particular aspect of that page’s functionality. In the following partial
screenshot of the top of the Media page, the Media Storage panel lets you browse files, the Viewer is
a panel that lets you watch video, and the Audio panel lets you see the strength of audio playing back
via a set of audio meters. Each of these panels has separate controls, but they all appear within the
main window of the DaVinci Resolve user interface.
57DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
Three panels side by side on the Media Page, showing Media Storage, the Viewer, and the Audio panel
Each panel you use has “focus,” meaning that clicking an item or control within a particular panel
makes that panel the active panel, which serves to direct keyboard shortcuts that are shared among
many panels to the particular panel you’re using. If you want to see which panel is in focus, you can
turn on the “Show focus indicators in the User Interface” checkbox in the UI Settings panel of the User
Preferences. When on, a red line at the top of the active panel indicates that it has focus.
A red line at the top of the Media Pool in the Edit page shows that it has focus
Showing and Hiding Panels Using the Interface Toolbar
Each page in DaVinci Resolve has an Interface Toolbar that runs along the top. This toolbar contains
buttons that let you show and hide different panels of functionality to accomplish different things:
 You can show panels that aren’t displayed by default, since most pages have many available
panels of functionality that are hidden until you need them.
 You can assign keyboard shortcuts to show and hide individual panels in your workspace for
instant configuration of the UI. Keyboard shortcuts to toggle these panels on or off can be
assigned using the Keyboard Customization window.
 You can switch which panel appears within a particular geographical location of the UI, for
example switching between showing the Media Pool or Effects in the upper-lefthand corner of the
Cut or Edit pages.
 You can hide panels you don’t need in order to create more room in the specific panels
you’re working within.
58DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
The Interface toolbar for the Color page lets you customize the Color page controls
If you right-click anywhere within the UI toolbar, two options appear: “Show Icons and Labels” and
“Show Icons Only.” If you show icons only, the UI toolbar becomes less cluttered.
Each page has a different set of options that reflect the capabilities of that page.
The UI Toolbar for the Edit page, showing icons only, to save space
Showing and Hiding Panels in the Workspace Submenu
This function provides the ability to turn on or off panels by choosing them in the Workspace >
Show Panel in Workspace drop-down menu. The exact panels, such as Inspector, Media Pool,
Metadata, etc., are dependent on which page you are working in. Alternatively, you can assign these
panels keyboard shortcuts as well.
Adjusting the Size of Different Panels
You can resize adjacent panels in the interface by positioning the pointer at the border between any
two panels, and dragging it to enlarge one and shrink the other.
```
(Before/After) Resizing UI regions
```
Certain panels and palettes can be expanded, in the process rearranging another part of the UI, by
clicking a small gray Expand button. For example, an expand button at the top right of the Keyframe
Editor in the Color page can be clicked to make the Keyframe Editor wider, while at the same time
hiding controls at the center to make room.
```
(Before/After) Expanding the Keyframe Editor
```
59DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
Certain vertically oriented panels, such as the Media Pool, Effects Library, Metadata Editor, and
Inspector, can be set to either half-display-height or full-display-height sizes to quickly create more or
less room for contents or controls whenever necessary. This is done by clicking a small button in the
UI toolbar that toggles between expanding or contracting the UI element it controls.
The button for expanding
a panel to full height
The button for contracting
a panel to half height
The result is that the panel in question expands or contracts. The following screenshots show the
Inspector of the Edit page in half height mode, where the Timeline is given room to expand, and in full
height mode, where the Timeline becomes shorter, but there’s more room in the Inspector to see all of
the controls.
```
(Left) A half-height Inspector with more room for the Timeline,
```
```
(Right) A full-height Inspector with more room for controls
```
60DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
Using Single- vs. Dual-Monitor Layouts
The Media, Edit, Color, and Fairlight pages can be switched between single-screen and dual-screen
layouts by choosing Workspace > Dual Screen > On. Each dual-screen layout makes it possible to see
many more controls at once, often in a larger workspace that lets you manage more clips, more Gallery
stills, etc. The second screen of a dual-screen layout can be resized but not reorganized.
If you have an single ultra-wide monitor, you can also use the dual-monitor layout, and DaVinci Resolve
will scale the interface as if you had two normal monitors side by side.
The Edit page in Dual-screen mode
In Single-screen mode, you can choose which display shows the DaVinci Resolve UI by choosing
```
Workspace > Primary Display > (Monitor Name). In Dual-screen mode, this reverses the contents of
```
both monitors.
61DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
Using the Full Screen Timeline Option in the Edit Page
If you’re working in the Edit page in Dual-screen mode and you need the biggest timeline you can get
for working through your program, you can choose Workspace > Dual Screen > Full Screen Timeline
to expose a layout with one large full-screen timeline, and all the other Edit page panels on the
other screen.
The Edit page in Dual-screen Timeline mode
62DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
```
Video Clean Feed (Studio Version Only)
```
A full-screen Viewer for a secondary monitor connected directly to your computer is now available.
To activate this monitor select Workspace > Video Clean Feed, and select your display in the submenu.
Selecting a monitor for full-screen display
Saving Custom Screen Layouts
If you’ve created a particular set of resized panels that you’ll want to use often, you can save it,
alongside other frequently useful screen layouts you may have saved.
Methods of working with custom screen layouts:
 To save a custom screen preset: Customize the various pages of DaVinci Resolve for the purpose
at hand, then choose Workspace > Layout Presets > Save Layout As Preset. Enter a name into the
Save Layout as Preset dialog, and click OK.
 To choose a previously saved screen preset: Choose Workspace > Layout Presets > LAYOUT
NAME > Load. You can assign keyboard shortcuts for up to five different presets in the Keyboard
```
Customization window (Application > Workspace > Layout Presets).
```
 To update a previously saved screen preset: Choose the layout you want from the Workspace >
Layout submenu, make your changes, and then choose Workspace > Layout Presets > LAYOUT
NAME > Update Preset.
 To delete a screen preset: Choose Workspace > Layout Presets > LAYOUT NAME > Delete Preset.
 To export a screen preset for use on another DaVinci Resolve installation: Choose Workspace >
Layout Presets > LAYOUT NAME > Export Preset.
 To import a screen preset: Choose Workspace > Layout Presets > Import Layout as Preset.
Resetting to the Default Layout
If you don’t like the current layout and you want to go back to the default, choose Workspace >
Reset UI Layout.
Undocking Specific Panels of the Interface
There are certain interface elements that can either be docked in their respective pages, or opened in
separate windows.
Media Pool bins can be opened into floating windows simply by right-clicking on the bin and choosing
Open As a New Window in the contextual menu. Even though you’re opening up the contents of the
selected bin, you’re really creating another Media Pool, complete with Bin list, Browsing area, and all
of the organizational controls found in the docked Media Pool. You can have as many floating Media
Pools as you like. They can be dragged to other monitors, and they can be closed via a button at the
upper left-hand corner of the title bar.
63DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
A floating Media Pool window
The video scopes let you precisely analyze the color and contrast of clips in the Color page.
They can be exposed in their docked position to the right of the Color page palettes by clicking the
Video Scope button in the Color page toolbar.
The video scope, docked next to the other palettes at the bottom of the Color page
64DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
Optionally, you can click the expand button at the top right of the video scope to open the video
scopes into a floating window, within which you can display all four video scopes together, or
individually, on any monitor connected to your workstation.
Video scopes in a floating window
Additionally, the Audio Mixer and video scopes are available in many of the dual-screen layouts
available in DaVinci Resolve. The video scopes aren’t just available in the Color page. They’re also
available in the Media and Deliver pages for whenever you need to evaluate the video signal more
objectively, such as when you’re setting up to capture from tape or scan from film, or when you’re
setting up for output.
In the DaVinci Resolve single screen layout, the video scopes can be moved to a second computer
display, if one’s available, and will disappear temporarily if you change pages or switch to
another application.
DaVinci Resolve User
Interface Conventions
While each chapter covers the unique onscreen controls found in each page of DaVinci Resolve, this
section summarizes how to use some of the more common controls you’ll see.
Contextual Menus
Nearly every panel on every page exposes additional functionality via contextual menus, which
appear when you right-click on the appropriate item. Sometimes, different commands become
available depending on whether you right-click the background of a particular panel, or directly on an
item such as a still or node.
65DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
Contextual menus expose additional controls in the Color page Viewer
Drop-Down Menus
Most of the buttons and drop-down menus that appear in various toolbars are activated with a single
click. For example, many panels, palettes, and windows expose an Option menu, that appears as three
```
horizontal dots (people like to refer to these as the “three dot menus,” but they’re option menus), which
```
expose additional options and/or commands that are related to that particular panel’s function.
Option menus Mode drop-down
```
Additionally, many (but not all) panels and palettes appear with a “Mode” drop-down at the upper
```
right-hand corner that lets you choose a different type of function within that palette.
Some buttons, such as transport controls and toolbar icons, display a little downward facing arrow
when you hover the pointer over them, to indicate that you can right-click on these controls to access
checkmark options that govern the functionality of those controls.
```
(Left) Hovering over a button to reveal it has a hidden menu,
```
```
(Right) Right-clicking a button to reveal options in a drop-down menu
```
66DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
Adjusting Parameters
Numeric parameters can usually be edited in a few different ways.
Sliders and Dials
Sliders can be dragged to change the value
of a parameter within a specific range. If
you see a dial, that means a value can be
endlessly edited with no restrictions to the
value. Sliders are typically best for making
large coarse adjustments to parameters.
The “virtual sliders” described next let you
make finer adjustments.
A slider and a dial with their
accompanying number fields
Virtual Sliders and Fields
When number fields appear, they can be used
as a “virtual slider” by hovering the pointer over
them until you see the “virtual slider cursor” and
then clicking and dragging to the right to raise the
```
value, or to the left to lower the value (white arrows
```
```
indicate the direction of change). Typically, using
```
a field’s virtual slider lets you make more precise
adjustments than the actual slider to the left.
Using virtual sliders
Double-clicking fields containing most number
values highlights the number so that you can type
a new value using the keyboard, pressing Return to
confirm the change.
Editing of Number Field Values Using Arrow Keys
You can manually edit numerical parameter values by using the arrow keys to navigate and make
adjustments to the decimal level in number fields.
To use the arrow keys to adjust numerical parameters:
1 Double-click to select a numeric value in a field, and a highlight appears around that value.
2 Use the left/right arrows to navigate the cursor to the right of the decimal value you want to adjust.
3 Use the Up/Down arrows to change the value of that decimal place.
4 If you select the entire number, the Up/Down arrows will adjust the minimum value.
This cursor is in place to adjust the tenths
position using the Up and Down arrows.
Copy and Pasting of Number Field Values in Virtual Sliders
You can do standard copy/paste functions of any value in a field to any other field.
To copy and paste numerical parameters from a field:
```
1 Right-click on the source field and choose copy (Command-C) from the drop-down menu.
```
```
2 Right-click on the destination field and choose paste (Command-V) from the drop-down menu.
```
67DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
Icons and Buttons
Some controls are exposed as icons and
buttons, which you simply click to invoke
whatever functionality they encompass.
A pair of buttons with icons to
illustrate their functionality
Resetting Parameters
To reset any editable parameter to its default
setting, double-click its text label, or click the
reset button, if one appears. Master reset buttons,
typically found in the headers of groups of controls,
reset all controls in that group. Individual reset
controls that appear to the right of parameters
typically only reset that one parameter. If you don’t
see a reset control, then double-clicking the name
of the parameter should work.
Reset button
Using a Mouse or Other Input Device
Resolve uses all three buttons of a multi-button mouse, or the three buttons available on other type
of input devices, when available. This section provides a brief summary of all the different ways these
three mouse buttons can be used.
Left Button
The left button is always referred to as a click, as in, “click the auto select button.” You click to turn
buttons or other controls on or off, to make selections, and to give areas of the Resolve UI focus so
that keyboard shortcuts will do whatever is specific to that panel or area of the user interface.
Double-clicking the left button usually opens items that are openable, such as opening a clip from the
Media Pool into the Source Viewer. You can also use double-clicking to do things like selecting nodes
in the Node Editor of the Color page.
Right Button
The right button is referred to as a right-click, as in, “right-click a clip in the Media Pool.” Right-clicking
an item or area of the Resolve interface usually opens a contextual menu, exposing additional
commands that are specific to the item or area you’ve right-clicked.
However, some areas of the UI use right-clicking in special ways. For example, when you’re using a
color adjustment curve in the Curve palette of the Color page, right-clicking a control point deletes
that point.
Middle Button
```
The middle button (usually the scroll wheel button, but you may have to turn this on in the Mouse
```
```
panel of the System Preferences) is referred to as a middle-click, which does different things in
```
different places.
 In all pages, rolling the scroll wheel while the pointer is within a viewer lets you zoom into and out
of the image being displayed when you need to do more detailed work.
 In all pages and panels, pressing and holding middle-click and dragging inside a panel allows you
to scroll the view of the panel’s data in the direction that you drag.
68DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
 In the Color page, you can move the pointer over the Thumbnail timeline and roll up to scroll to the
right or roll down to scroll to the left. You can also roll the scroll wheel while the pointer is within
the Mini-timeline to zoom into or out of the currently displayed area. Rolling up zooms out, while
rolling down zooms in.
 Middle-clicking and dragging within a viewer lets you drag the image to pan it around, which is
```
useful after you’ve used the scroll wheel (or scroll behavior) of your mouse to zoom in.
```
 You can middle-click and drag within the Edit page Timeline to quickly pan around your edit.
 You can also use middle-click to copy a grade in the Thumbnail timeline of the Color page, by first
```
selecting the clip that you want to copy TO (with a simple click) and then middle-clicking the clip or
```
gallery still you want to copy a grade FROM.
 Lastly, if you’re drawing a Bezier window in the Color page Viewer using the Window palette, then
middle-clicking a control point will delete that point.
```
TIP: If you’re using a pointing device that lacks a third button option, check to see if there are
```
any third party utilities or drivers that can enable this for you.
Mouse, Trackpad, and Tablet Behaviors
Different input devices use different gestures to trigger specific behaviors in DaVinci Resolve.
Here is a current breakdown of these gestures and the behaviors that they control.
Timeline Scroll Behavior
Standard Mouse Mac Magic Mouse Trackpad Tablet and Pen
Scroll timeline
vertically
Scroll
Magic Mouse
1 Finger Pan
Vertical and
Horizontal
panning
2 Finger
Pan
Vertical and
Horizontal
panning
—
Scroll timeline
horizontally
Scroll
Magic Mouse
1 Finger Pan
Vertical and
Horizontal
panning
2 Finger
Pan
Vertical and
Horizontal
panning
—
Zoom timeline
width
horizontally
With ability to
zoom where
cursor points
Can be
enabled in User
Workspace
preferences
Scroll
— — —
69DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
Standard Mouse Mac Magic Mouse Trackpad Tablet and Pen
Zoom
timeline track
height vertically
Zooms Video and
Audio section
separately
Scroll
— — —
Drag Timeline
with Hand Tool
Middle
Mouse
Button
Left
Button
— —
Viewer Behavior
Standard Mouse Mac Magic Mouse Trackpad Tablet and Pen
Zoom towards
mouse pointer
Can change in
preferences Scroll
— Pinch to
Zoom
Press and
hold the
middle
pen button
Wwhile
moving it
left and
right on the
tablet.
2 Finger
Pan
Free Pan
Middle
Mouse
Button
Magic Mouse
1 Finger Pan
2 Finger
Pan
Press and
hold the
middle
pen button
Lift the pen
nib a few
millimeters
above the
pad, moving
the pen will
move the
frame in
the viewer.
70DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
Standard Mouse Mac Magic Mouse Trackpad Tablet and Pen
Pan with
Hand Cursor
Middle
Mouse
Button
Left
Button
— Press and
hold the
middle
pen button
Lift the pen
nib a few
millimeters
above the
pad, moving
the pen
will move
the hand in
the viewer.
Tilt Up and
Down
Scroll
— — —
Pan Left
and Right
Scroll
— — —
Context Menu
Right
Button
— 2 Finger
Touch
Right
button
on the pen.
Gestures used in DaVinci Resolve for common input devices
Keyboard Shortcuts
Since the majority of DaVinci Resolve users are on macOS, this manual presents all keyboard
shortcuts using the macOS conventions of the Command key and the Option key. For users of other
systems, all keyboard shortcuts that use the Option key in macOS use the ALT key in Windows
and Linux, and all keyboard shortcuts that use the Command key in macOS use the Control key in
Windows and Linux.
```
TIP: To keep controls identical between macOS, Windows, and Linux, the Control key in
```
macOS is not used by default for any keyboard shortcuts. However, you can assign your own
keyboard shortcuts to the Control key if you like, opening up a whole new set of keyboard
shortcuts for your own use on macOS.
71DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
Undo and Redo in DaVinci Resolve
No matter where you are in DaVinci Resolve, Undo and Redo commands let you back out of steps
you’ve taken or commands you’ve executed, and reapply them if you change your mind. DaVinci
Resolve is capable of undoing the entire history of things you’ve done since creating or opening a
particular project. When you close a project, its entire undo history is purged. The next time you begin
work on a project, its undo history starts anew.
Because DaVinci Resolve integrates so much functionality in one application, there are three separate
sets of undo “stacks” to help you manage your work.
 The Media, Edit and Fairlight pages share the same multiple-undo stack, which lets you backtrack
out of changes made in the Media Pool, the Timeline, the Metadata Editor, and the Viewers.
 Each clip in the Fusion page has its own undo stack, so that you can undo changes you make to
the composition of each clip, independently.
 Each clip in the Color page has its own undo stack, so that you can undo changes you make to
grades in each clip, independently.
```
In all cases, there is no practical limit to the number of steps that are undoable (although there may be
```
```
a limit to what you can remember). To take advantage of this, there are three ways you can undo work
```
to go to a previous state of your project, no matter what page you’re in.
To simply undo or redo changes you’ve made one at a time:
```
 Choose Edit > Undo (Command-Z) to undo the previous change.
```
```
 Choose Edit > Redo (Shift-Command-Z) to redo to the next change.
```
You can also undo several steps at a time using the History submenu and window. At the time of this
writing, this only works for multiple undo steps in the Media, Cut, Edit, and Fairlight pages.
To undo and redo using the History submenu:
```
1 Open the Edit > History submenu, which shows (up to) the last twenty things you’ve done.
```
2 Choose an item on the list to undo back to that point. The most recent thing you’ve done appears
at the top of this list, and the change you’ve just made appears with a check next to it. Steps
that have been undone but that can still be redone remain in this menu, so you can see what’s
possible. However, if you’ve undone several changes at once and then you make a new change,
you cannot undo any more and those steps disappear from the menu.
Once you’ve selected a step to undo to, the menu closes and the project updates to show you its
current state.
The History submenu, which lets you undo several steps at once
72DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
To undo and redo using the Undo window:
1 Choose Edit > History > Open History Window.
When the History dialog appears, click an item on the list to undo back to that point. Unlike
the menu, in this window the most recent thing you’ve done appears at the bottom of this list.
Selecting a change here grays out changes that can still be redone, as the project updates to
show you its current state.
2 When you’re done, close the History window.
The Undo History window that lets you
browse the entire available undo stack
of the current page
73DaVinci Resolve Interface | Chapter 2 Using the DaVinci Resolve User Interface
INTRO
MEDIA
Setup and
Workflows
CONTENTS
3 Managing Projects and Project Libraries  75
4 System and User Preferences  96
5 DaVinci Control Panels Setup  130
6 Project Settings  137
7 Camera Raw Settings  165
8 Improving Performance, Proxies, and the Render Cache  191
9 Data Levels, Color Management, and ACES  219
10 HDR Setup and Grading  253
11 Image Sizing and Resolution Independence 282
12 Data Burn-In 297
13 Frame.io and Dropbox Replay Integration  303
14 Resolve Live 312
15 Stereoscopic Workflows  320
16 Using Variables and Keywords  343
Chapter 3
Managing Projects
and Project Libraries
This chapter covers how to use the Project Manager to organize the projects
you’re working on in DaVinci Resolve, as well as how to deal with managing the
project libraries that serve as the organizational foundation of the Project Manager.
You’ll also see how to export and import projects, and how to archive a project and
its media for long-term storage.
Contents
Using the Project Manager  76
Creating a New Project  77
Project Management  77
```
Importing and Exporting DaVinci Resolve Projects (.drp Files)  78
```
Project Manager View Options  79
Searching for Projects  81
Organizing Projects in Folders  81
Managing Project Libraries  82
Project Library Types  82
Opening the Project Libraries Sidebar  83
Moving Projects From One Project Library to Another on the Same Workstation  83
Managing Project Libraries in the Project Libraries Sidebar  84
Quick Access to Recent Projects from the File Menu  88
Saving Projects  89
Live Save  89
Project Backups  90
Project Notes  93
Dynamic Project Switching  93
Archiving and Restoring Projects  94
75Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
Using the Project Manager
Ordinarily, the Project Manager is the first window you’ll see when DaVinci Resolve starts up. It’s a
convenient, centralized browser for creating, organizing, and managing all of your projects. Unlike
other applications that rely on your file manager for organizing projects, DaVinci Resolve requires you
to do most project organization in the Project Manager.
Project Manager
If you’ve already opened a project, you can reopen the Project Manager at any time by clicking the
Home button at the bottom right-hand corner of the DaVinci Resolve window, in the Page Navigation
bar. If you’ve hidden the Page Navigation bar at the bottom of the DaVinci Resolve window, you can
open the Project Manager by choosing File > Project Manager.
The Project Manager button at
the bottom-right corner of the
DaVinci Resolve interface
76Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
Launching DaVinci Resolve for the First Time?
If you’ve just installed DaVinci Resolve and have opened it for the first time, it’s time to
set the preferences in order to specify your language, scratch disk volume, and hardware
```
configuration for video and audio I/O and control panels (if you have one).
```
For more information about setting the preferences in DaVinci Resolve, see Chapter 4,
“System and User Preferences.”
Creating a New Project
The first step into DaVinci Resolve is to create a new Project in the Project Manager, which is
conveniently the first thing that opens when you launch the program. Each project contains links to
all of the media, graphics, and sound files used in your film, as well as timelines where all the editing,
color correction, motion graphics, and audio post work is done.
```
There are several settings, options, and preferences attached to each project (you can access them by
```
```
clicking on the small gear icon in the very bottom right of the interface), and all of them are described
```
in detail later in this section. However, actually creating a project requires only four steps.
Creating a New Project:
1 Click on the New Project button at the bottom of the Project Manager.
2 Type in a name for your project.
3 Observe the folder where any media created by DaVinci Resolve will be stored in Media Location.
Make sure you have some space on this drive. Clicking on the Change Location button lets you
select another drive/folder instead of the default.
4 Click the Create button.
The Create New Project dialog
Project Management
The Project Manager provides an in-application interface for creating, renaming, and deleting projects.
Many of these commands exist within the contextual menu that appears when you right-click the
background of the Project Manager.
Methods of project management:
 To create a new project: Double-click the Default Project icon, or click the New Project button
at the bottom of the window. A new project is created, and DaVinci Resolve opens up the Media
page. Once a project is open, you can alter its project settings by clicking the gear icon.
 To open a previously saved project: Double-click any Project icon, or Item if you’re in List view.
You can also select a project and click the Open button.
77Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
 To open a project in Read-Only Mode: Right-click a Project icon or Item, and choose Open in
Read Only Mode. This lets you open a project without danger of altering it. If you make changes,
you can use the Save As command to save a new copy of the project with a new name.
 To rename a project: Right-click a Project icon or Item, choose Rename, and type a new name in
the dialog that appears, clicking OK when you’re finished.
 To load project settings from another project to the currently open project: Right-click a
```
Project icon or Item (other than the currently open project), and choose “Load Project Settings to
```
Current Project.” This lets you change a project’s settings prior to opening it in cases where the
project settings are causing some kind of problem that prevents you from opening the project.
 To update the thumbnails of a project in the Project Manager: Right-click any project, and
choose “Update Thumbnails.”
 To delete a project: Select one or more projects, then either press the Backspace key, or
right-click one of the selected projects and choose Delete. Click OK when a dialog asks you to
confirm the operation.
```
NOTE: You cannot move or delete the currently open or loaded project.
```
```
Importing and Exporting DaVinci Resolve Projects (.drp Files)
```
DaVinci Resolve projects are saved with the file extension .drp and enable you to exchange files
with other DaVinci Resolve users. If you double-click a DaVinci Resolve .drp file in the Windows or
macOS file system, this will automatically open DaVinci Resolve, import that project into the Project
Manager regardless of what kind of project library you’re using, and open that project so that you’re
ready to work.
Importing and Exporting Projects in Local Project Libraries
If you’re using local project libraries to manage your projects, you can copy and import
projects using the project folders in the file manager of either macOS or Windows. This
method does not work for DaVinci Resolve on Linux.
Moving projects from one local project library into another using macOS or Windows:
1 Locate the local project library directory in which the project you want to copy is stored. If you
don’t know where the designated local project library directory is, you can open DaVinci Resolve
and check the directory path for the current local project library in the Project Libraries sidebar.
2 Copy the project folder from the source workstation to the designated local project library
directory on the destination workstation. If you don’t know where the designated local project
library directory is, you can open DaVinci Resolve on the workstation you’re copying the project to
and check the directory path for the current local project library in the Project Libraries sidebar.
3 Once you’ve copied the project folder into the correct location, you’ll need to quit and reopen
DaVinci Resolve. Afterwards, the imported project should appear in the Project Manager.
Importing and Exporting Projects in Network Project Libraries
If you’re using a network project library, another set of commands let you import and export
projects using the .drp file format. You can also export .drp files from local project libraries if
you want to export a more self-contained item to transport.
78Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
To import a .drp project file, do one of the following:
 Select the Import button at the bottom of the Project Manager, then find and select a .drp project
file using the Import Project File dialog, and click Open.
 Drag the .drp file you want to import from your file system and drop it anywhere into the
Project Manager window.
 Right-click any empty area of the Project Manager and choose Import, then find and select a .drp
project file using the Import Project File dialog, and click Open.
To import a .drp project file and reconfigure the gallery path at the same time:
 Hold the Option key down while right-clicking any empty area of the Project Manager, and choose
Import+, then find and select a .drp project file, and click Open. Upon opening, the gallery path will
automatically be updated to that of your workstation.
To export the currently open project as a .drp file:
 Choose File > Export Project, and when the Save dialog appears, choose a location, enter
a name, and click Save. The result is a self-contained file with a .drp file suffix saved at the
location you chose.
To export a .drp project file from the Project Manager:
 Select the Export button at the bottom of the Project Manager, and when the Save dialog appears,
choose a location, enter a name, and click Save. The result is a self-contained file with a .drp file
suffix saved at the location you chose.
 Right-click a Project icon or Item in the Project Manager, then choose one of the
```
following commands;
```
 Export Project: Exports project data with no LUTs and no stills. Best when you need to export
the smallest possible file.
 Export Project With Stills and LUTs: Exports the project, including both still frames in the
Gallery and LUTs used in grades. Best when you want to export the most self-contained file and
you can’t guarantee the recipient will have the same LUTs you do.
 When the Save dialog appears, choose a location, enter a name, and click Save. The result is a
self-contained file with a .drp file suffix saved at the location you chose.
```
TIP: You can export multiple projects from the Project Manager at the same time by either
```
command-clicking or lassoing the projects, right-clicking on one of them, and selecting
Export Projects from the drop-down menu. All projects will be saved in the same location.
Project Manager View Options
Four buttons at the top right let you control how projects are viewed in the Project Manager.
Select Thumbnail or List View
```
 Zoom slider: (Only appears in Thumbnail view) Lets you adjust the size of the thumbnails in
```
Thumbnail view.
```
 Project Sort Order drop-down: (Only appears in Thumbnail view) Lets you choose the sort order
```
of projects in Thumbnail view.
79Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
```
 Information: (Only appears in Thumbnail view) Lets you show or hide additional project
```
information displayed underneath each project’s thumbnail, including the frame size, number of
timelines within, and when that project was last modified.
 Thumbnail view: Each project is represented by a large image that can be hover-scrubbed to
reveal five representative images from that project.
```
Hover-scrub over Project icon;
```
information is enabled
 List view: Every project appears as an item in a list that has seven columns: Name, Last Modified,
Timelines, Format, Frame Rate, Date Created, and Note. You can click any column header to sort
```
the contents of the Project Manager by that criteria; clicking the header a second time toggles that
```
column between ascending and descending sorting.
Project List view
80Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
Searching for Projects
Clicking the magnifying glass button at the upper right-hand corner of the Project Manager exposes
the Search Options, which can be used to locate one or more projects based on the metadata that’s
selected in the Filter By drop-down menu to the right of it.
Search field open with Filter by search criteria selected
Using the drop-down menu, you can choose to search by name, or by project format. Once you’ve
chosen a criteria, begin typing into the search field, and the Project Manager will immediately and
dynamically begin to be filtered by your search text.
Organizing Projects in Folders
If you’re organizing a lot of projects, you can create folders to put them into.
A folder in the Project Manager
Methods of working with project folders:
 To create a folder: Click the New Folder button, then enter a name into the Create New Folder
dialog and click Create.
 To delete a folder: Right-click a folder, choose Delete, and click Yes when prompted. All projects
inside a deleted folder will be deleted as well.
 To rename a folder: Right-click a folder, choose Rename, then enter a new name and click OK.
 To copy a folder: Right-click on a folder and choose Copy from the drop-down menu, or select the
folder and press Command-C. Any projects enclosed inside that folder will also be copied.
 To paste a folder: Once a copy operation has been made, right-click on the background of the
Project Manager and choose Paste from the drop-down menu, or press Command-V. You can
paste into other project libraries, into other folders, or into the same location where a new version
```
of the folder will have the word (Copy) appended to it. All enclosed timelines will copy over as well.
```
 To open a folder: Double-click a folder to open it and view its contents. At the upper left-hand
corner of the Project Manager, a folder path view shows you which folder is open, as well as where
you are within a nested series of folders if that’s what you’ve set up.
 To exit a folder: Use the path control at the top of the Project Manager to click on a higher level
in the folder hierarchy.
 To move a project into a folder: Drag the project onto a folder icon, and drop it to place it
inside the folder.
 To move a project out of a folder: Open a folder, select one or more projects you want to move,
then right-click the selection and choose Cut from the contextual menu. Then, navigate to the next
place in the Project manager where you want to place the cut projects, right-click the background
of the Project Manager, and choose Paste. The projects should appear in the new location.
81Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
Managing Project Libraries
Unlike other applications which save self-contained project files to user-specified locations
wherever you like in your file system, DaVinci Resolve takes a more centrally organized approach to
project management, using project libraries. By default, DaVinci Resolve uses a local project library
to keep track of every project you create. The Project Libraries sidebar lets you manage the projects
```
found within this project library, which are saved to a specific directory on your system (particular
```
```
to that project library). The default location of this local project library depends on the operating
```
system you use.
However, you can create additional project libraries with which to store other projects, if you like.
For example, you might create one project library each for each year in which you work. If you
work on series television, you could create multiple project libraries for each program you work
on. Or, you could create separate project libraries for each client you do work for. There’s no hard
```
and fast rule; ultimately how you use project libraries is entirely up to you and your individual
```
organizational preferences.
Project Library Types
Project libraries can be stored in three different project library types which work similarly in function
but have additional connectivity and sharing features based on your networking setup. You select the
Library Type at the top left of the Project Manager.
 Local: Stores your project libraries locally on your workstation. This is the default and is best for
individual users or single systems.
 Network: Stores your project libraries on an external computer that is connected to several
workstations on the same local network. It also allows you to control user access to the project
library. This is best for a facility composed of multiple workstations in the same building working
on the same material.
 Cloud: Stores your project libraries in the Blackmagic Cloud. This allows several workstations
to connect to the same project library over the internet. It also allows you to control user access
to the project library. This is best for multiple people working on the same project from different
locations around the world.
The three types of project libraries: local, network, and cloud.
For more information about setting up and configuring the different project library types,
see Chapter 196, “Managing Project Libraries and Project Servers.”
82Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
Opening the Project Libraries Sidebar
If you already have multiple project libraries, then clicking the button at the upper-left hand corner of
the Projects Browser reveals a sidebar at the left of the Project Manager that lists every project library
on your workstation, with various options for managing these project libraries and for browsing the
projects found within them.
You can use this sidebar to open different project libraries and browse the projects
found inside.
Project Libraries
sidebar button
Project Manager with the Project Libraries sidebar displayed
Moving Projects From One Project Library
to Another on the Same Workstation
If you’ve used multiple project libraries to organize your projects, you can browse the contents of each
project library to search for what you’re looking for, and then copy one or more projects from one
project library to another if you need to rearrange how they’re organized.
83Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
To view the contents of a project library:
1 Click the button at the upper-left hand corner of the Projects window to open the Project
Libraries sidebar.
2 Click to select a project library in the sidebar, and an orange highlight will appear
If you had a project already open, you’ll be asked if you want to save it before closing, because
all open projects must be closed prior to viewing the contents of another project library. Then,
the projects corresponding to that user within the selected project library appear in the Project
Manager window.
To import a project from another project library using the Project Libraries sidebar:
1 Click the button at the upper-left hand corner of the Projects window to open the Project
Libraries sidebar.
2 Click to select a project library in the sidebar, and if necessary use the drop-down menu at the
right of the project library listing to choose a specific user. The projects corresponding to that user
within the selected project library appear in the Project Manager window.
3 Select a project you want to import, and press Command-C to copy it.
```
4 Click to select the current project library again (the project library you want to work within).
```
5 Press Command-V to paste the project you copied. A copy appears in the current project library.
For more details on shared project library setup and operation, see Chapter 196, “Managing
Project Libraries and Project Servers.”
To import Project Settings from another project using the Project Libraries sidebar:
1 Click the button at the upper-left hand corner of the Projects window to open the Project
Libraries sidebar.
2 Select a project you want to import Project Settings to so that it’s highlighted.
3 Right-click any project and choose “Load Project Settings to Current Project.” That project’s
settings will be copied to the project you selected in step 2.
Managing Project Libraries in the Project Libraries Sidebar
```
Controls within the Project Libraries sidebar make it easy to create new project libraries (via the button
```
```
at the bottom), upgrade project libraries that have been flagged (via circular badges), import and
```
```
export project libraries (via buttons at the top), and reveal additional information about each project
```
```
library (via buttons at the top of this sidebar).
```
Project Libraries sidebar controls
The three controls at the top of the Project Libraries sidebar have the following functions:
 Sort Order drop-down menu: This menu lets you choose how to sort the various local and
network project libraries displayed in the sidebar. You can sort by Project Library Name, Schema
```
(by date), Status, or Location in Ascending or Descending order.
```
84Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
 Restore: Imports .resolve.backup files to restore a backed up project library.
 Show Search Field: Displays a search field and search criteria drop-down that lets you search for
project libraries in the sidebar by Name, Schema, Status, or Location.
```
Clicking on the Display Project Library Details icon (the circled letter “i” to the right of the project
```
```
library), shows additional information underneath each project library in the sidebar. What
```
information depends on the type of project library. Local project libraries display their status
```
(compatible/incompatible) and location (directory path). Network and cloud project libraries display
```
```
their schema (created and modified dates), their status (compatible/incompatible), their IP location,
```
and below any members that have access to the project library.
Creating and Connecting to Project Libraries
You can use local, network, and cloud libraries side by side for switching to the use of one or the
other, depending on your needs. These instructions will show you how to set up local project libraries.
Network and cloud libraries require additional configuration and setup first.
For more details on network and cloud project libraries setup and operation, see Chapter 196,
“Managing Project Libraries and Project Servers.”
To create a new local project library:
1 Click the button at the upper-left hand corner of the Projects window to open the Project
Libraries sidebar.
2 Click the Add Project Library button at the bottom of the sidebar.
3 Click on the Create tab. The Add Project Library window should look like the following screenshot:
Creating a local project library
4 In the remaining fields, do the following:
```
a) Type a name for the new project library into the Name field
```
```
b) Click within the Location field and use the Filesystem navigation dialog to choose where to
```
put the directory that will contain all of the DaVinci Resolve project directories
5 Click Create, and the new local project library will appear in the local project library section of the
Project Libraries sidebar.
85Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
To connect to an existing local project library:
1 Click the button at the upper-left hand corner of the Projects window to open the Project
Libraries sidebar.
2 Click the Add Project Library button at the bottom of the sidebar.
3 Click on the Connect tab. The Add Project Library window should look like the following screenshot:
Connecting to an existing local project library
4 In the remaining fields, do the following:
```
a) Type a name for the new project library into the Name field.
```
```
b) Click within the Location field and use the Filesystem navigation dialog to choose the location
```
of the existing project library you wish to connect to.
5 Click Connect, and the new local project library will appear in the local project library section of
the Project Libraries sidebar.
Duplicating Project Libraries
Local Project Libraries can be duplicated in the same database for backup or iteration purposes.
1 Right-click on the Library, and select Duplicate from the drop-down menu.
2 Select the Resolve Database folder in the file system browser. This can either be the same one
you use for the original project or a new one.
3 Click on the Open button.
4 Rename the new Library in the Clone Library dialog.
Backing Up and Restoring Project Libraries
You can also back up project libraries by exporting them, and then reimport them later.
To backup/export a project library:
1 Click the button at the upper-left hand corner of the Projects window to open the Project
Libraries sidebar.
2 Select the project library you want to back up.
```
3 Click the Display Project Library Details icon (the circled letter “i” to the right of the project library).
```
The Display Project Library Details icon
86Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
4 Select the Back Up button.
5 Choose a location to which to save the backup in the Backup Project Libraries dialog, and
click Save.
To import a project library:
1 Click the button at the upper-left hand corner of the Projects window to open the Project
Libraries sidebar.
2 Click the Restore button at the top of the Project Libraries sidebar.
The Restore button
3 Find the project library you need to import using the file import dialog, and click Open.
4 In the Add Project Library dialog, do the following:
```
a) Type a name for the new project library into the Name field. This will rename the imported
```
project library but will not alter its contents. You can also name it the same as the original
project library.
```
b) Click within the Location field and use the Filesystem navigation dialog to choose the
```
directory that contains the existing DaVinci Resolve project libraries.
5 Click Create, and the imported local project library will appear in the Local section of the Project
Libraries sidebar.
Upgrading Project Libraries
Selected libraries display an upgrade warning in the Project Manager only when you’ve installed a
new version of DaVinci Resolve and you have project libraries that were created in older versions of
DaVinci Resolve that need upgrading.
The upgrade warning in the Project Manager indicates
that the project library needs to be upgraded
It’s generally a good idea to back up a project library prior to upgrading it, in case something
goes wrong. In general, upgrading from a whole version release to the next whole version release
of DaVinci Resolve usually requires an upgrade, while upgrading to a dot release of the same
version may or may not. If the currently used project library requires an update, you’ll be told on
application startup.
87Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
To upgrade a project library from an old version of DaVinci Resolve:
Click on a project library that needs updating, and select the Upgrade Project Library button. A dialog
appears to confirm if you really want to upgrade that project library. Click Upgrade to proceed.
Disconnecting and Deleting Project Libraries
```
You cannot actually delete project libraries in DaVinci Resolve; you can only disconnect them so
```
they don’t appear in the Project Library list. However, disconnected project libraries can still be
reconnected if you remember their name. The only way to completely delete a project library entry in
PostgreSQL is to do so from the command line, or to use the PGAdmin III application that accompanies
the PostgreSQL installation that’s part of the DaVinci Resolve installation process.
To disconnect a project library you no longer need:
 Right-click a project library that is not currently selected, and choose Remove from the
contextual menu. A dialog appears to confirm if you really want to disconnect that project library.
Click Disconnect to proceed.
Locating Local Project Library Directories in Your File System
Because local project libraries have a link to a specific directory in your file system, there’s a way of
locating that directory.
To locate a project library on your system:
 Right-click any local project library, and choose “Reveal in Finder.” A file system window opens up
showing you the location of that local project library, inside which are all of its projects.
Quick Access to Recent
Projects from the File Menu
You can open recent projects directly from the File > Open Recent Project menu, rather than having to
go to the Project Manager and find it manually.
Opening a recent project from the File menu
88Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
Saving Projects
Once you’ve created and opened a project, you want to make sure that you regularly save your work.
 Methods of saving projects:
```
 Choose File > Save Project (Command-S).
```
 To save the current state of your project as a copy with a new name, choose File > Save Project As
```
(Command-Shift-S), then enter a name into the Save Current Project window and click Save.
```
To revert to the last saved state of a project:
 To save the current state of your project as a copy with a new name, choose File > Save Project As
```
(Command-Shift-S), then enter a name into the Save Current Project window and click Save. If you
```
chose to save as the same name as an existing project, a dialog box will appear allowing you to
confirm if you want to overwrite the existing project or to cancel out and choose another name.
As you work on your project, the word “Edited” appears to the right of the project name at
the top of the DaVinci Resolve UI to let you know that you have unsaved changes. If you
don’t save in over 15 minutes, the word “Edited” turns yellow, and if you still don’t save in over
30 minutes, it turns red to let you know that you probably should save. If you move the pointer
over the word “Edited,” a tooltip appears letting you know when the last save was performed.
The word “Edited” to the right of the project name
lets you know you have unsaved changes
DaVinci Resolve also has two auto save mechanisms that you can enable in the Save Settings
group of controls, called Live Save and Project Backups.
Auto Save controls in the User Preferences
Live Save
Enabling Live Save sets DaVinci Resolve to incrementally save changes as you make changes to your
project, with no user intervention required. Disabling Live Save puts DaVinci Resolve back into a state
```
where you have to manually save by pressing Command-S (this can be useful when doing demos
```
89Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
```
when you don’t want to save your changes to a project). Using Live Save is turned on by default and
```
highly recommended to prevent the loss of work in the event you have a problem. It even works for
previously unsaved projects that you’ve forgotten to save if anything goes wrong.
```
NOTE: When you use Collaborative Workflow to enable multiple artists to work together in
```
the same project, Live Save is automatically turned on and cannot be disabled.
Project Backups
Turning on the Project Backups checkbox in the Project Save and Load panel of the User Preferences
enables DaVinci Resolve to save multiple backup project files at periodic intervals, using a method
```
that’s analogous to a GFS (grandfather father son) backup scheme. This can be done regardless of
```
whether or not Live Save is turned on. Each project backup that’s saved is a complete project file,
excluding stills and LUTs, which are omitted in order to save storage space.
Once you’ve enabled Project Backups for a long enough time, whatever saved project backups have
been created are retrievable in the Project Manager via the contextual menu that appears when you
right-click a project, by choosing Project Backups to open the backups list dialog.
The backups list dialog shows you all backups that are available for a particular project, and has
controls for sorting the list via different columns, deleting some or all of the backups in the list, and
loading backups that you want to retrieve. Opening a project backup does not overwrite the original
```
project; project backups are always opened as independent projects.
```
To enable Project Backups:
1 Choose DaVinci Resolve > Preferences > User, and open the Project Save and Load panel.
2 Turn on the Project Backups checkbox.
3 Choose the settings that determine how many Project Backups will be maintained. Project Backups
are saved on a first in, first out basis. Three fields let you specify how often to save new backups and
how many backups to maintain, while the fourth lets you choose where the backups will be saved.
Perform backups every X minutes: The first field specifies how often to save a new backup within
the last hour you’ve worked. By default, a new backup is saved every 10 minutes, resulting in six
backups within the last hour. Once an hour of working has passed, an hourly backup is saved and
the per-minute backups begin to be discarded on a “first in, first out” basis.” By default, this means
that you’ll only ever have six backups at a time that represent the last hour’s worth of work.
Hourly backups for the past X hours: The second field specifies how many hourly backups
you want to save. By default, 8 hourly backups will be saved for the current day you’re working,
```
which assumes you’re working an eight hour day (wouldn’t that be nice). Past that number, hourly
```
backups will begin to be discarded on a “first in, first out” basis.
Daily backups for the past X days: The third field specifies for how many days you want to save
backups. The very last project backup saved on any given day is preserved as the daily backup
```
for that day, and by default daily backups are only saved for five days (these are not necessarily
```
```
consecutive if you take some days off from editing for part of the week). Past that number, daily
```
backups will begin to be discarded on a “first in, first out” basis. If you’re working on a project over
a longer stretch of time, you can always raise this number.
Project backup location: Click the Browse button to choose a location for these project backups
to be saved. By default they’re saved to a “ProjectBackup” directory on your scratch disk, although
you could change this to a volume that better fits into your data backup methodology.
4 Click Save to confirm your change, and then close the Preferences window.
90Setup and Workflows | Chapter 3 Managing Projects and Project Libraries
MEDIA
```
NOTE: When using this feature, the very first backup that’s saved for a given day may be
```
a bit slow, but all subsequent backups should be unnoticeable.
Once one or more Project Backups have been saved, you can access them in the Project Browser.
To open a Project Backup that’s been saved:
1 Open the Project Manager.
2 Right-click a project, and choose Project Backups from the contextual menu.
3 Select a backup that you want to restore from the Auto Backups list. If you don’t see the particular
backup you want, you can click the Refresh button to update the list, or you can try sorting by one
```
of the columns (Auto Backup, Date Modified, Width, Height) to better navigate the list.
```
4 Once you’ve selected the backup you want to restore, you can click Load to open that backup as
a new project. If the project it was saved from is already open, it won’t be overwritten.
Restoring a project backup
in the Project Browser
Selecting a backup
that you want to restore
Timeline Backups
Turning on the Timeline Backups checkbox in the Project Save and Load panel of the User
Preferences enables DaVinci Resolve to save multiple backups of a timeline at periodic intervals,
```
using a method that’s analogous to a GFS (grandfather-father-son) backup scheme. This can be done
```
regardless of whether or not Live Save is turned on.
If you want to revert to a previous backup of a timeline, simply right-click on the timeline in the Media
Pool, select Restore Timeline Backup from the contextual menu, and choose the backup from the list
of options. Backups are organized by date and time, making it easy to find the specific timeline you
want to restore.
91Setup and Workflows | Timeline Backups Managing Projects and Project Libraries
MEDIA
Restoring a timeline backup does not overwrite your current timeline. Instead the selected backup will
be brought into the Media Pool as a new timeline, with the name “Backup” appended to it.
Restoring a timeline backup in the Media Pool
Timeline backups are only saved when changes have been made to a project. If DaVinci Resolve
sits idle for any period of time, such as when your smart watch tells you to go outside and walk
around the block, no additional project backups are saved, preventing DaVinci Resolve from
overwriting useful backups with unnecessary ones.
Three fields let you specify how often to save a new backup, while the fourth lets you choose
where the backups will be saved. These settings apply to both Project and Timeline backups.
 Perform backups every X minutes: The first field specifies how often to save a new backup within
the last hour you’ve worked. By default, a new backup is saved every 10 minutes, resulting in six
backups within the last hour. Once an hour of working has passed, an hourly backup is saved and
the per-minute backups begin to be discarded on a first in, first out basis. By default, this means
that you’ll only ever have six backups at a time that represent the last hour’s worth of work.
 Hourly backups for the past X hours: The second field specifies how many hourly project
backups you want to save. By default, two hourly backups will be saved for the current day. Past
that number, hourly backups will begin to be discarded on a first in, first out basis.
 Daily backups for the past X days: The third field specifies for how many days you want to save
backups. The very last backup saved on any given day is preserved as the daily backup for that
day, and by default daily backups are only saved for two days. Past that number, daily backups
will begin to be discarded on a first in, first out basis. If you’re working on a project over a longer
stretch of time, you can always raise this number.
 Project backup location: Click the Browse button to choose a location for these backups to be
saved. By default they’re saved to a “ProjectBackup” directory on your scratch disk, although
you could change this to a volume that better fits into your data backup methodology. This folder
contains both Project and Timeline backups.
92Setup and Workflows | Timeline Backups Managing Projects and Project Libraries
MEDIA
Restoring Deleted Timeline Backups
From the Media Pool Options menu, you can select Deleted Timeline Backups and examine deleted
timelines and available backup files for each timeline. You can select backups to be restored or
choose to permanently delete selected backups.
Project Notes
Each DaVinci Resolve project now provides access to Project Notes, which is a simple “scratch pad”
for keeping track of text notes associated with each project. These notes can be accessed using the
File > Project Notes command, and there’s also a Project Notes command in the contextual menu
for project icons in the Project Manager, which makes these notes accessible to everyone who’s
connected to that project library.
Dynamic Project Switching
Dynamic Project Switching is an option in the Project Manager contextual menu that lets you open
multiple projects into RAM simultaneously, so you can quickly switch between projects when you
want to copy and paste clips, timelines, and node settings back and forth. If you plan on opening
many projects, or even just a few very large projects, you should be sure your workstation has an
appropriate amount of RAM installed or you could experience a slowdown in performance.
Switching among open projects using the Project
Title drop-down at the top of the DaVinci Resolve UI
Methods of using Dynamic Project Switching:
 To enable Dynamic Project Switching: Open the Project Manager, right-click anywhere within
the Project Manager and choose Dynamic Project Switching so that it’s checked. Dynamic Project
Switching will remain enabled until you turn it off.
 To open multiple projects in RAM: Open any project, then reopen the Project Manager and open
any other project. All projects you open are kept available in RAM.
 To switch among open projects: Choose File > Switch Project and select the project you want to
switch to from the submenu. You can also choose other projects that have been opened into RAM
from the drop-down menu that appears to the right of the project name at the top center of the
DaVinci Resolve user interface.
 To close a specific project: Choose File > Close Project and select the project you want to close
from the submenu. You may be prompted to save, after which the project closes.
 To close all other open projects: Open the Project Manager. All open projects appear with a
```
check mark in the upper right-hand corner; the currently open project has an orange corner
```
mark, while other projects open in memory have a gray corner mark. Right-click anywhere within
the Project Manager, and choose Close Projects in Memory to close all projects other than the
current one.
93Setup and Workflows | Timeline Backups Managing Projects and Project Libraries
MEDIA
Using dynamic project switching, you can do the following:
 Copy and paste clips from the Media Pool of one project into another.
 Copy and paste timelines from the Media Pool of one project into another. When you paste a
timeline from another project, all of the clips used in that timeline will be pasted to the same
location as well.
 Copy and paste clips from a timeline in one project to a timeline in another.
 Copy a node’s settings from one project and paste them to a node in another project.
You can also copy and paste clips, timelines, and node settings from one project to another
without using dynamic project switching, but using switching makes this process faster.
Archiving and Restoring Projects
DaVinci Resolve has a convenient feature for quickly archiving every single media file used by
a project, including subtitle files, along with the project itself, to a single location. This can be done to
hand a project off to another DaVinci Resolve user, or to bundle a project and its media up for either
short- or long-term archiving using the backup methodology of your choice. The process is simple.
To Archive a project:
1 Open the Project Manager.
2 Locate and right-click the project you want to archive, and choose Archive.
The contextual menu command
for archiving projects
3 When the Archive Project window appears, choose a location to save the archive. Make sure you
choose a volume that’s large enough to accommodate the size of all the media from the project
you’re archiving, and click Save.
94Setup and Workflows | Timeline Backups Managing Projects and Project Libraries
MEDIA
4 When the Archive dialog appears, verify the location the archive will be saved to, and choose
which optional media you want to save within the archive. You can optionally save Optimized
media and/or Render Cache media associated with a project.
A dialog letting you choose whether to save
Optimized and/or Render Cache media
5 Click Ok, and a dialog with a progress bar will show you how long the archive operation will take
to finish. If any errors come up, resulting from missing or offline media, they’ll be presented at the
end of the process.
The resulting archive that is written is a directory with the .dra file extension. Inside this folder are a
series of subdirectories containing all of the media that’s used by the archived project. Each directory
of media files used is saved within a directory path that mirrors the exact path it came from, so you
have a reference for where each clip came from originally.
To restore an Archived project:
1 Copy the .dra archive directory you want to restore to the volume where you want those media
files to be. Restoring doesn’t move this directory, it only adds the project file within to the Project
Manager, so you should make sure the .dra archive directory is located on a storage volume with
suitable performance for you to work.
2 Open the Project Manager, right-click anywhere, and choose Restore from the contextual menu.
Choose the .dra archive directory you just copied, and click Open.
3 At the prompt, enter a unique project name for the restored project, and click OK. The project is
restored to the Project Manager, and remains linked to the media located inside the .dra archive.
4 Alternatively you can simply drag the .dra folder from your file system directly into the
Project Manager.
If, after restoring an archive, you want to move its media to another location, you can use
Media Management to do a move operation for all clips in that project. For more information
on Media Management, see Chapter 46, “Media Management.”
95Setup and Workflows | Timeline Backups Managing Projects and Project Libraries
MEDIA
Chapter 4
System and
User Preferences
This chapter covers the settings used for customizing the DaVinci Resolve
environment. System Preferences govern setup options that control the
hardware and software environment, while User Preferences control various
user controls within the software.
Contents
DaVinci Resolve Preferences  97
Adjusting Preferences  97
Resetting Preferences  98
System 98
Memory and GPU 98
Media Storage  99
Decode Options  101
Video & Audio I/O  102
Video Plugins  105
Audio Plugins  106
Control Panels  108
General  108
Internet Accounts  109
Advanced  109
User  110
Saving User Preference Presets  110
UI Settings  111
Project Save and Load 112
Cache Management  115
Editing  115
Color  118
Fairlight  120
Playback Settings  121
Control Panels  121
Metadata  122
Keyboard Customization  123
Choosing Keyboard Shortcut
Emulation Presets  123
Viewing Commands Assigned
to Specific Key Combinations  124
Searching for Keyboard Shortcuts  125
Managing Keyboard Mappings  126
Remapping a Command to One or More Keys 126
DaVinci Resolve Extras Download Manager 129
96Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
DaVinci Resolve Preferences
The DaVinci Resolve Preferences window contains workstation-specific settings for customizing how
DaVinci Resolve works, divided into System and User panes, selectable via buttons at the top of
this window.
To open the Project Settings window, do one of the following:
 Choose DaVinci Resolve > Preferences.
 Press Command-Comma.
```
TIP: You can open the preferences while the Project Manager is open when you first run
```
DaVinci Resolve by pressing Command-Comma.
System Settings of the Preferences window
Adjusting Preferences
The System and User panes are each divided into a series of panels which can be selected from a
sidebar at the left. Each panel contains a collection of related settings that affects some category of
DaVinci Resolve functionality.
97Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
To alter any preference setting:
1 Click on the name of any group of settings in the sidebar at the left to open that panel.
2 Change whatever settings you need to change.
3 Click Save to apply the changes you’ve made and close the Preferences window.
If you’ve updated certain System Preferences, you’ll be prompted to restart DaVinci Resolve,
but if you’ve updated the User Preferences, this will probably be unnecessary.
Resetting Preferences
Resetting all preferences to their defaults is simple. Click the Option menu at the upper-right corner of
the Preferences window and choose Reset System Preferences.
System
The System pane of the Preferences window consists of a series of panels that configure the computer
and other hardware that comprises your DaVinci Resolve workstation.
Memory and GPU
The top section of this panel provides Memory Configuration options, while the bottom section of this
panel provides controls over how GPU processing is handled.
Memory Configuration
This section has the following preference settings handling memory usage.
System Memory: The total available RAM on your workstation is listed here.
Limit Resolve Memory Usage to: This preference limits the total amount of system memory that
Resolve uses, keeping memory available for other applications. The maximum and default setting
for this preference is 75 percent of your system’s RAM.
Limit Fusion Memory Cache to: Lets you limit how much RAM the playback cache on the Fusion
page is allowed to use. Depending on the length of clips you’re working on in the Fusion page,
the playback cache can occupy a considerable amount of available memory. The amount you
allocate here is taken from the total amount of memory allocated by the “Limit Resolve Memory
Usage to” setting.
GPU Configuration
This section lets you choose how GPU processing should be handled.
Options for configuring the GPUs on your workstation
98Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
GPU processing mode: Lets you set DaVinci Resolve to use the OpenCL, CUDA, or Metal GPU
computing APIs for doing effects processing. Which is best depends on the GPUs that are
installed in your computer. Most users can leave this set to Auto to let DaVinci Resolve choose
what’s appropriate. Otherwise, here are specific recommendations. If you have a macOS system,
you should use Metal. Linux and Windows users with AMD GPUs should use OpenCL. Linux and
Windows users with Nvidia GPUs should use CUDA, but make sure you have the correct drivers
for your system, and that you have the latest update to CUDA installed. Additionally, when you
manually choose an option from this drop-down menu, the GPU selection mode drop-down
also appears.
Use Apple Neural Engine when possible: Lets you toggle the use of Apple Silicon’s Neural Engine
in compute tasks.
Use neural engine optimization on NVIDIA: Lets you toggle the use of NVIDIA Neural Engine in
compute tasks.
GPU selection mode: Lets you choose between Auto, which lets DaVinci Resolve choose which
of the available GPUs on your computer to use for processing, and Manual, which lets you choose
which GPUs to enable or disable for processing from a list that appears below. This can be useful in
instances where you have multiple GPUs installed on a machine and you want to choose only the
most powerful GPUs for processing. This can also be useful in instances where an external eGPU
is connected to a laptop or all-in-one with a weaker GPU, so you can choose the more powerful
eGPU for processing.
Use Display GPU For Compute: By default, a single GPU system uses the same GPU for the
DaVinci user interface and also for image processing. As greater processing speeds are achievable
with two or more GPUs, if two GPUs are installed for image processing, this checkbox enables the
shared use of the display GPU instead of dedicating it to just the DaVinci user interface. Users of
the non-studio version of DaVinci Resolve are restricted to the use of a single GPU.
GPU selection list: This list only appears when GPU processing mode is set to either OpenCL,
CUDA, or Metal, and when GPU selection mode is set to Manual. A list of every GPU installed in
your computer appears, and you can use checkboxes to the left of each GPU to enable or disable
specific GPUs from being used for processing.
Optimized Viewer Updates: This only appears on multi-GPU macOS and Windows systems or on
```
single- and multi-GPU Linux systems; enables faster viewer update performance.
```
Media Storage
This panel lets you define the scratch disk and other media storage locations used by DaVinci
Resolve, as well as proxy locations, and the default cache directories locations to be used when
creating new projects.
Media Storage Locations: This list lets you define the scratch disk of the system. The first volume
in this list is where Gallery stills and cache files are stored, so you want to make sure that you
choose the fastest storage volume to which you have access.
Mapped Mount: This column allows you to specify translatable media path mapping between Mac,
Linux, and Windows file system conventions.
99Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Direct I/O: This option allows DaVinci Resolve to write directly to the drive using the kernel buffers,
bypassing the normal storage cache in RAM. This allows access to the full performance of the drive.
Automatically display attached storage locations: This checkbox lets DaVinci Resolve access
media on all temporarily and permanently mounted volumes, including SATA and eSATA, SAS, USB,
```
FireWire, Thunderbolt, Gigabit Ethernet (GbE or GigE), Fibre Channel, and otherwise connected
```
hard drives, without having to add them to this list. This is on by default.
If you’re using the Apple App store version of DaVinci Resolve, turning on “Automatically display
attached local and network storage locations” automatically prompts you via a dialog to add
“Macintosh HD” as a storage location. Clicking Add Location prompts you to select the Macintosh
HD volume with another dialog, and clicking Open then adds that volume to the Media Storage
Volumes list. After you click Save to close the Preference windows, Resolve should now auto-mount
any volumes attached to your computer in the Media Storage browser of the Media page. Don’t
do this until after you’ve added a fast storage volume to the Media Storage Locations list, because
you don’t want Macintosh HD as the first volume in this list – the very first volume in this list should
always be reserved for your fast scratch volume.
Proxy Generation Location: These options let you define where any proxy media you create
will be rendered to.
 Proxy subfolders in media file locations: The proxy media is generated inside a subfolder
named “Proxy” at the same level in the file hierarchy as the original media file. This means that
if your original media is all in the same folder, you will have one “Proxy” folder containing all of
```
the proxy clips. If your original media is all contained in separate folders (i.e., one folder for each
```
```
video clip), you will have multiple “Proxy” folders, one inside every clip folder and containing
```
one proxy clip each.
 Use project settings: Uses the “Proxy generation location” destination, found in the Working
Folders section of the Master Settings of the Project Settings.
 Ask when creating: Opens a filesystem dialog, allowing you to select a specific folder for the
proxy generation.
Adding Storage Locations Manually
Some versions of DaVinci Resolve do not allow automatic display of attached volumes. In this case,
you can right-click anywhere in the background of the Media Storage panel’s volumes list on the
Media page and choose “Add New Location” to open a dialog you can use to choose a volume you
want to add.
Manually adding a volume to the
Media Storage panel’s volumes list
100Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Using Path Mapping to Access Volumes From Other Operating Systems
Shared media path mapping support for Mac, Linux and Windows makes it easier for multi-system
shops to share Resolve projects among different platforms that use different file path conventions.
To add a mapped mount string:
1 Open the Media Storage panel of the Resolve Preferences window.
2 Add the volume you want to map to the Scratch Disks list.
3 Double-click the Mapped Mount column of the drive you added to edit it.
4 Enter the alternate file path you want that volume to have. For example, if you’re on a Windows
workstation and you want to access a Linux volume, type the Linux file path into the Mapped
Mount column.
```
NOTE: If the volume you’ve selected to use for the cache becomes unavailable,
```
DaVinci Resolve will warn you with a dialog.
Decode Options
This panel contains all options available for using the GPU to accelerate the decoding and debayering
of various formats.
Use GPU for Blackmagic RAW decode: Lets you use your GPU to accelerate the decoding of
```
Blackmagic RAW (BRAW) media.
```
Decode H.264/HEVC using hardware acceleration: Allows the use of hardware acceleration for
H.264 or HEVC playback, if available on the computer you’re using.
Use easyDCP decoder: Since DaVinci Resolve has its own DCP encoder and decoder built in, this
checkbox lets you switch over to using easyDCP to do DCP decoding, if you have a license installed
on your workstation.
Automatically refresh growing files in the media pool: If you’re using a third-party application that
records live to a growing video file, you can now begin to edit that file while it’s still recording. Simply
import the growing file into the Media Pool, and when this box is checked, DaVinci Resolve will
continuously refresh to determine if the file has changed, and automatically update its attributes in the
Media Pool.
Stream files during download from Blackmagic Cloud: Check this box to be able to use a clip via
streaming, before it downloads completely from the Blackmagic Cloud.
Use GPU for RED Debayer: Lets you use your GPU to accelerate debayering of R3D media.
The latest RED API enables accelerated 8K debayering using either Metal or Cuda.
There are three options:
 None
 Debayer
 Decompression and Debayer
101Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Video & Audio I/O
The preferences in this panel let you choose video and audio interfaces on your workstation.
Video I/O
This section lets you choose which Blackmagic Design video interfaces you want to use for
monitoring, capture, playback, and Resolve Live, assuming you have any connected to your
workstation. If you have more than one Blackmagic Design video device connected to your computer,
you can independently configure them for playback and capture. If no interfaces are connected, no
options will be available.
 Capture Device: If you have a compatible video capture card for video input, you should choose
from the card options that appear here. This setting also sets the selected input device for use
in Resolve Live, allowing you to monitor and color correct a live video signal. Any changes to this
setting require a restart of the program.
 Monitor Device: If you have a compatible video output card, you should choose from the card
options that appear here. Leaving this set to “None” disables external video output. Disabling
video output can improve real time performance when external monitoring and output is not a
priority. You can also choose “None” when you’re using DaVInci Resolve with another application
open at the same time that’s using your workstation’s video output interface. When you’ve quit
the other application, you can reselect the video output interface for use by DaVinci Resolve. Any
changes to this setting require a restart of the program.
 Release video device when not in focus: When turned on, DaVinci Resolve releases control of the
video output device whenever you switch to another application.
 Audio monitoring delay: Allows you to adjust any latency between the video images and
the audio monitoring.
Video input/output options in the System Preferences
Audio I/O
This section lets you define the audio hardware and different sets of speakers with which to monitor
audio playback. To access more than the default stereo system output that most workstations default
to, you must use whatever software is available for your operating system to choose the desired audio
hardware you want to use, and define how many audio outputs are required for the type of monitoring
```
you want to do (stereo, immersive, and so on). For example, on macOS you’ll use the Audio Midi
```
Setup utility to choose output hardware and select a speaker configuration to be made available on
your system.
 I/O Engine: Lets you choose the audio hardware that DaVinci Resolve uses to process
audio. Choices include System Audio, Desktop Video, Fairlight Audio Accelerator, and ASIO
```
(Windows only).
```
 System Audio: System Audio interfaces with your computer’s native audio hardware and enables
the following parameters.
```
Playback processing buffer size: Lets you determine the size of the Playback buffer; to the right a
```
latency display indicates the approximate latency of your choice in milliseconds.
102Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
```
Record buffer size: Lets you determine the size of the Record buffer; to the right a latency display
```
indicates the approximate latency of your choice in milliseconds.
Input Device: Lets you chose the audio input device from the hardware attached to your system.
Output Device: Lets you chose the audio output device from the hardware attached
to your system.
Automatic speaker configuration: Checking this box sets DaVinci Resolve to output audio via
your workstation’s built-in audio output, even if a compatible video I/O interface is enabled for
capture and playback or for Resolve Live. Unchecking this box exposes additional controls with
which you can define your own speaker setup.
Assigning different audio I/O devices and required buffer adjustments
About Audio Monitoring and Audio Input
The audio processing throughout DaVinci Resolve, including on the Fairlight page and
audio processing using Fairlight FX plugins, is equally compatible with all platforms that
DaVinci Resolve runs on, including macOS, Windows, and Linux. In particular, DaVinci
```
Resolve supports audio monitoring and audio input using (i) the audio of a supported
```
```
Blackmagic Design I/O device such as an UltraStudio or Decklink, (ii) your macOS, Windows,
```
```
or Linux workstation’s on-board audio, (iii) any Core Audio-compatible, Windows-compatible,
```
```
ASIO, or Advanced Linux Sound Architecture (ALSA)-supported third party audio interface.
```
Alternately, you can monitor audio with the optional Fairlight Audio Accelerator, which is a
PCI card that’s designed to handle even more channels of audio I/O monitoring and recording,
and that’s also capable of accelerating audio processing operations to provide better
performance for audio operations.
```
NOTE: ASIO is a trademark and software of Steinberg Media Technologies GmbH.
```
103Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Monitor Speaker Configuration
When the Automatic Speaker Configuration box is unchecked it reveals another panel in the Video
and Audio I/O Preferences. Here you can assign your monitors to the default Main or Near sets, and
you can also create an additional 15 monitor sets specific to your needs.
 Monitor Set: Choose the default Main or Near or create up to 15 other
user-definable configurations.
 Rename: This button allows you to rename any of the monitor sets to something more
meaningful for your individual needs.
 Format: A drop-down menu allows you to choose the desired format type from Mono up to
Dolby Atmos 9.1.6. Below the Format type there are three windows to create the Monitor Set:
```
Layout: Breaks out the channels that correspond to the chosen format.
```
```
Output: Where you can assign the Output channels to your system.
```
```
Trim: Where you can reduce each individual level by up to -24dB of gain or add up to +10dB
```
of gain for fine tuning the speaker calibration required for your particular playback space.
Monitor System External Inputs
You can create multiple sets of monitoring with up to 16 user-definable setups from this panel. This
allows flexibility to have different combinations of monitoring speakers that you can switch among for
checking, reviewing, and creating different mixes.
 External Monitor Source: Chose None or up to 16 definable configurations.
 Rename: Lets you specify a name for an External Monitor Source.
 Format: When a Format is chosen, a drop-down menu appears allowing you to choose the
desired format type from Mono up to Dolby Atmos 9.1.6. Once a format has been chosen, three
more windows appear:
```
Layout: Which breaks out the channels that correspond to the chosen format.
```
```
Source: Where you can assign either Input Destination or Audio Repro.
```
```
Input: Where you can assign an individual track when in Audio Repro, or assign the
```
specific channel when in Input Destination.
 Rename: This button allows you to rename any of the numerically labeled monitor sets to
something more meaningful for your individual needs.
Patching and renaming different external inputs in Video and Audio I/O Preferences
104Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Immersive Audio Controls
These two Preference panels allow you to configure for the type of immersive audio that you want to
have available in your project and also for linking to a Dolby RMU for doing Dolby Atmos mixing.
 Immersive Audio: This panel allows you to enable the various types of immersive audio
offered within DaVinci Resolve. Those formats are: Ambisonics, Audio Vivid, Auro 3D, BS.2051,
Dolby Atmos, MPEG-H Audio, 22.2 Surround, SMPTE ST 2098, and 360 Reality Audio.
Immersive Audio Preferences
 Dolby Atmos: Checking this box allows the use of an external Dolby Atmos renderer.
Once checked you can enter the IP address of the RMU and choose the base audio output.
Dolby Atmos Preferences
Video Plugins
You can selectively enable and disable specific Open FX plugins on startup. You can use this function
to streamline and organize the Open FX list to just the plugins you commonly use, or to exclude a
problematic plugin that causes instability in the system. Additionally, DaVinci Resolve automatically
checks the last plugin loading result on startup, and skips any plugins that previously caused a
crash or hang.
Individual Open FX plugins can be manually enabled and disabled in the Video Plugins panel by
checking or unchecking the boxes corresponding to the plugins.
105Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
The Video Plugins panel allows you to enable or disable specific Open FX plugins at startup.
Audio Plugins
Three sections of parameters let you manage VST effects, enabled plugins, and external audio
processes.
 VST Effects: A list at top lets you manually add and remove VST plugin effects directories,
if necessary. VST effects aren’t installed in a standard location, so it may sometimes be necessary
to add a newly installed directory of VST plugins that you’ve just installed on your system.
Audio Plugins Preferences - VST Effects
 Available Plugins: Once you’ve added one or more VST directories to the list, a second list
underneath shows all audio plugins that are available within these directories. Each plugin on the
list has a checkbox that shows whether or not it’s currently enabled. Any VST plugins that cause
DaVinci Resolve to crash while loading them during startup will be automatically disabled. You
can use this list to see which plugins have been disabled, for troubleshooting purposes, and to
reenable such “blacklisted” plugins by turning their checkboxes back on.
Category Column: VST and Audio Units plugins are organized into categories within the Fairlight
Mixer. You can move a plugin to a different category by clicking its category name and selecting a
new one from the Category popup list.
```
NOTE: This does not apply to Fairlight FX plugins.
```
106Setup and Workflows | Chapter 4 System and User Preferences
MEDIAAudio Plugins Preferences - Available Plugins
 Setup External Audio Processes: While working in the Fairlight page, you have the ability to
process an audio file using a third-party application, if necessary, in the event you need to use
another application’s capabilities to create an effect or solve an issue that can’t be accomplished
in the Fairlight page itself. To do this, you must first add one or more applications to the External
Audio Process list in the Audio Plugins panel of the System Preferences.
```
NOTE: VST is a trademark of Steinberg Media Technologies GmbH.
```
Audio Plugins Preferences - Setup External Audio Processes
To add an External Audio Process:
1 Click the Add button.
2 Double-click the text in the Name column and change the name to that of the application or
process you’re going to link to.
3 Click once in the Path column, and then use the file dialog to locate and select the application or
script you want to use as the external audio process.
4 Open the drop-down menu in the Type column, and choose how you want the selected audio
```
process to work: Reveal (open the application), Command Line (use from Terminal), or Clipboard
```
```
(copy the audio clip file path to the clipboard to paste into the open command of an application
```
```
or utility).
```
5 When you’re done, click Save, and restart DaVinci Resolve if you’re prompted to.
107Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Control Panels
Two sections let you specify which Color Grading Panel and Audio Console is connected
to your workstation.
 Color Grading Panel: A menu lets you choose which color grading panel you have connected to
your workstation. Some panels expose additional controls.
If you have a DaVinci Resolve Mini or Micro Panel, leave this setting set to None and these panels
will be auto-detected by Resolve when you plug them in.
If you have a control panel that connects via USB, choose your panel from the list.
If you have a DaVinci Resolve Mini Panel connected over Ethernet, choose “DaVinci Resolve Mini
```
Panel (Ethernet)” and then choose your panel from the drop-down that appears.
```
If you’re using a JLCooper Eclipse, choose “JLCooper Eclipse CX” and then enter the IP and Port
number into the fields that appear.
 Audio Console: A menu lets you choose which Fairlight Audio Console you have connected to
your workstation. Some panels expose additional controls.
 Use MIDI Audio Console: A checkbox lets you enable the use of a third-party audio console that’s
connected to your workstation. Turning this on exposes three additional menus.
MIDI Protocol: Lets you choose either the HUI or MCU protocol, whichever is compatible with the
audio console you want to use.
MIDI Input: Lets you choose the MIDI input used to connect your console.
MIDI Output: Lets you choose the MIDI output used to connect your console.
 Head Tracker: A menu lets you choose which head tracker profile to use for immersive audio.
General
This panel provides various options for scripting, audio processing, monitoring, and sending
problem reports.
```
 External Scripting Using: (Resolve Studio only) Options include None, Local, and Network. When
```
set to None, only scripting in the Console window is allowed. When set to Local, external scripts
and applications on the same computer can control DaVinci Resolve. When set to Network,
```
external scripts and applications from other computers on the network (or via the internet) can
```
control DaVinci Resolve.
 Use 10-bit precision in viewers if available: This checkbox only appears on macOS installations
of DaVinci Resolve. Turning this checkbox on lets DaVinci Resolve display 10-bit images in
the Viewer.
 Use Mac Display Color Profile for viewers: If you’re using DaVinci Resolve on macOS, this
checkbox enables all viewers in DaVinci Resolve to use whatever display profile is selected in the
Displays panel of the System Preferences. This lets DaVinci Resolve use ColorSync on macOS so
your Viewer image should better match your output display.
 Optimize project library cloud data traffic: If you’re having difficulty accessing the Blackmagic
Cloud through a corporate firewall, check this box to connect without having to set port mapping
and firewall exceptions. https://blackmagicdesign.com still needs to be whitelisted for access.
 Automatically Tag Rec.709 Scene Clips as Rec.709-A: Turn this checkbox on to automatically tag
any Rec. 709 QuickTime files for Rec. 709-A playback. This setting is useful if your final QuickTime
```
video does not match what you see in the Resolve viewers (gamma shift), and you wish to export
```
for the web rather than broadcast.
108Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
 Automatically Scan other project libraries for remote rendering jobs: Turn this checkbox on to
scan all connected project libraries, rather than just the current project library for possible remote
rendering jobs.
 Automatically Check for Updates: Turn this checkbox on to make it easier to ensure you’re using
the latest version of DaVinci Resolve. You can also choose DaVinci Resolve > Check For Updates
to notify you of new versions and download them when available.
 Automatically opt-in for new beta program notifications: Lets you know when public beta
versions of DaVinci Resolve become available, in case you’re interested in living on the edge.
 Send report when application quits unexpectedly: When this checkbox is turned on, this setting
enables DaVinci Resolve to automatically prepare a problem report whenever DaVinci Resolve
```
unexpectedly quits. You get to fill out some information (please be as specific as you can about
```
```
what you were doing when DaVinci Resolve had its issue) and click a button to send the report.
```
 Limit Presentations upload speed to X KB/s: Allows you to set a hard limit on the upload speed
while using Presentations to avoid saturating all your network bandwidth.
 Use Remote Monitoring without Blackmagic Cloud: Allows you to use remote monitoring on your
own network instead of going through Blackmagic Cloud.
 Use TURN server for Remote Monitoring: If you are not using Blackmagic Cloud for security
reasons and you are using a self-configured or cloud-based TURN servers to route and relay
monitoring streams, enter that server here.
 Prevent sleeping when Blackmagic Cloud sync enabled project is open: This checkbox is on by
default and prevents your computer from entering sleep mode while a Blackmagic Cloud project is
active to make sure all online data transfers complete. Uncheck this box to let your computer go to
sleep whenever it wants.
 Automatically send problem reports: When this checkbox is turned on, problem reports are
automatically sent, with no user intervention. You have the option of adding your name and email
address to be automatically included, but this information is optional.
Internet Accounts
The Internet Accounts panel serves as a login manager for the Blackmagic Cloud and other social
media sites.
DaVinci Resolve has tight integration with YouTube, Vimeo, TikTok, Dropbox, and Frame.io that allows
you to render and upload directly to each service. This panel provides buttons that let you sign into
your YouTube, Vimeo, TikTok, Dropbox, and Frame.io accounts, as well as specify a local cache
location for media being synced with Frame.io.
For each service you sign into, a floating window presents the interface in which you’ll need to enter
your login name and password to enable integration, followed by whatever two-factor identification
and other required steps are necessary. Once entered, DaVinci Resolve will sign in to each of these
services automatically when DaVinci Resolve opens.
Advanced
This tab is used for special Resolve configurations and SAN parameters that are applicable to
older file systems.
109Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
The Internet Accounts panel of the System tab of the DaVinci Resolve Preferences window
User
This panel lets you choose user preferences, specific to your workstation, that govern such things as
UI behaviors and appearance, auto save settings, editing and color defaults, control panel action, and
keyboard shortcut mappings.
```
TIP: Many of the settings in the User panel used to be found in the Project Settings window
```
prior to version 14, but they were moved here to accommodate collaborative workflows with
each user having their own independent general, editing, and color settings, as well as their
own keyboard shortcuts.
Saving User Preference Presets
It’s possible to save multiple presets for instant recall of different User Preference settings, using the
Option menu in the UI Settings window.
110Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
The commands for managing User Preference presets in
the Option menu of the UI Settings window
Methods of managing User Preference presets:
 To save a preset: Choose whatever settings you want to use, then click the UI Settings window
Option menu, and choose Save User Preferences as Preset. Enter a name into the dialog, and
click OK. That preset will now appear at the top of the Option menu.
 To load a preset: Click the UI Settings window Option menu, and choose Load Preset from the
submenu of the preset you want to load.
 To update a preset: Load a preset you want to edit, then change whatever settings you need to,
and choose Update Preset from the submenu of that preset in the Option menu.
 To export a preset: Choose Export Preset from the submenu of any preset in the Option menu.
A file with the .userprefs extension is saved at the location you chose.
 To import a preset: Choose Import User Preferences as Preset in the Option menu, use the dialog
to find the exported .userprefs preset file you want to import, and click Open.
 To delete a preset: Choose Delete Preset from the submenu of any preset in the Option menu.
 To reset all presets: Choose Reset User Preferences from the Option menu to restore all User
Preferences to their default settings.
UI Settings
A collection of operational preferences.
 Language: A Language drop-down at the top lets you specify which language the DaVinci
Resolve user interface displays. DaVinci Resolve currently supports English, Chinese, Japanese,
Spanish, Portuguese, French, German, Italian, Russian, Thai, Vietnamese, and Korean.
 Reload last working project on startup: Automatically reopens the last project a user had open
whenever that user logs back into DaVinci Resolve. This checkbox can only be enabled when
editing a preset configuration in the Presets panel, so that it’s always on no matter which project
you open as long as you’re using that particular preset.
 Show focus indicators in the User Interface: Lets you enable or disable a red line at the top of
each panel that indicates which panel currently has focus.
 Use gray background for user interface: By default, DaVinci Resolve uses a blue-gray
UI background, intended to provide a more attractive experience for users focused on the less
color-critical aspects of DaVinci Resolve, namely editing. Turning this checkbox on switches
DaVinci Resolve to a totally neutral, desaturated gray UI, which can be valuable as a point of
reference for colorists concerned about the blue-gray UI’s potential to bias the eye in the dark
environment of the grading suite.
 Use gray background in viewers: When turned on, sets the background of all viewers to gray,
making it easier to evaluate image blanking or minor sizing adjustments than with the default
dark background.
 Resize image in viewer to square pixels: This control will select between using a square or
non-square pixel aspect ratio within the Viewer. This is important when working with SD images
which do not have a square pixel aspect ratio.
111Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
 Delay viewer display by X frames: When turned on, you can enter a number of frames to delay
DaVinci Resolve Viewers as they appear on your computer displays so that the image on your
computer display better syncs up with the same image shown on external displays that are
delayed due to various signal processing processes.
 Output single field when paused: This setting will reduce flicker when grading using a computer
monitor or when working with interlaced material. Ordinarily, when viewing interlaced material in
Stop or Pause mode, field one is displayed followed by field two. Depending on the image, this can
result in a flicker on the display. When this option is enabled, only field one will be shown on the
```
monitor when playback is paused; however both fields will be shown when the clips are played.
```
 Stop playback when a dropped frame is detected: When enabled, sets DaVinci Resolve to stop
playback whenever a frame is dropped on output, to warn you that there are performance issues
on your workstation. This is particularly useful when you’re outputting to tape.
 Stop renders when a frame or clip cannot be processed: When enabled, this will halt a render if
DaVinci Resolve detects an error in the encoding, rather than continue to try to process it.
 Show playhead shadow: Checking this box turns on the playhead shadow, a transparent orange
range used for visually measuring that extends a certain number of frames before and after the
playhead. The number of frames in the range before or after the playhead can be adjusted in the
Editing section of the User Preferences.
 2D timeline scrolling: Checking this box will scroll the Timeline vertically through all the Video or
Audio tracks when moving the mouse wheel. Unchecking this box will scroll the entire Timeline
horizontally when moving the mouse wheel.
 Timeline sort order: A user setting that allows you to determine the default sort order of the
Timelines that appear in the Viewer drop-down menus throughout DaVinci Resolve.
```
Alphabetic: Sorts Timelines alphabetically A-Z.
```
Creation Date: Sorts Timelines by oldest creation date first.
```
Recently Used (default): Sorts Timelines by the last 10 actively used timelines.
```
Project Save and Load
The Project Save and Load panel lets you control how projects are opened, and how they’re saved.
Load Settings
The Load Settings preference lets you control a key aspect of project opening performance, namely
whether or not all timelines within a given project are loaded into memory at the time of opening.
 Load all timelines when opening projects: To improve the performance of longer projects with
multiple timelines, the “Load all timelines when opening projects” checkbox in the Project Save
and Load panel of the User Preferences defaults to off.
When this checkbox is off, opening a project only results in the last timeline you worked on being
```
opened into memory; all other timelines are not loaded into RAM. This speeds up the opening
```
of large projects. However, you may experience brief pauses when you open other timelines
within that project, as each new timeline must be loaded into RAM as you open it. If you open
a particularly gigantic timeline, a progress bar will appear letting you know how long it will take
to load. Another advantage of this is the reduction of each project’s memory footprint, which is
particularly valuable when working among multiple projects using Dynamic Project Switching.
If you turn this on, all timelines will be loaded into RAM, and you’ll experience no pauses when
opening timelines you haven’t opened already. However, projects with many timelines may take
longer to open and save.
112Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Save Settings
The Save settings allow you to control how DaVinci Resolve handles automated saving and
project backups. These features can save you from the heartache of lost work resulting from an
unexpected problem.
 Live Save: Enabled by default, Live Save is a progressive, fast, always-on autosave mechanism
that “saves as you go.” All changes in the Cut, Edit, and Fairlight pages are saved as you make
them. All changes in the Fusion and Color pages are automatically saved when you switch to
another clip, and also periodically and invisibly in the background while you work to ensure that
your work is saved even if you haven’t switched clips in a while.
 Project Backups: Turning on the Project Backups checkbox in the Project Save and Load panel
of the User Preferences enables DaVinci Resolve to save multiple backup project files at periodic
```
intervals, using a method that’s analogous to a GFS (grandfather father son) backup scheme.
```
This can be done regardless of whether or not Live Save is turned on. Each project backup is a
complete project file, excluding stills and LUTs.
Once you’ve enabled Project Backups for a long enough time, whatever saved project backups
have been created are retrievable in the Project Manager via the contextual menu that appears
when you right-click a project, by choosing Project Backups. Opening a project backup does not
```
overwrite the original project; project backups are always opened as independent projects.
```
Restoring a project backup in the Project Browser
 Timeline Backups: Turning on the Timeline Backups checkbox in the Project Save and Load panel
of the User Preferences enables DaVinci Resolve to save multiple backups of a timeline at periodic
```
intervals, using a method that’s analogous to a GFS (grandfather-father-son) backup scheme. This
```
can be done regardless of whether or not Live Save is turned on.
If you want to revert to a previous backup of a timeline, simply right-click on the timeline in the
Media Pool, select Restore Timeline Backup from the contextual menu, and choose the backup
from the list of options. Backups are organized by date and time, making it easy to find the specific
timeline you want to restore.
Restoring a timeline backup does not overwrite your current timeline. Instead the selected backup
will be brought into the Media Pool as a new timeline, with the name “Backup” appended to it.
113Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Restoring a timeline backup in the Media Pool
Project and Timeline backups are only saved when changes have been made to a project.
If DaVinci Resolve sits idle for any period of time, such as when your smart watch tells you to
go outside and walk around the block, no additional project backups are saved, preventing
DaVinci Resolve from overwriting useful backups with unnecessary ones.
Three fields let you specify how often to save a new backup, while the fourth lets you choose
where the backups will be saved. These settings apply to both Project and Timeline backups.
Perform backups every X minutes: The first field specifies how often to save a new backup within
the last hour you’ve worked. By default, a new backup is saved every 10 minutes, resulting in six
backups within the last hour. Once an hour of working has passed, an hourly backup is saved and
the per-minute backups begin to be discarded on a first in, first out basis. By default, this means
that you’ll only ever have six backups at a time that represent the last hour’s worth of work.
Hourly backups for the past X hours: The second field specifies how many hourly project
backups you want to save. By default, two hourly backups will be saved for the current day. Past
that number, hourly backups will begin to be discarded on a first in, first out basis.
Daily backups for the past X days: The third field specifies for how many days you want to save
backups. The very last backup saved on any given day is preserved as the daily backup for that
day, and by default daily backups are only saved for two days. Past that number, daily backups
will begin to be discarded on a first in, first out basis. If you’re working on a project over a longer
stretch of time, you can always raise this number.
Backup location: Click the Browse button to choose a location for these backups to be saved.
By default they’re saved to a “ProjectBackup” directory on your scratch disk, although you could
change this to a volume that better fits into your data backup methodology. This folder contains
both Project and Timeline backups.
114Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Cache Management
This section allows you to delete your local cache automatically after a certain number of days to keep
your drive from filling up with older projects.
Of course, you can always manage these files manually from the Playback > Manage Render Cache
menu, but this new preference lets you set and forget a cleanup operation.
Media Cache Settings
Delete Cache files older than xx days: Check the box and select the number of days after
which the automatic deletion of the Cache files will occur.
Editing
The settings in this panel affect new timeline settings, editorial default values, trim behaviors, timeline
UI appearance, and frame interpolation settings.
New Timeline Settings
These settings define the presets that populate the New Timeline Options window whenever you
create a new timeline.
 Start Timecode: You can change the Start Timecode if a specific start time is required.
 No. of Video Tracks: Enter how many video tracks you want to have. You can also drag within this
field to adjust the number of video tracks with a virtual slider.
 No. of Audio Tracks: Enter how many audio tracks you want to have. You can also drag within this
field to adjust the number of audio tracks with a virtual slider.
 Audio Track Type: Choose the channel mapping you want the new audio tracks to use.
Automatic Smart Bins
These settings let DaVinci Resolve automatically create Smart Bins whenever clips with relevant
metadata appear in the Media Pool, or whenever such metadata is added to clips that are already
in the Media Pool. You can choose which Smart Bins are automatically created via a series
of checkboxes.
General Settings
These settings define the timing of resolve-generated effects and editing operations.
 Standard generator duration: Defines the default duration of generators you edit into the
Timeline, in Seconds or Frames. The default value is 5 seconds.
 Standard transition duration: Defines the duration of transitions, in Seconds or Frames, that you
add to an edit point in DaVinci Resolve. The default value is 1 second.
 Standard still duration: Defines the duration of stills that you import such as TIFF, PNG and other
supported graphic file formats, in Seconds or Frames. The default value is 5 seconds.
 Pre-roll time: Determines how much of the Timeline before the current position of the playhead to
play when using the Play Around command.
 Post-roll time: Determines how much of the Timeline after the current position of the playhead to
play when using the Play Around command.
115Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
 Audio subframe nudge: Determines the number of milliseconds or subframes are nudged when
you use the Subframe Left/Right controls.
 Default handles length: The value used when creating a timeline with handles. The default is one
second worth of frames.
 Default fast nudge length: The number of frames that are nudged when you use the
```
Shift-Comma (,) and Shift-Period (.) keyboard shortcuts.
```
 Pre-playhead shadow length: The number of frames in the Timeline prior to the playhead covered
by the Playhead Shadow, if enabled by checking the “Show playhead shadow box” in the User UI
Settings preferences.
 Post-playhead shadow length: The number of frames in the Timeline after the playhead covered
by the Playhead Shadow, if enabled by checking the “Show playhead shadow box” in the
User UI Settings preferences.
 Timeline overlay retains the last performed action: Turn this checkbox on if you want
DaVinci Resolve to always remember the last edit type you used in the Timeline Viewer Overlay,
and highlight it on this Overlay whenever you drag another clip over the Timeline Viewer to let
you know that the last edit you performed is the new default edit if you drop clips to the left
of the overlay.
 Always highlight current clip in the media pool: When turned on, any clips at the position of the
playhead on the Edit or Color pages will be automatically highlighted in the Media Pool.
 Prioritize pasting to the in and out range: Normally, pasted clips appear at the playhead position
in the timeline. Check this box if you wish them to be pasted according to the timeline in and out
points instead.
 Sync the Master Timeline to the current frame: If you turned on “Automatically match master
timeline with media pool” in the Color settings, then this option lets you make sure that whenever
you open the Master Timeline, the playhead is at the same clip and frame that it was in the
previous Timeline you were working on.
 Show offline reference for timeline gaps: If there’s a missing clip in a conformed timeline that
results in a gap in the Timeline Editor, turning this option on sets DaVinci Resolve to show the
corresponding frames of an “offline reference movie,” if one has been assigned to that timeline,
instead of black. This can be helpful in emergency situations when you’re missing timeline clips
```
right before a screening or review session; this feature lets you play or output the missing frames
```
using the corresponding media from the offline reference movie, instead of outputting black.
For more information on using and assigning Offline Reference Movies, see Chapter 55,
“Preparing Timelines for Import and Comparison.”
 Show offline reference for non-conformed edits: If there’s missing media in a project that results
```
in an unlinked clip in the Timeline Editor (represented by a red exclamation point overlay on that
```
```
clip), turning this option on sets DaVinci Resolve to show the corresponding frames of an “offline
```
reference movie,” if one has been assigned to that timeline, instead of black. This can be helpful
in emergency situations when you’re missing source media right before a screening or review
```
session; this feature lets you play or output the missing frames using the corresponding media
```
from the offline reference movie, instead of outputting black.
For more information on using and assigning Offline Reference Movies, see Chapter 55,
“Preparing Timelines for Import and Comparison.”
116Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
 Use custom safe area overlays: When turned on, displays Action Area and Title Area fields that
let you set a custom percentage for each. The default values are 93% for Action Area and 90%
for Title Area.
 Align audio edits to frame boundaries: When turned on, the In and Out points of audio clips
always align themselves with whole frame boundaries, just like video clips. When turned off, you
can perform subframe audio edits to audio-only clips, or to linked audio when you’ve suspended
linked selection.
 Configure clips as multi-mono on import: Checking this box allows you to import any
multichannel audio in a multiple mono configuration. This lets you take any Stereo, 5.1, or other
multichannel sources and automatically configures them to multiple mono files with the same
number of tracks when you add them to the Media Pool.
 Limit media pool audio sync to first timecode match: When two or more audio clips overlap
timecode with a video clip, the default behavior is to sync all overlapping audio clips by making
as many new tracks as necessary. Checking this box replaces this behavior by having DaVinci
Resolve choose what it thinks is the most likely single audio track, and sync just that single audio
clip, ignoring the others.
```
 Import Finder tags as Keywords (Mac only): When turned on, any color tags that are set and
```
defined in Mac OS for a media file will automatically be imported as keyword metadata alongside
that media file.
```
NOTE: Even when Align audio edits to frame boundaries is turned off, if linked selection is
```
on, you’ll be unable to make subframe edits while you’re resizing both the audio and video of
linked clips.
Text
Check the Display Only Specific Fonts box to explicitly limit the font options shown for your text
elements. This lets you set a white list of fonts that you are cleared to use, and hide all other fonts on
the system.
To set up an allowed fonts list:
1 Check the box in Preferences > User > Editing > Text > Display Only Specific Fonts.
2 Select a font filter file.
A font filter file is any UTF-8 text file with a combination of explicit font names or text with asterisk
wildcards to match multiple fonts, listed one entry per line.
```
*Gothic* (any font name with Gothic in it)
```
Arial
```
Helvetica* (any font name beginning with Helvetica)
```
Open Sans
Default Fades
These settings define the curves of the default audio fades in Fairlight.
 Fade In/Out: Define the curve type for fade ins and outs.
 Crossfades: Define the curve type for the ins and out of the crossfade.
Checkboxes for None, Equal Power, and Equal Gain for crossfade type.
117Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Color
The settings in this panel govern different behaviors in the Color page.
General Settings
Affect a variety of behaviors while working in the Color page.
 Master reset maintains RGB balance: Defines how the DaVinci control panel trackball/ring reset
```
buttons reset primary color adjustments. When this option is turned off (the default), pressing the
```
ALL Reset button returns the primary correction values to their default values. When this checkbox
```
is turned on, then pressing the ALL Reset button (a) resets the YRGB values so that the overall
```
```
values are kept and the ratio of YRGB to each other is maintained, and (b) pressing the RGB Reset
```
button sets the three color channels to the average of what they were previously set to.
```
 Wipe wraps when viewing reference stills: Turning this on (the default) lets stills wrap around
```
the edge of the screen while you’re adjusting the wipe using the mouse, rather than stopping
at the screen’s edge. If you find this behavior awkward when trying to quickly create full-frame
comparisons with stills to flip on and off, it can be disabled.
 High-Visibility Power Window Outlines: Turning this on sets Power Window outlines to be drawn
```
as green (for the center shape) and yellow (for the softness shapes), to make these windows easier
```
to see in certain circumstances, instead of the default white and gray.
 Mattes display high contrast black and white: When enabled, the HILITE command, which displays
```
the current key, shows a black and white matte (i.e., high contrast) rather than the standard gray matte.
```
For more information on this setting, and on use of the HILITE command, see Chapter 135,
“Secondary Qualifiers.”
 Next scene switches to visible track: When grading a project with multiple tracks, you can use
this option to alter the “next scene” command to work better in projects with multi-clip composites.
With this option turned off, pressing NEXT SCENE on the DaVinci control panel, or using the
Down Arrow keyboard shortcut, moves the playhead to the very next clip in the Thumbnail
timeline, regardless of whether it’s in front of or behind another clip. Turning this option on causes
the NEXT SCENE command to move the playhead to the clip in the highest track if the next clip is
part of a multi-clip composite with multiple clips stacked over one another.
 Previous or Next node navigates only to correctors: Node navigation only selects corrector
nodes and bypasses mixer, splitter and combiner nodes, etc.
 Preserve node numbers when adding nodes: Checking this box increments the node numbering
by the order in which they are created, regardless of its position in the node tree. Unchecked
reflows the node numbering automatically based on the node’s position in the tree.
 Always perform copy and paste on selected nodes: Bypasses the interface focus-based
selection for copying and pasting full grades vs. individual nodes. When checked, DaVinci Resolve
will only copy and paste between selected nodes regardless of the interface focus.
 Use Legacy Auto Color: As of DaVinci Resolve 16, the A button in the Color Wheels palette and
the Shot Match command available from the Thumbnail Timeline contextual menu both now use
advanced algorithms, based on the DaVinci Neural Engine, to provide superior results when
automatically adjusting color balance and contrast. This checkbox lets you set the A button to use
the older algorithm instead.
 Use Legacy Shot Match: As of DaVinci Resolve 16, the Shot Match command available from the
Thumbnail Timeline contextual menu uses an advanced algorithm, based on the DaVinci Neural
Engine, to provide superior results when automatically adjusting color balance and contrast.
This checkbox lets you set the Shot Match command to use the older algorithm instead.
118Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
 Histogram Background on Grading Tools: This drop-down menu lets you turn the histogram
that appears in the background of the Curves palette either Off, On based on the node’s Input
```
(changes made to the curve do not affect the background histogram), or On based on the node’s
```
```
Output (changes made to the curve do affect the background histogram).
```
 Automatically cue x frames into timeline clips: This setting affects the operation of the NEXT
SCENE and PREV SCENE commands in the Color page. The default cue point when moving from
one clip to the next is the first frame of each clip. Entering a value, in frames, in this field sets the
default cue point to the specified number of frames after the first frame of each clip you move the
playhead to. This can be convenient if the source material has black or camera rollup flashes at the
beginning of every clip while you’re trying to grade dailies.
 Neighboring Clips in Split Screen: Lets you choose how many neighboring clips next to the
current clips are shown in a grid in the Color page Viewer when you turn on the Neighbor Clips
option of the Split-Screen shot comparison control.
```
 Switching clips: (this setting can also be changed from the Option menu in the Node Editor)
```
When switching clips, DaVinci Resolve can switch to the same or another node in the node graph.
The four options below determine which node is selected:
Selects last adjusted node: The default setting, where each clip in the Timeline retains its own
independent node selection that’s remembered whenever you move back to that clip.
Selects first node: The first node is always selected when you move to another clip.
Selects last node: The last node is always selected when you move to another clip.
Selects same node: If the clip you’ve moved to has as many or more nodes as the last clip, the
node of the same number will be selected. If the clip you’ve moved to has fewer nodes than the
last clip, the next highest node will be selected.
 Color picker: Changes the way that colors are selected when using the Secondary color
correction controls. DaVinci Resolve is the normal and modern mode, however some colorists who
are familiar with the legacy 2K prefer the DaVinci 2K mode.
Ripple Mode
This setting determines the behavior of the Ripple command that’s initiated in the Color page.
 Target clips are set to: The Ripple mode that’s used when you select a Ripple command in the Color
page, either using the RIPPLE button on the Advanced Panel, or selected from the Color menu.
For more information on using this function, see Chapter 142, “Grade Management.”
Exact values changed: Changes made to the current clip are rippled to the specified clips using
the exact parameters that were changed. For example, if the Master Gain level in the current
clip is changed to 0.75 of its range, each clip you ripple will have a Master Gain level of 0.75.
Only parameters you adjust are rippled.
Percent value changed: Changes made to the current clip are rippled to the specified clips by the
percentage of change you made to the altered parameters. For example, if the current clip has a
Master Gain level of 1.00 and is changed to 0.90 units, then the Master Gain level of each clip you
ripple will have a relative reduction of 10% relative to its previous value.
Unit values changed: Changes made to the current clip are rippled to the specified clips by the
same delta of change, using whichever units make sense for the affected parameter. For example,
if the current clip had a Master Gain of 0.80 and you increased it to 0.90, each rippled scene’s
Master Gain level increases by 0.10.
All values are copied: The current clip’s grade is rippled to the specified clips in its entirety.
No comparison is made with the original clip’s parameters, and all memory parameters are rippled.
119Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Printer Light Step Calibration
For film projects, when you have tight integration with a film lab, it is possible to adjust the printer light
calibration sets to match the lab you are using. You should work with your lab technician to set up the
Lab Aim settings, the Steps adjustments, which is an incremental value, and the Density Increment
adjustment, which is the amount of correction applied within each step. Usually, the Step and Density
values will be identical, but this will be up to your lab and your preference.
Fairlight
Video I/O Offset
The two preferences found in this section let you offset overall video playback up to 7 frames earlier
than your audio playback, to account for situations where image processing applied to your video
output is causing delays that make the video out of sync with your audio. For example, let’s say your
video output is going through a video convertor that adds a 1 frame delay, and then connects to a
video projector that adds another 1 frame of delay. You can set your Video Monitor Offset to 2 frames
to compensate, so the audio/video sync is solid.
 Video Monitor Offset: This drop-down menu lets you choose an offset from 0 to 7 frames.
 Apply Offset during Jog and Shuttle: Turning this checkbox on ensures that the offset you
choose is also applied when you use Jog and Shuttle to move through your program.
General Settings
The two preferences found in the General Settings section both let you customize the Loop Jog
behavior that’s currently available only on the Fairlight page. Choosing Timeline > Loop Jog enables
a brief sample preview to be heard while scrubbing the playhead through the Timeline. This can
make it easier to recognize bits of dialog or music as you’re quickly scrubbing through tracks, in
situations where you’re trying to locate specific lines or music cues. It also enables this brief sample
preview to loop endlessly when you hold the playhead on a frame, so you can pause while scrubbing
```
and hear (by default) the current 80 ms prior to the playhead as it loops. A pair of settings let you
```
customize this behavior.
 Loop Jog Alignment: Three options let you choose whether you loop audio Pre the position of the
playhead, Centered on the playhead, or Post the position of the playhead.
 Loop Jog Width: A field lets you choose how many milliseconds of audio to loop when Loop Jog
is enabled. How many milliseconds of audio corresponds to one frame depends on the frame rate
of the video. For example, at a frame rate of 25 fps, there are 1000/25 = 40 ms per frame, so the
default value of 80 ms equals two frames of looping.
 Enable auto patching: Checking this box routes the first of your system audio inputs to the track
that has “arm for record” on.
 Mixer follows selected track: Checking this box ensures that the selected track appears focused
and left-most in the Mixer pane.
 Include mixer events in Undo history: Checking this box ensures that you can undo mixer events
```
(such as edits to panning or track mute state).
```
120Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Automation
The two preferences found in the Automation section let you customize the Glide Time between
Automation events and whether or not Automation events are included when recalling a preset or
when copying and pasting.
 Glide Time: Enter a value in milliseconds to customize the Glide Time for automation.
 Write on Preset or Clipboard Paste: Checking this box ensures that Automation events are
written to the track when recalling a track preset or copying and pasting. Note that when enabled,
the information written is still dependent on the status of what master automation is enabled or
disabled. For example, if plugin automation is disabled, no plugin automation will be written.
Playback Settings
These preferences let you improve realtime performance in DaVinci Resolve by disabling specific
UI features and optimizing the quality of some operations.
 Hide UI overlays: When using a single GPU for both display and CUDA, OpenCL, or Metal
processing, or if your display GPU is underpowered, or if you lack the PCIe bandwidth required for
the currently specified resolution or frame rate, you may be able to improve real time performance
by turning this option on. When enabled, onscreen controls such as the cursor, Power Window
outlines, and split-screen views are disabled and hidden during playback. When playback is
paused, all onscreen controls reappear.
 Minimize interface updates during playback: When enabled, gives priority to real time
performance during playback by reducing user-interface updates. This is helpful when
you’re creating complex grades on systems with low processing power, or when working on
projects at high resolutions.
 Performance Mode Automatic/Manual: A trio of radio buttons let you choose between Automatic
```
(default) and Manual (user selectable) behaviors when you turn on Performance Mode in DaVinci
```
Resolve, or you can turn Performance Mode Off altogether. Set to Automatic, Performance mode
automatically optimizes a variety of operations in a bid to balance performance with the necessary
level of image quality, for fast onscreen performance while always maintaining the highest level of
quality for video output. Set to Manual, there are three different settings you can choose to disable
for instances where a particular performance tradeoff Resolve is making results in an undesirably
noticeable reduction in image quality in Performance Mode:
Optimized Sizing: Relates to how image resizing is handled.
Optimized Decode Quality: Relates to how clip resolution vs. timeline resolution is handled.
Optimized Image Processing: Relates to how image processing operations are handled.
Control Panels
The parameters in this panel let you customize the functionality of the DaVinci Control panels.
Panel Sensitivity
Lets you choose the orientation of red on the trackballs, how sensitive trackballs and rings are, and
how sensitive the qualifier knobs are.
 Classic DaVinci trackball alignment: When enabled, this checkbox sets all color balance controls
in DaVinci Resolve to the traditional orientation they’ve always used, which is close to, but not
exactly the same as, the vectorscope alignment of hues. When disabled, the alignment of color
balance controls is exactly the same as the vectorscope alignment of hues, which is similar to how
other color grading applications work. You should choose the mode you’re most familiar with.
121Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
 Grading style: Controls the orientation of the trackballs relative to the corrections they make.
There are two options:
```
DaVinci: Most users will be familiar with the standard DaVinci controls as this mimics the
```
```
vectorscope (how closely depends on the Classic DaVinci trackball alignment setting).
```
```
Rank: The Rank settings are somewhat different, so this option is for users who are familiar
```
with color controls that the Rank control system offered. In this mode, the orientation of red and
green are reversed.
```
 Lift RGB balance: Controls how quickly adjustments made to the Lift trackball (on the left) will
```
adjust the Lift Color Balance parameters in the Color page. This setting affects third-party panels.
```
 Lift master: Controls how quickly adjustments made to the Lift ring (surrounding the leftmost
```
```
trackball) will adjust the Lift Contrast parameter in the Color page. This setting affects
```
third-party panels.
 Gamma RGB balance: Controls how quickly adjustments made to the Gamma trackball
```
(second from the left) will adjust the Gamma Color Balance parameters in the Color page. This
```
setting affects third-party panels.
```
 Gamma master: Controls how quickly adjustments made to the Gamma ring (surrounding the
```
```
second trackball from the left) adjust the Gamma parameter in the Color page. This setting affects
```
third-party panels.
```
 Gain RGB balance: Controls how quickly adjustments made to the Gain trackball (third from
```
```
the left) will adjust the Gain Color Balance parameters in the Color page. This setting affects
```
third-party panels.
```
 Gain master: Controls how quickly adjustments made to the Gain ring (surrounding the third
```
```
trackball from the left) will adjust the Gain Contrast parameter in the Color page. This setting
```
affects third-party panels.
 Cursor offset: Controls how quickly adjustments made to the fourth trackball affect the cursor,
window position, log-mode offset, and other controls that can be manipulated via this trackball.
 Cursor master: Controls how quickly adjustments made to the fourth ring affect log-mode master
offset, and other controls that can be manipulated via this ring.
 Hue/Saturation/Luminance qualifier: Controls the sensitivity of the HSL panel control knobs.
 Jog: Controls the sensitivity of the jog wheel.
 Shuttle: Controls the sensitivity of the shuttle dial.
Display Settings
Lets you adjust the display of your Blackmagic Design control panels.
 LCD brightness: Controls the overall brightness of the DaVinci control panel displays.
 Key backlighting: Depending on which control panel you have selected, two controls let you
choose LCD Brightness and Key backlighting of the DaVinci Resolve Mini panel, or three controls
let you adjust the color balance of the lit buttons of the DaVinci Resolve Advanced control panel
```
(the default is red).
```
Metadata
The metadata panel lets you create custom sets of metadata parameters that will be exposed in the
Metadata Editor.
For more information on using this panel, see Chapter 19, “Using Clip Metadata.”
122Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Keyboard Customization
Choosing DaVinci Resolve > Keyboard Customization opens the standalone Keyboard Customization
window. This window lets you choose which set of keyboard shortcuts you want to use, discover which
keyboard shortcuts are available, or create your own custom keyboard mappings that more closely
adhere to the way you like to work, in whichever pages you find yourself working.
The Keyboard Customization window
Choosing Keyboard Shortcut Emulation Presets
Using a drop-down at the top right of this menu, you can choose the default DaVinci Resolve set or
any one of the other sets that attempt to mimic other NLEs you might be more familiar with. Please
note that keyboard shortcuts can only be remapped to commands that functionally exist within DaVinci
Resolve, so if a specific feature of another NLE does not have an equivalent in DaVinci Resolve, that
key shortcut may not be mapped in the same way. Fortunately, the editorial feature set of DaVinci
Resolve broadly overlaps with common features in other NLEs, so you should find that most features
you’re used to have a functional equivalent.
You can choose one of the preset keyboard mappings
to emulate another NLE you’re familiar with or the
default DaVinci Resolve keyboard mapping.
123Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
You also have the ability to create your own custom sets of keyboard shortcuts. The Commands list
below shows a hierarchical list of commands organized by the menu they appear within. This list lets
you select individual commands to remap and can be searched if you’re having a hard time finding
what you’re looking for. This is described in more detail later in this section.
Viewing Commands Assigned to Specific Key Combinations
To see what command a particular key of the keyboard is mapped to, you can click any combination of
modifier and other keys on the virtual keyboard at the top of this window. The currently selected keys
reveal how they’re mapped in the “Active Key” list below.
Selecting keys and modifiers on the virtual keyboard
displays their command mapping below
```
TIP: Starting in DaVinci Resolve 15.2, commands can have multiple keys or key combinations
```
assigned to them, and number keys on the numeric keypad of an extended keyboard can be
assigned independently from keys at the top of a keyboard.
Panel-Specific Keyboard Mappings
When customizing keyboard shortcuts, they can be assigned to the “Application” so that shortcut
works identically within every part of the DaVinci Resolve UI that’s applicable, or you can map a
particular keyboard shortcut to do a particular command within a specific panel.
Panel-specific keyboard shortcuts let you use a single key to do different things depending on which
```
panel has focus; for example, one key can do different things in the Media Pool, the Edit Timeline, the
```
Metadata Editor, and the Sound Library, to give a few Edit Page examples. This provides enormous
flexibility, but if you go this route, you need to be aware of which panel has focus. Fortunately, starting
in DaVinci Resolve 15.2, focus is indicated by a colored highlight at the top of each panel.
124Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Keyboard shortcuts can now be mapped to specific panels so that
different panels can use the same shortcut to accomplish different things
Searching for Keyboard Shortcuts
Whether you’re looking to see what keyboard shortcuts are available or looking for a particular
command you want to customize, a Search field above the Commands list is available for searching
```
whichever group of commands you want (including All Commands).
```
To search for specific keyboard shortcuts:
1 Choose DaVinci Resolve > Keyboard Customization.
2 Choose a command group from the Commands list to search within. If you want to search all of
DaVinci Resolve, choose “All Commands.”
3 Type a term into the Search field, and the Command/Keystroke list will update to show whatever
commands match the search criteria you’ve entered.
Selecting “All Commands” and searching for every keyboard
shortcut corresponding to the word “ripple”
125Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Managing Keyboard Mappings
DaVinci Resolve provides the following methods for creating and managing keyboard mappings in the
Option menu of the Keyboard Customization menu:
The Option menu of the Keyboard Customization window
lets you export, import, and delete keyboard mappings
 To create a new keyboard mapping: Choose a keyboard mapping from the drop-down to use as
your starting point, choose Save As New Preset from the Keyboard Customization Option menu,
then enter a preset name in the dialog, and click OK. That preset will now appear in the preset
drop-down menu.
 To export a keyboard shortcut file for use by another DaVinci Resolve workstation: Choose a
preset from the Export Preset submenu of the Keyboard Customization Option menu, then choose
a name and a location for the new file, and click Save.
 To import a keyboard shortcut file: Choose Import Preset from the Keyboard Customization
Option menu, choose a DaVinci Resolve keyboard shortcut file, and click Open.
 To delete a keyboard mapping: Choose a keyboard mapping preset you want to delete, then click
the trash can button.
Remapping a Command to One or More Keys
Changing the keyboard mapping for any given command is easy. You can even map a single
command to multiple keys, if necessary. In DaVinci Resolve, actions can be application-wide or
specific to Media Pool, or Timeline, or other panels. The right column in the key customization dialog
shows application-level and panel-level actions. When a panel is in focus, hotkeys prioritize panel-
local actions. This allows you to reuse the same key shortcut in the application level and within each
panel at the same time.
To change the keyboard shortcut for a particular command:
1 Find the command you want to remap in the Commands list by selecting a category. If necessary,
use the Search field. Whether a command is mapped generally to the entire application or
specifically to a particular panel depends on what you’ve selected from the list.
```
a) If you want the keyboard character you plan to map to work application-wide, choose a menu
```
name from underneath the Application category of the Commands list. Each menu shows all
commands associated with it and can be individually searched.
```
b) If you want the keyboard character you plan to map to this command to be specific to a
```
particular panel, then choose one from the Panels category underneath. Each panel shows all
commands associated with it and can be individually searched.
126Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
2 Click within the Keystroke column of the list, to the right of the command, and when a selection
appears type a new character using any combination of modifier keys you like.
Clicking to select a keyboard shortcut you want to modify
Please note that if you remap a key that was already assigned to another command, you’ll see a
warning that the key you’re about to remap is already assigned to another command, giving you a
chance to cancel and change key assignments if you like.
The warning you see if you try to map the same key to multiple commands
You can override the warning and make the assignment, but having the same character or
combination applied to multiple commands can cause problems, so a warning badge appears
next to affected commands. Clicking on this badge makes it easy to see where the duplicate is by
highlighting the keys on the keyboard, so you can remap one or the other command as necessary.
To resolve a shortcut conflict:
 Click the yellow warning icon next to the action. This shows all actions for that hotkey
in the left panel.
 Click on the other conflicting actions at the same level to reveal them in the right pane.
 Change or unset these values so as not to conflict with your new key assignment.
127Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
```
3 (Optional) You also have the option of assigning multiple keyboard shortcuts to a single command.
```
For example, if you want to use keys on the numeric keypad of an extended keyboard in addition
to other keys for a particular command, you can now set this up by clicking the “plus” button to the
right of a currently assigned keyboard shortcut. This makes another highlight appear, within which
you can type any secondary character or combination you like to make the additional assignment.
You can do this as many times as you like. When you’re done, all keyboard shortcuts applied to
that command appear, separated by commas.
You can map multiple keys to the same command, if necessary
4 When you’re finished changing keyboard shortcuts, click the Save button at the bottom right of the
Keyboard Mapping list, and then click Close to close the window.
For example, if you set ‘Option-G’ to:
```
a) The Media Pool-specific Clip Attributes,
```
```
b) The application-wide Mark > Add Flag > Green to ‘Option-G’.
```
When you are focused on the Media Pool, you cannot add green flags with a hotkey. You will need
to manually add them via the Mark menu.
In addition, the application-wide Color > Nodes > Add serial node with polygon power window
```
also has the same hotkey (Option-G), so action b will cause the the key customization dialog to
```
show a warning with the conflicting action name and display an icon on both actions.
```
If you save this state as a preset (with conflicts), DaVinci Resolve will still try to parse your shortcuts
```
```
logically. For example, on the Edit and Fairlight timelines, Option-G adds a green flag (as color
```
```
node actions are not applicable). But in the Color page, Option-G can refer to both actions and the
```
user needs to resolve the conflict to make the action work correctly.
128Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
DaVinci Resolve Extras Download Manager
As DaVinci Resolve evolves to incorporate more AI-based models, there is a tradeoff in application file
size. These AI models tend to be large datasets that not all users will want or need to use. To help with
this decision, DaVinci Resolve has the Extras Download Manager, allowing you to pick and choose
which optional functionality you want to add to DaVinci Resolve.
The Extras Download Manager can be found at DaVinci Resolve > Extras Download Manager.
The Extras Download Manager
To use the Extras Download Manager, simply view the packages available and select download.
You can remove a package in the same interface by clicking on the trashcan icon next to the package
name. Downloads will happen in the background while you continue to work. From time to time these
packages will be updated, and you will be notified here if your current package is out of date.
Currently, the Download Manager contains packages for AI Voice Training and Extended AI
Transcription Support Languages.
129Setup and Workflows | Chapter 4 System and User Preferences
MEDIA
Chapter 5
DaVinci Control
Panels Setup
There are several hardware control interfaces that are dedicated to more efficient
workflows for specific pages in DaVinci Resolve. The DaVinci Control Panels Setup
app is where you connect and configure these hardware interfaces.
Contents
DaVinci Control Panels Setup 131
DaVinci Control Panels Setup Layout  131
Using DaVinci Control Panels Setup  132
Firmware 133
Ethernet Connection  134
Settings  134
Connected Control Panels Popup  136
130Setup and Workflows | Chapter 5 DaVinci Control Panels Setup
MEDIA
DaVinci Control Panels Setup
DaVinci Resolve has many different hardware interfaces designed to increase your efficiency when
working within certain pages. Specialized keyboards, color control surfaces, and audio mixing panels
can be connected to your system, and the DaVinci Control Panels Setup is where you configure
these devices.
The DaVinci Control Panels Setup utility is a separate application automatically installed alongside
DaVinci Resolve. You can access this program directly from within DaVinci Resolve by choosing
Help > DaVinci Control Panels Setup, or you can launch the program from the DaVinci Resolve folder
in your OS.
Make sure your hardware is connected and powered on before launching the application.
The DaVinci Control Panels Setup icon
DaVinci Control Panels Setup Layout
When you launch DaVinci Control Panels Setup, you will be presented with an interface showing you
the detected hardware device on your system. If you have multiple hardware devices, you can scroll
through them by clicking on the Left and Right Arrows on the sides of the window. If no devices are
detected, the interface will tell you “No DaVinci control panels found.”
The DaVinci Control Panels Setup window showing a
DaVinci Editor Keyboard attached. The two dots below and the
triangle to the right show another device connected as well.
131Setup and Workflows | Chapter 5 DaVinci Control Panels Setup
MEDIA
The DaVinci Control Panels Setup showing no detected hardware
Using DaVinci Control Panels Setup
The DaVinci Control Panels Setup presents a simple interface to connect to your devices, update their
firmware, and modify their settings.
The DaVinci Control Panels Setup showing the
Fairlight Desktop Console attached
132Setup and Workflows | Chapter 5 DaVinci Control Panels Setup
MEDIA
Firmware
On startup, the DaVinci Control Panels Setup application will automatically check for any possible
firmware updates for your device from the Blackmagic Design servers. If the application finds a newer
firmware version it will ask you if you wish to update your device, or cancel and remain on your current
firmware version. When updating it’s important not to unplug or power-down the device during the
process as that can cause firmware corruption. Firmware updates include bug fixes and are required,
in some cases, to use your device with new features in DaVinci Resolve. It is recommended to always
update your device to the latest firmware unless you have a specific reason not to.
The firmware update dialog box
The firmware updating
133Setup and Workflows | Chapter 5 DaVinci Control Panels Setup
MEDIA
Ethernet Connection
If you are connecting your device via Ethernet, you may need to enter its IP address before it can be
configured in DaVinci Control Panels Setup. To do so, click on the “+” icon in the lower left corner of
the interface. An Add DaVinci Control Panel window will appear, allowing you to type in the device’s IP
address. The device must be on the same Ethernet network as the computer you’re connecting it to.
You can manually add an Ethernet-connected device by typing in its IP address.
Settings
You can access your device’s settings by clicking on the setup icon directly below your device.
Different hardware devices will have different settings, but generally they will be broken down into the
following categories:
Setup
```
Name: You can set a specific name for your hardware device to differentiate it in the interface and
```
bluetooth selection preferences.
```
Software: The current firmware version of the device.
```
Network
If your device has an ethernet connection, you can set up its networking settings. If you are new to
networking, it is suggested that you leave the Protocol setting to DHCP, and let the computer figure
it out. If you are part of a larger facility, you may want to consult with your IT department for the
appropriate manual settings instead.
```
Protocol: Choose whether you want the device’s IP address to be set automatically by DHCP or to
```
provide your own manual static IP address below.
IP Address: You can manually assign the IP address for the device.
Subnet Mask: You can manually assign the Subnet Mask for the device.
```
Gateway: You can manually assign the Gateway address for the device.
```
134Setup and Workflows | Chapter 5 DaVinci Control Panels Setup
MEDIA
Reset
Factory Reset: Resets your device back to the factory defaults. This maybe useful in some
troubleshooting situations.
The DaVinci Control Panels Setup showing
the DaVinci Resolve Mini Panel attached
The Settings for the DaVinci Resolve Mini Panel
135Setup and Workflows | Chapter 5 DaVinci Control Panels Setup
MEDIA
Connected Control Panels Popup
In the lower-right corner of the DaVinci Resolve interface, you will find a Control Panels popup box.
Clicking on this icon shows you all currently connected control panels, how they are connected, and
their battery status.
The Control Panels popup
136Setup and Workflows | Chapter 5 DaVinci Control Panels Setup
MEDIA
Chapter 6
Project Settings
This chapter covers the settings used for defining the properties of each individual
project. It’s a good idea to familiarize yourself with the information in this chapter
prior to setting up your first project.
Contents
What Are the Project Settings?  138
Opening and Editing Project Settings  138
Presets  139
Master Settings  141
Timeline Format  141
Video Monitoring  143
Optimized Media and Render Cache  144
Working Folders  145
Frame Interpolation 146
Image Scaling  147
Image Scaling  147
Input Scaling  148
Output Scaling 148
Color Management  149
Color Space and Transforms  149
Dolby Vision™  150
HDR10+  151
HDR Vivid 151
Lookup Tables  151
Broadcast Safe  153
General Options  154
Conform Options  154
Color  156
Dynamics Profile 157
Versions  158
Camera Raw  158
Capture and Playback  159
Deck Settings 159
Capture  160
Playout 160
Subtitles and Transcription  161
Fusion  161
Fairlight  162
Timeline Sample Rate  162
Bussing 162
Audio Metering 162
Path Mapping  163
Project Media Locations  164
137Setup and Workflows | Chapter 6 Project Settings
MEDIA
What Are the Project Settings?
The Project Settings window contains all project-specific parameters that are saved along
with that project. These include essential project properties such as the timeline format, video
monitoring settings, how to optimize media, and where to save cache files. It also includes image
scaling properties, color management settings, and many other properties that affect projects in
fundamental ways.
Opening and Editing Project Settings
All of these project-specific settings are easily accessed from anywhere in DaVinci Resolve by clicking
the gear button at the bottom right of the page bar.
Project Manager and Project
Settings buttons
The Project Settings window opens in the middle of the screen.
Project Settings window
138Setup and Workflows | Chapter 6 Project Settings
MEDIA
The Project Settings window is divided into a series of panels which can be selected from a sidebar
at the left. Each panel contains a collection of related settings that affects some category of DaVinci
Resolve functionality.
To alter project settings:
1 Click on the name of any group of settings in the sidebar at the left to open that panel.
2 Change whatever settings you need to change.
3 Do one of the following to apply your changes:
Click Save to apply the changes you’ve made and close the Project Settings.
Option-click Save to apply the changes you’ve made and keep the Project Settings window open,
so you can make other changes. This option is available because it’s sometimes necessary to
keep the Project Settings window open as you continue making changes that may visibly affect
the clips and timelines in your project.
Presets
The Presets menu lets you save customized collections of Project Settings for future recall. Presets
can save the state of nearly every parameter and setting in every panel of the Project Settings
window, and make it easy to switch among different setups for different tasks, or to accommodate
different types of projects.
```
The Presets menu is accessed by clicking on the option menu (three dots) in the upper-right corner of
```
the Project Settings window. The Presets menu shows the following items:
Project Settings Presets: The list of all current Project Presets is shown here, headed by the
Default Preset.
Set Current Settings as Default Preset: This option saves the current Project Settings as the new
Default Preset.
Save Current Settings as Preset: This option allows you to save the current Project Settings as a
new preset that will show up in the menu list above.
Import Preset: This option will open a file browser to let you import a DaVinci Resolve Project
Settings Preset file. The extension for these files is .preset.
You can use this menu to create, import, and export your own presets, adding as many as you need to
accommodate the types of projects you work on.
The Presets Menu is accessed by clicking on the option
menu of the Project Settings window
139Setup and Workflows | Chapter 6 Project Settings
MEDIA
To create a new preset:
1 Do one of the following:
 Right-click a project in the Project Manager, and choose Project Settings from the
contextual menu.
 Open any project, then open the Project Settings.
2 Use the different panels of the Project Settings window to alter whichever settings you need to.
```
There’s no need to save your changes as you go; you’ll save them all at once later.
```
```
3 Click on the option menu (three dots) in the upper right-hand corner of the Project
```
Settings window.
4 Select Save Current Settings as Preset.
5 Enter a descriptive name for your new preset in the dialog box, and press the OK button.
6 Your new preset name will now appear in the Project Settings Preset menu.
Once you’ve created one or more custom presets, you can load them into a project at any time.
To load a preset’s settings into a project:
1 Open a project with a preset you want to update.
2 Open the Project Settings window.
3 Click on the option menu in the Project Settings window.
4 Click on the Project Preset name you want to use for the open project.
5 Select Load Preset from the drop-down menu.
The Project Settings will be updated to the new preset immediately. There is no undo for this function.
To update a preset:
1 Open the Project Settings window.
2 Use the different panels of the Project Settings window to alter whichever settings you need
to update.
3 Click on the option menu in the Project Settings window.
4 Click on the Project Preset name you want to update.
5 Select Update Preset from the drop-down menu, and select Update from the dialog box.
The preset will be replaced with your current settings. There is no undo for this function.
To set the default preset:
1 Select the preset from the Project Settings Presets list you want to be loaded each time you make
a new project.
2 Click on the preset and select Set As Default Preset.
or
1 Select “Set Current Settings as Default Preset” from the option menu of the Project Settings
window to make whatever your project settings are currently the new default preset.
2 Select Update from the dialog box.
The preset will be replaced with your current settings. There is no undo for this function.
140Setup and Workflows | Chapter 6 Project Settings
MEDIA
To export a preset:
1 Click on the preset from the Project Settings Presets list you want to export.
2 Choose Export Preset from the drop-down menu.
3 Enter a name for the preset and where you want to save it in the file browser, and press Save.
The DaVinci Resolve Project Settings Preset file will export to that destination with a
“.preset” extension.
To import a preset:
1 Click on the option menu in the Project Settings window.
2 Select Import Preset.
3 Navigate the file browser to the DaVinci Resolve Project Settings Preset file you wish to import.
The file will have a “.preset” extension. Press Open.
To delete a preset:
1 Click on the preset from the Project Settings Presets list you want to delete.
2 Choose Delete Preset from the drop-down menu.
3 Press Delete in the dialog box.
The Project Settings will be deleted immediately. There is no undo for this function.
Master Settings
This panel is project specific and lets you set up and adjust the most essential properties of the
timelines in your project, including the timeline format, video monitoring method, and conform options.
In many workflows, you’ll want to adjust these settings before getting started with your project.
By default, all timelines use these project-wide settings. However, beginning with DaVinci Resolve
16, you can optionally create timelines with individual Format, Monitoring, and Output Sizing settings.
However, if you change a timeline to use “Basic Settings,” then that timeline will mirror the project-wide
options that are selected in the Project Settings.
Timeline Format
This group of settings affects the geometry and image processing of the current project.
 Timeline resolution: A drop-down menu that lets you choose a frame resolution preset to use
for image processing while grading. DaVinci Resolve is resolution independent, so you can
change the resolution at any time and all windows, tracks, sizing changes, and keyframe data will
be automatically recalculated to fit the new size. For example, you can work on a 4K project while
monitoring at HD resolutions if your room is only set up with an HD monitor, and then render the
finished project at 4K resolution for final delivery. Alternately, you can downsize an HD project to
an SD resolution to create another set of deliverables.
For more information on Resolve’s resolution independence, see Chapter 152, “Sizing and
Image Stabilization.””
```
 Frame size (Labeled “For X x Y processing”): Lets you set resolutions not found in the
```
“Timeline resolution” drop-down menu.
141Setup and Workflows | Chapter 6 Project Settings
MEDIA
 Use vertical resolution: This checkbox swaps the horizontal and vertical pixels of the Timeline
resolution. This lets you format your timeline vertically for display on smart phones, tablets, or
televisions that are in an upright configuration for digital signage.
 Pixel aspect ratio: Used to select PAR settings for image formats that don’t use the default
square pixel format. You can apply a 16:9 anamorphic PAR, a 4:3 PAR for SD projects, or a
Cinemascope ratio.
 Timeline frame rate: Determines the primary frame rate used by the project. A variety of standard
```
and high frame rate (HFR) settings are available. If you’re importing an AAF or XML file, this setting
```
is automatically set via an option in the Project Import dialog. Ideally, you should choose a frame
rate before importing media into the Media Pool. However, the first time you import media into an
empty Media Pool, you’re prompted if the incoming media frame rate doesn’t match the Timeline
frame rate set here, and you have the option of automatically updating this setting to match that
of the media you’re importing. Once one or more files have been added to the Media Pool, this
setting cannot be changed.
 Use drop frame timecode: Enables or disables drop frame timecode for the current project.
Off by default.
 Enable interlace processing: Interlaced media is supported throughout DaVinci Resolve. The
“Enable interlace processing” checkbox forces DaVinci Resolve to process all operations internally
using separated fields, in order to properly maintain the field integrity of interlaced clips in your
program. In addition, each clip in the Media Pool has a Field Dominance drop-down menu in the
Video panel of the Clip Attributes window that lets you specify whether clips are upper- or lower-
```
field dominant; an Auto setting makes this choice by default.
```
There is also a corresponding checkbox in the Render Settings panel of the Deliver page,
named “Field rendering,” that lets you enable and disable field rendering when you’re rendering
file-based output.
There are two instances where you want to leave this setting turned off:
• If you’re working with progressive-frame media, it is not necessary to turn this checkbox
on. Doing so will unnecessarily increase processing time.
• If you’re using interlaced clips in a progressive-frame project and you’re intending to
deinterlace those clips using the Enable Deinterlacing checkbox in the Clip Attributes
window, then you must keep “Enable video field processing” off. Otherwise, the Enable
Deinterlacing checkbox will be disabled for all clips.
For more information about deinterlacing clips, see Chapter 22, “Modifying Clips and Clip
Attributes.”
If you’re working on a project with interlaced media that you intend to keep interlaced, then
whether or not it’s necessary to turn field processing on depends on what types of corrections
you’re applying to your clips. If you’re mastering your program to an interlaced format, and you’re
applying any adjustments that would cause pixels from one field to move or bleed into adjacent
```
fields, then field processing should be enabled; effects requiring field processing include filtering
```
operations such as blur, sharpen, and OpenFX operations, as well as sizing transforms that include
pan, tilt, zoom, rotate, pitch, and yaw.
On the other hand, regardless of whether you’re outputting interlaced or progressive-frame media,
if you’re not filtering or resizing your clips, and you’re only applying adjustments to color and
contrast, it’s not necessary to turn on field processing for interlaced material, and in fact, leaving it
off may somewhat shorten your project’s rendering time.
142Setup and Workflows | Chapter 6 Project Settings
MEDIA
 Align Clips to Frame Boundaries: When working with interlaced material, you can chose whether
to perform edits at the field or frame boundaries. When checked this means all editing actions
and playhead stepping will occur at full frame boundaries. This works independently of the audio
subframe controls, so it’s still possible to get perfect audio sync while working with video at the
frame level. When unchecked, all editing actions and playhead stepping will be performed at the
field boundary instead.
```
 Playback frame rate: Usually mirrors the frame rate selected in the “Video format” setting (in the
```
```
Video Monitoring section below), which is typically based on the frame rate of the external display
```
that’s connected to your video interface, given the “Timeline Frame Rate” setting. For example,
a 50Hz monitor requires a 25 fps playback frame rate for synchronous display without dropped
frames. If you want to monitor playback at a slower frame rate, type the frame rate of your choice
in this field and DaVinci Resolve will make the appropriate calculations to drop or repeat frames as
necessary to match it. This can be useful for temporarily seeing how clips look in slow motion.
Video Monitoring
The settings available in this group control the signal that’s output by the video output interface that’s
connected to your workstation, and let you specify what standard of signal is output, and via which
signal path.
By default the frame size and frame rate match those in the Timeline resolution and Playback frame
rate options. However, if necessary you can change these settings to match those of the external
display you’re using to monitor your work. For example, if you’re working with 2K files for 2K output,
but you’re color correcting using a high definition monitor set to 1080 resolution, you can select the
appropriate HD standard for that monitor without changing the Timeline Resolution settings.
 Video Resolution: Lets you choose a standard video frame size to be output via your connected
video output interface.
 Format: Lets you choose a standard video frame rate to be output via your connected video
output interface.
 Video connection checkboxes: Lets you choose the signal standard to output from your
connected video output interface to the video monitor. Make sure to choose a standard that’s
supported by both your video interface and your monitor.
The options are:
Use 1080PsF: Output progressive video in 1080i format for older HDTV sets.
Use 4:4:4 SDI: A signal path for monitoring image data to monitors that supports 4:4:4
chroma sampling, typically over SDI connections.
Use Level A for 3Gb SDI output: A signal path for monitoring image data via a
single 3 Gb/s SDI connection.
Use dual outputs on SDI output: All DaVinci Resolve systems can generate a side-by-side
display that can be sent to a Stereoscopic monitor via the HD-SDI output of an UltraStudio 4K
or DeckLink card. When dual SDI 3D monitoring is enabled, each eye is output separately at full
resolution. In this mode, split-screen wipes and cursors will not be visible on the grading monitor.
 SDI Configuration: Lets you choose from among Single Link, Dual Link, and Quad Link SDI,
depending on what your display supports.
 Data Levels: This setting only affects the data levels being output via the video interface that
connects the DaVinci Resolve workstation to your external display. It has no effect on the data
that’s processed internally by DaVinci Resolve, or on the files written when you render in the
Deliver page. It is imperative that the option you choose in DaVinci Resolve matches the data
range to which your external display is set. Otherwise, the video signal will appear to be incorrect,
even though the internal data is being processed accurately by DaVinci Resolve.
143Setup and Workflows | Chapter 6 Project Settings
MEDIA
There are two options:
```
Video: This is the correct option to use when using a broadcast display set to the
```
Rec. 709 video standard.
```
Full: If your monitor or projector is capable of displaying “full range” video signals, and you wish to
```
```
monitor the full 10-bit data range (0–1023) while you work, this is the correct option to use.
```
For more information about data levels, see Chapter 9, “Data Levels, Color
Management, and ACES.”
 Retain sub-black and super-white data: Turning this checkbox on lets DaVinci Resolve output the
```
undershoots (sub-black) and overshoots (super-white) within the headroom of video encoded data
```
levels to video. When this is turned off, these out-of-bounds values are clipped in video output.
 Video bit depth: Choose the bit depth that corresponds to the capability of your display. You can
choose between 8-bit and 10-bit. Monitoring in 10-bit is more processor intensive, but preferable
to avoid the appearance of banding that may not in fact be in the image data being processed by
DaVinci Resolve.
 Monitor scaling: Defaults to basic, and is only enabled to smooth the edges of video being viewed
on a projector with very large screens. These settings minimize high frequency artifacts that may
be seen. This may also be noticeable if you have a 2K or HD project but are monitoring on an SD
monitor. The other option, Bilinear, has different effects on the monitored image depending on
your display device, so you may need to check to verify that it’s appropriate for your environment.
 Use Rec601 Matrix for 4:2:2 SDI output: Don’t use this checkbox unless you know what it does.
You know who you are.
```
 Enable HDR metadata: (only available in Studio version) Turning on this checkbox outputs the
```
metadata necessary to send High Dynamic Range signals over HDMI 2.0a and have it be correctly
decoded by an HDR-aware video display. When this checkbox is enabled, it’s recommended to
also enable the “HDR mastering is for X nits” checkbox in the Color Management page, and set
```
the “nit” level (slang for cd/m2) to whatever peak luminance level your HDMI connected HDR
```
display is capable of.
Optimized Media and Render Cache
These settings govern the resolution and codec of optimized media that DaVinci Resolve can
generate in order to facilitate greater real time performance, as well as cached media that’s generated
by the Smart and User Cache.
 Proxy media resolution: A drop-down list lets you choose whether to generate proxy media
at each clip’s Original size, or at Half, Quarter, One-Eighth, or One-Sixteenth the resolution of
the original media, or allow DaVinci Resolve to choose this automatically for you based on your
timeline settings.
 Proxy media format: Specifies the format in which proxy media files will be written. You can
choose from among a variety of Uncompressed, ProRes, and DNxHD formats, depending on
your requirements.
 Optimized media resolution: A drop-down list lets you choose whether to generate optimized
media at each clip’s Original size, or at Half, Quarter, One-Eighth, or One-Sixteenth the resolution
of the original media, or allow DaVinci Resolve to choose this automatically for you based on your
timeline settings.
 Optimized media format: Specifies the format in which optimized media files will be written.
You can choose from among a variety of Uncompressed, ProRes, and DNxHD formats, depending
on your requirements.
144Setup and Workflows | Chapter 6 Project Settings
MEDIA
 Render cache format: Specifies the format in which render cache files will be written. You
can choose from among a variety of Uncompressed, ProRes, and DNxHD formats, depending
on your requirements.
 Enable background caching after X seconds: Specifies the duration of inactivity after which
automatic background caching will begin.
A series of checkboxes let you force specific types of effects to be cached when you use the
User Cache, which is a more selective manner of caching than the Smart Cache. These include:
Automatically cache transitions in user mode: If you’re using User mode and you find that your
workstation does not have adequate performance to play transition effects in real time, you can
force these categories of effects to be automatically included in the Sequence Cache and cached
when you’re using the User mode of caching.
Automatically cache composites in user mode: If you’re using User mode and you find that your
workstation does not have adequate performance to play composite mode or opacity effects in
real time, you can force these categories of effects to be automatically included in the Sequence
Cache and cached when you’re using the User mode of caching.
Automatically cache Fusion effects in user mode: If you’ve created effects for a clip in the Fusion
page and you find that your workstation does not have adequate performance to play that clip in
real time, you can force these categories of effects to be automatically included in the Sequence
Cache and cached when you’re using the User mode of caching.
Working Folders
These fields let you specify to which folders cache and gallery files are written.
 Project media location: Lets you choose a specific folder on your system to hold all generated
media created for that project. Generated media includes things like new audio files created from
the Voiceover tool and Voice Convert, or essentially any type of new media created by DaVinci
Resolve itself. This allows you to make sure all the media for a project is in one common location,
making it easier to hand off, move or relink media, rather than have some media in DaVinci
Resolve’s internal file structure and some on a media drive. DaVinci Resolve will automatically
create new subfolders at your chosen media location based on media type, which makes it easy to
send some or all generated media to another location.
You can also set this location in the Create New Project dialog when creating a new project.
Inside the project media location,
DaVinci Resolve will create subfolders
automatically to organize any media
generated from within the program.
 Proxy generation location: All proxy media files that you create are saved in the directory path
specified by this field.
 Cache files location: All render cache files that you create are saved in the directory path
specified by this field. This path defaults to a hidden “CacheClip” directory that’s created at the
location of the first Media Storage Volume you specify in the DaVinci Resolve Preferences window.
145Setup and Workflows | Chapter 6 Project Settings
MEDIA
 Gallery stills location: By default, all stills you save are saved in the DPX format, and are placed
in the directory path specified by this field. This path defaults to a hidden “.gallery” directory
that’s created at the location of the first Media Storage Volume you specify in the DaVinci Resolve
Preferences window.
```
NOTE: If the volume you’ve selected to use for the cache becomes unavailable, DaVinci
```
Resolve will warn you with a dialog.
Frame Interpolation
These settings determine the default state for all retiming and speed change effects, including when
clips are in mixed frame rate timelines.
 Retime Process: This drop-down menu lets you choose a default method of processing clips
that don’t match the project frame rate in mixed frame rate timelines and clips with speed effects
```
(fast forward or slow motion) applied to them, throughout the project. Since each clip in every
```
timeline defaults to “Project Settings,” changing this setting will change the way most mixed frame
rate and speed effected clips will be processed, except for those with custom settings selected.
There are three options:
```
Nearest: The most processor efficient and least sophisticated method of processing; frames are
```
either dropped for fast motion, or duplicated for slow motion.
```
Frame Blend: Also processor efficient, but can produce smoother results; adjacent duplicated
```
frames are dissolved together to smooth out slow or fast motion effects. This option can provide
better results when Optical Flow displays unwanted artifacts.
Optical Flow: The most processor intensive, but highest quality method of speed effect
processing. Using motion estimation, new frames are generated from the original source frames
to create slow or fast motion effects. The result can be exceptionally smooth when motion in a clip
is linear. However, two moving elements crossing in different directions or unpredictable camera
movement can cause unwanted artifacts.
 Motion estimation mode: When using mixed frame rate clips in a timeline that has Optical Flow
retiming enabled, when using Optical Flow to process speed change effects, or when using Image
Stabilization or Temporal Noise Reduction controls in the Color page, the Motion Estimation drop-
```
down of the Master Settings (in the Project Settings window) lets you choose options that control
```
the trade-off between speed and quality.
There are additional “Enhanced” Optical Flow settings available in the “Motion estimation mode”
drop-down in the Master Settings panel of the Project Settings. The “Standard Faster” and
“Standard Better” settings are the same options that have been available in previous versions
of DaVinci Resolve. They’re more processor-efficient and yield good quality that are suitable for
most situations. However, “Enhanced Faster” and “Enhanced Better” should yield superior results
in nearly every case where the standard options exhibit artifacts, at the expense of being more
computationally intensive, and thus slower on most systems.
“Speed Warp Faster” and “Speed Warp Better” are available for even higher-quality slow motion
effects using the DaVinci Neural Engine. Your results with this setting will vary according to the
content of the clip, but in ideal circumstances this will yield higher visual quality with fewer artifacts
than even the Enhanced Better setting.
146Setup and Workflows | Chapter 6 Project Settings
MEDIA
New improved Motion estimation mode settings in
the Master Settings panel of the Project Settings
 Motion range: When using mixed frame rate clips in a timeline that has Optical Flow retiming
selected, or when using Optical Flow to process speed change effects, this drop-down menu lets
you choose the default setting to use, small, medium or large motion, for all speed and motion
related calculations so you can try and improve the result by matching the type of motion in the
source media. This setting can also be changed on a clip by clip basis in the Edit page Inspector.
Image Scaling
The Image Scaling panel contains settings that determine how and when clips are resized for
various reasons.
Image Scaling
These settings affect the methods used to resize clips in various situations.
 Resize Filter: The first group of settings lets you choose the filter method used to interpolate
image pixels when resizing clips:
```
Smoother: May provide higher quality for projects using clips that must be scaled down to fit an
```
SD resolution frame size.
```
Bicubic: While the Sharper and Smoother options are slightly higher quality, Bicubic is still an
```
exceptionally good resizing filter and is less processor intensive than either of those options.
```
Bilinear: A lower quality setting that is less processor intensive. Useful for previewing your work
```
on a low-performance computer before rendering, when you can switch to one of the higher
quality options.
```
Sharper: Usually provides the best quality in projects using clips that must be scaled up to fill a
```
larger frame size or scaled down to HD resolutions.
```
Custom: This setting lets you take control of the exact algorithm used in all resizing operations.
```
The custom Resize Filter options available are: Bessel, Box, Catmul-Rom, Cubic, Gaussian,
Lanczos, Mitchell, Nearest Neighbor, Quadratic, and Sinc. In practice, the difference between
these methods can be quite subjective. However, if you need to match a specific resizing method
used from another application, you can do it here. For everyday use, the normal resizing filters in
DaVinci Resolve should be sufficient.
 Override input scaling: Checking this box lets you choose an Input Sizing preset to
apply to the project.
 Override output scaling: Checking this box lets you choose an Output Sizing preset to
apply to the project.
147Setup and Workflows | Chapter 6 Project Settings
MEDIA
 Anti-alias edges: A second group of settings lets you choose how to handle edge anti-aliasing for
source blanking.
```
Auto: Adds anti-aliasing when any of the Sizing controls are used to transform the image.
```
Otherwise, anti-aliasing is disabled.
```
On: Forces anti-aliasing on at all times.
```
```
Off: Disables anti-aliasing. It might be necessary to turn anti-aliasing off if you notice black blurring
```
at the edges of blanking being applied to an image.
```
 Deinterlace quality: (only available in Studio version) A fourth group of settings lets you choose
```
the quality/processing time tradeoff when deinterlacing Media Pool clips using the Enable
Deinterlacing checkbox in the Clip Attributes window.
There are three settings:
```
Normal: A high-quality deinterlacing method that is suitable for most clips. For many clips, Normal
```
is indistinguishable from High. Normal is always used automatically during playback in Resolve.
```
High: A more processor-intensive method that can sometimes yield better results, depending on
```
the footage, at the expense of slower rendering times.
DaVinci Neural Engine: This option uses the advanced machine learning algorithms of the DaVinci
Neural Engine to analyze motion between the fields of interlaced material and reconstructs them
into a single frame. This option is very computationally intensive but, ideally, will deliver an even
more aesthetically pleasing result than the “high” setting.
Input Scaling
Contains one setting, Mismatched resolution files, that lets you choose how clips that don’t match the
current project resolution are handled. There are four options:
 Center crop with no resizing: Clips of differing resolution are not scaled at all. Clips that are
smaller than the current frame size are surrounded by blanking, and clips that are larger than the
current frame size are cropped.
 Scale full frame with crop: Clips of differing resolution are scaled so that the clip’s shortest
dimension is fit to match the frame. Excess pixels are cropped.
 Scale entire image to fit: The default setting. Clips of differing resolution are scaled so that the
clip’s longest dimension is fit to match the frame. The shorter dimension has blanking inserted
```
(letterboxing or pillarboxing).
```
 Stretch frame to all corners: Useful for projects using anamorphic media. Clips of differing
resolutions are squished or stretched to match the frame size in all dimensions. This way,
anamorphic media can be stretched to match full raster, or full raster media can be squished
to fit into an anamorphic frame. An added benefit of this setting is that it makes it easy to mix
anamorphic and non-anamorphic clips in the same project.
Output Scaling
These settings let you optionally choose a different resolution to be output via your video output
interface, for monitoring, outputting to tape, or rendering. In particular, if you set the resolution in
the Render Settings list of the Deliver page to something other than the Timeline Resolution, these
```
settings are used to make the change (for example, if you’re rendering a downconversion of the
```
```
current timeline). This can be used in situations where you’re working on a high resolution 4K project,
```
but you want to monitor using an HD display and output HD resolution media for approval.
 Match timeline settings: Turned on by default, so that these settings mirror the Timeline
Resolution, Image Scaling, and Input Image Scaling settings described above. Turning this
checkbox off lets you choose different settings for monitoring, outputting to tape, or rendering,
using the other settings in this group.
148Setup and Workflows | Chapter 6 Project Settings
MEDIA
 Output resolution: Lets you choose an alternate resolution.
 For: Lets you specify a different custom alternate resolution.
 Pixel aspect ratio: Lets you specify an alternate pixel aspect ratio to match the alternate
timeline format.
 Mismatched resolution files: Lets you choose an alternate way of handling mismatched resolution
files given the alternate resolution you’ve chosen. These options work identically to those of the
“Input Image Scaling” group.
 Super Scale: Sets a very processor-intensive and high quality upscaling algorithm that actually
creates new pixels for the resized image. The possible values are: None, 2-3-4x, 2-3-4x Enhanced,
and Auto. For more information on Super Scale, see Chapter 11, “Image Sizing and Resolution
Independence.”
For more information on Super Scale, see Chapter 11, “Image Sizing and Resolution
Independence.”
Color Management
The various options found in the Color Management panel let you configure DaVinci Color
```
Management (RCM) or ACES if you have either enabled, and they also allow you to pre- or post-
```
process the DaVinci Resolve image processing pipeline using LUTs and Broadcast Safe settings, in
order to accommodate a wide range of different color workflows.
Color Space and Transforms
If you choose DaVinci YRGB Color Managed or ACES in the Color Science menu at the top, then the
other drop-down menus in this section become enabled.
For more information about DaVinci Resolve Color Management and ACES, see Chapter 9,
“Data Levels, Color Management, and ACES.” If you’re new to color or color management,
you’re strongly recommended to read this chapter.
```
If you choose to use Resolve Color Management (RCM), ACEScc, or ACEScct, the settings in this
```
panel give you extensive control over how color is transformed, starting with choosing the default
```
color settings for the source media in your project (via the Input Color Space), through choosing how
```
```
you want your grading controls in DaVinci Resolve to behave (via the Timeline Color Space), and then
```
```
specifying how the final color will look on your monitor and output device (via the Output Color Space).
```
 Color science: There are four options that let you choose whether to work with manual or
automated color management.
DaVinci YRGB color science: DaVinci Resolve’s original color science, in which you manage
all and any color transforms from one color space to another manually, using either LUTs or
manual adjustments.
```
DaVinci YRGB Color Managed: Enables the Resolve color-managed workflow (RCM) for grading.
```
DaVinci ACEScc or ACEScct: Both of these are standardized color management schemes that
are available for facilities using ACES workflows. Of the available settings, ACEScct is the most
intuitive way of working for most colorists, as it handles the lifting of shadows in a creatively
useful way.
149Setup and Workflows | Chapter 6 Project Settings
MEDIA
For more information about Color Management and ACES, see Chapter 9, “Data Levels, Color
Management, and ACES.”
 ACES version: This drop-down only appears if you choose one of the DaVinci ACES options from
the Color science drop-down menu. Lets you switch between different versions of the ACES
specification. This lets you choose the appropriate older version of ACES whenever you open an
older project.
```
 Use Separate Color Space and Gamma: If this checkbox is turned off (the default), the
```
Color Management panel of the Project Settings exposes one drop-down each for the Input,
Timeline, and Output Color Space settings, and each setting simultaneously transforms the
gamut and gamma, depending on which option you choose. If you turn this checkbox on, then the
Color Management panel changes so that the Input, Timeline, and Output Color Space settings
each display two pop-ups. The first drop-down lets you explicitly set the gamut, while the second
drop-down lets you explicitly set the gamma.
To provide more detailed information, the simple and advanced global controls available for
```
Resolve Color Management (RCM) are covered in a dedicated chapter.
```
For more information, see Chapter 9, “Data Levels, Color Management, and ACES.”
Dolby Vision™
```
DaVinci Resolve includes a GPU-accelerated software version of the Dolby Vision CMU (Content
```
```
Mapping Unit) for doing Dolby Vision grading and finishing workflows right in either the free version
```
of DaVinci Resolve or in DaVinci Resolve Studio. This is enabled and set up in the Color Management
panel of the Project Settings with the Enable Dolby Vision checkbox.
s
Dolby Vision settings in the Color Management panel of the Project Settings
There are five controls available:
 Enable Dolby Vision: Turns Dolby Vision on and off. When on, this checkbox enables the
Dolby Vision palette in the Color page.
 Dolby Vision version drop-down: Lets you choose which version of the Dolby Vision algorithms to
use. Options at the time of this writing include 2.9 and 4.0.
 Analysis tuning: Choose from a variety of options for how Dolby Vision will analyze and control
highlight retention.
 Master Display drop-down: Lets you choose the nit level and gamut of the master HDR display
you’re grading on.
 Use External CMU: A checkbox lets you choose whether to use the built-in software CMU or a
hardware CMU that you have connected to your DaVinci Resolve workstation.
150Setup and Workflows | Chapter 6 Project Settings
MEDIA
```
NOTE: Dolby Vision controls are available to all DaVinci Resolve users for monitoring and
```
automatically generating Dolby Vision metadata for creating other HDR and SDR deliverables
from the HDR grade you’ve made. However, if you want to be able to make manual trims on
top of this automatic analysis, you must email dolbyvisionmastering@dolby.com for more
information on obtaining a license.
HDR10+
DaVinci Resolve supports the new HDR10+ HDR format by Samsung. Please note that this support
is a work in progress as this is a new standard. When enabled, an HDR10+ palette exposes trimming
parameters that let you trim an automated downconversion of HDR to SDR, creating metadata to
control how HDR-strength highlights look on a variety of supported televisions and displays. This is
enabled and set up in the Color Management panel of the Project Settings with the Enable HDR10+
checkbox. Turning HDR10+ on enables the Dolby Vision palette in the Color page.
HDR10+ settings in the Color Management panel of the Project Settings
HDR Vivid
HDR Vivid is the HDR video technology standard released by the China UHD Video Industry Alliance
```
(CUVA). Mastering in this format assures wide compatibility with HDR televisions, phones, computers,
```
and other devices in China.
HDR Vivid settings in the Color Management panel of the Project Settings
Lookup Tables
This group of controls lets you add LUTs to the Resolve image processing pipeline that affect every
timeline in the entire project all at once. These LUTs can be used for a wide variety of functions, such
as to trim Timeline grades, apply Log to Linear conversions, simulate film output, and limit the signal to
accommodate Broadcast Safe requirements.
Different options let you insert image processing to different stages of the pipeline as seen in the
following diagram:
151Setup and Workflows | Chapter 6 Project Settings
MEDIA
DISPLAY LUT
Monitored Image
Color Page
Image ProcessingINPUT LUT
Camera Raw
Decoding OUTPUT LUT
Raw
Image
Data
Deliver
Page
Output
Media
Keep in mind that since you can apply both 1D and 3D LUTs simultaneously, 1D LUTs at each step are
always applied before 3D LUTs.
 Input Lookup Table: Two drop-down menus let you add 1D and/or 3D LUTs that process the
current Timeline before every other image processing operation in DaVinci Resolve.
 Output Lookup Table: Two drop-down menus let you add 1D and/or 3D LUTs that process the
current Timeline after the operations applied in the Color page, but before the temporarily
applied Display LUT.
 Video Monitor Lookup Table: Two drop-down menus let you add 1D and/or 3D LUTs that process
the current Timeline after every other image processing operation in DaVinci Resolve. However,
```
Display LUTs are only temporarily applied for purposes of monitoring; they’re never applied to
```
rendered media, or to the signal that is output to tape using the controls in the Deliver page.
Display LUTs are particularly valuable for applying a film print emulation LUT in a Log workflow, or
for applying a monitor calibration LUT if you’re outputting to a single display and you don’t have
dedicated outboard calibration hardware.
Here’s an example. It’s common, when grading for film output using a Log workflow, that you’ll
use the Display LUT drop-down menu to apply a film emulation LUT that simulates the image as it
will be output from the film recorder, taking into account the film lab and print stock used, in order
to make sure that the image you’re grading will appear as close as possible to what the eventual
release print will look like in the cinema.
 Color Viewer Lookup Table: Two drop-down menus let you add 1D and/or 3D LUTs that process
the image shown in the Viewer on your computer display, independently of the Display LUT that’s
used to output to your broadcast display. By default, this follows the Video Monitor LUT setting,
but you can also use this option to apply a specific calibration transform for your computer monitor.
Alternately, you could use it to desaturate the GUI Viewer to be able to specifically evaluate image
contrast, or if you don’t want to have to argue with your client over which display looks correct.
 Scopes Lookup Table: Ordinarily, DaVinci Resolve’s internal software video scopes provide an
unbiased analysis of the actual video data levels within the Resolve image processing pipeline.
However, you can choose to have the software scopes use the Video Monitor LUT selection, or
any other LUT installed on your system, to transform this analysis to reflect the monitored output.
 3D Lookup Table Interpolation: Lets you choose the processing quality of both LUT and DCTL
```
operations in DaVinci Resolve. 3D Lookup tables (LUTs) are 3D tables of red, green, and blue
```
values that specify an output color value for each input color value, thereby providing a method
of making color transformations using pre-calculated data. While powerful, 3D LUTs have finite
```
detail; for example, one might have a 17x17x17 LUT that specifies 4913 individual color transforms.
```
When applied to a floating point image that contains more data than the LUT specifies transforms
152Setup and Workflows | Chapter 6 Project Settings
MEDIA
for, color values falling between the 17x17x17 color transforms specified by the LUT need to
be interpolated. You can choose from two methods that trade off processing efficiency for
higher quality:
```
Trilinear: (Default) Trilinear is backward compatible with grades that use LUTs from previous
```
versions of DaVinci Resolve and matches the look of LUTs being applied in other applications.
```
Tetrahedral: Tetrahedral is slightly more processor-intensive, but results in higher image quality
```
LUT and DCTL processing, with reduced color-banding. Tetrahedral is recommended for projects
that don’t need backward compatibility with previous versions of DaVinci Resolve or LUTs created
in other applications.
 Update Lists button: Refreshes the LUT drop-down menus if you’ve added new LUTs to your
system since DaVinci Resolve has been opened.
 Open LUT Folder button: This selection opens the master folder in your file system, as described
in the list of DaVinci Resolve LUT paths shown above.
Adding Lookup Tables to Your DaVinci Resolve Installation
The drop-down menus in the Color Management panel include a series of factory preset LUTs
that were installed with DaVinci Resolve, along with any LUTs that have been generated by
DaVinci Resolve, or that you’ve imported into the proper directory for your operating system.
• On macOS: Library/Application Support/Blackmagic Design/DaVinci Resolve/LUT/
• On Windows: C:\ProgramData\Blackmagic Design\DaVinci Resolve\Support\LUT
• On Linux: /opt/resolve/LUT
If you downloaded the non-studio version of DaVinci Resolve from the Apple App Store, LUTs
are saved in a different location in order for DaVinci Resolve to remain totally self-contained.
In this case, you can click the “Open LUT Folder” button in the Lookup Tables panel of the
Project Settings, to open up a Finder window at the location these LUTs are stored. You can
use this window to copy LUTs that you want Resolve to have access to, or delete LUTs that you
no longer need.
If you add a LUT to one of these directories after DaVinci Resolve has been opened, you can
click the Update Lists button to refresh the contents of the drop-down menus.
DaVinci Resolve uses both 1D and 3D LUTs. 3D LUTs that are created by DaVinci Resolve
are in the .cube format, configured as 33x33x33 cubes with 32-bit floating point processing.
DaVinci Resolve can also read and use LUTs in the Shaperlut format.
Broadcast Safe
Broadcast Safe settings can be enabled while you grade to limit both the luma and chroma of the
video signal to one of three levels of acceptable overshoots and undershoots.
```
 Broadcast safe IRE (mV) levels: A drop-down menu for choosing one of three levels
```
of aggressiveness when limiting the signal. Choose the range that corresponds to your
QC requirements.
 Make Broadcast Safe: A checkbox that turns broadcast safe limiting on and off.
```
NOTE: The clipping imposed by Broadcast Safe itself does not have an inherently soft
```
roll-off. For best results, Broadcast Safe should be used in conjunction with the Soft Clip
controls in the Color page.
153Setup and Workflows | Chapter 6 Project Settings
MEDIA
General Options
This panel presents a selection of general preferences that affect the interface and operation of
DaVinci Resolve.
Conform Options
The settings in this group determine how clips are conformed to match imported project files with
source media on disk by extracting timecode, reel names, file names, file paths, and so on.
For more information on conforming and relinking, see Chapter 56, “Conforming and
Relinking Clips.”
 Use Timecode: Determines how DaVinci Resolve extracts timecode from referenced media files.
There are two options:
Embedded in the source clip: The preferred setting for most projects to conform automatically and
apply grades to the resulting clips. As long as DaVinci Resolve can reference the timecode in either
a media file’s timecode track, or in the header metadata of the frames in a DPX sequence, you can
use timecode to reconform clips, or even completely change the media file to which a clip refers.
From the source clip frame count: This setting is useful if the source media lacks timecode
metadata, and all that’s available is a frame count that identifies frames via sequentially numbered
integer values.
 Conform partial clips with black gaps: Inserts black frames whenever you conform a clip that
doesn’t contain all the required frames. When this option is selected, partial clips are flagged in
the Edit page with a P in the thumbnail of the clip that it is lacking frames.
 Automatically conform missing clips added to Media Pool: Enabled by default, must be disabled
to use collaborative workflow. When this checkbox is turned on, DaVinci Resolve maintains a
dynamic relationship between clips in the Media Pool and those in a project’s various timelines.
When this checkbox is on and you import clips with matching timecode/file names/reel names to
clips in a timeline, DaVinci Resolve will automatically reconform all matching missing clips, and all
other timeline clips that have force conform turned off.
 Assist using reel names from the: When this checkbox is turned on, DaVinci Resolve uses reel
numbers when conforming clips to match any imported project. This setting must also be turned
on if you want to choose different reel name extraction methods for individually selected clips
using the Clip Attributes window. Turning this checkbox off forces DaVinci Resolve to identify
clips using file names when conforming XML and AAF projects. File names can only be used for
conforming XML or AAF files, or when importing a DaVinci Resolve project.
There are four options:
Source clip file pathname: Obtains the reel number by extracting it from each media file’s path.
This makes it possible to extract a reel number from all or part of the file name, or from all or part
of the name of any folder in the path that encloses that file. This extraction is defined using the
Pattern field.
```
Pattern: A code that defines how a reel number should be extracted from the source clip path name.
```
For more information about creating patterns in “Using the Pattern Field”, see Chapter 56,
“Conforming and Relinking Clips.”
154Setup and Workflows | Chapter 6 Project Settings
MEDIA
Media Pool folder name: The reel number is obtained from the name of the bin in the Media Pool
that encloses that clip. This option is often used for stereo projects, deriving the reel number from
“Left” and “Right” named directories. It’s also useful for projects that are inheriting new VFX clips
on a daily basis.
Embedding in source clip file: Useful for file formats where the reel number is embedded within
the media file itself. QuickTime files created by Final Cut Pro, DPX frame files, and CinemaDNG
files are all formats that are capable of containing reel number header data.
Source clip filename: If there is no defined reel number, often it’s easy to just use the source clip
filename. This is a safe option to use in situations where you want to manually choose different
reel name extraction methods for individual clips using the Clip Attributes window.
 Limit reel name matching to X characters: For situations where you’ve been provided with media
files with extra characters in the reel name that don’t correspond to the names used in the project
file you’ve been given, “Limit reel name matching to X characters” lets you omit a specific number
of characters from the end of a reel name. This works in conjunction with the following setting.
 Ignore the first X characters of the reel name: For situations where you’ve been provided with
media files with extra characters in the reel name that don’t correspond to the names used in
the project file you’ve been given, “Ignore the first X characters of the reel name” lets you omit a
specific number of characters from the beginning of the reel name. Combined with the previous
setting, you can trim any reel name to a conformable subset of characters.
 Extract reel names from EDL comments: Media file formats such as R3D have reel names,
obtained from the file names, that are longer than the eight characters that are allowable in
a standard EDL. This option allows DaVinci Resolve to extract reel names from appropriately
formatted EDL comments, such as those output from Final Cut Pro 7.
 Sort timeline using reel number and timecode: Lets you change the behavior of C mode sorting
```
in the Timeline. With this checkbox turned on (the default), all clips in the Timeline are sorted by
```
reel number first, and then by source timecode. This way, clips with similar timecode from the
same reel will appear next to one another in C mode. If you turn this checkbox off, reel number is
ignored, and all clips in the Timeline are sorted only by source timecode. This may result in clips
from multiple sources being mixed together, but it is useful in specific situations.
```
 Mixed frame rate format: (Only available prior to importing media into a project) This drop-down
```
menu lets you choose the method used to conform mixed frame rates for rendering and playback.
Which option you choose dictates the accuracy with which retimed clips in DaVinci Resolve match
the same clips that were retimed in other editing applications when you import those timelines
into DaVinci Resolve via XML or AAF. This drop-down menu also appears in the Load AAF
or XML dialogs.
If you’re editing from scratch in DaVinci Resolve: You should leave this setting set to “Resolve.”
When importing timelines via XML from Apple software: Choose the “Final Cut Pro 7” or
“Final Cut Pro X” methods of conform.
When importing timelines via XML or AAF from Premiere Pro, Media Composer, Smoke, or
other NLEs: You should choose “Resolve.”
When none is selected: DaVinci Resolve conforms and processes all clips in the Timeline to play
at the frame rate that’s selected in the “Timeline frame rate” drop-down menu. For example, 23.98,
29.97, 30, 50, 59.94 and 60 fps clips will all play at 24 fps if that’s what “Timeline frame rate” is set
to in the Master Project Settings, and clips will play slower or faster accordingly.
How clips in mixed frame rate timelines are rendered out depends on whether the Render
Settings are set to render individual source clips or one single clip. When you render the Timeline
as individual source clips, all clips are rendered individually at their original frame rate. If you select
“single clip,” all clips are converted to the “Timeline frame rate” frame rate and rendered as a
single media file.
155Setup and Workflows | Chapter 6 Project Settings
MEDIA
Color
These settings affect clip versions and timeline interactions when working in the Color page.
 Automatically label gallery stills using: When enabled, DaVinci Resolve automatically generates
labels for all gallery stills you take based on the following controls:
Naming drop-down: Lets you choose what name to use for new stills. Options include: Clip Name,
Clip Version Name, Source Timecode, Timeline Timecode, Timeline Name, Display LUT Name,
```
Custom Label Using Tags (using metadata variables).
```
Append still number on export checkbox: When enabled, each new still has an appended still
number. Where the number appears depends on the following radio buttons.
As Suffix/As Prefix buttons: Lets you choose to place still numbers at the end of an auto
generated gallery label or at the beginning.
 Luminance mixer defaults to zero: Selecting this option sets the Y channel of the YRGB
parameters for all grades to zero. This is required to be able to export a compliant ASC-CDL, and
will impact all grades that use the Lum Mix control.
 Use legacy Log grading ranges and curve: DaVinci Resolve 12.5 introduced a modification to
the Log grading controls that provides smoother, more pleasing results using the same controls.
To maintain backward compatibility with older projects, a “Use legacy Log grading ranges
and curve” checkbox in the Color panel of the Project Settings lets you switch your project
between the older Log control behavior and the newer one. Older projects that are opened in
DaVinci Resolve have this checkbox turned on by default, while new projects have this turned off
by default.
 Use S-curve for contrast: On by default, this checkbox sets the contrast control in the Color
Wheels palette to apply an “S-curve” to the image, such that the shadows and highlights of a
signal will not be clipped when you increase the value. If you would prefer for these contrast
adjustments to be made linearly, and for the signal to be allowed to clip when you reach the upper
and lower boundaries of the video signal, you can turn this checkbox off.
 Use legacy sizing interactions for windows and effects: DaVinci Resolve 14.1.1 improved how
```
window tracking applies transformations, to correctly handle things like pixel aspect ratio (par).
```
New projects should leave this setting disabled, however older projects should leave this
checkbox enabled to ensure tracking and transforms remain applied the way they were before.
 Apply stereoscopic convergence to windows and effects: When enabled, DaVinci Resolve
correctly maintains the position of a window that’s been properly placed over each eye as
convergence is adjusted in the 3D palette. Enabling this checkbox also enables an additional
Convergence parameter in the Window palette that lets you create properly aligned convergence
for a window that’s placed onto a stereoscopic 3D clip, as seen in the following screenshot.
l
The Convergence control in the Transform section of
the Window palette appears when you enable “Apply
stereoscopic convergence to windows and effects”
156Setup and Workflows | Chapter 6 Project Settings
MEDIA
 Use local version for new clips in timeline: Automatically sets all new clips that are added to
existing timelines, or all clips that are added to new timelines that are imported via AAF, EDL, or
XML, to use local grades by default. If you want all clips added to new timelines to use remote
grades instead, as with DaVinci Resolve version 9 and earlier, you can turn this checkbox off.
 Automatically match master timeline with media pool: If you turn on this option before importing
any media into the Media Pool, or importing any timelines that will in turn import media into the
Media Pool, you can create projects with a Master Timeline. When enabled, clips are added to and
removed from the Master Timeline as they’re added to and removed from the Media Pool, so that
the Master Timeline always contains all media in the Media Pool. Once media has been imported
into a project, this setting cannot be changed.
 Save timeline thumbnails with project: To minimize project size, and maximize the speed
of saving and loading projects, you should leave this checkbox unchecked. If you select the
checkbox, all of your Timeline thumbnails will be stored inside every project, instead of in the
default directory that’s ordinarily dedicated to stills, during both Save and Auto Save operations.
This provides a good history of the project but takes much longer to complete and uses more hard
disk space.
 Use BGR pixel order for DPX v2: Lets you choose a different pixel order for projects using
DPX version 2 media.
 Embed timecode in audio output: When turned on, directs DaVinci Resolve to output LTC
timecode that’s embedded in channel 16 of the SDI stream and channel 2 of the analog audio
output from your video interface.
 Use Timelines Bin: This option is only available to be changed before you add clips to the Media
```
Pool; after you’ve added clips, it’s no longer available. Turning Use Timelines Bin on creates a
```
dedicated Timelines bin in the Media Pool, at the top of the Bin List. When enabled, the Timelines
bin contains all timelines in a project, and you’re prevented from putting timelines into any other
bin in the Media Pool. Whenever you create or import a new timeline, it automatically appears in
the Timelines bin. You can add subfolders to the Timelines bin for more specific organization.
Dynamics Profile
Defines the default transition from one dynamic keyframe to the next for keyframed effects in the
Color page. By default this transition is linear, with the “Dynamic profile start” and “Dynamic profile
end” parameters set to 1. However, if you need to alter the acceleration of the interpolation of values
from one dynamic keyframe to the next, then you can change that keyframe’s Dissolve Type in order
to “ease” the effect transition you’re creating. The values in these settings correspond to the graph
curves found in the Dynamic Attributes dialog when editing keyframes in the Color page.
For more information, see Chapter 148, “Keyframing in the Color Page.” in “Changing Dynamic
Attributes”.
157Setup and Workflows | Chapter 6 Project Settings
MEDIA
Versions
Ten text fields provide a way for you to designate automatic names for the versions of grades that you
select in the Color page. To the right of each text field, a drop-down menu lets you add a name from a
handy list of predefined terms that’s been provided. Alternately, you can simply click any field and type
your own custom name.
When you change the name of a version in the Color page, the names you define in this list are
available from a drop-down menu in the Version Name dialog.
Using the named drop-down when editing the name of a version
Using a predefined list of names for your different versions avoids typos that can later create folder
naming issues when you use the “Commercial Workflow” options for rendering your media in the
Deliver page.
Camera Raw
This panel contains groups of parameters that correspond to every camera raw media format that’s
supported by DaVinci Resolve. Using these parameters in the Camera Raw panel, you can override
the original camera metadata that was written at the time of recording, and make simultaneous
adjustments to all camera raw clips using the “project” raw settings.
To provide more detail, these settings are covered in detail in a dedicated chapter.
For more information, see Chapter 128, “Camera Raw Palette.”
158Setup and Workflows | Chapter 6 Project Settings
MEDIA
Capture and Playback
All settings in this panel let you define the functionality of capture and playout to tape using
device controlled VTRs connected to your Resolve workstation via the connected video capture
and output interface.
For more information on deck capture, see Chapter 24, “Ingesting From Tape.”
For more information on video output to tape, see Chapter 189, “Delivering to Tape.”
Deck Settings
These settings affect both capture and playback when using the tape ingest options of the Media
page, or the tape output options of the Deliver page.
```
 Video capture and playback: You can choose the video format (frame size and frame rate) with
```
which to output to tape from this drop-down menu. HD timelines can be downconverted to SD,
and SD timelines can be upconverted to HD using the format conversion of your DeckLink card.
 Use left and right eye SDI: A checkbox that enables supported video interfaces to ingest and
output muxed stereoscopic video when used with supported VTRs, such as HDCAM SR decks
```
with 4:2:2 x 2 mode. (When muxed stereoscopic signals are ingested, each eye is separated into
```
```
individual left-eye and right-eye image files.) This parameter only appears when your hardware is
```
set up appropriately.
 Video connection operates as: Selects between the available signal options: Use 4:4:4 SDI
and Enable Single Link. Which options are available depend on which video capture card you
are using.
```
 Data Levels: Lets you specify the data range (normally Video or Full) that’s used when ingesting
```
from or outputting to tape. This option switches the data range of the signal output by your video
capture card, but only during capture from tape in the Media page, or output to tape in the Deliver
page. When capture or output is not currently occurring, your video capture card goes back to
using the identically named data range setting in the Master Project Settings pane, which governs
how you monitor the signal being output on an external broadcast display or projector.
 Video bit depth: Choose the bit depth that corresponds to the capability of your deck. Depending
on your workstation’s configuration, you can choose between 8-bit and 10-bit. Outputting to 10-bit
is more processor intensive, but higher quality for compatible devices, and is the default setting.
 Use deck autoedit: If supported by your video deck, this is the best method to record video
to the deck, as it enables the deck to roll the edit using the specified preroll, and control the
edits via serial device control. If this checkbox is turned off, a basic edit On/Off mode is used
by the deck, with the potential for frame inaccuracies if the “Non auto edit timing” setting is
not properly adjusted.
 Non auto edit timing: Adjusts the edit synchronization of the connected deck when auto
edit is turned off.
 Deck preroll: Sets the number of seconds for preroll. How much is appropriate depends on the
performance of your deck.
 Video output sync source: When using a DeckLink card this is set to Auto. Other capture cards
may require you to set the sync source to “Reference” for playout and “Input” for ingest. This
setting is only available if you have a DVS card installed on your system.
 Add 3:2 pulldown: Inserts or removes the 3:2 pulldown required to record or play 23.98 fps media
to or from a 29.97 tape format.
159Setup and Workflows | Chapter 6 Project Settings
MEDIA
Capture
These settings are used when you use the Capture mode in the Media page to capture clips from tape
into the Media Pool.
 Capture: Lets you choose whether to capture both Video and Audio, or Video Only.
 Video Format: The format that scanned film frames are saved as. When capturing from tape, the
available options are DPX and QuickTime. When capturing from the Cintel film scanner, this is
```
restricted to Cintel Raw Image (CRI), which is a raw data format that DaVinci Resolve automatically
```
debayers as a Cineon log-encoded image for grading.
 Codec: The codec used to write captured media. When capturing from tape, these include the
various type of Apple ProRes, 8- and 10-bit YUV 422, 10-bit RGB, and the various types of DNxHD.
Cintel Raw Image files default to rgb.
 Save clips to: A field that displays the directory path to which media files captured from tape are
written. You want to choose a volume that’s fast enough to accommodate the data rate of the
media format you’re capturing.
```
Browse: Click this button to choose a directory to write captured media to. The directory you
```
choose appears in the field above.
 Save in this folder path: A series of checkboxes let you specify what other information to use to
define the directory hierarchy that will hold the captured media. Every checkbox you turn on adds
an additional directory with a name defined by that checkbox’s metadata. You can choose any or
all of the following: Program name, Clip number, Reel number, and Roll/Card.
 Apply reel number to: Lets you choose how to write the reel name. Two checkboxes let you write
the reel number to the file’s name, and/or to the Header data.
 Use prefix: A field lets you type in a prefix to be used in the media file’s name. This lets you add
text identification that will make the media more easily identifiable and searchable.
 Apply prefix to: Two checkboxes let you choose to use the prefix you typed in the file name, and/
or in the folder name.
 Use frame number with: When capturing to image sequences, you can choose how many digits to
use when writing the frame number into the name of each frame file.
 Set batch ingest handles to: When capturing to image sequences from a batch list, defines how
many frames of additional handles to ingest along with each logged clip.
 Input: Lets you choose how many tracks of audio to capture, from 2 to 16.
Playout
These settings only affect the video signal that’s output when you use the Edit to Tape mode of the
Deliver page.
 Output: Lets you choose whether to output both Video and Audio, Video Only, or Audio Only if
you’re doing an audio layback.
 Output Source Timecode: Turn this checkbox on to output each individual clip’s source timecode.
This option is only applicable when assemble editing to tape.
 Output LTC: With a Blackmagic Design DeckLink or UltraStudio device using HD-SDI, longitudinal
```
timecode (LTC) is available on track 16 of the HD-SDI video signal, making it easy to use a Mini
```
Converter de-embedder to extract this analog timecode audio signal and feed it directly to a
recording device. This is particularly helpful if you have outboard video processing equipment
such as a noise reducer or format converter that passes through the VITC timecode.
 Delay LTC by x frames: When outputting LTC to bypass outboard processing gear, such as a
noise reducer or format converter, you can compensate for the processing delay by delaying the
timecode by a matter of frames to ensure that the processed image and timecode reach the deck
at the same time. With a DVS card there is a separate timecode output.
160Setup and Workflows | Chapter 6 Project Settings
MEDIA
 Offset audio by x frames: Lets you specify an offset between the audio track and video to achieve
proper A/V sync in cases where the video is being delayed by outboard processing hardware.
 Output x channels of audio: Choose the number of audio tracks to output to tape.
 Set batch playout head handle to x seconds: When batch outputting multiple clips, you can
specify a number of frames before the In point of each clip to be output as well.
 Set batch playout tail handle to x seconds: When batch outputting multiple clips, you can specify
a number of frames after the Out point of each clip to be output as well.
Subtitles and Transcription
The Subtitles panel lets you adjust presets that govern subtitles being created in subtitle tracks of
the timeline.
 Max Character Per Line: Defaults to 60. Lets you choose the maximum number of characters
allowed on one line in a subtitle.
 Minimum Caption Duration: Defaults to 3 seconds. Lets you choose the minimum duration
allowed for subtitles in the timeline.
 Maximum Characters Per Second: Defaults to 30. Automatically calculates the maximum
allowable characters per second based on a subtitle clip’s duration.
The Transcription setup panel lets you select the language that DaVinci Resolve uses to
analyze audio clips for transcription.
```
Language: Select one of the supported languages here. Selecting Auto lets DaVinci Resolve
```
analyze the audio clip and choose the language spoken.
Fusion
Fusion allows consistent frame numbering for all compositions, including trimmed clips. This means
that any composition created in Fusion can start with the same start frame number. In new projects
you can change the default start frame for Fusion compositions in the project settings.
 Legacy Fusion Composition Frame Count: Sets the Fusion composition at zero frames to the first
frame of the source media for the composition.
 Default Start Frame: Lets you type in a default frame number to start your fusion comps in
this project.
 This helps with Visual FX workflows in three ways:
 Matching existing keyframes to the right frame offsets—when replacing an asset with mismatched
```
frame offsets (e.g., a sub clip, different format or round trip, or VFX connect workflows with
```
```
mismatching handles).
```
 Rendering to specific frame ranges—when aligning to delivery standards for commercial
```
workflows (e.g., compositions should start at sequence frame 1000).
```
 Consistent Referenced Comp behavior—essential when applying a referenced composition to
different clips with different trims.
161Setup and Workflows | Chapter 6 Project Settings
MEDIA
Fairlight
The Fairlight panel lets you set up your project’s audio sample rate, as well as setting up various
audio-specific tools in the Fairlight page.
Timeline Sample Rate
This setting can only be changed prior to creation of your first timeline. Once one or more timelines
have been created in a project, the Audio Sample Rate is locked to whatever was chosen.
The Audio Sample Rate, measured in kilohertz, is the number of samples per second used for
```
audio processing in DaVinci Resolve. This setting defaults to 48000 (or 48 kHz), which is typical for
```
broadcast and cinema work. However, you can change this to 96000 or 192000 if you want to mix and
process audio at higher precision. Be aware that using a higher sample rate, such as 96 kHz instead of
48 kHz, will use twice as much processing power and result in media that’s twice the size.
```
NOTE: Regardless of the Timeline Sample Rate you select, when you import audio files at
```
different sample rates, they will be automatically re-sampled to the Timeline Sample Rate so
they play correctly.
Bussing
If you want to work using the previous method of fixed-bus mapping, you can do so for new
projects by opening the Fairlight panel of the Project Settings and turning on the “Use fixed bus
mapping” checkbox.
If your project has fixed busing enabled and you want to change to FlexBus, then uncheck the “Use
fixed bus mapping” checkbox. Note that once you have made the change, it will not allow you to
change it back to legacy busing. The advantages to changing from legacy busing to FlexBus are
enormous, so you will not regret making the change.
Audio Metering
Two options in the General Options of the Project Settings let you customize the Loudness Meters on
the Fairlight page, while the others affect all other audio meters in DaVinci Resolve.
 Meter Type: Lets you select the desired Meter Type.
 Level detector: If the Meter Type is set to Custom, this lets you select Sample Program, VU, or
RMS for audio level metering detection.
 Scale: If the Meter Type is set to Custom, this lets you select either IEC 60268-18 or Quasi Linear
for audio level metering scaling.
 Decay: If the Meter Type is set to Custom, this lets you set the time in seconds for level metering
decay in 20 dB increments, following peak levels registering on the meters.
 Peak Indicator: If the Meter Type is set to Custom, this lets you select the hold time for peak level
indication in the meters.
 Off
 Short hold + fall
 Medium hold + fall
 Medium hold
 Long hold
 Infinite hold
 Pre fader metering on tracks: Lets you choose how meters in the Fairlight page display their
audio analysis. There are two options:
162Setup and Workflows | Chapter 6 Project Settings
MEDIA
```
Post Fader (unchecked): Meters always display the level of each clip’s signal after whatever fader
```
adjustments have taken place. Fading a track’s level down diminishes the visible level of that
audio signal in the meter. This setting is good if you prefer a visual indication of the relative levels
you’ve set your various audio tracks to, which is a very NLE-oriented behavior.
```
Pre Fader (checked): Meters always use the volume levels of the audio clips in that track, even if
```
you’ve lowered the level using the sliders. If you’ve keyframed a clip’s volume, that change will be
reflected by the audio meters, even though fader changes are not. Viewing meters this way means
you can always see how much level is available to clips in your mix, regardless of what the current
fader levels are set to, in the event you want to keep track of audio you want to bring back into the
mix later on. This is a very DAW-oriented behavior.
 Target Loudness level: Lets you set the LUFS value that’s used as a reference level for loudness
metering. Defaults to –23 LUFS, which conveniently makes the display of these meters scale
similarly to traditional audio meters that you’re already used to.
 Loudness Scale: Lets you choose which scale you want to use with which to measure the meters.
```
Options currently include the default of EBU +9 Scale (–18 to +9), and EBU +18 Scale (–36 to +18).
```
 Bus Meter Alignment Level: Sets the peak of the bus meter.
 Bus Meter High Level: Sets the dB level at which the meter starts showing red.
 Bus Meter Low Level: Sets the dB level at which the meter starts showing yellow.
Path Mapping
The Path Mapping panel lets you configure your system’s file paths, allowing you to seamlessly link
and share media clips while collaborating with other users on their own systems. For example, Editor
A and Colorist B are collaborating on the same project. Editor A is working on a Mac in L.A., where
Colorist B is working on a PC in Bangkok. They are both sharing media in a cloud service’s folder, but
the file paths to that cloud folder are different for both of them locally.
 The Editor’s Mac folder is at /Users/editor/cloudfolder/Episode 12
 The Colorist’s Windows folder is at D:\Projects\Episodes\cloudfolder\Episode 12
Normally if they were collaborating, each one would constantly have to re-link the files from the
other before they could continue as the path names would not match. By both of them adding the
“Episode 12” location, and mapping their local paths in this section, DaVinci Resolve will automatically
convert the file paths on the fly as they work. There would be no need for re-linking the clips as long
as all the media they used was in the same hierarchy in the Episode 12 folder.
You can use Path Mapping to make things easier for non-collaborative workflows as well. For example,
for a single user on a laptop, they could setup a link from their local media folder to their NAS.
This removes the need to relink the media each time they leave and return to the office.
```
NOTE: Path Mapping differs from using the older Mapped Mount option in the Media Storage
```
preferences. Mapped mount requires each user knowing the file path of all the other users.
Path Mapping lets the user just present their own file path, and DaVinci Resolve takes care of
the translation for all the other users instead.
163Setup and Workflows | Chapter 6 Project Settings
MEDIA
Project Media Locations
This setting lets you set up your project’s media locations so that they can easily be shared and
translated with other DaVinci Resolve users. The idea is to have a media folder in common with all the
```
other users (i.e., all connected to the same shared cloud storage folder), and set up the path to your
```
own individual folder here.
 Location: Shows you the name of the shared folder.
 Local Path: Shows the path to this folder on your filesystem.
 Add: Opens a filesystem dialog to let you select the shared folder.
Once the location is selected, press the Browse button and use the file system to set the local
path to that folder on your computer.
 Remove: Removes a shared folder from the Path Mapping settings. It does not delete the folder
from your system.
 Automatically setup when relinking: With this setting enabled, when relinking offline media,
DaVinci Resolve automatically creates a mapping. It compares the path in the project file and the
user selected path and creates a relative path between the two. It checks if other offline media
in this project is available in those relative paths and relinks them as appropriate. It also does the
same check with proxies in proxy subfolders.
The Path Mapping Project Settings
164Setup and Workflows | Chapter 6 Project Settings
MEDIA
Chapter 7
Camera Raw
Settings
This chapter discusses in detail each of the settings available for every camera
raw format that is supported in DaVinci Resolve. These settings are available in
the Camera Raw panel of the Project Settings, via the Inspector in the Media, Cut,
and Edit pages, or in the Camera Raw palette of the Color page.
Contents
Camera Raw Decoding Explained  166
Camera Raw Project Settings  166
Camera Raw Image Inspector  167
ARRI  168
Master Settings  168
Project Settings 168
Use Camera Metadata 169
Blackmagic RAW 170
BRAW Sidecar Metadata Files  170
Master Settings  170
Project Settings 171
Use Camera Metadata 173
Canon RAW  173
Master Settings  173
Project Settings 174
Use Camera Metadata 174
CinemaDNG  175
Master Settings  175
Project Settings 176
Use Camera Metadata 177
Nikon RAW  178
Panasonic Varicam RAW  180
Master Settings  180
Project Settings 180
Use Camera Metadata 181
Phantom Cine  181
Master Settings  181
Project Settings 181
RED  182
Master RED Settings 182
Master  183
Project Settings 183
Decoder Settings  186
Use Camera Metadata 187
Sony RAW  188
Master Settings  188
Project Settings 188
Use Camera Metadata 190
165Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
Camera Raw Decoding Explained
Camera raw media formats are so named because they capture raw color space data directly from the
sensor of whatever digital cinema camera did the recording. Raw image data is not human readable,
and must be debayered or demosaiced to convert the original raw data into image data that can be
handed off to DaVinci Resolve’s image processing pipeline.
Raw
Image
Data
Color Page
Image Processing
Camera Raw
Decoding
Deliver
Page Output
Raw decoding is the very first image processing operation that takes place, and it takes place before
all other operations in the Color page, before even the Source bar in the Node Editor. For this reason,
it’s important to understand that the ideal transformation of raw image data to DaVinci Resolve-friendly
image data is one that preserves the maximum amount of image data for continued processing.
Since the 32-bit floating point accuracy of DaVinci Resolve’s image processing pipeline preserves all
transformed raw data with exceptional fidelity, the Camera Raw parameters are primarily useful for
making whatever initial adjustments will produce the most optimum starting point for grading.
Each group of Camera Raw settings is available from the Raw Profile menu. This description covers the
settings that are available for each of the camera raw media formats supported by DaVinci Resolve.
Camera Raw Project Settings
The Camera Raw panel of the Project Settings contain groups of parameters that correspond to every
camera raw media format that’s supported by DaVinci Resolve. Using these parameters in the Camera
Raw panel, you can override the original camera metadata that was written at the time of recording,
and make simultaneous adjustments to all camera raw media throughout your project.
Camera Raw project settings
166Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
Each supported camera format has different controls that are specific to that format. These controls
are also mirrored in the Camera Raw palette in the Color page, which lets you individually adjust the
Camera Raw parameters for individual clips in a Timeline when you set Decode Using to Clip.
Camera Raw project palette in the Color page
Camera Raw Image Inspector
The Image panel in the Inspector exposes the Camera Raw parameters. If the video clip is in a Raw
format, the specific camera’s Raw controls will be exposed for user manipulation. Raw still images from
```
Nikon (NEF) and Canon (CR2) cameras can also be adjusted in this panel.
```
The Image Inspector for a Blackmagic RAW file
167Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
ARRI
The ARRI ALEXA can record ProRes, DNxHD, or raw image data. When shooting raw, image data is
recorded straight from the Bayer sensor, and must be debayered by DaVinci Resolve.
Master Settings
ARRI ALEXA media is extremely simple to debayer. There are only three Master settings.
 Decode Quality: Lets you debayer ARRI ALEXA raw files at Full, Half, or Quarter resolution to
improve performance on slower systems. Lower resolution media is lower quality, but faster to
work with and process. If necessary, you can choose a lower resolution setting that provides
better real time playback on systems with limited performance while you work, and then switch
to a higher quality when rendering the final output. A “Force debayer res to highest quality”
checkbox in the Render Settings list of the Deliver page makes it easy to follow this workflow.
 Decode Using: The option you select determines whether all ARRI ALEXA media throughout
```
the project is decoded using the original Camera Metadata settings (the default selection), using
```
Project settings in which you choose custom settings to be applied to all clips, or using the
ARRI default settings.
 Import Media at Open Gate Resolution: Enables DaVinci Resolve to access the “open gate” area
of clips from ALEXA cameras capable of shooting in this mode, which produces a 3.4K image with
extra area for stabilization and repositioning.
Project Settings
The following decoder settings let you adjust the color and exposure of ALEXA clips.
 Lift: Adjusts the black point of the media, raising it or lowering it while scaling all midtone values
between it and the white point. Regardless of how you adjust this control, all image data is
preserved and can be retrieved in subsequent adjustments. The range is –100 to +100.
 Gain: Adjusts the white point of the media, raising or lowering it while scaling all midtone values
between it and the black point. Regardless of how you adjust this control, all image data is
preserved and can be retrieved in subsequent adjustments. 0 is unity. The range is –100 to +100.
 Contrast: Raising contrast reduces shadows and raises highlights, while leaving midtones at 50
percent unaffected. Regardless of how you adjust this control, all image data is preserved and can
be retrieved in subsequent adjustments. 0 is unity. The range is –100 to +100.
```
 Tint: Adjusts color balance to push the image between magenta and green; useful for balancing
```
images with a green or magenta color cast, such as fluorescent or sodium vapor bulbs. 0 is unity.
The range is –150 to +150.
 Sharpness: A debayer-specific sharpness filter applied to provide the appearance of enhanced
image detail. 0 is unity, and 10 is the default. The range is 0 to 100.
 Highlights: Makes it easy to selectively retrieve blown-out highlight detail in high-dynamic-range
media by lowering this parameter, and achieves a smooth blend between the retrieved highlights
```
and the unadjusted midtones for a naturalistic result. 0 is unity. The range is –100 (minimum)
```
```
through +100 (maximum).
```
 Shadows: Lets you selectively lighten or darken shadow detail. Raising this value retrieves shadow
detail recorded below 0 percent, while leaving the midtones alone. 0 is unity. The range is –100
```
(minimum) through +100 (very high).
```
 Color Boost: Lets you naturalistically raise the saturation of regions of low saturation, sometimes
referred to as a vibrance operation. Can be used also to lower the saturation of regions of low
```
saturation. 0 is unity. The range is –100 (minimum) through +100 (very high).
```
168Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
```
 Saturation: Adjusts the color intensity of the image. 0 is unity. The range is –100 (minimum)
```
```
through +100 (very high).
```
 Midtone Detail: When this parameter is raised, the contrast of regions of the image with high edge
detail is raised to increase the perception of image sharpness, sometimes referred to as definition.
When this parameter is lowered to a negative value, regions of the image with low amounts of
```
detail are softened while areas of high detail are left alone. 0 is unity. The range is –100 (minimum)
```
```
through +100 (very high).
```
 Decode as monochrome: When this box is checked the ArriRaw footage will be decoded in black
and white only. This setting is designed to work with the Alexa Monochrome range of cameras. If
applied to normal ARRI Raw, it will simply discard the color information. RAW controls that affect
color, such as saturation and color temp, will have no effect.
Use Camera Metadata
The most elemental camera metadata settings for exposure and color that are available.
 Color Temp: Adjusts color balance to alter the “warmth” of the image. Adjustable in Kelvin. Lower
values correct for “warmer” lighting, while higher values correct for “cool” lighting. +2000 is unity.
The range is +2000 to +11,000.
 Tint: Only available when White Balance is set to something other than As Shot. Designed to alter
the green to magenta balance of the image, for images with fluorescent tinting. Lower values add
green to compensate for magenta lighting, while higher values add magenta to compensate for
green lighting. 0 is unity. The range is –12 to +12.
 Exposure: Increases or lowers image lightness in units relative to ASA values. If your
```
intended exposure adjustment lifts image data above the maximum white level, don’t worry;
```
all image data is preserved and can be retrieved in subsequent adjustments. 160 is unity.
The range is +160 to +3200.
 Finetune Red: Advanced debayer setting.
 Finetune Green: Advanced debayer setting.
 Finetune Blue: Advanced debayer setting.
ARRI Media and Log-C
ALEXA media is usually recorded using Log-C gamma and color processing, which is very
similar to the Cineon Log gamma curve, developed by Kodak to produce flat-contrast, wide-
gamut image data that preserves image detail with a wide latitude for adjustment. There is no
ALEXA raw parameter to adjust this, so for Rec. 709 monitoring and deliverables you need to
“normalize” Log-C clips in one of three ways.
```
You can use Resolve Color Management (RCM) to automatically normalize log-encoded media
```
according to the type of media it is.
You can create your own adjustment to normalize Log-C clips as part of the grading process,
using the parameters of the Color page. This approach gives you the most flexibility, as you’ll
be making custom settings that maximize the image data that’s available in every scene.
Alternately, you can use a LUT to normalize Log-C clips to obtain a fast starting point for
additional grading. Used in this way, LUTs can be applied either as an output LUT, if the entire
Timeline is nothing but ALEXA raw media, or as a LUT that’s applied to an individual node of
a grade, if you’re mixing ALEXA raw media with other formats. This provides a fast and easy
solution to linearizing ALEXA media that can be useful for creating dailies for offline editing.
However, one LUT may not be suitable for all clips. If you’re applying individual LUTs to each
169Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
clip, you can create multiple LUTs, each with differing contrast settings, in order to gain the
speed benefits of using LUTs, while taking into account the individual differences among clips.
ARRI has a LUT generator available online that you can use to create custom LUTs for use with
a variety of color correction applications at: https://www.arri.com/en/learn-help/learn-help-
camera-system/tools/lut-generator
Blackmagic RAW
A raw format developed by Blackmagic Design and used by a variety of Blackmagic cameras.
This format relies on the increased processing capabilities of modern cameras to perform a certain
```
amount of in-camera pre-processing (including noise management, sensor profiling, and edge
```
```
reconstruction) to partially de-mosaic the image and then re-encode the result, factoring in the
```
characteristics of the originating image sensor. The image is encoded in such a way as to later enable
```
typical raw controls but with efficiently compressed files (using a custom non-linear 12-bit space)
```
that are not computationally challenging to decode and use. BRAW media can be encoded at either
```
a Constant Bitrate (with variable compression of 3:1, 5:1, 8:1, and 12:1) or at Constant Quality (with a
```
```
variable bitrate).
```
BRAW Sidecar Metadata Files
BRAW files have been designed to accommodate descriptive metadata that enables look
management from on-set through post. This metadata is both embedded in the .braw files and
included within .sidecar files that are saved alongside the media. Metadata .sidecar files that are
present always takes precedence over the embedded metadata for purposes of decoding. However, if
there’s no .sidecar file, decoding of the .braw file falls back on the embedded metadata.
Modifying Sidecar Files
You can use the Camera Raw palette of the Color page to Update a BRAW clip’s sidecar file with
changes made to the Camera Raw settings. Click Update Sidecar to save changes, and click Export
Frame to export a one-frame image for reference.
Master Settings
These parameters let you choose the decode quality and method that raw clips will be transformed to
use when debayered.
 Decode Quality: Lets you debayer .braw files at Full, Half, Quarter, or Eighth resolution to improve
performance on slower systems. Lower resolution media is lower quality but faster to work with
and process. If necessary, you can choose a lower resolution setting that provides better real time
playback on systems with limited performance while you work, and then switch to a higher quality
when rendering the final output. A “Force debayer res to highest quality” checkbox in the Render
Settings list of the Deliver page makes it easy to follow this workflow.
 Decode Using: The option you select determines whether all .braw media throughout the project
```
is decoded using the original Camera Metadata settings (the default selection), using Project
```
settings in which you choose custom settings to be applied to all clips, or using the Blackmagic
Raw default settings.
170Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
Project Settings
These parameters let you choose the color science, white balance color space, gamma, and other
visual settings guiding how the image will be transformed to suit your program and RCM.
 Color Science: Lets you choose what version of camera color science you want to use to
decode .braw media.
Camera Metadata: Chooses whichever version of color science was selected by
the camera at the time of shooting.
Gen 4: The original version of color science available for recording and decoding .braw media.
Gen 5: A newer more film-like curve designed for better skin tones and high
contrast/saturation color response.
 White Balance: The first seven options offer White Balance presets, which automatically adjust
the Color Temp and Tint parameters. These options include: Daylight, Cloudy, Shade, Tungsten,
Fluorescent, and Flash. An eighth option, Custom, makes the Color Temp and Tint parameters
user-adjustable. The default is As Shot.
 Color Space: Debayering .braw data requires choosing a color space to convert the raw signal
into. Bear in mind that the color space you choose is merely a starting point for further correction.
There is no requirement that you choose one or the other color space for any given workflow,
and all settings will yield high-quality image data suitable for further color correction. You should
choose the color space that provides the most pleasing starting point for your particular project.
Blackmagic Design: A wide gamut color space designed for digital cinema workflows on
Blackmagic Design cameras.
Rec. 709: Decodes into the standard color space specified by the Rec. 709 standard for high
definition video. While you may find this option useful as a starting point, it is not required for
programs being output to video.
Rec. 2020: Decodes into the standard color space specified by the Rec. 2020 standard for high
definition video, UHD video, and beyond. While you may find this option useful as a starting point,
it is not required for programs being output to video.
DCI-P3 D65: Decodes RGB-encoded image data with a D65 white point, intended for monitoring
with a P3-compatible display.
DCI-P3 Theater: A setting designed for adaptive viewing of DCI-P3 in a theater with a projector
using a D60 white point.
CIE 1931 XYZ D65: A specialty setting for outputting to an XYZ color space with a
D65 adaptive white point.
```
CIE 1931 XYZ D50 (PCS): A specialty setting for outputting to an XYZ color space with a
```
D50 adaptive white point, as used by the profile connection space of the DNG image format.
 Gamma: There are several options available for choosing a gamma profile to be used when
debayering .braw media. Which one is best really depends on how you like to work, as all will
yield high-quality image data without clipping the signal internally within DaVinci Resolve’s image
processing pipeline. Even though some of these options will produce a range of image data that
will clip on output, all of that image data is preserved “under the hood” and can be used and
retrieved in your grade.
Blackmagic Design Film: A log-encoded “film workflow” oriented option that’s specifically
designed for version 4 of the Blackmagic Design color science. This option is designed to fit the
maximum amount of information from wide latitude BMD cameras into the data range of 0–1023.
Using this setting provides all the dynamic range from the source media into a signal that can
be transcoded to other formats with no compromise. However, this is not a viewable image and
requires grading to normalize it into an image that can be delivered to audiences.
171Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
Blackmagic Design Video: The standardized gamma curve for standard-dynamic-range HD
and UHD display. For wide-latitude images, highlights will be clipped, but all image data will be
preserved internally for retrieval via grading as necessary.
Blackmagic Design Extended Video: An SDR-compatible gamma curve similar to the above but
with compressed highlights that preserve more highlight detail in the visible range of the image.
Intended to be a fast starting point for grading SDR images. Fewer highlights are clipped, but
nonetheless all image data is preserved internally for retrieval via grading as necessary.
Blackmagic Design Custom: For specialty workflows.
```
Linear: A scene linear setting, suitable for visual effects and specialty workflows.
```
Rec. 2100 Hybrid Log Gamma: The standardized gamma curve for the HLG standard of
```
high-dynamic-range (HDR) video jointly developed by the BBC and NHK.
```
```
Rec. 2100 ST2084 (PQ): The standardized gamma curve for high-dynamic-range (HDR) video as
```
encoded by Dolby Vision and HDR10+. Also referred to as the PQ curve.
 Highlight Recovery: A checkbox that lets you include additional highlight sensor data that’s
usually clipped by the standard decoding matrix. In cases where you have extremely clipped
peak highlights, you may obtain additional image detail this way, although it may contain unusual
color artifacts.
```
 Gamut compression: Prevents monochromatic highly saturated light sources (LEDs, neon
```
```
signs, etc.) from clipping the gamut.
```
 Apply LUT: Applies color metadata to the BRAW file from the selected LUT source.
 LUT source: Choose the color metadata from the sidecar file, or the metadata
embedded in the clip.
```
 Saturation: Adjusts the color intensity of the image. 1 is unity. The range is 0 (desaturated)
```
```
through +4 (extremely high).
```
 Contrast: Increases contrast by raising the top of the signal and lowering the bottom of the signal
```
about the Midpoint slider (described below). Raising this value increases contrast, while lowering
```
```
this value lowers contrast. 1 is unity. The range is 0 (minimum contrast) to +2 (maximum contrast).
```
 Midpoint: The level about which contrast is either expanded or contracted. 0.41 is unity.
```
The range is 0 (black) to +1 (maximum white).
```
 Highlight Rolloff: Makes it easy to selectively retrieve blown-out highlight detail in high-dynamic-
range media by lowering this parameter and achieves a smooth blend between the retrieved
```
highlights and the unadjusted midtones for a naturalistic result. 1 is unity. The range is 0 (minimum)
```
```
through +2 (maximum).
```
 Shadow Rolloff: Lets you selectively lighten or darken shadow detail. Raising this value
retrieves shadow detail recorded below 0 percent while leaving the midtones alone. 1 is unity.
```
The range is 0 (minimum) through +2 (very high).
```
 White Level: A gain setting for adjusting the highlights.
 Black Level: A lift setting for adjusting the shadows.
 Use Video Black Level: A legacy video setting that adds pedestal to the video signal. For people
using video equipment dating from when shoulder pads were cool.
172Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
Use Camera Metadata
The most elemental camera metadata settings for exposure and color that are available. Deselect the
Use Camera Metadata checkboxes to activate the controls.
 Exposure: Increases or lowers image lightness in units relative to ƒ-stops. If your intended
```
exposure adjustment lifts image data above the maximum white level, don’t worry; all image data
```
is preserved and can be retrieved in subsequent adjustments. 0 is unity. The range is –5 to +5.
 Color Temp: Only available when White Balance is set to something other than As Shot. Designed
to alter the “warmth” of the image. Adjustable in Kelvin. Lower values correct for “warmer” lighting,
while higher values correct for “cool” lighting. +5500 is unity. The range is +2000 to +50,000.
 Tint: Only available when White Balance is set to something other than As Shot. Designed to alter
the green to magenta balance of the image, for images with fluorescent tinting. Lower values add
green to compensate for magenta lighting, while higher values add magenta to compensate for
green lighting. 0 is unity. The range is –150 to +150.
BRAW Files and Blackmagic Design Film
Blackmagic Design’s logarithmically encoded Blackmagic Design Film gamma setting,
which produces flat-contrast, wide-gamut image data that preserves image detail with a
wide latitude for adjustment, is a modified version of the standard Cineon curve. However,
the modifications are designed to emphasize the strengths of the sensors used by the
Blackmagic Design cameras. Similarly to working with clips using Cineon, the ARRI
ALEXA’s Log-C gamma, or Sony’s proprietary S-Log or S-Log2 formats, you need to
```
normalize clips using Blackmagic Design Film by using Resolve Color Management (RCM), by
```
making a manual adjustment to color and contrast, or by applying a LUT, using techniques
discussed previously.
Canon RAW
```
Canon RAW (CRW) is produced by a variety of Canon cameras.
```
Master Settings
These parameters let you choose the decode quality and method that raw clips will be transformed to
use when debayered.
 Decode Quality: Lets you debayer Canon RAW files at Full, Half, or Quarter resolution to improve
performance on slower systems. Lower resolution media is lower quality but faster to work with
and process. If necessary, you can choose a lower resolution setting that provides better real time
playback on systems with limited performance while you work, and then switch to a higher quality
when rendering the final output. A “Force debayer res to highest quality” checkbox in the Render
Settings list of the Deliver page makes it easy to follow this workflow.
 Decode Using: The option you select determines whether all Canon RAW media throughout the
```
project is decoded using the original Camera Metadata settings (the default selection), using
```
Project settings in which you choose custom settings to be applied to all clips, or using the Canon
RAW default settings.
173Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
Project Settings
Canon RAW has a variety of settings that can be adjusted to alter the image quality of the debayered
result. The Color Temp and Tint parameters are only available if the White Balance drop-down menu is
set to Custom.
 White Balance: The first seven options offer White Balance presets, which automatically adjust
the Color Temp and Tint parameters. These options include Daylight, Cloudy, Shade, Tungsten,
Fluorescent, and Flash. An eighth option, Custom, makes the Color Temp and Tint parameters
user-adjustable.
 Color Space: Choose Canon Cinema Gamut or other common colorspaces.
 Gamma: Choose a Canon Log version or Rec 709.
 Sharpness: A debayer-specific sharpness filter applied to provide the appearance of enhanced
image detail. 20 is unity. The range is 0 to 100.
 Highlights: Makes it easy to selectively retrieve blown-out highlight detail in high-dynamic-range
media by lowering this parameter and achieves a smooth blend between the retrieved highlights
```
and the unadjusted midtones for a naturalistic result. 0 is unity. The range is –100 (minimum)
```
```
through +100 (maximum).
```
 Shadows: Lets you selectively lighten or darken shadow detail. Raising this value retrieves
shadow detail recorded below 0 percent, while leaving the midtones alone. 0 is unity. The range is
```
–100 (minimum) through +100 (very high).
```
 Color Boost: Lets you naturalistically raise the saturation of regions of low saturation, sometimes
referred to as a vibrance operation. Can be used also to lower the saturation of regions of low
```
saturation. 0 is unity. The range is –100 (minimum) through +100 (very high).
```
```
 Saturation: Adjusts the color intensity of the image. 0 is unity. The range is –100 (minimum)
```
```
through +100 (very high).
```
 Midtone Detail: When this parameter is raised, the contrast of regions of the image with high edge
detail is raised to increase the perception of image sharpness, sometimes referred to as definition.
When this parameter is lowered to a negative value, regions of the image with low amounts of
```
detail are softened while areas of high detail are left alone. 0 is unity. The range is –100 (minimum)
```
```
through +100 (very high).
```
 Lift: Adjusts the black point of the media, raising it or lowering it while scaling all midtone values
between it and the white point. Regardless of how you adjust this control, all image data is
preserved and can be retrieved in subsequent adjustments. The range is –100 to +100.
 Gain: Adjusts the white point of the media, raising or lowering it while scaling all midtone values
between it and the black point. Regardless of how you adjust this control, all image data is
preserved and can be retrieved in subsequent adjustments. 0 is unity. The range is –100 to +100.
 Contrast: Raising contrast reduces shadows and raises highlights, while leaving midtones at 50
percent unaffected. Regardless of how you adjust this control, all image data is preserved and can
be retrieved in subsequent adjustments. 0 is unity. The range is –100 to +100.
Use Camera Metadata
The most elemental camera metadata settings for exposure and color that are available.
 Exposure: Increases or lowers image lightness in units relative to ƒ-stops. If your intended
```
exposure adjustment lifts image data above the maximum white level, don’t worry; all image data
```
is preserved and can be retrieved in subsequent adjustments. 0 is unity. The range is –5 to +5.
174Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
 Color Temp: Only available when White Balance is set to something other than As Shot. Designed
to alter the “warmth” of the image. Adjustable in Kelvin. Lower values correct for “warmer” lighting,
while higher values correct for “cool” lighting. +6500 is unity. The range is +2000 to +50,000.
 Tint: Only available when White Balance is set to something other than As Shot. Designed to alter
the green to magenta balance of the image, for images with fluorescent tinting. Lower values add
green to compensate for magenta lighting, while higher values add magenta to compensate for
green lighting. 0 is unity. The range is –150 to +150.
CinemaDNG
CinemaDNG is an open format capable of high-resolution raw image data with a wide dynamic range
and is one of the formats recorded by the Blackmagic Design Camera when you shoot in raw mode.
CinemaDNG images are decoded with full dynamic range when the Highlight Recovery checkbox
is selected.
DaVinci Resolve version 11.2.1 introduced improved debayering for raw CinemaDNG media acquired
using any of the Blackmagic Design cameras. The “Apply Pre Tone Curve” setting controls whether
```
you’re using the older debayering method (when turned on) or the newer, visually improved
```
```
debayering method (when turned off).
```
Master Settings
These parameters let you choose the decode quality, white balance, color space, and gamma that raw
CinemaDNG clips will be transformed to use when debayered.
 Decode Quality: Lets you debayer CinemaDNG raw files at Full, Half, or Quarter resolution to
improve performance on slower systems. Lower resolution media is lower quality but faster to
work with and process. If necessary, you can choose a lower resolution setting that provides
better real time playback on systems with limited performance while you work, and then switch
to a higher quality when rendering the final output. A “Force debayer res to highest quality”
checkbox in the Render Settings list of the Deliver page makes it easy to follow this workflow.
 Decode Using: The option you select determines whether all CinemaDNG media throughout
```
the project is decoded using the original Camera Metadata settings (the default selection), using
```
Project settings in which you choose custom settings to be applied to all clips, or using the
CinemaDNG default settings.
```
 Apply Pre Tone Curve: When this checkbox is turned off (the default for new projects created
```
```
in DaVinci Resolve 11.2.1 or later), DaVinci Resolve debayers CinemaDNG raw media using an
```
improved method that delivers better-looking results, specifically for media acquired using any
```
of the Blackmagic Design cameras. When this checkbox is turned on (the default for projects
```
```
created in earlier versions of DaVinci Resolve), the older debayering method is reenabled for
```
backward compatibility. However, turning Pre Tone Curve on may also provide better results for
CinemaDNG raw files coming from other sources. If you’re importing .dng media from cameras
other than those from Blackmagic Design, you should try both settings to see which type of
debayering you prefer.
 Apply Soft Clip: This checkbox is only available when Apply Pre Tone Curve is turned off. When
```
turned on, high dynamic range parts of the signal (super-white highlights) are brought back into
```
the picture as visible image detail you can adjust, similar to using the Highlights control to retrieve
these otherwise clipped parts of the signal.
175Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
Project Settings
CinemaDNG has a variety of settings that can be adjusted to alter the image quality of the debayered
result. The Color Temp and Tint parameters are only available if the White Balance drop-down menu is
set to Custom.
 Color Science: Lets you choose what version of camera color science you want to use
to decode CinemaDNG media.
Camera Metadata: Chooses whichever version of color science was selected by
the camera at the time of shooting.
Gen 4: The original version of color science available for recording and decoding
CinemaDNG media.
 White Balance: The first seven options offer White Balance presets, which automatically
adjust the Color Temp and Tint parameters. These options include: Daylight, Cloudy, Shade,
Tungsten, Fluorescent, and Flash. An eighth option, Custom, makes the Color Temp and Tint
parameters user-adjustable.
 Color Space: Multiple color spaces are adjustable, depending on your intended workflow:
Rec. 709: Decodes into the standard color space specified by the Rec. 709 standard for high
definition video.
P3 D60: Decodes into the standard P3 color space specified by the DCI standard for digital
cinema projection.
Blackmagic Design: Decodes into a log-encoded color space that remaps the raw data into an
approximation of the Log-C standard. Choosing Blackmagic Design Film also forces the Gamma
setting to Blackmagic Design Film. This setting produces flat-contrast image data that preserves
image detail with a wide latitude for adjustment, which is suitable as a starting point for detailed
grading and is also compatible with log workflows intended for film output.
 Gamma: Five gamma settings are available, depending on what starting point you want to use for
further grading.
2.4: A simple power-function gamma setting commonly used for broadcast.
2.6: A simple power-function gamma setting commonly used for digital cinema projection.
Rec. 709: A gamma of 2.35, with a linear segment near black, approximating the EBU
recommended gamma for broadcast.
```
sRGB: A gamma of 2.2, with a linear segment near black, intended for reproduction on computer
```
displays alongside the sRGB color space.
```
Linear: A simple linear gamma setting.
```
Blackmagic Design Film: A log-encoded gamma setting that approximates Cineon encoding, the
main difference being that more data is encoded in the darkest portion of the Blackmagic Design
Film signal. When you choose this setting, the appropriate variation of gamma will be applied
based on your particular sensor, be it 4K or 4.6K.
Blackmagic Design Video: A normalized gamma setting that provides a fast starting point for
grading if you don’t want to begin with a log-encoded image.
 Highlight Recovery: A checkbox that lets you include additional highlight sensor data that’s
usually clipped by the standard decoding matrix. In cases where you have extremely clipped
highlights, you may obtain additional image detail this way, although it may contain unusual
color artifacts.
 Sharpness: A debayer-specific sharpness filter applied to provide the appearance of enhanced
image detail. 20 is unity. The range is 0 to 100.
176Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
 Highlights: Makes it easy to selectively retrieve blown-out highlight detail in high-dynamic-range
media by lowering this parameter and achieves a smooth blend between the retrieved highlights
```
and the unadjusted midtones for a naturalistic result. 0 is unity. The range is –100 (minimum)
```
```
through +100 (maximum).
```
 Shadows: Lets you selectively lighten or darken shadow detail. Raising this value retrieves shadow
detail recorded below 0 percent, while leaving the midtones alone. 0 is unity. The range is –100
```
(minimum) through +100 (very high).
```
 Color Boost: Lets you naturalistically raise the saturation of regions of low saturation, sometimes
referred to as a vibrance operation. Can be used also to lower the saturation of regions of low
```
saturation. 0 is unity. The range is –100 (minimum) through +100 (very high).
```
```
 Saturation: Adjusts the color intensity of the image. 0 is unity. The range is –100 (minimum)
```
```
through +100 (very high).
```
 Midtone Detail: When this parameter is raised, the contrast of regions of the image with high edge
detail is raised to increase the perception of image sharpness, sometimes referred to as definition.
When this parameter is lowered to a negative value, regions of the image with low amounts of
```
detail are softened while areas of high-detail are left alone. 0 is unity. The range is –100 (minimum)
```
```
through +100 (very high).
```
 Lift: Adjusts the black point of the media, raising it or lowering it while scaling all midtone values
between it and the white point. Regardless of how you adjust this control, all image data is
preserved and can be retrieved in subsequent adjustments. The range is –100 to +100.
 Gain: Adjusts the white point of the media, raising or lowering it while scaling all midtone values
between it and the black point. Regardless of how you adjust this control, all image data is
preserved and can be retrieved in subsequent adjustments. 0 is unity. The range is –100 to +100.
 Contrast: Raising contrast reduces shadows and raises highlights, while leaving midtones at
50 percent unaffected. Regardless of how you adjust this control, all image data is preserved and
can be retrieved in subsequent adjustments. 0 is unity. The range is –100 to +100.
Use Camera Metadata
The most elemental camera metadata settings for exposure and color that are available.
 Exposure: Increases or lowers image lightness in units relative to ƒ-stops. If your intended
```
exposure adjustment lifts image data above the maximum white level, don’t worry; all image data
```
is preserved and can be retrieved in subsequent adjustments. 0 is unity. The range is –5 to +5.
 Color Temp: Only available when White Balance is set to something other than As Shot. Designed
to alter the “warmth” of the image. Adjustable in Kelvin. Lower values correct for “warmer” lighting,
while higher values correct for “cool” lighting. +6500 is unity. The range is +2000 to +50,000.
 Tint: Only available when White Balance is set to something other than As Shot. Designed to alter
the green to magenta balance of the image, for images with fluorescent tinting. Lower values add
green to compensate for magenta lighting, while higher values add magenta to compensate for
green lighting. 0 is unity. The range is –150 to +150.
177Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
CinemaDNG Files and Blackmagic Design Film
Blackmagic Design’s logarithmically encoded Blackmagic Design Film gamma setting,
which produces flat-contrast, wide-gamut image data that preserves image detail with a
wide latitude for adjustment, is a modified version of the standard Cineon curve. However,
the modifications are designed to emphasize the strengths of the sensors used by the
Blackmagic Design cameras. Similarly to working with clips using Cineon, the ARRI ALEXA’s
Log-C gamma, or Sony’s proprietary S-Log or S-Log2 formats, you need to normalize clips
```
using Blackmagic Design Film by using Resolve Color Management (RCM), by making a
```
manual adjustment to color and contrast, or by applying a LUT, using the same techniques
discussed previously.
Nikon RAW
```
Nikon RAW (NEF) is produced by a variety of Nikon cameras.
```
Master Settings
These parameters let you choose the decode quality and method that raw clips will be transformed to
use when debayered.
 Decode Quality: Lets you debayer Nikon RAW files at Full, Half, or Quarter resolution to improve
performance on slower systems. Lower resolution media is lower quality but faster to work with
and process. If necessary, you can choose a lower resolution setting that provides better real time
playback on systems with limited performance while you work, and then switch to a higher quality
when rendering the final output. A “Force debayer res to highest quality” checkbox in the Render
Settings list of the Deliver page makes it easy to follow this workflow.
 Decode Using: The option you select determines whether all Nikon RAW media throughout the
```
project is decoded using the original Camera Metadata settings (the default selection), using
```
Project settings in which you choose custom settings to be applied to all clips, or using the Nikon
RAW default settings.
Project Settings
Nikon RAW has a variety of settings that can be adjusted to alter the image quality of the debayered
result. The Color Temp and Tint parameters are only available if the White Balance drop-down menu is
set to Custom.
 White Balance: The first seven options offer White Balance presets, which automatically adjust
the Color Temp and Tint parameters. These options include Daylight, Cloudy, Shade, Tungsten,
Fluorescent, and Flash. An eighth option, Custom, makes the Color Temp and Tint parameters user
adjustable.
 Color Space: Choose one of the common video colorspaces.
 Gamma: Choose N-Log or one of the common video colorspaces.
 Sharpness: A debayer-specific sharpness filter applied to provide the appearance of enhanced
image detail. 20 is unity. The range is 0 to 100.
 Highlights: Makes it easy to selectively retrieve blown-out highlight detail in high-dynamic-range
media by lowering this parameter and achieves a smooth blend between the retrieved highlights
```
and the unadjusted midtones for a naturalistic result. 0 is unity. The range is –100 (minimum)
```
```
through +100 (maximum).
```
178Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
 Shadows: Lets you selectively lºighten or darken shadow detail. Raising this value retrieves
shadow detail recorded below 0 percent, while leaving the midtones alone. 0 is unity. The range is
```
–100 (minimum) through +100 (very high).
```
 Color Boost: Lets you naturalistically raise the saturation of regions of low saturation, sometimes
referred to as a vibrance operation. Can be used also to lower the saturation of regions of low
```
saturation. 0 is unity. The range is –100 (minimum) through +100 (very high).
```
```
 Saturation: Adjusts the color intensity of the image. 0 is unity. The range is –100 (minimum)
```
```
through +100 (very high).
```
 Midtone Detail: When this parameter is raised, the contrast of regions of the image with high edge
detail is raised to increase the perception of image sharpness, sometimes referred to as definition.
When this parameter is lowered to a negative value, regions of the image with low amounts of
```
detail are softened, while areas of high detail are left alone. 0 is unity. The range is –100 (minimum)
```
```
through +100 (very high).
```
 Lift: Adjusts the black point of the media, raising it or lowering it while scaling all midtone values
between it and the white point. Regardless of how you adjust this control, all image data is
preserved and can be retrieved in subsequent adjustments. The range is –100 to +100.
 Gain: Adjusts the white point of the media, raising or lowering it while scaling all midtone values
between it and the black point. Regardless of how you adjust this control, all image data is
preserved and can be retrieved in subsequent adjustments. 0 is unity. The range is –100 to +100.
 Contrast: Raising contrast reduces shadows and raises highlights, while leaving midtones at 50
percent unaffected. Regardless of how you adjust this control, all image data is preserved and can
be retrieved in subsequent adjustments. 0 is unity. The range is –100 to +100.
Use Camera Metadata
The most elemental camera metadata settings for exposure and color that are available.
 Lens Distortion: Check this box to apply automatic Lens Distortion Correction.
 Lens Vignette: Adjusts the correction strength to control vignetting.
 Exposure: Increases or lowers image lightness in units relative to ƒ-stops. If your intended
```
exposure adjustment lifts image data above the maximum white level, don’t worry; all image data
```
is preserved and can be retrieved in subsequent adjustments. 0 is unity. The range is –5 to +5.
 Color Temp: Only available when White Balance is set to something other than As Shot. Designed
to alter the “warmth” of the image. Adjustable in Kelvin. Lower values correct for “warmer” lighting,
while higher values correct for “cool” lighting. +6500 is unity. The range is +2000 to +50,000.
 Tint: Only available when White Balance is set to something other than As Shot. Designed to alter
the green to magenta balance of the image for images with fluorescent tinting. Lower values add
green to compensate for magenta lighting, while higher values add magenta to compensate for
green lighting. 0 is unity. The range is –150 to +150.
179Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
Panasonic Varicam RAW
```
Panasonic Varicam RAW (CRW) is produced by a variety of Panasonic cameras (such as the VariCam
```
```
35 and VariCam Pure 4K) recording to Codex VRAW recorders.
```
Master Settings
These parameters let you choose the decode quality, white balance, color space, and gamma that raw
clips will be transformed to use when debayered.
 Decode Quality: Lets you debayer Varicam RAW files at Full, Half, or Quarter resolution to improve
performance on slower systems. Lower resolution media is lower quality but faster to work with
and process. If necessary, you can choose a lower resolution setting that provides better real time
playback on systems with limited performance while you work, and then switch to a higher quality
when rendering the final output. A “Force debayer res to highest quality” checkbox in the Render
Settings list of the Deliver page makes it easy to follow this workflow.
 Decode Using: The option you select determines whether all Varicam RAW media throughout
```
the project is decoded using the original Camera Metadata settings (the default selection), using
```
Project settings in which you choose custom settings to be applied to all clips, or using the
Varicam RAW default settings.
Project Settings
Panasonic Varicam RAW has a variety of settings that can be adjusted to alter the image quality of the
debayered result. The Color Temp and Tint parameters are only available if the White Balance drop-
down menu is set to Custom.
 White Balance: The first seven options offer White Balance presets, which automatically adjust
the Color Temp and Tint parameters. These options include: Daylight, Cloudy, Shade, Tungsten,
Fluorescent, and Flash. An eighth option, Custom, makes the Color Temp and Tint parameters
user-adjustable.
 Sharpness: A debayer-specific sharpness filter applied to provide the appearance of enhanced
image detail. 20 is unity. The range is 0 to 100.
 Highlights: Makes it easy to selectively retrieve blown-out highlight detail in high-dynamic-range
media by lowering this parameter and achieves a smooth blend between the retrieved highlights
```
and the unadjusted midtones for a naturalistic result. 0 is unity. The range is –100 (minimum)
```
```
through +100 (maximum).
```
 Shadows: Lets you selectively lighten or darken shadow detail. Raising this value retrieves
shadow detail recorded below 0 percent, while leaving the midtones alone. 0 is unity. The range is
```
–100 (minimum) through +100 (very high).
```
 Color Boost: Lets you naturalistically raise the saturation of regions of low saturation, sometimes
referred to as a vibrance operation. Can be used also to lower the saturation of regions of low
```
saturation. 0 is unity. The range is –100 (minimum) through +100 (very high).
```
```
 Saturation: Adjusts the color intensity of the image. 0 is unity. The range is –100 (minimum)
```
```
through +100 (very high).
```
 Midtone Detail: When this parameter is raised, the contrast of regions of the image with high edge
detail is raised to increase the perception of image sharpness, sometimes referred to as definition.
When this parameter is lowered to a negative value, regions of the image with low amounts of
```
detail are softened while areas of high-detail are left alone. 0 is unity. The range is –100 (minimum)
```
```
through +100 (very high).
```
180Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
 Lift: Adjusts the black point of the media, raising it or lowering it while scaling all midtone values
between it and the white point. Regardless of how you adjust this control, all image data is
preserved and can be retrieved in subsequent adjustments. The range is –100 to +100.
 Gain: Adjusts the white point of the media, raising or lowering it while scaling all midtone values
between it and the black point. Regardless of how you adjust this control, all image data is
preserved and can be retrieved in subsequent adjustments. 0 is unity. The range is –100 to +100.
 Contrast: Raising contrast reduces shadows and raises highlights, while leaving midtones at 50
percent unaffected. Regardless of how you adjust this control, all image data is preserved and can
be retrieved in subsequent adjustments. 0 is unity. The range is –100 to +100.
Use Camera Metadata
The most elemental camera metadata settings for exposure and color that are available.
 Color Temp: Only available when White Balance is set to something other than As Shot. Designed
to alter the “warmth” of the image. Adjustable in Kelvin. Lower values correct for “warmer” lighting,
while higher values correct for “cool” lighting. +6500 is unity. The range is +2000 to +50,000.
 Tint: Only available when White Balance is set to something other than As Shot. Designed to alter
the green to magenta balance of the image, for images with fluorescent tinting. Lower values add
green to compensate for magenta lighting, while higher values add magenta to compensate for
green lighting. 0 is unity. The range is –150 to +150.
Phantom Cine
The Phantom line of high-speed digital cinema cameras record wide latitude, high-gamut media
using the Cine Raw format.
Master Settings
These parameters let you choose the decode quality, white balance, color space, and gamma that raw
Phantom Cine clips will be transformed to use when debayered.
 Decode Using: The option you select determines whether all Phantom Cine media throughout
```
the project is decoded using the original Camera Metadata settings (the default selection), using
```
Project settings in which you choose custom settings to be applied to all clips, or using the Cine
default settings.
 Timecode: There are four types of timecode that Phantom Cine files can be set to use:
Set to zero: Camera timecode is ignored, instead using a simple frame count with
the first frame considered 0.
```
Time of day (Local): Time of day timecode recording.
```
```
Time of day (GMT): Time of day timecode recording based on Greenwich Mean Time.
```
```
SMPTE: Standard SMPTE timecode.
```
Project Settings
The following settings for exposure, color, and sharpness are available.
 Gamma: Three options are available for setting the gamma of the debayered output:
 Rec. 709
 Log 1
 Log 2
181Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
 Lift: Adjusts the black point of the media, raising it or lowering it while scaling all midtone values
between it and the white point. Regardless of how you adjust this control, all image data is
preserved and can be retrieved in subsequent adjustments. The range is –100 to +100.
 Gain: Adjusts the white point of the media, raising or lowing it while scaling all midtone values
between it and the black point. Regardless of how you adjust this control, all image data is
preserved and can be retrieved in subsequent adjustments. 0 is unity. The range is –100 to +100.
 Contrast: Raising contrast reduces shadows and raises highlights, while leaving midtones at
50 percent unaffected. Regardless of how you adjust this control, all image data is preserved and
can be retrieved in subsequent adjustments. 0 is unity. The range is –100 to +100.
 Sharpness: A debayer-specific sharpness filter applied to provide the appearance of enhanced
image detail. 20 is unity. The range is 0 to 100.
 Highlights: Makes it easy to selectively retrieve blown-out highlight detail in high-dynamic-range
media by lowering this parameter and achieves a smooth blend between the retrieved highlights
```
and the unadjusted midtones for a naturalistic result. 0 is unity. The range is –100 (minimum)
```
```
through +100 (maximum).
```
 Shadows: Lets you selectively lighten or darken shadow detail. Raising this value retrieves
shadow detail recorded below 0 percent, while leaving the midtones alone. 0 is unity.
```
The range is –100 (minimum) through +100 (very high).
```
 Color Boost: Lets you naturalistically raise the saturation of regions of low saturation, sometimes
referred to as a vibrance operation. Can be used also to lower the saturation of regions of low
```
saturation. 0 is unity. The range is –100 (minimum) through +100 (very high).
```
```
 Saturation: Adjusts the color intensity of the image. 0 is unity. The range is –100 (minimum)
```
```
through +100 (very high).
```
 Midtone Detail: When this parameter is raised, the contrast of regions of the image with high edge
detail is raised to increase the perception of image sharpness, sometimes referred to as definition.
When this parameter is lowered to a negative value, regions of the image with low amounts of
```
detail are softened while areas of high detail are left alone. 0 is unity. The range is –100 (minimum)
```
```
through +100 (very high).
```
RED
R3D source media, recorded by the various models of RED DIGITAL CINEMA cameras, contains one
of the most elaborate sets of raw parameters of any of the camera formats. These settings are divided
into four different groups.
Master RED Settings
The Master RED settings are the most important, handling decode quality and the control governing
whether the original camera metadata is used, or if you’re overriding the camera metadata project-
wide with custom settings.
These settings also contain the drop-down menus that let you choose the color space and gamma
curve used to transform the raw image data into image data for processing in DaVinci Resolve when
debayering R3D clips. Which Color Space and Gamma Curve settings you use are solely a matter of
```
preference; there is no absolute requirement to use one or the other for any given type of workflow.
```
You’re simply looking for settings that provide the best starting point for the media you have, given the
type of grading you’re looking to do.
182Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
For example, in many cases combining the REDcolor3 Color Space setting and REDlog Film gamma
curve will offer a starting point that retains the most image detail with the greatest latitude for
adjustment. On the other hand, if you’re working in a hurry, for example to generate dailies for offline
editing, using one of the REDcolor Color Space settings with one of the REDgamma settings can
offer an image that’s more immediately pleasing and that requires fewer adjustments to achieve
an acceptable result. These are not recommendations, they’re only examples. As always, the ideal
settings for your project depend heavily on the quality of the source media, so you should experiment
with media from your own projects to find the most suitable results to your eye.
Master
These top settings determine the image quality that you’re choosing to extract from the R3D source
media. The tradeoff is that higher quality media at higher resolution will be more processor-intensive
to debayer, depending on your workstation’s capabilities.
 Decode Quality: Determines the image quality of the decoded R3D data that’s handed off to
the DaVinci Resolve image processing pipeline. The Decode Quality you select has a direct
impact on real time performance. Decoding performance depends entirely on the hardware
capabilities of your system.
On the most modern systems, R3D files can be decoded using accelerated GPU-based
debayering if you set the Use GPU for R3D drop-down menu to Debayer in the Decode Options
panel of the DaVinci Resolve System Settings. DaVinci Resolve 16.1.2 introduced the latest RED
API-enabling 8K-accelerated debayering using Cuda. Otherwise, R3D files can be decoded with
high performance using multi-core CPU processing if your workstation has fast enough CPUs.
If necessary, you can also choose a lower quality setting that provides better real time playback
on systems with limited performance while you work, and then switch to a higher quality when
rendering the final output. A “Force debayer res to highest quality” checkbox in the Render
Settings list of the Deliver page makes it easy to follow this workflow.
 Bit Depth: DaVinci Resolve can decode R3D files with 8-, 10-, or 16-bit image data for processing.
Choosing 16-bit for maximum quality may impact playback performance on some hardware.
 Timecode: The timecode recorded for R3D media depends on the camera setting in use when it
was shot. There are three choices:
```
Camera: This setting automatically selects between Absolute and Edge depending on what was
```
chosen as the default timecode mode on the camera. This setting needs to be selected before
you add R3D media to the Media Pool. If you’re browsing R3D media when you change this
setting, you should refresh the folder in the Library of the Media Pool before adding media to the
Media Pool.
```
Absolute: The default. Records “time of day” timecode. If an external timecode source was
```
connected and the camera was put into Jam Sync mode, the external timecode would have been
recorded instead.
```
Edge: The first recorded clip for each magazine starts at 01:00:00:00, and the timecode of each
```
subsequent clip is recorded sequentially and continuously.
 Decode Using: The option you select determines whether all R3D media throughout the project is
```
decoded using the original Camera Metadata settings (the default selection), using Project settings
```
in which you choose custom settings to be applied to all clips, or using the RED default settings.
Project Settings
These settings control the fundamental methods used to debayer R3D media. The selections you
make to these settings determine the basic color and contrast that you’re choosing to extract from the
camera raw image data.
183Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
 Color Science: The options are Original, which was the color science used by early builds of the
REDone camera, Version 2, and IPP2, which is the current version of color science used by the
entire RED camera line. Unless you need to match the look of older projects using the older color
science, the newest color science is generally preferable.
 Color Space: Because RED cameras record R3D data which uses a raw color space, debayering
the native R3D data requires choosing a color space to convert the raw signal into. Bear in mind
that the color space you choose is merely a starting point for further correction. There is no
requirement that you choose one or the other color space for any given workflow. You should
choose the color space that provides the most pleasing starting point for your particular project.
```
DragonColor2: A further optimized version of DragonColor that is especially recommended for
```
underwater footage.
```
REDcolor4: A further optimized version of REDcolor3 that is especially recommended
```
for underwater footage.
```
REDWideGamutRGB: Part of RED’s IPP2 (image processing pipeline 2) initiative; this is a camera
```
color space designed to encompass all colors that can be recorded by RED cameras without
clipping, and is meant to provide a single common starting point for all models of RED cameras, for
convenient grading to HDR or SDR workflows.
Rec. 2020: Decodes into the standard color space specified by the Rec. 2020 standard for high
definition video, UHD video, and beyond. While you may find this option useful, it is not required
for programs being output to video.
Rec. 709: Decodes into the standard color space specified by the Rec. 709 standard for high
definition video. While you may find this option useful, it is not required for programs being
output to video.
```
sRGB: Decodes into the standard color space defined by the sRGB standard, typically used for
```
computer display.
```
Adobe1998: Decodes into Adobe’s unique version of the sRGB standard.
```
DCI-P3: Decodes to an RGB-encoded image data with a D61 white point, intended for use when
outputting media for DCI mastering.
DCI-P3 D65: Decodes RGB-encoded image data with a D65 white point, intended for monitoring
with a P3-compatible display.
ProPhoto RGB: A color space developed by Kodak that offers a large gamut intended for
photography. An idiosyncrasy of this color space is that the green and blue primary points are
outside the boundaries of visible color, meaning this gamut encompasses “imaginary” colors in
order to achieve an extremely large gamut.
```
CameraRGB: Outputs the original, unmodified sensor data. Not a recommended setting.
```
```
REDspace: Fits the raw R3D image data into a color space thatʼs larger than that of Rec. 709.
```
Appropriate for digital cinema mastering and film output. REDspace was the predecessor to the
REDcolor setting.
```
REDcolor: A color space thatʼs similar to the Rec. 709 option, but modified to balance accuracy
```
with pleasing color rendition, emphasizing accurate skin tones.
```
REDcolor2: Similar, but less saturated than, REDcolor.
```
```
REDcolor3: Similar saturation to REDcolor, but with additional modifications to improve the
```
color rendition of skin tone. Introduced as the optimum color space for Epic cameras, but also
appropriate for previous generations of RED cameras.
```
DragonColor: A color space optimized for cameras with the RED Dragon sensor, although this
```
color space can be used for previous generations of RED cameras as well.
184Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
 Gamma Curve: There are several options available for choosing a gamma profile to be used when
debayering the raw R3D data:
```
REDgamma4: The latest iteration of the REDgamma curve, designed to give a good in-camera
```
look without the need for grading, while retaining great dynamic range and highlight handling.
REDgamma4 is suitable for all RED cameras.
REDlog Film: An improved logarithmic gamma setting that’s designed to remap the original 12-bit
R3D data to the standard Cineon gamma curve. This setting produces flat-contrast image data that
preserves image detail with a wide latitude for adjustment, and is compatible with log workflows,
including those intended for film output.
```
Linear: No gamma adjustment is made, this is a linear-to-light representation of data from the RED
```
camera’s sensor.
Rec. 709: A gamma curve typical for Rec. 709 display. Does not provide an abundance of latitude
for grading.
Gamma 2.4: A simple power-function gamma setting commonly used for broadcast.
Gamma 2.6: A simple power-function gamma setting commonly used for digital cinema projection.
```
sRGB: Similar gamma setting to that employed by Rec. 709.
```
```
HDR ST.2084: The standardized gamma curve for high-dynamic-range (HDR) video. Also referred
```
to as the PQ curve.
Hybrid Log Gamma: The standardized gamma curve for the HLG standard of high-dynamic-range
```
(HDR) video jointly developed by the BBC and NHK.
```
BT.1886: The standardized gamma curve for standard-dynamic-range HD and UHD display. Does
not provide an abundance of latitude for grading.
```
Log3G12: An expanded option for RED’s IPP2 (image processing pipeline 2) initiative, this is a wide
```
dynamic range log space designed to encode camera data from all RED models to a common
starting point in RWG color space for convenient grading to HDR or SDR workflows. Log3G12
provides 12 stops of dynamic range above mid gray, 2 more stops than Log3G10. However, this is
at the expense of a slight loss of precision.
```
Log3G10: Part of RED’s IPP2 (image processing pipeline 2) initiative, this is a wide dynamic range
```
log space designed to encode camera data from all RED models to a common starting point in
RWG color space for convenient grading to HDR or SDR workflows. 3G represents the mapping of
18% mid gray to 1/3, and 10 represents the 10 stops of dynamic range above mid gray this supports.
PDlog 685: A logarithmic gamma setting that maps the native 12-bit RED image data into the linear
portion of a Cineon or film transfer curve.
PDlog 985: A logarithmic gamma setting with different mappings.
Custom PDlog: A logarithmic gamma setting that exposes user adjustable Black Point, White
Point, and Gamma PDlog parameters so you can customize your own log gamma curve.
```
REDspace: Similar to Rec. 709, but slightly altered to be more appealing, primarily through higher
```
contrast and lighter midtones. The predecessor to the REDgamma curve.
```
REDlog: A logarithmic gamma setting that maps the original 12-bit R3D image data to a 10-bit
```
curve. The blacks and midtones occupying the lowest 8 bits of the video signal maintain the
same precision as in the original 12-bit data, while the highlights that occupy the highest 4 bits
are compressed. While reducing the precision of highlight detail, the tradeoff is that there’s an
abundance of precision throughout the rest of the signal. This is a good setting for maintaining
maximum latitude.
```
REDgamma: An improved gamma curve designed to be perceptually appealing on displays
```
calibrated for Rec. 709, with an improved soft roll-off in the highlights to maintain highlight detail
while grading.
185Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
```
REDgamma2: Similar to REDgamma, with higher contrast.
```
```
REDgamma3: The most recent iteration of the REDgamma curve. Based on a log starting
```
point, but with a pleasing “ready to view” contrast curve applied, designed to be a visually
pleasing starting point that maintains excellent dynamic range. REDgamma3 is also designed to
work with REDcolor3.
 Blend Type: Works to control how RED HDRX media is used. When using either Simple or Magic
Motion to blend HDRX exposures, there’s no need to use the second output in the Node Editor.
You can choose from three options:
```
None: Only the regular exposure is used.
```
```
Simple: Blends the two HDRX exposures to achieve a pleasing middle ground.
```
Magic Motion: Uses a proprietary algorithm to combine the dual exposures to combine
overexposed and well-exposed regions of the picture in a more targeted fashion, while blending
the sharpness of the regularly exposed source with the motion blur of the underexposed source.
 Blend Bias: Lets you adjust how much of the regular exposure and how much of the
underexposure are combined.
 Apply Metadata Curves: If the R3D media files were preprocessed in REDCINE X Pro, and saved
with color curve metadata, you can use this setting to either use or discard that metadata.
```
 D.E.B. (Dragon Enhanced Blacks): A checkbox that enables the elimination of red noise in RED
```
cameras using the Dragon sensor.
 Embedded Audio: Enables embedded audio in R3D media.
Decoder Settings
This second group of settings contains additional controls for finessing the debayering of RED
raw image data. Which controls are exposed depends on which Color Science setting is selected
above. Many of the settings in this group are color correction adjustments, some of which resemble
analogous controls in the Color page. However, the FLUT and DRX controls manage the exposure of
the debayered media being fed to the DaVinci Resolve image processing pipeline, and so can be used
to retrieve image detail from R3D source media in cases where the default settings are clipping or
crushing detail in the highlights or shadows that would be unavailable to DaVinci Resolve as a result.
 De-noise: Applies image-wide noise reduction. There are seven settings available, from mild to
maximum, that you can use to balance noise reduction against any possible image degradation.
```
 OLPF Compensation: (color science versions 1 and 2) OLPF compensation applies a low pass filter
```
```
to reduce color moiré. There are four options: Off (the default), Low, Medium, and High.
```
```
 Image Detail: (color science versions 1 and 2) Controls the demosaicing algorithm that’s used for
```
the software decoding of R3D media. You can choose a level of sensor detail extraction: Low,
```
Medium, and High (recommended). If you’re using a RED ROCKET card, this setting is ignored as
```
there is a fixed algorithm that’s used.
```
 FLUT: (color science versions 1 and 2) A gain operation that lets you boost or attenuate the ISO in
```
smaller increments. 0 is unity. The range is –8 to +8.
 Contrast: Raising contrast reduces shadows and raises highlights, while leaving midtones at
50 percent unaffected. The image is compressed rather than clipped at the limits of 100 and 0
percent. 0 is unity. The range is –1 to +1.
```
 Saturation: (color science versions 1 and 2) Adjusts the color intensity of the image. 1 is unity.
```
```
The range is 0 (minimum) through 5.0 (very high).
```
```
 DRX: (color science versions 1 and 2) A Dynamic Range control (X) that lets you recover highlights
```
```
while taking into account Color Temperature (degrees Kelvin) and Tint. 0 is unity, and 1.0 is the
```
maximum value.
186Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
```
 Shadow: (color science version 1 and 2) Provides control over the toe (low range) of the
```
FLUT adjustment. 0 is unity. The range is –2 to +2.
 Brightness: Adjusts image lightness. Image data is compressed rather then clipped at
100 and 0 percent. 0 is unity. The range is –10 to +10.
 Flashing pixel adjust: A setting to apply noise reduction for removing or minimizing any flashing
pixels recorded from the sensor. Levels are: None, Low, Medium, and High.
Three additional parameters are available for IPP2 workflows, but they only function when DaVinci
Resolve is set to use DaVinci YRGB Color Managed color science and the Timeline to Output Gamut
Mapping in the Color Management panel of the Project Settings is set to RED IPP2 Gamut Mapping.
```
These controls (which are also mirrored in the Color Management panel when enabled) are designed
```
to let you tone map wide gamut media that’s being graded to a smaller gamut, such as Rec. 709.
The RED IPP2 Gamut Mapping controls that appear in the Color Management tab of the Project Settings
```
 Output Tone Map: (color science IPP2) Provides an easy setting for setting the resulting contract
```
```
when tone mapping wide dynamic range images to standard dynamic range (SDR) output. Settings
```
```
are: None, Low, Medium, and High. Low results in less contrast; High results in more contrast.
```
```
 Highlight Roll Off: (color science IPP2) Five settings let you adjust how much to roll off the
```
highlights to fit within the current gamut. These are: None, Hard, Medium, Soft, and Very Soft. Hard
```
provides a minimum of roll-off; Very Soft provides a maximum of roll-off. This setting interacts with
```
the HDR Peak Nits slider below.
```
 HDR Peak Nits: (color science IPP2) Adjusts the amount of highlight compression that’s done by
```
Highlight Roll Off.
Use Camera Metadata
The most elemental camera metadata settings for exposure and color that are available.
 ISO: A gain operation that keeps the black point at 0 while raising or lowering the white point
of the image, linearly scaling everything in between. Raising the ISO results only in boosted
```
highlights being more compressed; no clipping will occur. 320 is unity. The range is 50–6400.
```
 Exposure Adjust: Increases or lowers image lightness in units relative to ƒ-stops. Using exposure
to boost the image beyond 100 or to lower it below 0 will clip, not compress, the image data that’s
passed along to the DaVinci Resolve image processing pipeline. 0 is unity. The range is –7 to +7.
 Color Temp: Designed to alter the “warmth” of the image while keeping white elements of the
scene looking neutral. Adjustable in degrees Kelvin. Lower values correct for “warmer” lighting,
while higher values correct for “cool” lighting. This parameter is designed specifically to adjust
RED linear light image data to make the most photometrically accurate correction. 5600 is unity.
The range is 1700 to 10,000.
 Tint: Color balance correction for images with a green or magenta color cast, such as fluorescent
or sodium vapor bulbs. This parameter is designed specifically to adjust RED linear light image
data to make the most photometrically accurate correction. 0 is unity. The range is –100 to +100.
187Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
Sony RAW
Sony makes several digital cinema cameras, such as the F65 and F55, that record wide latitude, high-
gamut media either using Sony’s 12-bit SR codec, or as 16-bit raw media files. Since Sony’s cameras do
not use a traditional Bayer pattern, special debayering is necessary when working with F65 raw media,
and the image data is demosaiced using the following raw controls and parameters.
Master Settings
These parameters let you choose the decode quality, white balance, color space, and gamma that
Sony raw clips will be transformed to use when debayered.
 Decode Quality: Determines the image quality of the decoded Sony raw data that’s handed off to
the DaVinci Resolve image processing pipeline regardless of the Play Quality setting. The Decode
Resolution you select has a direct impact on real time performance, and decoding performance
depends entirely on the hardware capabilities of your system.
If necessary, you can choose a lower resolution setting that provides better real time playback
on systems with limited performance while you work, and then switch to a higher quality when
rendering the final output. A “Force debayer res to highest quality” checkbox in the Render
Settings list of the Deliver page makes it easy to follow this workflow.
 Decode Using: The option you select determines whether all F65 media throughout the project is
```
decoded using the original Camera Metadata settings (the default selection), using Project settings
```
in which you choose custom settings to be applied to all clips, or using the Sony default settings.
Project Settings
These settings control the fundamental methods used to debayer Sony raw media. The selections you
make to these settings determine the basic color and contrast that you’re choosing to extract from the
camera raw image data.
 White Balance: The first seven options offer White Balance presets, which automatically
adjust the Color Temp and Tint parameters. These options include: Daylight, Cloudy, Shade,
Tungsten, Fluorescent, and Flash. An eighth option, Custom, makes the Color Temp and Tint
parameters user-adjustable.
 Color Space: Multiple color spaces are adjustable, depending on your intended workflow:
Rec. 709: Decodes into the standard color space specified by the Rec. 709 standard for high
definition video.
P3 D60: Decodes RGB-encoded image data with a D60 white point, intended for monitoring with
a P3-compatible display.
```
SGamut: Decodes into Sony’s wider S-gamut color space, designed to provide the widest range
```
of image data for adjustment.
```
SGamut3: The gamut is identical to SGamut, but color reproduction is more accurate, according to
```
Sony’s “Technical Summary for S-Gamut3Cine/S-Log3 and S-Gamut3/S-Log3” whitepaper.
SGamut3.Cine: According to Sony’s “Technical Summary for S-Gamut3Cine/S-Log3 and
S-Gamut3/S-Log3” whitepaper, S-Gamut3.Cine is designed to provide a more traditionally log-
encoded workflow with color reproduction that is slightly wider than the P3 gamut.
```
P3: Decodes to an RGB-encoded image data with a D61 white point, intended for use when
```
outputting media for DCI mastering.
```
ACES: Decodes to image data that maps to the ACES profile for the camera that was used.
```
188Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
 Gamma: Five gamma settings are available, depending on what starting point you want to
use for further grading.
Gamma 2.4: A simple power-function gamma setting commonly used for broadcast.
Gamma 2.6: A simple power-function gamma setting commonly used for digital cinema projection.
Rec. 709: A gamma curve typical for Rec. 709 display.
```
SLog: Not designed for viewing, Sony’s SLog gammas are designed to provide a wide latitude for
```
```
grading; 14-stops according to Sony. 18% gray is at 38%.
```
```
SLog2: This version has a half stop offset from SLog to allow for a higher dynamic range.
```
18% gray is at 32%.
```
SLog3: An “easier to grade” version of SLog. 18% gray is at 40%. According to Sony’s
```
“Technical Summary for S-Gamut3Cine/S-Log3 and S-Gamut3/S-Log3,” SLog3 is designed to
provide a more traditionally log-encoded workflow, with a gamma curve that is similar, but not
identical, to Cineon workflows.
```
Linear: A simple linear gamma setting.
```
 Lift: Adjusts the black point of the media, raising it or lowering it while scaling all midtone values
between it and the white point. Regardless of how you adjust this control, all image data is
preserved and can be retrieved in subsequent adjustments. The range is –100 to +100.
 Gain: Adjusts the white point of the media, raising or lowering it while scaling all midtone values
between it and the black point. Regardless of how you adjust this control, all image data is
preserved and can be retrieved in subsequent adjustments. 0 is unity. The range is –100 to +100.
 Contrast: Raising contrast reduces shadows and raises highlights, while leaving midtones at 50
percent unaffected. Regardless of how you adjust this control, all image data is preserved and can
be retrieved in subsequent adjustments. 0 is unity. The range is –100 to +100.
 Sharpness: A debayer-specific sharpness filter applied to provide the appearance of enhanced
image detail. 20 is unity. The range is 0 to 100.
 Highlights: Makes it easy to selectively retrieve blown-out highlight detail in high-dynamic-range
media by lowering this parameter, and achieves a smooth blend between the retrieved highlights
```
and the unadjusted midtones for a naturalistic result. 0 is unity. The range is –100 (minimum)
```
```
through +100 (maximum).
```
 Shadows: Lets you selectively lighten or darken shadow detail. Raising this value retrieves shadow
detail recorded below 0 percent, while leaving the midtones alone. 0 is unity. The range is –100
```
(minimum) through +100 (very high).
```
 Color Boost: Lets you naturalistically raise the saturation of regions of low saturation, sometimes
referred to as a vibrance operation. Can be used also to lower the saturation of regions of low
```
saturation. 0 is unity. The range is –100 (minimum) through +100 (very high).
```
```
 Saturation: Adjusts the color intensity of the image. 0 is unity. The range is –100 (minimum)
```
```
through +100 (very high).
```
 Midtone Detail: When this parameter is raised, the contrast of regions of the image with high edge
detail is raised to increase the perception of image sharpness, sometimes referred to as definition.
When this parameter is lowered to a negative value, regions of the image with low amounts of
```
detail are softened while areas of high-detail are left alone. 0 is unity. The range is –100 (minimum)
```
```
through +100 (very high).
```
 Enable ICVFX: While VFX shooting in a virtual production workflow, the LED wall lighting in the
background is mixed with normal lighting for people in the foreground. Checking this box lets you
correct for that mixed lighting.
LED Wall Kelvin: Dial in the color temperature of the LED wall.
Light Blend: Specifies the mixing ratio of the normal lighting and LED wall lighting. A value of 100 is
```
normal lighting only (equivalent to ICVFX mode disabled). A value of 0 is the LED wall lighting only.
```
189Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
Use Camera Metadata
The most elemental camera metadata settings for exposure and color that are available.
 Exposure: Increases or lowers image lightness in units relative to ASA values. If your
```
intended exposure adjustment lifts image data above the maximum white level, don’t worry;
```
all image data is preserved and can be retrieved in subsequent adjustments. +800 is unity.
The range is +1 to +65,535.
 Color Temp: Designed to alter the “warmth” of the image. Adjustable in degrees Kelvin. Lower
values correct for “warmer” lighting, while higher values correct for “cool” lighting. +6500 is unity.
The range is +2000 to +50,000.
 Tint: Only available when White Balance is set to something other than As Shot. Designed to
alter the green to magenta balance of the image, for images with fluorescent tinting. Lower values
add green to compensate for magenta lighting, while higher values add magenta to compensate
for green lighting. 0 is unity. The range is –150 to +150.
Sony Media and SLog
Sony’s proprietary SLog gamma setting, which produces flat-contrast, wide-gamut image
data that preserves image detail with a wide latitude for adjustment, is also available on some
other Sony cameras. Similarly to working with clips using the ARRI ALEXA’s Log-C gamma,
```
you need to normalize SLog clips by using Resolve Color Management (RCM), by making a
```
manual adjustment to color and contrast, or by applying a LUT, using the same techniques
discussed previously.
When applying a LUT, there are two methods that Sony recommends. A 1D LUT can be used
```
to transform SLog clips into the standard Cineon (or Log-C) curve if your ultimate goal is to
```
output Log media for film printing. If you’re planning to output to a normalized format, you can
use a dedicated LUT to make this transformation.
For more information, search the web for Sony’s document “SLog: A new LUT for digital
production mastering and interchange applications.”
190Setup and Workflows | Chapter 7 Camera Raw Settings
MEDIA
Chapter 8
Improving
Performance,
Proxies, and
the Render Cache
DaVinci Resolve is a high-performance piece of software designed to enable
real time effects on a variety of workstations.
This section describes the various ways you can monitor your performance to make sure you’re
maintaining real time playback, along with different methods of optimizing real time performance,
including using on-the-fly proxies and the background Render Cache.
Contents
Understanding the GPU Status Display  193
Prioritizing Audio or Video Playback in the Edit Page  193
Performance Mode Improves Overall Performance 194
Adjusting Performance Mode  194
Timeline Proxy Mode Improves Effects Performance 194
Reducing Decode Quality Improves Raw Media Performance  195
Optimized Media Improves Overall Performance  196
Creating Optimized Media 196
Optimized Media for Raw Source Clips 197
Customizing the Type of Optimized Media You Create  197
Switching Between Optimized and Original Media  198
Sharing Optimized Media Between Projects  199
Rediscovering Lost Optimized Media  199
Deleting Optimized Media 199
Using Optimized Media for Delivery 199
191Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Using the Smart or User Cache Improves Effects Performance  199
How Cached Media Is Organized  200
Choosing a Cache Format and Location  202
When Caching Happens  202
The Difference Between the Smart Cache and User Cache Modes  203
Manually Controlling the Cache  204
Controlling Fusion Output Caching  204
Controlling Node Caching  205
Controlling Color Output Caching  205
Controlling Edit Page Filter Caching  205
Using Cached Media When Rendering in the Deliver Page  205
Clearing Cached Media  205
The Cache Manager 206
Automatic Cache Deletion 207
Using Proxy Media 207
Creating and Using Proxy Media 207
Proxy Handling Display  208
Creating Proxy Files with the Blackmagic Proxy Generator  209
Generating Proxy Media in Other Applications  212
Managing Proxy Media  213
Switching Between Proxy Media and Original Media 214
Using Proxy Files for Delivery 214
```
Moving Proxies Using a DaVinci Resolve Archive (.dra)  215
```
Working Remotely Using Proxy Media  215
Proxy Media vs. Other Playback Optimizations in DaVinci Resolve  216
Using Optimized Media, Proxy Media, and Caching Together  217
Which Playback Optimization Method Should I Use?  217
Other Project Settings That Improve Performance  218
192Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Understanding the GPU Status Display
```
Every viewer in DaVInci Resolve exposes a GPU status indicator and a frame-per-second (FPS) meter,
```
which appears in the Viewer’s title bar, which shows you your workstation’s performance whenever
```
playback is initiated. Since DaVinci Resolve uses one or more GPUs (graphics processing units) to
```
handle all image processing and effects, the GPU status display shows you how much processing
power is being used by whichever clip is playing.
Frame rate and GPU indication,
green is good
A green status indicator shows there is plenty of GPU processing headroom available. As the
GPU resources is increasingly taxed, this green graph eventually turns red to show that the
available GPU power is insufficient for consistent real time playback.
Red indicates that playback is at
slower than real time
Eventually, as you add more and more effects and corrections, you’ll reach the limits of available
performance, forcing DaVinci Resolve to either drop frames, or play video at a slower speed in
order to maintain high image quality, shown by the red FPS indicator.
When real time performance falls short, DaVinci Resolve provides a variety of controls and options
that let you enhance real time playback and effects. Each is useful for different situations, and all
can work together so you can choose the best trade-off between image quality and performance
while you work. All of these methods can be set up to have no effect on your delivered output.
Prioritizing Audio or Video
Playback in the Edit Page
When available processing power is insufficient to play the clip or clips at the position of the playhead
due to the grade, transforms, or effects that are applied at that moment in the Timeline, you have the
ability to choose exactly how performance in DaVinci Resolve degrades, by turning the “Show All
Video Frames” on or off in the Option menu of the Edit page Viewers.
 Show All Video Frames off: The default setting, ideal for video editing. Prioritizes audio playback
at the expense of dropping video frames when processing power is tight, resulting in a more
conventional playback experience.
 Show All Video Frames on: An alternate setting that’s ideal when you’re doing effects work, for
which you need to see every single frame play back, sequentially. Audio quality is compromised
while every frame of video plays in slower-than-real-time, if necessary, to maintain playback.
Keep in mind that this setting only affects playback when GPU performance is lacking.
In areas of the Timeline where performance is adequate, playback remains uncompromised.
193Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Performance Mode Improves
Overall Performance
Performance Mode, which is found in the Playback Settings of the User Preferences, analyzes your
computer’s configuration, the CPU, GPU, connected video interface, and so on, and automatically
tunes DaVinci Resolve’s under-the-hood image processing settings to provide the best interactivity on
your machine. It’s set to Automatic by default, although you can choose to adjust its effect manually,
or disable it altogether. When enabled, Performance Mode dramatically improves the experience of
editing, mixing, and grading on less powerful computers.
While Performance Mode is turned on, DaVinci Resolve still outputs to video, renders in the Delivery
page, and processes via the Media Management command at the highest quality. As a result, using
Performance Mode makes no compromise in the quality of your output, so creative editors and audio
mixers can leave this setting on always.
Finishing editors and colorists might notice subtle differences between the image on your computer
monitor on less powerful computers when Performance Mode is on versus when it’s off, which is
why this setting can be disabled, either entirely or in part using checkboxes in the Playback Settings
panel of the User Preferences for instances where GUI interactivity is less important than your
onscreen display.
Adjusting Performance Mode
A pair of radio buttons in the Playback Settings panel of the User Preferences let you choose between
```
Automatic (default) and Manual behaviors when you turn on Performance Mode in DaVinci Resolve.
```
Set to Automatic, Performance mode automatically optimizes a variety of operations in a bid to balance
performance with the necessary level of image quality, for fast onscreen performance while always
maintaining the highest level of quality for video output.
Set to Manual, there are three different settings you can choose to disable for instances where a
particular performance tradeoff results in an undesirably noticeable reduction in image quality in
Performance Mode:
Optimized Sizing: Relates to how image resizing is handled.
Optimized Decode Quality: Relates to how clip resolution vs. timeline resolution is handled.
Optimized Image Processing: Relates to how image processing operations are handled.
Timeline Proxy Mode
Improves Effects Performance
If you don’t want to either drop frames or play at slower than real time speed whenever the GPU Status
indicator is in the red, an immediate way of improving performance is to turn on the Use Timeline
Proxies option in the Playback menu. Using timeline proxies reduces processing demands by taking
advantage of the resolution independence of DaVinci Resolve to lower the resolution of your clips
on-the-fly, thereby increasing real time playback performance without the need to spend time caching
```
part or all of the timeline, or create optimized media (both discussed later).
```
194Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
To turn Use Timeline Proxies on and off:
Choose Playback > Timeline Proxy Resolution > Half Resolution, Quarter Resolution, or None.
Turning on one of the proxy resolutions reduces the working resolution by either half or a quarter
of whatever the current Timeline resolution is for your project. Working at a temporarily reduced
resolution increases your workstation’s real time performance, while the resolution independence of
Resolve guarantees that every window you draw and sizing operation you make scales correctly to
the actual resolution of your project.
Proxy Resolution Width Height
Full 8K UHD 7680 4320
Full UHD/Half 8K UHD 3840 2160
Full-HD/Half UHD/Quarter 8K UHD 1920 1080
Half-HD/Quarter UHD/Eighth 8K UHD 960 540
Quarter-HD/Eighth UHD/Sixteenth 8K UHD 480 270
Table of half and quarter proxy resolutions for different television frame sizes
```
IMPORTANT: Timeline Proxy Mode is entirely different and independent of the creation of
```
Proxy Media as described later in this chapter. The two functions, Timeline Proxy Mode and
Proxy Media, have no relation to each other.
Reducing Decode Quality
Improves Raw Media Performance
The Use Proxy command will improve performance when grades and effects are responsible for your
project’s slower than real time playback, but Use Proxy won’t help when real time performance is
being used up by the need to debayer raw media. While you could improve playback performance by
```
taking the time to either generate optimized media (see below) or render to the Fusion Output Cache
```
```
by enabling the Smart Cache (see later in this chapter), the fastest solution is to open the Camera Raw
```
panel of the Project Settings and reduce the Decode Quality of the raw media formats you’re using:
Decode Quality: Camera raw formats such as R3D and F65 can be debayered at different
levels of quality. For higher real time performance, you can choose a lower quality setting
while you work, and then switch to a higher quality when rendering the final output.
Options for reducing resolution vary by each raw format’s differing capabilities, but at the very
```
least include full, half, and quarter resolution (R3D and Sony Raw have options for full, half,
```
```
quarter, eighth, and sixteenth). Exceptions include the Canon RAW, Panasonic Varicam RAW,
```
and Phantom Cine formats, which only decode to full resolution.
195Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
If you reduce the decode quality of raw media formats in your project to improve performance,
you can use the “Force debayer res to highest quality” checkbox in the Render Settings list of
the Deliver page to ensure that DaVinci Resolve renders all raw formats at the highest quality
available, so you don’t have to worry about forgetting to change the decode quality back
when it’s time to render your deliverables.
Optimized Media Improves
Overall Performance
If you’re editing processor-intensive source formats such as camera raw, H.264, or 8K media, and
your computer isn’t fast enough to work with it easily in real time, you can create pre-rendered, low-
overhead duplicate media to use instead, that’s automatically managed alongside the original media.
This is called “Optimized Media.” Optimized Media lets you work more quickly by allowing you to edit
with a more processor-efficient media format and resolution, while providing the ability to easily switch
your project back to the original source media whenever you want. So, you can use Optimized media
to edit, and switch back to the original source media when it’s time to finish and output. Switching is as
easy as choosing Playback > Use Optimized Media if Available to toggle Optimized media on and off.
The advantage of using optimized media to help you work faster is that it’s pre-generated, meaning
```
you can render it once and then use the files for the duration of your work in that project (unless you
```
```
change the debayering settings of the raw media). Also, optimized media improves the playback
```
performance of clips throughout DaVinci Resolve, including in the Media page and in the Media Pool
and Source Viewer of the Edit page, whereas the similar but different Fusion Output Cache component
of the Smart Cache only improves the performance of clips that are already in the Timeline by caching
them at the Timeline resolution. This makes optimized media ideal for editing workflows of all kinds.
Choosing the Appropriate Optimized Media Format for Your Project
You have the option of choosing the Format of the optimized media you create, using controls
in the Master Settings panel of the Project Settings. Be aware that the format you choose via
```
the “Optimized Media Format” menu will determine whether out-of-bounds image data (also
```
```
known as “overshoots”) and Alpha Channels are preserved when the clip is cached.
```
Preventing Clipping: You should use 16-bit float, ProRes 4444, ProRes 4444 XQ, or DNxHR
444 if you plan on grading using optimized media. This is particularly true for HDR grading.
Preserving Alpha Channels: Also be aware that the format you choose will determine
whether Alpha Channels will be preserved if they’re present in the clips being optimized.
Currently, the Uncompressed 10-bit, Uncompressed 16-bit Float, ProRes 4444, ProRes 4444
XQ, and DNxHR 444 formats preserve alpha channels.
Creating Optimized Media
Creating optimized media to work with is easy. Resolve automatically manages the relationship
between source clips and the optimized media you create, so all you need to do is choose which clips
to make optimized media for. You can manually choose which clips to optimize, or you can use a Smart
Bin to collect all of the media corresponding to one or more formats you need to optimize to gather
it procedurally. In either case, this gives you the option of only optimizing clips in formats that require
optimization, saving you time.
196Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
For example, if you’re editing a project that consists half of camera raw media, and half of DNxHD
media, you probably only need to optimize the camera raw media, so you can create a Smart Bin that
gathers all of it, based on Resolution, Codec, File Name, or whatever other metadata is appropriate.
Once gathered, it’s an easy thing to select all of these clips in preparation for the next step.
To create optimized media for one or more selected clips:
Right-click one of the selected clips, and choose Generate Optimized Media from
the contextual menu.
All optimized media is written to the same directory as the Cache files are written, which defaults to
the first scratch disk listed in the Preference dialog’s Media Storage panel. The location of Cache and
Optimized files is also selectable via the “Cache files location” setting in the Master Settings panel of
the Project Settings.
Optimized Media for Raw Source Clips
In general, once you create optimized media, DaVinci Resolve keeps track of it and continues using it
regardless of whatever changes you make to your project, including changing the Timeline resolution.
However, any change to the camera raw settings of optimized clips will automatically discard the
optimized media, requiring you to re-generate optimized media for them.
Customizing the Type of Optimized Media You Create
The Master Settings panel of the Project Settings has a set of controls that govern what kind of media
files are created when you create optimized media.
Options available for creating optimized media in the Master Settings panel of the Project Settings
There are two settings affecting Optimized Media in the Optimized Media and Render Cache section:
 Resolution: Lets you choose whether to create optimized media at the same size as your original
```
media files (by choosing Original), or to reduce the bandwidth of your optimized media further by
```
reducing its resolution by a Half, Quarter, Eighth, or Sixteenth. The “Choose automatically” option
tries to balance visual quality with efficiency by only reducing the resolution of media files that are
larger than the currently selected Timeline resolution, using whatever reduction ratio best matches
the Timeline resolution.
 Optimized Media Format: Lets you choose the format and codec with which to generate
optimized media. Options include Uncompressed 10-bit, and Uncompressed 16-bit float for
maximum quality. Other options include ProRes Proxy through 4444 XQ, and DNxHR LB
through 444. All options will store image data in the optimized and proprietary .dvcc image format.
While smaller formats take less room on your scratch disk, there are two good reasons to use
higher-quality formats for creating Optimized Media.
197Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Preventing Clipping: Be aware that the format you choose will determine whether out-of-bounds
```
image data is preserved when the signal is optimized. If you find that image data (typically super-
```
```
white levels) are clipped after optimization, you should switch to 16-bit float, ProRes 4444, or
```
```
ProRes 4444 XQ; in particular, any of these three codecs are appropriate optimized formats for
```
HDR grading.
Preserving Alpha Channels: Also be aware that the format you choose will determine whether
Alpha Channels will be preserved, if they’re present in the clips being Optimized. Currently,
the Uncompressed 10-bit, Uncompressed 16-bit Float, ProRes 4444, ProRes 4444 XQ, and
DNxHR 444 formats preserve alpha channels.
Choosing Resolution Automatically
The “Choose automatically” option of the Resolution setting bears a bit more explanation. When
selected, only source media with a higher resolution than the selected Timeline resolution will
generate downsized optimized media. How much each clip will be downsized depends on how
much larger each clip is than the Timeline resolution. For example, if you’re working within a 1080
resolution project, then 8K clips will generate quarter-resolution optimized media, and 4K clips will
generate half-resolution optimized media, such that all optimized media is somewhere around 1080
resolution. All clips that are 1080 and smaller generate optimized media at the same resolution as the
source clips.
In the example of a 4K project, 8K clips will generate half-resolution optimized media, and all other
clips that are 4K and smaller will generate optimized media at the same resolution as the source clips.
Proxy Resolution Width Height
Full 8K UHD 7680 4320
Full UHD/Half 8K UHD 3840 2160
Full-HD/Half UHD/Quarter 8K UHD 1920 1080
Half-HD/Quarter UHD/Eighth 8K UHD 960 540
Quarter-HD/Eighth UHD/Sixteenth 8K UHD 480 270
Eighth-HD/Sixteenth UHD 240 135
Table of optimized resolutions for different television frame sizes
Switching Between Optimized and Original Media
Choosing whether or not you’re using optimized media is easy. Simply choose Playback > Use
```
Optimized Media if Available to switch your entire project between using optimized media (if it’s been
```
```
generated), or the original media. Furthermore, a checkbox in the Render Settings of the Deliver page
```
lets you choose whether you want to use optimized media to speed up rendering, or render using the
original media only.
```
NOTE: Optimized media is not included in Media Management operations, nor is it included
```
as part of Archive operations in the Project Manager.
198Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Sharing Optimized Media Between Projects
```
Optimized Media is shared across projects in the same project library (previously optimized media was
```
```
confined to a single project). This means that if you create optimized media for a clip in one project,
```
that same optimized media will be used for that clip in any other project that’s in the same project
library. This happens automatically and requires no user input. This will dramatically cut down the
space requirements for working with the same media across different projects.
Rediscovering Lost Optimized Media
It’s difficult, but it is possible to lose track of optimized media you’ve generated in certain rare
circumstances. For example, if you generate optimized media on another workstation, but failed to
save the project, DaVinci Resolve may lose the relationship between the clips in the Media Pool and
the optimized media files you created. In these cases, it’s possible to rediscover the optimized media
so you don’t have to regenerate it.
To rediscover lost optimized media:
Select the clips in the Media Pool for which you know you have optimized media, then right-click one
of the selected clips and choose Rediscover Optimized Media from the contextual menu.
Deleting Optimized Media
```
The optimized media you generate within a project is persistent; it’s saved for future use even when
```
the project is closed and later reopened. If you need to delete optimized media to free up space on
```
your scratch volume (or wherever you’ve decided to locate your project’s cache files), you must delete
```
the optimized media manually in your OS. By default, the Optimized Media is stored in the first volume
in the Media Storage tab of the System Preferences.
Using Optimized Media for Delivery
An option in the More options section of the Render Settings in the Deliver page, “Use Optimized
Media,” lets you output using Optimized Media, rather than the original media, in order to save
rendering time. If you’re planning on using this option, it’s advisable to set the Optimized media format
to a suitably high-quality HDR-capable format to guarantee the best results.
Using the Smart or User Cache
Improves Effects Performance
Another option for achieving real time performance when the GPU Status indicator is in the red due
either to Timeline effects, Color page grading, or processor-intensive media in the Timeline, is to use
the Smart Cache or User Cache modes of the Render Cache. What DaVinci Resolve calls “caching” is
sometimes referred to by other applications as “rendering.” Both terms refer to the behind-the-scenes
creation of new media, with all effects “baked in,” which DaVinci Resolve plays back in real time in
place of the original source media containing processor-intensive effects at the same time. This results
in smooth playback without the risk of dropped frames.
The settings governing caching in the Master Settings panel of the Project Settings
199Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
The DaVinci Resolve Smart Cache and User Cache automatically render and cache clips, including
simple video clips, compound clips, Fusion clips, and nested timelines that have processor-intensive
grades and effects applied to them, or that you manually flag for caching by right-clicking any clip in
the Color page or Edit page timeline and enabling the Render Cache Clip Output option. When the
Smart or User Caches are enabled, frames of each automatically or manually flagged clip are cached
either during playback in the Timeline, or automatically whenever you pause work, to the “Cache files
location” specified in the Master Settings panel of the Project Settings.
Once you’ve cached clips in the Timeline, they play back in real time until they’re modified, which
automatically flushes the now out-of-date cache files for those modified clips and triggers the need
to re-cache.
To use clip caching on any page, do one of the following:
 Choose Playback > Render Cache > Smart to set DaVinci Resolve to automatically cache
computationally intensive effects and timeline clips in formats judged too processor-intensive to
play in real time.
 Choose Playback > Render Cache > User to set DaVinci Resolve to cache clips and effects
that you manually choose to cache, as well as automatically caching processor-intensive
```
effects (transitions, composites, and Fusion Effects) you specify in the Master Settings of the
```
Project Settings.
 Choose Playback > Render Cache > Off to disable all render caching.
 In the Color and Edit pages, press Option-R to cycle among Off, Smart, and User.
Choosing the Appropriate Cache Media Format for Your Project
You have the option of choosing the Format of the cached media you create, using controls in
the Master Settings panel of the Project Settings. Be aware that the format you choose via the
```
“Render Cache Format” menu will determine whether out-of-bounds image data (also known
```
```
as “overshoots”) and Alpha Channels are preserved when the clip is cached.
```
Preventing Clipping: You should use 16-bit float, ProRes 4444, ProRes 4444 XQ, or DNxHR
444 if you plan on grading using cached media. This is particularly true for HDR grading.
Preserving Alpha Channels: Also be aware that the format you choose will determine whether
Alpha channels will be preserved, if they’re present in the clips being cached. Currently, the
Uncompressed 10-bit, Uncompressed 16-bit Float, ProRes 4444, ProRes 4444 XQ, and DNxHR
444 formats preserve Alpha channels.
How Cached Media Is Organized
The cache mechanism in DaVinci Resolve actually comprises three independently managed media
caches that interact with one another. This is done to keep you working quickly by ensuring that
changes you make to your timeline don’t require a grade to be re-cached, and that changes you make
to a grade don’t require the timeline to be re-cached. The three levels of caching are:
First, Fusion Output Caching
Formerly called the “Source Cache” in previous versions of DaVinci Resolve. When enabled by turning
on the Smart Cache, by individually turning on Render Cache Fusion Output for a particular clip, or by
enabling the automatic caching of clips with Fusion Effects applied in the Project Settings, this caches
the portion of each source media file that appears in the Timeline in its pre-graded state for clips that
have the following characteristics:
200Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
 Clips in media formats DaVinci Resolve considers to be processor-intensive to decode,
such as H.264, HEVC, and various raw camera formats
 Clips with Fusion Effects that have been added in the Fusion page
Effectively, this is a “pre-Color page” cache. By caching all processor-intensive clips in the Timeline,
you’ll experience vastly improved trimming and grading performance. However, you also have the
option to turn the Fusion Output Cache on or off for individual clips, or for multiple selected clips all at
once. This lets you switch between using the native source of each clip with live effects, or the cached
clip in the cache format you’ve chosen.
The advantage of the Fusion Output Cache over Optimized Media is that you only cache clips that
are used in a timeline, which is ideal for finishing workflows. However, the Smart and User caches
aren’t useful for speeding up work done with source media in the Media Pool and Source Viewer
```
when you’re at the very beginning of an edit; that’s what Optimized Media is for (as described in the
```
```
previous section).
```
If Optimized media exists for a given clip, and “Use Optimized Media if available” is turned on, then
Optimized media will be used instead of the Fusion Output Cache if there are no Speed effects or
Fusion Effects applied to a particular clip.
Second, Node Caching
The Node Cache, which is a separate level of caching from the Fusion Output Cache, can be triggered
in several different ways, corresponding to the three different purposes it serves.
```
 When enabled by turning on the Smart Cache, nodes with processor-intensive operations (along
```
```
with all nodes appearing upstream in that grade’s node tree) are automatically cached, meaning
```
that, for example, if Nodes 1 and 2 are cached, you can continue adjusting Nodes 3, 4, and 5 to
your heart’s content without needing to re-render your grade to the cache. Operations that trigger
caching include Noise Reduction, Motion Blur, and any Resolve FX or OFX plugin that’s added to
a node. If you’ve added a Resolve FX to a node that’s capable of playing in real time but that node
is being flagged for caching anyway, you can force caching off for that node by right-clicking it and
choosing Node Cache > Off from the contextual menu.
 You can manually force any node to cache if it and its upstream nodes are compromising
performance but somehow not being automatically flagged, by right-clicking a node and choosing
Node Cache > On from the contextual menu.
 You can also turn on the “Render Cache Color Output” option for a clip in the Timeline of either
the Edit or Color pages. This forces that clip’s entire grade to be cached via the Node Cache,
all the way through the Node tree’s output. This can result in higher real time performance in the
Edit page, at the expense of needing to completely re-cache that clip whenever you adjust any
part of its grade.
 If you apply Resolve FX or OFX filters to clips in the Edit page, these will also be cached via the
Node Cache. You can choose which OFX to cache via the Render Cache OFX Filter submenu
in the contextual menu for clips in the Timeline. This is useful when you have a combination of
```
realtime and non-realtime filters applied to a clip; caching the non-realtime filters only enables
```
you to continue adjusting realtime filters without the need to re-cache. However, be aware that
making changes to a filter being cached in the Edit page timeline will force that clip’s grade to be
re-cached in the Color page, and vice versa.
If multiple nodes are flagged for caching in a particular node tree, then each node will be individually
cached. That way, you can turn a cached node off and on to get a before-and-after look without
needing to re-cache the entire node tree. If a clip is part of a group in the Color page, you can enable
a Group Cache in the Group Pre-Clip and Group Post-Clip Node Editor modes, which cache these
parts of a group grade as part of the Node Cache.
201Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Third, the Sequence Cache
The Sequence Cache is a separate cache for effects that are specifically applied within the Timeline in
the Edit page. These include transitions, opacity adjustments, adjustment layers and composite mode
superimpositions, as well as clips with Speed or Retime effects. Sequence Cache effects can be auto-
cached in both the Smart and User caches.
Choosing a Cache Format and Location
The cache format is user selectable by opening the Master Settings panel of the Project Settings,
and using the “Render Cache Format” drop-down menu to choose one of the ProRes, DNxHR, or
uncompressed 10- or 16-bit float uncompressed .dvcc formats. Selecting a higher quality cache format
guarantees high quality image playback, but makes more demands on the throughput and size of
your available disk storage. On the other hand, choosing a more highly compressed cache format
makes real time playback possible on less capable computers with slower and smaller storage, at the
expense of slightly compromised image quality. Ideally, you should choose the highest quality cache
format that your workstation’s storage can accommodate.
The format you choose via the “Render Cache Format” menu will determine whether out-of-bounds
```
image data (including “super white” or HDR strength highlights) is preserved when the signal is
```
cached. Formats in this menu that end in “– HDR” preserve out-of-bounds image data, while formats
```
that don’t, wont. If you find that image data (typically bright highlights) is clipped after caching or
```
```
optimizing, you should switch to 16-bit float, ProRes 4444, ProRes 4444 XQ, or DNxHR 444; in
```
particular, any of these codecs are appropriate for HDR grading.
The Cache files location defaults to the first volume you add to the Scratch Disks list of the Media
Storage panel of the System Preferences. If no scratch disk is specified, your System disk will be
used, which may pose problems with capacity and/or performance depending on the size and type
of System disk you’re using, and on the media format you choose to cache to. For this reason, it’s
nearly always advisable to set your first scratch disk to the largest, fastest storage volume available to
your workstation.
When Caching Happens
When caching is enabled, cache indicators along the bottom of the Timeline Ruler of the
Edit page timeline shows the status of the cache. Red means “to be cached,” while blue means
“has been cached.”
```
Source, Clip, and Sequence Cache bars seen in the Timeline of the Edit page; red bars show
```
areas of the Timeline that need caching, blue shows areas that have been cached
In the Color page, cache indicators are node specific, showing the node in your grading node tree
```
(including all upstream nodes) at which caching will take place.
```
Node Cache indicator seen as a red colored node number
on node two of the Node Editor of the Color page
202Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Caching happens in two ways. First, when either Smart or User caching is enabled, caching always
happens whenever you play clips with red caching indicators.
```
Second, if background caching is enabled in the Project settings (it’s turned on by default), and you
```
```
don’t make any changes to your project for a user-definable number of seconds (this is adjustable in
```
```
the Master Settings panel of the Project Settings), caching will automatically begin during periods of
```
```
user inactivity. So feel free to use this as an excuse to take those coffee, mate, or tea breaks; DaVinci
```
Resolve will keep on working for you.
The Difference Between the
Smart Cache and User Cache Modes
The Smart Cache option of the Render Cache submenu provides the easiest user experience when
you want to “set it and forget it.” Choosing Smart triggers a variety of automatic caching behaviors
designed to optimize playback in DaVinci Resolve by rendering clip formats, grading operations, and
timeline effects that are known to be performance-intensive, while also letting you manually flag clips
that you’d like to cache that the Smart Cache hasn’t.
The User Cache, on the other hand, does not automatically cache clips in processor-intensive formats,
so this is a good option to choose when your workstation is capable of playing all media formats you’re
using in real time. Ordinarily, the User cache relies on you to control what is cached and what is not by
manually flagging specific clips and effects. However, the Master Settings panel of the Project Settings
has three options you can enable for automatically caching transitions, composites, and Fusion Effects
```
while in User Cache mode (these options are found in the Optimized Media and Render Cache group).
```
Of these settings, only “Automatically cache Fusion Effects in User Mode” is turned on by default.
Here are the differences between the Smart and User cache modes for each type of caching
DaVinci Resolve does.
Fusion Output Caching
```
 In Smart mode: For all clips with “Render Cache Fusion Output” set to either Auto (by default) or
```
On, three types of effects are rendered. First, H.264, H.265, DCP, JPEG2K, or camera raw clips
that have been edited into a timeline are cached. Camera Raw clips are cached using the currently
selected project or clip debayer settings. Second, Speed effects are cached at the source level,
which makes it possible to move cached speed effects clips on the Timeline without needing to
re-cache them. Finally, Fusion Clips or clips with Fusion Effects applied to them are also cached,
and manually flagged clips are also cached in Smart mode.
 In User mode: Clips with Render Cache Fusion Output set to On are cached, while clips set to
Auto are ignored, except for clips with Fusion Effects, which are automatically cached in Auto
mode when the “Automatically cache Fusion Effects in User Mode” Project Setting is on.
Caching Specific Nodes in the Color Page
 In Smart mode: DaVinci Resolve automatically caches all nodes that use Motion Blur,
Noise Reduction, or Resolve FX and OFX plugins. Manually flagged nodes are also
cached in Smart mode.
 In User mode: DaVinci Resolve only caches nodes that have been manually flagged by right-
clicking them and choosing Node Cache > On to force that node to cache in User mode, along
with all upstream nodes to the left of them.
203Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Cache Color Output Is Actually Node Caching for the Whole Grade
 In Smart mode: Manually flagged clips with Render Cache Color Output turned on cache the
entire output of the Color page node graph, effectively caching that clip’s entire grade. This is
most useful when you want to improve trimming and playback performance in the Edit page.
Flagging a clip for caching also causes EVERY SINGLE VERSION associated with that clip to be
cached as well.
 In User mode: Manually flagged clips with Render Cache Color Output turned on also cache the
entire output of the Color page node graph.
Caching of Resolve FX and OFX in the Edit Page Is Also Node Caching
Caching of Resolve FX and OFX filters applied to clips in the Edit page can only be set manually,
whether you’re in Smart or User mode. Only filters that you have flagged to cache by right-clicking the
clip they’re applied to and choosing them in the Render Cache OFX Filter submenu are cached.
Sequence Caching
 In Smart mode: DaVinci Resolve automatically caches all superimposed clips that use composite
modes other than “Normal,” any clips with opacity or speed effects, and any transitions.
Clips cannot be manually flagged for Sequence caching.
 In User mode: If you’ve enabled User mode and you find that your workstation does not have
adequate performance to play composite and opacity effects in the Edit page, you can force
these categories of effects to be automatically cached in User mode via a set checkboxes in
the Optimized Media and Render Cache section of the Master Settings of the Project Settings.
When these options are enabled, you also gain the ability to exclude specific tracks from being
cached, by right-clicking the track header of any video track you want to exclude from caching,
and choosing Exclude track from caching. Excluding an entire track from caching is a convenient
way of keeping a track full of effects that are capable of playing in real time on your workstation,
such as a track of titles, from wasting time and storage by being cached when it’s not necessary.
Manually Controlling the Cache
This section describes how to manually control each type of caching that is manually controllable in
DaVinci Resolve.
Controlling Fusion Output Caching
You can manually control which clips in the Timeline are cached, and which are not. You can select
one or more clips in the Timeline of the Edit page, or in the Thumbnail Timeline of the Color page,
right-click one of the selected clips or thumbnails, and choose an option from the Render Cache
Fusion Output submenu. There are three options:
 Auto: The clip will only be cached in Smart mode if it’s a format designated for caching or if
there’s a speed effect applied. The clip will only be cached in User Mode if “Automatically cache
transitions in User Mode” is enabled.
 On: The clip will be cached in either Smart or User mode, no matter what format or effects
are applied.
 Off: The clip will not be cached at all, in either Smart or User modes.
204Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Controlling Node Caching
You can manually control which nodes in a grade are cached, and which are not. Right-click any node
in a node tree, and choose an option from the Node Cache submenu. There are three options:
 Auto: The flagged node and all upstream nodes will only be cached in Smart mode if it
contains an operation that’s designated for caching.
 On: The node will always be cached in either Smart or User mode, no matter
what operations it performs.
 Off: The node will not be cached, in either Smart or User modes. This lets you exclude nodes from
caching in Smart mode if they’re capable of real time operation on your system.
Controlling Color Output Caching
```
Each clip in the Timeline (including Adjustment clips) has a Color Output setting that you can turn on or
```
off by right-clicking that clip in the Timeline of the Edit page, and choosing Render Cache Color Output
from the contextual menu. A check mark indicates when this setting is turned on.
Controlling Edit Page Filter Caching
You can choose which of the Resolve FX or OFX filters applied to a particular clip should be cached
by right-clicking that clip in the Timeline of the Edit page, and choosing which of the filters in the
Render Cache OFX Filter submenu you want to cache.
Each filter applied to that clip appears in this submenu in the order in which it’s applied to the clip, and
```
you can turn the caching of specific filters on and off (selected filters appear with a check mark to the
```
```
left of their menu item).
```
Using Cached Media When Rendering in the Deliver Page
The “Use Render Cached Images” option in the “More options” section of the Video panel of
the Render Settings in the Deliver page lets you write media directly from the cache, rather than
re-rendering the effects from scratch, in order to save rendering time when you output your project.
If you’re planning on using this option, it’s advisable to set the cache format to a suitably high-quality
format to guarantee the best results.
Clearing Cached Media
```
Each project’s cache is persistent; the cache is saved for future use even when the project is closed
```
and later reopened. If you need to delete a project’s cache to free up space on a storage volume,
there are three options in the Delete Render Cache submenu:
 All: You can delete all media in the cache to reset every single cached clip.
 Unused: You can choose to delete only Unused cache clips that no longer correspond to clips or
effects in the Timeline.
 Selected clips: You can make a manual selection of clips in the Timeline, and delete the cache
corresponding to just those clips.
To clear a project’s cache:
Open the project, and choose Playback > Delete Render Cache > All, Unused, or
Selected Clips.
205Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
The Cache Manager
There is an advanced render cache management window to help you easily see the size and manage
your cache data for various projects across all your project libraries. This cache manager can be
accessed from Playback > Manage Render Cache.
The Cache Manager window ties in with the Project Manager, letting you select cached media from
any library accessible from your system, not just the current project library.
The functions of the Cache Manager are:
• Location: This drop-down menu lets you choose the type of project library to connect to.
Options are: Local, Network, Cloud, and All.
• Project Library: This drop-down menus lets you choose the project library whose projects
you want to manage. This lists all the project libraries in the selected Location, and you
can select one for management. You can also select All to reveal all project libraries in
that location.
• Project: The main window shows all the projects in the Project Libraries selected above. It
is categorized into sortable columns by Location, Project Library, Project Name, and Render
Cache. Check the box in the Render Cache column to select any projects you want to
delete the cache of.
• Clear Selected Cache: Click this button to delete the Cache for all the selected projects.
As of this writing there is no warning dialog or undo for this function, so double check that
you’ve selected the correct caches for deletion.
• Close: Closes the Cache Manager.
The Cache Manager
206Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Automatic Cache Deletion
A User Preference allows you to delete your local cache automatically after a certain number of days
to keep your drive from filling up with older projects.
It is found in DaVinci Resolve > Preferences > User > Cache Management > Delete cache older
than xx days.
Check the box to automatically delete any cache files older than the number of days set in
the field.
You can always manage these files manually from the Playback > Manage Render Cache
menu, but this new preference lets you set and forget a cleanup operation.
Using Proxy Media
DaVinci Resolve includes a Proxy Media workflow to provide a playback optimization option that
makes it easier to exchange projects online, work on projects remotely, and work with external media
asset management systems. It creates a simple and flexible system for editing collaboration that can
be custom configured to your specific requirements.
Creating and Using Proxy Media
```
Proxy Media is essentially more highly compressed (and potentially lower resolution) versions of your
```
source media that are linked to your source media in DaVinci Resolve via metadata. This is done in
such a way as to make it easy to switch back and forth between the original and proxy media as your
needs require.
Typically, this lets you use lower bandwidth proxy media for increased real-time effects performance
and full speed playback while editing, while easily reverting back to more bandwidth and processor-
intensive source media for color correction, finishing, and final output. In addition to enabling better
performance, these proxy files are fully portable, which lets you move your whole project easily
from workstation to workstation, and even across the internet, accompanied by much more compact
proxy media.
You set the resolution and format of your proxies in the Optimized Media and Render Cache section of
the Master Settings panel in the Project Settings. There are two settings that control the actual media
files created by the Generate Proxy Media command.
Proxy Media Resolution: Choose “Original” to keep proxies the same resolution as the
source media. If you prefer, reduce the resolution of the proxy media files by choosing Half,
Quarter, Eighth, or Sixteenth to save bandwidth. The “Choose Automatically” option balances
visual quality with efficiency by only reducing the resolution of media files that are larger than
the currently selected Timeline resolution, using whatever reduction ratio best matches the
Timeline resolution.
Proxy Media Format: Lets you choose the specific QuickTime format and codec that the
proxy files will be created with. There are several ProRes and DNxHR varieties to chose
from, as well as H.264 and H.265 options. Which format you chose will be determined by the
bandwidth and quality tradeoffs that you need for a particular project. For example, if you
207Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
simply want better playback speed from RAW media while preserving image quality, you may
want to pick a high-quality codec like ProRes 422 HQ, or DNxHR HQX. If your goal is to send
your media across the internet to another editor, you may want to chose a more compressed
format, such as ProRes Proxy, or even H.264 or H.265, to keep file sizes small.
The Proxy Media Resolution and Format settings
To generate proxy media in DaVinci Resolve:
1 Select all of the clips you wish to generate proxies for in the Media Pool.
2 Right-Click any selected clip and choose “Generate Proxy Media” from the contextual menu.
DaVinci Resolve will display a progress bar and give you a time estimate for completion as it renders
out your selected clips to the format and codec determined by the Proxy Media Resolution and
Format settings.
```
NOTE: If your source clip has a separate audio file synced to it in the Media Pool, any proxies
```
generated from that clip will include the synced audio, but that audio will be embedded in the
video clip instead of being created as a separate file.
Where is Proxy Media Saved?
Proxy media is created in the “Proxy generation location” destination, found in the Working Folders
section of the Master Settings of the Project Settings. The proxies are further organized into subfolders
by original source clip location. It is important to have enough free space on this drive to contain the
proxies. Once created, these proxy files can then be moved to any other drive location on the system,
if you wish, and then re-linked to their source files.
This location can be overridden by adjusting the Proxy Generation Location options in the Media
Storage settings in the DaVinci Resolve Preferences.
Proxy Handling Display
In both the Media Pool and on the Timeline in the lower left corner of a clip, there can be found a
proxy status icon. This icon changes to let you know exactly which type of media DaVinci Resolve is
currently using.
The Proxy Only icon
Purple PXY Only: This icon indicates that only
```
proxy media is available; the camera original
```
media is missing.
208Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
The Proxy
Preferred icon
Purple PXY over a White Background: This
icon indicates that both camera originals and
proxy media for this clip exist, and that proxy
media is being used.
The Camera Original
Preferred icon
White HQ over a Purple Background: This
icon indicates that both camera originals and
proxy media for this clip exist, and that original
media is being used.
The Camera Original
Preferred icon
No Icon: No icon means that proxy workflow
has been disabled, and all media is Camera
Original.
You can select which media you prefer to use in the Proxy Handling selector in the top right
of the Viewer. This is a global setting that changes proxy handling for all the viewers across
DaVinci Resolve.
The Proxy Handling Selector in the Viewer
lets you choose which type of media to use.
Creating Proxy Files with the Blackmagic Proxy Generator
The Blackmagic Proxy Generator is a separate program that can automatically generate proxy media
from master video files placed in a watch folder. This is a small, lightweight application that can be left
to run in the background while importing media. This frees up your DaVinci Resolve program to do
more creative tasks while the proxies are generated.
209Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Using Watch Folders
Watch folders are simply specific folders in your OS that are constantly monitored by the Blackmagic
Proxy Generator. When new files are added to the watch folder, the Blackmagic Proxy Generator
is notified, and it automatically transcodes those new files into proxy media, without any additional
```
human interaction needed. You can have as many different watch folders as you want; the only
```
requirement is that the storage media the watch folder is on has enough space to hold both the
original media files and the new proxy media.
```
IMPORTANT: The proxy media is generated inside a subfolder named “Proxy” at the same
```
level in the file hierarchy as the original media file. This means that if your original media is
all in the same folder, you will have one “Proxy” folder containing all of the proxy clips. If your
```
original media is all contained in separate folders (i.e., one folder for each video clip), you will
```
have multiple “Proxy” folders, one inside every clip folder and containing one proxy clip each.
```
NOTE: You can not name a watch folder “proxy.” That name is reserved for the
```
Proxy Generator.
To Add a New Watch Folder
You need to create at least one watch folder and can have as many different watch folders as you
need. For example, you could have separate watch folders for each card, or scene, or date, or
whatever makes the most sense for your workflow.
1 Select the Add button.
2 Create a new folder, or select an existing folder in the file system window.
3 Click on the open button.
The new watch folder will appear in the Watch Folders pane of the Blackmagic Proxy Generator and
will display its location and current status.
To Remove an Existing Watch Folder
When you’re finished using a specific watch folder, you can remove it from the Blackmagic Proxy
```
Generator’s watch list. Removing a folder does not delete it or its files from your drive; it only stops the
```
Blackmagic Proxy Generator from monitoring it.
1 Select the watch folder from the Watch Folders list.
2 Select the Remove button.
If you’ve accidentally removed the wrong watch folder, you can simply add it back again using the
steps above.
Monitoring Watch Folders
You can see the status of all your watch folders in the Watch Folders section of the Blackmagic Proxy
Generator. You can manually change the order that they appear in the list by dragging an entry up or
down in the list. The estimated disk space required for the proxies can be found below, and there are
three columns that contain information about each folder.
```
 Volume: This is the logical volume (disk, network storage, usb drive, etc.) that the watch folder
```
is on. This lets you know which physical device needs to be attached to the computer for the
Blackmagic Proxy Generator to function.
 Folder: This is the name of the Watch Folder. It does not show the folder’s path, only the name of
the watch folder itself.
210Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
 Status: This column shows the current status of the files in the watch folder.
```
Waiting: This folder has clips in it that have not been transcoded yet into proxies. It is waiting
```
for the Blackmagic Proxy Generator to be started or for a folder ahead of it in the queue
to be finished.
```
Processing (x/x): This folder has clips that are currently being transcoded. The number to the left
```
of the slash is the current clip number, the number to the right is the total number of clips to be
transcoded.
```
Completed: This folder has finished transcoding all proxy files for the media in the folder.
```
The Watch Folders section of the Blackmagic Proxy Generator
Setting the Proxy Format
You can select the proxy codec you wish to use by selecting the format from this list.
The Proxy Media Format section of the Blackmagic Proxy Generator
211Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Starting and Stopping the Blackmagic Proxy Generator
Once you’ve set up a watch folder and selected a proxy format, all you need to do is select the Start
button in the Processing pane to automatically transcode and monitor your watch folders. If you want
to stop the process at any time, just select the Stop button. You can also toggle Start/Stop by pressing
the space bar.
The Processing pane of the Blackmagic Proxy Generator
In the Processing pane, you can also see the status of the current job. The pane displays the progress
```
of the job in terms of number of clips rendered (x of x), a progress bar, and a percentage indicator.
```
```
It also displays the name of the current clip, the frames-per-second (fps) that the render is happening
```
at, and an estimated time left to complete.
Managing Proxies from the Blackmagic Proxy Generator
There are two options to help manage your proxy files once they’ve been created. The Processing
mode must be stopped for them to be available.
```
Delete Proxies: This option deletes all proxy files (and the Proxy folder) from the
```
selected watch folders.
Extract Proxies: This option copies all proxy files from the selected watch folders to a new
destination in the file system dialog. This is useful to create a separate proxy-only folder that
you can hand over to another person on a portable hard drive or upload onto cloud storage.
Linking Proxies from the Blackmagic Proxy Generator in DaVinci Resolve
Once your proxies are created they are linked automatically to their original source media in
DaVinci Resolve when you import the original clips in the watch folder into the Media Pool. You can
also link and unlink them manually as explained in the Managing Proxy Media section later in
this chapter.
Generating Proxy Media in Other Applications
Proxy files can also be generated in applications outside of DaVinci Resolve, such as other NLEs or
various media asset management systems. To properly link the proxy to its source media in DaVinci
Resolve, the proxy file must meet the following criteria:
 Proxy files must have identical timecode to the source file.
```
 Proxy files must have the same file name as the source file (excluding extensions).
```
 Proxy files must have the same frame rate as the source file.
 The format and codec used for proxy files must be supported in DaVinci Resolve.
If your proxy file meets these criteria, you’ll be able to manually link proxy media created in other
applications to source clips in the Media Pool as described below.
212Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Managing Proxy Media
You can check the status and location of all your proxy media in the List view of the Media Pool. Right-
click on any column heading and click the checkboxes of “Proxy” and “Proxy Media Path.”
 Proxy: This column shows the current proxy status.
```
None: Indicates no proxy media has been created.
```
```
Offline: Indicates a proxy has been created but cannot be found in the Proxy Media path.
```
```
(Resolution): A number indicating the resolution of the created proxy and that it is online.
```
 Proxy Media Path: The location of where DaVinci Resolve is looking for the proxy file. If this
location is incorrect, you can relink the proxy to a new path manually.
The proxy columns in List view, showing Proxy Media status and location
Linking Clips to Proxy Media
If you’ve created proxy media in another application, or moved the internally created proxy media out
of its default location in “ProxyMedia,“ you’ll need to manually link the proxies to their source media
files in your Media Pool.
To link proxy media to a source clip:
1 Select one or more clips in the Media Pool you wish to link proxy media to.
2 Right-click one of the selected clips, and choose “Link Proxy Media” from the contextual menu.
```
3 Use the file browser to find the specific proxy file or directory (in the case of multiple clips) to set a
```
new Proxy Media path, and click Open. If you select an incorrect file or directory, a warning dialog
box will appear and no linking will occur.
4 If the linking was successful, the proxy media icon will show up on the clip’s thumbnail in the
Media Pool.
The Proxy Icon showing in
the lower left corner of the
thumbnail, indicating proxy
media is linked for this clip
To unlink proxy media from a source clip:
1 Select a clip or clips in the Media Pool you wish to unlink proxy media from.
2 Right-click on any clip and select “Unlink Proxy Media” from the contextual menu. This will remove
the metadata link from proxy to source and will set the status in the Proxy column to “None.”
```
NOTE: Unlinking a proxy file does not delete it. The proxy file remains on the hard drive
```
where it was created. As of this writing, proxy files must be deleted manually using your
OS file system outside of DaVinci Resolve.
213Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Re-generating Proxy Media
You can generate more than one proxy file per clip. This can be useful if you want to set multiple
Camera Raw parameters and choose between them, or to create proxy files of different resolutions.
To generate a new proxy:
1 Make your desired changes to the current clip’s settings.
2 Right-click on the same clip and select “Generate Proxy Media” from the contextual menu.
A new proxy file is created in the same directory as the previously linked proxy file, and its file name
is appended with “_s00x” to differentiate it. The latest proxy generated is automatically linked to
the source file, but previous proxy versions are retained on disk, so you can then manually relink the
different versions as needed.
Switching Between Proxy Media and Original Media
You can switch between using your original source media and the proxy media for playback in the
Cut page by using the Proxy Handling icon in the Viewer, or in the Edit page, by selecting Playback >
Proxy Handling and selecting one of the following options.
Disable All Proxies: This option disables the proxies altogether and forces the original
media playback only. If the original media is not available, the clip is replaced with a Media
Offline graphic.
Prefer Proxies: This option will use proxy files for playback, and if there is no proxy file for a
clip, the original media will automatically be used instead. If the original media is not available,
the proxies will be used, and the timeline will have a purple line across it for the duration that
the original clips are missing.
Prefer Camera Originals: This option will use the original media files for playback, and if there
is no original media file for a clip, the proxy media will automatically be used instead, and the
timeline will have a purple line across it for the duration that the original clips are missing.
```
TIP: Regardless of the proxy mode, a purple line on your timeline indicates the original media
```
is missing and gives you a visual indicator to help identify those missing clips.
Using Proxy Files for Delivery
By default, the Deliver page always reverts proxies to the original source media for final output to
ensure the highest quality render. Checking the “Use proxy media” box in the Advanced Settings of
the Video Render settings in the Deliver page overrides this so DaVinci Resolve uses proxy media for
final output instead. This can be useful if you need to save rendering time while making dailies, or to
quickly create outputs of your timeline for producers or audio engineers where master quality is not
necessarily needed. You will also need to check the “Use proxy media” box if you are editing with
proxies and do not have access to the original source media.
214Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
```
Moving Proxies Using a DaVinci Resolve Archive (.dra)
```
When moving proxies from one DaVinci Resolve system to another, it can be time consuming and
```
problematic to manually copy many individual assets (proxies, graphics, source files, etc.) from different
```
folders and locations. By far the easiest way to move complete projects from system to system is by
letting DaVinci Resolve do all that file management for you, by creating a DaVinci Resolve Archive
```
(.dra). An archive file contains not only your project, but all its media as well, maintaining the file paths
```
and organization of the original project.
To create a DaVinci Resolve Archive file, right-click on any project in the Project Manager, and choose
“Export Project Archive” from the drop-down menu. Within this mechanism, a new Archive setting in
DaVinci Resolve makes working with proxies simple and elegant.
Creating a Proxy-Only Archive to Share
In the Archive Options dialog, if you check Proxy Media, and uncheck Media Files and Render Cache,
DaVinci Resolve will make an Archive using only the proxy media. This allows you to create a compact
and easily transported version of your project to either move to another computer, or to give to an
```
editor working remotely. If proxy media is not available for a clip (say a graphic or a media file you
```
```
didn’t create a proxy for in the first place), the original media is automatically exported to ensure that
```
nothing goes offline.
Archive Setting options for exporting only Proxy Media
The resulting .dra is a folder that is a fully self-contained version of your project and proxy media.
This folder can easily be moved from drive to drive, or zipped up and sent across the internet.
Working Remotely Using Proxy Media
The proxy workflow in DaVinci Resolve opens up many new possibilities for editing collaboration and
media management. For example, one common workflow is to use the RAW camera master source
clips in the editing suite but to then generate low resolution proxies to take home to edit on a laptop.
To create a portable set of proxies for editing on a laptop:
1 Set up the Resolution and Format settings for the proxies in the Project Settings. In this case, you
may want to use “Choose Automatically” and a low-bandwidth, easily editable codec like ProRes
LT or DNxHR LB.
2 Select all source media in the Media Pool and Generate Proxy.
```
3 Export a DaVinci Resolve Archive (.dra) onto an external drive, with only Proxy Media checked.
```
4 Go away. Once at home, connect that drive to your home laptop, and use the Restore Project
Archive command in the Project Manager to import the archive.
5 When you’ve finished working at home, export a timeline, bin, or project from your laptop when
finished, and bring just that file back into the edit suite to continue working with the original
source media.
215Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Another common scenario might involve sending proxies over the internet to an editor in
another city or country.
To send a project to another editor over the internet:
1 Set up the Resolution and Format settings for the proxies in the Project Settings. In this case,
you may want to use a low resolution like “quarter” or “one-eighth,” and a low-bandwidth,
highly-compressed codec like H.265 for the smallest file sizes possible.
2 Select all of the source media in the Media Pool and Generate Proxy.
```
3 Export a DaVinci Resolve Archive (.dra), with only Proxy Media checked.
```
4 Using the file compression tools in your OS, zip the archive folder so it becomes one large file.
5 Upload the resulting .zip to the online file sharing service you prefer, and send the download link
to the remote editor.
6 Once the other editor unzips and imports the archive, you and they can then simply send
timelines, bins, and/or project files back and forth to collaborate. These files are small enough to
transfer over email or an instant messaging service.
Additionally, you may have your editing computer connected via ethernet to a Media Asset
Management system that can create its own proxies. In order to edit smoothly via the network, you
need to use low bandwidth proxies instead of the source media.
To create proxy media externally to edit over a local network:
1 Import the original source media files to your Media Pool from the network storage system
you’re using.
2 Set up the proxy generation settings in your Media Asset Management software to accommodate
the amount of network bandwidth you expect to have access to.
3 Make sure the timecode and frame rate of the proxies match the original source media, and render
the proxies to a network location.
4 Select all of your original source media in the Media Pool, and choose “Link Proxy Media.”
5 Choose the proxy media at the network location where they’ve been rendered.
Proxy Media vs. Other Playback
Optimizations in DaVinci Resolve
There continue to be other methods of optimizing real time performance in DaVinci Resolve, so it’s
natural that one might wonder how this is different from Optimized media, Timeline Proxy Mode, and
other performance optimization techniques available in DaVinci Resolve. The key aspect of proxy
media that differentiates it is that proxy media is independent, portable, and can be created by
applications outside of DaVinci Resolve, if desired.
Proxy Media vs. Timeline Proxy Mode
One of the oldest performance optimization options, originally named “Proxy Mode” in previous
versions of DaVinci Resolve, has been renamed “Timeline Proxy Mode” in DaVinci Resolve 17 to
differentiate it from Proxy Media. While the new Proxy Media feature creates actual media files on disk,
“Timeline Proxy Mode” simply reduces the resolution of the timeline on-the-fly, allowing for increased
real time playback performance. To be clear, Proxy Media and Timeline Proxy Mode are two entirely
different features, which are wholly independent of one another.
216Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Proxy Media vs. the Render Cache
Proxy Media is designed to create easy-to-edit primary source material on the Timeline, for improved
performance before you start editing. The Render Cache is designed to improve the real time
```
performance of clips that have enough computationally intensive effects (such as Resolve FX, color
```
```
corrections, noise reduction, compound clips, fusion compositions, etc.) to slow playback, even at the
```
```
current Timeline resolution. Proxy Media is independent and portable (you can move clips wherever
```
```
you want; you just have to relink them afterward), while the Render Cache media is not designed to be
```
moved or interacted with externally and only works with the project it was made for.
Proxy Media vs. Optimized Media
On the surface, Proxy Media and Optimized Media appear similar in function. Both options are
designed to create lower bandwidth, easier to edit versions of source media. However, Optimized
Media is managed internally by DaVinci Resolve, cannot be exported, and is not user accessible.
In contrast, Proxy Media creates fully portable and independent media that can be easily managed
by the user.
Using Optimized Media,
Proxy Media, and Caching Together
How you use DaVinci Resolve’s various performance-enhancing features together is entirely up to you,
but you should know that they’re not an either/or proposition. For example, you can create optimized
media from the camera raw original clips in your project, then enable Timeline Proxy Mode playback
to enhance the performance of your 4K timeline, and turn on Smart Cache to speed up your work in
the Color page as you add Fusion effects, noise reduction, and Resolve FX or OFX to every clip. All of
these optimization methods work happily and seamlessly together to improve your performance while
keeping the image quality of your project as high as the Optimized, Proxy, and Cache formats you’ve
selected in the Master Settings panel of the Project Settings.
Which Playback Optimization
Method Should I Use?
DaVinci Resolve’s various playback optimization features are designed to specifically increase
performance to make up for hardware, storage, and bandwidth deficiencies, but knowing when to use
each method is essential to proper functionality. Included below is a quick reference.
 Timeline Proxy Mode: My timeline is playing back, just a little bit too slowly.
 Cache Clip: I need help playing back a few clips in real time that have heavy effects applied.
 Optimized Media: I need help playing back all my source media in real time, and I will only be
editing on this computer.
 Proxy Media: I need help playing back all my source media in real time, and I need to collaborate
and share this media with other users, programs, or outside storage locations.
217Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Other Project Settings
That Improve Performance
In addition to working with proxies, using reduced raw decoding quality, generating optimized media,
and enabling the Smart and User caches, there are five additional options in the Project Settings
window and one setting in the UI Settings panel of the User Preferences that you can use to further
improve real time performance if you’re working on an underpowered computer, at the expense of
lower image quality while you work. These settings can then be changed back to higher quality modes
prior to rendering.
```
 Set timeline resolution to: (Master Project Settings, Timeline Format) DaVinci Resolve is resolution
```
independent, so you can change the resolution at any time and all windows, tracks, sizing
changes, and keyframe data will be automatically recalculated to fit the new size. Lowering the
Timeline resolution while you’re grading will improve real time performance by reducing the
amount of data being processed, but you’ll want to increase Timeline resolution to the desired size
prior to rendering. This is effectively the same as using the Proxy command, but you get to choose
exactly what resolution you want to work at.
```
 Enable video field processing: (Master Project Settings, Timeline Format) You can leave this
```
option turned off even if you’re working on interlaced material to improve real time performance.
When you’re finished, you can turn this setting back on prior to rendering. However, whether or
not it’s necessary to turn field processing on depends on what kinds of corrections you’re making.
If you’re applying any filtering or sizing operations such as blur, sharpen, pan, tilt, zoom, or rotate,
then field processing should be on for rendering. If you’re only applying adjustments to color and
contrast, field processing is not necessary.
```
 Video bit depth: (Master Project Settings, Video Monitoring) Monitoring at 8-bit improves real time
```
performance, at the expense of possibly introducing banding to the monitored image.
```
 Monitor scaling: (Master Project Settings, Video Monitoring) Lets you choose which transform
```
filter to use when scaling video to fit into the Video format resolution you’ve specified. Options are
Bilinear and Basic.
```
 Resize Filter: (Image Scaling) A drop-down menu that lets you choose an alternate image
```
```
transform filter (such as Bilinear) that is lower quality but less processor intensive. A “Force sizing
```
highest quality” checkbox in the Render Settings list of the Deliver page helps make sure you
don’t accidentally render your final media at this lower quality setting, however.
```
 Hide UI overlays: (User Preferences, Playback Settings) Off by default. When using a single GPU
```
for both display and CUDA or OpenCL processing, or if your display GPU is underpowered, or
if you lack the PCIe bandwidth required for the currently specified resolution or frame rate, you
may be able to improve real time performance by turning this option on. When enabled, onscreen
controls such as the cursor, Power Window outlines, and split-screen views are disabled and
hidden during playback. When playback is paused, all onscreen controls reappear.
```
 Minimize interface updates during playback: (User Preferences, Playback Settings) On by default.
```
While enabled, this setting improves real time performance by hiding on-screen controls that
appear in the Viewer, such as the cursor, Power Window outlines, and split-screen views during
playback. When playback is stopped, onscreen controls reappear.
218Setup and Workflows | Chapter 8 Improving Performance, Proxies, and the Render Cache
MEDIA
Chapter 9
Data Levels,
Color Management,
and ACES
This chapter covers operational details that affect how color is managed for media
that is imported into and exported from DaVinci Resolve. If color accuracy is
important to you, then it’s a good idea to learn more about how Resolve handles
the data levels of each clip, how DaVinci Resolve Color Management helps you to
work with different formats, and how to use ACES.
Contents
Data Levels Settings and Conversions  220
Converting Between Ranges and Clipping 221
Internal Image Processing and Clip Data Levels  221
Assigning Clip Levels in the Media Pool  222
Video Monitoring Data Levels  222
Deck Capture and Playback Data Level  223
Output Data Level Settings in the Deliver Page  224
So, What’s the “Proper” Data Range for Output? 224
Introduction to DaVinci Resolve Color Management  224
Display Referred vs. Scene Referred Color Management  225
Updated RCM In DaVinci Resolve 17  225
Resolve Color Management for Editors  226
The Input, Timeline, and Output Color Space  226
The RCM Image Processing Pipeline  228
Identifying the Input Color Space of Different Clips  228
Simple RCM Setup  230
Automatic Color Management  230
Resolve Color Management Presets  231
Output Color Space  232
219Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Advanced RCM Setup  234
Single Setting vs. Dual Setting RCM  234
Setting the Input Color Space  235
Choosing a Timeline Color Space  236
Timeline Working Luminance 238
203 Nit Support for SDR to HDR  238
Gamut Limiting, Restricting Values Within a Larger Gamut  239
Input DRT Tone Mapping  239
Output DRT Tone Mapping  240
Use Inverse DRT for SDR to HDR Conversion  242
Use White Point Adaptation 242
Color Space Aware Grading Tools  243
Apply Resize Transformations In  243
Graphics White Level  243
Display HDR On Viewers If Available 244
```
HDR Mastering Is For (Studio Version Only) 244
```
Resolve Color Management and the Fusion Page  244
Ability to Bypass Color Management Per Clip  245
Exporting Color Space Information to QuickTime Files 245
Color Management Using ACES  246
Setting Up ACES in the Project Settings Window  247
ACES AMF 2.0  250
The Timeline Color Space in ACES Workflows is Fixed 252
Tips for Rendering Out of an ACES Project  252
Data Levels Settings and Conversions
Different media formats use different ranges of values to represent image data. Since these data
```
formats often correspond to different output workflows (cinema vs. broadcast), it helps to know where
```
your project’s media files are coming from, and where they’re going, in order to define the various data
range settings in DaVinci Resolve and preserve your program’s data integrity.
```
To generalize, with 10-bit image values (with a numeric range of 0–1023), there are two different data
```
```
levels (or ranges) that can be used to store image data when writing to media file formats such as
```
QuickTime, MXF, or DPX. These ranges are:
• Video: Typically used by Y’CBCR video data. All image data from 0 to 100 percent must fit
into the numeric range of 64–940. Specifically, the Y’ component’s range is 64–940, while
the numeric range of the CB and CR components is 64–960. The lower range of 4–63 is
reserved for “blacker-than-black,” and the higher ranges of 941/961–1019 are reserved for
“super-white.” These “out of bounds” ranges are recorded in source media as undershoots
and overshoots, but they’re not acceptable for broadcast output.
220Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
• Full: Typical for RGB 444 data acquired from digital cinema cameras, or film scanned to DPX
image sequences. All image data from 0 to 100 percent is simply fit into the full numeric
range of 4 to 1023.
Keep in mind that every digital image, no matter what its format, has absolute minimum and
maximum levels, referred to in this section as 0–100 percent. Whenever media using one data
range is converted into another data range, each color component’s minimum and maximum
data levels are remapped so that the old minimum value is scaled to the new data level
```
minimum, and the old maximum value is scaled to the new data level maximum;
```
```
• (minimum Video Level) 64 = 4 (Data Level minimum)
```
```
• (maximum Video Level) 940 or 960 = 1023 (Data Level maximum)
```
Converting Between Ranges and Clipping
Simply converting an image from one data range to another should result in a seamless change. All
“legal” data from 0–100 percent is always preserved and is linearly scaled from the previous data
range to fit into the new data range.
The exceptions to this are undershoots and overshoots that you’ve deliberately set, also referred to
as out-of-bounds levels. The overshoots and undershoots that are allowable in “Video Levels” media
```
(known as sub-black or super-black and super-white) are usually clipped when converted to full-range
```
“Full Levels.” However, DaVinci Resolve preserves this data internally, and these clipped pixels of
detail in the undershoots and overshoots are still retrievable by making suitable adjustments in the
Color page to bring them back into the “legal” range.
The out-of-bounds image data that’s preserved within the headroom of Video Levels by DaVinci
Resolve while working is usually clipped, however, when you either output to video or render your
output. There are two settings that let you get around this for instances where you want to preserve
these levels:
A checkbox in the Video Monitoring group of the Master settings, “Retain sub-black and
```
super-white data,” lets DaVinci Resolve output undershoots (sub-black) and overshoots
```
```
(super-white) to video when Data Level is set to Video. When this is turned off, these out-of-
```
bounds values are clipped on output.
A checkbox in the Advanced settings of the Render settings in the Deliver page, “Retain
```
sub-black and super-white data,” lets DaVinci Resolve render undershoots (sub-black) and
```
```
overshoots (super-white) to exported media when Data Level is set to Video.
```
Internal Image Processing and Clip Data Levels
It’s useful to know that, internally to DaVinci Resolve, all image data is processed as full range,
uncompressed, 32-bit floating point data. What this means is that each clip in the Media Pool,
whatever its original bit-depth or data range, is scaled into full-range 32-bit data. How each clip is
scaled depends on its Levels setting in the Clip Attributes window, available from the Media Pool
contextual menu.
Selecting Auto, Video,
or Full levels
221Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
By converting all clips to uncompressed, full-range, 32-bit floating point data, Resolve guarantees the
highest quality image processing that’s possible. As always, the quality of your output is dependent
on the quality of the source media you’re using, but you can be sure that Resolve is preserving all the
data that was present in the original media.
Assigning Clip Levels in the Media Pool
When you first import media into the Media Pool, either manually in the Media page or automatically
by importing an AAF or XML project in the Edit page, Resolve automatically assigns the “Auto” Levels
setting. When a clip is set to Auto, the Levels setting used is determined based on the codec of the
source media.
DaVinci Resolve generally does a good job of figuring out the appropriate Levels setting of each
clip on its own. However, in certain circumstances, such as when you’re working with media that was
originated in one format but transcoded into another, you may find that you need to manually choose
the appropriate settings so that the levels of each clip are interpreted correctly. This can be done
using each clip’s Levels setting in the Clip Attributes window, available from the Media Pool contextual
menu in either the Media or Edit pages.
To change a clip’s Data Level setting:
1 Open the Media or Edit page.
2 Select one or more clips, then right-click one of them and choose Clip Attributes.
3 Click the Levels ratio button corresponding to the data level setting you want to assign,
then click OK.
```
TIP: If you need to change the Levels setting of a range of clips that share a unique property
```
such as reel name, resolution, frame rate, or file path, you can view the Media Pool by column,
and sort by the particular column that will best isolate the range of media to which you need
to make a data level assignment.
Once you change a clip’s Levels setting, that clip will automatically be reconverted based on the new
assignment. If it appears to be correct, then you’re ready to work. If it doesn’t, then you may want to
reconsider the Levels assignment you’ve made, and you should check with the person who provided
the media to find out how it was generated, captured, and exported.
So long as the Levels settings used by your clips are accurate, you should be ready to work. However,
problems can still occur based on what external video hardware you’re using with your workstation,
and how you need to deliver the finished media to your client. For this reason, there are three
additional data level settings that you can use to maintain data integrity, while at the same time seeing
the proper image as you work.
Video Monitoring Data Levels
Superficial problems may result if the settings used by your external display differ from the settings
you’re using to process data levels in Resolve. Accordingly, there is a Video/Full Level setting in the
```
Master Settings panel of the Project Settings (in the Video Monitoring section).
```
When you change this setting, the image being output to your external display should change, but the
image you see in your Viewer will not. That’s because this setting only affects the data levels being
output via the video interface connecting the Resolve workstation to your external display. It has no
effect on the data that’s processed internally by Resolve, or on the files written when you render in the
Deliver page.
222Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
There are two options:
```
Video: This is the correct option to use when using a broadcast display set to the
```
```
Rec. 709 video standard (10-bit 64–940).
```
```
Full: If your monitor or projector is capable of displaying “full range” video signals, and you
```
```
wish to monitor the full 10-bit data range (4–1023) while you work, then this is the correct
```
option to use.
It is imperative that the option you choose in DaVinci Resolve matches the data range the
external display is set to. Otherwise, the video signal will appear to be incorrect, even though
the internal data is being processed accurately by DaVinci Resolve.
Auto/Video/Full Level
selection for monitoring
Deck Capture and Playback Data Level
There is a separate “Video/Data Level” setting that is specific to when you’re capturing from or
outputting to VTRs. This setting also affects the video signal that is output via the video interface
```
connecting the Resolve workstation to your VTR (which is usually also in the signal chain used for
```
```
monitoring). However, it only takes effect when you’re capturing from tape in the Media page, or
```
editing to tape in the Deliver page. If you never capture or output to tape, this setting will never
take effect.
This setting is found in the Deck Capture and Playback panel of the Project Settings.
The reason for a separate option for tape capture and output is that often you’d want to monitor in one
```
format (normally scaled Rec. 709), but output to tape in another (full range RGB 444). This way, you can
```
set up Resolve to accommodate this workflow, and then not have to worry about manually switching
your video interface back and forth.
There are two options:
```
Video: This is the correct option to use when you want to output conventional
```
Rec. 709 video to a compatible tape format.
```
Full: This is the correct option to use when you want to output “full range” RGB 444 video
```
to a compatible tape format.
Once tape ingest or output has finished, your video interface goes back to outputting using
the setting specified by the “Colorspace conversion uses” setting in the Master Settings panel
```
of the Project Settings (in the Video Monitoring section).
```
223Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Output Data Level Settings in the Deliver Page
Finally, there’s one last set of data level settings, available in the Render Settings list, within the Format
group. It’s the “Set to video or data level” drop-down menu. It’s there to give you the ability to convert
the data level of your rendered output, if necessary.
All media is output using a single data level, depending on your selection.
There are three options:
```
Automatic: The output data level of all clips is set automatically based on the codec you
```
select to render to in the “Render to” drop-down menu.
```
Video: All clips are rendered as normally scaled for video (10-bit 64–940).
```
```
Full: All clips are rendered as full range (10-bit 4–1019).
```
For most projects, leaving this setting on “Automatic” will yield the appropriate results.
```
However, if you’re rendering media for use by another image processing application (such as
```
```
a compositing application) that is capable of handling “full range” data, then full range output
```
is preferable for media exchange as it provides the greatest data fidelity. For example, when
outputting media for VFX work as a DPX image sequence, or as a ProRes 4444 encoded
QuickTime file, choosing “Unscaled full range data” guarantees the maximum available image
quality. However, it is essential that the application you use to process this media is set to read
it as “full range” data, otherwise the images will not look correct.
So, What’s the “Proper” Data Range for Output?
Strictly speaking, there is no absolutely “proper” data range to use when outputting image data.
As long as the Levels setting of each clip in the Media Pool is set to reflect how each clip was created,
your primary consideration is which data range is compatible with the media format or application
you’re delivering to. If the media format you’re exporting to supports either normally scaled or full
range, and the application that media will be imported into supports either normally scaled or full
range, then it’s really your choice, as long as everyone involved with the project understands how the
data range of the media is meant to be interpreted once they receive it.
Outputting to hardware is a bit trickier, in that you need to make sure that the external display or VTR
you’re outputting to is set up to receive a signal using the data range you’ve chosen. If the device is
limited to only one data range, then you need to be sure that you’re outputting to it using that data
range, or the levels of the image will appear to be incorrect, even though the image data being
processed by Resolve is actually fine.
Introduction to DaVinci Resolve
Color Management
How color is managed in DaVinci Resolve depends on the “Color Science” setting at the top of the
Color Management panel of the Project Settings. There are four options: DaVinci YRGB, DaVinci
YRGB Color Managed, DaVinci ACEScc, and DaVinci ACEScct. This section discusses the second
setting, DaVinci YRGB Color Managed. ACEScc and ACEScct is discussed in the following section in
this chapter.
224Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Display Referred vs. Scene Referred Color Management
The default DaVinci YRGB color science setting, which is what DaVinci Resolve has always used,
relies on what is called “Display Referred” color management. This means that Resolve has no
```
information about how the source media used in the Timeline is supposed to look; you can only
```
judge color accuracy via the calibrated broadcast display you’re outputting to. Essentially, you are
the color management, in conjunction with a trustworthy broadcast display that’s been calibrated to
ensure accuracy.
DaVinci Resolve 12 introduced a color science option called “DaVinci YRGB Color Managed,” or
```
more simply “Resolve Color Management” (RCM). This introduced a so-called “Scene Referred” color
```
management scheme, in which you have the option of matching each type of media you’ve imported
into your project with a color profile that informs DaVinci Resolve how to represent each specific color
from each clip’s native color space within the common working color space of the timeline in which
you’re editing, grading, and finishing.
This is important, because two clips that contain the same RGB value for a given pixel may in actuality
be representing different colors at that pixel, depending on the color space that was originally
associated with each captured clip. This is the case when you compare raw clips shot with different
cameras made by different manufacturers, and it’s especially true if you compare clips recorded using
the differing log-encoded color spaces that are unique to each camera.
This Scene Referred component of color management via RCM doesn’t do your grading for you, but
it does try to ensure that the color and contrast from each different media format you’ve imported
into your project are represented accurately in your timeline. For example, if you use two different
manufacturer’s cameras to shoot green trees, recording Blackmagic Film color space on one, and
recording to the Sony SGamut3.Cine/SLog3 color space on the other, you can now use RCM to make
sure that the green of the trees in one set of clips match the green of the trees in the other, within the
shared color space of the Timeline.
It should be mentioned that this sort of thing can also be done manually in a more conventional
Display Referred workflow, by assigning LUTs that are specific to each type of media, or using
Color Space Transform Resolve FX in order to transform each clip from the source color space to
the destination color space that you require. However, RCM’s automation can make this process
faster by freeing you from the need to locate and maintain a large number of LUTs to accommodate
```
your various workflows. Also, the matrix math used by RCM (as well as the Color Space Transform
```
```
operation) extracts high-precision, wide-latitude image data from each supported camera format,
```
preserving high-quality image data from acquisition, through editing, color grading, and output. These
are all advantages when compared to lookup tables, which can have plenty of precision, but can clip
out-of-bounds image data and introduce issues when differing lookup table interpolation methods
cause minor inconsistencies with color space transformations from application to application.
The preservation of wide-latitude image data deserves elaboration. LUTs clip image detail that goes
outside of the numeric range they’re designed to handle, so this often requires the colorist to make a pre-
LUT adjustment to “pull back” image data in the highlights that you want to retrieve. Using RCM eliminates
this two-step process, since the input color space matrix operations used to transform the source
preserves all wide-latitude image data, making highlights easily retrievable without any extra steps.
Updated RCM In DaVinci Resolve 17
In version 17, DaVinci Resolve introduced the biggest improvements to Resolve Color Management
```
(RCM) since it was originally introduced, adding numerous features to simplify setup, improve image
```
quality, and make the “feel” of your grading controls more consistent. Specific improvements include
improved metadata management for incoming media files that support color metadata, a new wide
gamut color space suitable for using as your default Timeline working color space for any program,
```
a new Input Tone Mapping option (Input DRT) that makes it easier to mix media formats for SDR and
```
```
HDR grading, improved Timeline to Output Tone Mapping (Output DRT) that offers improved shadow
```
225Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
and highlight handling, and select color space-aware grading palettes that make controls feel and
perform well no matter what you’re grading.
This updated Resolve Color Management has the same name as the previous version. However, older
projects using the previous version of RCM will have Color science set to Legacy, to preserve the
older color management settings and color transformations effect on your work. For more information
on how the previous generation of RCM works, see the September 2020 version of the DaVinci
Resolve 16 Manual.
How Is DaVinci Resolve Color Management Different from ACES?
This is a common question, but the answer is pretty simple. Resolve Color Management
```
(RCM) and ACES are both Scene Referred color management schemes designed to solve the
```
same problem. However, if you’re not in a specific ACES-driven cinema workflow, DaVinci
Resolve Color Management can be simpler to use, and will give you all of the benefits of color
management, while approximating the “feel” that the DaVinci Resolve Color page controls
have always had.
Resolve Color Management for Editors
RCM isn’t just for Colorists. RCM can be easier for editors to use in situations where the source
material is log-encoded. Log-encoded media preserves highlight and shadow detail, which is great for
grading and finishing, but it looks flat and unpleasant, which is terrible for editing.
Even if you have no idea how to do color correction, it’s simple to turn RCM on in the Color
Management panel of the Project Settings, and then use the Media Pool to assign the particular
Input Color Space that corresponds to the source clips from each camera. Once that’s done, each
log-encoded clip is automatically normalized to the default Timeline Color Space of Rec. 709
Gamma 2.4. So, without even having to open the Color page, editors can be working with pleasantly
normalized clips in the Edit page.
The Input, Timeline, and Output Color Space
The foundation of Resolve Color Management rests on three core settings. Not only do you have the
```
ability to either automatically or manually identify the color science of each individual source clip (the
```
```
Input Color Space), but you also have explicit control over the working color space within which all
```
```
color adjustments and operations are made (the Timeline Color Space), and you have separate control
```
over the Output Color Space that defines how your graded image will be monitored and output.
This means that, basically, Resolve Color Management consists of two color transforms working
together, converting each source clip via its Input Color Space definition into the Timeline Color Space
in which you work, and then converting the adjusted image from the Timeline Color Space to whatever
Output Color Space you require to deliver the project.
226Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Input Color Space Timeline Color Space Output Color Space
Resolve Color Management consists of three color transforms working together.
This means that, as a colorist, you can set the Timeline Color Space that you’re working in to whatever
you prefer. If you prefer grading wide-gamut log media because you like the way the grading controls
behave in that color space, you can set the Timeline Color Space in the Color Management panel of
```
the Project Settings to DaVinci Wide Gamut (more on this below), or any of the available log formats,
```
including ARRI Log C, REDWideGamutRGB/Log3G10, and Cineon Film Log. If you instead prefer
```
grading in the Rec. 709 color space because you’re mastering a standard dynamic range (SDR)
```
program to Rec. 709 and you’re more comfortable with how the controls in DaVinci Resolve have
always felt in that color space, you can choose that instead. Whatever Timeline Color Space you
assign is what all source clips will be transformed to for purposes of making grading adjustments in the
Color page, so you can make this choice using a single setting.
A key benefit of the color space conversions that RCM applies is that no image data is ever clipped
during the Input to Timeline color space conversion. For example, even if your source is log-encoded
or in a camera raw format, grading with a Rec. 709 Timeline Color Space does nothing to clip or
otherwise limit the image data available to the RCM image processing pipeline. All image values
greater than 1.0 or less than 0.0 are preserved and made available to the next stage of RCM
processing, the Timeline to Output color space conversion.
Consequently, if you’re grading in a color space other than the one you need to output to, you don’t
have to worry about data loss during the color transformation back to the color space you actually
want to output to. The Output Color Space setting gives you the freedom to work using whatever
Timeline Color Space you like while grading, with Resolve automatically converting your output to the
specific color space you want to monitor with and deliver to. And thanks to the precision of the image
processing in DaVinci Resolve, you can convert from a larger color space to a smaller one and back
again without clipping or a loss of quality. Of course, if you apply a LUT or use Soft Clip within a grade,
then clipping will occur, but that’s a consequence of using those particular operations.
```
TIP: If you want to use Resolve Color Management, but you want the Input and Output Color
```
Spaces to match whatever you set the Timeline Color Space to, you can choose “Bypass” in
the “Input Colorspace” and “Output Colorspace” drop-down menus.
227Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Finally, it is the Output Color Space that determines the final color space of your rendered result. While
no image data is clipped during the Source to Timeline color space conversion, image data will be
clipped during the Timeline to Output color space conversion in order for the final image to conform to
the color space being rendered and output, unless you use the Gamut Mapping options to compress
image data during the Timeline to Output Color Space conversion.
The RCM Image Processing Pipeline
The previous explanation is, of course, simplified. To clarify the inner workings of Resolve Color
Management for advanced users, the following flowchart presents a rudimentary overview of how
every parameter works together to automatically manage the color of clips in your program.
Input ColorSpace Input DRT TimelineColor
SpaceOutput DRT
YourGradeOuput ColorSpace Final Output
Timeline WorkingLuminance
SourceMedia
Manual ColorSpace Tagging
orSource Media Color
Space Metadataor
Input Color SpaceProject Setting
AffectsInput DRT
Resolve Color Management Parameters
AffectsOutput DRT
Resolve Color Management’s image processing pipeline, illustrated
Identifying the Input Color Space of Different Clips
Central to the process of automated color management is knowing the color space and transfer
```
function used by every clip of source media in your project. There are a variety of ways DaVinci
```
Resolve can figure this out, in a cascading decision-tree that can be manually overridden if necessary.
Deriving the Input Color Space involved the following stages of automated decision making:
1 If the source media is a camera raw format like .braw, .R3D, .ari, etc., DaVinci Resolve uses
manufacturer-supplied colorimetry to automatically debayer the clip and identify its Input
Color Space.
```
2 Otherwise, if the source media has embedded color space metadata (QuickTime or .MXF make
```
```
this possible), then use that to identify the Input Color Space.
```
3 Otherwise, if there is no embedded color space metadata, use the default Input Color Space
setting of the Project Settings to assign an Input Color Space to all otherwise unidentified clips.
4 If necessary, you can manually set the Input Color Space of clips in the Media Pool, which
```
overrides both embedded color space metadata (in case it’s wrong), or the default Input Color
```
```
Space setting (if you’re dealing with multiple color spaces). You cannot override the Input Color
```
Space of camera raw media.
The following sections discuss each of these steps in more detail.
228Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Using Camera Raw Formats
When you use RCM in a project that uses Camera Raw formats, color science data from each camera
manufacturer is used to debayer each camera raw file to specific color primaries with linear gamma,
so that all image data from the source is preserved and made available to DaVinci Resolve’s color
managed image processing pipeline. As a result, the Camera Raw project settings and Camera Raw
palette of the Color page are disabled, because RCM now controls the debayering of all camera
raw clips, and all image data from the raw file is available no matter which Timeline Color Space you
choose to work within.
Using Source Media Color Space Metadata
When enabled, RCM automatically identifies the color space information of imported media that’s
been either transcoded or recorded directly to supported non-raw media formats, reading the NCLC
metadata of QuickTime-wrapped files, the color space metadata of .mxf-wrapped files, and the XML
```
sidecar files that track color management in ACES workflows. This behavior is automatic; there are no
```
visible controls governing this behavior aside from the individual Input Color Space and Input Gamma
settings associated with each clip in the Media Pool.
Color Space Metadata in QuickTime
DaVinci Resolve is capable of reading the NCLC metadata found within media files wrapped within a
QuickTime container for proper color management. This metadata consists of three values formatted
```
as (for example) 1-1-1. From left to right, these three digits specify the Color Primary (or color space),
```
```
Transfer Function (or gamma), and Color Matrix used by that media file.
```
These values are standardized in the SMPTE Registered Disclosure Document RDD 36:2015. For your
information, the different codes are listed in the following table. In the previous example, the code
of 1-1-1 indicates a standard dynamic range clip that uses the BT.709 primaries, transfer function,
and color matrix.
Color Primary Transfer Function Color Matrix
0 Reserved 0 Reserved 0 GBR
1 ITU-R BT.709 1 ITU-R BT.709 1 BT709
2 Unspecified 2 Unspecified 2 Unspecified
3 Reserved 3 Reserved 3 Reserved
4 ITU-R BT.470M 4 Gamma 2.2 curve 4 FCC
5 ITU-R BT.470BG 5 Gamma 2.8 curve 5 BT470BG
6 SMPTE 170M 6 SMPTE 170M 6 SMPTE 170M
7 SMPTE 240M 7 SMPTE 240M 7 SMPTE 240M
8 FILM 8 Linear 8 YCOCG
9 ITU-R BT.2020 9 Log 9 BT2020 Non-
constant Luminance
10 SMPTE ST 428-1 10 Log Sqrt 10 BT2020
Constant Luminance
229Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Color Primary Transfer Function Color Matrix
11 DCI P3 11 IEC 61966-2-4 – –
12 P3 D65 12 ITU-R BT.1361 Extended
Colour Gamut
– –
– – 13 IEC 61966-2-1 – –
– – 14 ITU-R BT.2020 10 bit – –
– – 15 ITU-R BT.2020 12 bit – –
```
– – 16 SMPTE ST 2084 (PQ) – –
```
– – 17 SMPTE ST 428-1 – –
```
– – 18 ARIB STD-B67 (HLG) – –
```
The Default Input Color Space
The default Input Color Space can only be set if the “Resolve color management preset” drop-down
menu is set to Custom. Otherwise, it defaults to “Rec. 709 Gamma 2.4” for all presets. Or else, this
setting is the default color space that all otherwise unidentified clips in the Media Pool will default to.
Manually Tagging Clip Color Space
If necessary, you can manually identify the color space of one or more selected clips in the Media Pool
```
by right-clicking them and choosing the Input Color Space (and optionally the Input Gamma) from the
```
contextual menu.
Simple RCM Setup
When you first choose DaVinci YRGB Color Managed from the Color science drop-down menu of the
Color Management panel in the Project Settings, you’re presented with a simple pair of menus for
setting up how you want to work with Resolve Color Management: the “Resolve color management
preset,” and the “Output Color Space.”
Automatic Color Management
The first option when using RCM is to decide to use either Automatic Color Management or the
Manual Presets. When the Automatic Color Management box is checked, DaVinci Resolve presents
you with a simplified set of options for the most common use cases. For the Color Processing Mode,
you choose SDR or HDR, and based on the file types and codecs in the Media Pool, DaVinci Resolve
will automatically choose the appropriate input color space. Then, select from a list of common Output
color spaces for delivery. If you want specific control of these parameters, uncheck Automatic Color
Management box and select from the Color Management Presets below.
230Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIAAutomatic Color Management presets for fast, simple color management set up
Resolve Color Management Presets
The Resolve Color Management preset menu lets you choose how you want to use RCM to grade
your program. Each of these presets fully configures your project’s use of color management, and the
setting you select directly impacts how you’ll grade your program. Because of this, once you choose
a method of working and you grade every clip in your program, those grades rely on the preset you
used being selected in order to appear as they should.
Resolve Color Management presets for manual color management set up
When it comes to choosing a preset, a good way to think about which to use is to choose an SDR or
HDR preset that corresponds to the primary deliverable you plan on outputting. Both SDR and HDR
presets have several variations that you can choose among.
While these presets correlate to how you plan on outputting your program, they don’t lock you in,
```
since you can always change the Output Color Space (described below). This makes it possible to
```
export multiple versions of your program, each intended for different venues, no matter which color
management preset you’re using.
Whenever you choose a preset, a brief description explains the workflow that preset is intended to
facilitate. Here’s a list of the available presets, with slightly more detailed explanations.
```
 SDR Rec.709: (default) Sets up a Rec. 709 SDR grading environment. Your work can be converted
```
to HDR on output, if specified, but is limited to a Rec. 709 gamut with out-of-bounds colors
being clipped. Gamma 2.4 is not mentioned in the name because scene versus display OOTF is
managed automatically. Suitable for conventional streaming and broadcast.
 SDR P3 Broadcast: Sets up a P3-D65 SDR grading environment. Your work can be mapped
to HDR for output, if specified, but it is limited to a P3-D65 gamut with out-of-bounds colors
being clipped. Gamma 2.4 is not mentioned in the name because scene versus display OOTF is
managed automatically. Suitable for wider gamut streaming and broadcast at SDR levels.
231Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
 SDR P3 Cinema: Sets up a P3-D60 SDR grading environment. Your work can be mapped to HDR
for output, if specified, but it is limited to a P3-D60 gamut with out-of-bounds colors being clipped.
Suitable for conventional Cinema projection.
 SDR Rec.2020: Sets up a Rec. 2020 SDR grading environment. Your work can be mapped to HDR
for output, if specified. Good for wide gamut streaming and broadcast.
 DaVinci Wide Gamut: Sets up an extra wide gamut grading environment that’s suitable for grading
either SDR or HDR. Capable of exporting with maximum image fidelity, preserving highlight details
of up to 10,000 nits. This is a log-encoded grading space for colorists wishing to work that way.
Suitable for creating mezzanine intermediates or final deliverables, or for grading HDR with high
nit levels.
 HDR P3 Broadcast: Sets up a P3-D65 HDR grading environment. Output gamut is limited to
P3-D65, with out-of-bounds colors being clipped. Suitable for grading wide gamut SDR or HDR up
to 1000 nits.
 HDR Rec.2020: Sets up a Rec. 2020 HDR grading environment. Suitable for wide gamut SDR or
HDR deliverables up to 1000 nits.
 Custom: If none of the available presets suits how you need to work, you can choose Custom,
which exposes the full set of RCM settings for you to set up to suit your needs.
```
IMPORTANT: For all presets, importing media that’s in an identical or smaller gamut maps
```
the image data into the larger color space of the preset without transforming it. Importing
media with a wider gamut than the color space of the preset remaps the image data to fit into
the smaller color space, while preserving as much image detail as possible.
Output Color Space
For most DaVinci Resolve installations and projects, you’ll set your Output Color Space to match the
```
needs of your program, according to your display’s capabilities (or the capabilities your display is set to
```
```
use for the project at hand). You’ll also typically use a Resolve Color Management preset that matches
```
those capabilities.
However, RCM gives you the flexibility of grading in one color space and then outputting to others,
when necessary. For example, it’s easy to grade an SDR Rec. 709 version of a program for streaming
or broadcast, and then switch the Output Color Space to SDR P3 Cinema to output an additional
deliverable for theatrical exhibition.
To facilitate this, you can set the Output Color Space to any setting, independent of the Resolve Color
Management preset you’ve selected, and DaVinci Resolve will automatically convert from your Color
Management Preset to the Output Color Space of your choice. When you do so, here are the rules that
govern the resulting image transform.
When going SDR to HDR:
```
• 0-50 nits (18% mid-gray) in your program is mapped to 0-50 nits on output (no change).
```
```
• Everything from 51-90 nits in your program is remapped from 51 to 100 nits (slightly
```
```
expanded).
```
• Everything from 91-100 nits in your program is remapped from 101 to 1000 nits
```
(greatly expanded).
```
232Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Original SDR grade seen within an HDR scale,
After an automatic SDR to HDR conversion
When going from HDR to SDR, the reverse is done:
```
• 0-50 nits (18% mid-gray) in your program is mapped to 0-50 nits on output (no change).
```
```
• Everything from 51 to 100 nits in your program is remapped from 51-90 nits (slightly
```
```
compressed).
```
• Everything from 101 to 1000 nits in your program is remapped from 91-100 nits
```
(greatly compressed).
```
233Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
While these methods of converting between SDR and HDR provide an effective starting point for
conversion, they’re not meant to be an automatic solution. It’s critical that you do a trim pass whenever
outputting a deliverable in a new color space and EOTF, so you can check every clip and make
adjustments to improve the result when necessary.
```
NOTE: When converting SDR to HDR, this behavior may exaggerate noise in imported SDR
```
media that happens to have large flat expanses of bright colors. If you see particular clips that
show this issue, you can disable this behavior on a clip by clip basis in the Media Pool clip
contextual menu, or the Thumbnail Timeline contextual menu in the Color page, by toggling
“Inverse DRT for SDR to HDR Conversion.”
Advanced RCM Setup
Advanced users who need more detailed control over every aspect of RCM can choose Custom from
the Resolve Color Management preset menu. This exposes every control that’s available, which opens
a world of workflow possibilities for advanced users and post production facilities.
Because each of the settings encompasses a significant amount of functionality, the following sections
cover each particular parameter in detail.
```
NOTE: Older projects using RCM will have Color science set to Legacy, to preserve the
```
older color management settings and color transformations effect on your work. For more
information on how the previous generation of RCM works, see the September 2020 version
of the DaVinci Resolve 16 Manual.
Custom Color Management settings of Resolve Color Management, as updated in DaVinci Resolve 17
Single Setting vs. Dual Setting RCM
There are two ways you can set up RCM. When the “Use Separate Color Space and Gamma”
checkbox is turned off, the Color Management panel of the Project Settings exposes one drop-down
each for the Input, Timeline, and Output Color Space settings. Each setting lets you simultaneously
234Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
transform the gamut and gamma, depending on which option you choose. This makes it a bit simpler
to set up the transform you need.
Single setting Resolve Color Management
If you turn the “Use Separate Color Space and Gamma” checkbox on, then the Color Management
panel changes so that the Input, Timeline, and Output Color Space settings each display two pop-ups.
The first drop-down lets you explicitly set the gamut, while the second drop-down lets you explicitly
set the gamma. This makes it easier to see exactly which pair of transforms is being used at each
stage of RCM.
Dual setting Resolve Color Management
Additionally, Dual Setting RCM enables you to assign separate gamut and gamma transforms to clips in
the Media Pool.
Dual setting Resolve Color Management
assignments for Media Pool clips
Setting the Input Color Space
This setting is the default color space that all otherwise unidentified clips in the Media Pool will default
to, unless you manually identify the color space of these clips by right-clicking them and choosing an
```
Input Color Space (and optionally Input Gamma) from the contextual menu.
```
This setting does not affect media in camera raw formats, or media with embedded
color space metadata.
235Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Choosing a Timeline Color Space
The Timeline Color Space is the “working” color space that determines how each clip’s contrast and
color are mapped for adjustment, which in turn has an impact on how sensitive the effects and grading
controls are as you work. Some colorists prefer to work in the classic “video” color space of Rec. 709,
since the controls feel comfortable and familiar, particularly if you’re mastering SDR content. On the
```
other hand, colorists who are used to working with log-encoded media (likely using the Log controls)
```
often prefer to work in a more film-oriented workflow using Cineon, LogC, or other wide gamut,
logarithmically encoded formats.
If you’re outputting an SDR deliverable, any color space that you’re comfortable will produce good
results. However, if you’re outputting an HDR deliverable, it’s in your best interest to choose a wide
```
gamut Color Space (and Gamma) to obtain the best results on output. In this instance, DaVinci Wide
```
```
Gamut is a great choice (see below for more information).
```
No matter which Timeline Color Space you choose to work in, all clips in an edit are transformed from
the Input Color Space that’s either automatically or manually assigned to them, to the Timeline Color
Space setting to provide the final output. This is how you can grade within a Log-encoded timeline
color space and yet view a normalized or de-logged image.
```
IMPORTANT: Once you choose a Timeline Color Space and begin grading, do not change
```
your Timeline Color Space, or you’ll end up changing all of the grades that are built using
the mathematics it defines. You can always change the Output Color Space to create a new
deliverable, but all of your grades depend on the Timeline Color Space to render correctly.
DaVinci Wide Gamut Color Space and DaVinci Intermediate Gamma
```
DaVinci Wide Gamut (DaVinci WG) and DaVinci Intermediate are Timeline Color Space and Gamma
```
settings developed by Blackmagic Design that provide a reliable universal internal working color
space, which encompasses a practical maximum of what image data any given camera can capture.
The DaVinci Wide Gamut color space is greater than BT.2020, ARRI Wide Gamut, and even ACES, so
you don’t ever lose image data, no matter where your media is coming from.
The DaVinci Wide Gamut color space
236Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Furthermore, the primary color values of the DaVinci WG color space are set such that the process of
automatically mapping source media from different cameras into this gamut is extremely accurate as
part of the Input to Timeline Color Space conversion, and tone and saturation mapping from one color
space to another can be done more accurately in the Timeline to Output Color Space conversion.
This also helps to produce greater consistency among media from different cameras when making
```
manual grading adjustments (though some variations due to differences in camera and lens systems
```
```
will remain).
```
The DaVinci Intermediate OETF gamma setting has been designed to work with DaVinci Wide Gamut
to provide a suitable internal luminance mapping of high precision image data, in preparation for
mastering to either HDR or SDR standards, as your needs require, without losing image data.
The DaVinci Intermediate OETF seen encoding HDR levels
The DaVinci Intermediate OETF encoding SDR levels
237Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Resolve Color Management is extremely flexible, so you don’t have to use DaVinci Wide Gamut/
DaVinci Intermediate as your Timeline color space if you don’t want. However, it presents many
advantages and is worth trying out to see if it can improve your workflow.
For more information, see the “DaVinci Resolve Wide Gamut Intermediate” document at
```
https://www.blackmagicdesign.com/support/family/davinci-resolve-and-fusion.
```
Timeline Working Luminance
This control is only visible while the Resolve Color Management presets menu is set to Custom
Settings. The Timeline Working Luminance drop-down menu lets you choose how the Input DRT
```
(described below) maps the maximum level of a source image to the currently selected Timeline Color
```
Space. This setting also defines the maximum highlight level that’s possible to output into the currently
selected Output Color Space using the Output DRT.
While it’s typical to set this according to the mastering standard you’re grading to via a collection of
SDR and HDR labeled settings, there are additional settings available that make it possible to add
more automatic compression of highlights as you grade.
SDR 100: The conventional setting for grading SDR material with a maximum level of 100 nits.
HDR 500-4000: Conventional settings for grading HDR material at a variety of maximum
mastering levels. So long as output DRT isn’t set to None, there will be some manner of rolloff
in the highlights, unless inverse DRT is enabled, in which case there will be no rolloff.
SDR and HDR ER settings: These “extended range” settings each specify two values and
provide more headroom for aggressive grading of highlights by enabling DaVinci Resolve to
compress a greater range of out-of-bounds image data without clipping, which can result in a
smoother look.
Here’s how it works. Suppose you choose the setting “HDR ER 1000/2000.” In this case,
the Input DRT is used to map the maximum brightness of each source image to the range
specified by the first value, which is 1000 nits. Then, when you grade, the signal isn’t clipped
until it reaches the maximum range specified by the second value, which is 2000 nits. This
provides an additional 1000 nits of out-of-bounds headroom before the image data is hard
clipped by RCM’s image processing pipeline. The Output DRT is then used to map from the
```
maximum brightness specified by the second number (2000 nits) to the output value defined
```
by the currently selected Output Color Space, in the process compressing this out-of-bounds
headroom to preserve as much highlight detail as is possible given the range you’ve selected.
```
Custom: Exposes a field where you can enter a specific nit value.
```
203 Nit Support for SDR to HDR
This control is only visible while the Resolve Color Management presets menu is set to Custom
Settings. Resolve Color Management has support for remapping SDR content to HDR by mapping
```
100 nits to 203 nits (defined as the diffuse white level) according to the BT.2100 recommendation.
```
This enables the peak highlights of SDR material to compete more favorably against the significantly
```
brighter highlights of HDR content in programs that combine both (such as documentaries), so that
```
SDR whites continue to appear white, rather than gray, when compared to diffuse white in HDR.
238Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
The checkbox that enables this is hidden by default. Whenever you set the Output to an HDR standard
while the Timeline is set to an SDR standard, the “Use 203 nits reference for Rec.2100 HDR” checkbox
for remapping SDR highlights to HDR appears in both the RCM settings of the Color Management
panel of the Project Settings and in the Color Space Transform Resolve FX plugin.
The “Use 203 nits reference for Rec.2100 HDR” checkbox in Resolve Color
Management for scaling SDR levels appropriately into HDR color space
Gamut Limiting, Restricting Values Within a Larger Gamut
This control is only visible while the Resolve Color Management presets menu is set to Custom
Settings. In the emerging world of larger gamuts for distribution, it’s increasingly common for delivery
specifications to specify output to a large gamut, such as Rec. 2020, yet require that image values
be restricted to a smaller gamut, such as P3. This is to allow delivery to “future-proofed” delivery
standards, while preventing saturation values that are too high to be displayed on consumer displays
that aren’t capable of implementing the full scope of those standards.
In this case, you’ll choose a larger gamut in Output Color Space, but you’ll then choose a smaller
gamut in “Limit Output Gamut To.” When you do this, all image values falling outside the “Limit Output
Gamut To” standard specified will be hard clipped. This setting defaults to None.
Choose a setting from the Limit Output Gamut To menu to limit image values within a larger gamut
Input DRT Tone Mapping
This control is only visible while the Resolve Color Management presets menu is set to Custom
Settings. RCM has always transformed the color primaries of different media formats to match one
```
another within the shared Timeline Color Space. In this updated version, the Input DRT (Display
```
```
Rendering Transform) drop-down menu provides a variety of different options to enable DaVinci
```
Resolve to automatically tone map the image data of SDR and HDR clips to better match one another
when they’re fit into the currently selected Timeline Color Space. While each option varies in the
details, they are all automated input-to-timeline color transforms that do the following:
239Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
 Log-encoded media, or media using a 2.4 gamma transfer function, is mapped so the black point,
midtones at 18% gray, and white levels match those of HDR media. Highlight data will be carefully
stretched as necessary so that the highlights of all clips in the Timeline, whether SDR or HDR,
are treated similarly.
 Raw formats such as BRAW, RED, and ARRI RAW, and media using HDR transfer functions are
minimally mapped along an HDR range of tonality.
 All color transforms into the Timeline Color Space are done without clipping.
The idea is to distribute the image data of each clip in the Timeline, be it SDR or HDR media, along
a similar histogram, with shadows, midtones, and highlights spread out in such a way as to create an
easier starting point for grading. One result of this is that grades made for one type of media mostly
work well with other types of media.
Different options are provided governing the details of how this Input to Timeline Color Space
transform is achieved. They all do the same thing but have different advantages.
 None: This setting disables Input DRT Tone Mapping. No tone mapping is applied to the
Input to Timeline Color Space conversion at all, resulting in a simple 1:1 mapping to the
Timeline Color Space.
 Simple: A good mapping for color transforms from HDR to SDR.
 Luminance Mapping: Same as DaVinci, but more accurate when the Input Color Space of all your
media is in a single standards-based color space, such as Rec. 709 or Rec. 2020.
 DaVinci: This option tone maps the transform with a smooth luminance roll-off in the shadows and
highlights, and controlled desaturation of image values in the very brightest and darkest parts of
the image. This setting is particularly useful for wide-gamut camera media and is a good setting to
use when mixing media from different cameras.
 Saturation Preserving: This option has a smooth luminance roll-off in the shadows and highlights,
but does so without desaturating dark shadows and bright highlights, so this is an effective option
for colorists who like to push color harder. However, because over-saturation in the highlights
of the image can look unnatural, two parameters are exposed to provide some user-adjustable
automated desaturation.
```
Sat. Rolloff Start: Lets you set a threshold, in nits (cd/m2 ), at which saturation will roll off along with
```
highlight luminance. Beginning of the rolloff.
```
Sat. Rolloff Limit: Lets you set a threshold, in nits (cd/m 2 ), at which the image will be totally
```
desaturated. End of the rolloff.
Output DRT Tone Mapping
This control is only visible while the Resolve Color Management presets menu is set to Custom
Settings. To accommodate workflows where you need to transform one color space into another that
has a dramatically larger or smaller gamut, an additional group of settings have been added that can
help to automate the expansion or contraction of image data necessary to give a pleasing result.
Using the available options in the Output DRT drop-down menu will compress or expand your image
data as necessary during the Timeline to Output Color Space transformation that RCM performs when
monitoring or rendering a timeline, in order to make sure that the final result is either not clipping, or to
ensure that it’s taking better advantage of the new color space. This is not meant to provide your final
grade. Rather, it’s meant to give you a faster starting point, when you need it, for proceeding with your
own more detailed grade of the result.
240Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Here are some examples of what the Gamut Mapping controls of RCM can be used for:
1 If you’re working with high-dynamic-range log-encoded media and you’re outputting to Rec. 709
as you work, turning on Gamut Mapping lets RCM use saturation and tone mapping to give you a
more immediately pleasing image with highlight detail that’s not clipped.
2 If you’re working with standard-dynamic-range log-encoded media and you’re outputting to an
HDR format as you work, turning on Gamut Mapping lets RCM use saturation and tone mapping
to expand the highlights of the image to HDR strength to give you an image with more immediate
visual impact on HDR screens.
```
(Before/After) Gamut Mapping used to automatically fit
```
high-dynamic-range media into the Rec. 709 color space
```
The Output DRT (Display Rendering Transform) drop-down menu provides the following options.
```
 None: No tone mapping is applied to the Timeline to Output Color Space conversion at all,
resulting in a simple 1:1 output with no softness or rolloff applied. All image data outside of gamut
will be clipped.
 Simple: A good mapping for color transforms from HDR to SDR.
 Luminance Mapping: Same as DaVinci, but more accurate when all your media is in a single
standards-based color space, such as Rec. 709 or Rec. 2020, set to the Timeline and Output.
 DaVinci: This option tone maps your output with a smooth luminance roll-off in the shadows and
highlights, and controlled desaturation of image values in the very brightest and darkest parts
of the image. It’s been designed to give smooth, naturalistic highlights and shadows as you
push and pull the values of your images, without the need for additional settings. This setting is
particularly useful for wide-gamut camera media and is a good setting to use when mixing media
from different cameras.
241Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
 Saturation Preserving: This option has a smooth luminance roll-off in the shadows and highlights
to prevent clipping. It does so without desaturating dark shadows and bright highlights, so this
is an effective option for colorists who like to push color a bit harder. However, because over
saturation in the highlights of the image can look unnatural, two parameters are exposed to
provide some user-adjustable automated desaturation.
```
Sat. Rolloff Start: Lets you set a threshold, in nits (cd/m2 ), at which saturation will roll off along with
```
highlight luminance. Beginning of the rolloff.
```
Sat. Rolloff Limit: Lets you set a threshold, in nits (cd/m 2 ), at which the image will be totally
```
desaturated. End of the rolloff.
 RED IPP2: This setting lets you use RED IPP2 tone mapping to output to an SDR format, such as
```
Rec. 709; two settings are exposed with which to choose how your output will be shaped.
```
Output Tone Map: Lets you choose what kind of tone mapping you want to use for your output.
Options include: None, Low, Medium, and High.
Highlight Roll Off: Lets you choose what kind of highlight rolloff you want to use to prevent
clipping. Options include: None, Hard, Medium, Soft, and Very Soft.
HDR peak nits: A slider lets you choose the peak nit level you want to tone map to.
Defaults to 10,000 nits.
Use Inverse DRT for SDR to HDR Conversion
This control is only visible while the Resolve Color Management presets menu is set to Custom
```
Settings. A device rendering transform (DRT) is typically used when converting high dynamic range
```
media to a lower dynamic range color space/mastering standard. Thus, setting up a color transform
from SDR to HDR is an “inverse” operation to expand the dynamic range of SDR media to HDR
standards. The way this works is that levels at 100 nits are mapped to the maximum value set for the
Timeline Working Luminance parameter, and all other image levels are strategically tone mapped in
order to give yourself a good starting point for grading SDR media into an HDR program.
This setting also has a secondary use. With this setting turned on, you can output Rec. 709 clips with
color that’s identical to the input, with no compression in the highlights.
```
NOTE: Turning on “Use Inverse DRT for SDR to HDR Conversion” may exaggerate noise in
```
imported SDR media with large flat expanses of bright colors.
Use White Point Adaptation
This control applies a chromatic adaptation transform to account for different white points between
color spaces.
 Uncheck this box if you simply want to view the input color space’s white point unaltered in the
output color space. For example, wanting to use a P3-D60 mastered clip inside a P3-D65 timeline
for reference purposes.
 Check this box to apply the chromatic adaptation transform to convert the input white point to
match the output color space’s white point. For example, wanting a P3-D60 mastered clip to cut in
with other clips mastered in a P3-D65 timeline.
```
NOTE: This control is only visible while the Resolve Color Management presets menu is set
```
to Custom Settings.
242Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Color Space Aware Grading Tools
In DaVinci Resolve version 17, both Resolve Color Management and ACES enables “color space aware”
palettes, such as the new HDR palette, to have controls that feel consistent, no matter what color
space the original media is from, or what Timeline Color Space you’re using.
Other palettes, such as the Qualifier and Curves palettes, become color space aware when you turn
on the “Use Color Space Aware Grading Tools” checkbox in the Color Management panel of the
```
Project Settings (this is turned on by default). When you’re using color space aware grading tools, you
```
should not turn on HDR Mode for the node you’re working on.
 In the case of the Qualifier palette, this enables Qualifiers to create high-quality keys as you would
expect, no matter what the color space of the original media is, or what Timeline Color Space
you’re using.
 In the case of the Curves palette, this makes the overall range of each curve better fit the overall
data range of the current clip, making curves adjustments easier and more specific.
```
NOTE: This control is only visible while the Resolve Color Management presets menu is set
```
to Custom Settings.
Apply Resize Transformations In
When you’re using Resolve Color Management, a new “Apply Resize Transformations In” Project
Setting is available in the Color Management panel while the Resolve Color Management presets
menu is set to Custom Settings. This setting lets you choose which color space is used for resizing
operations. Ordinarily, resizing is done in Linear, but certain specialty workflows benefit from doing
resizing in other color spaces, so this option lets you choose which is best. The available options are:
```
Timeline: Uses the Timeline Color Space to perform all resizing operations.
```
```
Log: Uses a Log Color Space for resizing. Good for avoiding artifacts in certain high-contrast
```
images, such as titles and star fields.
```
Linear: Usually provides the best results with most SDR media.
```
Linear Mapped: Usually provides the best results with most HDR media.
```
Gamma: Provided in case you find a need for this option.
```
Gamma Mapped: Usually provides best results when mixing SDR media with
wide gamut and log-encoded media on the same timeline.
Graphics White Level
```
The “Graphics white level” setting lets you define a shared maximum level in nits (cd/m2 ) for titles,
```
generators, and selected effects that generate color. Changing this setting lets you change the
maximum level of all DaVinci Resolve-generated titles, generator graphics, and effects at once to
accommodate different mastering and output requirements.
243Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Display HDR On Viewers If Available
Turn this checkbox on if your computer monitors and operating system are capable of accommodating
HDR display. This allows the Viewers to show true HDR, according to the capabilities of your
computer monitor.
```
HDR Mastering Is For (Studio Version Only)
```
If you have a DeckLink 4K Extreme 12G or an UltraStudio 4K Extreme video interface, then DaVinci
Resolve 12.5 and above can output the metadata necessary to correctly display HDR video signals to
display devices using HDMI 2.0a when you turn on the “Enable HDR metadata over HDMI” checkbox
in the Master Project Settings.
The Enable HDR metadata over HDMI option in the
Master Project Settings lets you output HDR via HDMI 2.0a.
When you do so, a setting in the Color Management panel of the Project Settings, “HDR mastering
is for X” lets you specify the output, in nits, to be inserted as metadata into the HDMI stream being
output, so that the display you’re connecting to correctly interprets it. The output you specify should
match what your display is expecting.
The “HDR mastering is for” setting lets you insert
metadata for HDR output via HDMI 2.0a.
Resolve Color Management and the Fusion Page
Enabling RCM also allows the Fusion page to handle the color of clips automatically. Images output by
MediaIn nodes are automatically converted to Linear color space, which is the preferred color space
with which to perform high-quality compositing operations. Setting the LUT menu of each Viewer in
the Fusion page to Managed ensures that you’re looking at the image in Rec. 709, so that the image
looks correct to the artist even though they’re really working in the Linear color space. Each MediaOut
node then converts the image back to the timeline color space for handoff to the Color page.
With RCM off, you must manage color in the Fusion page manually, either using the Source Color
Space and Source Gamma Space settings of each MediaIn node, or using the CineonLog or FileLUT
nodes in your node tree.
For more information on how color management affects the Fusion page, and why the Linear
color space is preferable for compositing, see Chapter 76, “Controlling Image Processing and
Resolution.”
244Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Ability to Bypass Color Management Per Clip
When you right-click a clip in the Thumbnail Timeline of the Color page, a “Bypass Color Management”
setting appears underneath the Input Color Space and Input Gamma submenus that let you identify a
clip’s color characteristics. Choosing this option so that it appears checked lets you exclude that clip
from color management altogether, in the event you want to manually manage that clip using LUTs, the
Color Space Transform node, or simply by doing manual grading.
The Bypass Color Management option for clips in
the contextual menu of the Thumbnail Timeline
Exporting Color Space Information to QuickTime Files
If you render QuickTime files from the Deliver page, then color space tags will be embedded into each
```
file based on either the Timeline Color Space (if Resolve Color Management is disabled) or the Output
```
```
Color Space (if Resolve Color Management is enabled). Two settings in the Advanced Settings of the
```
Render Settings let you choose how color space metadata will be embedded into your output for
supported media formats, “Color Space Tag,” and “Gamma Tag.” These default to “Same as Project,”
which will match the Output Color Space currently selected in the Project Settings.
The Color Space Tag and Gamma Tag settings in the Render Settings
245Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Color Management Using ACES
```
The ACES (Academy Color Encoding Specification) color space has been designed to make scene-
```
referred color management a reality for high-end digital cinema workflows. ACES also makes it easier
to extract high-precision, wide-latitude image data from raw camera formats, in order to preserve high-
quality image data from acquisition through the color grading process, and to output high-quality data
for broadcast viewing, film printing, or digital cinema encoding.
An oversimplification of the way ACES works is that every camera and acquisition device is
```
characterized to create an IDT (Input Device Transform) that specifies how media from that device
```
is converted into the ACES color space. The ACES gamut has been designed to be large enough to
encompass all visible light, with more than 25 stops of exposure latitude. In this way ACES has been
designed to be future-proof, taking into consideration advances in image capture and distribution.
```
Meanwhile, an RRT (Reference Rendering Transform) is used to transform the data provided by
```
each image format’s IDT into standardized, high-precision, wide-latitude image data that in turn is
```
processed via an ODT (Output Device Transform). Different ODT settings correspond to each standard
```
of monitoring and output, and describe how to accurately convert the data within the ACES color
space into the gamut of that display in order to most accurately represent the image in every situation.
The RRT and ODT always work together.
Encode ACES to
ACEScc / ACEScct
DaVinci Image
ProcessingIDT
Decode ACEScc / ACEScct
back to ACES
ODT RRT
Monitoring
Image
Data
Disable
ODT for
Deliver
Page
Output
ACES signal and processing flow
By using the ACES color space and specifying an IDT and an ODT, you can ingest media from any
capture device, grade it using a calibrated display, output it to any destination, and preserve the color
fidelity of the graded image.
For more information on ACES see the ACES Central Website.
246Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Setting Up ACES in the Project Settings Window
There are four parameters available in the Color Science drop-down of the Color Management panel
of the Project Settings that let you set up DaVinci Resolve to use the ACES workflow:
Color science is: Using this drop-down menu, you can choose either DaVinci ACES, or
DaVinci ACEScc color science, which enables ACES processing throughout DaVinci Resolve.
```
ACEScc: Choose DaVinci ACEScc color science to apply a standard Cineon-style log encoding
```
to the ACES data before it is processed by DaVinci Resolve. This well defined common encoding
makes it possible for ASC CDL values to be used across systems using the same ACEScc
encoding. After processing, a reverse encoding is applied in order to output ACES linear data.
```
ACEScct: A variation of ACEScc that adds a roll-off at the toe of the image that’s different from
```
the encoding of ACEScc, in order to make color correction lift operations “feel” more like they do
with film scans and LogC encoded images, which makes it easier to raise the darkest values of the
image and get milky shadows, something that can be difficult with ACEScc. After processing, a
reverse encoding is applied in order to output ACES linear data.
ACES Version: When you’ve chosen one of the ACES color science options, this drop-down becomes
available to let you choose which version of ACES you want to use. You can choose from ACES 1.0.3,
```
ACES 1.1, ACES 1.2, ACES 1.3, or ACES 2.0 (the latest version).
```
ACES AMF: For Aces 1.3 or above, you can select an ACES AMF file to be applied. More details can be
found in the ACES AMF section below.
```
ACES Input Device Transform: This drop-down menu lets you choose which IDT (Input Device
```
```
Transform) to use for the dominant media format in use. DaVinci Resolve currently supports the
```
following IDTs:
ACEScc/ACEScct/ACEScg: Standardized transforms for each of these ACES standards.
```
ADX (10 or 16): 10-bit or 16-bit integer film-density encoding transforms meant for use if you’re
```
working with film scans that were initially encoded in an ACES workflow. This transform is
designed to maintain the variation in look between different film stocks.
```
ALEXA: Color management settings for all ARRI ALEXA cameras.
```
BMD Film/4K/4.6K: Color management settings for Blackmagic Design cameras.
Canon 1D/5D/7D/C200/C300/C300MkII/C500/C700: Color management settings for
Canon cameras.
```
DCDM: This IDT transforms X’Y’Z’-encoded media with a gamma of 2.6.
```
```
DCDM (P3D65 Limited): This IDT transforms X’Y’Z’-encoded media with a gamma of 2.6,
```
specifically hard clipped to a P3 gamut with a D65 white point.
DRAGONcolor/2 and REDgamma3/4/REDlogFilm combinations: Different combinations of the
DRAGONcolor, REDgamma, and REDlogFilm settings are provided for legacy RED workflows.
P3-D60: Transforms RGB-encoded image data with a D60 white point, intended for monitoring
with a P3-compatible display using a D60 white point.
```
P3-D65: Transforms RGB-encoded image data with a D65 white point; intended for monitoring
```
with a P3-compatible display using a D65 white point.
```
P3-D65 (D60 sim.): Transforms RGB-encoded image data with a D65 white point; intended to
```
simulate monitoring with a P3-compatible display using a D60 white point on a display with D65.
```
P3-D65 ST2084 (108/1000/2000/4000 nits): Transforms an image that’s compatible with the P3
```
```
color gamut, using the SMPTE standard PQ (ST.2084) tone curve for High Dynamic Range (HDR)
```
```
post-production. Three settings for four different peak luminance ranges are provided; which
```
one is appropriate to use depends on the maximum white level of the display used to create the
media. Preliminary standards exist for HDR displays with peak luminance at 1000 nits, 2000 nits,
and 4000 nits. A setting of 108 nits is provided for Kodak laser projection.
247Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
P3-D65: Transforms RGB-encoded image data with a D65 white point, intended for monitoring
with a P3-compatible display using a D65 white point.
```
P3-D65 ST2084 (1000/2000/4000 nits): Transforms an image that’s compatible with the P3 color
```
```
gamut, using the SMPTE standard PQ (ST.2084) tone curve for High Dynamic Range (HDR) post-
```
```
production. Three settings for three different peak luminance ranges are provided; which one is
```
appropriate to use depends on the maximum white level of the display used to create the media.
Preliminary standards exist for HDR displays with peak luminance at 1000 nits, 2000 nits, and 4000˛nits.
```
P3-DCI (D60 sim.): Produces output that’s specifically for output on a DCI projector with a
```
D60 white point. This output may look magenta on other display devices that aren’t set up for
DCI display.
```
P3-DCI (D65 sim.): Produces output that’s specifically for output on a DCI projector with a
```
D65 white point. This output may look magenta on other display devices that aren’t set up for
DCI display.
Panasonic V35: Color management settings for each listed camera.
Rec.2020: This IDT transforms media created with the wide-gamut standard for consumer and
broadcast television.
```
Rec.2020 ST2084 (1000/2000/4000 nits): This IDT transforms media created within the
```
wide-gamut standard for consumer and broadcast television, using the SMPTE standard PQ
```
(ST.2084) tone curve for High Dynamic Range (HDR) post-production. Three settings provided
```
for HDR televisions with different peak luminance capabilities.
```
Rec.2020 HLG (1000 nits): This IDT transforms media within the wide-gamut standard for
```
```
consumer and broadcast television and uses the Hybrid Log-Gamma (HLG) standard tone curve
```
```
for High Dynamic Range (HDR) post-production. A single setting is provided for HDR televisions
```
with peak luminance at 1000 nits.
```
Rec.709 (Camera): A deprecated legacy IDT for Rec. 709 that’s included for backward
```
compatibility. Converts the source data to linear based on Rec. 709 and transforms the result
to ACES, but while this transformation is technically correct, it’s not necessarily pleasing after
conversion through the matching ODT. For this reason, the academy updated to the following Rec.
709 IDT, which is the inverse of the Rec. 709 ODT.
Rec.709: A standard transform designed to move media in the Rec. 709 color space into the
ACES color space. This option is used for any other file type that might be imported, such as
ProRes from Final Cut Pro, DNxHD from Media Composer, and any media file captured from tape.
```
Rec.709 (D60 sim.): A standard transform designed to move media in the Rec. 709 color space
```
with a white point of D60 into the ACES color space.
REDColor2/3/4/REDGamma3/4/REDLogFilm combinations: Different combinations of the
REDcolor, REDgamma, and REDlogFilm settings are provided for legacy RED workflows.
```
RWGLog3G10: The standardized RED IPP2 color pipeline transform for all RED camera media.
```
If you’re working on a project that mixes media formats that require different IDTs, then you can assign
different IDTs to clips using the Media Pool’s contextual menu, or using the Clip Attributes window,
which is also accessible via the Media Pool’s contextual menu.
```
ACES Output Device Transform: This drop-down menu lets you choose an ODT (Output Device
```
```
Transform) with which to transform the image data for monitoring on your calibrated display, and when
```
exporting a timeline in the Deliver page. You can choose from the following options:
```
ADX (10 and 16): A standardized ODT designed for media destined for film output. Two settings
```
accommodate 10-bit and 16-bit output. This ODT is not meant to be used for monitoring.
```
DCDM: This ODT exports X’Y’Z’-encoded media with a gamma of 2.6 intended for handoff to
```
```
applications that will be re-encoding this data to create a DCP (Digital Cinema Package) for digital
```
cinema distribution. This can be displayed via an XYZ-capable projector.
248Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
```
DCDM (P3D60 Limited): Outputs a P3 hard-limited signal with a D60 white point.
```
```
DCDM (P3D65 Limited): Outputs a P3 hard-limited signal with a D65 white point.
```
```
P3 D60: Outputs RGB-encoded image data with a D60 white point; intended for monitoring
```
with a P3-compatible display using a D60 white point.
```
P3 D65: Outputs RGB-encoded image data with a D66 white point; intended for monitoring
```
with a P3-compatible display using a D66 white point.
```
P3 D65 (D60 sim.): Outputs RGB-encoded image data to simulate monitoring with a
```
P3-compatible display using a D60 white point on a display with a D65 white point.
```
P3 D65 (Rec.709 Limited): Outputs RGB-encoded image data with a D65 white point within a
```
P3 gamut that’s hard-limited to the color range of Rec. 709.
```
P3 D65 ST2084 (108/1000/2000/4000 nits): Outputs an image that’s compatible with the
```
```
P3 color gamut, using the SMPTE standard PQ tone curve for High Dynamic Range (HDR)
```
```
post-production. Three settings for three different peak luminance ranges are provided; which one
```
is appropriate to use depends on the maximum white level of your display. Preliminary standards
exist for HDR displays with peak luminance at 1000 nits, 2000 nits, and 4000 nits. A setting of
108 nits is provided to simulate an HDR signal clipped to an SDR range.
```
P3 DCI (D60 sim.): Outputs RGB-encoded P3 image data that appears as if with a D60 white point
```
on a DCI projector with a DCI white point.
```
P3 DCI (D65 sim.): Transforms RGB-encoded image data with a D61 white point (the DCI mastering
```
```
standard) that appears as if with a D65 white point.
```
```
P3-D65 ST2084 (1000/2000/4000 nits): Transforms an image that’s compatible with the P3 color
```
```
gamut, using the SMPTE standard PQ (ST.2084) tone curve for High Dynamic Range (HDR)
```
```
post-production. Three settings for three different peak luminance ranges are provided; which
```
one is appropriate to use depends on the maximum white level of the display used to create the
media. Preliminary standards exist for HDR displays with peak luminance at 1000 nits, 2000 nits,
and 4000 nits.
Rec.2020: This ODT is for compatibility with the full range of this wide-gamut standard for
consumer and broadcast television.
```
Rec.2020 (P3D65 Limited): Outputs a P3D65 hard-limited signal within this wide-gamut standard
```
for consumer and broadcast television.
```
Rec.2020 (Rec.709 Limited): Outputs a Rec. 709 hard-limited signal within this wide-gamut
```
standard for consumer and broadcast television.
Rec.2020 HLG: Outputs the full Rec. 2020 gamut to the Hybrid Log-Gamma standard for HDR.
```
Rec.2020 HLG (1000 nits, P3D65 Limited): Outputs a 1000 nit, P3D65 hard-limited signal within
```
the Rec. 2020 gamut and the Hybrid Log-Gamma standard for HDR.
```
Rec.2020 ST2084 (1000/2000/4000 nits): This ODT transforms media created within the wide-
```
```
gamut standard for consumer and broadcast television, using the SMPTE standard PQ (ST.2084)
```
```
tone curve for High Dynamic Range (HDR) postproduction. Three settings are provided for HDR
```
televisions with different peak luminance capabilities.
```
Rec.2020 ST2084 (1000/2000/4000 nits, P3D65 Limited): This ODT transforms media within
```
the wide-gamut standard for consumer and broadcast television but with hard clipping at the
boundary of the P3 gamut for televisions that are limited to the smaller P3 gamut for digital
```
cinema; also uses the SMPTE standard PQ (ST.2084) tone curve for High Dynamic Range
```
```
(HDR) post-production. Three settings are provided for HDR televisions with different peak
```
luminance capabilities.
Rec.709: This ODT is used for standard monitoring and deliverables for TV.
249Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
```
Rec.709 (D60 Sim): A standard transform designed to move media in the Rec. 709 color space
```
with a white point of D60 into the ACES color space.
```
sRGB: A standardized transform designed for media created for computer display in a
```
consumer environment.
```
sRGB (D60 Sim): A standardized ODT designed for media destined for computer display in a
```
consumer environment. Suitable for monitoring when grading programs destined for the web.
ACEScc/ACEScct/ACEScg: Standardized transforms for each of these ACES standards.
You must manually select an ODT that matches your workflow and room setup when working in ACES.
Process Node LUTs in: This drop-down menu lets you choose how you want to process CLF LUTs
that are added to nodes in your grades while working in ACES, such as Look LUTs in on-set or VFX
```
workflows. There are two choices: ACEScc AP1 Timeline Space (the default), and ACES AP0 Linear.
```
ACEScc AP1: For LUTs that have been designed to take the specific range of ACEScc data using
the AP1 primary coordinates.
ACES AP0: For LUTs that have been designed for normal ACES data from 65504 to -65504
floating point values.
```
NOTE: ACES grades require CLF LUTs that have been specifically created for ACES
```
workflows. If you want to apply a regular LUT within a grade, you must do a color space
transform to convert the image from ACES to whatever space the LUT was designed to work
```
within, and then another color space transform to convert the image back to ACES; however,
```
this workflow does not alway provide ideal results.
The Initial State of Clips When Working in ACES
Don’t worry if the initial state of each image file appears differently than what was monitored originally
on set. What’s important is that if the camera original media was well exposed, the IDT used in ACES
mode will retain the maximum amount of image data, and provide the maximum available latitude for
grading, regardless of how the image initially appears on the Timeline.
ACES AMF 2.0
DaVinci Resolve supports ACES AMF 2.0 files for import and export. ACES AMF is a sidecar file written
in XML that defines the input and output transforms of the clip. This makes sure that the correct input
and output transforms are applied throughout the post production pipeline. These files can either
be loaded at a project level or a clip level. Clips with the “applied” attribute set to true are tagged
appropriately with no transforms applied. However, if they are set as false, the transform is applied
within DaVinci Resolve.
```
NOTE: You must use version 1.3 or above of the ACEScc or ACEScct Color Science to
```
use AMF files.
250Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Working with AMF Files
```
Project level AMF: These will have all transforms applied. (i.e., any defined input, look, or output
```
```
transforms which have their “applied” attribute set to false will be applied.) The input and output
```
transforms are applied via the project settings “ACES Input Transform” and “ACES Output Transform”
menus, and these menus will display “From AMF” if they are using a transform from the loaded AMF file.
Clip level AMF: An AMF can be loaded from the Color page clip thumbnail context menu from the
Clip AMF menu. This list is also populated from the ACES Transforms AMF subfolder. A clip-level AMF
```
will not apply the output transform; that can only be applied from project settings. Any input or look
```
transforms will have their “applied” attribute set to false. The look transforms are applied within a
compound node labeled AMF LMTs.
ACES Gamut Compression: If the ACES reference gamut compress algorithm is specified in a look
transform within the AMF, it will set the “Apply ACES reference gamut compress” checkbox to checked.
The user can see what input, gamut compress, look and output transforms are applied by clicking the
“View Transforms” button at the bottom of the “Color Space & Transforms” section of the Settings >
Color Management section.
To Import an AMF
1 Place your AMF files in the ACES Transforms/AMF directory on your computer. This is
folder is found:
 MacOS: the users Library/Application Support/Blackmagic Design/DaVinci Resolve/Aces
Transforms/AMF
 Windows: the users AppData\Roaming\Blackmagic Design\DaVinci Resolve\Support\ACES
Transforms\AMF
 Linux: opt/resolve/Developer/DaVinciCTL/AcesTransforms/AMF
2 In the Project Settings, set the Color Management > Color Science setting to ACEScc or ACEScct.
3 Select the ACES version to be 1.3 or above.
4 Click on the ACES AMF drop-down menu, and select the AMF from the list.
Exporting AMF Files
There are three choices to select from when you export an AMF file.
Source Master mode:
• All the applied attributes will be set to false.
• A source master is not associated with any clips or images.
Dailies Request mode:
• You can select the folder to store the output AMFs.
• A dailies AMF is created for and associated with each clip, and the applied attribute will be
set to false.
VFX Request mode:
• A VFX AMF will only have the input transform with the applied attribute set to false.
251Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
AMF Delivery Behaviors
 For AMF delivery, the export AMF option can be chosen in the Deliver page render settings.
 When using Source Master, the images are rendered to ACES AP0 or Linear masters with only the
```
input transforms applied; all other transforms are set to applied false.
```
 The resulting AMF is not associated with any clips or images with an aim to define and transmit a
color pipeline with its post production look alongside ACES AP0 or Linear data.
 In Dailies Request, all transforms are applied on the rendered images and all transforms are
set to applied true.
 The resulting AMF is associated with each clip in the project.
 In VFX Request, the clips are rendered to ACES AP0 or Linear with only the input transform
applied and all other transformed are set to false.
To Export an AMF
1 Right-click on your timeline in the Media Pool.
2 Select Timelines > Export > AMF in the contextual menu.
3 Choose the type of AMF file to export: Source Master, Dailies Request, or VFX Request.
4 Enter the name of the AMF file and its save location in the file browser.
5 Click on the Save button.
The Timeline Color Space in ACES Workflows is Fixed
When you’re working in ACES, you do not get to change the Timeline Color Space as you do in
Resolve Color Management. The ACES working color space is a log-encoded color space, which
encourages a more traditional, film-oriented approach to grading.
Tips for Rendering Out of an ACES Project
When choosing an output format in the Deliver page, keep the following in mind:
• If you’ve delivering graded media for broadcast, set the ACES Output Device Transform to
be Rec. 709, then you can output to whatever media format is convenient for your workflow.
• When you’re delivering graded media files to another ACES-capable facility using the
```
DCDM or ADX ODCs, you should choose the OpenEXR RGB Half (uncompressed) format
```
in the Render Settings, and set the ACES Output Device Transform to “No Output Device
Transform.”
• When you’re rendering media for long-term archival, you should choose the OpenEXR
```
RGB Half (uncompressed) format in the Render Settings, and set the ACES Output Device
```
Transform to “No Output Device Transform.”
252Setup and Workflows | Chapter 9 Data Levels, Color Management, and ACES
MEDIA
Chapter 10
HDR Setup
and Grading
```
High Dynamic Range (HDR) grading for cinema, television, and streaming is the
```
latest evolution of the consumer media experience.While HDR workflows in
high-end cinema and television aren’t new, this way of mastering media has been
slow to expand to less expensive programming.
However, new developments and an expanding array of affordable HDR-capable consumer devices
are poised to make HDR mastering of visual content increasingly ubiquitous.
This chapter describes what HDR is for the uninitiated and covers the operational details that will let
you set up DaVinci Resolve to do HDR grading.
Contents
```
High Dynamic Range (HDR) Grading in DaVinci Resolve  254
```
HDR Isn’t Just for Televisions 255
The Different Ways of Mastering HDR  255
What Do I Do With HDR?  256
Analyzing HDR Signals Using Video Scopes  256
Dolby Vision ®  258
Organizing Your Timeline for Dolby Vision Mastering 260
Letterboxing for Dolby Vision Mastering  260
Setting Up Color Management for Dolby Vision Mastering  260
Choosing Mastering Displays for Dolby Vision  261
```
Using the Dolby Vision Internal Content Mapping Unit (iCMU) 261
```
Simultaneous Master and Target Display Output for Dolby Vision  262
HDMI Tunneling using DeckLink 8K Pro G2  262
```
External Content Mapping Unit (eCMU) for Dolby Vision  264
```
Auto Analysis is Available to All Studio Users  264
Licensing DaVinci Resolve to Expose Dolby Vision Trim Controls  265
Dolby, Dolby Vision, and the double-D symbol are registered trademarks of Dolby Laboratories Licensing Corporation.
253Setup and Workflows | Chapter 10 HDR Setup and Grading
MEDIA
```
High Dynamic Range (HDR)
```
Grading in DaVinci Resolve
The HDR features found in DaVinci Resolve are only available in DaVinci Resolve Studio.
```
High Dynamic Range (HDR) video describes an emerging family of video encoding and distribution
```
technologies designed to enable a new generation of television displays to play video capable of
intensely bright highlights and increased saturation. The general idea is that the majority of an HDR
```
image will be graded similarly to how a Standard Dynamic Range (SDR) image is graded now, with the
```
shadows and midtones being mostly the same between traditionally SDR and HDR-graded images.
```
This is mostly because shadows are shadows and are meant to be dark; however this philosophy
```
also maintains a comfortable viewing experience and easier backward compatibility when you need
to master both SDR and HDR versions of a program. The difference is that HDR provides abundant
additional headroom for very bright highlights and color saturation that far exceed what has been
previously visible in SDR television and cinema. This enables the colorist to create more vivid and
life-like highlights in images, such as sunsets, lit clouds, firelight, explosions, sparkles, and other
intensely bright and colorful imagery. In short, you can now “open up” the highlights in an image just
Dolby Vision ® Trim Controls in DaVinci Resolve  265
Previewing and Trimming At Different Levels  268
Managing Dolby Vision Metadata  268
Setting Up Resolve Color Management for Grading HDR  269
DaVinci Resolve Grading Workflow For Dolby Vision  270
Delivering Dolby Vision  271
SMPTE ST.2084 and HDR10 272
Monitoring and Grading to ST.2084 in DaVinci Resolve  274
Connecting to HDR-Capable Displays using HDMI 2.0a  274
HDR10+™  275
Monitoring and Grading to ST.2084 for HDR10+ 275
HDR10+ Grading Workflow 275
Simultaneous Master and Target Display Output for HDR10+ 275
HDR10+ Auto Analysis Commands  276
Delivering HDR10+  276
HDR Vivid  277
Monitoring and Grading to ST.2084 for HDR Vivid  277
HDR Vivid Grading Workflow  277
Simultaneous Master and Target Display Output for HDR Vivid  277
HDR Vivid Trim Controls in DaVinci Resolve  278
Delivering HDR Vivid  279
```
Hybrid Log-Gamma (HLG)  279
```
Grading Hybrid Log -Gamma in DaVinci Resolve  280
Ouputting Hybrid Log-Gamma 280
```
Generate HDR Light Level Report (Studio Version Only)  281
```
254Setup and Workflows | Chapter 10 HDR Setup and Grading
MEDIA
as you’ve always been able to open up, or expand, the detail of the shadows. This not only provides
more life-like lighting intensity and saturation, but it also dramatically expands the contrast available
in the scene. For example, a calibrated SDR display should have a peak luminance level of 100 nits
```
(cd/m2 ), but existing HDR displays can provide peak luminance levels of 700, 1000, or even 4000 nits.
```
However, because it’s an evolving technology, the technical standards that have been developed
far exceed what current consumer televisions, projectors, phones, and tablets are capable of. At the
time of this writing, consumer televisions are capable of outputting 700 to 1600 nits. Furthermore,
```
consumer displays are often saddled with automatic brightness limiting (ABL) circuits that limit power
```
consumption to acceptable levels for home use, which means that only a certain percentage of the
picture may reach these peak values at any one time. This is fine, because the point of HDR is not that
you’re making the entire image brighter, it’s that you have more headroom for specific bright highlights
and additional saturation.
For all of these reasons, HDR standards focus on describing what displays should be capable of, not
how these levels are to be used. That is a creative decision.
HDR Isn’t Just for Televisions
Lest you think that living room televisions and projectors are the only way to watch HDR content,
certain flagship iOS and Android phones and tablets have implemented HDR viewing capabilities that
are capable of meeting or even exceeding the UltraHD requirements for HDR content on an OLED
display. This makes HDR, surprisingly, a widely available mobile experience.
The Different Ways of Mastering HDR
While different HDR technologies use different methods to map the video levels of your program to
an HDR display’s capabilities, they all output a “near-logarithmically” encoded signal that requires a
compatible television that’s capable of correctly stretching this signal into its “normalized” form for
viewing. This means if you look at an HDR signal that’s output from the video interface of your grading
workstation on an SDR display, it will look flat, desaturated, and unappealing until it’s plugged into your
HDR display of choice.
A graded HDR image being output looks similar to a log-encoded image
At the time of this writing, there are five principal approaches to mastering HDR that DaVinci Resolve is
capable of supporting, including:
 Dolby Vision ®
 HDR10
 HDR10+
 HDR Vivid
```
 Hybrid Log-Gamma (HLG)
```
255Setup and Workflows | Chapter 10 HDR Setup and Grading
MEDIA
Each of these HDR standards define how an HDR signal is encoded for export and later mapped to the
visible output of an HDR or SDR display. Grading to each of these standards requires some degree of
color management, and DaVinci Resolve gives you three main ways to handle this:
```
 The easiest way is to enable Resolve Color Management (RCM) or ACES in the Color Management
```
panel of the Project Settings, and use the Color Space conversion options that are available.
There are options there for each supported type of HDR.
 The transforms that are available in RCM are also available as Resolve FX operations, if you want to
organize your grading pipeline more manually using the Color Transform Resolve FX adjustment.
 LUTs are also available to accomplish each of these color space conversions if you want to develop
your own specific image processing pipeline based on custom-made LUT or DCTL transforms.
Overall, Resolve Color Management and ACES are reliable and recommended approaches to handling
HDR grading in DaVinci Resolve in most instances.
For more information about Resolve Color Management, see Chapter 9, “Data Levels, Color
Management, and ACES.”
What Do I Do With HDR?
While these standards make HDR mastering and distribution possible, they have nothing to say about
how these HDR-strength levels should be used creatively. That’s up to you, because the question of
how to utilize the expansive headroom for brightness and saturation that HDR enables is fully within
the domain of the colorist, as a series of creative decisions that must be made regarding how to assign
the range of highlights that are available in your source media to the above-100 nit HDR levels you’re
mastering to as you grade, given the peak luminance level that you’re assigned to master with. Which
```
HDR peak luminance level you use (1000 nit, 3000 nit, 4000 nit) probably depends on which display
```
you have access to and who’s distributing the resulting program.
Analyzing HDR Signals Using Video Scopes
When you’re using waveform scopes of any kind, including parade and overlay scopes, the signal will
fit within the 10-bit scale used to analyze the signal much differently owing to the way HDR is encoded.
```
The following chart of values will make it easier to understand how each level in “nits” (i.e., cd/m2 )
```
corresponds to a code value within the 10-bit image scale:
10-Bit Code
Nearest
Value in cd/m2 HDR Display Peak Luminance Capability
1019 † 10,000 No commercially available display
948 5000 Outdoor LED Displays
920 4000 Professional HDR Displays from Sony, Dolby, Flanders Scientific, EIZO, etc.
889 3000 Professional HDR Displays from Sony, Dolby, Flanders Scientific, EIZO, etc.
844 2000 Professional HDR Displays from Sony, Dolby, Flanders Scientific, EIZO, etc.
824 1600 Virtual Production Wall Panels
767 1000 Professional HDR Displays from Sony, Dolby, Flanders Scientific, EIZO, etc.
728 700 OLED mobile phone brightness
691 500 Minimum standard for an “UltraHD” OLED display
256Setup and Workflows | Chapter 10 HDR Setup and Grading
MEDIA
10-Bit Code
Nearest
Value in cd/m2 HDR Display Peak Luminance Capability
635 300 Professional SDR displays in “HDR preview mode”
593 203 BT.2408 recommendation for diffuse white of SDR content being intercutwith 1000 nit max HDR content
528 108 Dolby Cinema projector
520 100 Standard peak luminance for SDR displays
447 48 Standard peak luminance for SDR DCI projection, Dolby Cinema 3D peakluminance
4† 0 Absolute black
† 0–3 and 1020–1023 are reserved values
While this table of values is useful for understanding where HDR nit levels fall on legacy external
scopes, if you’re monitoring with the built-in video scopes in DaVinci Resolve, you can turn on
```
“HDR (ST.2084/HLG)” in the Waveform Scale Style settings in the Scopes option menu, which
```
```
replaces the 10-bit scale of the video scopes with a scale based on nit values (or cd/m2 ) instead.
```
```
The video scopes with HDR (ST.2084/HLG) on in the Waveform Scale Style settings in the Scopes option menu
```
```
TIP: If you’re unsatisfied with the amount of detail you’re seeing in the 0–519 range
```
```
(0–100 nits) of the video scope graphs, then you can use the 3D Scopes Lookup Table setting
```
in the Color Management panel of the Project Settings to assign the appropriate “HDR X nits
to Gamma 2.4 LUT,” with X being the peak nit level of the HDR display you’re using. This
converts the way the scopes are drawn so that the 0–100 nit range of the signal takes up the
entire range of the scopes, from 0 through 1023. This will push the HDR-strength highlights
up past the top of the visible area of the scopes, making them invisible, but it will make it
easier to see detail in the midtones of the image.
257Setup and Workflows | Chapter 10 HDR Setup and Grading
MEDIA
HDR Viewers
You can display the native viewers in DaVinci Resolve in HDR on Mac and Windows systems.
The setting affects all DaVinci Resolve viewers, including the main page viewers, Cinema Mode,
Fairlight Floating Viewer, Scene Cut Dialog, and the Video Clean Feed.
You will need an HDR-capable display and to turn on HDR in your OS:
```
 Activate the Windows HDR display settings (System > Display > HDR).
```
```
 Activate the Mac HDR display settings (System Settings > Displays > High Dynamic Range).
```
 In DaVinci Resolve Preferences > System > General, you will need to check the “Use 10-bit
precision in viewers if available” box.
```
NOTE: The general controls/UI and non-viewer dialogs (e.g., secondary screen, project
```
```
manager, floating Media Pool) are not affected.
```
Dolby Vision®
Long a pioneer and champion of HDR for enhancing the consumer video experience,
Dolby Laboratories has developed a method for mastering and delivering HDR called Dolby Vision.
```
As with most HDR standards discussed in this chapter, Dolby Vision uses the PQ (perceptual quantizer)
```
```
electrical-optical transfer function (EOTF, which defines how an electronic video signal is presented on
```
```
a display), which is defined by SMPTE ST.2084, along with a hierarchy of metadata that’s embedded
```
alongside the video stream. All metadata used by Dolby Vision is organized into levels, of which the
following are important to the colorist:
```
 Level 0 metadata, which is global metadata that defines the Mastering Display (what the colorist is
```
```
using), including aspect ratio, frame rate, color encoding and information on all the target displays
```
that are used for the Level 2 and Level 8 trim metadata below.
 Level 1 metadata, which is the Dolby Vision v2.9 analysis metadata that’s generated automatically
when you use the Dolby Vision controls to analyze the clips in the timeline. The controls for
automatically generating Level 1 metadata are available to all DaVinci Resolve Studio users.
 Level 2 metadata, which is the Dolby Vision v2.9 trimming metadata that’s set by the colorist via
the version 2.9 trim controls available in the Dolby Vision palette of the Color page. This trimming
```
allows adjustment of how the Dolby Vision image is to be mapped to a target display (such as
```
```
a 100 nit BT.709 display) that’s different from the mastering display (such as a 1000 nit BT.2020
```
```
display). The purpose of this metadata is to maintain a program’s artistic intent by providing
```
guidance from the colorist over how the program’s signal should be fit into the differing luminance
ranges of a variety of displays with different peak luminance capabilities. Manually adjustable
Level 2 metadata is only available to DaVinci Resolve Studio users via a license obtained from Dolby.
 Level 3 metadata, which is the offset for Dolby Vision v4.0 added to Level 1 metadata generated
by the analyze buttons in the Dolby Vision controls. It also stores the mid tone offset data.
 Level 5 metadata, which provides information about the aspect ratio of the deliverable format, and
the aspect ratio of the actual image within that format. This metadata is also applicable at the per
clip level.
258Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
 Level 6 metadata, which stores the MaxCLL and MaxFALL levels required by the HDR10 mastering
standard of HDR.
 Level 8 metadata, which is the updated Dolby Vision v4.0 trimming metadata that’s set by the
colorist via the v4.0 trim controls available in the Dolby Vision palette of the Color page. This
evolved set of trimming commands allows more detailed adjustment of how the Dolby Vision
```
image is to be mapped to a target display (such as a 100 nit BT.709 display) that’s different from
```
```
the mastering display (such as a 1000 nit BT.2020 display). Just like Level 2 metadata, the purpose
```
of Level 8 metadata is to maintain a program’s artistic intent by providing guidance from the
colorist over how the program’s signal should be fit into the differing luminance ranges of a variety
of displays with different peak luminance capabilities. Manually adjustable Level 8 metadata is
only available to DaVinci Resolve Studio users via a license obtained from Dolby. Whether you
use Level 2 trim controls or Level 8 trim controls depends on the Dolby Vision version setting you
choose in the Color Management panel of the Project Settings.
```
NOTE: It’s currently recommended for all users to choose Dolby Vision v4.0 for analysis
```
and trimming, as it provides superior results. If you’re required to deliver Dolby Vision v2.9
metadata when mastering for backwards compatibility, DaVinci Resolve can now export v2.9
metadata from projects using v4.0 workflows.
The metadata levels described above are current of this writing. However Dolby Vision
is a rapidly evolving technology, and as Dolby adds new features and metadata levels
you should reference Dolby’s website to keep track of the latest developments: https://
professionalsupport.dolby.com/s/article/Dolby-Vision-Metadata-Levels?language=en_US
For the foreseeable future, the current consumer display landscape encompasses a wide variety of
differently performing televisions and projectors that are guaranteed to improve year over year. This
means that mastering for today’s displays may render content less vibrant than content that emerges
five years from now. This can be especially vexing for narrative content that will have a long lifespan on
streaming services as new generations of viewers discover them. While one way of solving this would
be to re-grade your program many times at a variety of nit levels to create deliverables suitable to a
range of display capabilities, that’s an enormous amount of work.
Dolby Vision offers a shortcut by using sophisticated algorithms to derive automatically analyzed
```
metadata that intelligently guides how an image graded at one nit level (say 4000 nits) can be
```
adjusted to be perceptually similar to viewers watching a 1000 nit display. Highlights and saturation
that are too bright for a particular display will be adjusted to provide as close to the same experience
without clipping or flattening image detail.
Furthermore, this automatic analysis can be manually trimmed by a colorist to account for the artistic
intentions of the authors of a program, in cases where the automatic analysis doesn’t do exactly what’s
wanted. This combination of auto-analysis and manual trimming is key to how Dolby Vision streamlines
the process of mastering programs to accommodate backward compatibility with SDR displays, as
well as the varying peak luminance capabilities of different makes and models of HDR consumer
displays, both now and in the future. You’re only required to make a 100 nit trim pass to guide the HDR
program’s conversion all the way down to SDR, and the Dolby Vision system can use that information
```
to guide how intermediate presentations (such as at 700 or 1200 nits) should be adjusted. You can
```
even do multiple trim passes at specific nit levels, such as a 100 nit pass and a 1000 nit pass, to give
the Dolby Vision system more information to accurately guide intermediate presentations on different
displays. Additionally, you don’t have to trim every clip. If the analysis is good, you can skip those clips
and only trim clips that need it. The overall system has been created to make it as efficient as possible
for colorists to ensure that the widest variety of viewers see the image as it’s meant to be seen.
This, in a nutshell, is the advantage of the Dolby Vision system. You can grade a program on a more
future-proofed 4000 nit display, and use auto-analysis plus one or two manual trim passes to make
259Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
the program backward compatible with SDR televisions, and capable of intelligently scaling the HDR
highlights to provide the best representation of the mastered image for whatever peak luminance and
color volume a particular television is capable of. All of this is guided by decisions made by the colorist
during the grade.
At the time of this writing, all seven major Hollywood studios are mastering in Dolby Vision for cinema.
Studios that have pledged support to master content in Dolby Vision for home distribution include
Universal, Warner Brothers, Sony Pictures, and MGM. Content providers that have agreed to distribute
streaming Dolby Vision content include Netflix, Vudu, and Amazon. If you want to watch Dolby Vision
content on television at home, consumer television manufacturers LG, TCL, Vizio, HiSense, Sony,
Toshiba, and Bang & Olfusen have all shipped models with Dolby Vision support.
Organizing Your Timeline for Dolby Vision Mastering
One of the first things you need to do before doing a Dolby Vision grade is to organize your timeline
accordingly. Because each clip undergoes a visual analysis to facilitate the Dolby Vision workflow,
there are specific limitations to how clips can appear in a timeline.
```
 All clips to be analyzed in a Dolby Vision workflow need to be on video track V1; clips on other
```
tracks will be ignored.
 All clips that overlap one another as part of a composite must be turned into a single item in
the timeline in order to be correctly analyzed. This means that each group of clips that create
a composite in a timeline, be it multiple overlapping clips combined via keys or alpha channel
transparency, multiple overlapping clips combined using composite or blend modes, or text
generators appearing above one or more video clips, must be turned into a compound clip for
Dolby Vision analysis to work correctly.
Letterboxing for Dolby Vision Mastering
The analysis of clips in a Dolby Vision workflow keeps track of the timeline aspect ratio, as well as the
image aspect ratio of each clip in that timeline. Programs that mix different aspect ratios of letterboxing
```
(or blanking) will be accommodated by the Dolby Vision analysis, however Dolby Vision does not
```
```
support letterbox on two sides (both pillarbox and letterbox), only one at a time.
```
Setting Up Color Management for Dolby Vision Mastering
For an HDR signal to look correct, you need to output your graded program using the right EOTF for
the HDR standard you’re mastering. The EOTF maps the different levels DaVinci Resolve outputs to
your HDR display using the SMPTE ST.2084 PQ setting required for outputting Dolby Vision. You can
set this up in one of three different ways, as:
 Output Color Space and Gamma settings in RCM or ACES
 Color Space and Gamma settings within a series of Resolve FX Color Transform plugins that can
be used at the end of each grade or at the end of a Timeline grade
 3D LUTs used for converting signals from one standard to another that can be used at the end of
each grade or at the end of a Timeline grade
While Dolby Vision content is not limited to a particular color space, Resolve Color Management
provides a P3 D65 setting that matches the capabilities of most mastering displays in use at the time of
this writing.
260Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
Choosing Mastering Displays for Dolby Vision
To do HDR grading, you need a suitable HDR display. Technically any monitor that supports SMPTE
```
ST.2084 (aka PQ) will work. Happily, a growing number of professional displays from Sony, Flanders
```
Scientific, TV-Logic, Canon, and Eizo are suitable for use in HDR grading suites. EBU Tech 3320
specifies the requirements for a Grade 1 HDR mastering monitor. Dolby recommends the following
minimum requirements for HDR monitors:
 A minimum Peak Luminance of 1000 nits
 A 200,000:1 contrast ratio
 Minimum black at 0.005 nits
 Capable of at least 99% of P3 gamut
For more information on Dolby best practices for color grading Dolby Vision, visit:
```
https://www.dolby.com/us/en/technologies/dolby-vision/dolby-vision-for-creative-
```
professionals.html.
```
Using the Dolby Vision Internal Content Mapping Unit (iCMU)
```
```
DaVinci Resolve has a GPU-accelerated “internal” software version of the Dolby Vision CMU (Content
```
```
Mapping Unit) for previewing Dolby Vision mapping right in DaVinci Resolve. iCMU support can be
```
enabled and set up in the Color Management panel of the Project Settings by turning on the Enable
Dolby Vision checkbox. This is a DaVinci Resolve Studio-only feature.
Dolby Vision settings in the Color Management panel of the Project Settings
The Dolby Vision group of settings also exposes menus for choosing the version of Dolby Vision you
want to use, the type of analysis and what kind of Master Display you’re using, and whether or not
```
to use an eCMU (assuming you possess the option). In addition, there are options to enable HDMI
```
```
tunneling (as described below). Finally, turning Dolby Vision on also enables the Dolby Vision palette
```
and controls in the Color page, which are described in greater detail later in this chapter.
To master with Dolby Vision in DaVinci Resolve using the built-in iCMU, you still need a more
specific hardware setup than the average grading and finishing workstation, consisting of the
following equipment:
 Your DaVinci Resolve grading workstation using a DeckLink 8K Pro or DeckLink 4K Extreme 12G
video interface.
 A mastering display capable of outputting HDR nit levels suitable for the deliverable you’re
required to produce
261Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
Simultaneous Master and Target
Display Output for Dolby Vision
When mastering HDR and trimming versions for more limited displays, it’s extremely useful to be able
to evaluate your HDR grade and SDR trim pass side-by-side. It’s possible to output both the Master
Display output and the Target Display output simultaneously when you’re grading with either Dolby
Vision or HDR10+ enabled.
Necessary Hardware
To work in this manner, you must have the following equipment:
 Your DaVinci Resolve grading workstation must output via a DeckLink 8K Pro via the attached
HDMI card. This will pass the Dolby Vision metadata through to the SDR display, so you will see
the SDR out from the HDR grade.
 Your Mastering Display must be capable of HDR nit levels suitable for the deliverable you’re
required to produce.
 A display that can be set to output calibrated SDR, probably using the BT.709 gamut
Enabling Simultaneous Monitoring
When you set up your display hardware, the HDR Master Display must be connected to output A,
and the Target Display must be connected to output B of whichever BMD video output device you’re
using. Then, you need to turn on the “Use dual outputs on SDI” checkbox in the Master Settings of
the Project Settings. At this point, assuming all of your connections are compatible with one another,
you should see an HDR image output to your HDR display, and a trimmed image output to your
SDR display.
HDMI Tunneling using DeckLink 8K Pro G2
HDMI Tunneling allows you to preview Dolby Vision content directly on a consumer display in real
time. The variables involved in display type and manufacturer all have their own processing behaviors,
so HDMI tunneling is not for reference grading but more of letting you get an idea of what the
audience will be seeing at home for QC purposes.
Performing HDMI tunneling in DaVinci Resolve is possible using lower cost Blackmagic DeckLink cards
instead of Dolby’s dedicated eCMU hardware. Currently, the only DeckLink card that supports Dolby
Vision HDMI tunneling is the DeckLink 8K Pro G2.
Setting up Dolby Vision HDMI Tunneling in DaVinci Resolve:
1 In Preferences > System > Video and Audio I/O, make sure that both the Capture Device and
Monitor Device are set to the DeckLink 8K Pro.
2 In Project Settings > Master Settings > Video Monitoring, set the following parameters:
 Use 4:4:4 SDI: Check this box.
 Video bit depth: Set this value to 12 bit.
 Enable HDR metadata: Check this box.
262Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
The Project settings in Video Monitoring to enable Dolby Vision HDMI tunneling
3 In Project Settings > Color Management > Dolby Vision, set the following parameters:
 Enable Dolby Vision: Check this box.
 Enable Dolby Vision HDMI tunneling: Check this box.
 Enable L5 metadata on HDMI: Check this box.
The Project settings in Dolby Vision to enable HDMI tunneling
4 In the Color page, in the Dolby Vision palette, make sure that the Enable Tone Mapping Preview is
```
disabled (the box is not checked). HDMI tunneling will not work if this box is checked.
```
Disable the Enable Tone Mapping Preview box
in the Dolby Vision palette in the Color page
263Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
For more information on Dolby Vision HDMI tunneling go to Dolby’s website:
```
https://professionalsupport.dolby.com/s/article/HDMI-Tunneling?language=en_US
```
```
External Content Mapping Unit (eCMU) for Dolby Vision
```
```
DaVinci Resolve supports the use of a Dolby External Content Mapping Unit (eCMU) for studios doing
```
more intensive HDR mastering work, as it lets you monitor and adjust an HDR display simultaneously
to an SDR display for side-by-side trimming at high resolutions via hardware. The eCMU also has the
ability to preview Dolby Vision on a consumer display in real time via HDMI tunneling to view directly
what the audience will see at home.
Auto Analysis is Available to All Studio Users
Resolve Studio enables either unlicensed or licensed users to automatically analyze the image and
generate Dolby Vision analysis metadata. This metadata is used to deliver Dolby Vision content and
to render other HDR and SDR deliverables from the HDR grade that you’ve made. This enables any
DaVinci Resolve Studio user to create Dolby Vision deliverables with Level 1 metadata. However,
manual trimming of the analysis metadata requires a license from Dolby.
The commands governing Dolby Vision auto-analysis, which are available to all Resolve Studio
users, are available in the Color > Dolby Vision™ submenu, as well as the Dolby Vision palette,
and consist of the following:
• Analyze All Shots: Automatically analyzes each clip in the Timeline and stores
the results individually.
```
• Analyze Selected Shot(s): Only analyzes selected shots in the Timeline.
```
• Analyze Selected And Blend: Analyzes multiple selected shots as if they were a single
sequence. The result is the same analysis being saved to each clip. Useful to save time
when analyzing multiple clips that have identical content.
• Analyze Current Frame: A fast way to analyze clips where a single frame is representative
of the entire shot.
Once you analyze a clip, the Min, Max, and Average fields automatically populate with the
```
resulting L1 data; these fields are not editable.
```
The metadata fields for each clip
Additionally, clips that have been analyzed show an HDR badge in the Thumbnail timeline,
to help you keep track of which clips have been analyzed and which have yet to be.
Analyzed clips have HDR badges to identify them
264Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
Licensing DaVinci Resolve to Expose Dolby Vision Trim Controls
To expose the Dolby Vision controls in DaVinci Resolve Studio that let you make manual trims
on top of the automatic analysis that any copy of DaVinci Resolve Studio can do, you must email
dolbyvisionmastering@dolby.com to receive more information about obtaining a license.
Once you’ve obtained a license file from Dolby, you can import it by choosing File > Dolby Vision >
Load License, and its successful installation will enable the Dolby Vision controls to be enabled in
the Color page. You should also receive a display configuration file, which can be loaded via the File
> Dolby Vision > Load Configuration command and lets you populate the Dolby Vision drop-down
menus with the most up to date options.
Dolby Vision® Trim Controls in DaVinci Resolve
Once you’ve analyzed a clip, you’re in a position to trim the result. The latest version of the
Dolby Vision palette exposes four sets of controls. The first are the main controls:
 Target Display Output: This drop-down specifies what Dolby refers to as the Target Display, used
to display the tone mapped image. This menu lets you choose specific display properties to obtain
a preview of what the trimmed image will look like on different displays with different gamuts
and peak luminance capabilities. You can link the Target Display Output and the Trim Controls
For fields by clicking on the little chain icon directly to the left of the options. This automatically
changes the Trim Controls For field to the same value you set in the Target Display Output,
ensuring your trim controls are always right for the selected display.
 Trim Controls for: Which Target Display you’re currently trimming for. The default setting
```
(100-nit, BT.709, BT.1886, Full) lets you monitor an SDR version of the HDR image, so you can see
```
how the trim metadata tone maps the image on non-HDR televisions.
 Analyze controls: The commands governing Dolby Vision auto-analysis are available as buttons,
which perform the same functions as their similarly named counterparts in the Color > Dolby Vision
submenu. Please note that most trim controls are disabled until you perform an analysis, which is a
necessary first step.
```
All: Automatically analyzes each clip in the current Timeline and stores the results individually.
```
```
Selected: Only analyzes selected shots in the Timeline.
```
```
Blend: Analyzes multiple selected shots as if they were a single sequence. The result is the same
```
analysis being saved to each clip. You need to use the blend option when analyzing two clips that
meet at a through edit separating otherwise contiguous frames. It’s also typical to use the Blend
option when analyzing a scene of clips that take place at the same location at the same time, to
ensure that natural variations in lighting don’t add unwanted variations between the analyses of
clips that are supposed to already be balanced with one another. Blend also saves time when
analyzing multiple clips that have identical content.
```
Frame: Useful in situations where part of a clip has an extreme level of color or lightness that’s
```
not typical of the rest of the clip, that incorrectly biases the analysis and produces a poor result.
Placing the playhead on a frame that’s representative of how the clip is supposed to look and
using the Frame option bases the analysis on only that frame. This is also a fast way to analyze
clips where a single frame is representative of the entire shot.
 Enable Tone Mapping Preview: Lets you see the target display output in the Color page Viewer
and video output, so you can evaluate how the tone mapped version looks on your HDR display.
This control is disabled when you enable “Use dual-outputs on SDI” in the Master Settings of the
Project Settings, since the second output SDI now automatically displays the target display output.
```
 Mid Tone Offset (CM v4.0 only): This control is used to match the overall exposure between the
```
tone mapped SDR signal to the HDR master. This offset is applied to the L1 Mid values, allowing
the adjustment of mid tones without affecting the blacks and highlights. It can be used to shift
265Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
overall L1 analysis to ensure the best preservation of artistic intent. This setting is shared among all
trim passes you do at all nit levels, so if you’ve done two trim passes, one at 100 nits and another
at 1000 nits, adjusting this setting always adjusts both trim passes at once. Changes made to this
control are recorded to the L3 metadata for each clip.
The second are the Min, Mid, and Max metadata fields that are populated by the analyzed values
of the current clip. These fields cannot be edited, although analysis metadata can be copied and
pasted among clips. These values represent the L1 analysis and are used to calculate how the
HDR image should be trimmed to fit into the video standard specified by the Target Display.
The third are the Primary Trims, which are only editable if you’ve performed an analysis and if you
have a license from Dolby. Which controls are exposed depends on the version of Dolby Vision
you’ve selected in the Color Management panel of the Project Settings.
Dolby Vision CM v2.9 Controls
If you choose Dolby Vision 2.9 in the Color Management panel of the Project Settings, it activates the
2.9 version of Dolby’s content mapping algorithm and exposes the original Dolby Vision trim controls.
It is no longer suggested to use these, since you can do a Dolby Vision 4.0 analysis and trim, and still
export converted 2.9 metadata for legacy workflows.
 Lift/Gamma/Gain: These controls function similarly to the Y-only Lift, Gamma, and Gain master
wheels of the Color Wheels palette, to let you trim the overall contrast levels of the image. The
Dolby Best Practices Guide recommends to limit positive Lift to no more than 0.025, and mostly
restrict yourself to using Gamma and Gain if necessary to lighten the image.
 Saturation Gain: Lets you trim the saturation of the most highly saturated areas within a scene.
Lesser saturated values will be less affected.
 Chroma Weight: Darkens saturated parts of the image to preserve colorfulness in areas of
the image that are clipped by smaller gamuts that don’t have enough headroom for saturation
in the highlights.
 Tone Detail: Lets you preserve contrast detail in the highlights that might otherwise be lost when
the highlights are mapped to lower dynamic ranges, usually due to clipping. Increasing Tone Detail
Weight increases the amount of highlight detail that’s preserved. When used, can have the effect
of sharpening highlight detail.
Dolby Vision CM v4.0 Controls
If you choose Dolby Vision 4.0 in the Color Management panel of the Project Settings, it activates the
4.0 version of Dolby’s content mapping algorithm, and exposes the following controls.
 Lift/Gamma/Gain: These controls function similarly to the Y-only Lift, Gamma, and Gain master
wheels of the Color Wheels palette, to let you trim the overall contrast levels of the image. The
Dolby Best Practices Guide recommends to limit positive Lift to no more than 0.025, and mostly
restrict yourself to using Gamma and Gain if necessary to lighten the image.
 Saturation Gain: Lets you trim the saturation of the most highly saturated areas within a scene.
Lesser saturated values will be less affected.
 Chroma Weight: Darkens saturated parts of the image to preserve colorfulness in areas of
the image that are clipped by smaller gamuts that don’t have enough headroom for saturation
in the highlights.
 Tone Detail: Lets you preserve contrast detail in the highlights that might otherwise be lost when
the highlights are mapped to lower dynamic ranges, usually due to clipping. Increasing Tone Detail
Weight increases the amount of highlight detail that’s preserved. When used, can have the effect
of sharpening highlight detail.
 Mid Contrast Bias: Affects image contrast in the region around the computed average picture
level. This lets you increase or decrease contrast in the midtones of the image.
266Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
 Highlight Clipping: Reduces details and affects the roll-off the brighter part of the image by
clipping the highlights as required. This is useful when the tone mapped image is displaying
unwanted details.
The Primary Trims controls that are found in the Dolby Vision palette are only enabled
once you’ve authorized your system with a special license, available from Dolby.
The fourth set of controls is available via a second palette mode, the Secondary Trims. These are only
editable if you’ve performed an analysis and if you have a license from Dolby.
```
 Secondary Saturations: A set of slider-based vector-style controls (similar to the Hue vs. Sat
```
```
curve) lets you adjust the Saturation of Red, Yellow, Green, Cyan, Blue, and Magenta to help you
```
selectively fine tune the results.
```
 Secondary Hues: Another set of slider-based vector-style controls (similar to the Hue vs.
```
```
Hue≈controls) lets you adjust the Hue of Red, Yellow, Green, Cyan, Blue, and Magenta to help you
```
fine tune the results.
The Secondary Trims controls, as seen on a licensed Dolby Vision system
Together, all of this trimming metadata lets the colorist guide how the iCMU or eCMU transforms
the image from the Mastering Display specified in the Project Settings to the Target Display
specified in the Dolby Vision palette. This metadata is carried throughout the ecosystem so that
your artistic intent is preserved on a variety of platforms and displays.
267Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
Previewing and Trimming At Different Levels
Additionally, the iCMU or eCMU can be used to preview 100 nit, 600 nit, 1000 nit, and 2000 nit versions of
your program, with different gamuts, if you want to see how your master will scale to those combinations
of peak luminance levels and standards. This, of course, requires your DaVinci Resolve workstation or
eCMU to be connected to a display that’s capable of being set to those peak luminance output levels.
Though it’s not at all typical, you also have the option to set the “Trim Controls For” drop-down menu
to different combinations of peak luminance, gamut, and color temperature, in order to visually trim
the grades of your program at up to four different peak luminance levels, including 100 nit, 600 nit,
1000 nit, and 2000 nit reference points. Choosing a setting from the “Trim Controls For” drop-down
menu sets you up to adjust trim metadata for that setting.
Choosing different settings from the “Trim Controls For” drop-down menu lets you can optimize a
program’s visuals for the peak luminance and color volume performance of many different televisions
with a much finer degree of control. If you take this extra step of doing a complete trim pass of your
```
program at multiple nit levels (using the Dolby Vision controls), the Level 2, or Level 8 metadata you
```
generate in each trim pass ensures that the artistic intent is preserved as closely as possible across a
wide variety of displays, in an attempt to provide the viewer with the best possible representation of
the director’s intent, no matter where it appears.
For example, if a program were graded relative to a 4000 nit display, along with a single
100 nit BT.709 trim pass, then a Dolby Vision-compatible television with 750 nit peak output
will reference the 100 nit trim pass metadata in order to come up with the best way of “splitting
the difference” to output the signal correctly. On the other hand, were the colorist to do three
trim passes, the first at 100 nits, -cond at 600 nits, and a third at 1000 nits, then a 750 nit-
capable Dolby Vision television would be able to use the 600 and 1000 nit trim metadata
to output more accurately scaled color volume and HDR-strength highlights, relative to the
colorist’s adjustments, that take better advantage of the 750 nit output of that television.
Managing Dolby Vision Metadata
As you go through the process of analyzing and trimming the HDR grades displayed on your Master
Display to look appropriate on your Target Display, you’ll sometimes find it useful to copy and paste
metadata from one clip to another. You can copy and paste Analysis Metadata separately from Trim
Metadata and Mid Tone Offset, and you can choose to copy and paste metadata for all Target Displays
when you’re trimming multiple passes, or you can copy and paste metadata for only the current Target
Display if you’re trimming multiple passes and you only want to overwrite metadata for a single pass.
Methods of Copying and Pasting Dolby Vision Metadata:
To copy and paste Analysis Metadata: Select a clip you want to copy from, choose Copy Analysis
Metadata from the Dolby Vision palette option menu, then select a clip you want to paste to, and
choose Paste Analysis Metadata from the Dolby Vision palette option menu.
To copy and paste Trim Metadata for all Target Displays: Do one of the following:
 Select a clip you want to copy from, choose Edit > Dolby Vision > Copy Trim Metadata, then select
a clip you want to paste to, and choose Edit > Dolby Vision > Paste Trim Metadata.
 Select a clip you want to copy from, choose Copy Trim Metadata from the Dolby Vision palette
option menu, then select a clip you want to paste to, and choose Paste Trim Metadata from the
Dolby Vision palette option menu.
 Select a clip you want to paste to, then press and hold the Option-Shift keys, and middle-click the
clip you want to copy from.
268Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
To copy and paste Trim Metadata for the current Target Display: Do one of the following:
 Select a clip you want to copy from, choose Copy Trim Metadata from the Dolby Vision palette
option menu, then select a clip you want to paste to, and choose Paste Trim Metadata to Current
from the Dolby Vision palette option menu.
 Select a clip you want to paste to, then press and hold the Option key, and middle-click the clip
you want to copy from.
To copy and paste Mid Tone Offset: Select a clip you want to copy from, choose Copy Mid Tone
Offset from the Dolby Vision palette option menu, then select a clip you want to paste to, and choose
Paste Mid Tone Offset from the Dolby Vision palette option menu.
Setting Up Resolve Color Management for Grading HDR
Once the hardware is set up, setting up Resolve itself to output HDR for Dolby Vision mastering is easy
```
using Resolve Color Management (RCM). This procedure is pretty much the same no matter which
```
```
HDR mastering technology you’re using; only specific Output Color Space settings will differ.
```
1 Set Color Science to DaVinci YRGB Color Managed in the Color Management panel of the
Project Settings.
2 Then, open the Color Management panel, and set the Output Color Space drop-down to the
ST.2084 setting that corresponds to the peak luminance, in nits, of the grading display you’re
using. For example, if you’re grading with a Sony BVM X300, choose ST.2084 1000 nit, but if
you’re grading with a Flanders Scientific XM310K, choose ST.2084 3000 nit, in order to use the full
capabilities of each display. Be aware that whichever HDR setting you choose will impose a hard
clip at the maximum nit value supported by that setting. This is to prevent accidentally overdriving
```
HDR displays for which there are negative consequences (not all HDR displays have this limitation).
```
 ST.2084 300 nit
 ST.2084 500 nit
 ST.2084 800 nit
 ST.2084 1000 nit
 ST.2084 2000 nit
 ST.2084 3000 nit
 ST.2084 4000 nit
```
This setting is only the output EOTF (a sort of gamma transform, if you will, using the terminology
```
```
that DaVinci Resolve’s UI has used up until now).
```
3 Next, choose a setting in the Timeline Color Space that corresponds to the gamut you want
to use for grading, and that will be output. For example, if you want to grade the Timeline as
a log-encoded signal and “normalize” it yourself, you can choose ARRI Log C or Cineon Film
```
Log (this workflow is highly recommended for the best results). If you would rather save time by
```
having DaVinci Resolve normalize the Timeline to P3-D65 and grade that way, you can choose
that setting as well. In terms of defining the output gamut, the rule is that if “Use Separate Color
Space and Gamma” is turned off, the Timeline Color Space setting will define your output gamut.
If “Use Separate Color Space and Gamma” is turned on, then you can specify whatever gamut you
want in the left Output Color Space drop-down menu, and choose the EOTF from the right drop-
```
down menu (as described in step 2).
```
269Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
4 Be aware that, when it’s being properly output, HDR ST.2084 signals appear very “log-like,” in
order to pack a wide dynamic range into the bandwidth of a standard video signal. It’s the HDR
display itself that “normalizes” this log-encoded image to look as it should. For this reason, the
image you see in your Color page Viewer is going to appear flat and log-like, even though the
image being displayed on your HDR reference display looks vivid and correct. If you’re using a
typical SDR computer display, and you want to make the image in the Color Page Viewer look
```
“normalized” at the expense of clipping the HDR highlights (in the Viewer, not in the grade), you
```
can use the 3D Color Viewer Lookup Table setting in the Color Management panel of the Project
Settings to assign the appropriate ST.2084 setting with a peak nit level that corresponds to the
HDR broadcast display you’re outputting to.
```
5 Additionally, the “Timeline resolution” and “Pixel aspect ratio” (in the project settings) that your
```
project is set to use is saved to the Dolby Vision metadata, so make sure your project is set to the
final Timeline resolution and PAR before you begin grading.
DaVinci Resolve Grading Workflow For Dolby Vision
Once the hardware and software is all set up, you’re ready to begin grading HDR. The workflow is
fairly straightforward.
1 First, grade the HDR image on your HDR Monitor to look as you want it to. Dolby recommends
starting by setting the look of the HDR image, to set the overall intention for the grade.
2 When using various grading controls in the Color page to grade HDR images, you may find it
useful to enable the HDR Mode of the node you’re working on by right-clicking that node in
the Node Editor and choosing HDR Mode from the contextual menu. This setting adapts that
node’s controls to work within an expanded HDR range. Practically speaking, this makes controls
that operate by letting you make adjustments at different tonal ranges, such as Custom Curves,
Soft Clip, and so on, work more easily with wide-latitude signals.
3 When you’re happy with the HDR grade, click the Analysis button in the Dolby Vision palette.
This analyzes every pixel of every frame of the current shot, and performs and stores a statistical
analysis that is sent to the iCMU or eCMU to guide its automatic conversion of the HDR signal to
an SDR signal.
4 Choose “Target Display Output” and “Trim Controls For” settings that you want to trim to.
By default, these are set to “100-nit, BT.709, BT.1886, Full,” which is a typical SDR deliverable.
However, other options are available if you want to do multiple trim passes to obtain a more
accurate result. Whichever setting you choose from, “Trim Controls For” dictates which trim pass
you’re doing. You can do multiple trim passes by choosing another option from this menu.
5 If you’re not happy with the automatic conversion, use the trim controls in the Dolby Vision palette
to manually trim the result to the best possible BT.709 approximation of the HDR grade you
created in step 1.
6 If you obtain a good result, then move on to the next shot and continue work. If you cannot obtain a
good result, and worry that you may have gone too far with your HDR grade to derive an acceptable
SDR tone mapping, you can always trim the HDR grade a bit, and then retrim the SDR grade to try
and achieve a better tone mapping. Dolby recommends that if you make significant changes to the
HDR master, particularly if you modify the blacks or the peak highlights, you should reanalyze the
scene. However, if you only make small changes, then reanalyzing is not strictly required.
As you can see, the general idea promoted by Dolby is that a colorist will focus on grading the
HDR picture relative to the 1000, 2000, 4000, or higher nit display that is being used, and will then
rely on the colorist to use the Dolby Vision controls to “trim” this into a 100 nit SDR version. This
metadata is saved as part of the mastered media, and it’s used to more intelligently tone map the
entire image to fit within any given display’s parameters. The colorist’s artistic intent is used to guide
all dynamic adjustments to the content.
270Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
Delivering Dolby Vision
Once you’re finished grading the HDR and trimming the SDR tone mapping, you need to output your
program correctly in the Deliver page.
Rendering a Dolby Vision Master
To deliver a Dolby Vision master after you’ve finished grading, you want make sure that the Output
Color Space of the Color Management panel of the Project Settings is set to the appropriate HDR
```
ST.2084 setting based on the peak output you want to deliver (any values above will be clipped).
```
Then, you want to set your render up to use one of the following Format/Codec combinations:
 TIFF, RGB 16-bit
```
 EXR, RBG-half (no compression)
```
When you render for tapeless delivery, all Dolby Vision metadata is recorded into a Dolby Vision XML
and delivered along side either the Tiffs or EXR renders. To export a Dolby Vision XML file, select
your timeline in the media pool and choose File > Export >Timeline. Navigate to where you want to
```
save the file and select Dolby Vision v2.9 (or v4.0) MXF files from the file type selector and click save.
```
These two sets of files are then delivered to a facility that’s capable of creating the Dolby Vision
deliverable file.
Rendering a Dolby Vision IMF
You can deliver directly to an IMF that includes an MXF with embedded Dolby Vision metadata in the
package. To export a Dolby Vision IMF use the following Video settings in the Deliver page:
 Format: IMF
 Codec: Kakadu JPEG 2000
```
 Type: Dolby Vision (HD, 2K, UHD, or 4K) depending on your deliverable resolution.
```
Configure the rest of the IMF settings as necessary for your project.
The Video settings to use for creating a Dolby
Vision IMF in the Deliver page
Rendering a Dolby Vision H.265 file
You can deliver directly to a Dolby Vision compatible H.265 file, which allows you to playback video
that triggers playback in the Dolby Vision mode on your television or computer screen. To export a
Dolby Vision H.265 file, use the following Video settings in the Deliver page:
 Format: MP4 or QuickTime
 Codec: H.265
 Dolby Vision Profile: Set the Dolby Vision profile you wish to use, or None to select the
Tone Mapping manually.
271Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
 Tone Mapping: Choose None for no tone mapping, or Dolby Vision to expose a list of common
deliverables to tone map to.
Configure the rest of the H.265 settings as necessary for your project.
The Dolby Vision Profile and Tone Mapping settings in
the H.265 Video section of the Deliver page
Rendering an Ordinary SDR Media File or Other Specific HDR Trim Pass
If you want to export the SDR trim pass, then you can choose Dolby Vision from the Tone Mapping
drop-down menu in the Advanced Settings of the Render Settings list on the Deliver page, and
choose the 100-nit, BT.709, BT.1886, Full setting below. With this enabled, you can output the SDR
version of your program to any format you like.
You can also export the trims for other HDR nit levels for specific displays, at 600, 1000 or 2000 nits
and in the either the BT.2020 or P3 gamuts.
The Tone Mapping setting in the Advanced Settings of the Render Settings list
SMPTE ST.2084 and HDR10
Many display manufacturers who have no interest in licensing Dolby Vision for inclusion in their
displays are instead going with the simpler method of engineering their displays to be compatible with
SMPTE ST.2084. It requires only a single stream for distribution, there are no licensing fees, no special
```
hardware is required to master for it (other than an HDR mastering display), and there’s no special
```
metadata to write or deal with.
Interestingly, SMPTE ST.2084 ratifies the “PQ” EOTF that was originally developed by Dolby, and
which is used by Dolby Vision, into a general standard that accommodates encoding HDR at peak
luminance values up to 10,000 cd/m 2 . This standard requires at minimum a 10-bit signal for distribution,
and the EOTF is mathematically described such that the video signal utilizes the available code
values of a 10-bit signal as efficiently as possible, while allowing for such a wide range of luminance in
the image.
SMPTE ST.2084 is also part of the “Ultra HD Premium” industry specification, which stipulates that
televisions bearing the Ultra HD Premium logo have the following capabilities:
 A minimum UHD resolution of 3840 x 2160
 A minimum gamut of 90% of P3
```
 A minimum dynamic range of either 0.05 nits black to 1000 nits peak luminance (to accommodate
```
```
LCD displays), or 0.0005 nits black to 540 nits peak luminance (to accommodate OLED displays)
```
 Compatibility with SMPTE ST.2084
272Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
Finally, ST.2084 has been included in the HDR 10 standard adopted by the Blu-ray Disc Association
```
(BDA) that covers Ultra HD Blu-ray. HDR 10 stipulates that Ultra HD Blu-ray discs have the following
```
```
characteristics:
```
 UHD resolution of 3840 x 2160
 Up to the Rec. 2020 gamut
 SMPTE ST.2084
 Mastered with a peak luminance of 1000 nits
The downside is that, by itself, an HDR10 mastered program is not backward compatible with BT.709
```
displays using BT.1886 (although the emerging HDR10+ standard described later addresses this).
```
Furthermore, no provision is made to scale the above-100 nit portion of the image to accommodate
different displays with differing peak luminance levels. For example, if you grade and master an image
to have peak luminance of 4000 nits, and you play that signal on an HDR10-compatible television
```
(using ST.2084) that’s only capable of 800 nits, then everything above 800 nits will be clipped, while
```
everything below 800 nits will look exactly as it should relative to your grade.
This is because ST.2084 is referenced to absolute luminance. If you grade an HDR image
referencing a 1000 nit peak luminance display, as is recommended by HDR10, then any display using
ST.2084 will respect and reproduce all levels from the HDR signal that it’s capable of reproducing
as you graded them, up to the maximum peak luminance level it can reproduce. For example, on an
HDR10-compatible television capable of outputting 500 nits, all mastered levels from 501–1000 will be
clipped, as seen in the screenshot below.
Comparing the original 1000 nit waveform representing the grading monitor
to a 500 nit clipped waveform representing the consumer television
273Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
How much of a problem this is really depends on how you choose to grade your HDR-
strength highlights. If you’re only raising the most extreme peak highlights to maximum HDR-
strength levels, then it’s entirely possible that the audience might not notice that the display
is only outputting 800 nits worth of signal and clipping any image details from 801–1000
nits because there weren’t that many details above 800 anyway. Or, if you’re grading large
explosive fireballs up above 800 nits in their entirety because it looks cool, then maybe the
audience will notice. The bottom line is, when you’re grading for displays that are only capable
of ST.2084, you need to think about these sorts of things.
Monitoring and Grading to ST.2084 in DaVinci Resolve
Monitoring an ST.2084 image is as simple as obtaining a ST.2084-compatible HDR display and
connecting it to the output of your DeckLink 8K, DeckLink 4K Extreme 12G, or UltraStudio 4K Extreme.
Setting up Resolve Color Management to grade for ST.2084 is identical to setting up to grade for
Dolby Vision. You’ll also monitor the video scopes identically, and output a master identically, given
that both standards rely upon the same PQ curve.
```
TIP: If you’re monitoring with the built-in video scopes in DaVInci Resolve, you can turn
```
```
on “HDR (ST.2084/HLG)” in the Waveform Scale Style settings in the Scopes option menu,
```
which will replace the 10-bit scale of the video scopes with a scale based on nit values
```
(cd/m2 ) instead.
```
Connecting to HDR-Capable Displays using HDMI 2.0a
If you have a DeckLink 4K Extreme 12G or an UltraStudio 4K Extreme video interface, then DaVinci
Resolve 12.5 and above can output the metadata necessary to correctly display HDR video signals to
display devices using HDMI 2.0a when you turn on the “Enable HDR metadata over HDMI” checkbox
in the Master Settings panel of the Project Settings.
The Enable HDR metadata over HDMI option in
the Master Settings panel of the Project Settings
lets you output HDR via HDMI 2.0a
When you do so, a setting in the Color Management panel of the Project Settings, “HDR mastering
is for X” lets you specify the output, in nits, to be inserted as metadata into the HDMI stream being
output, so that the display you’re connecting to correctly interprets it. The output you specify should
match what your display is expecting.
The “HDR mastering is for” setting lets you insert
metadata for HDR output via HDMI 2.0a
274Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
HDR10+™
DaVinci Resolve supports the new HDR10+ HDR format by Samsung. Please note that this support is
a work in progress as this is a new standard. When enabled, an HDR10+ palette shows the results of
the trimming analysis that make an automated downconversion of HDR to SDR, creating metadata to
control how HDR-strength highlights look on a variety of supported televisions and displays. This is
enabled and set up in the Color Management panel of the Project Settings with the Enable HDR10+
checkbox. Turning HDR10+ on enables the HDR 10+ palette in the Color page.
HDR 10+ settings in the Color Management panel of the Project Settings
Monitoring and Grading to ST.2084 for HDR10+
When you’re grading a program for HDR10+ output, you’ll need to monitor an ST.2084 image, which
is as simple as obtaining a ST.2084-compatible HDR display and connecting it to the output of your
DeckLink 8K, DeckLink 4K Extreme 12G, or UltraStudio 4K Extreme.
Setting up Resolve Color Management to grade for ST.2084 is identical to setting up to grade for
Dolby Vision or regular HDR10. You’ll also monitor the video scopes identically, and output a master
identically, given that each of these standards rely upon the same PQ curve.
```
TIP: If you’re monitoring with the built-in video scopes in DaVinci Resolve, you can turn
```
```
on “HDR (ST.2084/HLG)” in the Waveform Scale Style settings in the Scopes option menu,
```
which will replace the 10-bit scale of the video scopes with a scale based on nit values
```
(cd/m2 ) instead.
```
HDR10+ Grading Workflow
The idea behind the HDR10+ workflow is that you’ll grade the HDR version of each clip in your
program first, and then use the automatic analysis to create a downconverted tone mapped version
of each shot that’s controlled by metadata. Once the HDR10+ trim pass is complete, you’ll deliver the
rendered HDR output along with a set of HDR10+ JSON metadata files to a facility for final mastering.
Simultaneous Master and Target Display Output for HDR10+
When mastering HDR and trimming versions for more limited displays, it’s extremely useful to be able
to evaluate your HDR grade and tone mapped trim pass side by side. Starting in DaVinci Resolve 15,
it’s possible to output both the Master Display output and the Target Display output simultaneously
when you’re grading with either Dolby Vision or HDR10+ enabled.
275Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
Necessary Hardware
To work in this manner, you must have the following equipment:
 Your DaVinci Resolve grading workstation must output via a DeckLink 8K, DeckLink 4K
Extreme 12G, UltraStudio 4K Extreme video interface, or better.
 Your Mastering Display must be capable of HDR nit levels suitable for the deliverable you’re
required to produce.
 An HDR target display that can be set to the appropriate tone mapped output.
Enabling Simultaneous Monitoring
When you set up your display hardware, the HDR Master Display must be connected to output A,
and the Target Display must be connected to output B of whichever BMD video output device you’re
using. Then, you need to turn on the “Use dual outputs on SDI” checkbox in the Master Settings of the
Project Settings. At this point, assuming all of your connections are compatible with one another, you
should see an HDR image output to your HDR display and a trimmed image output to your SDR display.
HDR10+ Auto Analysis Commands
After you’ve graded an HDR version of each clip in your program, a set of HDR10+ specific commands
let you auto-analyze each clip to create custom HDR to SDR downconversion metadata that give you
a starting point for the SDR trim pass you need to do. These commands are available in the Color >
HDR10+ submenu:
Analyze All Shots: Automatically analyzes each clip in the Timeline and
stores the results individually.
```
Analyze Selected Shot(s): Only analyzes selected shots in the Timeline.
```
Analyze Selected and Blend: Analyzed multiple selected shots and averages the result,
which is saved to each clip. Useful to save time when analyzing multiple clips that have
identical content.
Analyze Current Frame: A fast way to analyze clips where a single frame is
representative of the entire shot.
Delivering HDR10+
Once you’re finished grading the HDR and trimming the SDR downconversion, you need to output
your program correctly in the Deliver page.
Rendering an HDR10+ Master
To deliver an HDR10+ master after you’ve finished grading, you want make sure that the Output Color
Space of the Color Management panel of the Project Settings is set to the appropriate HDR ST.2084
```
setting based on the peak output you want to deliver (any values above will be clipped). Then, you
```
want to set your render up to use the highest quality Format/Codec combination that can be delivered
to whomever is doing the final mastering.
The HDR10+ analysis and manual trim metadata you generated while trimming is saved per clip,
in a series of JSON sidecar files, which should then be exported by right-clicking that timeline in the
Media Pool, and choosing Timelines > Export > HDR10+JSON.
276Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
These two sets of files are then delivered to a facility that’s capable of creating an HDR10+ Mezzanine
```
File (this cannot be done in DaVinci Resolve).
```
```
NOTE: The HDR10+ mastering workflow is still a work in progress. More information will be
```
provided as it becomes available.
HDR Vivid
```
HDR Vivid is the HDR video technology standard released by the UHD World Association (UWA).
```
Mastering in this format assures wide compatibility with HDR televisions, phones, computers, and other
devices adhering to this standard.
HDR Vivid settings in the Color Management panel of the Project Settings
Monitoring and Grading to ST.2084 for HDR Vivid
When you’re grading a program for HD Vivid output, you’ll need to monitor an ST.2084 image, which
is as simple as obtaining a ST.2084-compatible HDR display and connecting it to the output of your
DeckLink 8K, DeckLink 4K Extreme 12G, or UltraStudio 4K Extreme.
Setting up Resolve Color Management to grade for ST.2084 is identical to setting up to grade for
Dolby Vision or regular HDR10. You’ll also monitor the video scopes identically, and output a master
identically, given that each of these standards rely upon the same PQ curve.
```
TIP: If you’re monitoring with the built-in video scopes in DaVinci Resolve, you can turn
```
```
on “HDR (ST.2084/HLG)” in the Waveform Scale Style settings in the Scopes option menu,
```
which will replace the 10-bit scale of the video scopes with a scale based on nit values
```
(cd/m2 ) instead.
```
HDR Vivid Grading Workflow
The idea behind the HDR Vivid workflow is that you’ll grade the HDR version of each clip in your
program first, and then use the automatic analysis to create a downconverted tone mapped version of
each shot that’s controlled by metadata. Once the HDR Vivid trim pass is complete, you’ll deliver the
rendered HDR output with embedded HDR Vivid metadata.
Simultaneous Master and Target Display Output for HDR Vivid
When mastering HDR and trimming versions for more limited displays, it’s extremely useful to be able
to evaluate your HDR grade and tone mapped trim pass side by side. Starting in DaVinci Resolve 15,
it’s possible to output both the Master Display output and the Target Display output simultaneously
when you’re grading with HDR Vivid enabled.
277Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
Necessary Hardware
To work in this manner, you must have the following equipment:
 Your DaVinci Resolve grading workstation must output via a DeckLink 8K, DeckLink 4K Extreme
12G, UltraStudio 4K Extreme video interface, or better.
 Your Mastering Display must be capable of HDR nit levels suitable for the deliverable you’re
required to produce.
 An HDR target display that can be set to the appropriate tone mapped output.
Enabling Simultaneous Monitoring
When you set up your display hardware, the HDR Master Display must be connected to output A,
and the Target Display must be connected to output B of whichever BMD video output device you’re
using. Then, you need to turn on the “Use dual outputs on SDI” checkbox in the Master Settings of
the Project Settings. At this point, assuming all of your connections are compatible with one another,
you should see an HDR image output to your HDR display and a trimmed image output to your
SDR display.
HDR Vivid Trim Controls in DaVinci Resolve
The latest version of the HDR Vivid palette exposes three sets of controls. The first are the
main controls:
 Target Display Output: This drop-down specifies what parameters are used to display the
tone mapped image. This menu lets you choose specific display properties to obtain a preview
of what the trimmed image will look like on different displays with different gamuts and peak
luminance capabilities.
 Trim Mode: Determines the toolset used to create the trims, either Curve or Statistical modes.
 Analyze controls: The commands governing HDR Vivid auto-analysis are available as buttons,
which perform the same functions as their similarly named counterparts in the Color > HDR Vivid
submenu. Please note that most trim controls are disabled until you perform an analysis, which is a
necessary first step.
```
All: Automatically analyzes each clip in the current Timeline and stores the results individually.
```
```
Selected: Only analyzes selected shots in the Timeline.
```
```
Frame: Useful in situations where part of a clip has an extreme level of color or lightness that’s
```
not typical of the rest of the clip, that incorrectly biases the analysis and produces a poor result.
Placing the playhead on a frame that’s representative of how the clip is supposed to look, and
using the Frame option, bases the analysis on only that frame. This is also a fast way to analyze
clips where a single frame is representative of the entire shot.
 Enable Tone Mapping Preview: Lets you see the target display output in the Color page Viewer
and video output, so you can evaluate how the tone mapped version looks on your HDR display.
 The next set of controls activate based on which Trim Mode you have selected.
 Curve: The Curve trim mode exposes a variety of controls that lets the colorist adjust the trim
metadata manually at the clip or frame level. Offset, Brightness, and Detail settings are available
for the Dark and Bright parts of the curve. Midtones have a brightness control. Highlight Crop
lets you bring any highlights back into range that may have exceeded the display’s maximum
brightness, thus blowing out. Separate Global and Highlight saturation settings are also possible.
 Statistical: The Statistical trim mode exposes controls that let you fine tune the automatic tone
mapping algorithm used in the Analyze step.
278Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
HDR Vivid controls in the Color page
Delivering HDR Vivid
Once you’re finished grading the HDR and trimming the SDR downconversion, you need to output
your program correctly in the Deliver page.
Rendering an HDR Vivid Master
To deliver an HDR Vivid master after you’ve finished grading, you want make sure that the Output
Color Space of the Color Management panel of the Project Settings is set to the appropriate HDR
```
ST.2084 setting based on the peak output you want to deliver (any values above will be clipped).
```
Then, you want to set your render up to export an H.265 codec in the Video Settings, check the
Embed HDR Vivid Metadata box, and select the appropriate HDR mode that you used to grade the
master in the drop-down box below.
HDR Vivid settings in the Video section of the Deliver page
```
Hybrid Log-Gamma (HLG)
```
The BBC and NHK jointly developed another method of encoding HDR video, referred to as Hybrid
```
Log-Gamma (HLG). The goal of HLG was to develop a method of mastering HDR video that would
```
support a range of displays of different peak luminance capabilities without additional metadata, that
could be broadcast via a single stream of data, that would fit into a 10-bit signal, and that in the words
of the ITU-R Draft Recommendation BT.HDR, “offers a degree of compatibility with legacy displays by
more closely matching the previous established television transfer curves.”
The basic idea is that the HLG EOTF functions very similarly to BT.1886 from 0 to 0.6 of the signal
```
(with a typical 0–1 range), while 0.6 to 1.0 smoothly segues into logarithmic encoding for the highlights.
```
This means that, if you just send an HDR Hybrid Log-Gamma signal to an SDR display, you’d be able
to see much of the image identically to the way it would appear on an HDR display, and the highlights
would be compressed to present an acceptable amount of detail for SDR broadcast.
279Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
```
On a Hybrid Log-Gamma compatible HDR display, however, the log-like highlights of the image (not
```
```
the BT.1886-like bottom portion of the signal, just the highlights) would be stretched back out, relative
```
to whatever peak luminance level a given HDR television is capable of outputting, to return the image
to its true HDR glory. This is different from the HDR10 method of distribution described previously, in
which the graded signal is referenced to absolute luminance levels dictated by ST.2084, and levels
that cannot be represented by a given display will be clipped.
And while this facility to support multiple HDR displays with differing peak luminance levels is
somewhat analogous to Dolby Vision’s ability to tailor HDR output to the unique peak luminance levels
of any given Dolby Vision-compatible television, HLG requires no additional metadata to guide how
```
the highlights are scaled, which depending on your point of view is either a benefit (less work), or a
```
```
deficiency (no artistic guidance to make sure the highlights are being scaled in the best possible way).
```
As is true for most things, you don’t get something for nothing. The BBC White Paper WHP 309 states
that, for a 2000 cd/m2 HDR display with a black level of 0.01 cd/m2 , up to 17.6 stops of dynamic range
```
without visible quantization artifacts (“banding”) is possible. BBC White Paper WHP 286 states that
```
the proposed HLG EOTF should support displays up to about 5000 nits. So, partially, the backward
compatibility that HLG makes possible is due in part to discarding long-term support for 10,000 nit
displays. However, it’s an open question whether or not over 5000 nits is even necessary for
consumer enjoyment.
Sony, LG, Panasonic, JVC, Phillips, Hisense, Hitachi, and Toshiba have all either announced or
are shipping consumer HDR televisions capable of displaying HLG encoded video, and of course
DaVinci Resolve supports this standard through Resolve Color Management.
Grading Hybrid Log-Gamma in DaVinci Resolve
Monitoring an ST.2084 image is as simple as getting a Hybrid Log-Gamma-compatible HDR display,
and connecting the output of your video interface to the input of the display.
Setting up Resolve Color Management to grade for HLG is identical to setting up to grade for Dolby
Vision, except that there are four HLG settings to choose from for the Output Color Space:
 Rec.709 HLG ARIB STD-B67
 Rec.2020 HLG ARIB STD-B67
 Rec.2100 HLG
```
 Rec.2100 HLG (Scene)
```
Optionally, if you choose to enable “Use Separate Color Space and Gamma,” you can choose either
Rec. 2020 or Rec. 709 as your gamut, and Rec. 2100 HLG as your EOTF.
The levels you’ll be monitoring in your scopes will be different from the table of data to nit values listed
previously for grading to the PQ EOTF.
Ouputting Hybrid Log-Gamma
Once you’ve created an HLG grade for your program, you can output it to any high-quality 10-bit
capable media format.
280Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
Generate HDR Light Level Report
```
(Studio Version Only)
```
You can now generate HDR Light Level reports from the Media Pool. To do so, select a clip in the
Media Pool, right-click it and choose Generate HDR Report from the context menu. The tool will
prompt you to select a location to save the HDR Light Level report in .pdf format.
This tool analyzes all frames in rendered HDR clips and presents light level statistics, including MaxCLL
and MaxFALL. It also includes a snapshot of the frame containing the maximum luminance level with a
box highlighting the point where the maximum values were found.
An HDR Light Level report exported from DaVinci Resolve
281Setup and Workflows | HDR Viewers HDR Setup and Grading
MEDIA
Chapter 11
Image Sizing
and Resolution
Independence
DaVinci Resolve is a resolution-independent application. This means that, whatever
the resolution of your source media, it can be output at whatever other resolution
you like, and just about every size-dependent effect in your project, text, windows
of grades, edit and input clip scaling, and other effects will scale appropriately to
match the new output resolution.
This also means that you can freely mix clips of any resolution, fitting 4K, HD, and SD clips into the
same timeline, with each scaling to fit the project resolution as necessary.
Your project’s resolution can be changed at any time, allowing you to work at one resolution, and
then output at another resolution. This also makes it easy to output multiple versions of a program at
different resolutions, for example, outputting 4K, HD, and SD sized versions of the same timeline.
Additionally, most controls that let you transform clips, either to push into a clip for creative intent, or
to pan and scan media of one format to fit better into a different output format, are smart enough to
always refer back to the source resolution when combining resizing operations to shrink, then enlarge
an image for various reasons as you work in the Cut, Edit, Fusion, and Color pages.
This chapter covers the relationship among the different sizing and transform controls found in DaVinci
Resolve, showing how they work together to intelligently manage the sizing of clips and effects
as you work.
Contents
About Resolution Independence  283
Timeline Resolution 283
Mixing Clip Resolutions 284
Changing the Timeline Resolution  284
You Can Use Separate Timelines to Output Different Resolutions 284
You Don’t Need Separate Timelines to Output Different Resolutions  284
Using High Resolution Media in Lower Resolution Projects  285
282Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
About Resolution Independence
If you only read one paragraph of this chapter, read this: Resolution Independence in DaVinci Resolve
means you can add clips to a timeline in any combination of resolutions to fit the project resolution you’ve
chosen to work at, and you can later output that timeline to as many other resolutions as necessary
in order to create multiple deliverables. When you do so, all effects and transforms will automatically
readjust themselves to match the sizing of each new timeline resolution, and most transforms are
calculated and processed using the full native resolution of the source media you’ve linked to that clip.
In short, what this means is that you can create multiple deliverables in multiple resolutions by
simply changing the timeline resolution or by using a lower resolution setting in the Deliver page
compared to the timeline resolution when you create a new job to render out, and every effect will be
the right size automatically.
Timeline Resolution
The timeline resolution is one of the most fundamental settings of your project, defining its frame size.
It’s found in the Master Settings panel of the Project Settings, where you can choose a predefined
resolution from the “Timeline resolution” drop-down menu, or you can type a custom resolution into
the X and Y fields below.
The project-wide Timeline Resolution parameters found in the Master Settings panel of the Project Settings window
Clip Source Resolution  285
```
Pixel Aspect Ratio (PAR) 285
```
Clip Resolution  285
The DaVinci Resolve Sizing Pipeline  286
```
“Super Scale” High Quality Upscaling (Studio Version Only)  286
```
Fusion Effects and Resolution  287
Image Scaling  289
Edit Sizing in the Cut and Edit pages  293
Image Stabilization  294
Input Sizing on the Color Page 294
Node Sizing on the Color Page 294
Output Sizing on the Color Page 294
Output Blanking  295
Format Resolution on the Delivery Page  295
Rendering Sizing Adjustments and Blanking  296
283Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
Mixing Clip Resolutions
Media used in a project does not have to match the timeline resolution. In fact, it’s extremely common
to mix multiple resolutions within the same timeline. Clips that don’t match the current resolution will be
```
automatically resized according to the currently selected Image Scaling setting (described below).
```
Changing the Timeline Resolution
As mentioned earlier, you can change the timeline resolution whenever you like. When you do so,
each Edit page transform, Fusion clip effects output, Color page Power Window, Input and Output
Sizing adjustment, tracking path, spatial keyframing value, as well as any other other resolution-
dependent Resolve FX effect or transform operation in DaVinci Resolve is automatically and
accurately scaled to fit the new resolution.
You Can Use Separate Timelines
to Output Different Resolutions
Beginning in DaVinci Resolve 16, you have the option of creating separate timelines with individual
```
Format (including Input Scaling), Monitoring, and Output Sizing settings for situations where
```
you need to set up multiple timelines to create multiple deliverables with different resolutions,
pixel aspect ratios, frame rates, monitoring options, or output scaling options than the overall project,
including “Mismatched Resolution Files” settings.
For more information, see Chapter 34, “Creating and Working with Timelines.”
You Don’t Need Separate Timelines
to Output Different Resolutions
Because of the way DaVinci Resolve works, it’s not necessary to create separate timelines when all
you need is to output the same timeline at multiple resolutions. Instead, you can focus on mastering a
single timeline, which you can output to as many other resolutions as you need.
```
For example, with only a single timeline in a project set to 4096x2160 (4K DCI) resolution, you can
```
easily output UHD, HD, center-cut SD, and center-cut Instagram sized deliverables in any format you
need by simply changing the Resolution drop-down setting in the Deliver page Render Settings before
you create a job to render. DaVinci Resolve takes care of the rest.
The Deliver page drop-down menu in the Render Settings panel lets you
choose what resolution you want to output the current timeline using
284Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
Using High Resolution Media in Lower Resolution Projects
Every set of transform and sizing parameters and settings that resize clips is combined intelligently,
so that the full resolution of a clip’s source media is always used as the source for any transform. For
example, if you’re using 8K media within a 1920x1080 project, and you need to enlarge a clip using the
Input Sizing palette’s Zoom parameter to 200%, the image is scaled relative to the native 8K resolution
of the source, and the result is fit into the current timeline resolution. This automatically guarantees
the highest quality for any image transform you make so long as you don’t zoom in past the native
resolution of any given clip.
This also applies to situations where, for example, you shrink a clip in the Edit page using the Edit
Sizing controls, only to re-enlarge the same clip in the Color page, using the Input Sizing controls.
In this situation, DaVinci Resolve is smart enough to do the math combining the project resolution,
the Edit Sizing, and the Input Sizing controls so that a single transform is applied to the native source
resolution of that clip, giving you the best quality result.
```
NOTE: This changes when you apply Fusion effects to any clip,
```
as described later in this chapter.
Clip Source Resolution
Clip resolution in DaVinci Resolve is handled by the combination of Pixel Aspect Ratio and Resolution.
```
Pixel Aspect Ratio (PAR)
```
The Timeline Format settings, found in the Master Settings of the Project Settings, let you specify a
Pixel Aspect Ratio for the project, in addition to the frame size. This setting defaults to Square Pixel,
which is appropriate for high definition projects and most digital media. However, there are also
options for 16:9 anamorphic, 4:3 standard definition, or Cinemascope. Which options are available
depends on what timeline resolution you’ve selected.
In addition, each clip has individually adjustable PAR settings in the clip attributes, for
situations where you’re mixing multiple types of media within a single project. For example, if
you’re mixing SD clips with non-square pixels and HD clips with square pixels, you can sort out
all of the SD clips in the Media Pool and assign them the appropriate NTSC or PAL non-square
pixel ratio PAR setting.
For more information, see Chapter 22, “Modifying Clips and Clip Attributes.”
Clip Resolution
Ordinarily, the resolution of a clip is entirely dependent on the resolution that was selected when that
media was shot, or rendered out of a compositing, VFX, or 3D application. Once a piece of media has
been created, the native resolution of that media cannot be changed, and to maintain the ideal amount
of sharpness for that clip, you need to make sure that whatever transforms you apply to resize a clip
```
zoom into that clip no more than 10-20% over its native resolution (if even that), otherwise the image
```
will visibly soften.
285Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
However, DaVinci Resolve provides advanced Super Scale image processing in the Clip Attributes of
every video and image clip, that make it possible to resize clips beyond their native resolution while
maintaining the perceptible sharpness of a clip that’s still within it’s native resolution. This is an illusion,
but it’s a convincing one.
The DaVinci Resolve Sizing Pipeline
This section discusses the various sizing controls that are available in DaVinci Resolve, and how they
work together.
```
“Super Scale” High Quality Upscaling (Studio Version Only)
```
For instances when you need higher-quality upscaling than the standard Resize Filters allow, you
can now enable one of the “Super Scale” options in the Inspector or in the Video panel of the Clip
Attributes window for one or more selected clips. Unlike using one of the numerous scaling options in
the Edit, Fusion, or Color pages, Super Scale actually increases the source resolution of the clip being
processed, which means that clip will have more pixels than it did before and will be more processor-
```
intensive to work with than before, unless you optimize the clip (which bakes in the Super Scale effect
```
```
into the optimized media) or cache the clip in some way.
```
Super Scale options in the Video panel of the Clip Attributes
The Super Scale dropdown menu provides the options of 2-3-4x, and 2-3-4x Enhanced, as well as
Sharpness and Noise Reduction options to tune the quality of the scaled result. Most of the Super
Scale parameters are in fixed Low, Medium, or High increments, however the Enhanced modes let
you apply them in variable amounts. Selecting one of these options enables DaVinci Resolve to use
advanced algorithms to improve the appearance of image detail when enlarging clips by a significant
amount, such as when editing SD archival media into a UHD timeline, or when you find it necessary to
enlarge a clip past its native resolution in order to create a closeup.
You may find that, depending on the source media you’re working with, setting Sharpness to Medium
yields a relatively subtle result that can be hard to notice, but setting Sharpness to high should be
immediately more preferable, while also sharpening grain and noise in the image to an undesirable
extent at the default settings. However, while raising Noise Reduction will ameliorate this effect, it will
also diminish the gains you obtained by raising Sharpness. In these cases, it’s worth experimenting
with keeping Sharpness at Low or Medium so that Super Scale sharpens all aspects of a clip, but then
```
using the Noise Reduction tools of the Color page (with their additional ability to be fine-tuned) to
```
diminish the unwanted noise.
```
TIP: Super Scale, while incredibly useful, is a processor-intensive operation, so be aware that
```
turning this on will likely prevent real-time playback. One way to get around this is to create
Optimized Media for clips in which you’ve enabled Super Scale, since Optimized Media
“bakes in” the Super Scale effect. Another way to work is to create a string-out of all of the
source media you’ll need to enlarge at high-quality, turn on Super Scale for all of them, and
then render that timeline as individual clips, while turning on the “Render at source resolution”
and “Filename uses > Source Name” options.
286Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
Fusion Effects and Resolution
All image processing by the Fusion page takes place before effects that are applied by the Edit page,
with the sole exception of the Lens Correction effect. When it comes to sizing and image resolution,
whether or not the Fusion page affects resolution depends on how you use it.
Fusion Effects Inherit the Source Resolution of a Clip
When you open a clip on the Timeline in the Fusion page, the Fusion page is set to the full source
resolution of that clip, regardless of the Timeline resolution. This can be seen if you look at the
resolution that’s listed above the upper right-hand corner of the Viewer. This means that if you
```
don’t apply any operations that reduces the image resolution (described later), subsequent sizing
```
adjustments in other pages will refer to the same resolution as the source clip.
The available resolution and bit depth of the currently selected clip is visible
above the upper right-hand corner of the Viewer, circled in red
Fusion Clips Inherit the Timeline Resolution
If you combine multiple clips on the Timeline into a Fusion clip, the Fusion page is set to the timeline
resolution, regardless of the source resolution of the clip. The image is then output to the Edit page at
this timeline resolution, and all subsequent sizing adjustments are performed relative to the timeline
resolution, with no reference to the original resolution in the source clip.
287Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
The available resolution and bit depth of a clip that’s been turned into a
Fusion Clip, that’s set to the timeline resolution of 1920x1080
Operations in the Fusion Page That Change Resolution
If you don’t do anything to change the size of a clip in the Fusion page, then its resolution stays the
same and you’ll effectively output the source resolution of that clip to the Edit page.
However, if you Merge the image with a second clip attached to the background which has a different
resolution, or if you use a Crop or Resize node to increase or decrease the resolution of the image,
then the new resolution will be passed to the Cut and Edit pages as the effective source resolution of
that clip.
In short, the Fusion page passes whatever resolution is output by the last node of your composition
back to the Edit page as the effective resolution of that clip in the DaVinci Resolve image
processing pipeline.
Fusion Page Transform Operations Are Resolution Independent
Within the Fusion page, multiple Transform nodes operate in a resolution independent manner relative
to the resolution of the source clip. This means that if you shrink an image to 20% with one Transform
node, and then enlarge it back up to 100% using a second Transform node, you end up with an image
that has all the resolution and sharpness of the input image.
Fusion Page Resize Operations Are Not
Within Fusion there are two kinds of transform effects, the Transform node and the Resize node. Which
of these nodes you use has a dramatic impact on resolution independence.
288Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
```
• The Transform node always refers back to the input resolution of the clip (as defined by the
```
```
Clip Attributes) to enable resolution-independent sizing, such that multiple Transform nodes
```
can scale the image down and up repeatedly within the Fusion page with no unnecessary
loss of image resolution.
• The Resize node actually decreases image resolution when you shrink an image or
```
increases image resolution (with filtering) when enlarging. This means that the Resize node
```
will break resolution independence, and the resolution of the image will be fixed at whatever
you specify from that point in your composite’s node tree forward.
In most situations, you probably want to use the Transform node to maintain resolution independence
relative to the source media, unless you specifically want to alter and perhaps reduce image resolution
to create a specific special effect which purposefully degrades the image. For example, if you want
a clip to be forced to a standard definition resolution in order to make it look like a low-resolution
archival clip, the Resize node will accomplish this. Enlarging the result with a Transform node will then
perform a filtered enlargement that will look like a real SD clip being enlarged.
Transforms from the Fusion Page to the Edit Page
All transform operations you apply on the Cut, Edit, and Color pages are resolution independent,
referring to the original resolution of the source media, so long as you don’t use the Fusion page.
```
For example, if you shrink an image to 20% in the Edit page (using Edit sizing controls) and then
```
```
enlarge it in the Color page back to 100% (using Input sizing controls), you end up with an image that
```
has all the resolution and sharpness of the original media, because the final resolution is drawn from
the original source media.
However, once you use the Fusion page to do anything to a clip, from adding a small effect to creating
a complex composition, the resolution-independent relationship of the Edit and Color pages to the
source media is broken, and whatever resolution is output from your Fusion composition is the new
effective resolution of the clip that appears in the Timeline. This means if you shrink an image to
```
20% in the Fusion page (using a Transform node) and then enlarge it in the Color page by 150%, you
```
end up with an image that isn’t as sharp as the original because the downconverted image in the
Fusion page is effectively the new source resolution of that clip.
Image Scaling
DaVinci Resolve has a dedicated mechanism for automatically managing the size of clips with
resolutions that don’t match the timeline resolution, and it’s separate from the Zoom transform controls
that are available for making creative adjustments to clips. This is called Image Scaling, and it’s
customizable in a few different areas.
Resize Filter Project Setting
The Resize Filter setting lets you choose the filter method that’s used to interpolate image pixels when
resizing clips:
```
Smoother: May provide a more pleasing result for projects using clips that must be scaled down to
```
standard definition as this filter exhibits fewer sharp edges at SD resolutions.
```
Bicubic: While the sharper and smoother options are slightly higher quality, bicubic is still an
```
exceptionally good resizing filter and is less processor-intensive than either of those options.
```
Blinear: A lower quality setting that is less processor-intensive. Useful for previewing your work on a
```
low-performance computer before rendering when you can switch to one of the higher quality options.
289Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
```
Sharper: Usually provides the best quality for most projects, using an optical quality processing
```
technique that’s unique to DaVinci Resolve.
```
Custom: This setting lets you take control of the exact algorithm used in all resizing operations. The
```
custom Resize Filter options available are: Bessel, Box, Catmul-Rom, Cubic, Gaussian, Lanczos,
Mitchell, Nearest Neighbor, Quadratic, and Sinc. In practice, the difference between these methods
can be quite subjective. However, if you need to match a specific resizing method used from another
application, you can do it here. For everyday use, the normal resizing filters in DaVinci Resolve should
be sufficient.
Override Input scaling: Checking this box lets you choose an Input Sizing preset to
apply to the project.
Override Output scaling: Checking this box lets you choose an Output Sizing preset to
apply to the project.
Anti-alias edges: A second group of settings lets you choose how to handle edge anti-aliasing
for source blanking.
 Auto: Adds anti-aliasing when any of the Sizing controls are used to transform the image.
Otherwise, anti-aliasing is disabled.
 On: Forces anti-aliasing on at all times.
 Off: Disables anti-aliasing. It might be necessary to turn anti-aliasing off if you notice black blurring
at the edges of blanking being applied to an image.
```
Deinterlace quality: (only available in Studio version) A fourth group of settings lets you choose the
```
quality/processing time tradeoff when deinterlacing Media Pool clips using the Enable Deinterlacing
checkbox in the Clip Attributes window. There are two settings:
 Normal: A high-quality deinterlacing method that is suitable for most clips. For many clips,
Normal is indistinguishable from High. Normal is always used automatically during playback in
DaVinci Resolve.
 High: A more processor-intensive method that can sometimes yield better results, depending on
the footage, at the expense of slower rendering times.
 DaVinci Neural Engine: This option uses the advanced machine learning algorithms of the DaVinci
Neural Engine to analyze motion between the fields of interlaced material and reconstructs them
into a single frame. This option is very computationally intensive, but ideally will deliver an even
more aesthetically pleasing result than the “high” setting.
Input Scaling Project Setting
If the native resolution of an imported clip doesn’t match the timeline resolution, then the currently
selected Input Scaling Preset in the Image Scaling panel of the Project Settings dictates how
mismatched clips will be handled project-wide. The default setting is “Scale entire image to fit,”
which shrinks or enlarges the image to fit the current dimensions of the frame without cropping any
part of the image, adding letterboxing or pillarboxing as necessary to fill the unused portion of the
frame depending on whether the horizontal or vertical dimension of the image hits the edge of the
frame first.
The Mismatched resolution files option let you choose how clips that don’t match the current project
resolution are handled. The illustrated examples below show an SD clip being fit into an HD project
using each of the different options.
290Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
Center crop with no resizing
Clips of differing resolution are not scaled at all. Clips that are smaller than the current frame size
are surrounded by blanking, and clips that are larger than the current frame size are cropped.
Keep in mind that this is a good setting to use if you’re importing a timeline from another NLE in
which clip resolution adjustments are imported as scaling adjustments. Choosing “Center Crop
with no resizing” prevents DaVinci Resolve from “double scaling” clips in imported timelines.
Center crop with no resizing
Scale full frame with crop
Clips of differing resolution are scaled so that the clip fills the frame with no blanking. Excess
pixels are cropped. This is a good setting when you want clips that don’t match the project
resolution to automatically fill the frame, with no letterboxing or pillarboxing.
Scale full frame with crop
Stretch frame to all corners
Useful for projects using anamorphic media. Clips of differing resolutions are squished or
stretched to match the frame size in all dimensions. This way, anamorphic media can be stretched
to match full raster or full raster media can be squished to fit into an anamorphic frame. An added
benefit of this setting is that it makes it easy to mix anamorphic and non-anamorphic clips in
the same project.
Stretch frame to all corners
291Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
Scale entire image to fit
The default setting. Clips of differing resolution are scaled so that each clip fills the frame without
```
cropping. The dimension that falls short has blanking inserted (letterboxing or pillarboxing). This is
```
a good setting when you want clips that don’t match the project resolution to automatically fit into
the frame without being cropped in any way, and you’re fine with letterboxing or pillarboxing as a
result. However, if you’ve imported a timeline from another NLE and there are clips that are twice
as big as they should be, it’s because this setting is on by default, and your imported timeline
has imported scaling settings used to resize clips that didn’t match the timeline resolution. If this
happens, switch to “Center crop with no resizing” instead, and that will fix the problem.
Scale entire image to fit
Output Image Scaling Project Settings
Another group of settings found in the Image Scaling panel of the Project Settings lets you optionally
choose a different resolution to be output, either via the Deliver page, or via your video output
interface for monitoring or outputting to tape.
In particular, if you set the “Resolution” in the Render Settings panel of the Deliver page to something
other than the timeline resolution, these settings are used to make the change. This is useful in
situations where you’re mastering a high resolution 4K project, but you want to monitor using an
HD display, and you plan on eventually outputting HD resolution deliverables in addition to the 4K
deliverables for which you want to use different Scaling and/or Resize Filter settings that work better at
the lower resolution.
Match timeline settings: This checkbox is turned on by default so that these settings mirror
the Image Scaling and Input Scaling settings described above. Turning this checkbox off lets
you choose different settings to be used when monitoring, outputting to tape, or rendering,
using the other settings below.
Output resolution: Lets you choose an alternate resolution for monitoring and delivery. You
can also set this from the “Resolution” drop-down menu of the Video panel in the Render
Settings of the Deliver page.
For “X x Y” processing: Lets you specify a different custom alternate resolution.
Pixel aspect ratio: Lets you specify an alternate pixel aspect ratio to match the
alternate timeline format.
Mismatched resolution files: Lets you choose an alternate way of handling mismatched
resolution files that works better for the alternate resolution you’ve chosen. These options
work similarly to those of the “Input Scaling” group. For example, for an HD or UHD resolution
project you may have the Image Input Scaling set to “Scale Full Frame With Crop” so that all
Standard Definition resolution files are center-cut to eliminate blanking. However, if you’re
using Output Image Scaling to create a Standard Definition deliverable, you may want to set
292Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
the Output Image Scaling > Mismatched resolution files setting to “Scale entire image to fit”
in order to letterbox all HD or UHD resolution clips, while preserving the original aspect ratio
of the SD clips.
Super Scale: Sets a very processor-intensive and high quality upscaling algorithm that
actually creates new pixels for the resized image. The possible values are None, 2-3-4x,
2-3-4x Enhanced, and Auto.
Clip-Specific Scaling Settings
There’s an additional set of Scaling and Resize Filter settings, available in the Video Inspector for
selected clips, that provide the same options as those found in the Project Settings window, except
that they let you choose settings that will be specific to a particular clip. These are valuable for
situations where the project-wide scaling setting is working for most clips, but you have a handful of
specific clips that would benefit from individual settings.
Edit Sizing in the Cut and Edit pages
The Video Inspector contains a set of Transform parameters with which you can alter clips in the
Timeline. These parameters operate independently of the Input Sizing controls found in the Color
page. Separate Edit sizing controls serve a number of different functions:
 They’re convenient for editors and are easily animated for creating motion graphics effects right
on the Cut and Edit page timelines. They also keep editor transform adjustments separate from
colorist transform adjustments, for a clear division of labor and responsibility.
 Edit sizing parameters also store incoming transform data from imported AAF and XML projects
that come from other applications, so that imported transforms are kept separate from adjustments
made by colorists and finishing artists.
The Transform parameters in the Inspector of the Edit page
If, when importing an AAF or XML project file, you turned on the “Use sizing information” checkbox,
then every clip that had position, scale, rotation, or crop settings applied in the originating NLE will
have those adjustments applied to these transform parameters, which is convenient for keeping
imported transform settings separate from other DaVinci Resolve-native transform settings.
Additionally, a set of Dynamic Zoom parameters also exists in the Video Inspector, which let you make
quickly animated transforms using graphical controls that correspond to the start and end states of
an animated transform. However, these transforms are lumped in with the other Edit page Transform
parameters in terms of the order of sizing operations occurring throughout DaVinci Resolve.
293Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
The Dynamic Zoom settings in the Inspector of the Video Inspector
The transform that’s made via the Edit Sizing controls refers back to either the source resolution of
each clip, or the resolution output by the Fusion page if it’s in use.
Image Stabilization
DaVinci Resolve provides Image Stabilization controls in the Cut, Edit, and Color pages that all
control the same transform operation that happens between Edit sizing and Input Sizing in the image
processing pipeline. The transform that’s made via the Image Stabilization controls refers all the way
back to either the source resolution of each clip, or the resolution output by the Fusion page if it’s in use.
Input Sizing on the Color Page
The Sizing palette on the Color page has another dedicated set of keyframable transform parameters
that work with the various DaVinci control panels to let the colorist apply pan and scan adjustments
while working through a project. These parameters work independently of the Edit page Transform
parameters, allowing you to keep imported transform settings separate from other transform settings
that you apply. However, for convenience the Edit sizing controls are available in the Color page as well.
The transform that’s made via the Input Sizing controls refers all the way back to either the source
resolution of each clip, or the resolution output by the Fusion page if it’s in use.
Node Sizing on the Color Page
Using Node Sizing, you can apply individual sizing adjustments to clips on a per-node basis within the
Color page, which is similar in principal to using Transform nodes in the Fusion page. All Node Sizing
adjustments within a grade are cumulative, and any keyframing done to Node Sizing parameters is
stored in that node’s Node Format keyframe track in the Keyframe Editor. Two good examples of Node
Sizing include realigning color channels individually in conjunction with the Splitter/Combiner nodes
or duplicating windowed regions of an image by moving them around the frame. Subsequent Node
Sizing operations do not refer back to the source resolution of a clip, so using multiple Node Sizing
operations to reduce and enlarge an image will reduce image resolution and sharpness.
Output Sizing on the Color Page
Output sizing is an additional transform that is applied after Edit sizing, Fusion sizing, Input sizing, and
Node sizing. It’s an overall adjustment that affects every clip at once, which is suitable for making last-
minute format alterations that you want to affect the entire program. Technically, Output Sizing includes
the Blanking controls, but those are important enough to discuss separately. Output Sizing also does
not refer back to the source resolution of clips, so if you use Edit or Input Sizing to shrink a clip, and
Output Sizing to enlarge it again, the final result will be somewhat softened as you’re enlarging the
lower resolution image output by Input Sizing.
294Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
Output Blanking
Output blanking is not a sizing operation, but it’s often related and so worth mentioning here. Blanking
is an adjustment you can use to add black areas to the top, bottom, left, or right of an image, in order
```
to add “letterboxing” (black bars at the top and bottom of the image) or “pillarboxing” (black bars at the
```
```
left and right of the image) that lets you fill in the unused parts of an image frame that’s either shorter
```
or thinner than the current output resolution.
Once all transforms, compositing operations, and color corrections have been applied by the DaVinci
Resolve image processing pipeline, the very last operation to be performed is Output blanking, if
it’s enabled. This guarantees that overlapping images, grading, and other adjustments are properly
“blacked out” no matter what you’re doing to the program.
```
Output Blanking controls are found in the Timeline menu (as a series of aspect ratios) as well as in the
```
```
Output Sizing parameters of the Color page Sizing palette (via Top, Right, Bottom, and Left controls).
```
```
TIP: Text and graphics superimposed via the Data Burn-In window, if enabled, are the only
```
effects that will appear in front of picture areas affected by blanking. This lets you add timecode
and other information over letterboxed areas that you don’t want to obscure the picture.
Format Resolution on the Delivery Page
By default, the Format Resolution setting in the Render Settings of the Deliver page matches the
timeline resolution when “Match timeline settings” is enabled in the Output Scaling Preset in the Image
Scaling panel of the Project Settings.
Choosing a new resolution from the “Set Resolution to” drop-down menu lets you override the current
Format Resolution setting before rendering. Using this control, you can queue up multiple jobs, each
set to a different resolution, to output multiple formats during a single render session.
For more information on rendering and setting up jobs for the Render Queue,
see Chapter 186, “Using the Deliver Page.”
295Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
Rendering Sizing Adjustments and Blanking
When rendering your final output, you have the option of choosing whether or not to “bake in” the
sizing operations that have been performed. For example, you may have set up a whole set of specific
sizing adjustments for the clips in a program, but then you’re requested to render the project and its
media as individual clips for round trip re-delivery to the editor for further work. In this case, you can
choose to either render the sizing into the final media, or not.
Whether or not sizing is rendered into your final media depends on the “Disable edit and input sizing”
checkbox in the Advanced Settings options of the Render Settings panel. You can disable sizing and
blanking either when rendering the current timeline as a single clip, or when rendering individual clips.
If “Disable sizing and blanking output” is turned off: Output Blanking, Cut and Edit page
sizing adjustments, Color page Input and Output Sizing adjustments, and Image Stabilization
are rendered into the final rendered media using the optical-quality sizing algorithms available
to DaVinci Resolve. This is best if your sizing adjustments are approved and final, and you
want to “bake” sizing adjustments into the final media you’re delivering.
If “Disable sizing and blanking output” is turned on: Output Blanking, Cut and Edit page
sizing adjustments, Color page Input and Output Sizing adjustments, and Image Stabilization
are not rendered, and each clip will be rendered either at the source resolution if “Render at
source resolution” is enabled in individual clips mode, or to the currently specified resolution
of the timeline or project. However, the sizing adjustments you’ve made will be exported as
part of the XML or AAF file that you’re exporting. This is best for workflows where the editor
wants to continue adjusting sizing after you’ve handed off the graded project relative to the
original size of the clips.
Keep in mind that if you want to render Input Sizing adjustments into the media you’re outputting, the
“Force sizing to highest quality” checkbox guarantees that DaVinci Resolve will use the highest-quality
sizing setting, even if you’ve temporarily chosen a faster-processing option for a slower computer.
```
NOTE: “Disable sizing and blanking output” does not disable any transform operations that
```
happen within the Fusion page. Those will continue to be applied to the final output.
296Setup and Workflows | Chapter 11 Image Sizing and Resolution Independence
MEDIA
Chapter 12
Data Burn-In
This chapter covers how to use the Data Burn-In window that’s available to every
page in DaVinci Resolve.
Contents
Data Burn-In  298
Project vs. Clip Mode  299
Setting Up Burned-In Metadata  299
Saving and Loading Burn-In Presets  299
Data Burn-In Metadata  300
Custom Output Options  301
Gang Rendered Text Styles  302
Prefix Render Text  302
297Setup and Workflows | Chapter 12 Data Burn-In
MEDIA
Data Burn-In
The Data Burn-In window lets you display select metadata as a timeline-wide “window burn”
that’s superimposed over the image in the Viewer. This window burn is written into files that you
render in the Deliver page, and it’s also output to video, for viewing on your external display, or for
outputting to tape.
The Burn-In window is available by choosing Workspace > Data Burn-In.
Data Burn-In window
Traditionally, window burns are useful as a reference when creating offline media that you need to
keep track of later. However, the Data Burn window is extremely flexible. For example, it’s also useful
for watermarking review files that you don’t want to be distributed accidentally with either custom text
or graphics with alpha channels, for adding graphical logos or “bugs” to programs in preparation for
```
broadcast (again, optionally using graphics with alpha channels), for superimposing custom reference
```
guidelines of some sort over the images being monitored, or even just for temporarily displaying
timecode or clip names to refer to on your monitor while editing, mixing, or reviewing graded dailies
with a client.
Viewer displaying record timecode, source timecode, and source clip name
298Setup and Workflows | Chapter 12 Data Burn-In
MEDIA
Project vs. Clip Mode
Two buttons at the top of the Data Burn window let you choose whether you want to edit one set of
burned-in metadata that will be displayed for the entire duration of the Timeline, or edit burned-in
metadata on a clip-by-clip basis. You can combine the two, having timeline-wide window burn settings
and separate clip-specific window burn settings for a handful of clips in that timeline at the same time.
When rendering in the Delivery page, window burns are applied both when rendering timelines as
individual source clips and when rendering as one single clip.
Two separate panels let you adjust project-wide
window burns vs. clip-specific window burns
Setting Up Burned-In Metadata
Setting up different clip and project metadata to output as a window burn is easy.
To set up a window burn:
1 Choose Workspace > Data Burn-In.
2 Click Project or Clip at the top of the Data Burn-In window.
3 Turn on the checkboxes of whatever items of metadata you want to display in the “Add to
Video Output” column. More information about the available items appears later in this chapter.
The first item of metadata is centered near the bottom of the frame, above Action Safe. Each
additional item of metadata you turn on for display is added above whichever items are already
displayed, regardless of their position in the “Add to Video Output” list.
4 Click any currently enabled item of metadata from the list to highlight it in black, and edit that
item’s Custom Output parameters at the right. More information about the available parameters
appears later in this chapter.
To reset the current window burn setup:
Click the Reset button next to the Option drop-down menu to reset the current mode of the
Data Burn window.
Saving and Loading Burn-In Presets
If there are common sets of metadata that you regularly use and switch among, you can save each set
up as a preset for future use.
To save a burn-in preset:
1 Click the Option menu and choose Save As New Preset.
2 Type a name into the Burn In Preset dialog that appears, and click OK. That preset is added to the
list of saved presets in the Option menu.
299Setup and Workflows | Chapter 12 Data Burn-In
MEDIA
To delete a burn-in preset:
1 Choose a preset from the Option menu.
2 Click the Option menu, and choose Delete.
3 A dialogue box appears asking you to confirm the deletion.
To modify a burn-in preset:
1 Choose a preset from the Option menu.
2 Edit it however you like.
3 Click the Option menu, and choose Update.
Data Burn-In Metadata
The leftmost column in the Data Burn-In window contains a list of all the options that you can add to
the video output as a window burn. Each option has a checkbox that lets you turn it on or off. You
can also select in the Option drop-down if you would like the item name rendered as a prefix to the
burn-in data.
```
NOTE: If two clips overlap in the Timeline, the metadata that matches the currently visible clip
```
in the Viewer is what will be displayed in the window burn.
 Record Timecode: The timecode relative to the Timeline, as set in the Conform Options section of
the General Options panel of the Project Settings.
 Record Frame Number: The number of frames from the first frame of the Timeline.
 Source Timecode: Each clip’s individual timecode.
 Source Frame Number: The number of frames from the first frame of the clip.
 Record TC & Frame Num: Both metadata options combined in one line.
 Source TC & Frame Num: Both metadata options combined in one line.
 Source & Record TC: Both metadata options combined in one line.
 Feet + Frames 35mm: Displays a Feet + Frames conversion of the program’s record timecode,
calculated for 35mm film.
 Feet + Frames 16mm: Displays a Feet + Frames conversion of the program’s record timecode,
calculated for 16mm film.
 Audio Timecode: The timecode of the audio track of the clip.
 Keycode: Also referred to as edge-code, the identification codes running along the edge of film
stocks that provide an absolute reference for which digital frames correspond to which film frames.
 Source File Name: The full file path, including file name, of the media file that’s
linked to the current clip.
 Record File Name: The file name as defined in the Render Settings list of the Deliver page.
 Source Clip Name: The file name of the media file that’s linked to the current clip,
without the file path.
 Synced Audio File Name: The file name of the audio clip that’s been synced to the clip.
 Synced Audio Timecode: The timecode of the audio clip that’s been synced to the clip.
300Setup and Workflows | Chapter 12 Data Burn-In
MEDIA
 Custom Text1: A line of text that you type into the Text field of the Custom Output parameters.
You can use any characters you like. When editing any of the three custom text fields that are
available, you can use “metadata variables” that you can add as graphical tags that let you
display clip metadata. For example, you could add the corresponding metadata variable tags
%scene_%shot_%take and the custom text would display “12_A_3” if “scene 12,” “shot A,” “take 3”
were its metadata.
For more information on the use of variables, as well as a list of all variables that are
available in DaVinci Resolve, see Chapter 16, “Using Variables and Keywords.”
 Custom Text2: A second line of text that you can customize.
 Custom Text3: A third line of text that you can customize.
 Logo1: Lets you superimpose a graphic over the image in a customizable location. Compatible
graphics formats include PNG, TGA, TIF, BMP, and JPG. Alpha channels are supported for
transparency in logos.
 Logo2: Lets you superimpose a second graphic.
 Logo3: Lets you superimpose a third graphic.
 Reel Name: The currently defined reel number for the current clip.
 Shot: Shot metadata, if it’s been written to the file by a camera, or entered into the Metadata Editor
on the Media page.
 Scene: Scene metadata, if it’s been written to the file by a camera, or entered into the Metadata
Editor on the Media page.
 Take: Take metadata, if it’s been written to the file by a camera, or entered into the Metadata
Editor on the Media page.
 Angle: Angle metadata, if it’s been written to the file by a camera, or entered into the Metadata
Editor on the Media page.
 Day: Day metadata, if it’s been written to the file by a camera, or entered into the Metadata Editor
on the Media page.
 Date: Date metadata, if it’s been written to the file by a camera, or entered into the Metadata
Editor on the Media page.
 Good Take: Corresponds to Good Take metadata, if it’s been written to the file by a camera, or
entered into the Metadata Editor on the Media page.
 Camera: Corresponds to the Camera metadata, if it’s been written to the file by a camera, or
entered into the Metadata Editor on the Media page.
 Roll/Card: Corresponds to the Roll/Card metadata, if it’s been written to the file by a camera, or
entered into the Metadata Editor on the Media page.
Custom Output Options
The parameters in the Custom Output panel let you modify the look, position, and in some
cases content, of the selected metadata item. Pan and Tilt are individually customizable for each
metadata item.
 Display During First x frames: Turning on this checkbox lets you specify a number of frames
during which the current item of metadata will be displayed before dissolving away over one
second. When enabled, the current item of metadata will cut onscreen with the beginning of each
new clip, remain onscreen for the duration specified, and then dissolve away.
301Setup and Workflows | Chapter 12 Data Burn-In
MEDIA
 Display During Last x frames: Turning on this checkbox lets you specify a number of frames
before the end of each clip during which the current item of metadata will appear onscreen after
fading up over one second, before cutting away with the end of the clip.
 Font: Defaults to Courier, but you can choose any font that’s installed on your system.
 Size: Defaults to 48, but you can choose standard increments from 6 to 72.
 Alignment: Defaults to Center. The only other option is Left.
```
 Font (color): Defaults to white, but you can choose from a range of predefined colors in this
```
drop-down menu.
 Background: Defaults to black, although the apparent color is influenced by the Opacity
setting. For a more garish look, you can choose from a range of predefined colors in this
drop-down menu.
 Text Opacity: Defaults to 1.00. Lets you define the transparency of the burned-in metadata’s text.
 Background Opacity: Defaults to 1.00. Lets you define the transparency of the burned-in
metadata’s background color.
 X-Y Position: Lets you change the horizontal and vertical orientation of the current item of
metadata. The default horizontal value is the center of the frame, relative to the current project’s
frame size. The first item of metadata is centered vertically near the bottom of the frame, above
Action Safe. Each subsequent item of metadata you turn on is automatically placed above the
previous item of metadata, regardless of its order in the “Add to Video Output” list.
```
 Text: (only if one of the Custom Text options is checked) A text field that lets you enter custom text
```
to display as one of three possible custom text items.
```
 Logo: (only if one of the Logo options is checked) A field that displays the file path of any currently
```
selected graphic that you’re displaying as one of the three possible Logo graphics. Compatible
graphics formats include PNG, TGA, TIF, BMP, and JPG. Alpha channels are supported for
transparency in logos.
```
 Import File button: (only if one of the Logo options is checked) Lets you choose a graphics file to
```
use as a logo.
Gang Rendered Text Styles
You have the option of independently styling each item of metadata, depending on whether the Gang
Render Text Styles option is checked in the Data Burn-In window’s Option menu. When turned on, all
text metadata share the same font, size, color, background, justification, and opacity. When turned off,
each item of metadata can have individual settings.
Prefix Render Text
Another option in the Data Burn-In window’s Option menu lets you turn the prefixes, or headers, on or
off for all metadata that’s enabled to be burned in.
302Setup and Workflows | Chapter 12 Data Burn-In
MEDIA
Chapter 13
Frameio and
Dropbox Replay
Integration
DaVinci Resolve has sophisticated integrations with Frame.io, and Dropbox
Replay video review and collaboration services designed specifically for the
postproduction industry.
Contents
Enabling Frame.io Integration in Preferences  304
Deliver and Upload to Frame.io  304
Frame.io Comments Sync with Timeline Markers  305
Importing Media from Frame.io  307
Linking Media Pool Clips and Timelines with Frame.io Clips  308
Enabling Dropbox Replay Integration in Preferences  308
Deliver and Upload to Dropbox Replay  309
Upload New Versions to Dropbox Replay  310
Dropbox Replay Comments Sync with Timeline Markers  310
Working With Dropbox Markers  311
303Setup and Workflows | Chapter 13 Frame.io and Dropbox Replay Integration
MEDIA
Enabling Frame.io
Integration in Preferences
An Internet Accounts panel in the System tab of the DaVinci Resolve Preferences lets you sign into
your Frame.io account and specify a local cache location for media being synced with Frame.io.
You’ll need to enter your login name and password to enable Frame.io integration, but once entered,
DaVinci Resolve will sign in automatically when DaVinci Resolve opens.
The Internet Accounts panel of the System tab of the
```
DaVinci Resolve Preferences window (login deliberately obscured)
```
The local cache location is used to store clips you import into a DaVinci Resolve project from the
Frame.io volume in the Media Storage panel of the Media page.
Deliver and Upload to Frame.io
A Frame.io preset at the top of the Deliver page’s Render Settings panel lets you render and upload
a program for review. All options in the Render Settings panel update to present suitable controls for
this process.
When you choose the Frame.io preset, the Location field turns into an Upload To field, and the Browse
button lets you choose a project and folder path to which to upload the exported result.
304Setup and Workflows | Chapter 13 Frame.io and Dropbox Replay Integration
MEDIA
Choosing the Frame.io preset Choosing a Frame.io account to deliver a program to
When you export to Frame.io, the available choices in the Resolution, Format, Video Codec, and Type
pop-up menus are limited to those that are most suitable for Frame.io file sharing. Choose the desired
export options, then click the Add to Render Queue button to add this job to the Render Queue as you
would with any other export. When that job is rendered, it automatically proceeds to upload to Frame.
io, and an upload percentage indicator appears in the job listing to show how far along this upload is.
When it’s finished, the job displays the text “Upload completed.”
The job in the Render Queue shows you the
percentage the file has uploaded so far
This upload is done in the background, so you can continue working on other things in DaVinci
Resolve while the file uploads. If you want to see how long the upload will take on any other page, you
can choose Workspace > Background Activity to see the Background Activity window.
Frame.io Comments Sync
with Timeline Markers
When you render a timeline directly to Frame.io, that timeline is automatically linked to the movie
```
that’s been uploaded to Frame.io, and all comments, “Likes,” and graphical annotations (drawings
```
```
and arrows) from reviewers that are added online via the Frame.io interface are automatically synced
```
```
to Frame.io markers on your timeline (so long as your computer has an active internet connection).
```
Frame.io markers are distinct from all other markers and can be independently shown and hidden,
or deleted. Drawings and arrows from Frame.io are converted into their equivalent DaVinci Resolve
annotation graphics for visibility in DaVinci Resolve.
305Setup and Workflows | Chapter 13 Frame.io and Dropbox Replay Integration
MEDIA
Comments and graphical annotations from Frame.io appear as markers with
their corresponding overlays in your DaVinci Resolve Timeline
Working With Frame.io Markers
Double-clicking any Frame.io marker in the Timeline opens a dialog that lets you send replies to
comments that appear on Frame.io, enabling editors to respond directly to commenters.
You can also place Frame.io markers on the Timeline to have them automatically sync back to Frame.
```
io, giving you the ability to send your own comments back to commenters (be kind).
```
If you delete one or more Frame.io markers on the DaVinci Resolve timeline, those markers will
also be deleted in Frame.io. This includes the Mark > Delete All Markers > Frame.io command.
This is not undoable.
The editor talking to himself
using the Frame.io comment
dialog that appears when
you open a Frame.io marker
306Setup and Workflows | Chapter 13 Frame.io and Dropbox Replay Integration
MEDIA
Frame.io Marker Navigation
You can specifically navigate only the markers created in Frame.io while in the comment dialog of
```
a Frame.io marker, using the Previous Marker (Shift-UpArrow) and Next Marker (Shift-DownArrow)
```
commands. This allows you to skip directly from comment to comment in Frame.io without having to
either navigate all markers in-between, or double-click each Frame.io marker individually to respond.
Frame.io interoperability is a Studio Only feature.
Importing Media from Frame.io
A Frame.io volume appears in the Media Storage panel of the Media page that lets you access
the media available from your Frame.io account. Within this Frame.io volume, a top-level directory
represents your account directory, and within that each project you’ve created in Frame.io appears as
a sub-directory.
Accessing the directories of a Frame.io account from the Media Storage browser
Any media files that can be accessed in Media Storage can be imported into the Media Pool via the
usual methods. Once added to the Media Pool, that media file downloads in the background to the
specified local cache location, but it’s immediately available via your internet link until the download is
complete, so you can begin working immediately. If you want to see how long the download will take,
you can choose Workspace > Background Activity to see the Background Activity window.
The Background Activity window lets you see what’s
happening in the background while you work
307Setup and Workflows | Chapter 13 Frame.io and Dropbox Replay Integration
MEDIA
Linking Media Pool Clips and
Timelines with Frame.io Clips
You can also use Frame.io accessibility in the Media Storage panel of the Media page to link clips or
timelines with media that’s already uploaded to your Frame.io account. Just locate and select a Frame.
io clip in Media Storage, then right-click the clip or timeline you want to link it to in the Media Pool and
choose Link to Frame.io Media from the contextual menu.
If you’ve linked a Frame.io clip to a timeline, comments made on that Frame.io clip appear on the
linked timeline as Frame.io markers, just as if you’d exported that timeline directly to Frame.io.
Enabling Dropbox Replay
Integration in Preferences
An Internet Accounts panel in the System tab of the DaVinci Resolve Preferences lets you sign
into your Dropbox account. You’ll need to enter your login name and password to enable Dropbox
integration, but once entered, DaVinci Resolve will sign in automatically when DaVinci Resolve opens.
The Dropbox Login window in the Internet Accounts panel
of the System tab of the DaVinci Resolve Preferences window.
308Setup and Workflows | Chapter 13 Frame.io and Dropbox Replay Integration
MEDIA
Deliver and Upload to Dropbox Replay
A Dropbox Replay preset at the top of the Deliver page’s Render Settings panel lets you render and
upload a program for review. All options in the Render Settings panel update to present suitable
controls for this process.
```
NOTE: The Dropbox Replay Render settings are separate from the normal Dropbox Render
```
settings, and you need to use this specific set of presets to integrate with Dropbox Replay.
```
The Dropbox Replay Render settings (highlighted).
```
Note they are different from the normal
Dropbox Render settings to the left.
When you export to Dropbox Replay, the available choices in the Resolution, Format, Video Codec,
and Audio pop-up menus are limited to those that are most suitable for Dropbox Replay. Choose
the desired export options, then click the Add to Render Queue button to add this job to the Render
Queue as you would with any other export. When that job is rendered, it automatically proceeds to
upload to Dropbox Replay, and an upload percentage indicator appears in the job listing to show how
far along this upload is. When it’s finished, the job displays the text “Upload completed.”
The job in the Render Queue shows you the percentage the
file has uploaded, and lets you know when it’s completed.
This upload is done in the background, so you can continue working on other things in DaVinci
Resolve while the file uploads. If you want to see how long the upload will take on any other page,
you can choose Workspace > Background Activity to see the Background Activity window.
309Setup and Workflows | Chapter 13 Frame.io and Dropbox Replay Integration
MEDIA
Unlinking a Timeline from Dropbox Replay
If you wish to remove a specific timeline from using Dropbox Relay integration, simply right-click on the
Timeline and select Unlink from Dropbox Media from the contextual menu.
Upload New Versions to Dropbox Replay
DaVinci Resolve supports the versioning functions found in Dropbox Replay. This lets the Replay user
easily comment and switch between different versions of the same clip.
Once the original timeline has been rendered and uploaded to Dropbox using the Replay preset in the
Deliver page, an additional checkbox appears in the preset, called “Upload as new version.” With this
box checked, any subsequent renders of this timeline will automatically be added to the version
stack of the clip in Dropbox Replay. The latest version will always be the default for the clip in the
Replay interface.
Dropbox Replay Comments Sync
with Timeline Markers
When you render a timeline directly to Dropbox Replay, that timeline is automatically linked to
the movie that’s been uploaded to Dropbox Replay, and all comments, and graphical annotations
```
(drawings and arrows) from reviewers that are added online via the Dropbox Replay interface are
```
```
automatically synced to Dropbox markers on your timeline (so long as your computer has an active
```
```
internet connection). Dropbox markers are distinct from all other markers and can be independently
```
shown and hidden or deleted. Drawings and arrows from Dropbox Replay are converted into their
equivalent DaVinci Resolve annotation graphics for visibility in DaVinci Resolve.
Comments and graphical annotations from Dropbox Replay appear as markers
with their corresponding overlays in your DaVinci Resolve timeline.
310Setup and Workflows | Chapter 13 Frame.io and Dropbox Replay Integration
MEDIA
Working With Dropbox Markers
Double-clicking any Dropbox marker in the Timeline opens a dialog that lets you send replies to
comments that appear on Dropbox Replay, enabling editors to respond directly to commenters.
The Dropbox Replay comment dialog that
appears when you open a Dropbox marker
You can also place Dropbox markers on the Timeline to have them automatically sync back to
```
Dropbox Replay, giving you the ability to send your own comments back to commenters (be kind).
```
If you delete one or more Dropbox markers on the DaVinci Resolve timeline, those markers will also be
deleted in Dropbox Replay. This includes the Mark > Delete All Markers > Dropbox command. This is
not undoable
Dropbox Marker Navigation
You can specifically navigate only the markers created in Dropbox Replay while in the comment dialog
```
of a Dropbox marker, using the Previous Marker (Shift-UpArrow) and Next Marker (Shift-DownArrow)
```
commands. This allows you to skip directly from comment to comment in Dropbox Replay without
having to either navigate all markers in-between, or double-click each Dropbox marker individually
to respond.
311Setup and Workflows | Chapter 13 Frame.io and Dropbox Replay Integration
MEDIA
Chapter 14
Resolve Live
The Color page has another mode available to aid you in using DaVinci Resolve in
on-set grading workflows. Turning the Resolve Live option on puts DaVinci Resolve
into a live grading mode, in which an incoming video signal from a camera can be
monitored and graded during a shoot.
Contents
More About Resolve Live  313
Configuring Your System for Resolve Live 313
Setting up your Camera and Hardware for Resolve Live  313
Setting up DaVinci Resolve for Resolve Live  314
Grading Live  316
Going Live 316
Using Freeze  317
Using Snapshot  317
Resolve Live Audio Monitoring  318
Using Resolve Live Grades Later  319
Using LUTs in Resolve Live Workflows  319
312Setup and Workflows | Chapter 14 Resolve Live
MEDIA
More About Resolve Live
Resolve Live has been designed to let you use all of the features of DaVinci Resolve to grade these
on-set video previews, in the process saving video snapshots that contain a captured image, your
grade, and reference timecode from the camera. The idea is that, using Resolve Live, you can work
with the cinematographer to develop looks and test lighting schemes on the footage being captured
during the shoot, and then later you can use those looks to build dailies, and as a starting point for the
final grade once the edit has been completed.
Additionally, you can use Resolve Live in conjunction with other Color page features such as the
Alpha output to build test composites to check green screen shots, comparing them against imported
background images in order to aid camera positioning and lighting adjustments. The built-in video
scopes can also be used to monitor the signal levels of incoming video. Finally, you can use 1D and
3D LUTs to monitor and grade log-encoded media coming off the camera.
Configuring Your System for Resolve Live
Setting up your Camera and Hardware for Resolve Live
Setting up Resolve Live is straightforward. Whether you’re using a tower workstation or a laptop,
any of the Blackmagic Design DeckLink or UltraStudio video interfaces can be used to connect your
DaVinci Resolve workstation to a camera and external video display. The important thing to keep in
mind is that, if you want to connect to a live incoming signal and output that signal for monitoring at
the same time, you need to either use two separate DeckLink PCIe cards or UltraStudio Thunderbolt
interfaces, or a single DeckLink card/Ultrastudio with multiple separate inputs and outputs on a single
PCIe card/device.
During the shoot, the digital cinema camera in use needs to be connected to your DaVinci Resolve
workstation video input via HD-SDI or HDMI, which must be configured to carry both the video image
and timecode that mirrors the timecode being written to each recorded clip. Most cameras allow
timecode output over HD-SDI and HDMI, and both DeckLink and UltraStudio interfaces can pass
this timecode to DaVinci Resolve. Without a proper timecode reference, you won’t be able to take
the shortcut of automatically syncing your saved Snapshots to recorded camera original media using
ColorTrace, although you can always apply grades manually.
Resolve Live hardware checklist:
• Install and update the Blackmagic Design Decklink card or Ultrastudio device you will be
```
using for live video input in your DaVinci Resolve workstation (see your Blackmagic Design
```
```
hardware documentation for specific details).
```
• Connect the video camera’s SDI or HDMI video output to the Blackmagic device’s video
input. Make sure that embedded timecode out of the camera is enabled as well.
• Select the appropriate video input for your device in the Blackmagic Desktop Video Setup
application on your computer.
313Setup and Workflows | Chapter 14 Resolve Live
MEDIA
Video input options in the Blackmagic Desktop Video Setup
```
NOTE: the resolution and frame rate that your camera is outputting through
```
the SDI/HDMI cable.
Setting up DaVinci Resolve for Resolve Live
Once the hardware is set up, you will need to check the configuration of DaVinci Resolve to be able to
make use of the live grading features of Resolve Live.
The first setting is to select the appropriate video input hardware in the Video I/O settings.
The Video I/O panel of the System Preferences provides two sets of options for configuring video
interfaces connected to your computer, one for capture, and one for monitoring. Resolve Live uses the
video hardware input selected in the capture device. You will need to restart DaVinci Resolve if you
modify these settings.
Video input/output options in the System Preferences
Next, you should begin with a new empty project. You should set up the new project’s Timeline and
Video Monitoring settings to match the format and frame rate coming out of your camera.
314Setup and Workflows | Chapter 14 Resolve Live
MEDIA
```
IMPORTANT: You must set up the resolution and frame rate in your new project’s
```
Timeline format and Video Monitoring format in the project’s Master Settings to match the
resolution and frame rate of the video coming out of the camera.
Make sure your Timeline format and Video Monitoring size and frame rate
match your camera’s video output in the Master Settings
Then add a new empty timeline, since the live grading workflow involves capturing live graded
snapshots to an otherwise unoccupied timeline. One recommended way of organizing the live
grades of a shoot is to create one new project per day of shooting. This way, snapshots captured
during shoots using all 24 hours of time-of-day timecode won’t conflict with one another. Also,
separate projects can make it easier to use ColorTrace to copy grades from your live grade
snapshots to the camera original media you’ll be creating dailies from, eventually.
```
TIP: Having an empty Media Pool and Timeline doesn’t mean you can’t install useful
```
LUTs and pre-import reference stills and saved grades to the Gallery, as these can be
valuable tools for expediting your on-set grading.
Once you’ve created your new project, you also need to choose the disk where all snapshots you
take will be saved. By default, snapshots are saved on the scratch disk at the top of the Scratch
Disks list in the Media Storage panel of the System Preferences. They’re automatically saved in a
folder named identically to the current project, inside a folder called Resolve Live.
315Setup and Workflows | Chapter 14 Resolve Live
MEDIA
Resolve Live software checklist:
• Choose the Capture Device for inputting the video signal from the Video Input/Output
options in the System Preferences.
• Create a New Project.
• Make sure your Timeline format and Video Monitoring size and frame rate match your
camera’s video output in the project’s Master Settings.
• Create a New Timeline.
Grading Live
Once your camera and computer are appropriately connected and configured, using Resolve Live
is straightforward. This section describes the live grading workflow as it was designed to be used.
Once you’re familiar with the capabilities of Resolve Live, you may find your own ways of working that
are more in tune to the needs of your particular project.
Going Live
Once you’ve created your day’s project, you need to turn on Resolve Live to begin work.
To turn on Resolve Live:
1 Open the Color page.
```
2 Choose Color > Resolve Live (Command-R).
```
A red Resolve Live badge at the top of the Viewer indicates that Resolve Live is turned on,
and the transport controls are replaced by the Freeze and Snapshot buttons.
A red badge shows that Resolve Live is active and showing incoming video from the camera
316Setup and Workflows | Chapter 14 Resolve Live
MEDIA
At this point, the video from the connected camera should become visible within the Viewer, the
camera timecode should be displayed in the Viewer’s timecode window, and you can begin using all
of the capabilities of the Color page to begin grading whatever is onscreen, including Gallery split-
screens for matching and comparing. The current color adjustments in all palettes are automatically
```
applied to both the image in the Viewer and the video output to an external display (if there is one).
```
While Resolve Live is on, much of DaVinci Resolve’s non-grading functionality is disabled, so when
you’re finished, be sure to turn Resolve Live off.
To turn off Resolve Live, do one of the following:
 Click the Exit button at the bottom left-hand corner of the Viewer.
```
 Choose Color > Resolve Live (Command-R).
```
Using Freeze
```
In Resolve Live mode, the Freeze button (it looks like a snowflake) freezes the current incoming video
```
frame, so you can grade it without being distracted by motion occurring during the shoot. When you’ve
made the adjustment you need, you can unfreeze playback in preparation for grabbing a snapshot.
To freeze incoming video:
```
 Click the Freeze button (that looks like a snowflake).
```
```
 Choose Color > Resolve Live Freeze (Shift-Command-R).
```
The snowflake button freezes the image
so you can grade a particular frame
Using Snapshot
Once you’re happy with a grade, clicking the Snapshot button saves a snapshot of the current still in
the Viewer, the incoming timecode value, and your grade into the Timeline. Snapshots are simply
one-frame clips. They use grades and versions just like any other clip. In fact, ultimately there’s no
difference between the timeline created by a Resolve Live session and any other timeline, other than
that the Resolve Live timeline only has a series of one frame clips, which appear in the Timeline of the
Edit page as a series of 1-frame stills.
To save a snapshot, do one of the following:
```
 Click the snapshot button (with a camera icon).
```
```
 Choose Color > Resolve Live Snapshot (Command-Option-R).
```
The snapshot button saves a frame
and the grade for future use
317Setup and Workflows | Chapter 14 Resolve Live
MEDIA
For example, you may begin the process of building and refining a grade for a particular scene
during an unrecorded run-through. Then, once shooting starts, you may take snapshots of
each shot’s slate, and then of significant takes that follow, tweaking where necessary and in
conjunction with the DP’s feedback once things get going. New camera setups may require
further tweaks, which you’ll save as snapshots for those shots, and as you work in this way
you’ll find yourself building up a timeline of snapshots that correspond to that day’s shoot.
As you work, keep in mind that you must temporarily turn Resolve Live off in order to open a
grade from a previous snapshot in the Timeline, in order to use it as a starting point for another
shot. You can also save grades into the Gallery.
Resolve Live Audio Monitoring
When using Resolve Live, you can now hear the audio signal from the camera coming into the
Decklink or Ultrastudio device as you grade. You can toggle this behavior on or off by clicking on the
speaker icon underneath the Viewer.
Clicking on the speaker icon toggles the audio on and off during a Resolve Live session.
318Setup and Workflows | Chapter 14 Resolve Live
MEDIA
Using Resolve Live Grades Later
Since each Snapshot you capture during a Resolve Live session contains timecode that was captured
from the camera, grades from snapshots with timecode that overlaps recorded camera original media
can be synced using ColorTrace when the time comes to start making dailies.
Keep in mind that snapshot grades correspond to the monitored output of the camera during the
shoot. If you shot using a raw format, you’ll need to use whatever in-camera debayering settings
were used for monitoring during the shoot if you want the grades from your snapshots to produce the
same result.
For more information on using ColorTrace, see Chapter 149, “Copying and Importing Grades
Using ColorTrace.”
Using LUTs in Resolve Live Workflows
```
Many on-set workflows use Lookup Tables (LUTs) to calibrate displays, normalize log-encoded media
```
for monitoring, and preview looks in the video village to test how the current lighting scheme will work
with the intended grade. You can apply LUTs using the Lookup Tables section of the Project Setting’s
Color Management panel, or within a grade as part of a node tree.
However, you can also export LUTs, if necessary for monitor previewing, that you can apply by loading
them into a compatible LUT box of some kind, connected in-between the camera’s video output and a
display, or using a display capable of loading LUTs internally.
If you’re exporting LUTs using the Generate 3D LUT command of the Thumbnail timeline’s contextual
menu, you should limit yourself to using only Primaries palette and Custom Curves palette controls
within a single node. These are the only grading controls that can be mathematically converted
into a LUT.
When exporting a LUT, any nodes that use Windows or OpenFX will be ignored along with all
corrections made within these nodes. All other nodes with Primaries palette and Custom Curves
palette adjustments that can be translated into a LUT will have their combined result translated
```
into a LUT. For any nodes that mix supported and unsupported adjustments for LUT export (such as
```
```
sharpening or blur filtering operations), the unsupported adjustments will simply be ignored.
```
For more information on exporting LUTs, in “Exporting Grades and LUTs” see Chapter 142,
“Grade Management.”
```
NOTE: DaVinci Resolve exports LUTs in the .cube format, which is a DaVinci-developed
```
LUT format, with no relation to the Adobe SpeedGrade.cube format.
319Setup and Workflows | Chapter 14 Resolve Live
MEDIA
Chapter 15
Stereoscopic
Workflows
DaVinci Resolve has robust support for a wide variety of stereoscopic workflows.
Using the built-in tools of the Studio version of DaVinci Resolve, you can edit using
stereoscopic clips, grade the resulting program, adjust each clip’s stereo-specific
properties such as convergence and floating windows, and master stereoscopic
output, all within DaVinci Resolve.
Contents
Stereoscopic Workflows  321
Hardware Requirements for Working in Stereo 3D 321
Setting Up to Display Stereo 3D via SDI 322
Setting Up to Display Stereo 3D via HDMI  322
Supported Stereo 3D Media  323
Using Dual Sets of Media in Any Supported Format 323
Using Stereoscopic OpenEXR Media  323
Using Stereoscopic CineForm Media  323
Creating Stereo 3D Clips From Separate Files  324
Step 1 – Import and Organize Your Media  324
Step 2 – Generate 3D Stereo Clips 324
```
Step 3 – (Optional) Create Optimized Media  326
```
Monitoring Stereoscopic 3D in the Edit Page  326
Converting Clips Between Stereo and Mono  326
Converting Stereo Clips Back to Mono  326
Converting Mono Clips or an Entire Timeline to Stereo  327
Attaching Mattes to Stereo 3D Clips 327
Organizing and Grading Stereo 3D Dailies 328
Step 1 – Create 3D Stereo Clips 328
Step 2 – Edit the New Stereo Clips Into One or More Timelines for Grading  328
Step 3 – Align Your Media  328
320Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Step 4 – Grading Stereo Media  328
Step 5 – Output Offline or Online Media for Editing  330
Conforming Projects to Stereo 3D Media  331
Grading Mastered Stereoscopic Media From Tape  331
Adjusting Clips Using the Stereo 3D Palette  331
Stereo Eye Selection  332
Stereo 3D Geometry Controls  333
Swap and Copy Controls 334
Automatic Image Processing for Stereo 3D 335
Stereo 3D Monitoring Controls  337
Floating Windows  338
Outputting Stereo 3D Media in the Deliver Page 340
Rendering Frame-Compatible Media  340
Rendering Individual Left- and Right-Eye Clips 340
```
Apple Spatial Video (MacOS only)  341
```
Using Apple Spatial Video in DaVinci Resolve 341
Stereoscopic Workflows
Creating a stereo 3D project is a multi-step process that benefits from careful media organization.
This chapter covers how to set up for working on stereoscopic projects, how to import stereoscopic
projects, and how to export stereoscopic media.
First, stereoscopic pairs of clips, i.e., the individual left- and right-eye media files, are imported into the
Media Pool, organized, and then linked together using the “Stereo 3D Sync” command to create a new
set of linked stereo clips. Then, these clips stereo clips can be either edited or conformed to imported
project data using a single Timeline. DaVinci Resolve lets you manage left- and right-eye grades and
sizing in the Color page using the controls found in the shortcut menu of the Thumbnail timeline, and in
the Stereo 3D palette.
If you’re using stereoscopic CineForm media, which contains muxed left-eye and right-eye image data
that can be decoded by DaVinci Resolve, you still need to go through this process, although you’ll be
using duplicate clips to populate Left and Right folders with matching sets of clips.
Hardware Requirements for
Working in Stereo 3D
With DaVinci Resolve on Mac systems, dual 4:2:2 Y’CbCr stereoscopic video streams are output via
SDI from a compatible Blackmagic Design video interface. You can select either Side-by-Side or Line
Mesh output to be fed to your stereo 3D-capable display, depending on its compatibility. Alternately,
if you turn on the “Enable Dual SDI 3D Monitoring” checkbox in the Video Monitoring group of the
Master Settings panel of the Project Settings, your compatible Blackmagic Design video interface
outputs full resolution 4:2:2 Y’CbCr for each eye to compatible displays.
When setting up a 3D-capable DaVinci Resolve workstation, keep in mind that the dual video streams
of 3D projects make greater demands on disk bandwidth, media decoding via your workstation’s CPU,
and effects processing via your workstation’s available GPU cards.
321Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Setting Up to Display Stereo 3D via SDI
All DaVinci Resolve systems can output a side-by-side frame-compatible signal that can be viewed on
a stereo 3D-capable display via a single SDI connection, output from a DeckLink HD Extreme card or
better. For higher-quality monitoring, two SDI signals can be used to output the left-eye and right-eye
images separately at full resolution using one of the following Blackmagic Design video interfaces:
 DeckLink HD Extreme 3D+
 DeckLink 4K Extreme
 DeckLink 4K Extreme 12G
 DeckLink 8K Pro
 UltraStudio 4K
 UltraStudio 4K Extreme
 UltraStudio 4K Extreme 3
Very old legacy systems accomplish this via NVIDIA dual SDI monitoring outputs.
```
NOTE: If your stereo display is not capable of multiplexing the two incoming SDI signals by
```
itself, you can accomplish this using an external device to multiplex both SDI signals into
a single stereo 3G signal that will be compatible. Check with your display manufacturer in
advance to see if this is necessary.
The following procedures describe how to set up stereo 3D monitoring in two different ways.
Monitoring via dual SDI to dual SDI:
1 Open the Master Settings panel of the Project Settings, then do the following:
 Make sure the Use 4:4:4 SDI checkbox is unchecked.
 Turn on the “Use dual outputs on SDI” checkbox.
2 Open the Stereo 3D palette in the Color page, and do the following:
 Set Vision to Stereo.
 Set the Out pop-up menu to None.
```
NOTE: When “Enable dual SDI 3D monitoring” is turned on, split-screen wipes and cursors
```
will not be visible on the grading monitor, nor will you be able to view image resizing.
Setting Up to Display Stereo 3D via HDMI
If your stereo-capable display only has HDMI input, you’ll need to use the HDMI output of a compatible
```
Blackmagic Design video interface that has HDMI 1.4 or better to output stereo 3D signals; see the
```
documentation accompanying your video interface for more information.
322Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Supported Stereo 3D Media
When importing stereo 3D media from other applications, there are two types of media that are
compatible with DaVinci Resolve stereoscopic workflows.
Using Dual Sets of Media in Any Supported Format
When originally shot, the media corresponding to stereo 3D workflows consists of two directories, one
for the left-eye media, and one for the right-eye media. For the most automated workflow possible,
this media must be tightly organized. Each pair of left-eye and right-eye media files in both directories
should have matching timecode, and reel numbers that clearly indicate which are the left-eye shots,
and which are the right-eye shots. When organized in this way, it’s relatively easy to use DaVinci
Resolve to convert each matching pair of clips into the stereo 3D clips that you’ll need to work in
DaVinci Resolve. This process is covered in detail in a subsequent section.
Using Stereoscopic OpenEXR Media
DaVinci Resolve is compatible with stereo OpenEXR files to accommodate professional cinema and
specialty workflows. Stereo OpenEXR clips include the media for both eyes stored as separate parts
so that a single OpenEXR file may output either a single image or stereo 3D images when used with
an application that supports it, such as DaVinci Resolve. This means you can edit stereo OpenEXR
media, grade it, and make all of the stereoscopic adjustments that the Stereo palette of the Color
page supports.
If you import stereo OpenEXR clips to the Media Pool, they will at first appear to be regular non-stereo
clips that output a single image. However, these can easily be converted to stereo 3D clips using the
following procedure.
To set stereo OpenEXR clips to be usable as stereo clips:
1 Import the OpenEXR media to the Media Pool as you would any other clips.
2 Select one or more OpenEXR clips, then right-click the selection and choose “Convert to Stereo”
from the contextual menu. Those clips will now appear with a stereo 3D badge to indicate that
they’re stereo.
Using Stereoscopic CineForm Media
DaVinci Resolve is also compatible with CineForm stereo QuickTime files. CineForm clips encode
```
the media corresponding to both eyes and mux (multiplex) it together in such a way so that CineForm
```
files may output either a single frame of image data, if used in an application that is not capable of
stereoscopic processing, or stereo 3D media when used with an application that is, such as DaVinci
Resolve. This means that you can edit CineForm media using nearly any NLE, export a project via
whatever workflow is convenient, and end up with a stereoscopic project that can be graded in
DaVinci Resolve.
There are two ways of creating CineForm files. One is by using a camera or recording system that
processes dual synchronized video signals to create a single set of CineForm media. The other is to
use the CineForm conversion tools that come with GoPro CineForm Studio to reprocess dual sets of
stereo 3D assets into the CineForm format.
The CineForm codec itself encodes full-frame image data using wavelet compression, at any
resolution, at up to 12-bits, in a choice of RGB, Y’CbCr, or RAW color spaces. DaVinci Resolve is
compatible with CineForm in a QuickTime wrapper using any supported color space, allowing access
to the dual streams of image data that are provided.
323Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
When the time comes to output your program, keep in mind that while DaVinci Resolve can read
CineForm files, CineForm files cannot be rendered out of DaVinci Resolve unless you’ve purchased
an encoding license for OS X or Windows from GoPro. Furthermore, DaVinci Resolve cannot render
Stereoscopic CineForm files.
If you import stereo CineForm clips to the Media Pool, they will at first appear to be regular non-stereo
clips that output a single image. However, these can easily be converted to stereo 3D clips using the
following procedure.
To set stereo CineForm clips to be usable as stereo clips:
1 Import the CineForm media to the Media Pool as you would any other clips.
2 Select the CineForm media you need to convert, then right-click the selection and choose
“Convert to Stereo” from the contextual menu. Those clips will now appear with a stereo 3D badge
to indicate that they’re stereo.
Creating Stereo 3D Clips
From Separate Files
If you’re working with stereo media that was either captured or created as individual left- and right-eye
files, then you need to convert each matching pair of clips into the stereo 3D clips that you’ll need to
work in DaVinci Resolve. This is a two-step procedure.
Step 1 – Import and Organize Your Media
You need to import all of the left-eye and right-eye media into separate bins.
1 Open the Media page, and create three Media Pool bins named “Left,” “Right,” and “Stereo Clips.”
The exact names are not important, but the way the media is organized is.
2 Import all left-eye media into the “Left” bin, and all right-eye media into the “Right” bin. If you’re
importing stereoscopic Cineform media, you still need to create this kind of organization, which
requires you to place duplicates of each clip into each of the “Left” and “Right” bins.
Step 2 – Generate 3D Stereo Clips
Once you’ve organized your media appropriately, you’re set up to synchronize the left- and right-eye
clips using timecode.
1 Create a new bin in the Media Pool, and name it “Stereo Clips.” This is the bin that will eventually
contain the linked stereo clips you’re about to create.
How to organize media for working in stereo 3D
324Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
2 Right-click anywhere within the Media Pool and choose Stereo 3D Sync.
The Stereo 3D Sync dialog appears, with buttons for choosing the left-eye folder, choosing the
right-eye folder, choosing the output folder, and checkboxes for specifying whether to match
reel names and file names, and additional fields for entering characters that identify left- and
right-eye clips.
The Stereo Media Sync window
3 Click the Browse button corresponding to “Choose left eye folder” and then use the hierarchical
list of bins that appears to choose the bin you named “Left.” Follow the same procedure to choose
the right-eye media.
4 Click the Browse button corresponding to “Output folder” and then use the hierarchical list of bins
that appears to choose the bin you named “Stereo Clips.”
5 Choose which matching criteria to use. Ideally, you only need to use whichever one of the three
criteria that apply. The three options are:
Match Reel Name: If the reel names of the left- and right-eye media match, turn this checkbox on.
Match File Name checkbox: If the file names of the left- and right-eye media match,
turn this checkbox on.
Left Identifiers and Right Identifiers fields: If the left- and right-eye clips are identified by a
```
special subset of characters within the file name (for example, “3D_R” and “3D_L”), then you
```
can type each into the appropriate field, and these characters will be used to match the left
and right eyes together.
6 Click Sync.
The original clips in the Left and Right bins disappear, and a full set of Stereo 3D clips appear in
the output bin you selected in step four.
325Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIAFinal stereo clips, ready to be edited and graded
```
Step 3 – (Optional) Create Optimized Media
```
If your stereo media is excessively large, you can create optimized media.
1 Select the stereo clips you’ve created.
2 Right-click one of the selected clips, and choose Generate Optimized Media from the contextual
menu. A window appears showing you ho.w long it will take to finish creating optimized media.
Monitoring Stereoscopic 3D
in the Edit Page
You can now view a Stereoscopic 3D signal directly from the Edit page. Previously, the Edit page
was restricted to left eye for video output monitoring. The Edit Page Viewer itself still shows only
a single eye, but it now displays Stereoscopic 3D video from the Decklink or Ultrastudio video
outputs. The 3D palette in the Color page has the stereoscopic controls to select the stereo viewing
```
options (Side by Side, Anaglyph, Line by Line, etc.), as well as adjusting the convergence and other
```
stereoscopic parameters.
Converting Clips Between
Stereo and Mono
You also have the option of converting clips between mono and stereo 3D using a pair of commands
in the Media Pool.
Converting Stereo Clips Back to Mono
If necessary, you can split one or more stereo clips into mono clips using a single command.
To convert stereo clips into mono clips:
1 Select one or more stereo clips in the Media Pool.
2 Right-click one of the selected clips and choose Split Stereo 3D Clips from the contextual menu.
Afterwards, two new bins are created named Left and Right, containing the individual left- and right-
eye clips that you’ve split apart.
326Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Converting Mono Clips or an Entire Timeline to Stereo
```
Non-stereo clips (for which there are not separate left- and right-eye media files) can be converted into
```
stereo clips either individually or throughout an entire timeline for one of two different reasons:
 You can convert non-stereo clips into stereo for use in a stereo project, so they output properly
along with the rest of a stereo timeline, albeit without adjustable convergence or depth effects.
 If you want to grade an HDR and non-HDR version of your program at the same time, converting
```
non-stereo clips to stereo makes it possible for you to a) manage two separate SDR and HDR
```
```
grades for each clip in a timeline using the left- and right-eye channels, and b) output the SDR and
```
HDR signals separately via your compatible Blackmagic Design interface’s left- and right-eye SDI
outputs when you turn on the “Use dual outputs on SDI” checkbox in the Video Monitoring section
of the Master Settings panel of the Project Settings.
To convert mono clips into stereo clips:
1 Select one or more non-stereo clips in the Media Pool.
2 Right-click one of the selected clips and choose Convert to Stereo from the contextual menu.
Afterwards, that clip appears in the Media Pool as a Stereo 3D clip, and when edited into a timeline,
can expose its controls in the 3D Stereo palette in the Color page.
If you have a timeline full of clips that you’ve just converted into stereo using the above procedure, you
need to take the additional step of setting the Timeline to stereo in order to create stereo grades for
each clip.
To convert a timeline to have stereo grades for
simultaneous HDR/SDR output while grading:
Right-click a timeline in the Media Pool and choose Timelines > Set Timeline to Stereo.
For more information about using stereo timeline workflows for simultaneous HDR and SDR
grading, see Chapter 9, “Data Levels, Color Management, and ACES.”
Attaching Mattes to Stereo 3D Clips
If you have left- and right-eye mattes that need to be attached to stereo clips, the process works
identically to importing mattes for regular clips, except that when you’ve selected a stereo 3D
clip in the Media Pool, you have two matte import commands, “Add As Left Eye Matte,” and
“Add As Right Eye Matte.”
327Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Organizing and Grading Stereo 3D Dailies
A common workflow is the creation of digital dailies within DaVinci Resolve before editing in an NLE.
This provides the editors, director, and producers with the advantage of having more attractive media
to work with, that’s also more comfortable to view if handled with the automatic geometry and color-
matching functions that match the media of each pair of shots together for a preliminary left- and
right-eye balance. The resulting Timelines can then be output to whichever media format is most
convenient to use.
Step 1 – Create 3D Stereo Clips
The very first step in the process of creating dailies is to import all of the left-eye and right-eye media
into individually organized bins, and to then link them together to create stereo 3D clips, as described
in the previous section.
Step 2 – Edit the New Stereo Clips
Into One or More Timelines for Grading
Now that you’ve created a set of Stereo 3D clips, you’re ready to edit them into one or more Timelines
for grading. You can do this by simply creating a new Timeline and deselect the Empty Timeline
checkbox. A new Timeline will be created with the stereo 3D clips you created.
Step 3 – Align Your Media
For the stereoscopic effect to work without causing headaches, it’s critical that both eyes are aligned.
This can be tricky to adjust using manual controls, but is something that can be automatically analyzed.
You can perform stereo 3D alignment to a single clip using the Stereo 3D Palette controls, or you can
```
select a range of clips to align all of them automatically at once. There are two methods of alignment;
```
which is more appropriate depends on the type of geometry issues you have to address.
 Transform Alignment: Analyzes the image and makes vertical and rotational adjustments to line
up the left- and right-eye images as closely as possible.
 Vertical Skew: Analyzes the images and makes a vertical-only adjustment to line up the left- and
right-eye images.
Controls for aligning the left- and right-eye media
Step 4 – Grading Stereo Media
Grade the clips in the Timeline as you would any other digital dailies, with the sole addition of
using the controls in the Stereo 3D palette to control monitoring and manage the adjustments
made to each eye as necessary. The currently selected eye will be reflected in the video scopes.
As when creating any other kind of dailies, you can use LUTs, the Timeline Grade, and individual clip
grading to make whatever adjustments are necessary to create useful media for editing.
328Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Grading Windows
If you’re using windows, The Color group of the General Options panel of the Project Settings has a
checkbox called “Apply stereoscopic convergence to windows and effects” that correctly maintains
the position of a window that’s been properly placed over each eye when convergence is adjusted.
You must turn on a checkbox in the Project Settings
to enable stereo convergence for windows
When this option is enabled, the Window palette displays an additional Transform parameter,
“Convergence,” that lets you create properly aligned convergence for a window placed onto a
stereoscopic 3D clip.
The Convergence control in the
Transform section of the Window palette
After placing a window over a feature within the image while monitoring one eye, you can enable
Stereo output in the Stereo 3D palette and use the Pan and Convergence controls to make sure that
window is properly stereo-aligned over the same feature in both eyes. At that point, adjusting the
Convergence control in the Stereo 3D palette correctly maintains the position of the window within the
grade of each eye.
A convergence-adjusted window in stereo
329Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Matching Media From Left and Right Eyes
To help you manage the visual differences between left- and right-eye clips, there are also three
automatic color matching commands that can be used to batch process as many clips as you need to
adjust at once.
```
 Stereo Color Match (Primary Controls): Uses the Lift/Gamma/Gain controls to match one eye to
```
the other. The result is a simple adjustment that’s easy to customize, but may not work as well as
Custom Curves in some instances.
```
 Stereo Color Match (Custom Curves): Uses the Custom Curves to create a multipoint adjustment
```
to match one eye to the other. Can be more effective with challenging shots.
```
 Stereo Color Match (Dense Color Match): Performs a pixel by pixel, frame by frame color match
```
that is incredibly accurate. This operation is processor intensive, so if you’re going to batch
process many clips, or if you’re matching long clips, you’ll want to make sure you have adequate
time. Because this is such a precise match, it’s recommended to use Dense Color Match after
you’ve used one of the stereo alignment commands.
Controls for matching the grade of
the left and right eye media
Step 5 – Output Offline or Online Media for Editing
When you’re done applying whatever grading is necessary to make the media suitable for editing,
you’ll need to export each clip as separate left- and right-eye clips using the controls of the
Deliver page.
1 Open the Deliver page, and set up your render to output the format of media you require. Be sure
to do the following:
 Set Render Timeline As to Individual source clips.
 Turn on the “Filename uses Source Name” checkbox.
 To render both eyes’ worth of media, choose “Both eyes as” from the Render Stereoscopic 3D
option, and choose Separate Files from the accompanying pop-up menu. Optionally, you could
also choose to render only the left-eye or right-eye media.
```
2 Choose how much of the Timeline to render from the Render pop-up menu in the Timeline toolbar;
```
to render everything, choose Entire Timeline.
3 Click “Add Job to Render Queue.”
4 Click Start Render.
DaVinci Resolve will now render either two sets of left- and right-eye clips, or one set of media
corresponding to the eye you chose.
To make sure that the resulting edited project conforms easily to the originating DaVinci Resolve
project, it’s important to be sure that you render individual source clips, and that you turn on the
“Filename user Source Name” checkbox, in order to clone the timecode, reel numbers, and file names
of the source media.
330Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Conforming Projects to Stereo 3D Media
Since DaVinci Resolve manages stereo via a single set of specially created stereo 3D clips, you can
use the same project import methods to import stereo 3D projects as you would for any other project.
Only a single imported timeline is necessary.
This also means that you can edit stereo projects in NLEs that aren’t otherwise stereo-aware, and
finish them in full stereo 3D in DaVinci Resolve. To do this, you need to make sure that you edit the
left-eye media in your NLE, and then export either an EDL or XML file to conform in DaVinci Resolve.
To conform an EDL to stereo 3D media:
1 Open the Media page, and create the necessary set of stereo 3D clips that will correspond to the
project you’re going to import, as described previously.
Open the Edit page, and then use the Import AAF/EDL/XML command to import your edit.
2 When the Load EDL/XML dialog appears, do the following:
 If importing an EDL, verify that the frame rate is correct, and click OK.
 If importing XML, make sure you turn off the “Automatically import source clips into
Media Pool” checkbox, since you want to relink the imported project to the stereo 3D clips you
created in step one.
The left-eye media timecode and reel information that’s embedded within each stereo 3D clip will
be used to conform the stereo 3D clips with the imported EDL, and you should be ready to work.
Grading Mastered Stereoscopic Media From Tape
If you’ve been handed a stereo 3D muxed tape with a mastered program that needs to be graded,
but you haven’t been given a project file or EDL, you can ingest it as individual left- and right-
eye media files with a supported VTR, such as HDCAM SR with 4:2:2 x 2 mode, by turning on the
“Use left and right eye SDI” checkbox in the Capture and Playback panel of the Project Settings.
When muxed stereoscopic signals are ingested, each eye is separated into individual left-eye and
right-eye image files
Once ingested, you can use Scene Detection to split the left-eye media in one bin, and to create an
EDL, you can use to split the right-eye media in the same way in another bin, so that you can create a
sequential set of stereo clips for grading.
Adjusting Clips Using the Stereo 3D Palette
Once you’ve either created or imported a stereoscopic 3D-identified timeline, you’re ready to begin
```
grading. The left eye will be displayed in the Edit and Color pages by default; however, you can
```
right-click on the Timeline and select Stereo 3D Mode to view the other eye. Most colorists work by
```
grading one eye first (typically the left), and rippling their grades to the other eye, making separate
```
adjustments to each eye’s clips when necessary to match undesirable variation between cameras.
DaVinci Resolve lets you do this automatically.
Setting up stereo 3D media enables the Stereo 3D palette on the Color page. This palette contains all
the controls necessary for working on stereoscopic projects. It provides controls for choosing which
eye to grade, adjusting convergence, swapping and copying grades and media between matching
left- and right-eye clips, auto-processing the color and geometry of left- and right-eye clips to match,
stereo 3D monitoring setup, and controls for floating windows.
331Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Stereoscopic 3D palette
Your project must contain stereo 3D clips in order to open this palette.
For more information on setting up a stereo 3D project, see the “Creating Stereo 3D Clips
From Separate Files” section of this chapter.
Stereo Eye Selection
```
Most colorists work by grading one eye first (typically the left), and rippling their grades to the other
```
eye, making separate adjustments to each eye’s clips when necessary to match undesirable variation
between cameras.
The first three buttons in the Stereo 3D palette let you choose which eye to grade while you’re
working, as well as whether or not to ripple each clip’s grade to the matching opposite-eye
clip. Whenever you switch eyes, the 3D badge above each clip’s thumbnail changes color
```
(blue for right, red for left) and the thumbnails themselves update to show that eye’s media.
```
The Left eye is master
and ganged with the Right
• Left button: Displays the left-eye image and grade.
```
• Ripple Link button: When enabled (orange), all changes you make to the grade of the
```
currently selected eye are automatically copied to the correspondingly opposite eye.
```
When disabled (gray), grades made to the currently selected eye are made independently.
```
• Right button: Displays the right-eye image and grade.
You can also choose which eye you’re viewing and grading by right-clicking a clip’s thumbnail
and choosing Stereo 3D > Switch Eye or by choosing View > Switch Eye To > Left Eye or
Right Eye.
332Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Using Ripple Link When Grading Stereo 3D Clips
You would turn Ripple Link off to suspend rippling when you want to make an individual adjustment
to the grade of one eye to obtain a better match between the two. When you’re finished matching the
two clips, you can turn it back on to resume automatic grade rippling.
Stereo 3D grade rippling is always relative, so differences between the grades that are applied to the
left- and right-eye clips are preserved. In fact, when you add or remove nodes to or from one eye,
the same nodes are automatically added to or removed from the corresponding clip it’s paired with,
regardless of whether or not Ripple Linked is enabled.
```
IMPORTANT: Regardless of whether or not Ripple Link is enabled, local versions created for
```
one stereo 3D-identified clip are automatically available to the paired timeline.
Stereo 3D Geometry Controls
The next group of parameters lets you adjust the geometry of stereo 3D clips. The Pan, Tilt, and
Zoom controls are provided as a convenience, and simply mirror the same parameters found in the
Transform palette’s Input mode, but made specific to the geometry of the left- and right-eye media.
Convergence, Pitch, and Yaw are the three parameters that are unique to the Stereo 3D palette.
Stereoscopic 3D Geometry controls
 Convergence: Adjusts the disparity between the left and right eyes, to define the point of
```
convergence (POC), or the region within the image where the left- and right-eye features are in
```
perfect alignment. If necessary, Convergence can be animated using the Stereo Format parameter
group in the Sizing track of the Keyframe Editor. If you want to adjust convergence in pixels, open
the Stereo 3D palette option menu, and turn on “Show convergence in pixels.”
Features that overlap perfectly in both right- and left-eye clips are at zero parallax, putting that
feature’s depth at the screen plane. Matching features that are divergent in the left- and right-
eye clips have increasingly positive parallax, and appear to be farther away from the audience.
Matching features that are divergent and reversed in the left- and right-eye clips have increasingly
negative parallax, and appear to be closer to the audience than the screen plane.
```
 Linked Zoom button: When enabled (white), both the left- and right-eye clips are automatically
```
zoomed whenever Convergence is adjusted so that both eyes always fill the screen. When
```
disabled (gray), changes to Convergence will cause the opposing left and right edges of each
```
eye’s clip to have blanking intrude.
 Pitch: Pivots the image around the horizontal center plane of the frame.
 Yaw: Pivots the image around the vertical center plane of the frame.
333Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Sizing Repositioning in Stereo 3D
Generally, you’ll want to reposition stereo 3D clips with Ripple Link turned on, but you may
occasionally find yourself needing to make a manual adjustment to one eye in particular with Ripple
Link disabled. As with color adjustments, Sizing adjustments made with Ripple Link disabled are only
applied to the clip in the current Timeline. When Ripple Link is turned on, all Sizing adjustments are
automatically copied to the correspondingly numbered shot of the other stereo 3D timeline.
```
WARNING: It is not advisable to use the Rotate parameter when transforming stereo
```
3D clips. Geometrically, rotation tilts a stereo pair of clips inappropriately, and ruins the
“side by side” convergence that’s necessary to create the stereoscopic illusion.
Protecting Stereo Adjustments When Copying Grades
Each version of a grade has independent stereo adjustments stored along with the Sizing settings.
To prevent accidental overwrite of convergence and alignment data when copying grades from
one clip to another, you can right-click within the Gallery and choose one of the following options to
turn them on:
 Copy Grade: Preserve Convergence
 Copy Grade: Preserve Floating Windows
 Copy Grade: Preserve Auto Align
When enabled, these options let you overwrite a clip’s grade without overwriting specific
Stereo 3D parameters.
```
TIP: Stereo 3D and Sizing settings are processed before node-based corrections in the
```
DaVinci Resolve image processing pipeline.
Swap and Copy Controls
Another set of controls at the right of the Stereo 3D palette lets you swap and copy grades, and swap
clips, in situations where you need to reverse what’s applied to a pair of left- and right-eye clips.
Swap and Copy grades between eyes
 Swap Grade: Exchanges the grades that are applied to the left- and right-eye clips.
 Swap Shot: A checkbox that, when enabled, switches the actual media used by two
corresponding left- and right-eye clips. Useful in situations where the eyes of a stereo
3D clip were mislabeled, and you want to switch the clips without rebuilding both EDLs.
 Copy Right to Left: Copies the right-clip grade to the corresponding left-eye clip.
 Copy Left to Right: Copies the left-clip grade to the corresponding right-eye clip.
334Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Batch Grade Management for Stereo 3D Projects
There are also a series of batch-processing commands that are useful for stereoscopic grading that
are available when you right-click one or more selected clips in the Thumbnail timeline:
 Stereo 3D Batch Copy: Copies every grade from the left-eye clips to the right-eye clips.
 Stereo 3D Batch Sync: Copies grades from one eye to the other only when their node graphs
have the same number of nodes. This prevents you from accidentally overwriting a custom grade
with a different node structure that was necessary to match two eyes for a problem shot.
The Copy Grade, Swap Grade, Swap Shots, Ripple Link, and Switch Eye commands are also available
from the Stereo submenu of the Timeline contextual menu.
Automatic Image Processing for Stereo 3D
It’s common during stereoscopic shoots for minor divergences in geometry and color to appear in
the source footage. To make the process of grading stereo 3D media less onerous, DaVinci Resolve
provides a set of auto-adjustment controls at the right of the Stereo 3D palette that gives you a starting
point for matching left- and right-eye clips together.
Auto align and color match buttons
Options for Auto Processing
You can choose which frame should be used to automatically analyze and process stereo clips using
the Alignment and Matching controls from the Stereo 3D palette option menu. You can choose Auto
Process > First or Middle, depending on what works best for your media.
Auto Process—Stereo Alignment
For the stereoscopic effect to work without causing headaches, it’s critical that both eyes are aligned.
This can be tricky to adjust using manual controls, but is something that can be automatically analyzed.
You can perform stereo 3D alignment to a single clip, or you can select a range of clips to align all of
them automatically at once. There are two options. Which is more appropriate depends on the type of
geometry issues you’re needing to address.
 Transform Alignment: Analyzes the image and makes vertical and rotational adjustments to line
up the left- and right-eye images as closely as possible.
 Vertical Skew: Analyzes the images and makes a vertical-only adjustment to line up the left- and
right-eye images.
To align one or more clips automatically:
1 Select one or more stereo clips in the Thumbnail timeline of the Color page.
2 Choose which frame of each clip you want to use for the analysis by opening the Stereo 3D
palette, clicking the Option menu, and choosing Auto Process > First or Auto Process > Middle.
3 Click either of the Stereo Alignment buttons. The button to the left is for Automatic Transform,
while the button to the right is for Automatic Vertical Skew.
335Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
If you selected multiple clips, then the Stereo Alignment window appears, and a progress bar shows
the remaining time this operation will take.
Auto Process—Color Matching
Due to the design of different stereo 3D rigs, sometimes the color and contrast of one eye’s media
doesn’t precisely match that of the corresponding eye. DaVinci Resolve provides two commands for
quickly and automatically matching two eyes together.
```
 Stereo Color Match (Primary Controls): Uses the Lift/Gamma/Gain controls to match one eye to
```
the other. The result is a simple adjustment that’s easy to customize, but may not work as well as
Custom Curves in some instances.
```
 Stereo Color Match (Custom Curves): Uses the Custom Curves to create a multipoint adjustment
```
to match one eye to the other. The result can be more effective with challenging shots.
```
 Stereo Color Match (Dense Color Match): Performs a pixel by pixel, frame by frame color match
```
that is incredibly accurate. This operation is processor intensive, so if you’re going to batch
process many clips, or if you’re matching long clips, you’ll want to make sure you have adequate
time. Because this is so precise match, it’s recommended to use Dense Color Match after you’ve
used one of the stereo alignment commands.
```
TIP: For the best results, it’s recommended to use automatic color matching in a separate
```
node, independent of other corrections.
Stereo 3D color match works differently depending on whether or not one of the stereo 3D-paired
clips has already been graded. The following procedure shows how to match a pair of left- and right-
eye clips before you make any manual adjustments of any kind.
To match a pair of left- and right-eye clips automatically:
1 Select one or more clips in the Thumbnail timeline of the Color page.
2 Open the Stereo 3D palette, and click one of the three Color Match controls.
The Color Matching window appears, and a progress bar shows the remaining time this operation
will take. You can also use automatic color matching to match an ungraded clip to a paired clip that’s
```
already been graded. This only works for grades consisting of one or more primary corrections;
```
secondary corrections cannot be auto-matched.
To match an ungraded clip automatically to a paired stereo clip that’s graded:
1 To suspend stereo grade linking temporarily:
 Open the Stereo 3D palette, and turn off the Ripple Link button.
 Right-click the Thumbnail timeline, and choose Stereo 3D > Ripple Link > Solo.
2 Make a primary adjustment to a clip in the left-eye timeline to create a simple base grade.
The left-eye clip now has a grade, and the right-eye clip does not.
3 Do one of the following to switch eyes:
 In the Stereo 3D palette, click Right.
 Right-click the Thumbnail timeline again, and choose Stereo 3D > Switch Eye.
This procedure only works when you use the Stereo Color Match commands on the ungraded clip
of a left- and right-eye stereo pair, to match it to the graded clip.
4 To make the match, do the following:
In the Stereo 3D palette, click one of the three color match controls. Both clips should match one
another very closely.
336Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Stereo 3D Monitoring Controls
To output both eyes to a stereo 3D display, you need to click the Vision: Mono or Stereo button, and
then choose a display mode from the Out pop-up menu.
Monitoring controls for Stereo 3D
 Vision: Click a button to choose between Stereo, where both eyes can be displayed in the Viewer
and output to video in a variety of different formats, and Mono, where only one eye is monitored in
the Viewer and your video output interface.
 Out: A pop-up menu that provides different stereo viewing options for previewing stereo 3D
signals in different ways. By default, this option is also linked to the Viewer display Internal Video
Scope options. For detailed descriptions of each stereo 3D viewing mode, see the following
section, “Stereo 3D Output Options.”
 Link button: When enabled, the Viewer and internal video scopes both use the Out pop-up
menu’s option for stereo 3D viewing. When disabled, you can choose different stereo 3D viewing
options for the Viewer and internal video scopes.
 Viewer: Lets you choose a stereo 3D viewing option for the Viewer.
 WFM: Lets you choose a stereo 3D viewing option for the internal video scopes.
 Cbd Size: If any stereo 3D viewing options are set to Checkerboard, this parameter becomes
enabled, and lets you define the size of the checkerboard boxes, in pixels.
Dual 4:2:2 Y’CbCr stereoscopic video streams are output via HD-SDI on selected Blackmagic I/O
devices when you turn on the ”Use left and right eye SDI output” checkbox on the Master Settings
panel of the Project Settings. You can select either Side-by-Side or Line-by-Line output to be fed
to your stereo-capable display, depending on your display’s compatibility.
Stereo 3D Output Options
Additionally, the Viewer and video scopes can be set to display both “eyes” in one of a variety of
different modes.
 Side by Side: Displays both images side by side. Each eye is squeezed anamorphically to fit both
eyes into the same resolution as the GUI viewer.
 Top and Bottom: Displays both images one over the other. Each eye is squeezed vertically to fit
both eyes into the same resolution as the GUI viewer.
```
 Line by Line (Even/Odd): An interlaced mode where each eye is displayed on alternating lines.
```
The thickness of the lines as seen in the Viewer depends on how zoomed in you are.
 Checkerboard: Displays both eyes via an alternating checkerboard pattern. This is an excellent
mode for identifying regions of the image where there’s variation in color or geometry between
the two eyes.
337Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
```
 Anaglyph (B/W): Each eye is desaturated and superimposed via Red/Cyan anaglyph to show the
```
disparity between both eyes in different regions of the image. Left-eye divergence is red, and
right-eye divergence is cyan. Regions of alignment between both eyes appear grayscale.
Anaglyph modes are useful for evaluating the geometric differences between both eyes, as well
```
as for identifying the point of convergence (where both eyes align most perfectly) that places a
```
region of the image at the screen plane.
Red/cyan color coding also identifies the direction of parallax. For any given feature, disparity
```
such that red is to the right and cyan is to the left indicates positive parallax (backward projection
```
```
away from the audience). Red to the left and cyan to the right indicates negative parallax (forward
```
```
projection towards the audience).
```
```
 Anaglyph (Color): Similar to Anaglyph (B/W), except that regions of close alignment are shown
```
in full color. Incidentally, both anaglyph modes can be previewed on ordinary displays using
old-fashioned red/cyan anaglyph glasses, enabling stereo 3D monitoring on non-stereo
3D-capable displays.
 Difference: Superimposes grayscale versions of both eyes using the difference composite
mode. Corresponding left/right-eye pixels that are perfectly aligned appear black, while pixels
with disparity appear white. This mode is extremely useful for evaluating geometric differences
between both eyes, as well as for identifying the point of convergence, without the distraction of
color that the anaglyph modes present.
```
NOTE: Only displays the eye corresponding to the currently selected timeline in the Viewer.
```
However, this option also works in conjunction with the “Use Dual Outputs on SDI” checkbox
in the Master Settings of the Project Settings which, when turned on, outputs each eye to an
individual HD-SDI output of your Blackmagic I/O card.
The Viewer set to display an anaglyph stereo image in color
Floating Windows
Floating Windows are meant to correct for “Window violations,” where elements of the image with
negative parallax, that project forward from the screen plane towards the audience, are cut off by the
edge of the frame. In these instances, differences between the images being shown to the left and
right eyes can result in a visual paradox that’s difficult for viewers to reconcile. Specifically, when a
forward-projecting element is cut off by the left or right edge of the frame, one eye sees things that
the other eye does not.
338Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
```
If the subject is moving quickly, this may not be an issue, but if the cut off (or occluded) element lingers
```
onscreen, it causes problems for viewers that defeat the stereo 3D illusion. The viewer’s binocular
```
vision (or stereopsis) is providing one depth cue, while occlusion is providing a completely different
```
depth cue.
To fix this, you can use Floating Windows to crop the cut off object from the eye on the side of the
object that’s cut off, thus eliminating the portion of the stereo image that is unseen to the other
eye that causes the problem.
Floating Window controls
The objective of using Floating Windows is to manipulate the illusion of the viewer’s “window into
the scene.” In addition to fixing Window violations, it has been proposed that Floating Windows
can be used as a creative tool by manipulating the geometry of this Window to alter subtly the
viewer’s perception of the screen orientation.
 By cropping the right-hand side of the right-eye frame, you also create the illusion that the right
edge of the “window into the image” is tilted farther forward toward the viewer.
 By cropping the left-hand side of the left-eye frame, you create the illusion that the left edge of the
Window is tilted toward the viewer.
 If you crop both the left-hand side of the left-eye frame and the right-hand side of the right-eye
frame, you create the illusion that the entire plane of the “virtual screen” is coming toward you.
 If you apply opposite-angled Windows to the left- and right-eye clips at one or both of the edges
of the frame, it appears to “tilt” the screen toward or away from the viewer.
Animating Floating Windows
Floating Windows can be animated using the Float Window keyframing track, found within the Sizing
track of the Keyframe Editor, to push the edge of the frame in as needed, and then pull it back out
when the partially occluded subject has moved fully into the frame.
For more information about animating keyframing tracks, see Chapter 148, “Keyframing in the
Color Page.”
Floating Windows have the following controls and parameters.
L/R/T/B buttons: Lets you choose an edge to which to apply a Floating Window. Click the
button corresponding to the edge you want to adjust. Each edge has its own position, rotate,
and softness settings.
```
Position: Adds masking to the currently selected edge.
```
```
Rotate: Rotates the currently selected edge, letting you create an angled Window.
```
```
Softness: Feathers the edge of the currently selected edge, letting you create a soft Window that can
```
be less noticeable to viewers.
339Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
To add a Floating Window to fix a Window violation:
1 Choose to which eye you want to add the Floating Window.
 To apply a Floating Window to eliminate a Window violation on the right-hand side of the screen,
click the right eye view.
 To apply a Floating Window to eliminate a Window violation on the left-hand side of the screen,
click the left eye view.
2 Choose which edge you want to adjust by clicking the L or R buttons.
 To eliminate a Window violation on the right-hand side, click R.
 To eliminate a Window violation on the left-hand side, click L.
3 Adjust the Position parameter as necessary to crop the portion along the edge of the selected eye
that’s not visible in the other.
4 Optionally, if you feel that the Window adjustment you’ve just made is too obvious, increase the
Softness parameter to make that edge less noticeable.
Outputting Stereo 3D Media
in the Deliver Page
To render full frame media, you’ll need to render each stereo 3D eye separately using the controls of
the Deliver page, outputting whatever media format is required by the client.
Rendering Frame-Compatible Media
Frame-compatible media has both the left- and right-eye images squeezed anamorphically into a
single media file. To create frame-compatible media, choose the “Both eyes as” option from the
Render Stereoscopic 3D controls at the bottom of the File output options of the Deliver page, and then
choose a method of output from the Mesh Options pop-up menu.
Stereoscopic 3D mesh render options on the Deliver page
You can choose Side-by-Side, Line-by-Line, or Top-Bottom. You can also choose Anaglyph if you want
to output a traditional anaglyph red/cyan stereo 3D image for viewing on any display.
Rendering Individual Left- and Right-Eye Clips
If your workflow requires you to deliver separate sets of left- and right-eye media, this is easily
accomplished by either setting up a render job with “Render Stereoscopic 3D” set to either “Right eye”
or “Left eye,” or selecting “Both eyes as” and choosing the “Separate files” option.
340Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
```
Apple Spatial Video (MacOS only)
```
Recent models of Apple iPhone have a Spatial Video mode that creates 3D videos designed to be
viewed in a VR headset. These spatial videos are automatically recognized by DaVinci Resolve and
allow you to use all of DaVinci Resolve’s features, including the full 3D toolset described above.
```
Grading an Apple Spatial Video in the Color page using Anaglyph (B/W)
```
```
mode (not pictured: goofy 3D glasses on the colorist)
```
Using Apple Spatial Video in DaVinci Resolve
Spatial Video footage recorded on an iPhone is easily transferred into DaVinci Resolve but is only
available on the MacOS version.
To import iPhone Spatial Video footage into DaVinci Resolve:
```
1 On your iPhone, the camera mode must be turned to Spatial Video (not photo) before you record
```
the video.
2 Once the video is finished, find the video in the Photos app and press the Share icon.
3 Now export the spatial video via AirDrop or other method to your computer.
4 Open DaVinci Resolve and import the spatial video clips into the Media Pool as normal.
5 Properly imported spatial video clips will have a 3D icon automatically applied to their thumbnails.
Once imported, you can edit, color, audio mix, and create visual effects using all of DaVinci Resolve’s
toolset, just as if it were normal 3D footage.
Spatial Video clips imported correctly should
have a 3D icon applied on their thumbnails.
341Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Tips for using Apple Spatial Video in DaVinci Resolve:
• Currently Apple Spatial Video is required to be 1080p at 30fps. Ensure your
project settings match this.
• In the 3D tools in the Color page, make sure that the Left/Right eyes and
Convergence are linked.
When exporting a Spatial Video for playback in various VR headsets,
the Deliver page Video Settings should be:
• Format: QuickTime
• Codec: H.265
• Render Stereoscopic 3D: Both eyes as: MV-HEVC
Spatial Video export settings
342Setup and Workflows | Chapter 15 Stereoscopic Workflows
MEDIA
Chapter 16
Using Variables
and Keywords
This chapter describes how to use metadata variables and keywords to help you
manage your clips.
Contents
Using Metadata Variables 344
Where Variables Can Be Used  344
How to Edit Metadata Variables  344
Using Keywords  345
Keyword Dictionary 346
Assign and Apply Favorite Keywords to Clips and Markers  348
343Setup and Workflows | Chapter 16 Using Variables and Keywords
MEDIA
Using Metadata Variables
```
If you’re an enthusiastic user of clip metadata (and you should be), you can use “metadata variables”
```
that you can add into supported text fields that let you reference other metadata for that clip. For
example, you could add the combination of variables and text seen in the following screenshot.
Variables, once they’ve been entered, are represented as graphical tags shown with a background,
while regular text characters that you enter appear before and after these tags.
Variables and text characters entered to create a display name based on a clip’s metadata
As a result, that clip would display “12_A_3” as its name if scene “12,” shot “A,” and take “3” were
```
its metadata. When you do this, you can freely mix metadata variables with other characters (the
```
```
underscore, as in the example above) to help format the metadata to make it even more readable.
```
Be aware that, for clips where a referenced metadata field is empty, no characters appear for that
corresponding metadata variable’s tag wherever it happens to be used.
Where Variables Can Be Used
Metadata variables are extremely flexible, and can be used to procedurally add metadata to several
functions in DaVinci Resolve. Here’s a partial list of where you can use variables.
 Clip names: You can use variables in the Clip Name column of the Media Pool in List view, or in
the Clip Name field of the Clip Attributes window’s Name panel, to use each clip’s metadata to
generate a more readable and useful display name.
 Other metadata fields in the Metadata Editor: You can use variables to reference metadata in
other fields.
 Automatic labeling of stills in the Gallery: You can choose an option from the Color group in the
General Options panel of the Project Settings to “Automatically label Gallery stills” in the Gallery,
and you can use variables to do so.
 Custom text in the Data Burn palette: You can use variables to automatically populate metadata
in different combinations as a window burn.
 The Filename field of the Render Settings in the Deliver page: Using variables, you can
automatically set the name of rendered clips to follow any metadata that’s associated with a
timeline or individual clip. This is especially useful when you want to generate specific file names
when rendering individual source clips.
How to Edit Metadata Variables
Every single item of metadata that’s available in the Metadata Editor can be used as a variable, and
several other clip and timeline properties such as the version name of a clip’s grade, a clip’s EDL event
number, and that clip’s timeline index number can be also referenced via variables.
344Setup and Workflows | Chapter 16 Using Variables and Keywords
MEDIA
To add a variable to a text field that supports the use of variables:
```
1 Type the percentage sign (%) and a scrolling list appears showing all variables that are available.
```
2 To find a specific variable quickly, start typing that variable’s name and this list automatically filters
itself to show only variables that contain the characters you’ve just typed.
3 Choose which variable you want to use using the Up and Down Arrow keys, and press Return to
choose that variable to add.
As soon as you add one or more metadata variables to a field and press Return, the string is replaced
by its corresponding text. To re-edit the metadata string, simply click within that field to edit it, and the
metadata variables will reappear as the graphical tags that they are.
The variable list that appears when you type the % character
To remove a metadata variable:
 Click within a field using variables to begin editing it, click a variable to select it, and press Delete.
Using Keywords
While most metadata in the Metadata Editor is edited via text fields, checkboxes, or multiple button
```
selections (such as Flags and Clip Color), the Keyword field is unique in that it uses a graphical “tag”
```
based method of data entry. The purpose of this is to facilitate consistency with keyword spelling by
making it easy to reference both a built-in list of standardized keywords, as well as other keywords that
you’ve already entered to other clips.
Once added, keywords are incredibly useful for facilitating searching and sorting in the Media Pool,
for creating Smart Bins in the Media and Edit pages, and for use in Smart Filters on the Color page.
Reaping these benefits by adding and editing keywords is simple and works similarly to the method of
entering metadata variables that’s described above.
To add a keyword:
1 Select one or more clips, then click in the Keyword field of the Metadata Editor, and begin typing
the keyword you want to use. As you begin typing, a scrolling list appears showing all keywords
that are available using the string of characters you’ve just typed.
2 To find a specific keyword in the list, start typing that keyword’s name and this list automatically
filters itself to show only keywords that contain the characters you’ve just typed. Choose which
keyword you want to use in the list using the Up and Down Arrow keys, and press Return to
choose that keyword to add.
345Setup and Workflows | Chapter 16 Using Variables and Keywords
MEDIA
3 If you selected multiple clips, don’t forget to click Save or you’ll lose your changes. If you only
selected a single clip, your changes will be saved automatically.
The keyword list that appears when
you type within the Keyword field
As soon as you add one or more keywords, they appear as a graphical tag. To re-edit any keyword,
simply click anywhere within the Keyword field to edit it.
To edit a keyword:
 Double-click any keyword to make it editable, then edit it as you would any other piece of text,
and press Return to make it a graphical keyword tag again.
To remove a keyword:
 Click any keyword to select it, and press Delete.
Keyword Dictionary
DaVinci Resolve comes with a suggested set of built in keywords, but by using the Keyword
Dictionary, you can add a new set of keywords or delete previously entered keywords that no longer
are applicable to your project.
To access the Keyword Dictionary go to Workspace > Keyword Dictionary.
The Keyword Dictionary presents a list of all currently suggested and assigned keywords, a search
field, and the ability to add your own keywords to the list.
Any keyword that you add will be added to both the Project and User keyword dictionaries.
 To switch between Keyword Dictionaries, select Project or User from the menu on the toolbar.
The User Dictionary
The User Dictionary shows keywords that will be remembered and suggested for autocomplete across
all projects in this library. The User Dictionary is always based on the last inputs entered.
The Project Dictionary
The Project Dictionary shows keywords that will be remembered and suggested for autocomplete
for only this project.
You can also Import and Export keywords in .txt format into and out of the Project Dictionary.
This lets you prepare a list of custom keywords in any text editor and import them all at once into the
Keyword Dictionary.
346Setup and Workflows | Chapter 16 Using Variables and Keywords
MEDIA
The Keyword Dictionary
To Import a .txt File into the Keyword Dictionary:
```
1 Create a plain text file (.txt) of your keywords, either one word per line or as comma-
```
separated values.
```
2 In the Keyword Dictionary Option Menu (three dots), select Import Project Dictionary.
```
3 Navigate to your .txt file in the file browser and press Open.
```
You can also export any custom keywords in the Keyword Dictionary to a plain text file (.txt) of your
```
keywords, one word per line.
To Export a .txt File from the Keyword Dictionary:
```
1 In the Keyword Dictionary Option Menu (three dots), select Export Project Dictionary.
```
2 Navigate to where to want your .txt file to be saved in the file browser and press Save.
You can add your own keywords, one at a time as needed, to the Keyword Dictionary.
To Add a Keyword to the Keyword Dictionary:
1 Press the Add Keyword button.
2 Type in the new keyword into the text field and hit return.
The new keyword is initially added to the bottom of the Keyword list for easy access, but
once the Keyword Dictionary has been closed and reopened, the new keyword will appear in
alphabetical order.
You can also remove a keyword from the Keyword list if it is no longer applicable, or misspelled.
347Setup and Workflows | Chapter 16 Using Variables and Keywords
MEDIA
To Delete a Keyword from the Keyword Dictionary:
1 Hover the pointer over the keyword that you want to delete.
2 Press the trashcan icon to the right of the keyword.
The keyword will instantly be removed from the list, and this action is not undoable. Please note
that the default keyword set that comes with DaVinci Resolve cannot be deleted.
Assign and Apply Favorite
Keywords to Clips and Markers
You can now set up to nine keywords as favorites in the Keyword Manager in the Workspace menu.
Simply type your new keyword in the slots on the left of the Keyword Manager to set them.
The nine Favorite Keywords slots in the Keyword Manager
You can quickly assign these keywords to selected clips or in a marker window from the Mark >
Favorite Keywords menu. Or even faster, use the default keyboard shortcuts Option-Shift 0 through 9.
The same menu also has an action to clear all keywords from a clip or marker.
348Setup and Workflows | Chapter 16 Using Variables and Keywords
MEDIAMEDIA
Ingest and
Organize Media
CONTENTS
17 Using the Media Page  350
18 Adding and Organizing Media with the Media Pool  368
19 Using Clip Metadata  408
20 Using the Inspector in the Media Page  423
21 Syncing Audio and Video  437
22 Modifying Clips and Clip Attributes  444
23 Using Scene Detection  457
24 Ingesting From Tape  465
25 Capturing From the Cintel Film Scanner  473
Chapter 17
Using the
Media Page
The Media page is the primary interface for media import and clip organization in
DaVinci Resolve. It’s also where all timelines that you edit in DaVinci Resolve or
import from other applications are organized.
While timelines and clips are both saved in the Media Pool, it’s central to the way DaVinci Resolve
works that the source media used by a project is managed separately from your timelines. In this way,
you can manage and update the clips used by timelines with ease, importing and reorganizing clips,
switching between offline and online media, and troubleshooting any problems that occur.
The Media page also contains much of the core functionality used for on-set workflows, as well
as most of the functions that are used in the ingest, organization, and sound-syncing procedures
corresponding to digital dailies workflows.
Contents
Understanding the Media Page
User Interface  351
The Interface Toolbar 351
Showing Which Panel Has Focus 352
The Media Storage Browser  352
Playing Media in the Media Storage Browser  353
The Media Storage Browser’s Volume List  353
The Media Storage Browser Area  354
Revealing a Finder Location
in the Media Browser  356
Viewer  356
Export The Current Frame from The Viewer  358
Live Media Preview  358
Media Pool  358
The Bin List 359
Showing Bins in Separate Windows  359
Bins, Power Bins, and Smart Bins  360
Filtering Bins Using Color Tags  360
Sorting the Bin List  361
Deleted Timeline Backups 362
Metadata Editor  362
Audio Panel  363
Dual-Monitor Layout  364
Customizing the Media Page  365
Undo and Redo in DaVinci Resolve  366
350Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
Understanding the Media Page
User Interface
By default, the Media page is divided into five different areas, designed to make it easy to find, select,
and work with media in your project.
The Media page
Much of the functionality and most of the commands are found within the contextual menus that
appear when you right-click clips in the Media Storage browser or Media Pool.
The Interface Toolbar
At the very top of the Media page is a toolbar with buttons that let you show and hide different parts of
the user interface. These buttons are as follows, from left to right:
The Interface toolbar
 Media Storage full/half height button: Lets you set the Media Storage browser to take up the full
height of your display, if you need more area for browsing at the expense of a smaller Media Pool.
 Media Storage: Lets you hide or show the Media Storage browser. Hiding the
Media Storage browser creates more room for the Viewer.
 Clone Tool: Shows or hides the Clone tool, used for cloning media from camera cards
or hard drives.
 Audio Panel: Hides or shows the Audio Panel.
 Metadata: Hides or shows the Metadata Editor.
 Inspector: Hides or shows the Inspector Panels.
 Capture: Switches the Viewer and Audio Panel to Capture Mode, exposing the controls necessary
for cuing up a device-controllable deck, and batch recording from tape.
 Audio Panel/Metadata Editor full/half height button: Lets you set the Audio Panel or Metadata
Editor to take up the full height of your display, if you need more area for either of those functions.
351Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
Showing Which Panel Has Focus
Whenever you click somewhere on the DaVinci Resolve interface using the pointer, or use a keyboard
```
shortcut to “select” a particular panel (such as in the Edit page), you give that panel of the user
```
interface “focus.” A panel with focus will capture specific keyboard shortcuts to do something within
that panel, as opposed to doing something elsewhere in the interface.
Disabled by default, checking the “Show focus indicators in the user interface” box in the UI Settings
section of the User Preferences causes an orange highlight to appear at the top edge of the focused
panel, allowing you to keep track of which part of the current page is taking precedence. You can
switch focus as necessary to do what you need to do.
The Focus indicator shown at the top edge of the Media Pool, shown next to a Viewer that doesn’t have focus
The Media Storage Browser
The Media Storage browser lets you see all of the volumes connected to your workstation, browsing
them for media that you want to preview and eventually import into your DaVinci Resolve project in
one way or another. Whereas other applications rely on some sort of import dialog, DaVinci Resolve
provides the Media page for doing complex media import tasks. To facilitate media import, the Media
Storage browser is divided into two areas, the Volume List, and the Media Browser.
Media Storage browser with scrubbable clip view
352Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
Playing Media in the Media Storage Browser
You can select media in the Media Storage Browser to play directly in the Media page Viewer, without
importing it, so long as it’s in a format that DaVinci Resolve supports. This is useful for previewing
clips that you’re considering using in a project, but it’s also useful for quality control review sessions
of media that you’ve exported from DaVinci Resolve. All clips that are played in the Media page
Viewer are also output to video, if you have a supported Blackmagic output interface. You can also
output the video to a second monitor by choosing Workspace > Video Clean Feed, and selecting your
monitor. Additionally, if you choose Workspace > Dual Screen > On, the second computer display is
capable of displaying a set of video scopes on the Media page, which can help you QC a program
you’re delivering.
Playing DCP and IMF Packages
It’s also possible to use the Media Storage Browser to select and play DCP and IMF packages that
have been exported either using EasyDCP or using the native DCP/IMF export capabilities of DaVinci
Resolve. Simply locate the package, select it, and play it in the Viewer like any other clip. It will be
output to video and analyzed by the video scopes.
DCP and IMF packages can also be imported from Media Storage to the Media Pool for
various workflows. For more information, see Chapter 188, “Delivering DCP and IMF.”
The Media Storage Browser’s Volume List
At the left of the Media Storage browser is a list of all volumes that are currently available to your DaVinci
Resolve workstation. It’s used to locate media that you want to import manually into your project.
Scratch volumes: Indicated by a usage statistic to the right of the volume name that lists
how full that volume is, these are disks that you’ve added to the Media Storage panel of the
System Preferences window. The topmost of these scratch disks is used to store Gallery stills
and cache files.
Available volumes: Indicated by disk icons, this is a list of all fixed, removable, and network
volumes that are currently available to your workstation. When the “Automatically display
attached local and network storage locations” checkbox is turned on in the Media Storage
panel of the DaVinci Resolve Preferences, new volumes that are attached to your workstation
should automatically appear in this list.
```
This is a hierarchical list; clicking the disclosure triangle to the left of any volume opens up an
```
additional list of that volume’s subdirectories, with additional disclosure triangles next to each
subdirectory. Using the Media Storage browser, you can drill down into as many subdirectories as
you need to.
Adding Volumes That Don’t Appear in This List
If you need to access a storage volume that doesn’t appear on this list, for example if you’re using the
version of DaVinci Resolve that is available in the Apple App Store, then you can right-click anywhere
in the background of the Volume list and choose “Add New Location” to open a dialog you can use to
choose a volume you want to add.
353Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
If you’re using the Apple App Store version of DaVinci Resolve, auto-mounting of attached storage
volumes is not enabled automatically. However, you can enable this in the Media Storage panel of the
DaVinci Resolve Preferences.
For more information, refer to the DaVinci Resolve Preferences section of see Chapter 4,
“System and User Preferences.”
Media Storage Browser Favorites
Underneath this is the Favorites area. If there are special directories that you find yourself frequently
accessing, you can add them to the Favorites in order to avoid having to traverse complex hierarchies
in order to access the media you need. The Favorites can be easily customized and used.
Methods of organizing favorite file system locations in the Media Storage Browser:
 To add a favorite: Right-click any folder in the Media Storage browser folder list, and choose
“Add folder to favorites” from the contextual menu. The new favorite appears at the bottom of the
Favorites area.
 To open a favorite: Click any favorite to expose the contents of the corresponding directory in the
Media Storage browser.
 To remove a favorite: Right-click the favorite you want to remove, and choose “Remove folder
from favorites” from the contextual menu.
The Media Storage Browser Area
Once you’ve selected a volume or subdirectory in the Media Storage browser, you can view its
contents in List view, Thumbnail view, or Metadata view to search through the media that’s available to
you as you try to find what you need.
List View
In List view, the following columns are available for sorting media prior to importing it into the
Media Pool:
 File name: The name of a file.
 Reel name: The reel name as it’s currently derived according to the Conform Options that are
currently chosen in the General Options panel of the Project Settings.
 Start TC: The first timecode value in the source media.
 Start: The first frame number in the source media.
 End: The last frame number in the source media.
 Frames: The duration of each clip in frames.
 Resolution: The frame size of the source media.
 Bit Depth: The bit depth of the source media.
 Video Codec: The codec used for the video track of supported media.
 Audio Codec: The codec used for the audio tracks of supported media.
 FPS: The frame rate of the source media.
 Audio Ch: The number of audio channels within the source media.
 Date Created: The date a media file has been created.
 Date Modified: The date a media file has been changed in some way and saved.
354Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
 Shot: Additional metadata from media formats that support it.
 Scene: Additional metadata from media formats that support it.
 Take: Additional metadata from media formats that support it.
 Angle: Additional metadata from media formats that support it.
 Good Take: Additional metadata from media formats that support it.
If you work in List view, you gain additional organizational control by exposing columns that show
the metadata that each clip contains, prior to media being added to your timeline. You can use these
columns to help organize your media.
Methods of customizing metadata columns in List view:
 To show or hide columns: Right-click at the top of any column in the Media Storage browser and
select an item in the contextual menu list to check or uncheck a particular column. Unchecked
columns cannot be seen.
 To rearrange column order: Drag any column header to the left or right to rearrange the column order.
 To resize any column: Drag the border between any two columns to the right or left to narrow or
widen that column.
 To sort by any column: Click the column header you want to sort with. Each additional time you
click, the same header toggles that column between ascending and descending sort order.
You can also customize column layouts in the Media Storage area. Once you’ve customized a column
layout that works for your particular purpose, you can save it for future recall.
Methods of saving and using custom column layout:
 To create a column layout: Show, hide, resize, and rearrange the columns you need for a
particular task, then right-click any column header in the Media Pool and choose Create Column
Layout. Enter a name in the Create Column Layout dialog, and click OK.
 To recall a column layout: Right-click any column header in the Media Pool and choose the name
of the column layout you want to use. All custom column layouts are at the top of the list.
 To delete a column layout: Right-click any column header in the Media Pool and choose the name
of the column layout you want to delete from the Delete Column Layout submenu.
The Thumbnail Sort drop-down
in the Media Storage browser
355Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
Thumbnail View
While in Thumbnail view, you can scrub through a clip’s icon to see its contents, and you can also
click the Clip Info drop-down menu at the bottom right corner of any clip’s thumbnail to see an instant
summary of that clip’s vital information, including:
 File name: The name of that file.
 In timecode: The first frame in the source media.
 Out timecode: The last frame in the source media.
 Duration: The total duration of the source media.
 Resolution: The frame size of the source media.
 Frame Rate: The frame rate, in fps, of the source media.
 Pixel Aspect Ratio: The aspect ratio of the source media.
 Codec: Which codec is used by the source media.
 Date Created: The date created metadata from the source media file.
 Flags: Flag metadata applied either by the camera that shot the media,
in the Metadata Editor, or in the Color page Timeline.
```
Also while in Thumbnail view, you can use the Thumbnail Sort drop-down menu (between the Search
```
```
and Option menu) to choose a criteria by which to organize the thumbnails. A wide variety of metadata
```
options appear, including: File Name, Reel Name, Start TC, FPS, Audio Ch, etc. You can also sort in
ascending or descending order.
Revealing a Finder Location in the Media Browser
If you drag a folder from the macOS Finder into the Media Storage browser, the Media Storage
browser will immediately update to show the location of that folder.
Viewer
Clips that you select in any area of the Media page show their contents in the Viewer. The current
position of the playhead is shown in the timecode field at the upper right-hand corner of the Viewer.
The Media page Viewer
356Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
Simple transport controls appear underneath the jog bar, letting you Jump to First Frame, Play
Backward, Stop, Play Forward, and Jump to Last Frame. A jog control to the left of these buttons lets
```
you move through a long clip more slowly; click it and drag to the left or right to move through a clip a
```
frame at a time.
Audio playback can be turned on or off by clicking on the speaker icon, or adjust the level by right-
clicking on the speaker icon and dragging the slider.
To the right of the transport controls, In and Out buttons let you set In and Out points for the current
clip. The clip’s timecode is also displayed at the top right.
A jog or scrubber bar appears directly underneath the image, letting you drag the playhead directly
with the pointer. The full width of the jog bar represents the full duration of the clip in the Viewer.
The Media Viewer has an option menu that looks like three dots in the upper right corner. Clicking on
this menu reveals the options below.
An optional info bar for showing the timecode and duration of a marked section of media
Media Viewer Option menu: Contains the following commands:
 Live Media Preview: Enabled by default, makes it possible for thumbnails that you’re skimming
in the Media Pool to show the skimmed frame in the Viewer. When skimming with Live Media
Preview enabled, the playhead that appears in the thumbnail is locked to the playhead displayed
in the Viewer’s jog bar.
 Show All Video Frames: When available processing power is insufficient to play the clip or clips
at the position of the playhead due to the grade, transforms, or effects that are applied at that
moment in the Timeline, you have the ability to choose exactly how performance in DaVinci
Resolve degrades. When off, DaVinci Resolve prioritizes audio playback at the expense of
dropping video frames when processing power is tight, resulting in a more conventional playback
experience. When on, audio quality is compromised while every frame of video plays in slower-
than-real time to maintain playback.
 Show Timecode Toolbar: The Timecode Toolbar shows the In/Out point timecodes as well as the
total duration set.
 Show Audio Waveforms in Source Clip: When enabled, shows an audio waveform overlay at the
bottom of the Source Viewer that displays the audio over the entire duration of the clip.
 Show Audio Waveforms Zoomed In: When enabled, shows an audio waveform overlay at the
bottom of the Source Viewer with a zoomed in section of the audio surrounding the current
position of the playhead.
 Previous Clip: Goes to the previous clip in the Media Pool.
 Next Clip: Goes to the next clip in the Media Pool.
 Clear Recently Viewed Clips: Clears the memory of the recent clips in the Source Viewer.
 Show Marker Overlays: Enabled by default, markers that intercept the playhead when playback is
paused appear superimposed in the Viewer.
 Markers submenu: When one or more markers are applied to the clip in the Source Viewer, they
appear in this list in chronological order, listed by Name and Note. Choosing a marker from this
menu jumps the playhead to that marker in the Source Viewer.
You can also put the Viewer into Cinema Viewer mode by choosing Workspace > Viewer Mode >
```
Cinema Viewer (Command-F), so that it fills the entire screen. This command toggles Cinema Viewer
```
mode on and off.
357Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
Export The Current Frame from The Viewer
You can now export a still frame from the Viewer in the Media, Cut, and Edit pages.
To Export a Still Frame from the Viewer:
1 Use the Viewer’s playback controls to navigate to the frame you want to export.
2 Select File > Export > Current Frame as Still.
3 Enter the name of the still frame in the File System viewer.
4 Enter the desired format of the still frame in the File System viewer.
5 Click on the Export button.
Live Media Preview
```
Enabled by default, the Live Media Preview setting found in the Viewer options menu (the three-
```
```
dots menu found at the upper right-hand corner of the Viewer) makes it possible for thumbnails that
```
you’re skimming in either the Media Storage browser or Media Pool to show the skimmed frame in the
Viewer. When skimming with Live Media Preview enabled, the playhead that appears in the thumbnail
is locked to the playhead displayed in the Viewer’s jog bar. You can turn Live Media Preview on or off.
When Live Media Preview is on in the Viewer options
menu, skimming thumbnails mirrors to the Viewer
Media Pool
The Media Pool is central to the DaVinci Resolve experience. It contains all of the media that you
import into the current project, as well as all of the timelines you create. It also contains all media that’s
automatically imported along with Projects, Timelines, or Compositions that have themselves been
imported into DaVinci Resolve. In the Media page, enough room is given to the Media Pool to make it
an ideal place to sort, sift through, and organize the clips in your project. However, the Media Pool is
also mirrored in the Cut, Edit, Fusion, Color, and Fairlight pages, so you can access clips as you build
timelines, composites, grades, and sound design.
Media Pool with the Bin list open
358Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
The Bin List
Ordinarily, all media imported into a project goes into the Master bin, which is always at the top of the
Bin list and encompasses everything in a given project. However, you can add bins of your own, and
the Media Pool can be organized into as many user-definable bins as you like, depending on your
needs. Media can be freely moved from one bin to another from within the Media Pool. When working
in projects with multiple bins, you can choose to expose the bin structure in one of two ways:
Bin list open: The Bin List button at the upper left-hand corner of the Media Pool lets you
open a separate List view showing all bins in your project, hierarchically. Bins that contain
other bins appear with a disclosure button to their left, that you can use to show or hide the
contents. With the Bin list exposed, it’s easy to organize clips among a large collection of bins.
Bin list closed: When the Bin list is closed, all bins are hidden, and contents of whichever bin
is currently selected populate the Media Pool browser.
Showing Bins in Separate Windows
If you right-click a bin in the Bin list, you can choose “Open As New Window” to open that bin into its
own window. Each window is its own Media Pool, complete with its own Bin, Power Bins and Smart
Bins lists, and display controls.
This is most useful when you have two displays connected to your workstation, as you can drag these
separate bins to the second display while DaVinci Resolve is in single screen mode. If you hide the
Bin list, not only do you get more room for clips, but you also prevent accidentally switching bins if you
really want to only view a particular bin’s contents in that window. You can have as many additional
Bin windows open as you care to, in addition to the main Media Pool that’s docked in the primary
window interface.
Media Pool bins opened as new windows
359Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
Bins, Power Bins, and Smart Bins
There are actually three kinds of bins in the Media Pool, and each appears in its own section of the
Bin list. The Power Bin and Smart Bin areas of the Bin list can be shown or hidden by using the Media
Pool option menu and selecting/deselecting Show Smart Bins and Show Power Bins. Here are the
differences between the different kinds of bins:
```
Bins: Simple, manually populated bins. Drag and drop anything you like into a bin, and that’s
```
where it lives, until you decide to move it to another bin. Bins may be hierarchically organized,
so you can create a Russian dolls nest of bins if you like. Creating new bins is as easy as right-
clicking within the Bin list and choosing Add Bin from the contextual menu.
Power Bins: Hidden by default. These are also manually populated bins, but these bins
are shared among all of the projects in your current project library, making them ideal for
shared title generators, graphics movies and stills, sound effects library files, music files,
and other media that you want to be able to quickly and easily access from any project. To
create a new Power Bin, show the Power Bins area of the Bin list, then right-click within it and
choose Add Bin.
Smart Bins: These are procedurally populated bins, meaning that custom rules employing
metadata are used to dynamically filter the contents of the Media Pool whenever you select
a Smart Bin. This makes Smart Bins fast ways of organizing the contents of projects for which
```
you (or an assistant) has taken the time to add metadata to your clips using the Metadata
```
Editor, adding Scene, Shot, and Take information, keywords, comments and description text,
and myriad other pieces of information to make it faster to find what you’re looking for when
```
you need it. To create a new Smart Bin, show the Smart Bin area of the Bin list (if necessary),
```
then right-click within it and choose Add Smart Bin. A dialog appears in which you can edit the
name of that bin and the rules it uses to filter clips, and click Create Smart Bin.
Filtering Bins Using Color Tags
If you’re working on a project that has a lot of bins, you can apply color tags to identify particular bins
with one of eight colors. Tagging bins is as easy as right-clicking any bin and choosing the color you
want from the Color Tag submenu.
Using Color Tags
to identify bins
Using Color Tag filtering to
isolate the blue bins
360Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
For example, you can identify the bins that have clips you’re using most frequently with a red
tag. A bin’s color tag then appears as a colored background behind that bin’s name.
Once you’ve tagged one or more Media Pool bins, you can use the Color Tag Filter
```
drop-down menu (the drop-down control to the right of the Bin List button) to filter out all but a
```
single color of bin.
To go back to seeing all available bins, choose Show All from the Color Tag Filter drop-down.
Sorting the Bin List
```
The Bin list (and Smart Bin list) of the Media Pool can be sorted by bin Name, Date Created, or
```
Date Modified, in either ascending or descending order. Simply right-click anywhere within the Bin list
and choose the options you want from the Sort by submenu of the contextual menu.
You can also choose User Sort from the same contextual menu, which lets you manually drag all bins
in the Bin list to be in whatever order you like. As you drag bins in this mode, an orange line indicates
the new position that bin will occupy when dropped.
If you use User Sort in the Bin list to rearrange your bins manually, you can switch back and forth
```
between any of the other sorting methods (Name, Date Created, Date Modified) and User Sort and
```
your manual User Sort order will be remembered, making it easy to use whatever method of bin
sorting is most useful at the time, without losing your customized bin organization.
Dragging a bin to a new position in
the Bin list in User Sort mode
You can now enable waveform thumbnails in the
Media Pool that you can scrub with Live Media Preview.
361Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
Deleted Timeline Backups
From the Media Pool Options menu, you can select Deleted Timeline Backups and examine deleted
timelines and available backup files for each timeline. You can select backups to be restored or
choose to permanently delete selected backups.
Metadata Editor
Both the Media and Edit pages have a Metadata Editor. When you select a clip in any area of the
Media page, its metadata is displayed within the Metadata Editor. If you select multiple clips, only the
last clip’s information appears. The Metadata Editor’s header contains uneditable information about
the selected clip, including the file name, directory, duration, video codec, frame rate, resolution, audio
codec, sample rate, and number of channels.
Because there are so very many metadata fields available, two drop-down menus at the top let you
change which set of metadata is displayed in the Metadata Editor.
```
Metadata Presets (to the left): If you’ve used the Metadata panel of the User Preferences to
```
create your own custom sets of metadata, you can use this drop-down to choose which one to
expose. Surprisingly enough, this is set to “Default” by default.
```
Metadata Groups (to the right): This drop-down menu lets you switch among the various
```
groups of metadata that are available, grouped for specific tasks or workflows.
The heart of the Metadata Editor is a series of editable fields underneath the header that let
you review and edit the different metadata criteria that are available.
For more information on editing clip metadata and creating custom metadata presets, see
Chapter 19, “Using Clip Metadata.”
Clip Metadata Editor showing the Clip Details panel
362Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
Audio Panel
The Audio Panel can be put into one of two modes via an option menu. In the default Meters
mode, audio meters are displayed that show the levels of audio in clips you’re playing. In Waveform
mode, you can open audio clips side by side with video clips in the Viewer in order to sync them
together manually.
For more information on manually syncing audio to video, see Chapter 21, “Syncing Audio
and Video.”
When set to Levels mode, you can check audio embedded within clips you’ve imported into the Media
Pool. As you play a clip, each audio meter shows the levels for whichever of these tracks contain
audio. A Mute button in the Viewer lets you disable and enable audio playback.
Audio Meters Exposed
363Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
Dual-Monitor Layout
The Media page has a dual-monitor layout that provides maximum space for the Media Storage
browser and Media Pool on the primary monitor, and an enlarged Viewer, Audio Panel, and
Metadata Editor on the secondary monitor, along with a complete set of video scopes for helping
you to evaluate media as you organize it. The second screen of a dual-screen layout can be resized
but not reorganized.
If you have an single ultra-wide monitor, you can also use the Dual-Monitor Layout, and
DaVinci Resolve will scale the interface as if you had two normal monitors side by side.
To enter dual screen mode:
Choose Workspace > Dual Screen > On.
The Media page in dual-screen mode
364Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
To switch which UI elements appear on which monitors:
Choose Workspace > Primary Display > Display 1 or Display 2, which reverses the
contents of both monitors in dual screen mode.
Customizing the Media Page
The Media Page can be customized to create more room in different areas
to accommodate specific tasks.
To resize any area of the Media page:
Drag the vertical or horizontal border between any two panels to enlarge one and shrink the other.
Methods of hiding different parts of the Media page:
To toggle the Clone Tool on and off: Click the Clone Tool button in the UI toolbar at the top.
To toggle the Audio Panel on and off: Click the Audio button in the UI toolbar at the top.
To toggle the Metadata Editor on and off: Click the Metadata button in the UI toolbar at the top.
To toggle the Media Storage browser folder list on and off: Click the button at the top-left
corner of the Media Browser.
To toggle the Media Pool Bin list on and off: Click the button at the top-left corner of the Media Pool.
Methods of organizing favorite file system locations in the Media Storage browser:
To add a favorite: Right-click any folder in the Media Storage browser folder list, and choose
“Add folder to favorites” from the contextual menu.
To remove a favorite: Right-click the favorite you want to remove, and choose
“Remove folder from favorites” from the contextual menu.
To return all pages to their default layout:
Choose Workspace > Reset UI Layout.
365Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
Undo and Redo in DaVinci Resolve
No matter where you are in DaVinci Resolve, Undo and Redo commands let you back out of steps
you’ve taken or commands you’ve executed and reapply them if you change your mind. DaVinci
Resolve is capable of undoing the entire history of things you’ve done since creating or opening a
particular project. When you close a project, its entire undo history is purged. The next time you begin
work on a project, its undo history starts anew.
Because DaVinci Resolve integrates so much functionality in one application, there are three separate
sets of undo “stacks” to help you manage your work.
 The Media, Cut, Edit, and Fairlight pages share the same multiple-undo stack, which lets you
backtrack out of changes made in the Media Pool, the Timeline, the Metadata Editor, and
the Viewers.
 Each clip in the Fusion page has its own undo stack so that you can undo changes you make to
the composition of each clip, independently.
 Each clip in the Color page has its own undo stack so that you can undo changes you make to
grades in each clip, independently.
```
In all cases, there is no practical limit to the number of steps that are undoable (although there may be
```
```
a limit to what you can remember). To take advantage of this, there are three ways you can undo work
```
to go to a previous state of your project, no matter what page you’re in.
To simply undo or redo changes you’ve made one at a time:
```
Choose Edit > Undo (Command-Z) to undo the previous change.
```
```
Choose Edit > Redo (Shift-Command-Z) to redo to the next change.
```
```
TIP: If you have the DaVinci control panel, there is one other control that lets you control
```
the undo stack more directly when using the trackballs, rings, and pots. Pressing RESTORE
POINT manually adds a memory of the current state of the grade to the undo stack.
Since discrete undo states are difficult to predict when you’re making ongoing adjustments
with the trackball and ring controls, pressing RESTORE POINT lets you set predictable states
of the grade that you can fall back on.
You can also undo several steps at a time using the History submenu and window. At the time of this
writing, this only works for multiple undo steps in the Media, Cut, Edit, and Fairlight pages.
366Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
To undo and redo using the History submenu:
```
1 Open the Edit > History submenu, which shows (up to) the last twenty things you’ve done.
```
2 Choose an item on the list to undo back to that point. The most recent thing you’ve done appears
at the top of this list, and the change you’ve just made appears with a check next to it. Steps
that have been undone but that can still be redone remain in this menu, so you can see what’s
possible. However, if you’ve undone several changes at once and then you make a new change,
you cannot undo any more and those steps disappear from the menu.
The History submenu, which lets you undo several steps at once
Once you’ve selected a step to undo to, the menu closes and the project updates to show you its
current state.
To undo and redo using the Undo window:
1 Choose Edit > History > Open History Window.
2 When the History dialog appears, click an item on the list to undo back to that point. Unlike
the menu, in this window the most recent thing you’ve done appears at the bottom of this list.
Selecting a change here grays out changes that can still be redone, as the project updates to
show you its current state.
The Undo history window that lets you browse the
entire available undo stack of the current page
3 When you’re done, close the History window.
367Ingest and Organize Media | Chapter 17 Using the Media Page
MEDIA
Chapter 18
Adding and
Organizing Media
with the Media Pool
Before you can edit or grade media, you need to add it to the Media Pool, which is
the central repository of clips in DaVinci Resolve. The Media Pool is a feature-rich
environment, giving you many different methods of importing clips into your project
and organizing them.
Contents
Copying Media Using the Clone Tool  370
Adding Media to the Media Pool  371
Basic Methods for Adding Media in the Media Page  372
Adding Subclips From the Media Storage Panel  373
Adding Individual Frames From Image Sequences  374
Adding Media Based on EDLs  374
Splitting Clips Based on EDLs  375
Import Clips With Metadata Via Final Cut Pro 7 XML  375
Adding Media With Offset Timecode  376
Import Blackmagic Cloud Shared Folders to Media Pool  376
Sync Media Pool Bins with File System Folders  378
Adding Media to the Cut, Edit, Fusion, and Fairlight Pages  380
Removing Media From the Media Pool  380
Removing Unused Media from a Project  381
Adding and Removing External Mattes  381
What Are Mattes For?  383
Adding Mattes  383
Using Embedded Mattes in OpenEXR Files  384
368Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Adding Offline Reference Movies  384
Extracting Audio in Media Storage  385
Manually Organizing the Media Pool  385
To Select Clips in the Media Pool  385
Organizing Media into Bins  385
```
Import and Export DaVinci Resolve Project Bins (.drb)  386
```
```
Import and Export DaVinci Resolve Timelines (.drt)  387
```
Sharing Media Among Projects Using Power Bins 388
Automated Organization Using Smart Bins  389
Smart Bins Are Only As Good As Your Metadata  389
Smart Bins Update Their Contents Dynamically  389
Automatic Smart Bin Creation  390
Manual Smart Bin Creation  391
Organizing Smart Bins  393
Duplicating Clips in the Media Pool  394
Duplicating Timelines  394
Choosing How to Display Bins  395
Showing Bins in Separate Windows  395
Using the Media Pool in Thumbnail View  395
Custom Sort of Clip Thumbnails in the Media Pool 396
Working With Columns in List View  396
Editable Name, Description, Keyword, and Comments Columns  399
Using Metadata View in the Media Pool  400
Finding Clips, Timelines, and Media  402
Finding Clips and/or Timelines Within the Media Pool 402
Finding Synced Audio 403
Finding Timeline Clips in the Media Pool 403
Finding Timelines in the Media Pool  403
Finding Media in the Media Storage Panel and Finder  403
Going Immediately to a File System Location in the Media Browser  404
Tracking Media Usage  404
Thumbnail Clip Usage Indicators  404
List View Clip Usage Column  404
Relinking Media Simply 405
Relink Media  405
Relink Selected Clips  406
Change Source Folder  407
369Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Copying Media Using the Clone Tool
One of the few things you may want to do before you add media to your project is to clone all camera
original media onto a safe set of backup volumes, for redundancy in case any one volume fails.
Additionally, you should consider cloning all media to an off-site backup as well.
Whether you’re on-set working as a DIT, or doing data ingest at a post facility, the Clone Tool in the Media
page lets you safely and accurately copy media from SD cards, SSDs, or disk drives, to multiple destinations,
```
with a checksum report (based on a choice of six checksum options) written to the root of each destination
```
volume that verifies the absolute accuracy of the duplicate media saved to each destination.
To duplicate media using the Clone Tool:
1 Open the Clone Tool by clicking the Clone button at the far left of the Media Pool toolbar, which
reveals the Clone Tool palette.
2 Click the Add Job button at the bottom left to create a new job. A job item appears within the
Clone Tool palette, with overlays to guide you through its use.
3 Drag a volume or folder from the Media Storage panel to the “Drop source here” drop zone. Alternately,
you can right-click any volume or folder in the Media Storage panel and choose Set As Clone Source.
4 Next, drag one or more volumes or folders from the Media Storage panel to the “Drop destination
here” drop zone. Alternately, you can right-click any volume or folder in the Media Storage panel
and choose Set As Clone Destination. You can have more than one destination.
5 If you want to preserve the top level folder name from the source volume or folder, click the Clone
Tool panel’s option menu, and choose “Preserve Folder Name.” The overall folder structure of the
cloned media is always preserved.
6 If you want to change the checksum method used by DaVinci Resolve to verify that each clip
has copied properly, you can choose an option from the Checksum submenu of the Clone Tool’s
option menu. Each option is a tradeoff between the speed of your file copy operation and the
security of the verification process. Greater security generally means a slower copy operation.
The options are:
```
None: Disables data verification, sacrificing safety for speed.
```
File Size: Fast, but minimal data verification. Data verification is done simply by comparing the file
```
size of a duplicate file with that of the original. “Collision resistance” refers to whether two files (or a
```
```
file and an incorrectly duplicated file) may coincidentally have the same comparison value (be it file
```
```
size, an error-detecting code, or a hash). File Size is very fast, but it’s minimally collision resistant.
```
CRC 32: Faster than MD5, but less secure. An error-detecting code rather than the hash used
by the next three options. A “check value” is generated based on the remainder of a polynomial
division of the file’s contents. By comparing the check value derived from an original file with that
derived from a copy, data integrity can be verified. This is a much faster data verification scheme
```
than MD5 (the default), but it is significantly less collision resistant.
```
```
MD5: This is the default setting. A reasonable tradeoff between speed and security. A hash
```
```
function generates a 128-bit value that’s unique to a particular file; Data integrity is checked by
```
comparing the hash value generated by the original file to that generated by the copied file. MD5
is not as collision resistant as the SHA options, but it’s a faster operation, and the probability of
such collisions in conventional film and video workflows is probably small.
SHA 256, SHA 512: Slower, but more secure. SHA is a more collision resistant hash function
```
than MD5; options are provided for 256- and 512-bit value generation, with 512 being even more
```
collision resistant than 256. However, these options are progressively slower than MD5, and will
result in significantly slower copy times. Similarly to MD5, data integrity is checked by comparing
the hash value generated by the original file to that generated by the copied file.
7 When you’re ready, click the Clone button to initiate the cloning process.
370Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
To duplicate media quickly using the Clone Tool:
1 Right-click any volume or folder in the Media Storage panel, and choose Set as Clone Source.
A job item appears within the Clone Tool palette, populated by the volume or folder you selected.
2 Next, right-click any volume or folder in the Media Storage panel, and choose Set As Clone
Destination. You can do this more than once because you can have more than one destination.
3 If you want to preserve the top level folder name from the source volume or folder, click the Clone
Tool panel’s option menu, and choose “Preserve Folder Name.” The overall folder structure of the
cloned media is always preserved.
4 When you’re ready, click the Clone button to initiate the cloning process.
The Clone tool with a job set up
Adding Media to the Media Pool
At minimum, you’ll be using the Media page to add clips to a project to begin editing, in preparation
to create dailies, or as a prelude to conforming a project using an EDL. All clips you want to work with
must first be added to the Media Pool to be available for grading and processing in DaVinci Resolve,
regardless of whether or not there’s edited project data to go along with it.
If you import XML or AAF projects, you can choose to automatically import all accompanying media
as part of the import process you initiate in the Edit page. However, if you find yourself needing to
replace updated effects or stock footage in the Timeline, or you’re called upon to add additional media
such as animated titles or superimposed clips for compositing, then you’ll still need to use the Media
page to do so.
371Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Whatever kind of project you’re working on, you can add clips to the Media Pool from as many different
volumes as you need. All imported clips are linked to the original media on whichever disks you found
```
them; files are not moved, copied, or otherwise transcoded when you add them to the Media Pool.
```
Consequently, it’s a good idea to make sure that all media you want to import into your project has
already been copied to a suitably fast volume before importing it.
Basic Methods for Adding Media in the Media Page
There are several ways of adding clips to the Media Pool.
To add individual clips from the Media Storage panel to the Media Pool:
1 Use the Media Storage panel to find a media file to import.
2 If you have multiple bins available in the Bin list, choose the bin you want to add the
incoming media to.
3 Do one of the following:
Shift-click or Command-click multiple files, then right-click one of the selected files and
choose “Add into Media Pool.”
Drag a clip from the Media Storage panel browser to the Media Pool or to a specific
bin in the Bin list.
4 If a dialog appears asking if you want to change your project to match the criteria, click “Change”
to alter the project’s settings, or click “Don’t Change” to continue importing the media while
leaving the project at its previous frame rate. Once clips have been imported into the Media Pool,
the frame rate cannot be changed again, so choose carefully.
You also have the option of dragging media directly from the file system of supported platforms into
the Media Pool.
```
To drag one or more clips from the File System to the Media Pool (supported platforms only):
```
1 Select one or more clips in your File System.
2 Drag those clips into the Media Pool of DaVinci Resolve or to a specific bin in the Bin list.
Those clips are added to the Media Pool of your project.
If you need to add the contents of all directories and subdirectories to the Media Pool as a flat group
of media, that’s easily accomplished. A good example of this is when you’re importing camera original
media from a cloned file structure, in which clips are organized into subdirectories that are many levels
deep. DaVinci Resolve can easily import all of these clips and put them all into the same bin.
To add the entire contents of one or more directories of clips to the Media Pool:
1 Use the Media Storage panel to find and select one or more directories containing media files you
need to import.
2 If you have multiple bins available in the Bin list, select the specific bin you want to add the
incoming media to.
3 Do one of the following:
Right-click the selected directory or directories in the Media Storage panel, and choose
“Add Folder into Media Pool” to add only clips from the selected directory. Subdirectories
are ignored.
Right-click the directory in the Media Storage panel, and choose “Add Folder and
SubFolders into Media Pool” to add clips from the selected directory and those from all
subdirectories within.
372Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Drag one or more selected directories you want from the Media Storage panel’s browser area
to the browser area of the Media Pool to add its contents, and the contents of all subdirectories
within, to the currently selected bin in the Bin list.
You also have the option of using the directories and subdirectories that organize media in
your file system as bins in the Media Pool, so that you can preserve the original organization
of your media.
To add all clips and folders in a directory organized into matching folders in the Media Pool:
1 Use the Media Storage panel to find the directory containing the files you need to import.
2 Do one of the following:
```
3 Right-click the directory and choose “Add Folder and SubFolders into Media Pool (Create Bins)”
```
4 Drag the folder you want to import from the Media Storage panel to the Bin list of the Media Pool
to add that folder, and all subfolders within, as a new bin in the Bin list.
A folder appears in the Media Pool with the same name as the folder you dragged in. All clips and all
subdirectories appear within, nested hierarchically in the Media Pool as they were in the file system.
Import Hierarchically Organized Nests of Empty Directories
You can also import a nested series of directories and subdirectories that constitutes a default
bin structure you’d like to bring into projects, even if those directories are empty, by dragging
them from your file system into the Media Pool Bin list of a project. The result is a hierarchically
nested series of bins that mimics the structure of the directories you imported. This is useful if
you want to use such a series of directories as a preset bin structure for new projects.
Adding Subclips From the Media Storage Panel
If you’re browsing long source clips in the Media Storage panel, but you only want to import a small
segment of a much longer clip into the Media Pool, you can create subclips directly from the Media
Storage panel.
To add a subclip from a clip in the Media Storage panel to the Media Pool:
1 Single-click any clip in the Media Storage panel to open it into the Viewer in order to create a
subclip without needing to first import that clip into the Media Pool.
2 Set In and Out points in the Source Viewer to define the section you want to turn into a subclip.
3 Do one of the following:
 Right-click the jog bar and choose Make Subclip from the contextual menu
 Drag the clip from the Viewer to the Media Pool to add it as a subclip
373Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Adding Individual Frames From Image Sequences
If you’re working with image sequences, or with sequentially numbered image files from any source,
DaVinci Resolve automatically presents them as clips in the Media Storage panel. This is good if that’s
what they are, but there are instances where sets of photos, of which each frame is in actuality a
separate media file, are also sequentially numbered. For this reason, you can import individual frames,
rather than entire image sequences.
To choose between adding individual frames from a number sequence of images,
or adding them as image sequence clips in the Media Storage panel:
1 Click the Media Storage panel option menu, and choose Frame Display Mode.
2 Close one of the drop-down options:
```
Auto: DaVinci Resolve will automatically select Individual Frames or Image Sequence based on file
```
type. For example, DPX and EXR files will be imported as image sequence clips, while JPG files
will be imported as individual frames.
```
Individual: Each image sequence is now separated into its individual frames, allowing you to
```
select only the frames you need.
```
Sequence: Will group sequentially numbered files together as an image sequence clip, regardless
```
of file type.
3 Use any of the previous described methods to add the frames you want to the Media Pool as
individual clips or image sequences.
Adding Media Based on EDLs
Another strategy for adding media to the Media Pool is to use an EDL to add only the clips it refers
to from a directory. This lets you add only the clips that are necessary for conforming a particular
imported project before conforming an EDL, and eliminates the need to add too much media to
the Media Pool, which might slow you down in the case of projects referencing terabytes of media.
Furthermore, you can choose multiple EDLs to base the import on, and many directories to examine.
The EDLs will reference clips via their timecode and sometimes reel name and path. It is these settings
and the conform frame rate that you made previously in the Configuration screen that are now used to
place images correctly into the Media Pool.
To add only media used in an EDL to the Media Pool:
1 If necessary, open the General Options panel of the Project Settings, turn on the “Assist using
reel names from the” checkbox, and choose a method with which to extract reel name
information from the media files you’re about to import.
For more information, see Chapter 19, “Using Clip Metadata.”
2 Right-click a directory in the Media Storage panel, and choose one of the following commands:
 Add Folder Based on EDLs into Media Pool
 Add Folder and SubFolders Based on EDLs into Media Pool
3 Using the file dialog that appears, select one or more EDLs to use.
DaVinci Resolve searches the directory hierarchy, either one level deep or all levels deep, for every
media file matching the source timecode and the reel ID of an event in one of the selected EDLs.
374Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Splitting Clips Based on EDLs
You can also use EDLs to split a media file into multiple clips in the Media Pool, either as an alternate
means of “preconforming” a flattened master media file, or to import multiple sections of a longer
media file that happen to be referenced by an EDL.
To split and add clips based on an EDL:
1 Right-click a directory in the Media Storage panel, and choose “Split and add into Media Pool.”
2 Using the file dialog that appears, select an EDL to use, and click Open.
3 Choose a frame rate to use to conform the clips to in the “File Conform Frame Rate” dialog,
and click OK.
4 Choose a handle size, in frames, and whether or not you want to split unreferred clips from
the “Enter handle size for splitting” dialog, and click Split & Add. The media file is split into the
component clips specified in the EDL, and added to the Media Pool.
```
TIP: Turning on the Split Unreferred Clips checkbox automatically splits out sections of the
```
file that were not referred to by the EDL you selected, and adds them to the Media Pool
separately, giving you access to every piece of media that’s available.
Import Clips With Metadata Via Final Cut Pro 7 XML
```
In order to support workflows with media asset management (MAM) systems, DaVinci Resolve
```
supports two additional Media Pool import workflows that use Final Cut Pro 7 XML to import clips
with metadata.
To import clips with metadata using Final Cut Pro 7 XML files, do one of the following:
Right-click anywhere in the background of the Media Pool, choose Import Media from XML,
and then choose the XML file you want to use to guide import from the import dialog.
Drag and drop any Final Cut Pro 7 XML file into the Media Pool from the macOS Finder.
Every single clip referenced by that XML file that can be found via its file path will be imported into
the Media Pool, along with any metadata entered for those clips. If the file path is invalid, you’ll
be asked to navigate to the directory with the corresponding media. Additionally, the following
metadata is imported:
 Clips
 Browser metadata
 Subclips
 Clip Markers, with colors and duration
 Bin Hierarchy
 Comments
375Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Adding Media With Offset Timecode
Sometimes source media was created with incorrectly offset timecode, due to mistakes made earlier
in the postproduction process. If this offset is consistent, you can use the “Add Folder with Source
Offset” command to add media to the Media Pool as clips with a timecode offset.
To add a folder of clips to the Media Pool with offset timecode:
1 Right-click a directory in the Media Storage panel, and choose one of the following commands:
 Add Folder with Source Offset
 Add Folder and SubFolders with Source Offset
2 Choose a number of frames with which to offset the timecode from the “Change Frame Offset”
dialog, and click Apply.
The media is imported as clips with offset timecode in the Media Pool. However, the original source
timecode of the clips on disk has not been altered. All media rendered out of the Deliver page will
reflect the offset timecode.
Import Blackmagic Cloud
Shared Folders to Media Pool
You can now import and sync Blackmagic Cloud Folders into the Media Pool. This allows you to
connect to one or more cloud media folders and selectively download media from them to your
local machine. Blackmagic Cloud Folders are online common storage folders that are not tied to a
specific project. This lets you create a pool of commonly used media assets, such as title sequences,
credits, bumpers, etc., and share them online without having to import them separately into each
individual project.
The Import Cloud Folder icon at the top of the Media Pool
To link a Blackmagic Cloud Folder to your project:
1 Sign into your Blackmagic Cloud account in DaVinci Resolve.
2 Click on the Import Blackmagic Cloud Folder icon at the top of the Media Pool in any page.
3 In the Blackmagic Cloud Folder dialog, click select to choose a Blackmagic Cloud Folder. The
choices here will show any Blackmagic Cloud Folder that you have created or someone else has
shared with you. Click the Add button.
4 In the Download Folder Location, select a file location on your local system that you want the
media from the Blackmagic Cloud Folder to be stored in.
5 Choose whether you want to sync proxies only, or proxies and used originals.
6 Press Download to add the Cloud Folder to your Media Pool.
376Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
The Blackmagic Cloud Folder link dialog
When you open the Blackmagic Cloud Folder in the Media Pool, it will be empty and populate
```
one clip at a time as their clip names (not their media) are downloaded from the cloud. Also, the
```
```
Blackmagic Cloud Folder is not actually linked to your project yet; it is only linked when the first
```
media clip is “used.”
A “used” clip is new terminology in DaVinci Resolve and simply means a clip that has been altered
in any way inside the project. A clip can be used be by putting it on a timeline, certainly, but also
includes other actions like applying a flag, altering its metadata, transcribing it, etc. Once a clip is
used, its media will start to download to your local machine. Clips that are used are denoted by a
red dot next to them in the Media Pool. Any unused clips will remain as virtual clips in the Cloud
Folder until used. Once downloaded, clips in Cloud Folders can be used just like any other clip in
the Media Pool.
The Cloud Folder linked in List view. Clips with red dots are “used,” and the original media
has been downloaded. Unused clips have just their proxies available to view. The Cloud
Sync column shows that the media is registered and synced with the Blackmagic Cloud.
377Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Sync Media Pool Bins
with File System Folders
```
You can sync a Media Pool bin with a folder on your computer’s file system (MacOS, Windows, Linux,
```
```
etc.). This allows you to add additional media into a folder on your computer and have it automatically
```
import to its respective bin in DaVinci Resolve.
To set up a folder with Automatic Syncing:
1 On the Cut page, use the Import Folder icon on the top menu bar to set up matching folder and
sub folder names.
2 Right-click on the imported folder and choose ”Automatically Resync Media Files.“
Use the Import Media Folder
icon in the Cut page
Right-click on the bin and select
Automatically Resync Media Files
Newly added clips in this folder will be added automatically to the media bin. This can be useful
```
when working with cloud-synced media files (as when using DaVinci Resolve’s Replay capabilities),
```
or any files that may be added to the folder later.
To manually resync the contents of a Media Pool bin once, right-click a bin and choose
”Resync Media Files.”
Right-click on the bin and select Resync Media Files
to perform the sync operation manually.
For both Resync actions, ensure that:
 At least one clip is present in the media bin.
 All existing clips in the media bin share the same file path.
 The media bin name matches the parent folder of the clip paths. You can ensure this is set up
correctly by using “Import Media Folder” in the Cut page, or “Add Folder and SubFolders into
```
Media Pool (Create Bins)” in the Media page.
```
378Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Sync actions will add new clips from sub-folders if the corresponding sub-bins exist. However, newly
created sub-folders without corresponding media bins are not tracked, and new media bins without
the corresponding sub-folders are skipped.
For example, say you were editing a sporting event, and you had a graphics operator creating
animated lower-thirds for each of the players. By creating a common network folder called “CG” and
automatically syncing it in DaVinci Resolve, each time a new lower-third was finished and saved, it
would automatically appear in your bin in the Media Pool ready for use.
Here’s how you would set this up:
• Create a folder on your network storage called “CG.” Both the editor and the graphics
operator need to have access to this folder.
• Note that because this folder is currently empty, it can not be used in a Resync action yet.
Only after there is at least one media file in the folder can you perform a Resync.
• The graphics operator finishes his first animated lower third and saves it to the “CG”
```
folder as a .mov file (though any DaVinci Resolve readable media format would work).
```
• The editor then imports the “CG” folder into the Media Pool in DaVinci Resolve and selects
Automatically Resync Media Files from the context menu.
• As the graphics operator finishes and saves additional lower thirds into that folder, they
automatically appear in the Editor’s “CG” bin in the Media Pool, without having to specifically
import them.
• For organizational purposes, the graphics operator then creates a new folder in “CG” for
the other team, called “Team B.” Unfortunately, because this folder structure was not in
the original imported bin, it does not show up in the editor’s media pool. However, if they
had created this Team B folder before the editor imported it, and it had media in it, it would
been there.
• Now in this case, the editor simply imports the same bin again, selects Automatically Resync
Media Files, and the new folder and all its media appear as expected. Any further files in
dropped in “Team B” will show up in the editor’s media pool.
```
IMPORTANT: Media entries for clips that are removed or not found on the file system are
```
set as offline media. This allows for retention of metadata and is useful when the clip path is
temporarily offline, on cloud storage where file status may be in flux, or moved away by apps
or workflows seeking to write a new version in its place.
379Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Adding Media to the Cut, Edit,
Fusion, and Fairlight Pages
While adding clips to the Media Pool in the Media page provides the most organizational flexibility and
features, if you find yourself in the Cut, Edit, Fusion, or Fairlight page and you need to quickly import a
few clips for immediate use, you can do so in a couple of different ways.
```
To add media by dragging one or more clips from the Finder to the Media Pool (macOS only):
```
1 Select one or more clips in the Finder.
2 Drag those clips into the Media Pool of DaVinci Resolve, or to a bin in the Bin list.
Those clips are added to the Media Pool of your project.
To use the Import Media command in the Media Pool:
1 Right-click anywhere in the Media Pool, and choose Import Media.
2 Use the Import dialog to select one or more clips to import, and click Open.
Those clips are added to the Media Pool of your project.
Removing Media From the Media Pool
If you’ve added clips to the Media Pool that you need to eliminate, this is easy to do, either singly, or in
the aggregate.
To remove clips from the Media Pool, do one of the following:
 Select one or more clips in the Media Pool, then press the Delete or Backspace key.
 Select one or more clips in the Media Pool, right-click one of the selected clips, and then choose
Remove Selected Clips.
 Right-click anywhere in the Media Pool, and choose Remove All Clips in Bin.
```
NOTE: If you’ve turned on “Automatically match master timeline with media pool” in the
```
General Options panel of the Project Settings, you cannot remove all clips from the Media
Pool if there are other timelines using that media.
```
To remove clips from the Master Timeline (if it’s exposed):
```
 Open the Edit page, then select one or more clips in the Media Pool, right-click one of the
selected clips, and choose “Remove Selected Clips from Master Timeline.”
For more information about using the Master Timeline, see Chapter 33, “Using the Edit Page.”
380Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Removing Unused Media from a Project
You can have DaVinci Resolve automatically remove any unused media clips from the Media Pool in
preparation for archiving or handing off a clean project to another workstation. This action loads all
timelines, compound clips, and Fusion compositions then analyzes them for media usage. Any clips
not found during this analysis are removed from the Media Pool. This option does not delete any clips
from your disk, it only removes them from the Media Pool and the Project. This operation is un-doable.
Depending on the size of the Project, this operation can take several minutes.
To remove unused media from a Project:
```
1 Click on the Media Pool Option (3-dot) menu.
```
2 Select Remove Unused Clips from the drop-down menu.
3 Click on the Load All Timelines button to start the operation, or Cancel to abort it.
Select Remove Unused Clips from the Media Pool Option menu
Click the Load All Timelines button to start the analysis
Adding and Removing External Mattes
If you’ve been provided with matte files to accompany one or more media files used by a program
you’re grading, you can attach them directly to specific clips in the Media Pool, in order to use them as
key sources for a Clip Grade in the Node Editor of the Color page. You can even use matte files that
pack multiple mattes within a single piece of media. This can be done by either writing different mattes
to each of the red, green, and blue channels of a clip, or by embedding multiple matte passes within a
single OpenEXR file.
381Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Matching RGB and Matte images
When the Media Pool is in Icon view, clips with clip mattes appear with a badge.
A clip matte, seen in Icon view
Clip mattes appear listed underneath a clip in the Media Pool when it’s in List view.
A clip matte, seen in List view
Alternately, you can add a timeline matte to the Media Pool, which isn’t attached to any clip,
that can be used as a key source in the Color page within any clip’s Clip grade, or within a
Timeline Grade. Timeline mattes appear as stand-alone clips in the Media Pool.
A timeline matte,
seen in Thumbnail view
382Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
What Are Mattes For?
Matte files are useful for two things. Traditionally, mattes are grayscale media files that identify
regions of varying opacity, with white representing solid areas, and black representing transparency.
For example, exported clips from a compositing application sometimes are accompanied by one or
more matte files that correspond to keys or rotoscoped mattes from the composite. By importing these
matte files using the “Add as Matte” command, you can attach them to the clips they belong to in the
Media Pool, so that they’re only available to the clips they’re synced to.
However, mattes can also be used as creative tools to apply grain and texture for effect. What a matte
does depends on how you connect it in the Node Editor of the Color page. These are media files that
you may want to use as mattes for potentially any clip, so they can also be added to the Media Pool as
a so-called timeline matte, that can be applied to any clip you want.
```
TIP: If necessary, you can also apply LUTs to both clip mattes and timeline mattes in
```
the Media Pool, simply by right-clicking a matte, and choosing a LUT from the 1D LUT or
3D LUT submenus. This can be helpful for adjusting incorrectly formatted mattes.
Adding Mattes
To use mattes, you need to add them in very specific ways.
To assign a matte to a clip in the Media Pool:
1 Select a clip in the Media Pool to which you want to attach an external matte.
2 Select the matching external matte file in the Media Storage panel, right-click it, and choose
Add to Media Pool as a Matte.
The matte is attached to the clip as a clip matte. A badge indicates that clip has a matte when the
Media Pool is in Icon view, and the matte itself can be seen, if you put the Media Pool into List
view, appearing as a nested item underneath the clip it’s attached to.
Removing mattes from clips in the Media Pool:
1 Put the Media Pool into List view.
2 Right-click the external matte file you need to remove, and choose Remove Selected Clips.
Removing an external matte clip also removes that matte’s key from any clip grades that use
it, such that any clips using it as a key input change from a secondary operation to a primary
operation, where the color adjustment affects the entire image.
To add a timeline matte to the Media Pool:
1 Make sure no clip is selected in the Media Pool.
2 Select an external matte file in the Media Storage panel, right-click it, and choose Add to Media
Pool as a Matte.
The external matte appears in the Media Pool as a timeline matte.
You can also assign mattes to clips directly in the Color page, which can sometimes be faster.
383Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
To assign a matte to a clip in the Color page:
 Drag any clip from the Media Pool to the Node Editor.
That clip appears an an External matte for the current clip’s grade in the Node Editor, and it’s also
automatically assigned to the current clip in the Media Pool.
For more information on using external matte clips as keys when grading, see Chapter 146,
“Combining Keys and Using Mattes.”
Using Embedded Mattes in OpenEXR Files
If you’re importing OpenEXR files with embedded matte passes, there’s nothing special you
need to do, as the mattes are within the clip you’ve just imported into the Media Pool.
For more information on how to use mattes within OpenEXR files, see Chapter 146,
“Combining Keys and Using Mattes.”
Adding Offline Reference Movies
When moving a project from another application to DaVinci Resolve, it’s useful to export the entire
program as a single media file for use as an Offline Reference Movie. Then, you can import this file
in a special way to use for dual Viewer comparison in the Edit page, or as a split-screen comparison
for fade wipe in the Color page. As of DaVinci Resolve 16 it’s no longer necessary to import reference
movies in this way to make an offline comparison, but it can still be convenient when managing
multiple timelines and versions that require great specificity.
To add a clip as an offline reference clip:
Right-click it in the Media Storage panel, and choose “Add As Offline Clip.”
That clip appears with a small checkerboard badge in its icon in the Media Pool, or as the icon
to the left of the Media Pool.
Checkerboard icon indicating
an Offline comparison video
For more information on using an offline video to compare with an imported Timeline in the
Edit page, see Chapter 55, “Preparing Timelines for Import and Comparison.”
For more information on split-screen reference of Offline video in the Color page, see Chapter
124, “Using the Color Page.”
384Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Extracting Audio in Media Storage
If there’s a video clip in the Media Storage panel that has audio you need, but you don’t want the video
component, you can use the Extract Audio command to create a self-contained audio clip that you can
then import into the Media Pool by itself.
To extract the audio from a media file:
1 Right-click a clip in the Media Storage panel, and choose Extract Audio.
2 Click the Browse button in the Extract Audio dialog to find another disk location for the
extracted clip.
3 Click Extract. The audio channels are extracted and written as a .WAV file to the selected
destination.
4 After you’ve extracted the stand-alone .WAV file, you’ll need to import it into the Media Pool if you
want to use it in your project.
Manually Organizing the Media Pool
Whether you’re doing onset work, creating digital dailies, organizing media to edit, or ingesting media
to conform to an imported project, it’s vitally important to stay organized. The Media Pool provides
many different tools for doing so. This section examines how you can create bins to manually organize
collections of clips.
To Select Clips in the Media Pool
There are a variety of ways you can make clip selections in the Media Pool in preparation for relinking,
unlinking, moving, duplicating, deleting, or doing any other operation to them.
• Click any clip to select it.
• Drag a bounding box around several clips to select them all.
• Hold the Command or Shift keys down and drag a bounding box around another
discontiguous group of clips to either add them to the current selection or remove them
from the current selection.
• Click one clip, then Shift-click another to select both clips and make a continuous selection
of all clips in-between. Shift-clicking another clip can expand or contract the selection.
• Command-click individual clips to select a discontiguous number of clips. Command-
click a clip that’s already selected to individually de-select it, while leaving the rest of the
selection alone.
• With one clip selected, hold the Shift or Command keys down and use the Arrow keys to
expand the selection to other clips.
Organizing Media into Bins
You can easily organize clips into different bins in the Media Pool. For some workflows, this is required,
while with other workflows it’s purely optional.
385Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Methods of working with bins in the Media Pool:
 To add a bin to the Media Pool: Right-click in the Bin list and choose Add Bin. To add a bin inside
another bin, right-click any bin and choose Add Bin.
 To move selected clips into a new bin: Select all the clips you want to put into a new bin, then
right-click one of the selected clips, and choose Create Bin With Selected Clips.
 To rename a bin: Select the bin you want to rename, and then click its name a second time to
make it editable. With the bin name highlighted, type a new name and press Return. Alternately,
you can right-click a bin, choose Rename Bin, and then type a new name and press Return.
 To add incoming clips to a specific bin in the Media Pool: Click a bin to select it, then use any of
the previously described methods to add media from the Media Storage panel directly to that bin.
 To move media from one bin to another: Drag one or more selected clips from their current
location in the Media Pool into that bin. Multiple clips in the Media Pool can be selected by
Shift-clicking or Command-clicking them, or by dragging a bounding box over a group of clips.
You can also drag one bin into another one.
 To delete a bin: Select the bin you want to delete, and press the Backspace or Delete key.
Or, right-click a bin and choose Delete Bin. Deleting a bin with nested bins inside of it results in
that entire set of bins being deleted.
 To sort bins: Right-click on any bin, and choose an option from the Sort By submenu. You can
choose from Name, Date Created, Date Modified, and User Sort.
 To reorganize bins manually: Right-click anywhere within the Bin list, and choose Sort By
> User Sort. Then, drag bins up or down in the Bin list to put them into the order you want.
An orange dividing line shows where dragged bins will be placed when you drop them and helps
you see when a bin you’re dragging will become nested within another bin or not. The User Sort
order is saved even when you change to another sort order, and selecting User Sort again results
in your custom sort order being recalled.
Import and Export DaVinci Resolve
```
Project Bins (.drb)
```
You can import/export specific bins from one DaVinci Resolve project to another, allowing you to pass
bins quickly between projects and workstations that have access to the same media. All Metadata,
In/Out points, Timelines, etc. are transferred along with the clips in the bin, but none of the actual
media files are included.
To export bins from the Media Pool:
1 Select one or more bins in the Media Pool.
2 Right-click the selection and choose “Export Bin,” or choose File > Export > Export Bin.
```
3 Choose where to save the DaVinci Resolve Bin file (.drb) in the file system dialog, and click Save.
```
To import bins into the Media Pool:
1 Right-click in the Media Pool and choose “Import Bin,” or choose File > Import > Import Bin.
2 Do one of the following:
```
 Choose a DaVinci Resolve Bin file (.drb) from the file system dialog.
```
 Double click the .drb file in your file system.
386Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
The bin or bins will appear in the Media Pool. Any bins imported this way will have the word “import”
appended to their name, to avoid duplicate names. If you import a bin that contains clips that were
already in the Media Pool, the potentially duplicate clips are excluded from the import and instead
relinked to the media referenced by your project. This keeps your Media Pool tidy. However, if the bin
or bins have been moved to another computer, you may have to relink offline media.
Import and Export Power Bins
```
You can import and export Power Bins (bins that persist from project to project) as .drb files,
```
just like normal bins. Power Bins are hidden by default and can be turned on by clicking on the
```
Media Pool Option (3-dot) menu and selecting Show Power Bins.
```
Import and Export
```
DaVinci Resolve Timelines (.drt)
```
You can export and import individual timelines from one DaVinci Resolve project into another
previously existing DaVinci Resolve project, allowing you to pass timelines quickly between projects
and workstations, without creating additional imported project files. Just the timeline and its
associated clip information is exported, none of the actual media files are included.
To export a timeline from the Media Pool:
1 Select a timeline from the Media Pool.
```
2 Choose File > Export > Export AAF, XML, DRT (Shift-Command-O).
```
```
3 Choose “DaVinci Resolve Timeline Files (*.drt)” from the format options popup
```
in the file system dialog.
```
4 Choose where to save the DaVinci Resolve Timeline file (.drt) in the file system dialog,
```
and click Save.
To export multiple timelines from the Media Pool:
1 Select multiple timelines from the Media Pool.
2 Right-click on a timeline and choose Timelines > Export > DaVinci Resolve Timeline Files.
3 Select the folder where you wish to save them from your file browser.
Unlike exporting individual timelines, when exporting multiple timelines you will not be able to rename
the .drt files on export. They will retain the timeline name they have in the Media Pool.
To import a timeline into the Media Pool:
1 Choose a bin in the Media Pool in which you want the imported timeline to be saved.
2 Do one of the following:
```
 Choose File > Import Timeline > Import AAF, XML, DRT (Shift-Command-I), then Select a DaVinci
```
```
Resolve Timeline file (.drt) from the file system dialog, and click Open.
```
 Double click the .drt file in your file system.
387Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
The timeline will appear in the Media Pool, along with all of the clips associated with it, including
any media sync information. Any timelines imported this way will have the word “import” appended
to their name, to avoid duplicate names. The imported timeline will be automatically conformed to
corresponding media that’s already in the Media Pool. However, if the timeline has been moved to
another computer, you may have to reimport or relink missing or offline media in to bring the imported
timeline fully online.
```
NOTE: Only a single timeline can be imported and exported at a time using this method.
```
To import or export multiple timelines, use the Import/Export Bin function described above.
Sharing Media Among
Projects Using Power Bins
Power Bins provide a way of importing and organizing media that you want to be available to all
projects in DaVinci Resolve. Power Bins reside in a separate area of the Media Pool, with resizable
dividers separating them from both the ordinary bins and Smart Bins areas. Power Bins are
hierarchical, just like regular bins, and you can nest as many as you like, one inside another.
Like regular bins, Power Bins must be manually created by right-clicking within the Power Bins area
and choosing Add Bin. The difference is that whatever clips you import into Power Bins are shared
among all projects in a single-user installation, or all projects belonging to a particular user in a multi-
user installation. In this way, they’re similar to Power Grades in the gallery of the Color page. This
makes Power Bins ideal for storing shared media that’s re-used often, such as stock video, sound
effects, stills, and things like company slates and network graphics and animations that go into every
show of a series.
The Power Bins area of the Bin list
388Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Power Bins are created and used like any other bin, using the procedures
described previously.
To show or hide the Power Bin area of the Bin list:
Choose Show Power Bins from the Media Pool option menu to toggle the visibility of all power
bins on and off.
Automated Organization Using Smart Bins
A completely automated way of organizing media in the Media Pool is to use Smart Bins that are either
automatically or manually created, in order to collect all clips and timelines in the Media Pool that have
commonalities based on any of the intrinsic or user-editable metadata that’s available in the Metadata
Editor and Media Pool. If you’re familiar with the Color page, Smart Bins work much the same way as
Smart Filters, and they’re created and edited using much the same procedures.
For more information about Smart Filters, see Chapter 124, “Using the Color Page.”
Smart Bins are incredibly flexible. Using one or more metadata-based rules, they can be as simple
or sophisticated as you require. They’re even capable of using multiple groups of multiple rules for
situations where you need to gather clips that match all of one set of criteria, but only one of a second
set of criteria. In this way, you can use Smart Bins to solve a wide variety of organizational needs as
you edit your program.
Smart Bins Are Only As Good As Your Metadata
It’s important to point out, however, that as much intrinsic metadata is available to every clip in DaVinci
```
Resolve automatically (clip properties such as frame rate, frame size, codec, file name, and so on), the
```
more time you take entering extra metadata in the Metadata Editor to prepare your project for editing
and grading, the more powerful Smart Bins can be in helping you to sift and sort through the contents
of a program you’re grading. Examples of metadata entry that will guarantee immediate benefits from
Smart Bins include the entry of scene, shot, and take information, keywords identifying key descriptors
```
(day and night, interior and exterior, framing, and so on), and using Face Detection to assign character
```
names. These categories of metadata can be used for the automatic creation of Smart Bins, but they
can also be used in combination when manually creating Smart Bins that are even more specific.
Imagine being able to gather all the clips in a particular scene, find all the interview clips for a particular
subject, or find all the edited timelines corresponding to a particular name, all by simply selecting a
Smart Bin that automatically examines the current contents of the Media Pool. If you or an assistant can
take the time to enter metadata for the source material in a project that identifies these characteristics,
you’ll be able to work even more quickly to find the clips you need for any given situation.
Smart Bins Update Their Contents Dynamically
Smart Bins are always dynamically up to date and include whatever new media is added to the Media
Pool. This makes it easy to stay organized, even when working on projects where new media is being
added to the Media Pool every day, such as when editing during a shoot. By using metadata entered
either in-camera, by the DIT or media wrangler managing ingest, or by an Assistant Editor who’s
working with you, Smart Bins will automatically include all clips in the Media Pool that have matching
criteria, whether they were added a month ago or a minute ago.
389Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Automatic Smart Bin Creation
The process of adding metadata to your clips can be used for the automatic creation of sets of “Smart
Categories,” which are Smart Bins that are generated and organized by the presence of specific
categories of metadata and appear in the Smart Bins section of the Media Pool sidebar. To enable or
disable this behavior, open the Editing panel of the User Preferences, and use the checkboxes in the
Automatic Smart Bins group to choose which metadata automatically creates Smart Bins.
Preferences governing what metadata can automatically create Smart Bins
Metadata capable of creating Smart Bins include:
 Clip Keywords
 Marker Keywords
```
 People Keywords (added via People Detection)
```
 Scene metadata
 Shot metadata
These categories are hierarchically organized, with each category closed by default to save space.
Click the disclosure triangle of any category to reveal all Keyword, People, Scene, or Shot Smart Bins
that are available in the current project. Selecting the Smart Category’s top bin lets you see every clip
referenced by every Smart Bin inside of it, whereas selecting individual Smart Bins shows you only the
clips referenced by that Smart Bin.
A Smart Category seen in the Smart Bins
area of the Media Pool sidebar
Drag and Drop Clips to Assign Automatic Smart Bin Properties
Metadata entry does not need to be a one way process, starting with typing in the metadata editor.
```
For certain Automatic Smart Bin categories (keywords, shot, and scene), you can drag multiple clips
```
from the Media Pool on top of an existing smart bin to assign the properties of that bin to all the
clips at once.
390Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
To automatically assign Smart Bin Properties to a range of clips:
1 Create a Smart Bin in one of the following categories: Keywords, Shot, or Scene.
2 Select all of the clips that you want to apply the Smart Bin property to.
3 Drag those clips from the Media Pool and drop them on top of the Smart Bin.
For example, you could make a smart bin with the Keyword: “Sunset.” That bin would
automatically show up under the Keywords category in the Smart Bins. Then you could select
all the sunset shots in your Media Pool, and drag them on top of that bin to apply the “sunset”
keyword to all the clips at the same time.
```
NOTE: Dragging and dropping clips to assign Smart Bin properties only works with the
```
Automatic Smart Bin Keywords, Shot, or Scene categories. Dragging clips to any other Smart
Bin will have no effect.
Manual Smart Bin Creation
It’s easy to manually create Smart Bins with customized rules to filter very specific collections of media
and timelines that you want to use.
To show or hide the Smart Bin area of the Bin list:
 Choose Show Smart Bins from the Media Pool option menu to toggle the visibility of
all Smart Bins on and off.
To create a Smart Bin:
1 If necessary, open the Bin list, choose Show Smart Bins from the Media Pool option menu, then
right-click anywhere in the background of the Smart Bin area of the Bin list, and choose Create
Smart Bin.
2 In the Create Smart Bin dialog, enter a name for the filter, and use the following controls to create
```
one or more filter criteria (you can have as many filter criteria as you like):
```
The Create Smart Bin dialog
 Show in all projects checkbox: Lets you create a persistent Smart Bin that appears in all projects
in your project library. Smart Bins created this way will be found in the User Smart Bins folder
inside every project’s Smart Bin area in the Media Pool.
 Match options: For multi-criteria filtering, choosing All ensures that every single criteria you
specify is met for a clip to be filtered. Choosing Any means that if only one out of several criteria is
met, that clip will be filtered.
391Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
 Filter criteria enable checkbox: Lets you enable or disable any criteria without having to delete it.
 Metadata category drop-down: Lets you choose which category of metadata you want to select
a criteria from. Each category of metadata that’s available in the Metadata Editor is available from
```
this drop-down menu. Additionally, Color Timeline Properties (containing many properties unique
```
```
to the Color page timeline) and Media Pool Properties (containing every column in the Media Pool)
```
provide access to additional metadata you can use for filtering.
 Metadata type drop-down: For choosing which exact type of metadata to use, of the options
available in the selected metadata category.
 Metadata criteria drop-down: Lets you choose the criteria by which to filter, depending on
the metadata you’ve selected. Options include “true/false,” integer ranges, date ranges, string
searches, flag and marker colors, et cetera.
 Add filter criteria button: Lets you add additional criteria to create multi-criteria filters. You could
use multiple criteria to, for example, find all exterior clips, that also contain the keyword “Sunset,”
that aren’t closeups, in order to find all the exterior long and medium shots in sunset lighting.
Additionally, if you Option-click this button, you can add a nested match option in order to create
even more sophisticated filters, such as when the filter must match all of one set of criteria, and
any of another set of criteria.
A complicated Smart Bin with multiple criteria and a second match option setting
As you’re editing the filter criteria, the thumbnail timeline automatically updates to show you how
the Smart Bin you’re creating is working.
3 When you’re done editing the filter criteria, click Create Smart Bin. The resulting Smart Bin appears
in the Smart Bin area of the Bin list, at the left of the Media Pool’s browser area.
Once you’ve created a Smart Bin, it appears in the lower half of the Media Pool’s Bin list, alongside
every other Smart Bin in that project. This keeps them organized, separate from the manually created
bin shown above.
All Smart Bins appear together at the
bottom of the Media Pool’s Bin list
392Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Once you’ve created a Smart Bin, you can re-edit it whenever the situation requires.
Methods of modifying existing Smart Bins:
 To rename a Smart Bin: Right-click the Smart Bin you want to rename, choose Rename from the
contextual menu, enter a new name, and press Return.
 To edit a Smart Bin: Double-click the Smart Bin, then edit the filter criteria, and click OK.
 To duplicate a Smart Bin: Right-click any Smart Bin and choose Duplicate from the contextual
menu. This is a good way to create multiple variations of a Smart Bin that you created with
complex rules, where you need to create variations by modifying those rules without needing to
reinvent the wheel each time.
 To delete a Smart Bin: Right-click the Smart Bin you want to delete, choose Delete Smart Bin from
the contextual menu, and click Delete in the warning dialog. Deleting a Smart Bin does not delete
any gathered media associated with that bin.
Smart Bins Work Better With Metadata
Keep in mind that the more metadata you associate with each clip, the more methods
```
you have at your disposal for creating custom Smart Bins (for editing) and Smart Filters
```
```
(for grading) with which to zero in on the clips you need for any given situation. This will not
```
only make it easier to find what you need, but it’ll help you to work faster. At the very least,
it would be valuable for you to use the Metadata Editor to add information to each clip such
as a Description, Shot and Scene designations, take information, and possibly some useful
keywords such as character names, shot framing, interior or exterior keywords, and so on.
For example, if you’ve entered enough metadata, then you can create multi-criteria Smart Bins
or Smart Filters that let you find the equivalent of “every close-up of Sally inside the diner,”
or “every long shot of Antonio outside in the parking lot.” In a documentary, you could easily
isolate “every interview shot of Louis from camera 1,” or “every B-roll clip with Robyn.” All of
this will help you find media faster for editing, or quickly isolate similar clips that you need to
match together for grading.
For more information about using the Metadata Editor, see Chapter 19, “Using Clip Metadata.”
Organizing Smart Bins
Manually created Smart Bins can be organized into Folders and Sub-Folders for better sidebar
management, just like regular bins.
Smart Bins organized into folders
To add a Smart Bin folder:
Right-click in the Smart Bins area and choose Add Folder from the contextual menu to create folders
that you can drag Smart Bins into. Each folder has a disclosure triangle, so you can show or hide
its contents.
393Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Another benefit of Folders is that when you select a Folder, you can see the full contents of all Smart
Bins inside of it in the Media Pool browsing area. Selecting any one Smart Bin then restricts the Media
Pool to showing only the media reference by that Smart Bin.
Folders can be renamed, removed, opened as a new window, or sorted along with all other Smart Bins
by right-clicking them and using commands in the contextual menu.
Duplicating Clips in the Media Pool
You can duplicate clips in order to create an instance of that media that’s treated as a completely new
source clip, entirely separate from the original instance of that clip that was imported into DaVinci
Resolve. The duplicate is capable of storing individualized metadata and markers that are completely
distinct from the original clip that was imported into your project.
To duplicate one or more clips:
1 Select one or more clips to duplicate.
2 Do one of the following:
 Choose Edit > Duplicate Clip
 Hold the Option key down while dragging one or more selected clips to another bin
 Right-click a clip in the Media Pool, and choose Duplicate Clip from the Contextual Menu
Adding Clips From the Timeline to the Media Pool
You can also drag one or more clips from the Timeline back into the Media Pool to create a duplicate.
As with duplicating clips in the Media Pool, each duplicate is created as a new source clip that’s
entirely separate from the original instance of that clip that was imported into DaVinci Resolve and is
capable of storing individualized metadata and markers that are completely distinct from the original
clip that was imported into your project.
For example, the original clip in the Timeline remains conformed to the original clip that was first
```
imported into the Media Pool; deleting the original clip from the Media Pool will make that clip “non-
```
conformed” in the Timeline, while the duplicate you just created remains linked and available. If
you’re in this situation, you can always turn Conform Lock Enabled off for that clip in the Timeline and
reconform the Timeline Clip to the duplicate you just created, but that’s an extra step because the
duplicate clip is considered by DaVinci Resolve to be a whole new piece of media that just happens to
share the same clip details.
This may seem strange, but there are a variety of finishing workflows that use this capability, so it’s
good to know about.
Duplicating Timelines
Timelines can be duplicated for a variety of reasons: to create a backup of a timeline at a specific date,
to create a variation of an edit, or to create separately graded versions.
To duplicate a Timeline:
 Select a Timeline in the Media Pool, and choose Edit > Duplicate Timeline.
 Press Command-4 to give focus to the Timeline, and choose Edit > Duplicate Timeline.
394Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Choosing How to Display Bins
Once you’ve created a bin structure for your project, you can customize how your bins are displayed,
depending on how you like to work.
Showing Bins in Separate Windows
If you right-click a bin in the Bin list, you can choose “Open As New Window” to open that bin into its
own window. That window is basically its own Media Pool, complete with its own Bin list, Power Bins
and Smart Bins lists, and display controls.
Multiple Media Pool bins opened as new windows
When multiple Media Pool windows are open, the Workspace > Media Pool Windows submenu lets
you bring a floating Media Pool window into focus when you have one or more open and hidden.
This is most useful when you have two displays connected to your workstation, as you can drag these
separate bins to the second display while DaVinci Resolve is in single screen mode. If you hide the
Bin list, not only do you get more room for clips, but you also prevent accidentally switching bins if you
really want to only view a particular bin’s contents in that window.
Using the Media Pool in Thumbnail View
If you work in Thumbnail view using the controls at the top right of the Media Pool, you have the option
to resize the thumbnails to make them easier to see, and you can move the mouse pointer over each
clip to hover scrub through its contents. Clicking any clip to select it displays it in the Media page
Viewer. Whichever clip is currently selected is also output to video for monitoring.
In Thumbnail view, you can use the Sort Order drop-down, at the top right of the Media Pool, between
the Icon Size slider and the Icon/List view buttons, to choose how clips are sorted. There are fourteen
```
options: File Name, Reel Name, Clip Name, Start TC, Duration, Type, FPS, Audio Ch, Flags, Date
```
Modified, Date Created, Shot, Scene, and Take.
395Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Custom Sort of Clip Thumbnails in the Media Pool
You can now manually reposition Media Pool clips in Thumbnail view, allowing you to group clips
together in any way that visually makes sense to you.
You can turn on Custom Sort by selecting Custom in the Sort menu in the Media Pool.
Select Thumbnail View in the Media Pool, and from the sort menu select Custom. Then you can
drag your thumbnails around in any order or grouping that you wish. If Snap to Grid is selected in the
Sort menu, the icons will line up in neat rows and columns. Turn off Snap To Grid to enable freeform
positioning. If two thumbnails are overlapping, the last one moved will show on top.
```
With Snap to Grid deselected you can rearrange thumbnails in any way (even overlapping),
```
and it is retained throughout the Medial Pool on all pages.
The position of your icon thumbnails are persistent in the Media Pools across all pages in DaVinci
Resolve. The positioning is also retained if you temporarily choose another sort order, and then return
to the Custom sort.
Working With Columns in List View
If you work in List view using the controls at the top right of the Media Pool, you gain additional
organizational control by exposing columns that show the metadata that each clip contains, prior to
media being added to your timeline. You can use these columns to help organize your media.
396Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Methods of customizing metadata columns in List view:
 To show or hide columns: Right-click at the top of any column in the Media Pool to reveal the
column list, and while the column list is open, click the checkboxes of any columns you want to
show or hide. Unchecked columns cannot be seen. When you’re finished, click anywhere else in
the Media Pool to dismiss the column list.
 To rearrange column order: Drag any column header to the left or right to rearrange
the column order.
 To resize any column: Drag the border between any two columns to the right or left to narrow or
widen that column.
 To sort by any column: Click the column header you want to sort with. Each additional time you
click, the same header toggles that column between ascending and descending sort order.
Once you’ve customized a column layout that works for your particular purpose, you can save it for
future recall.
Methods of saving and using custom column layouts:
 To create a column layout: Show, hide, resize, and rearrange the columns you need for a
particular task, then right-click any column header in the Media Pool, and choose Create Column
Layout. Enter a name in the Create Column Layout dialog, and click OK.
 To recall a column layout: Right-click any column header in the Media Pool, choose the name of
the column layout you want to use from the contextual menu, and choose Load from that item’s
submenu. All custom column layouts appear at the top of the list.
 To edit a column layout: Load the column layout you want to edit, make whatever changes you
need to, then right-click any column header in the Media Pool, choose the name of the column
layout you just edited from the contextual menu, and choose Update from that item’s submenu.
 To delete a column layout: Right-click any column header in the Media Pool, choose the name
of the column layout you want to delete from the contextual menu, and choose Delete from
that item’s submenu.
While the available columns of metadata correspond to those fields shown in the Metadata Editor,
the available columns in the Media Pool of the Media and Edit pages are a subset of the total amount
of metadata that’s available, although they represent the most commonly used metadata you’ll find
yourself referring to when editing and finishing.
The available columns in List view include:
```
Angle: An editable field to contain the angle of the media in a multi-camera shoot.
```
Audio Bit Depth: The bit depth of any audio channels in the media file.
Audio Ch: The total number of audio tracks in the media file.
Audio Codec: The specific codec used by the audio portion of the media file.
Audio Offset: Lists the audio offset, in frames, for clips that have been synchronized to separately
recorded audio. This parameter is editable in the Media Pool.
Bit Depth: The bit depth of the media file.

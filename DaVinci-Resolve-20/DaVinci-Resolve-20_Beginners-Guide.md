DAVINCI RESOLVE 20
Download
DAVINCI
RESOLVE 20
Free!
The Beginner’s Guide to
```
Authors: Chris Roberts, Simon Hall
```
The Beginner’s Guide to
The Beginner’s Guide to DaVinci Resolve 20
Chris Roberts, Simon Hall
© 2025 by Blackmagic Design Pty Ltd
Blackmagic Design
www.blackmagicdesign.com
To report errors, please send a note to learning@blackmagicdesign.com.
Series Editor: Klark J. Perez
```
Editor: Dan Foster
```
Contributing Author: Nahuel Srnec
Cover Design: Blackmagic Design
```
Layout: Blackmagic Design, Danielle Foster
```
Notice of Rights
All rights reserved. No part of this book may be reproduced or transmitted in any form by any means, electronic,
mechanical, photocopying, recording, or otherwise, without the prior written permission of the publisher.
For information on getting permission for reprints and excerpts, contact learning@blackmagicdesign.com.
Notice of Liability
Neither the author nor Blackmagic Design shall have any liability to any person or entity for any loss or damage
caused or alleged to be caused directly or indirectly by the information contained in this book, or by omissions
from this book, or by the computer software and hardware products described within it.
Trademarks
Many of the designations used by manufacturers and sellers to distinguish their products are claimed as trademarks.
Where those designations appear in this book, and Blackmagic Design was aware of a trademark claim, the
designations appear as requested by the owner of the trademark. All other product names and services identified
throughout this book are used in editorial fashion only and for the benefit of such companies with no intention of
infringement of the trademark. No such use, or the use of any trade name, is intended to convey endorsement or
other affiliation with this book.
```
(Mac) and (macOS) are registered trademarks of Apple Inc., registered in the U.S. and other countries. Windows is a
```
registered trademark of Microsoft Inc., registered in the U.S. and other countries.
ISBN 13: 979-8-9924874-6-6
Contents
Foreword ix
Acknowledgments x
About the Authors x
Who This Book Is For xii
Getting Started xiii
Introducing Blackmagic Cloud xxiv
1 Editing a Rough Cut 1
Importing a Project 2
Relinking the Media Files 6
Understanding Bins and Smart Bins 9
Creating a New Timeline 13
Adding the Soundbites 17
Working with the Subclips 28
Adding the Other Soundbites 34
Reordering the Timeline Clips 40
Insert and Append at End Edits 42
Pacing the Soundbites 45
Painting the Interview 48
Backtiming Edits 59
Adding the Music 64
Lesson Review 67
2 Finessing the Rough Cut 69
Setting Up the Project 70
Duplicating and Managing Timelines 70
Trimming the Timeline Clips 76
Replace Edit 89
Visual Effects 98
Adding the Logo 122
Adding the Closing Titles 130
Lesson Review 139
3 Audio Editing and Quick Export 141
Setting Up the Project 142
Audio Mixing 142
Normalizing Clip Levels 147
Noise Reduction Using Fairlight FX 154
Adding Audio Fades and Transitions 159
Mixing the Music Levels 165
Recording a Voiceover 168
Full-Screen Review 173
Quick Export 174
Lesson Review 179
An Introduction to Color Correction 181
4 Performing Primary Color Corrections 189
Exploring the Color Page Interface 190
Using the Primary Corrector 193
Understanding Video Scopes 195
Color Correcting Using Lift, Gamma, and Gain 198
Understanding Nodes 204
Using Nodes to Separate Corrections 206
Labeling Nodes 210
Making Automatic Adjustments 211
Using Separate Timeline Settings 217
Using DaVinci Resolve Color Management 218
Matching Different Cameras 224
Adjusting Individual Color Channels 228
Using Curves for Primary Color Corrections 231
Using Curves in Separate Nodes 236
Using the HDR Wheels 240
Lesson Review 245
5 Making Secondary Adjustments 247
Masking Areas with Windows 248
Reversing Selections with Outside Nodes 253
Using Windows to Adjust Lighting 255
Making Secondary Adjustments with HSL Curves 262
Making Quick Adjustments with the Color Warper 267
Using the Chroma Warper 271
Selecting Areas with the Qualifier 275
Combining Qualifiers and Power Windows 280
Using the Tracker 284
Using the Color Slice Tool 289
Lesson Review 293
6 Finishing and Management 295
Applying Resolve FX in the Color Page 296
Identifying Ungraded Clips 300
Copying Grades 303
Working with Stills 306
Importing and Exporting Grades 317
Working with LUTs 321
Making Creative Decisions 329
Lesson Review 333
7 Project Setup and Preferences 335
Creating a New Project 336
Exploring the Source Media 339
Project Settings 344
Importing Media 350
Syncing Audio to Video 353
Working with Metadata 365
Creating Keyword Smart Bins 370
Creating Custom Smart Bins 378
Renaming Clips with Metadata 384
Creating Subclips 388
Preferences 396
Exploring Keyboard Shortcuts 407
Lesson Review 415
An Introduction to Audio Post and Sound Design 417
8 An Introduction to Fairlight 425
Setting Up the Project 426
Preparing the Timeline 428
Exploring the Fairlight Interface 433
Setting Track Formats and Clip Channels 437
Trimming Clips in Fairlight 440
Using the AI Dialogue Leveler 442
Applying EQ 449
Adding Sound Effects 455
Using Scrollers 459
Aligning Sound Effects 467
Mixing the Soundtrack 473
Ducking the Music 479
Lesson Review 491
An Introduction to Visual Effects Compositing 493
9 An Introduction to Fusion 499
Creating a Fusion Composition 500
The Fusion Interface 502
Adding the First Node 503
The Merge Node 509
Text Creation 512
Keyframes and Animation 517
Quick Changes in the Edit Page 523
VFX Compositing 527
Lesson Review 541
10 Delivery and Media Management 543
Preparing the Project 544
Creating Vertical Timelines 545
Changing Timeline Settings 552
Reframing Shots 556
Using the Deliver Page 570
Optimizing Audio Standards 571
Customizing Deliver Presets 574
Saving a Render Preset 577
Adding the Vertical Timeline 579
Reviewing the Jobs 581
Rendering the Jobs 584
Exporting Timelines and Project Files 586
Media Management 587
Creating a Project Archive 592
Creating and Switching Project Libraries 593
Copying Projects Between Project Libraries 596
Backing Up Project Libraries 598
Lesson Review 599
Index 601
ixForeword
Foreword
Welcome to The Beginner’s Guide to DaVinci Resolve 20.
DaVinci Resolve 20 is the only post-production solution that combines editing, color
correction, visual effects, motion graphics, and audio post-production all in one software
tool! Its elegant, modern interface is fast to learn for new users yet powerful enough for
the most experienced professionals. DaVinci Resolve lets you work more efficiently
because you don’t have to learn multiple apps or switch software for different tasks. It’s
like having your own post-production studio in a single app!
DaVinci Resolve 20 adds editing with transcriptions from audio, film look creator and
ColorSlice six vector grading, IntelliTrack AI for panning audio to match vision, broadcast
replay for live multi-camera broadcast editing, layout and replay with speed control, and
so much more!
Best of all, Blackmagic Design offers a version of DaVinci Resolve 20 that is completely free!
We’ve made sure that this version of DaVinci Resolve includes more features than any paid
editing system. That’s because at Blackmagic Design we believe everybody should have
the tools to create professional, Hollywood-caliber content without having to spend
thousands of dollars.
I invite you to download your copy of DaVinci Resolve 20 today and look forward to seeing
the amazing work you produce!
Grant Petty
Blackmagic Design
xAbout the Authors
Acknowledgments
We would like to thank the following individuals for their contributions of media used
throughout this book:
— Chris Lang, Aaron Walterscheid, Nathan LeFever, and Sherwin Lau for Organ Mountain
Outfitters content
— “Furever Glass” music composed and performed by Matt Carlin
— Sean Viljoen and the Conservation Film Company
— CyberBox, an ICVFX Virtual Production project shot by Nahuel Srnec
— Machine for the Aura, directed by Ana Monserrat and Nahuel Srnec
About the Authors
Chris Roberts has spent nearly 30 years editing everything from online corporate promos
to broadcast television, with editing credits that include the BAFTA award-winning series
The Great House Giveaway.
He has been delivering video editing training for over 20 years, and has trained university
students and staff, broadcast journalists, and sports, factual, and drama editors. As a
Blackmagic Certified Master Trainer, he has been responsible for delivering DaVinci Resolve
training to end users and other trainers around the world, both in person and remotely.
Over the years, he has also written articles on editing techniques and editing software for
a variety of magazines and online publications, as well as writing a number of books,
including The Editor’s Guide to DaVinci Resolve.
Chris lives in Worcestershire, UK, with his partner, Samantha, and, when not working,
enjoys reading post-apocalyptic fiction, listening to hard rock and blues music, and
binge-watching the TV he has invariably missed.
This book is dedicated to the memory of his dearly loved and sadly missed parents,
Frank and Maureen.
www.chrisroberts.info
Nahuel Srnec, CSI, ADF, is a film producer and director, cinematographer, post-production
coordinator, and university professor with over 15 years of experience teaching at
universities and film schools worldwide. His courses span a range of topics, from
xiAbout the Authors
```
directing and cinematography to post-production and virtual production (specifically
```
```
ICVFX). Nahuel is also a Blackmagic Design Certified Trainer in English, Spanish, and Italian,
```
as well as an Unreal Authorized Instructor for Unreal Engine.
Throughout his career, Nahuel has directed and produced acclaimed films and worked as a
cinematographer and colorist on numerous feature films, TV shows, and commercials. He
is the producer, co-director, and post-production coordinator of the Argentinian feature
```
film Machine for the Aura (WIFF, BJIFF).
```
```
He is a full member of the Colorist Society International (CSI) and the Argentine Society of
```
```
Cinematographers (ADF) and served as a voting member of the ISO/TC 36 Cinematography
```
international standards committee.
He has worked as a consultant and trainer at Paramount’s Buenos Aires offices and
currently researches the integration of cinematography and virtual production. He also
presented an advance on his research on IA and film teaching at the CILECT congress in
```
2024 (Beijing). The production group he founded, NSfilms, is a Blackmagic Design Training
```
```
Partner: https://nsfilms.net/
```
Simon Hall has been in the post-production industry for 20 years. Starting at a small
post-production house as an edit assistant, he moved to being an offline editor for
numerous broadcast productions and high-end corporate promotions, and then
progressed to online editing and finishing.
During this time, he also started delivering training to a small number of broadcast editors
before expanding into training promo editors, documentary and factual editors,
journalists, university and college students, and online broadcast editors.
He moved to Soho Editors in London to take up the position of lead trainer specializing in a
variety of post-production disciplines, as well as continuing to work on editing and
finishing jobs. During this time, he started working with DaVinci Resolve 8 to replace older
color correction software.
In 2015, Simon joined Blackmagic Design as a product specialist focusing on post-
production and DaVinci Resolve more specifically, and now heads up the post-production
product team in the EMEA region.
He lives in Cheshire, UK, with his wife, Emma, their new son, Seb, and Nola the dog. When
not working and running around after a toddler, he enjoys following numerous sports,
taking peaceful walks with an energetic Labrador, and reading a wide range of books. He is
also a self-confessed petrolhead.
This book is dedicated to my wife, Emma, for her endless support and to my son, Sebastian.
xiiWho This Book Is For
Who This Book Is For
This book is designed for both beginners and professionals. Beginners will find clear and
concise lessons to get up and running quickly. If you’re a professional switching from
another system, you’ll find lessons that cover everything from basic editing and trimming
to working with audio, adding text, effects, and more. You’ll also find dozens of pro tips
and tricks that will help you make the switch to DaVinci Resolve!
xiiiGetting Started
Getting Started
Welcome to The Beginner’s Guide to DaVinci Resolve 20, the official Blackmagic Design
Training and Certification book that teaches editors, artists, and students how to edit,
composite, color correct, and mix audio in DaVinci Resolve. All you need is a Mac or
Windows computer, the free download version of DaVinci Resolve 20, and a passion to
learn and tell your story!
This official step-by-step training guide covers the basics of editing, visual effects, motion
graphics, color correction, and audio so you can start creating your own Hollywood-caliber
film and video today!
About DaVinci Resolve 20
DaVinci Resolve is the world’s fastest-growing and most advanced post-
production software.
It also has a long history of being the world’s most trusted application for color correction.
With DaVinci Resolve 20, Blackmagic Design has added a complete 2D and 3D visual effects
compositing and motion graphics environment that enables you to complete even the
most challenging projects using only one piece of software!
xivGetting Started
What You’ll Learn
— How to mark selections, edit clips in the timeline, and perform context-
sensitive trimming
— How to retime clips, add transitions, and add Resolve FX
— How to work with Fusion title templates, create your own titles, and add animation
— How to perform primary and secondary corrections using DaVinci Resolve’s legendary
color tools
— How to match shots, use color management, create looks, and grade multiple clips
— How to use Power Windows, track objects in a shot, use curves, and add ResolveFX
— How to set up projects, import media, and use metadata to speed up your work
— How to edit and mix audio using the Fairlight audio tools
— How to navigate the Fusion page and use a node-based interface for visual
effects compositing
— How to deliver projects in a variety of formats and share them directly to
YouTube and Vimeo
— And dozens of tips and tricks throughout the book that will transform how you work!
The Blackmagic Design Training
and Certification Program
Blackmagic Design publishes several training books that take your skills further in
DaVinci Resolve 20. They include:
— The Beginner’s Guide to DaVinci Resolve 20
— The Colorist Guide to DaVinci Resolve 20
— The Editor’s Guide to DaVinci Resolve 20
— The Fairlight Audio Guide to DaVinci Resolve 20
— The Visual Effects Guide to DaVinci Resolve 20
— Advanced Visual Effects in DaVinci Resolve 20
DAVINCI RESOLVE 20Advanced Visual Effects in
DownloadDAVINCIRESOLVE 20Free!
```
Authors: Damian Allen, Dion Scoppettuolo
```
DAVINCI RESOLVE 20The Colorist Guide to
DownloadDAVINCIRESOLVE 20Free!
```
Authors: Daria Fissoun, CSI
```
DAVINCI RESOLVE 20
DownloadDAVINCIRESOLVE 20Free!
The Editor’s Guide to
```
Author: Chris Roberts
```
DAVINCI RESOLVE 20 The Fairlight Audio Guide to
DownloadDAVINCIRESOLVE 20Free!
```
Author: Mary Plummer
```
DAVINCI RESOLVE 20The Visual Effects Guide to
DownloadDAVINCIRESOLVE 20Free!
```
Authors: Damian Allen, Tony Gallardo, Dion Scoppettuolo
```
xvGetting Started
Whether you want an introductory guide to DaVinci Resolve or want to learn more
advanced editing techniques, color grading, sound mixing, or visual effects, our certified
training program includes a learning path for you.
Getting Certified
After completing this book, you are encouraged to take a 1-hour, 50-question online
proficiency exam to receive a Certificate of Completion from Blackmagic Design. The link
to the online exam can be found on the Blackmagic Design training webpage. The
webpage also provides additional information on our official Training and Certification
Program. Please visit www.blackmagicdesign.com/products/davinciresolve/training.
System Requirements
This book supports DaVinci Resolve 20 for macOS and Windows. If you have an older version
of DaVinci Resolve, you must upgrade to the current version to follow along with the lessons.
NOTE The exercises in this book refer to file and resource locations that will differ
if you are using the version of software from the Apple Mac App Store. For the
purposes of this training book, we recommend that macOS users download and
use the DaVinci Resolve software from the Blackmagic Design website rather than
from the Mac App Store.
Download DaVinci Resolve
To download the free version of DaVinci Resolve 20 or later from the
Blackmagic Design website:
1 Open a web browser on your Windows or macOS computer.
2 In the address field of your web browser, type:
www.blackmagicdesign.com/products/davinciresolve.
3 On the DaVinci Resolve landing page, click the Download button.
4 On the download page, click the button corresponding to your computer’s
operating system.
5 Follow the installation instructions to complete the DaVinci Resolve installation.
When you have completed the software installation, follow the instructions in the following
sections to launch DaVinci Resolve and download the media files used throughout this book.
xviGetting Started
DaVinci Resolve 20 Quick Setup
When DaVinci Resolve 20 is successfully installed, you can launch the application for the
first time.
macOS users will find the DaVinci Resolve application in their Applications folder. Double-
click the DaVinci Resolve folder, and then double-click the DaVinci Resolve application.
Alternatively, you can use Launchpad or Spotlight search to locate and launch
DaVinci Resolve.
Windows users will find a shortcut has been added to their Desktop. Alternatively, click the
Start menu and search for “DaVinci Resolve” and press Enter to launch the application.
When DaVinci Resolve 20 opens for the first time, you’ll see a Welcome splash screen
detailing the new features available in the current version.
xviiGetting Started
1 If required, you can change the language used. You can also learn more about these
and hundreds of other amazing features available in DaVinci Resolve 20 by clicking
Learn More. Otherwise, click Continue.
Next, you are invited to go through the Quick Setup process. Experienced users can
skip this process by clicking “Skip and Start Right Now,” but new users are advised to
follow this process. It will only take a couple of minutes and is useful for understanding
how Resolve is working.
xviiiGetting Started
2 Click the Quick Setup button.
3 DaVinci Resolve will check your system to ensure that your operating system and
graphics card will perform well. If both pass this test, click Continue.
xixGetting Started
Next, you will be asked what type of project you would like to begin. DaVinci Resolve
```
supports projects at different resolutions, from Standard Definition (SD) and High
```
```
Definition (HD) to Ultra High Definition and beyond.
```
4 If you know the resolution you commonly work with, you can set it here. Otherwise,
leave the resolution set to 1080 HD and click Continue.
NOTE You will learn more about setting the resolution for your projects in
Lesson 7, “Project Setup and Preferences.”
The next screen asks where you would like to store your media. This does not refer to
the video, audio, and graphics files you’ll edit and grade, but rather the ancillary files
Resolve will need to create as you’re working. This location is commonly referred to as
```
a “scratch disk” and by default is set to your current user’s Movies folder (macOS) or
```
```
Videos folder (Windows).
```
xxGetting Started
5 Leave this set to the default location and click Continue.
NOTE You will learn more about changing the Media Storage Locations
in Lesson 7.
On the next screen, you will be asked which keyboard layout you would like to use. This
```
is specifically relevant if you’re familiar with using another nonlinear editor; however,
```
throughout this Beginner’s Guide you will be introduced to keyboard shortcuts that use
the DaVinci Resolve keyboard layout. Therefore, if you change the layout at this point,
you may find that those shortcuts no longer work.
xxiGetting Started
6 For now, leave the layout set to DaVinci Resolve and click Continue.
NOTE You will learn more about changing the keyboard layout, including
setting your own keyboard shortcuts, in Lesson 7.
Congratulations! You have completed the Quick Setup process and have changed
precisely nothing in terms of DaVinci Resolve’s default setup. Nevertheless, you have
also gained an insight into some aspects of using DaVinci Resolve that will serve you
well as you continue learning about the application and how it uses your system.
xxiiGetting Started
7 Click Start to launch and begin enjoying DaVinci Resolve 20!
Once loaded, DaVinci Resolve will open to the cut page, which is the default starting
page for all projects. However, this is not the usual place to begin working with
DaVinci Resolve. Instead, you should now exit the application in readiness to begin the
first lesson in this book.
```
8 Choose DaVinci Resolve > Quit DaVinci Resolve or press Command-Q (macOS) or
```
```
Ctrl-Q (Windows).
```
DaVinci Resolve 20 will close.
Get the Lesson Files
To perform the steps detailed in the exercises throughout this book, the Beginner’s Guide
lesson files must be downloaded to your macOS or Windows computer. After you save the
```
files to your hard drive, extract the file and copy the folder to your Movies folder (macOS)
```
```
or Videos folder (Windows).
```
To Download and Install the DaVinci Resolve Lessons Files
When you are ready to download the lesson files, follow these steps:
1 Open a web browser on your Windows or macOS computer.
2 In the address field of your web browser, type:
www.blackmagicdesign.com/products/davinciresolve/training
3 Scroll the page until you locate The Beginner’s Guide to DaVinci Resolve 20.
4 Click the Lesson Files Part 1 link to download the media. The file is roughly 5 GB in size.
xxiiiGetting Started
5 After downloading the zip file to your macOS or Windows computer, open your
Downloads folder and double-click R20_Beginner_Guide.zip to unzip it if it doesn’t
unzip automatically. You’ll end up with a folder named R20 Beginner Guide that
contains all the content for this book.
6 From your Downloads folder, move or copy the R20 Beginner Guide folder to a
convenient location on your computer or an external hard drive. If in doubt, use your
```
User’s Movies folder (macOS) or Videos folder (Windows).
```
Once you have DaVinci Resolve 20 installed and the media files downloaded, you are ready
to begin Lesson 1.
xxivIntroducing Blackmagic Cloud
Introducing Blackmagic Cloud
DaVinci Resolve is the world’s only complete post-production solution that lets everyone
work together on the same project at the same time. Traditionally, post-production follows
a linear workflow with each artist handing off to the next, introducing errors and
mountains of change logs to keep track of through each stage. With DaVinci Resolve’s
collaboration features, each artist can work on the same project, in their own dedicated
page with the tools they need.
Now Blackmagic Cloud lets editors, colorists, VFX artists, animators, and sound engineers
work together simultaneously from anywhere in the world. Plus, they can review each
other’s changes without spending countless hours reconforming the timeline.
Simply create a Blackmagic Cloud ID, log in to the online DaVinci Resolve Project Server,
and follow the simple instructions to set up a new project library—all for one low
monthly price!
Once this library is created, you can access it directly from the Cloud tab in the Project
Manager to create as many projects as you need—all stored securely online. Then invite up
to 10 other people to collaborate on a project with you. With a simple click, they can relink
to local copies of the media files and start working on the project immediately, with all their
changes automatically saved to the cloud.
Enabling Multiple User Collaboration for your project means that everyone can work on
the same project at the same time—edit assistants, editors, colorists, dialogue editors,
and visual effects artists can now all collaborate wherever they are in the world in a way
never before possible.
Media Sync with Blackmagic Cloud Store
Now you don’t need to buy expensive proprietary storage that needs an entire IT team to
manage! Blackmagic Cloud Store has been designed for multiple users and can handle the
huge media files used by Hollywood feature films. You can also have multiple Blackmagic
Cloud Stores syncing the media files with your Dropbox account so that everyone has
access to the media files for the project.
To find out more about these exciting workflows, visit
www.blackmagicdesign.com/products/davinciresolve/collaboration.
Time
This lesson takes approximately
75 minutes to complete.
Goals
Importing a Project 2
Relinking the Media Files 6
Understanding Bins and
Smart Bins 9
Creating a New Timeline 13
Adding the Soundbites 17
Working with the Subclips 28
Adding the Other Soundbites 34
Reordering the Timeline Clips 40
Insert and Append at End Edits 42
Pacing the Soundbites 45
Painting the Interview 48
Backtiming Edits 59
Adding the Music 64
Lesson Review 67
Lesson 1
Editing a Rough Cut
Whether you are creating social media
videos, high-end commercials, episodic
television series, or the latest cinematic
blockbuster, DaVinci Resolve 20 is the
complete post-production solution that
allows you to organize, edit, grade, and
deliver your video content all in one
place. Beyond this, DaVinci Resolve also
provides tools for creating complex
visual effects and motion graphics,
as well as professional tools for
sweetening and mixing your audio.
With this level of complexity, it’s
sometimes difficult to know where to
start, especially for the new user.
2Lesson 1 Editing a Rough Cut
In this first lesson, you will begin by exploring the tools and techniques you can employ in
the edit page to tell your stories by putting together a rough cut of a 1-minute social media
promo for New Mexico outdoor clothing brand Organ Mountain Outfitters. In subsequent
lessons, you will learn how you can refine this initial edit, mix the audio, add titles and
graphics, and export the final video in a suitable format for sharing on social media sites
like YouTube and Vimeo.
So make sure you’re comfortable as the opening titles roll….
Importing a Project
The process of working with DaVinci Resolve doesn’t necessarily start with editing. Usually,
there’s a whole lot of time, effort, and energy expended making sure the project is set up
correctly and that all the media is available and properly organized, both on the hard
drives of the computer you’re using as well as within the project you’re working on
within Resolve.
In large-scale productions, this process is often handled by a dedicated person called the
```
DIT (Digital Intermediate Technician), Data Wrangler, Media Manager, or Edit Assistant.
```
On smaller productions, this person and the editor, colorist, audio mixer, etc., are all usually
the same person!
```
Don’t worry; you’ll explore all these roles throughout this book. However, to cut to the
```
chase, you will start by working on a project that has already been set up for you. You
simply need to import it into your copy of DaVinci Resolve 20 and start editing. This way,
you can see how various techniques and processes were applied to make it easier for you
to edit—techniques and processes that you will explore further in later lessons so that you
can apply them successfully to your own projects in due course.
NOTE The following steps assume that you’ve already downloaded and
unzipped the media files that accompany this book and have opened
```
DaVinci Resolve 20 at least once and been through (or skipped) the Quick Setup
```
process. If you haven’t completed either of these steps, please refer to the
“Getting Started” section at the beginning of this book.
3Lesson 1 Editing a Rough Cut
1 Open DaVinci Resolve, letting the application load until the Project Manager opens.
The Project Manager is the place in DaVinci Resolve where you can access, organize,
and manage each of your projects. Each project is stored inside a database called a
project library, which is accessible from one of three locations:
— Local Project libraries are stored on your computer or on directly attached
storage such as an external hard drive. These are the simplest and easiest types of
project libraries to work with, especially for someone working on their own
projects who doesn’t need to collaborate with others regularly.
— Network Project libraries are available to anyone using DaVinci Resolve in a
networked environment, such as a post-production facility where different people
may need access to the same set of projects.
— Cloud Project libraries are stored on dedicated Blackmagic Cloud servers where
they can be accessed anywhere you can get online by anyone you choose to invite.
Both networked and cloud-based project libraries have the advantage that they can be
used to collaborate so that multiple DaVinci Resolve users can not just access a set of
projects in a project library but actually work on the same project simultaneously!
As this is a Beginner’s Guide, you will work with the default local project library and, as
discussed, you will import a project that has already been set up for you by the authors
```
(think of them as your edit assistants for this lesson).
```
4Lesson 1 Editing a Rough Cut
NOTE You will learn more about creating your own project libraries in
Lesson 10, “Delivery and Media Management.”
2 In the lower left corner of the Project Manager, click the Import button.
```
3 In the Finder window (macOS) or Explorer window (Windows) that opens, navigate to
```
the R20 Beginner Guide / Lesson 01 folder and select the file OMO PROMO.drp.
The file extension .drp indicates that this is a DaVinci Resolve Project file. Project files
contain information about how the project is set up and organized but do not contain
```
any media (audio and video) files. These files are kept in the Media folder in the R20
```
Beginner Guide folder.
4 With the OMO PROMO.drp file selected, click Open.
5Lesson 1 Editing a Rough Cut
After a brief process, the project file is imported into the Project Manager and is now
available for you to open.
NOTE DaVinci Resolve does not open projects directly from .drp files.
Instead, the project file is copied into the current project library.
Thereafter, any changes to the project are applied to the copy in the
project library, not the .drp file you initially selected. This is why you must
always open a project using the Project Manager rather than double-clicking
a .drp file directly from your computer, which you might do if you’re more
familiar with other video editing software.
5 With the OMO PROMO project selected in the Project Manager, click Open.
Alternatively, double-click the OMO PROMO project.
DaVinci Resolve will open the project in the last page that was active when it was last
opened, so you might be looking at this project in any of the pages.
6 If necessary, click the Edit button at the bottom of the interface to open the edit page.
6Lesson 1 Editing a Rough Cut
7 Select Workspace > Reset UI Layout to reset the interface to the default layout preset .
8 In the bin list, select the B-ROLL bin to display its contents and move your mouse over
any of the clips.
Relinking the Media Files
Currently, all the video, audio, and image clips in this project are displaying as “offline media.”
This means that the links that were originally created when the media files were first added
to this project have been broken. So, before you can do anything with these clips, you’ll need
to relink them to their associated media files on your computer’s hard drive.
7Lesson 1 Editing a Rough Cut
Media files may go offline for a variety of reasons, most commonly because they have
been moved. To prevent this from happening, once the files have been added to a project,
you should always leave them alone. If you need to move them to a different location, such
as a larger hard drive, you should use DaVinci Resolve’s built-in Media Management
feature, which you will explore in Lesson 10. You should never rename a file on your hard
drive once it’s in use in DaVinci Resolve because this might break the link completely and
cause lots of problems. If you need to rename a clip, do it in the DaVinci Resolve project
since this does not rename the file on the hard drive.
NOTE You will learn more about the value of renaming clips in Lesson 7, “Project
Setup and Organization.”
In this case, the reason why the media files are all offline is that the project was originally
set up with the media files in one location. However, as the copies of the media files live on
your computer in a different location, you must tell DaVinci Resolve where to find them.
Thankfully, DaVinci Resolve makes it easy to quickly relink them.
1 In the top left of the interface, above the media pool in the edit page, click the red
Relink Media button.
NOTE The Relink Media button will only be red if there are any media files in
the project that are unexpectedly offline. Media that has been deliberately
unlinked in the project is not indicated.
8Lesson 1 Editing a Rough Cut
2 The Relink Media window appears, showing how many files are currently offline.
TIP Place your mouse cursor over the location where Resolve expected
the media files to be located to view more detail about the original location of
the files.
```
3 Click the Locate button to open a Finder window (macOS) or Explorer window (Windows).
```
You now need to tell Resolve where the appropriate media files can be found on
your system.
4 Navigate to the R20 Beginner Guide folder on your system and click Open.
9Lesson 1 Editing a Rough Cut
Resolve automatically searches the location and will relink to the media files.
NOTE If Resolve cannot find the appropriate files, you can initiate a more
comprehensive search from the Relink Media window using the Disk Search
button. Be aware, though, that this search will take much longer, especially if
you have very large hard drives with lots of media files to search through!
Now that the clips have been successfully relinked, you can begin reviewing this project
and start assembling the rough cut.
Understanding Bins and Smart Bins
The media pool is the place where clips and other project elements, such as timelines, are
stored and organized. You can think of the media pool as a large filing system similar to the
Finder in macOS or File Explorer in Windows. In the same way you organize files for use in
```
your OS in folders, you can likewise organize the media pool, except in NLE (nonlinear
```
```
editing) software, folders are invariably referred to as bins.
```
NOTE You might wonder why folders are called bins in editing software. Well, this
terminology dates to the earliest days of film editing, when editors would store
strips of film in containers they referred to as “bins.” As editing moved from
physically splicing film on an editing machine to moving digital media around on a
screen, the term “bin” was simply retained to maintain continuity and familiarity
for editors.
10Lesson 1 Editing a Rough Cut
In DaVinci Resolve, you can see the bins in the current project in the bin list, which is displayed
to the left of the main media pool window. Each project has a default Master bin, which is
listed at the top of the bin list. You can think of this as the top level for your project. All the
other bins containing the footage you need for the project are listed inside the Master bin.
You can access the clips inside each bin by simply selecting the bin in the bin list.
1 Select the VIDEO bin to see the clips contained in this bin in the main media
pool browser.
TIP You can use the slider at the top of the media pool to resize the
thumbnails of the clips, making them larger or smaller, according to your
preferred view. You can also resize the media pool by dragging the dividing
line between the media pool and the source viewer.
2 Move your mouse pointer over the clips in this bin to preview them in the source
viewer to the right of the media pool.
11Lesson 1 Editing a Rough Cut
TIP You can disable/enable Live Media Preview by clicking the Options
```
menu (…) at the top right corner of the source viewer and selecting
```
Live Media Preview.
You can also organize bins inside other bins.
3 Click the disclosure arrow to the left of the INTERVIEW bin to reveal the sub bins called
VIDEO, AUDIO, and SUBCLIPS.
You can also display the contents of multiple bins together in the media pool.
```
4 With the VIDEO bin still selected, Command-click (macOS) or Ctrl-click (Windows) the
```
AUDIO bin to display all the clips in both bins together.
12Lesson 1 Editing a Rough Cut
While bins are a useful way of organizing your footage, sometimes the sheer amount
of footage you have to work with is overwhelming. That’s one reason why the edit page
has a much more flexible approach to organizing the clips by using the metadata
applied to a clip and grouping the clips in a series of smart bins.
5 In the Smart Bins section of the bin list, select the Keywords folder and click the
disclosure arrow to reveal the Keywords Smart Bins.
The Keywords smart bins are a set of automatic smart bins that appear when you start
adding keywords to clips in your projects.
6 Select the RETAIL keyword smart bin, which lists three clips that have the keyword
“RETAIL” applied.
13Lesson 1 Editing a Rough Cut
7 Click the disclosure arrow for the Keywords category to collapse the Keywords smart
bins, and then click the disclosure triangle for the MY SMART BINS category and select
the GOOD TAKES smart bin.
This is a manually created smart bin that contains clips that have been marked as good takes.
NOTE You’ll learn more about viewing, adding, and modifying clip metadata,
including adding keywords and marking clips as good takes so you can create
your own smart bins, in Lesson 7.
Creating a New Timeline
Someone once said that the hardest part of writing a book is starting the first chapter.
Indeed, the same is true for editing, except rather than trying to decide which words you
should start with, you have to decide which sounds and pictures you need. Placing those
```
first few clips into an empty timeline can be quite daunting; you never quite know where
```
you should start or where you will ultimately end up. However, once you begin assembling
14Lesson 1 Editing a Rough Cut
the footage clip by clip, the edit will slowly start to reveal itself, and you’ll start to see what’s
working, what doesn’t work, and what might be coaxed into working with a little more
effort on your part.
You’ll begin by editing some soundbites from the main interview with the proprietor of
Organ Mountain Outfitters, Chris Lang. While not every edit relies on spoken dialogue, it
can be a useful starting point since it will start to reveal the story you want to tell.
However, to start this exciting process, you will need an empty timeline. And to keep the
project organized, you will place this timeline in its own bin.
1 In the bin list, select the Master bin and choose File > New Bin.
A new bin is created called “Bin 8” since this is the 8th bin created in this project.
```
TIP You can also press Shift-Command-N (macOS) or Shift-Ctrl-N (Windows)
```
to create a new bin. New bins are automatically created in the currently
selected bin.
15Lesson 1 Editing a Rough Cut
2 With the name of the bin highlighted, type TIMELINES to rename it and select your
new bin in the bin list.
Next, you’ll create a new, empty timeline in this bin.
3 With the TIMELINES bin still selected, choose File > New Timeline.
The Create New Timeline window opens.
```
TIP You can press Command-N (macOS) or Ctrl-N (Windows) to create a new
```
timeline. New timelines are automatically created in the currently selected bin.
16Lesson 1 Editing a Rough Cut
4 In the Timeline Name field, type OMO PROMO.
5 Click Create.
A new timeline is created in the selected bin, and additional controls appear in the
timeline window.
NOTE A DaVinci Resolve project can contain many separate timelines. By default,
each of these timelines can be created using various settings specified in the
Project Settings. However, each timeline can have its own settings specified when
you create it, or you can change certain properties later if required. You’ll learn
more about the importance of choosing the correct timeline settings in Lesson 7.
17Lesson 1 Editing a Rough Cut
Adding the Soundbites
Now it’s time to start assembling the initial edit for Organ Mountain Outfitters.
1 In the bin list, select the INTERVIEW bin.
This bin contains three additional bins:
— VIDEO This bin contains all the Chris Lang interview clips that you’ll need to tell
the story of Organ Mountain Outfitters and will be the focus for your work over
the next steps.
— AUDIO This bin contains the audio clips for the interview that were recorded
separately—a common production practice. The audio has already been synced
with the interview clips by your edit assistant, so you don’t need to work with this
bin for now.
— SUBCLIPS This bin contains a series of subclips of the main interview clips which,
again, have been created by the edit assistant to help make working with the long
interview clips easier.
NOTE You’ll learn how to sync audio and video clips and create subclips
in Lesson 7.
18Lesson 1 Editing a Rough Cut
2 Select the VIDEO bin to reveal the full set of interview clips.
TIP If necessary, move the slider at the top of the media pool to the right to
increase the size of the thumbnails, making it easier to view the clip name.
3 Place your mouse pointer over the first clip in the VIDEO bin and move it left and right.
As your mouse pointer moves across the clip, the interview is previewed live in the
source viewer.
19Lesson 1 Editing a Rough Cut
TIP You can disable audio scrubbing by choosing Timeline > Audio Scrubbing
or pressing Shift-S.
4 Select the clip and drag it to the source viewer.
This opens the clip in the source viewer at the frame that was last displayed during
Live Preview.
NOTE Live previewing clips is very handy for quickly seeing the content of
clips in the media pool, especially if there are a lot of clips. This process quickly
but temporarily allows you to view the clip in the source viewer. However, when
you want to spend more time viewing a clip or choosing parts of it to edit into
the timeline, it’s better to open the clip in the source viewer by double-clicking
it or dragging it to the source viewer.
20Lesson 1 Editing a Rough Cut
5 In the source viewer’s transport controls, click the Go To First Frame button to move
the playhead back to the start of the clip.
TIP Press Home to move the playhead to the first frame of a clip or press End
to move to the last frame. If you are working on a laptop or other keyboard
without dedicated Home and End keys, you can often use fn-Left Arrow for
Home and fn-Right Arrow for End.
6 In the source viewer’s transport controls, click the Play button to begin playing the clip
from the start.
7 Listen to the interview as it plays in the source viewer.
21Lesson 1 Editing a Rough Cut
TIP Press the Spacebar to start/stop playback. See also the sidebar
“Controlling Playback” later in this chapter.
As you’ll probably realize very quickly, this interview clip is rather long and
encompasses several answers to different questions. You certainly wouldn’t want to
use this entire clip. Instead, you will use just a small soundbite.
NOTE A soundbite is a short, often memorable part of a longer spoken
recording. Soundbites are generally only a few seconds long and are chosen
as a way of communicating information, ideas, and arguments in a concise
format. They are used a lot when editing interviews for news broadcasts and
social media promos, for example, because they are often impactful and
attention-grabbing. But they should be used carefully so as not to
misrepresent the person speaking or oversimplify complex subjects.
8 In the source viewer’s transport controls, click the Stop button to halt playback.
To help you locate the soundbite, you can display the clip’s audio waveform alongside
the source video.
```
9 Click the source viewer’s Options (…) menu and choose Show Audio Waveform in
```
Source Clip.
22Lesson 1 Editing a Rough Cut
A green waveform appears along the bottom of the source viewer.
10 Click the Go To First Frame button to return the playhead back to the beginning
of the clip.
11 Press the Spacebar to start playing the interview again.
12 Listen to the interview as it’s playing and just after Chris laughs, but before he says,
“I’m Chris Lang…,” press the Spacebar to stop playback.
You should be able to judge where Chris starts to introduce himself from the gap in
the audio waveform displayed, but you can also switch to a zoomed view of the
waveform for even more accuracy.
23Lesson 1 Editing a Rough Cut
```
13 From the source viewer’s Options menu (…), select Show Audio Waveforms Zoomed In.
```
The waveforms now show a zoomed-in display.
24Lesson 1 Editing a Rough Cut
14 In the source viewer’s transport controls, click and hold the jog wheel to refine the
position of the playhead in the source viewer.
15 Use the jog wheel to move the playhead to just before the start of the large waveform.
TIP If you disabled audio scrubbing in the earlier steps, press Shift-S to
re-enable it. Hearing the audio scrub can help you refine the position just
before Chris starts speaking.
This is where you want the first soundbite to start. To specify this, you’ll need to add an
In point at the current playhead position.
16 In the source viewer transport controls, click the Mark In button.
25Lesson 1 Editing a Rough Cut
The clip’s In point moves from the start of the clip to the position of the playhead.
This is the portion that Resolve will edit to the timeline for you, but it’s still far too long
for your purposes. Instead, you will specify the end of the soundbite you’ll use by
adding—yep, you guessed it—an Out point!
17 Press the Spacebar to continue playing the clip from the current playhead position for
a few seconds until Chris says “…in Las Cruces, new Mexico,” and then press the
Spacebar to stop playback.
18 Using the jog wheel, again refine the position of the playhead to just before
Chris blinks.
```
TIP Press the Left Arrow to jog the playhead back 1 frame; press the Right
```
Arrow to jog the playhead forward 1 frame. See also the sidebar “Controlling
Playback” below.
26Lesson 1 Editing a Rough Cut
19 In the source viewer’s transport controls, click the Mark Out button.
The highlighted duration changes to the newly marked portion of the clip—between
the In and Out points you’ve just set.
This is the portion of the clip you’ll edit into the timeline.
TIP Press I to add an In point and press O to add an Out point.
20 Click in the middle of the source viewer and drag the clip down into the timeline,
ensuring that you drag the clip into the existing Video 1 and Audio 1 tracks and to the
start of the timeline at the far left.
NOTE If you accidentally drag the clip and add additional tracks or leave a gap
at the start of the timeline, it’s not a huge problem. You can simply drag the
clip to the right tracks and location after you’ve added it to the timeline. It’s
just that this takes a bit more time and slows down your editing slightly.
```
Alternatively, press Command-Z (macOS) or Ctrl-Z (Windows) to Undo the last
```
action and try dragging the clip to the empty timeline again.
27Lesson 1 Editing a Rough Cut
21 In the timeline viewer transport controls, click the Play button or press the Spacebar to
play the edited clip in the timeline.
Congratulations! You’ve successfully added your first clip to the timeline! Now all you need
to do is keep repeating this process for all the other clips you’ll need to build up the Organ
Mountain Outfitter’s promo.
Controlling Playback
An important part of editing is learning how to control the playback of your video.
DaVinci Resolve’s default keyboard layout supports all the usual shortcuts for
playback that professional editors around the world recognize. You can use the
Spacebar to start and stop playback and the Left Arrow and Right Arrow keys to
move forward and back one frame at a time. More experienced users will be happy
to know that the J, K, and L keys also control playback at different speeds.
J LK
The order of the JKL keys match the layout of the Play Reverse, Stop, and Play
transport controls in both the source and timeline viewers.
Try the following to practice controlling the playback of the source or
timeline viewer:
— Hold K and tap L to jog forward 1 frame.
— Hold K and tap J to jog backward 1 frame.
— Hold K and Hold L to scrub forward at half speed.
— Hold K and hold J to scrub backward at half speed.
— Press L twice to shuttle forward at twice normal speed.
— Press J twice to shuttle backward at twice normal speed.
You can keep tapping the J or L keys to increase the shuttling speed up to 64x
normal speed.
28Lesson 1 Editing a Rough Cut
Working with the Subclips
Before you start adding additional soundbites to this timeline, it’s worth considering just
how much of that first clip you used. If you look at where you added the In and Out points
on the clip in the source viewer, you’ll see that it’s only a small portion of a much larger
clip—only about 6 or 7 seconds of a clip that is about a minute long!
TIP You can tell how long a clip is, or the duration between the In and Out points
you’ve added, using the duration timecode value in the top left of the
source viewer.
This disparity between the amount of footage shot and the amount used in the edit is not
unusual and is often referred to as the shooting ratio. Depending on what’s being edited,
```
shooting ratios can vary wildly; a typical news piece might have a shooting ratio of 3:1
```
```
(for every 3 minutes shot, 1 minute was used), whereas some reality shows might have a
```
shooting ratio of around 600:1 or more!
With so much footage being captured and needing to be edited, it can sometimes be
helpful to just focus on a much smaller, relevant portion of much longer clips like Chris’s
interview. This is where subclips come in.
Subclips are discrete clips that have been isolated from a much longer clip but, because
they are still referencing the original media file, are not taking up additional storage space
on your system. You will learn how to create and manage your own subclips in Lesson 7.
For this lesson, though, your edit assistant has already created a series of subclips for you
from the much longer interview clips.
NOTE You will learn how to create your own subclips in Lesson 7.
29Lesson 1 Editing a Rough Cut
Opening Clips in the Source Timeline
While subclips are one way of dealing with lengthy clips, DaVinci Resolve 20
has another trick up its sleeve to help you navigate through long clips like
Chris’s interview.
Clicking the Timeline button at the top of the source viewer will show the current
clip in its own timeline.
This can be useful for easily finding parts of a clip since you can zoom in, zoom out,
```
and move around the footage just like in a regular timeline (see “Controlling
```
```
Timeline Zoom” later in this lesson).
```
Opening a timeline from the source viewer makes it read-only, which is
represented by a blue clip name at the top of the source viewer and a blue timeline
playhead. Read-only timelines cannot be edited. However, you can add In and Out
points and other markers to help you edit footage more efficiently.
To switch from the source timeline to your main editing timeline, simply click the
relevant viewer or press Q.
To return to the regular clip view, click the Source Clip button at the top of
the viewer.
30Lesson 1 Editing a Rough Cut
1 In the bin list, select the SUBCLIPS bin to view the subclips.
Each subclip has a unique clip name assigned to it, making it easy to recognize.
TIP To show the file names of the clips rather than the clip names used in the
project, you can choose View > Show File Names. Choose View > Show File
Names again to return to seeing the clip names.
31Lesson 1 Editing a Rough Cut
2 Double-click the clip CL SUBCLIP 1 - Experiences to open it in the source viewer, and
then play this clip through from the start.
Even though this is only about 27 seconds of a much longer interview clip, you still only
need to use a portion of it. However, because the subclip is a much more manageable
duration, it’s easier to see the waveform represented over the duration of the subclip.
```
3 Click the Options (…) menu in the source viewer and deselect the Show Audio
```
Waveforms Zoomed In option.
32Lesson 1 Editing a Rough Cut
4 Using the waveform as a guide, move the playhead to just before Chris Starts speaking
and press I to add an In point.
5 Play through the clip and then stop after Chris says, “…it’s changed my life” but before
he blinks, and press O to add an Out point.
With the In and Out points set, you can add this clip to the timeline.
6 Click in the middle of the source viewer and, again, drag the marked clip into the
timeline so that it snaps to the end of the previous clip.
7 In the timeline viewer, click the Play button or press the Spacebar to play the two clips
in the timeline.
Excellent. The soundbites seem to make sense next to each other, even though they were
taken from two different parts of the interview. Yes, there is a nasty visual jump cut as the
second interview starts, but you will fix that using some of the B-roll clips as cutaways in a
short while.
33Lesson 1 Editing a Rough Cut
Controlling Timeline Zoom
The edit page has three main options for controlling the zoom level of clips in the
timeline, which you will need to be able to use effectively as you build up your edit:
Full Extent Zoom, Detail Zoom, and Custom Zoom.
Full Extent Zoom will always display the whole duration of your timeline in the
timeline window, automatically adjusting the zoom to keep everything in sight.
This is most useful for seeing a bird’s-eye view of your edit and allows you to
navigate anywhere within the timeline, like the upper timeline in the cut page.
Detail Zoom scales the timeline to a closer, zoomed view, centered on the
playhead. This option is most useful when you want to step into the timeline to
select a clip or edit point to make fine adjustments, like the lower timeline in
the cut page.
Custom Zoom provides the most flexibility, since it allows you to set your own
zoom scale in the timeline. You can use the slider to zoom in and out of the
```
playhead location or hold Option (macOS) or Alt (Windows) and use the scroll
```
```
function on your mouse (or trackpad) to adjust the zoom of the timeline
```
dynamically, centered on the playhead.
Timeline track heights can be adjusted using the Timeline View Options menu or
by holding Shift and using the mouse scroll wheel in either the audio or video
areas of the timeline.
Useful keyboard shortcuts for zooming the timeline include:
```
— Command-= (equals) in macOS or Ctrl-= (equals) in Windows to zoom in to the
```
timeline playhead
```
— Command--(minus) in macOS or Ctrl--(minus) in Windows to zoom out of the
```
timeline playhead
— Shift-Z toggles between fitting the timeline to the timeline window and
returning to the previous zoom level
34Lesson 1 Editing a Rough Cut
Adding the Other Soundbites
The “drag and drop” approach to editing clips into the timeline you used in the previous
steps is one simple way of building up an edit. However, this is a very basic way of editing
that offers limited options. In the next steps, you will continue adding soundbites using
different editing methods that provide more accuracy and flexibility.
1 Click the Full Extent Zoom button in the timeline toolbar.
2 In the timeline, move the playhead so it snaps to the beginning of the second clip and
press the Spacebar to play the clip.
On reflection, the last part of the clip where Chris says, “I can honestly say it’s changed
my life” doesn’t really work.
3 In the timeline, place the playhead after Chris says “…the landscapes” but before he
looks away from the interviewer.
This is where you will edit the next clip into the timeline.
4 From the SUBCLIPS bin, double-click the clip CL SUBCLIP 2 - Brand and, if necessary,
return the playhead to the start of the clip.
35Lesson 1 Editing a Rough Cut
5 Play the clip in the source viewer, listening to the interview, and add In and Out points
around the soundbite where Chris says, “Our brand is really a reflection of our
community and who we are.”
This time, instead of simply dragging the clip to the timeline, you’ll use a slightly
different method of editing.
6 Drag the clip from the source viewer to the timeline viewer, but don’t immediately
release the mouse.
This time, a series of editing overlays appears showing the different types of edits
```
available to you in DaVinci Resolve. If you have used other nonlinear editing (NLE)
```
software before, you may recognize some of these functions. The default is Overwrite.
36Lesson 1 Editing a Rough Cut
7 With the Overwrite edit overlay highlighted, release the mouse button.
The clip is edited into the timeline, starting at the playhead position and overwriting the
end of the clip that was in its way.
Don’t worry, though, all this editing is completely non-destructive, and you can
always trim the clip back out later, recovering the footage that you’ve just overwritten,
if necessary.
8 Ensure that the timeline playhead is at the end of the third clip you just edited into the
```
timeline (it should be automatically unless you have moved it since the previous step).
```
9 In the SUBCLIPS bin, double-click the CL SUBCLIP 3 - #EXSW clip to open it in the
source viewer.
10 Add In and Out points around the soundbite “And that’s why we say, ‘experience
the Southwest.’”
37Lesson 1 Editing a Rough Cut
11 In the timeline toolbar, click the Overwrite Clip button or press F10 to overwrite the clip
into the timeline.
The new clip is added to the timeline, starting at the timeline playhead position.
NOTE If you’re using DaVinci Resolve on macOS, you may need to configure
your keyboard settings to use the default editing shortcuts. Select the Apple
menu, choose System Settings, and select Keyboard in the sidebar. In the
Keyboard settings, click the Keyboard Shortcuts button and select Function
Keys. Enable the option “Use F1, F2, etc. as standard function keys.” Then
select the Mission Control option and uncheck the Show Desktop option for
F11, and click Done. Alternatively, you can use the fn key with any F-key to
override the macOS shortcuts.
12 If you have moved the timeline playhead since the previous step, ensure it is at the end
of the fourth clip in the timeline.
38Lesson 1 Editing a Rough Cut
13 Double-click CL SUBCLIP 4 - Inspiration to open it in the source viewer and move the
playhead to the second group of waveforms.
This is the start of the final soundbite you will add to the timeline, but it’s a bit of a tight
edit to find the In point for when Chris stumbles slightly and says “that” twice.
However, using the zoomed audio waveform display will make it so much easier to
locate the short pause between the two “thats” quickly and accurately for a clean start
to the soundbite.
39Lesson 1 Editing a Rough Cut
14 From the source viewer’s Options menu, choose Show Audio Waveforms Zoomed In
and jog the playhead into the gap between the waveforms.
15 When the playhead is aligned after the first “that” but before the second “that,” press I
to add an In point.
```
16 Turn off the zoomed waveforms by clicking the Options menu (…) and deselecting
```
Show Audio Waveforms Zoomed In, continue playing the clip in the source viewer, and
add an Out point after Chris says, “… that’s really where the design process starts.”
40Lesson 1 Editing a Rough Cut
17 Press F10 or click the Overwrite Clip button to overwrite the clip into the timeline at the
playhead position.
This is the final soundbite you need to add to this timeline. At this point, feel free to move
the playhead back to the start of the timeline and play back the current timeline to review
the soundbites.
Reordering the Timeline Clips
The soundbites are working well as they currently sit in the timeline. However, there are
always changes you’d probably like to make. One of the most common changes at this
stage is the reordering of clips in the timeline. While you can select and move clips around
freely, DaVinci Resolve has a neat feature that makes this process fast and efficient. It’s
```
called a Shuffle Insert edit (or a Swap Insert edit).
```
1 In the timeline, select the last of the soundbite clips, CL SUBCLIP 4 - Inspiration.
41Lesson 1 Editing a Rough Cut
```
2 Choose Edit > Swap Clips Towards Left, or press Shift-Command-, (comma) in macOS or
```
```
Shift-Ctrl-, (comma) in Windows, to swap the clip with the previous clip.
```
3 Select the third soundbite clip CL SUBCLIP 2 – Brand and choose Edit > Swap Clips
```
Towards Right, or press Shift-Command-. (period) in macOS or Shift-Ctrl-. (period) in
```
Windows, to swap it with the subsequent timeline clip.
4 Play through the clips in the timeline again for a slightly better flow to the soundbites.
Using Shuffle Insert edits like this is a useful way of quickly and accurately reordering
the timeline clips into a more logical order. You can also use this technique with
multiple selected timeline clips.
NOTE If you need to catch up before moving to the next step, select the
TIMELINES bin and choose File > Import > Timeline, navigate to R20 Beginners
Guide / Lesson 01 / Timelines / OMO PROMO CATCHUP 01.drt and click Open.
Please note that whenever you import a catchup timeline using clips with synced
audio, DaVinci Resolve will attempt to reimport the separate audio clips and ask
you to search for the media files to relink. This is not necessary. Click Cancel and
remove the offline clips that have been added to the bin with the
imported timeline.
42Lesson 1 Editing a Rough Cut
Insert and Append at End Edits
Now that you have the soundbites in the timeline, you can start building out the story with
some of the B-roll footage. You will start by adding a shot at the start and end of the edit,
which will eventually be used as a background for the opening and closing titles.
1 Select the B-ROLL bin in the bin list.
All the potential B-roll footage for this edit is in this single bin but, depending on how
much footage you’re dealing with, it may be difficult to see where to start. You could
```
organize this footage further into separate bins; however, as with the subclips you
```
used earlier, this process has already been done for you using a series of keyword
smart bins.
2 In the Smart Bins list in the bottom section of the bin list, select the Keywords folder
and then click the disclosure triangle to open the list of keywords smart bins, and
select the TIMELAPSE smart bin.
43Lesson 1 Editing a Rough Cut
TIP You can resize the Smart Bins area by dragging the dividing line at the top
of the Smart Bins section of the bin list.
This smart bin contains any clips that have been identified and tagged with the
“TIMELAPSE” keyword, which is just one in this case.
3 Double-click the clip in this smart bin, ORGAN MOUNTAIN 1, to open it in the
source viewer.
This is a timelapse shot of the eponymous Organ Mountain and will serve well as a
background to the opening graphic and closing titles you will add later. Notice that In
and Out points have already been applied for you at a duration of 7 seconds.
44Lesson 1 Editing a Rough Cut
Now you will tell Resolve where in the timeline you want this clip to be edited.
4 Deselect any clips and move the timeline playhead to the start of the timeline.
5 Drag the clip from the source viewer to the timeline viewer, placing it on the Insert
overlay, and release your mouse button.
The clip is inserted into the timeline without overwriting any existing clips.
The Insert edit is an effective way to add clips to an earlier part of your edit.
By inserting the clips, the rest of the edit will move up the timeline to accept the newly
edited clip. This is different from an Overwrite edit that will simply overwrite any clips
in the way in the timeline.
45Lesson 1 Editing a Rough Cut
Another useful editing function is the Append at End edit. This does exactly what it
```
says: it adds the new clip after the last clip in the timeline.
```
6 Drag the clip from the source viewer to the timeline viewer, placing it on the Append
At End overlay.
The same 7-second clip is added to the end of the timeline.
Pacing the Soundbites
The timeline is starting to take shape, but currently all the clips are tightly edited, meaning
there’s no “breathing space” between the soundbites. This “breathing space” is important
for two reasons. First, it makes the interview sound natural and doesn’t distract the
```
audience. This best reflects how people normally speak; very rarely does someone speak
```
out loud without having to take a breath every once in a while, like a voiceover artist
reading the terms and conditions in a commercial. Second, it allows the audience to
process what’s been said. If you hit them too early with the next piece of information, the
audience might feel overwhelmed and might not take in the story or messages you’re
trying to convey, like a voiceover artist reading the terms and conditions in a commercial!
46Lesson 1 Editing a Rough Cut
To make the soundbites sound natural, you’ll introduce a short gap between each clip. The
best way to do this is to move the clips up in the timeline.
1 In the timeline toolbar, ensure that the Full Extent Zoom is selected.
2 Position the timeline playhead anywhere over the third clip in the timeline.
3 Choose Timeline > Select Clips > Forward on Track, or press Y.
This command selects all the clips forward from the timeline playhead on the
targeted track.
TIP If you have clips on multiple tracks, you can choose Timeline > Select Clips
```
> Forward on All Tracks, or press Option-Y (macOS) or Alt-Y (Windows).
```
With all the clips selected, it’s easy to move them together.
4 With the clips still selected, type +200 into the timeline viewer’s timecode field.
47Lesson 1 Editing a Rough Cut
```
5 Press Enter (Return).
```
This moves the selected clips forward by 2 seconds, leaving a gap. This is an arbitrary
amount that will most likely be adjusted later when you’re refining the timeline.
NOTE You can use the number pad of an extended keyboard to quickly enter
timecode values.
6 Press the Down Arrow key to move the timeline playhead to the next edit, and press Y
to select all the clips forward of this point.
```
7 Type +100 and press Enter (Return) to add a 1-second gap between the second and
```
third soundbites.
8 Move the playhead anywhere over the fifth clip in the timeline and press Y to again
select all the clips forward from the playhead.
```
9 Again, type +200 and press Enter (Return) to have the last three clips move forward by
```
2 seconds, leaving another gap in the timeline.
10 Place the timeline playhead anywhere over the final soundbite clip and press Y.
```
11 Type +100 and press Enter (Return) to create a 1-second gap before the payoff of this
```
video, where Chris delivers the tagline, “Experience the Southwest.”
12 Click in an empty space in the timeline to deselect all the clips in the timeline.
48Lesson 1 Editing a Rough Cut
When you play this timeline back now, it might seem very strange to have these gaps.
However, once you start covering them with the B-roll clips, Chris’s interview will sound
more natural and better paced. Think of it as the movie-making equivalent of punctuation!
NOTE If you need to catch up before moving to the next step, select the
TIMELINES bin and choose File > Import > Timeline, navigate to R20 Beginners
Guide / Lesson 01 / Timelines / OMO PROMO CATCHUP 02.drt and click Open.
Painting the Interview
Now that you have the general structure of the edit in place, you can start adding the
B-roll. This performs the dual role of making Chris’s interview come alive and covering the
gaps between the soundbites, pulling the edit into a cohesive whole. This process is often
referred to as painting since you are primarily enhancing the story through pictures. To do
this, you will set In and Out points in the timeline to specify the placement and duration of
the shots you’ll need.
1 Move the playhead so that it snaps to the end of the second clip in the timeline, where
the first gap starts.
TIP To quickly jump to the start of gaps in the timeline, you can choose
Playback > Previous > Gap or Playback > Next > Gap.
2 Press I to add an In point here in the timeline.
3 Play the timeline until Chris says, “… experience the southwest because…” and then
stop playback.
49Lesson 1 Editing a Rough Cut
4 Press O to add an Out point here in the timeline.
You have now marked a portion of the timeline where you want the first B-roll clip to
be edited.
5 Select the PINE TRAIL smart bin and double-click the first clip, PINE TRAIL 5, to open it
in the source viewer.
This is a shot of three friends, attired in Organ Mountain Outfitters clothing, walking in
the foothills of the mountains.
50Lesson 1 Editing a Rough Cut
6 Play the clip from the beginning and add an In point after you hear the director shout,
“Go ahead” and the girl is about to take her second step.
Typically, B-roll shots like this are edited on top of the interview already in the timeline
as a cutaway. DaVinci Resolve provides an editing function to make this as easy
as possible.
7 Drag the PINE TRAIL 5 clip to the Place on Top function in the timeline viewer overlays.
51Lesson 1 Editing a Rough Cut
The clip is edited between the In and Out points in the timeline, starting at the In point
you set in the viewer. The Place on Top edit has also created an extra video and audio
track to accommodate the new clip without overwriting any of the existing footage.
As before, the timeline viewer is now the active window, and the playhead is
automatically positioned at the end of the clip you just added to the timeline, ready
for you to specify where the next edit should be.
8 Without moving the timeline playhead, press I to add an In point to the timeline.
9 Play the timeline and add an Out point after Chris says “…there’s nothing like it….”
10 From the PINE TRAIL smart bin, open the clip PINE TRAIL 12 in the source viewer.
52Lesson 1 Editing a Rough Cut
11 Set an In point just as the second guy enters the frame and has his left leg
outstretched.
12 Choose Edit > Place on Top or press F12 to add the clip to the same tracks as the
previous cutaway.
53Lesson 1 Editing a Rough Cut
13 With the timeline active, press I to add an In point in the timeline, play forward, and
add an Out point after Chris says, “… ever experienced.”
14 Select the WHITE SANDS smart bin and open the shot WHITE SANDS 36 in the
source viewer.
15 Add an In point to this shot after the girl in the pink top starts to move her hair
behind her ear.
The wind noise against the camera microphone is a little off-putting for this shot.
54Lesson 1 Editing a Rough Cut
16 In the source viewer, click the video-only overlay and drag to the Place on Top overlay
in the timeline viewer.
Using the video-only overlay just edits the video portion of this clip into the timeline,
not the audio. Unfortunately, this technique only works when dragging a clip from the
source viewer into either the timeline viewer overlays or the timeline itself. If you want
to use shortcuts or editing buttons in the timeline toolbar, you must use a slightly
different control.
17 Add an In point to the playhead position in the timeline and an Out point after Chris
says, “… the culture, the food….”
55Lesson 1 Editing a Rough Cut
18 Select the PINA BLANCA smart bin, open the PINA BLANCA 70 clip in the source
viewer, and add an In point near the top of the clip where the girl is spinning the
flaming torches.
19 In the timeline, click the destination control for A1 to disable it.
Turning this control off prevents the audio from the source clip from being edited into
the timeline while allowing you to use editing shortcuts.
56Lesson 1 Editing a Rough Cut
20 Press F12 to make a Place on Top edit.
21 Add an In point to the timeline directly after the shot you’ve just edited, and an Out
point after Chris says, “…. really inspires us….”
57Lesson 1 Editing a Rough Cut
22 From the media pool, open the clip PINA BLANCA 44 and add an In point when the
guy is about to jump onto the rock.
23 Press F12 to make a Place on Top edit.
Hopefully, you can see just how powerful an understanding of the different editing
techniques can be to quickly add a series of cutaways like this. These shots will likely need
trimming, but before you turn your attention to that, you will add a few more cutaways to
the end of the interview using a variation of the technique you’ve just been using.
NOTE If you need to catch up before moving to the next step, select the
TIMELINES bin and choose File > Import > Timeline, navigate to R20 Beginners
Guide / Lesson 01 / Timelines / OMO PROMO CATCHUP 03.drt and click Open.
58Lesson 1 Editing a Rough Cut
Using Source Tape
If you are working with a series of clips in the media pool, instead of opening each
clip in turn as you have in the last few steps, you can instead open all the clips in
```
the currently selected bin(s) in the source viewer’s Source Tape mode. Simply click
```
the Source Tape button to view all the clips in the current Sort order.
Source Tape allows you to browse through large amounts of clips effortlessly,
without having to manually open each one in turn. You can add In and Out points
as you have been doing in the previous steps.
Enabling Timeline mode after Source Tape enables you to open the Source Tape in
the timeline, giving you a greater degree of control when navigating around the
footage in the Source Tape and, again, allowing you to add In and Out points with
more precision.
To switch from the Source Tape timeline to your main editing timeline, simply click
the relevant viewer or press Q.
To return to the regular clip view, click the Source Clip button at the top of
the viewer.
59Lesson 1 Editing a Rough Cut
Backtiming Edits
When you were adding the first set of cutaways to Chris’s interview, you were specifying
where each of those shots would start based on the placing of the In point. However, there
are certain circumstances when you’ll want to edit a clip into the timeline and specify
where that shot should end. This process is often referred to as backtiming.
1 Play the third interview clip in the timeline, adding an In point just after Chris says,
“…we bring it back to the store….”
2 Press the Down Arrow to jump to the next edit point in the timeline, and press O to
add an Out point.
NOTE The playhead in DaVinci Resolve is inclusive of the current frame, which
in practice means that In points are always added at the head, or start, of the
frame, and Out points are always added at the tail, or end, of the frame. This
means the minimum duration you can mark is 1 frame.
3 Select the RETAIL smart bin, locate the clip named STORE 2, and open it in the
source viewer.
60Lesson 1 Editing a Rough Cut
This is a clip of Organ Mountain Outfitters’ lead designer creating their latest T-shirt
design on the computer.
4 Locate the frame, near the beginning of the clip, just before the large black
circle appears.
This is where you want this shot to end.
5 Add an Out point at this frame.
In this case, because there is just an Out point and no In point in the source viewer, the
clip will be edited to the timeline as expected, but the two Out points will be aligned,
meaning the shot will then be backtimed to the timeline In point.
TIP If you need to remove an In point, you can choose Mark > Clear In or
```
press Option-I (macOS) or Alt-I (Windows). Similarly, to remove an unwanted
```
```
Out point, choose Mark > Clear Out or press Option-O (macOS) or Alt-O
```
```
(Windows). To remove an In and Out point simultaneously, choose Mark >
```
```
Clear In and Out or press Option-X (macOS) or Alt-X (Windows).
```
61Lesson 1 Editing a Rough Cut
6 Press F12 to make a Place on Top edit.
Next, you’ll add a cutaway to help bridge the next gap.
7 Add an In point to the start of the gap in the timeline.
8 Play forward and add an Out point after Chris says, “Our brand is just really a
reflection of….”
9 From the RETAIL smart bin, open the STORE 34 clip in the source viewer.
This clip is a lengthy sequence of a shirt making its way out from the design studio
to the shop shelves. You need only the last part of this ambitious shot, though
```
(apologies to the director!).
```
62Lesson 1 Editing a Rough Cut
10 In the source viewer, locate the frame where the girl hangs the T-shirt up and has left
```
the frame (near the end of the clip), and mark an Out point.
```
11 Press F12 to make a Place on Top edit.
63Lesson 1 Editing a Rough Cut
12 Add an In point to the current playhead location in the timeline, and an Out point after
Chris says, “That’s why we say….”
13 From the RETAIL smart bin, open the clip STORE 28 in the source viewer.
14 Add an Out point on a frame just after the girl in the black hat has exited the store and
releases the door.
64Lesson 1 Editing a Rough Cut
15 Press F12 to make a Place on Top edit, with the audio.
With the final cutaway in place, all the jump cuts and gaps between Chris’s soundbites have
been covered. There’s just one final element to add to this timeline to complete the
rough cut.
NOTE If you need to catch up before moving to the next step, select the
TIMELINES bin and choose File > Import > Timeline, navigate to R20 Beginners
Guide / Lesson 01 / Timelines / OMO PROMO CATCHUP 04.drt and click Open.
Adding the Music
```
Music is such an important part of many edits. Whereas the spoken word (scripted
```
```
dialogue, interviews, or narration) will often convey what we need to know about a subject,
```
music will most often convey what we should feel about a scene or subject. Get the music
wrong and the whole edit might communicate the wrong impression completely!
Thankfully, in this case the music has been carefully chosen for you. All you have to do is
add it to the current timeline.
1 Ensure that the timeline viewer is selected and press Home to return the playhead to
the start of the timeline.
65Lesson 1 Editing a Rough Cut
2 In the timeline, click the A1 destination control to ensure you can edit audio into
the timeline.
3 Select the MUSIC bin from the bin list in the media pool and open the
ONE MIN SOUNDTRACK.wav clip in the source viewer.
NOTE When viewing audio-only clips such as this, the source viewer
automatically switches to Audio Track mode.
You can add In and Out points to audio clips just as you’ve done throughout this
lesson. In this case, though, it’s unnecessary because the music is already just under a
minute in length, which is the desired duration for the whole edit.
66Lesson 1 Editing a Rough Cut
4 Press F12 to make a Place on Top edit to add the music clip to a new audio track.
```
The only thing left to do now is attenuate (reduce) the volume of the audio clip so that
```
it more closely matches the rest of the audio in the timeline. It doesn’t have to be the
ideal level at this time—just low enough that it doesn’t overpower the other elements
in the timeline as you continue to refine it in the next lesson.
5 Place your mouse over the volume overlay for the audio clip in the timeline, which is
represented by a thin white line running through the length of the clip.
6 Click and hold the volume overlay and drag down to reduce the volume of the clip until
the tooltip reads about -18 dB.
TIP Hold Shift while adjusting the volume overlay for more precise control.
7 Press Home to return the playhead to the start of the timeline and play back to review
the rough cut with the music.
67Lesson 1 Editing a Rough Cut
Congratulations! You have completed this first lesson and successfully assembled a rough
cut of the Organ Mountain Outfitters promo. Remember, this lesson was about being able
to quickly put together a rough cut using the editing tools available in the edit page.
However, there is still much, much more to do to refine this timeline before it’s ready to
show to the client at Organ Mountain Outfitters. This will be the focus of the next lesson.
Lesson Review
1 Where do you access the projects for the current project library?
```
a) Project Manager
```
```
b) Media page
```
```
c) The current user’s Documents folder on your computer’s file system
```
2 What element is most often used to organize unedited clips in DaVinci Resolve?
```
a) Timelines
```
```
b) Thumbnails
```
```
c) Bins
```
3 Which zoom function allows you to manually zoom in and out of the timeline?
```
a) Full Extent Zoom
```
```
b) Detail Zoom
```
```
c) Custom Zoom
```
4 Which of the following can be used to separate long clips into more manageable clips?
```
a) Source clips
```
```
b) Master clips
```
```
c) Subclips
```
5 What is the name given to an edit that uses a combination of two Out points and only
one In point?
```
a) Reversed edit
```
```
b) Backtimed edit
```
```
c) Append edit
```
68Lesson 1 Editing a Rough Cut
Answers
```
1 a) The Project Manager contains all the projects for the current project library,
```
although project libraries themselves can be stored locally, on a network, or in the
Blackmagic Cloud.
```
2 c) Bins are most commonly used to organize imported clips in DaVinci Resolve.
```
```
3 c) Custom zoom allows you to change the zoom around the playhead manually. You
```
```
can use the custom zoom slider, keyboard shortcuts, or Option-scroll (macOS) or
```
```
Alt-scroll (Windows).
```
```
4 c) Subclips.
```
```
5 b) Backtimed edit.
```
Time
This lesson takes approximately
75 minutes to complete.
Goals
Setting Up the Project 70
Duplicating and
Managing Timelines 70
Trimming the Timeline Clips 76
Replace Edit 89
Visual Effects 98
Adding the Logo 122
Adding the Closing Titles 130
Lesson Review 139
Lesson 2
Finessing the
Rough Cut
In the previous lesson, you created a
rough cut for a short promotional video
for the outdoor clothing brand Organ
Mountain Outfitters. For many, knowing
how to quickly create an edit like this is
often enough. However, for many other
editors, this is only the beginning. Now
that the basic structure of the edit has
revealed itself, it’s time to precisely
fine-tune each individual shot and edit
so that the piece is as polished as it can
possibly be.
To apply the 80/20 rule: the rough
cut you created in Lesson 1 has
accomplished about 80% of the editing
required for the promo, but this should
be accomplished quickly—within
20% of the available editing time.
```
The remaining 20% of the editing (the
```
```
trimming, audio mixing, graphics, etc.)
```
will then take up the remaining 80% of
the time! As you can see, the job is far
from finished!
70Lesson 2 Finessing the Rough Cut
Of course, part of the job of the editor is to deliver the final project to meet a deadline—
you wouldn’t want to miss the movie’s opening night!—so it’s not surprising that many feel
```
that a job is never really “completed”; it’s more that you just run out of time and money!
```
Setting Up the Project
This lesson starts exactly where Lesson 1 finished. If you completed Lesson 1, you may
proceed to the next section in this lesson, “Duplicating and Managing Timelines.”
However, if you didn’t fully complete the previous lesson, you can always import a catch-up
timeline to help you get started with this lesson.
NOTE The following steps assume that you have at least completed the first part
```
of Lesson 1 and that you have imported the OMO Promo (Organ Mountain
```
```
Outfitters promo) project file into your current project library and relinked the
```
offline media. If you haven’t, complete those steps as detailed in Lesson 1 before
continuing with the following steps.
1 Open DaVinci Resolve and, in the Project Manager, double-click the OMO Promo
project to open it in DaVinci Resolve.
2 If necessary, ensure that the edit page is selected.
3 In the bin list, select the TIMELINES bin and choose File > Import > Timeline.
4 Navigate to R20 Beginners Guide/Lesson 02/Timelines, select the file OMO PROMO
CATCHUP 05.drt, and click Open.
The timeline is imported into the selected bin in your project and automatically opens in
the timeline viewer. You can now continue with this lesson.
Duplicating and
Managing Timelines
It’s generally good practice to duplicate your current timeline before you start making
```
major changes because if you (or your client/director) don’t like the subsequent changes
```
you make, you always have a backup copy of the timeline to return to.
1 Choose Timeline > Find Current Timeline in Media Pool to quickly reveal the currently
active timeline in its bin.
71Lesson 2 Finessing the Rough Cut
2 Right-click the current timeline and choose Duplicate Timeline.
A copy of the timeline is created in the same bin.
This duplicate of your active timeline has the same name but with the word copy added
to the end to signify that this is the duplicated timeline.
Many editors often like to rename the duplicated timeline, usually replacing “copy” with a
```
version number (v1, v2, v3, etc.) so they know what they are looking at in the bin. However, if
```
you leave the name of the duplicated timeline as is, subsequent duplication of the original
timeline will result in the name of the new duplicated timeline being incrementally increased
```
(copy, copy 1, copy 2, etc.). This is a useful technique since, firstly, it always means the version
```
of the timeline you’re working on is the latest, and, secondly, the automatic names of the
duplicated timelines can help to “backtrack” to a previous version of the timeline if needed.
72Lesson 2 Finessing the Rough Cut
NOTE If you need more detail about when a particular timeline or copy was
created, you can click the “I” button in the bottom right of the timeline thumbnail.
Alternatively, you can view the Date Modified column using List View in the media
pool. You will learn more about the different views in the media pool in Lesson 7,
“Project Setup and Preferences.”
Restoring a Timeline Backup
Duplicating timelines is a useful step for the reasons outlined above, but it is a step you
must undertake manually. Occasionally, you may find yourself in the situation where you’ve
been so caught up in the creative process of editing that you have completely neglected to
duplicate your timeline! In this case, it would be very difficult to rewind the clock and go
back to an earlier version without having to use so many Undo commands that the Z key
on your keyboard would wear away!
Never fear, though, because DaVinci Resolve has your back and is saving backups of your
timelines as you work on them.
1 If necessary, choose Timeline > Find Current Timeline in Media Pool to reveal the active
timeline in its bin.
2 Right-click the timeline and choose Restore Timeline Backup.
A list of backups is revealed, date and time-stamped when the backup was created.
73Lesson 2 Finessing the Rough Cut
3 Choose a backup timeline to restore.
The backup timeline doesn’t overwrite the original timeline but adds the restored timeline
to the current bin as a separate timeline with the word “Backup” added to the
timeline name.
NOTE If the Restore Timeline Backup option isn’t available, then no backups are
available for that timeline. In this case, make a few changes and check again after a
few minutes’ work. The time increments between each timeline backup can be
viewed and adjusted by using DaVinci Resolve’s User Preferences, which you will
explore in more detail in Lesson 7.
Disabling Unused Timelines
Projects often contain many timelines: different versions of the same edit you create
```
yourself, possibly different cuts of the same material (such as a “Director’s Cut”), timelines
```
containing separate scenes, and even backups you need to restore. You might want to
keep many of these timelines in the project in case they are useful later, especially if you
ever need to restore a deleted scene without having to re-edit it from scratch!
You can use bins to help organize these duplicated timelines so that you always know
which timeline you should be working on. Alternatively, you can always disable a timeline
you’re not using.
74Lesson 2 Finessing the Rough Cut
```
1 To disable any unused timeline(s), select the timeline(s) in the media pool and then
```
```
right-click them and choose Disable Timeline(s).
```
A disabled timeline’s thumbnail is replaced by a struck-through eye.
Disabled timelines cannot be opened without first re-enabling them, and they won’t
appear in the timeline viewer dropdown list.
2 To re-enable a previously disabled timeline so you can open it and use it again,
```
right-click the disabled timeline(s) in the media pool and choose Enable Timeline(s).
```
75Lesson 2 Finessing the Rough Cut
You now have a greater degree of understanding when it comes to managing your working
timelines and restoring backups. Ensure that you have at least one backup of the current
OMO PROMO timeline in the media pool, and you can now continue to finesse the Organ
Mountain Outfitters promo.
The Editor’s Art
Trimming is the term given to adjusting a clip’s In and Out points once it is in the
timeline and is arguably the most important skill an editor possesses. Trimming
allows you to adjust the start of a clip, the end of a clip, the start and end of a clip,
or, in certain circumstances, the start and end of other timeline clips.
DaVinci Resolve has one of the most flexible, fully featured trimming toolsets of
```
any nonlinear editor (NLE), allowing you to perform complex timeline adjustments
```
intuitively and precisely.
Beyond simply cutting a clip and removing large sections of unwanted footage,
trimming in DaVinci Resolve generally occurs in one of two timeline modes:
Selection mode or Trim Edit mode.
— Selection mode allows you to move clips around the timeline and adjust their
durations simply and easily. This is the most intuitive way to begin trimming
clips in Resolve’s timeline.
— Trim Edit mode unlocks the true power of the trimming functions. In this
mode, you can ripple edit points, as well as slip the content of a shot and slide
the position of a shot in relation to its neighboring clips.
All the trimming features in Resolve can also be applied to multiple clips or
multiple edit points simultaneously and can be made by clicking and dragging with
your mouse or using keyboard shortcuts for the utmost precision.
NOTE If you need to catch up before moving to the next step, select the
TIMELINES bin and choose File > Import > Timeline, navigate to R20 Beginners
Guide / Lesson 02 / Timelines / OMO PROMO CATCHUP 05.drt and click Open.
76Lesson 2 Finessing the Rough Cut
Trimming the Timeline Clips
In the previous lesson, you added a series of cutaways to “paint” the interview by adding In
and Out points to the timeline and quickly editing the B-roll footage using the Place on Top
edit. Following the steps in the lesson, you didn’t spend much time reviewing each of those
edits as you made them, focusing instead on just getting the material into the timeline.
Now, though, you can start to consider how those shots are working together, trimming
each one as appropriate.
You will begin by trimming some of the clips in the OMO Promo timeline using Selection mode.
1 Place the timeline playhead at the beginning of the first interview clip and review the
first group of cutaways on the Video 2 track.
The edit is functional but feels a little loose, especially coming out of the interview clip
into the first cutaway of the friends walking up the path in the foothills.
2 Return the playhead to the start of the first clip on Video 2, PINE TRAIL 5.
3 Click the Detail Zoom button to zoom in on the playhead position in the timeline.
4 Select the clip on Video 2 to select PINE TRAIL 5 and drag it backward by about a
```
second (-01:00 in the tooltip).
```
Unfortunately, moving the clip like this has left a gap in the cutaways, which
disconcertingly cuts back to the underlying clip of Chris’s interview on V1. You will
need to trim the start of the next clip on Video 2 to fill this gap.
77Lesson 2 Finessing the Rough Cut
5 Scroll along the timeline a little, and then click the start of the second clip on Video 2,
PINE TRAIL 12, and drag backward until it snaps to the end of the previous clip.
This process has lengthened the second clip by one second to fill the gap created
when you moved the first clip.
NOTE The white outline shows the available handles for the trimmed
clip—that is, the portion of this clip not currently being used in the timeline
but that can still be used if required.
6 Return the playhead to the start of the first interview clip and play back to review the
changes you’ve just made.
Slipping Clips
Simply bringing the first cutaway in slightly earlier makes the edit feel a little “tighter,” but
the edit point between the first and second cutaway clips now feels a little more awkward
because you’ve changed the point at which the second clip starts. To refine this edit point,
you will slip each shot in turn using Trim Edit mode.
1 Click the Trim Edit Mode button in the timeline toolbar or press T.
The Trim Edit button turns red to indicate that Trim Edit is now active. You will also see
that the mouse pointer has changed from the arrow of Selection mode to a
trim symbol.
78Lesson 2 Finessing the Rough Cut
2 Move your mouse pointer over PINE TRAIL 5.
The Trim Edit mode is contextual, meaning that it will have different functions
depending on where you place your cursor. When you place your mouse pointer over
the middle of the clip, the trim symbol changes to a slip icon to reflect the type of trim
you are about to perform.
3 With the slip icon displayed, click PINE TRAIL 5 and drag left in the timeline.
This time, because you are in Trim Edit mode, the clip does not move in the timeline.
Instead, you will see that you are slipping the clip within its own In and Out points!
The timeline viewer has automatically changed to a four-up multi-view preview of the
change you’re making.
79Lesson 2 Finessing the Rough Cut
```
The top two images show the start and end (the In and Out points) of the currently
```
selected clip, PINE TRAIL 5, and the bottom two images show the last frame of the
```
previous timeline clip (Chris’s interview on V1, CL INTERVIEW Tk2) and the first frame
```
```
of the following timeline clip (the second cutaway on Video 2, PINE TRAIL 12).
```
In the timeline itself, you will also see a white outline extending from the start and end
of the clip being slipped, again indicating the available handles of that clip.
4 With PINE TRAIL 5 selected, drag to the left to slip the shot until the top-right image
in the multi-view preview shows the guy in the red shirt stepping forward with his left
```
leg forward (about -01:00 in the tooltip), and then play the first clip on Video 2 to
```
review the change.
Things seem to work well. However, it’s always worth playing with an edit to see how it
might be further improved.
80Lesson 2 Finessing the Rough Cut
5 Select PINE TRAIL 12 and slip it to the left so that the top-left image in the muti-view
preview has the same guy with his left leg extended in a similar manner.
```
TIP You can use the lower-left image (which now shows the last frame of
```
```
PINE TRAIL 5) to help visually match the two shots.
```
6 Return the timeline playhead to the beginning of the first interview clip on Video 1 and
play back to review the changes you’ve just made.
Even though you haven’t adjusted the timing of the gap between the two interview
clips on Video 1, by trimming and finessing the edit between the cutaway shots, the
edit feels slightly tighter as a result.
NOTE More often than not, you will find that you need to use different
trimming operations in combination. In the previous steps, you trimmed
the start of one clip but then needed to slip both clips to refine how the
first shot cut to the second. As you will see, this is common to most
trimming operations.
81Lesson 2 Finessing the Rough Cut
Rolling Edits
Another useful trimming function is the roll edit, which allows you to reposition an edit
point by trimming two neighboring clips at the same time.
NOTE In DaVinci Resolve, roll edits can be made in both Selection and Trim Edit
```
modes; the functionality is the same.
```
1 Position the timeline playhead at the start of PINE TRAIL 12 and play the next
four cutaways.
The shot of the four friends smiling for the camera, WHITE SANDS 36, is a little short
when viewed in context with the other cutaways.
2 Place your mouse pointer over the center of the edit between WHITE SANDS 36 and
PINA BLANCA 70, so it displays the roll icon.
```
3 Click to select both sides of the edit: the end, or Out point, of WHITE SANDS 36 (referred
```
```
to as the outgoing clip) and the start, or In point, of PINA BLANCA 70 (referred to as the
```
```
incoming clip).
```
82Lesson 2 Finessing the Rough Cut
```
4 Trim the selected edit to the right for about 20 frames (+00:20 in the tooltip) or until
```
the two shots appear to be similar durations.
This rolling trim adds footage to the end of the outgoing clip but also trims the same
duration of footage from the start of the incoming clip, so it doesn’t leave a gap.
5 Return the timeline playhead to the start of WHITE SANDS 36 and review the change
you’ve just made.
6 Now that the timing of each of the cutaways seems to work better, click the Full Extent
Zoom button to zoom out and see the entire timeline.
Creating Split Edits
Rolling edit points is most useful when it comes to creating split edits. Split edit is the term
used to refer to an edit for which the sound and picture cut at different times and is a
technique employed by editors in all genres around the world.
NOTE Technically, you have already made a basic split edit when you moved the
PINE TRAIL 5 clip back a second, overlapping the end of CL INTERVIEW Tk2
before Chris finishes speaking.
To see how split edits are created, you will roll the video edit between the opening shot
and the first interview clip so that Chris starts his introduction while the viewer is still
looking at Organ Mountain.
1 In the timeline, place the playhead on the edit of the opening timelapse shot of Organ
Mountain, ORGAN MOUNTAIN 1 and CL INTERVIEW Tk2.
2 Click the Detail Zoom button to increase the timeline zoom so it’s easier to concentrate
on this edit.
At this point, you will only want to adjust the video edit, not the audio edit.
83Lesson 2 Finessing the Rough Cut
3 In the timeline toolbar, click the Linked Selection button.
Linked Selection is used for automatically selecting both the video and audio parts of
linked timeline clips and makes it easy to quickly trim both parts of a clip together.
Linked clips are indicated by the presence of the chain icon before the clip name in
the timeline.
4 Click the edit point between the ORGAN MOUNTAIN 1 and CL INTERVIEW Tk2 clips
to select just the video edit point.
NOTE You can move the playhead out of the way so it’s easier to see the
edit point.
```
5 Drag the Selected edit point forward by about 15 frames (+00:15 in the tooltip).
```
You can also use the two-up display in the timeline viewer to view the outgoing and
incoming sides of the edit, so you can adjust the edit visually when Chris has lowered
his hand to his knee in the incoming shot.
84Lesson 2 Finessing the Rough Cut
NOTE This type of split edit is often referred to as a J-cut because of the
implied shape it creates between the video and audio edits. Rolling the video
edit to the left of the audio edit creates an L-cut.
This results in the ORGAN MOUNTAIN TIMELAPSE clip extending slightly into the
CL INTERVIEW Tk2 visuals and over the audio.
6 Once complete, review the change you’ve just made.
Split edits like this are very powerful since they help an edit knit together better. Rather
than a clumsy sound and picture cut, you now have a sophisticated edit in which Chris’s
audio preempts the visual cut, making it feel a little less abrupt.
Ripple Trimming
Another powerful function of the timeline’s Trim Edit mode is the ability to ripple edit
points. Rippling edits is very useful when you want to refine the timing or pacing of shots
```
because, unlike with Selection mode, the changes you make aren’t confined to the clip(s)
```
you have selected. Instead, the change in duration ripples through the rest of the timeline.
In the current timeline, you can use a ripple edit to adjust the pacing of the gaps between
the interview clips.
85Lesson 2 Finessing the Rough Cut
1 Click the Full Extent Zoom button to view the entire timeline.
```
2 Click the Linked Selection button or press Shift-Command-L (macOS) or Shift-Ctrl-L
```
```
(Windows) to re-enable Linked Selection.
```
3 With Trim Edit mode still selected, click on the outgoing edit of the second gap, just
before the third interview clip, CL SUBCLIP 4 – Inspiration.
Even though there isn’t actually a clip at this point in the timeline, the “outgoing” part
of the gap is selected.
NOTE On a laptop, you might need to zoom in closer to this edit to select
it effectively.
4 Drag the selected edit point to the right to begin lengthening the gap.
As you do this, you’ll notice that all the other clips starting after the selected edit are also
being adjusted based on the change you’re making. This is the power of ripple edits.
However, the clip covering the gap between the second and third interview clips,
PINA BLANCA 44, isn’t included in this change because it starts before the selected
edit. As a result, that clip’s position remains unchanged, so you will end up cutting
back to Chris’s interview at a different place!
86Lesson 2 Finessing the Rough Cut
While it should be no problem to simply roll the end of the cutaway of the guy on the
rock, sometimes it’s easier to trim multiple edit points together.
```
5 Release the mouse button and choose Edit > Undo or press Command-Z (macOS) or
```
```
Ctrl-Z (Windows) to undo any changes that you might have made to this edit.
```
TIP You can view a complete list of the steps you can undo and redo by
choosing Edit > History > Open History Window.
```
6 With the end of the gap still selected, Command-click (macOS) or Ctrl-click (Windows)
```
the end of PINA BLANCA 44 on VIDEO 2.
By selecting both of these edit points, you can now trim them together.
7 Drag the selected edit on Video 2 to the right to add about 1 second to the duration of
this clip and the selected gap below.
8 Play back this part of the timeline to review the change.
Finally, you will adjust the final gap between the soundbite clips by rippling the start of
the final clip on Video 2.
87Lesson 2 Finessing the Rough Cut
9 Click the start of STORE 28.
```
10 Ripple the start of the STORE EXTERIOR SIGN clip backward by a second (-01:00 on
```
```
the tooltip).
```
By ripple trimming the start of the clip on Video 2, all clips that start after this point will
also be rippled. This has the effect of increasing the duration of the gap below the
STORE EXTERIOR SIGN clip.
Sliding Clips
The fourth type of trim that you can make in Trim Edit mode is the slide edit. Slide edits are
probably the least used type of trimming operation, but it’s still useful to know that they’re
available to you.
Like a slip edit, slide edits are made to selected clips, but they affect the outgoing and
```
incoming clips on either side of the selected clip(s). The net result is that the clip slides
```
between the two clips on either side.
1 Place the timeline playhead over the middle of the final three cutaways on Video 2 and
click the Detail Zoom button.
2 If necessary, readjust the timeline zoom and scroll so you can comfortably see the
three clips on Video 2.
88Lesson 2 Finessing the Rough Cut
3 Ensure that the timeline is still in Trim Edit mode and place your mouse pointer over
the lower part of the second of the final three middle cutaways, where you can read
the name of the clip, STORE 34.
When in Trim Edit mode, the cursor changes to the slide icon when placed over a
clip’s name bar.
4 With the slide icon displayed, click and hold STORE 34 and drag right, pressing N to
```
disable snapping if necessary to slide the clip by 1 second (+01:00 in the tooltip).
```
TIP When you disable snapping by pressing N when in the middle of adjusting
a clip like this, snapping will be automatically re-enabled when you release the
mouse button.
89Lesson 2 Finessing the Rough Cut
When sliding the clip, you’ll notice in the four-up preview viewer that the two lower
clips are being adjusted.
These are the outgoing and incoming frames of the two clips on either side of
STORE 34 in the timeline: STORE 2 and STORE 28, respectively.
Excellent! You should now have a fuller appreciation of how DaVinci Resolve’s Trim Edit
mode functions in practice.
NOTE If you need to catch up before moving to the next step, select the
TIMELINES bin and choose File > Import > Timeline, navigate to R20 Beginners
Guide / Lesson 02 / Timelines / OMO PROMO CATCHUP 06.drt and click Open.
Replace Edit
Another useful function that can help you finesse the edit is the replace edit. This type of
edit allows you to quickly change an existing clip in the timeline for alternative takes or
even completely different shots.
90Lesson 2 Finessing the Rough Cut
The replace edit is slightly different from the editing functions you’ve learned previously
because it primarily uses the positions of the timeline and source playheads to align the
edits, rather than the traditional In and Out points.
1 In the timeline, play the final interview clip and listen to Chris deliver his “experience
the southwest” tagline.
Arguably, it’s not exactly his best delivery, especially since this is the final dialogue of
this promo video. Luckily, this wasn’t the only take of this spoken line.
2 Click the Detail Zoom button to zoom in to the clip and place the timeline playhead
where Chris begins to say, “And that’s why we say…” using the waveforms as a guide.
3 From the INTERVIEW smart bin, double-click the clip CL INTERVIEW Tk7 to open it in
the source viewer.
91Lesson 2 Finessing the Rough Cut
This clip contains a marker to help you locate the correct part of this clip.
TIP You can add your own markers to a clip in the source, in the timeline, or to
the timeline itself by pressing M. Double-click any existing marker to change
the name and color of the marker and add comments or keywords. You will
learn more about adding and working with markers in later lessons.
4 If the source viewer playhead is to the left of the marker, press Shift-Down Arrow to
```
jump forward to the marker; if the source playhead is to the right of the marker, press
```
Shift-Up Arrow to jump back to the marker.
Once the playhead is on the same frame as the marker, an overlay in the source viewer
shows details about the marker.
92Lesson 2 Finessing the Rough Cut
5 Drag the clip from the source viewer to the replace edit in the timeline viewer overlays.
The clip in the timeline is replaced by the clip in the viewer. Notice that the marker from
the source clip appears under the position of the timeline playhead.
However, as this alternative take of the “experience the southwest” line was delivered
slightly slower than the one you originally used, you’ll need to do a bit of trimming.
6 If required, press T to enable Trim Edit mode and ripple trim the end of the new clip by
```
about 1 second (01:00 in the tooltip).
```
93Lesson 2 Finessing the Rough Cut
7 Roll the end of the last clip on Video 2, STORE 28, so that you cut back to Chris’s final
interview clip on Video 1 after he has put his hands on his knees.
The replace edit is one of the most useful types of edits beyond the usual overwrite
and insert edits. In fact, it’s so common to use the replace edit that it is one of only
three editing functions available in the timeline toolbar.
NOTE On macOS systems, you might need to make a further change to the
default keyboard functions in order to use F11 as the shortcut for replace edits.
Select the Apple menu > System Settings and choose Keyboard > Shortcuts >
Mission Control, and either deselect or change the shortcut used for
Show Desktop.
Specifying Destination Tracks
In the previous lesson, you started by editing a series of clips onto the first video and audio
tracks in the timeline: Video 1 and Audio 1. The clips you subsequently added as cutaways
```
were edited onto additional tracks (Video 2 and Audio 2, and then Audio 3 for the music)
```
using the Place on Top edit, which automatically created those additional tracks as they
were needed.
94Lesson 2 Finessing the Rough Cut
NOTE You can create new tracks manually by right-clicking the track controls for
any track in the timeline and choosing Add Tracks. Right-clicking the controls for a
```
video track will allow you to create a new video track directly above it (e.g., right-
```
clicking the track controls for Video 2 and choosing New Track will automatically
```
create a Video 3 track) and right-clicking the track controls for an audio track will
```
allow you to create a new audio track below it. If you wish to add multiple video
and/or audio tracks, right-click the controls for any track and choose Add Tracks.
However, if you wish to edit directly to an existing track, you will need to specify that track
using the destination controls in the timeline track headers.
1 Click the Full Extent Zoom button to see the entire timeline.
2 Place the timeline playhead at the start of the third clip on Video 2, WHITE SANDS 36,
and click the Detail Zoom button.
This shot is OK, but there’s another shot that might work better instead. Time for
another replace edit.
3 Select the WHITE SANDS keyword smart bin to view the clips for this location.
4 Double-click WHITE SANDS 11 to open the clip in the source viewer.
95Lesson 2 Finessing the Rough Cut
5 In the source viewer, place the playhead at the point where the girl on the left raises
her head and smiles.
Because the clip you want to replace is on Video 2, you’ll need to change the timeline
destination controls to specify that you want to edit that track.
6 In the timeline, change the V1 destination control to the Video 2 track by clicking the
V2 source control.
7 Click the A1 destination control to disable audio editing and prevent the audio on the
destination track from being replaced as well.
96Lesson 2 Finessing the Rough Cut
TIP A series of commands for changing the various video and audio
destination controls can be found by choosing Timeline > Track
Destination Selection.
8 Click the Replace Clip button in the timeline toolbar or press F11 to perform a replace
edit and replace WHITE SAND 36 with WHITE SANDS 11.
Replace edits are so powerful and quick. You can also use In and Out points to refine
the portion of the timeline being replaced.
9 Place the timeline playhead at the start of the fifth clip on VIDEO 2, PINA BLANCA 44,
and add an In point.
10 Add an Out point about 2 seconds later, as the guy reaches the top of the rock.
97Lesson 2 Finessing the Rough Cut
11 From the PINA BLANCA keyword smart bin, open the clip PINA BLANCA 48 in the
source viewer and locate a frame about halfway through the clip that most closely
matches the frame in the timeline viewer.
12 Press F11 to perform a replace edit between the In and Out points you set on
the timeline.
13 Review the change you’ve just made.
An advantage of using the replace edit, rather than a backtimed overwrite edit, is that you
don’t need to add any In or Out points in the source viewer. Indeed, any In or Out points in
the source viewer will be ignored whenever you make a replace edit. Also, when you perform
replace edits, the source and timeline playheads can be placed on frames outside the In
and Out points in the timeline, but the portion of the source footage replaced within the
In and Out points will be calculated from the offset of the In and Out points from the
playheads. This makes it a much more flexible editing function in this situation.
NOTE If you need to catch up before moving to the next step, select the
TIMELINES bin and choose File > Import > Timeline, navigate to R20 Beginners
Guide / Lesson 02 / Timelines / OMO PROMO CATCHUP 07.drt and click Open.
98Lesson 2 Finessing the Rough Cut
Visual Effects
In addition to using industry-standard professional editing tools and functions to assemble
and trim your footage into the story you want to tell, the edit page also contains several
controls that allow you to enhance or fix the clips directly in the timeline.
You will explore some of the ways you can adjust the audio clips in the next lesson, but for
now you will continue to focus on the visual aspects of this timeline starting with a simple
but very common change you’ll often need to make: changing the framing of a shot.
About Real-Time Performance and the Render Cache
DaVinci Resolve is high-performance software that is optimized to deliver real-time
effects at high resolutions on a variety of workstations. To ensure that your system
is maintaining real-time performance, you can check the GPU and frame rate
playback indicator at the top of the viewers. If the indicator is green, all is well.
However, if it changes to red, this indicates that the available GPU power of your
computer is insufficient for real-time playback, and the frame rate indicator drops
accordingly. Depending on your system specifications, this is probably most
noticeable when trying to play back clips with multiple color corrections or a
portion of the timeline with many effects and/or titles.
When your real-time performance drops, one of the simplest solutions is to enable
the Render Cache by choosing Playback > Render Cache and choosing one of the
three options:
— Off No render caching takes place, and all timeline clips, grades, effects, and
titles are attempted to be played in real time.
— Smart Automatically caches intensive effects and timeline clips in formats
judged too processor-intensive to play in real time.
— User Allows you to manually specify which timeline clips will be cached,
along with automatically caching all Fusion titles and effects as part of the
```
Project Settings (see Lesson 7, “Project Setup and Organization”).
```
Smart is arguably the easiest option to use since it will do much of the work for
you, and you can always manually flag a clip to cache by right-clicking the clip and
choosing Render Cache Color Output.
You can clean up the render cache for the current timeline at any point by choosing
Playback > Delete Render Cache and choosing All, Unused, or Selected Clips.
```
Pressing Option-R (macOS) or Alt-R (Windows) allows you to cycle between the
```
three render caching options.
99Lesson 2 Finessing the Rough Cut
Changing Shot Framing
There are several reasons why you might need or want to adjust the size, position, or
rotation of a clip. One common reason is to be able to change the framing of a shot. This
could be to correct poor framing when the shot was originally filmed, or if you wish to
change the shot size to add emphasis or visual variety to the shots.
In the current edit, it might be better to finish on a slightly closer shot of Chris to
emphasize the “Experience the Southwest” motto of Organ Mountain Outfitters.
1 In the timeline, move the playhead over the final interview clip.
2 In the timeline viewer, click the Transform Mode button, or choose View > Viewer
Overlay > Transform to enable the onscreen transform controls.
The onscreen transform controls can be used to change the zoom of the clip as well as
the onscreen position and rotation.
100Lesson 2 Finessing the Rough Cut
3 With your mouse pointer over the center of the onscreen guides, use the scroll wheel
on your mouse and zoom out slightly in the timeline viewer.
TIP If you are using a trackpad, you can use Option-two finger scroll
```
(macOS) or Alt-two finger scroll (Windows) to zoom the viewer in and out.
```
You can also scroll around the image by holding the middle mouse
```
button, scroll horizontally by using Command-Shift-scroll (macOS) or
```
```
Ctrl-Shift-scroll (Windows), or scroll vertically by using Command-scroll
```
```
(macOS) or Ctrl-Scroll (Windows).
```
101Lesson 2 Finessing the Rough Cut
4 Drag the corner controls to resize the clip so it appears to be a closer shot.
5 When you are happy with the adjusted framing of the shot, click the Transform Mode
button or choose View > Viewer Overlay > Toggle On/Off to turn off the onscreen
transform controls.
6 Press Z to adjust the scale of the image so it fits the timeline viewer.
102Lesson 2 Finessing the Rough Cut
This is a simple example of how you can change the size of a shot in the timeline. There are
many other creative reasons to make similar adjustments.
Changing Clip Speed
Another common technique is often employed to enhance the action of a clip by slowing
down a shot. While there are several ways you can adjust the speed at which a clip plays in
the timeline, one of the easiest is by using the Speed Change controls in the Inspector.
1 To open the Inspector, click the Inspector button at the top right of the interface.
The Inspector opens to the right of the timeline viewer. You can use the Inspector to
make changes to a clip in the timeline, including its size, position, and rotation on the
screen using the Zoom, Position, and Rotation controls, respectively, similar to using
the onscreen controls you used in the previous steps to resize the interview shot.
You can scroll down to view the controls lower down in the Inspector. Alternatively, you
can “expand” the Inspector vertically, so it occupies the full height of the Resolve
interface, by clicking the Expand button at the top right of the interface.
103Lesson 2 Finessing the Rough Cut
NOTE If you’re working on a laptop or screen using a resolution lower than
1920 x 1080, you will probably find that Resolve automatically switches to
single-viewer mode. In this mode, it appears as though the source viewer you
have been using has vanished! You can still open a clip in the source viewer by
```
double-clicking it in the media pool as before; it’s just that the source viewer
```
and timeline viewers will now occupy the same space in the interface. This is a
space-saving method employed to prevent the various parts of the interface
from becoming too small and unusable.
To make a change to a clip in the timeline, you need to display its controls in the
Inspector. You can do this in a couple of ways. First, you can single-click a clip in the
timeline to select it. If you are selecting a clip in this manner, then you are also best off
moving the timeline playhead over the clip you want to adjust. This way, you will see
the changes you’re making reflected in the timeline viewer. Alternatively, you can
simply place the timeline playhead over a clip. Using this latter method will
automatically display the controls for the uppermost timeline clip in the timeline at the
location of the timeline playhead.
2 Place the timeline playhead over the clip PINA BLANCA 70.
104Lesson 2 Finessing the Rough Cut
The Inspector automatically displays the controls for this clip since it’s on the
uppermost video track. You can confirm whether this is the correct clip by verifying the
name displayed at the top of the Inspector.
NOTE If you see another clip’s name in the Inspector, ensure that you don’t
have any clips selected in the timeline. Selected clips will override the
automatic selection method.
3 In the Inspector, locate the Speed Change controls.
Currently, the specific Speed Change controls are collapsed to save space in the Inspector.
105Lesson 2 Finessing the Rough Cut
4 Click the Speed Change section to reveal the controls.
The Speed Change controls show several options.
5 Ensure that the Direction arrow is facing to the right, so the clip is playing forward, and
drag the Change Speed percent wheel value to the left to 40.00 to reduce the clip’s
speed to 40% of its original.
TIP For quicker and more precise adjustments, you can type 40 into the
```
Change Speed percent field and press Enter (Return).
```
106Lesson 2 Finessing the Rough Cut
The clip now plays back at 40% of its original speed, and an icon on the clip in the timeline
indicates that a speed change has been made.
You can use the same controls to increase the speed of a clip from its original speed by
increasing the Change Speed percent value to above 100%.
Stabilizing Shots
Next, you will use the controls in the Inspector to stabilize a clip that has some excessive
and distracting camera movement.
1 In the timeline, play the second clip of the guy standing on the rock looking out over
the mountains, PINA BLANCA 44.
The shake from the handheld camera is quite noticeable and detracts from an
otherwise fantastic shot.
2 In the timeline, place the timeline playhead over the clip and, in the Inspector, click to
expand the Stabilization controls.
107Lesson 2 Finessing the Rough Cut
3 Click the Stabilize button.
Resolve analyzes the clip and attempts to stabilize the shot. Once the analysis has
completed, play the shot to review the changes.
The shot seems to be a little less shaky, but it doesn’t completely smooth the
camera movement.
4 Increase the Smooth control to about 0.900 and click the Stabilize button again to
apply the changes.
The increased smoothing value helps to reduce the camera shake even further, resulting in
a much-improved shot.
108Lesson 2 Finessing the Rough Cut
```
NOTE These are the same (albeit simplified) stabilization controls you can find in
```
the color page’s Tracker pallet. The resulting stabilization applied in the edit page
will be mirrored in the color page, allowing you to make further refinements if
necessary.
Adding Transitions
Video transitions are a set of effects that are often used to make the cut between two
clips a little more visually interesting. They can be a powerful storytelling tool when
used correctly.
1 In the timeline, place the timeline playhead at the start of the final clip on Video 1
and click the Detail Zoom button.
2 Select the edit point between the last interview clip, CL INTERVIEW Tk7, and the
ORGAN MOUNTAIN 1 clip.
If Linked Selection is enabled for the timeline, the audio and video edit points are
```
selected (even though the timelapse shot has no audio). If only the video edit is
```
selected, ensure that the Linked Selection button is active in the timeline toolbar.
```
3 Choose Timeline > Add Video Only Transition or press Option-T (macOS) or
```
```
Alt-T (Windows).
```
109Lesson 2 Finessing the Rough Cut
The current Standard Transition is added to the video edit using a default duration.
4 Select the transition in the timeline.
With the transition selected, the Transition tab of the Inspector automatically becomes
active, with controls for the currently selected transition.
```
5 Press / (forward slash) to preview the transition.
```
By default, the current transition should be a Cross Dissolve with a 1-second duration,
but you can always adjust a transition to your requirements.
110Lesson 2 Finessing the Rough Cut
6 From the Transition Type dropdown menu, choose Blur Dissolve, click in the Duration
Seconds field, and type 0.5 for half a second.
```
7 Press / (forward slash) again to preview the changes.
```
You can save transitions as presets that you can use over and over again.
8 In the timeline, right-click the transition and choose Create Transition Preset.
The Transition Preset window opens.
9 In the Preset Name field, type My Blur Dissolve and click OK to save the preset.
111Lesson 2 Finessing the Rough Cut
Saved presets like this are available in the Video Transitions in the Effects Library.
10 Click the Effects button at the top left of the interface to reveal the Effects Library.
11 Select Toolbox > Video Transitions.
This section of the Effects Library lists all the available transitions, including any
third-party transitions you may have installed on your system. Each transition is
```
grouped in a category (for example, Dissolve, Iris, Wipe, etc.), indicating the type of
```
transition it is.
Note that the Cross Dissolve currently has a red tag in the top left corner of the
transition’s icon. This indicates it is currently the Standard Transition, which you
applied by default.
NOTE You can preview any of the supplied transitions by hovering your
mouse pointer over a transition and moving it left and right. To add any of
these transitions, just drag them to an edit point in the timeline.
112Lesson 2 Finessing the Rough Cut
12 Scroll down to the User group of transitions.
Here you will find all your saved transition presets.
13 Right-click the My Blur Dissolve transition and choose Set As Standard Transition.
113Lesson 2 Finessing the Rough Cut
A red tag appears in the top left corner of the transition’s icon, indicating that
this transition is now the Standard Transition. You can now apply this using a
keyboard shortcut.
NOTE To remove an unwanted user transition preset, right-click the transition
and choose Delete Transition Preset.
```
14 In the timeline, Command-click (macOS) or Ctrl-click (Windows) the edit points
```
between the STORE 2, STORE 34, and STORE 28 clips.
```
15 Choose Timeline > Add Video Only Transition or press Option-T (macOS) or Alt-T
```
```
(Windows) to add your customized transition to both selected edit points.
```
114Lesson 2 Finessing the Rough Cut
NOTE To return the Standard Transition back to the default, scroll back up to the
Dissolve category of transitions, right-click the Cross Dissolve transition, and
choose Set As Standard Transition.
About Transition Alignment and Clip Handles
Whenever you add a transition, you should consider a couple of things—firstly,
whether the clips on either side of the edit where you’re adding the transition have
enough handles to allow you to add the transition and, secondly, how the transition
is aligned around the edit point.
Handles are parts of the clips that extend beyond the current In and Out points of
the clips in the timeline. You see the handles of a clip outlined in white whenever
you trim a clip. Transitions need these handles in order to create the overlap
needed. A 1-second transition will play a half-second extra of both the outgoing
and incoming clips, even though the clips won’t appear longer in the timeline.
If you attempt to apply a transition to an edit point that doesn’t have sufficient
handles on one or both sides, a warning box will appear.
You can choose to cancel applying the transition, trim the clips so there are
enough handles, or skip the clips that don’t have enough handles. In most cases,
you probably don’t want your edit shortened like this unless absolutely necessary,
and it’s always best to manually ensure that you have enough handles.
Alternatively, you can choose to adjust the alignment of the applied transition.
Transition alignments are always based around the edit point where they are
applied. When you select both sides of an edit to apply a transition, this will center
the transition across the edit, with equal numbers of frames used from the
available handles of both the outgoing and incoming clips.
115Lesson 2 Finessing the Rough Cut
If you don’t have enough handles on a clip on one side of the edit, you can choose
to align the transition either starting or ending on the edit point by selecting the
outgoing or incoming side of the edit only. Transitions aligned “starting on edit”
```
are useful if there are no handles on the incoming clip; aligning them “ending on
```
edit” is useful if the outgoing clip doesn’t have the required handles.
You can change the current alignment of a transition in the Transition tab of the
Inspector or by right-clicking the transition on the timeline. You can also choose
the transition alignment when dragging a transition to an edit point from the
```
Effects Library by dragging it to the left or right of the edit point (provided enough
```
```
handles are available, of course).
```
116Lesson 2 Finessing the Rough Cut
Adding Video Filters
Transitions are one way in which you can add stylization and visual flair to your edits.
Another commonly employed technique is to add video filters to stylize an entire clip.
Many NLE systems often have color correction tools included in their video effects and
filters and, while Resolve has some of these, they are more specialized than other systems’
tools. As you’re no doubt aware, Resolve has a page entirely dedicated to color correction
and grading, which you will explore starting with Lesson 4, “Primary Color Correction.”
Nevertheless, there are a number of creative filters you can apply in the edit page.
1 In the timeline, move your playhead over the opening shot of Organ Mountain.
As with transitions, filters can be accessed in the Effects Library.
2 In the Effects Library, select the Open FX > Filters group.
```
As with transitions, video filters are listed here in descriptive categories (e.g.,
```
```
Resolve FX Blur, Resolve FX Key, Resolve FX Light, etc.) and can be live previewed by
```
hovering your mouse pointer and moving it left and right over a filter.
117Lesson 2 Finessing the Rough Cut
3 In the list of Filters, scroll down to the Resolve FX Film Emulation category and place
your mouse pointer over the Vignette filter.
NOTE In photography and cinematography, vignetting refers to a reduction in
brightness and/or saturation of the image around the edge of the frame. It
was traditionally a result caused by the type of lens used, its focal length, and
the aperture selected, or obstructions like lens hoods or filters. These days it
tends to be added in post-production to draw the viewer’s attention to the
center of the frame or to create a dreamy or nostalgic atmosphere.
4 Double-click the Vignette filter or drag it directly to the clip to apply it using its default
```
(and rather intense) settings.
```
118Lesson 2 Finessing the Rough Cut
The Effects tab of the Inspector becomes active and displays the parameters for the
effects applied to the selected timeline clip.
The clip in the timeline also displays the FX badge to indicate that a filter is applied.
5 In the Inspector, change the Softness value to 0.0 to better see the shape of the
vignette being applied.
6 Increase the Size to around 0.9 and reduce the Anamorphism to around 1.4.
TIP The Size slider only allows you to adjust the value to a maximum of 1.
To increase it further, click and drag in the value field, or select the field and
type in the desired value.
119Lesson 2 Finessing the Rough Cut
7 Increase the Softness back to around 0.35 to darken the sides of the frame.
8 Click the red Enable button to disable the Vignette filter to see what the clip looked like
originally, and then click it again to re-enable the Vignette filter.
For consistency, you now need to apply this same filter, with the same settings, to the
same shot you’re using at the end of the current edit. To do that, you will copy the first
clip and then choose to paste just the filter and its settings to the other clip.
9 In the timeline, select the first clip and choose Edit > Copy or press Command-C
```
(macOS) or Ctrl-C (Windows).
```
10 Click the Full Extent Zoom button and move the playhead over the final clip.
11 Click the Detail Zoom button and select the clip under the playhead.
120Lesson 2 Finessing the Rough Cut
```
12 Choose Edit > Paste Attributes or press Option-V (macOS) or Alt-V (Windows) to open
```
the Paste Attributes window.
The Paste Attributes window allows you to choose which specific attributes from the
```
copied clip you want to apply to the selected clip(s). Since the clip you initially copied
```
had the Vignette filter applied, the Plugins option has been selected automatically.
13 Click the Apply button.
The Vignette filter is pasted from the first clip to the last clip, using the same settings. This
means you don’t have to re-create the effect from scratch.
121Lesson 2 Finessing the Rough Cut
Studio Only Filters
If you’re using the free version of DaVinci Resolve to work through this book, as
you are live previewing the Open FX filters, you will no doubt come across filters
that bring up the DaVinci Resolve Studio watermark in the viewer. These filters are
only fully available in DaVinci Resolve Studio.
You can still apply these filters, but you will see a dialog informing you that you
have reached the limitation of the free version of DaVinci Resolve.
If you choose to continue without upgrading, the watermark will continue to
display in the timeline viewer when playing that clip. However, if you open the
same project in DaVinci Resolve Studio, the watermark will disappear.
122Lesson 2 Finessing the Rough Cut
Adding the Logo
Visually, the edit is coming along nicely, but now it’s time to add some graphic elements—
specifically, the Organ Mountain Outfitters logo—to the opening shot and some titles to
the closing shot featuring a “call to action” to encourage the viewer to visit the Organ
Mountain Outfitters website.
1 In the timeline, press Home to move the playhead to the start, over the
ORGAN MOUNTAIN 1 clip.
2 Press the Detail Zoom button.
```
3 Choose Playback > Go To > Last Frame or press ’ (apostrophe) to jump to the last frame
```
of the ORGAN MOUNTAIN 1 clip, and press O to set an Out point at this frame in
the timeline.
4 From the GRAPHICS bin, open the clip OMO LOGO.png in the source viewer.
123Lesson 2 Finessing the Rough Cut
When using graphic files in DaVinci Resolve, the clips have a default “duration” of
5 seconds, which will be enough for this graphic. However, because graphic files are
simply the same frame repeated, the clip can be trimmed to be as long or as short
as needed.
NOTE You can adjust this default “duration” used for graphics or still images
in the User Preferences > Editing category under “Standard still duration.”
You will learn more about adjusting preferences in Lesson 7.
DaVinci Resolve can work with various graphic file formats as well as video and audio
```
files. This image is a PNG (portable network graphics) file that contains an alpha
```
channel, a separate channel from the RGB picture information that determines which
portions of the image are transparent. This is useful since it can be composited on top
of other clips in the timeline without completely blocking the other images, as the
cutaways have been doing.
To verify that this channel is being used correctly, you can view a checkerboard
background in the viewers.
5 Click the Timeline View Options menu and choose Viewer Background > Checkerboard.
124Lesson 2 Finessing the Rough Cut
The black viewer background is replaced with a checkerboard background, indicating
an alpha channel. These parts of the image will remain transparent when the clip is
edited into the timeline, allowing the image to be composited over the background clip.
6 Click the Timeline View Options menu again and choose Viewer Background > Black.
You will now backtime the graphic into the timeline.
7 Drag the clip in the source viewer to the timeline viewer and choose Place on Top from
the editing overlays, or press F12, to edit the clip to the Video 2 track.
125Lesson 2 Finessing the Rough Cut
8 In the timeline, drag the fade handle at the start of the clip to the right to apply a
```
12-frame fade in (+00:12 in the tooltip).
```
The fade handles appear on every video clip in the timeline and can be used in lieu of a
cross-dissolve transition to quickly fade the clip over any clips in video tracks below.
9 Place the timeline playhead over the OMO LOGO.png clip to see the graphic over the
background in the timeline viewer.
At the moment, the white graphic is getting a little lost against the bright background,
despite the vignette applied to the timelapse shot in the background.
126Lesson 2 Finessing the Rough Cut
10 In the Effects Library, select Open FX > Filters, scroll down to the Resolve FX Stylize
group, and locate the Drop Shadow filter.
11 Double-click the Drop Shadow filter to apply the effect or drag the filter directly to the
OMO LOGO.png clip in the timeline.
The drop shadow helps the logo stand out from the background clip on V1. To adjust
the settings for this clip, you will need to use the controls available in the Inspector.
127Lesson 2 Finessing the Rough Cut
NOTE DaVinci Resolve automatically “selects” the clip on the highest track in
the timeline without the need for you to physically click and select it. Clicking
and selecting a clip will override this behavior, allowing you to manually choose
which clip the effect will be applied to. Alternatively, you can drag the filter
directly to any clip or selected clips in the timeline.
12 In the Inspector, reduce the Drop Distance to about 0.020 and the Blur to about 0.40
to create a more defined shadow.
With the drop shadow applied and finessed, there’s one more useful effect you can
apply to this graphic to provide some much needed visual interest.
13 In the Inspector, click the Video tab.
128Lesson 2 Finessing the Rough Cut
14 Enable the Dynamic Zoom and click to reveal the controls.
Dynamic Zoom applies an automatic movement to the current clip so it appears to
move into the frame.
15 Change the Dynamic Zoom Ease dropdown menu to Ease Out.
Play the OMO LOGO.png clip in the timeline to review the dynamic zoom results, and
notice how the still image fades and zooms, coming to a gentle rest toward the end
of the clip.
You can also choose to refine the start and end framing for the Dynamic Zoom.
129Lesson 2 Finessing the Rough Cut
16 In the timeline viewer’s Transform Mode menu, select the Dynamic Zoom controls or
choose View > Viewer Overlay > Dynamic Zoom to reveal the onscreen controls for the
Dynamic Zoom.
17 Adjust the starting framing for the dynamic zoom by dragging the corners of the
green box out slightly, away from the edges of the graphic.
18 Once you’re happy with the starting and ending framing of the Dynamic Zoom, choose
View > Viewer Overlay > Toggle On/Off or click the timeline viewer’s Transform Mode
button to turn off the viewer overlays.
By utilizing some of the built-in effects and controls in the Inspector, you have taken a
simple still image and used it to create an eye-catching opening for the promo.
130Lesson 2 Finessing the Rough Cut
NOTE You can also animate this graphic using keyframes. You might prefer to use
keyframes since they offer a greater level of control over the animation than the
Dynamic Zoom option. You will learn more about adding and adjusting keyframes
in Lesson 10, “Delivery and Media Management.”
Adding the Closing Titles
Next, it’s time to add the call to action using one of Resolve’s built-in Fusion Titles templates.
1 Scroll to the end of the timeline and play the final clip, ORGAN MOUNTAIN 1. Using
the audio waveforms of the ONE MIN SOUNDTRACK.wav as a guide, stop when you
hear the final strum of the music.
Resolve has many options for creating text and titles using a series of title generators
and templates directly in the edit page. You will explore more options for creating your
own text using the Fusion page in Lesson 9, “An Introduction to Fusion.”
131Lesson 2 Finessing the Rough Cut
2 In the Effects Library, select the Titles category and scroll through the list of Fusion
Titles to the Horizonal Line Reveal title.
As with the transitions and filters you’ve worked with previously, each title template
can be live previewed by hovering your mouse pointer over the title and moving it
left and right.
To add a title to your timeline, you can simply drag it to the location where you want
it to appear. However, as you discovered in the previous lesson, this can be quite
limiting. Instead, you can open the title in the source viewer.
132Lesson 2 Finessing the Rough Cut
3 Double-click the Horizontal Line Reveal title to open it in the source viewer. If
necessary, move the source viewer’s playhead to the center so you can see the
title better.
4 Drag the Horizontal Line Reveal title from the source viewer to the timeline viewer, or
press F12, to perform a Place on Top edit.
133Lesson 2 Finessing the Rough Cut
5 Place the timeline playhead over the title clip in the timeline.
The Inspector automatically displays the controls for the Horizontal Line Reveal title.
TIP You can open the Inspector by double-clicking any title once it’s been
added to the timeline.
6 In the Inspector, select the SAMPLE UPPER text in the Upper Text Controls and type
organmountainoutfitters.com.
134Lesson 2 Finessing the Rough Cut
To ensure that the text isn’t too large, you can use the safe areas as a guide. Safe areas
are used to ensure that titles and graphics are correctly displayed on screens with
overscan and are typically required for broadcast programs.
7 In the timeline viewer, click the Safe Area Guides menu.
8 In the Safe Area Guides category, enable the Title option.
Adhering to the guides that are now displayed in the viewer will ensure that your titles
appear correctly on different HD monitors.
135Lesson 2 Finessing the Rough Cut
9 Change the Upper Text Size to about 0.08 so the title fits within the inner safe
title guide.
10 To change the color of the text, reduce the Blue control to 0.00 and the Green to about
0.40 to give the text a bright orange color.
11 Scroll down in the Inspector to the Lower Text Controls, highlight the SAMPLE text, and
type #experiencethesouthwest.
12 Adjust the Lower Text Spacing to about 1.09 so the text is about the same length
as the line.
136Lesson 2 Finessing the Rough Cut
TIP You can press the Up Arrow and Down Arrow keys to adjust the values of
a selected field in the Inspector.
13 Scroll to the bottom of the Inspector to the Line Color controls.
14 Change the Line Color to a similar shade of orange as the Upper Text: Red 1.00,
Green 0.40, Blue 0.00.
Finally, you will position the entire title over the lower portion of the screen.
15 Click the Settings tab at the top of the Inspector.
137Lesson 2 Finessing the Rough Cut
16 Change the Y Position value to about -360.00 to move the title down in the timeline
viewer but still inside the inner title safe guide.
```
17 In the timeline, use the title clip’s fade handle to apply a 12-frame fade out (-00:12 in
```
```
the tooltip).
```
18 Apply a 1-second fade-out using the fade handle on the ORGAN MOUNTAIN 1 clip
```
(-01:00 on the tooltip).
```
19 Trim the end of the ORGAN MOUNTAIN TL.mov clip on V1 so it snaps to the end of
the audio clip on A3.
138Lesson 2 Finessing the Rough Cut
20 In the timeline viewer, click the Guides button in the timeline viewer to turn off
the guides.
21 Click the Full Extent Zoom button and watch the timeline.
NOTE If you need to catch up before moving to the next step, select the
TIMELINES bin and choose File > Import > Timeline, navigate to R20 Beginners
Guide / Lesson 02 / Timelines / OMO PROMO CATCHUP 08.drt and click Open.
Excellent! The edit looks great, and you’ve brought it to a whole new level using the tools
and techniques detailed in this lesson. However, it’s still not finished. Now that you’ve made
it look as good as it can look, it’s time to make it sound as good as it can sound! It’s time to
refine the audio before providing the client with a file they can upload to their social
media accounts.
139Lesson 2 Finessing the Rough Cut
Lesson Review
```
1 Which timeline mode(s) allow you to add or remove frames from the start or end of a
```
clip in the timeline?
```
a) Selection mode
```
```
b) Trim Edit mode
```
```
c) Blade Edit mode
```
```
2 Which timeline mode(s) allow you to slip a clip in the timeline?
```
```
a) Selection mode
```
```
b) Trim Edit mode
```
```
c) Blade Edit mode
```
3 True or False? The replace edit uses the position of the timeline and source viewer
playheads but always ignores In and Out points in the timeline.
4 True or False? DaVinci Resolve Studio OFX filters cannot be applied in the free version
of DaVinci Resolve.
5 Which elements can be previewed live in the Effects Library before being applied to a
clip in the timeline?
```
a) Video Transitions
```
```
b) Open FX Filters
```
```
c) Fusion Titles
```
140Lesson 2 Finessing the Rough Cut
Answers
```
1 a) and b). Selection and Trim Edit modes can be used to trim the start and end of a clip
```
in the timeline.
```
2 b). Trim Edit mode allows you to slip a clip in the timeline by adjusting the In and Out
```
points of the clip at the same time.
3 False. The replace edit will use In and Out points in the timeline to limit the amount
replaced but will always ignore any In or Out points in the source viewer.
4 False. However, Studio-only effects applied in the free version of DaVinci Resolve will
display a watermark.
```
5 a), b), and c). Video transitions, Open FX filters, and Fusion Titles can all be previewed
```
live from the Effects Library by placing your mouse pointer over them and moving it
left and right.
Time
This lesson takes approximately
75 minutes to complete.
Goals
Setting Up the Project 142
Audio Mixing 142
Normalizing Clip Levels 147
Noise Reduction Using
Fairlight FX 154
Adding Audio Fades
and Transitions 159
Mixing the Music Levels 165
Recording a Voiceover 168
Full-Screen Review 173
Quick Export 174
Lesson Review 179
Lesson 3
Audio Editing
and Quick Export
Over the previous two lessons, you
have focused primarily on editing and
refining the video clips in the OMO edit
timelines. However, at some point you
must switch your focus to other parts
of the edit that need your attention,
especially if you’re going to deliver the
edit to the client in good time!
Since the visual side of the edit is well
in hand, it’s time to turn your attention
to the audio in the timeline.
142Lesson 3 Audio Editing and Quick Export
Setting Up the Project
This lesson starts exactly where Lesson 2 finished. If you completed Lesson 2, you may
proceed to the next section in this lesson, “Audio Mixing.”
If, however, you didn’t fully complete the previous lesson, you can import a catch-up
timeline to help you get started with this lesson.
1 Open DaVinci Resolve and, in the Project Manager, double-click the OMO Promo
project to open it in DaVinci Resolve.
2 If necessary, ensure that the edit page is selected.
3 In the bin list, select the TIMELINES bin and choose File > Import > Timeline.
4 Navigate to R20 Beginners Guide/Lesson 03/Timelines, select the file
OMO PROMO CATCHUP 08.drt, and click Open.
The timeline is imported into the selected bin in your project and automatically opens in
the timeline viewer. You can now continue with this lesson.
Audio Mixing
In many cases, you can spend as much time refining and finessing the audio in the timeline
as you can the video. Over the first part of this lesson, you’ll use some common techniques
to ensure that you can mix your audio to the correct levels efficiently and effectively.
Arguably, while the audio in your timelines is made up of many different elements
```
(dialogue, effects, and music are just three of these elements), the most important of these
```
is the spoken word. Whether it be an interview as you have with the Organ Mountain
Outfitters footage, voiceover, or dialogue in a dramatic scene, each spoken word is an
important way of communicating with your audience and will need to be easily heard and
understood. If the audience can’t hear what someone is saying, then clearly there is no way
they will be engaged with your story or messaging.
With this in mind, setting the initial levels of the dialogue clips in your timelines is a good
starting point for creating a successful mix. So for the Organ Mountain Outfitters edit, you
will start by normalizing Chris’s interview clips to a consistent level. However, to do that,
you need to know where the levels are currently.
1 Choose Workspace > Reset UI Layout to reset the interface layout to the default.
143Lesson 3 Audio Editing and Quick Export
2 In the timeline, click the Full Extent Zoom button and, if necessary, adjust the timeline
so you can see all the clips.
TIP To prevent the timeline view from resetting when you choose Reset UI
Layout, choose File > Close Current Timeline before resetting the UI layout.
You can then choose to reopen the last timeline from the timeline menu at the
top of the timeline viewer.
3 Click the Media Pool button in the top left of the interface to close the media pool since
you won’t need it until later in this lesson.
4 Click the Mixer button in the top right of the interface to open the audio mixer to the right
of the timeline, dragging the left edge to resize it, showing all the audio track controls.
144Lesson 3 Audio Editing and Quick Export
5 Click the Single-Viewer Mode button in the top right of the timeline viewer so that
Resolve now displays a single viewer.
6 Click the Timeline View Options menu and resize the video tracks to make them smaller
and the audio tracks to make them larger.
145Lesson 3 Audio Editing and Quick Export
This will give you a more focused layout that makes the best use of your screen
real estate.
TIP To save this layout for use later, choose Workspace > Layout Preset > Save
Layout Preset.
You need to start off by focusing on Chris’s dialogue clips. These are currently all in the
first audio track, Audio 1.
7 Click the Mute button for Audio 3 in the timeline track controls or in the mixer so the
music doesn’t play, allowing you to focus just on what Chris is saying.
146Lesson 3 Audio Editing and Quick Export
8 Play the timeline from the start, observing the levels of the clips in the mixer
for Audio 1.
Even though the audio for these clips is from the same interview, there’s a lot of variation
in the levels. In the mixer, you should see some clips peak as loud as -3 dBFS, while others
peak as low as -18 dBFS.
147Lesson 3 Audio Editing and Quick Export
Normalizing Clip Levels
Normalizing the clips will help to smooth out some of the differences in the levels of each
clip. Normalization in itself does not “fix” the levels. Instead, you are trying to discern a
starting point from which you will be able to adjust the clips appropriately.
1 Make sure the timeline is in Selection mode and select all the clips on the
Audio 1 track.
NOTE If Linked Selection is enabled for the timeline, both the audio clips and
```
their linked video clips will be selected. This is fine; normalization is an audio-
```
only process and does not affect video clips.
2 With the clips on Audio 1 selected, right-click any of the selected clips and choose Clip
Operations > Normalize Audio Levels to open the Normalize Audio Levels window.
The Normalization Mode dropdown menu allows you to choose the method used to
determine how each clip’s volume level will be normalized.
148Lesson 3 Audio Editing and Quick Export
Options include a variety of loudness normalization algorithms specific to various
international standards, which are useful for balancing the perceived overall loudness of
several clips to one another, regardless of transient levels throughout each clip. You can
also perform peak normalization, with options for both Sample Peak and True Peak.
Whichever method you choose, the result is largely the same: each clip’s audio level is
analyzed and then adjusted to the various peak and/or loudness levels specified.
NOTE You will learn more about delivering your audio for various loudness
standards in Lesson 10, “Delivery and Media Management.”
3 Leave the Normalization Mode set to Sample Peak Level and the Target Level
to -9 dBFS.
With the target set to -9 dBFS, this is where the normalization process will set the peak
```
(highest) levels of the selected clips and is a good starting point for setting
```
dialogue levels.
4 Change the Set Level option to Independent.
When Set Level is set to Relative, all selected clips are treated as if they’re one clip so
that the highest peak and/or loudness level of all the selected clips is used to define
the adjustment, and the volume of all selected clips is adjusted by the same amount.
When Set Level is set to Independent, the peak and/or loudness levels of each clip are
used to define the adjustment to that specific clip. This is likely to result in different
volume adjustments to each clip that make the peak and/or loudness levels of each
audio clip better match one another. Relative is useful if you’re normalizing a series of
clips that have a consistent recorded level, such as a controlled dialogue recording,
149Lesson 3 Audio Editing and Quick Export
whereas Independent is much more useful if you’re trying to balance a series of clips
```
that have different recorded levels (subtle or not), such as interviews or other location
```
audio, which might have been recorded under less-controlled conditions.
5 Click Normalize.
The audio levels for the selected clips are each adjusted so that the peak level for each
clip reaches the target level of -9 dBFS on the audio meters in the mixer.
6 To verify, play through the timeline again, looking for the peak levels of the clips
on Audio 1.
150Lesson 3 Audio Editing and Quick Export
You should now see that each clip peaks at the consistent level of -9 dBFS. However, as
```
you’ll no doubt see (and hear), that does not mean the levels are entirely consistent with
```
each other, because it depends on the consistency with which the original audio levels
were recorded! For example, while the first and fifth interview clips each start with a peak
of -9 dBFS, the rest of the audio levels for these clips is around 6 dB lower than each of the
other clips due to the nature of the recorded audio.
Adding Keyframes to Audio Clips
Normalizing audio levels doesn’t really set the correct level for each of your clips. Instead,
think of it as a useful starting point from which you can make further adjustments. Having
set the initial peak level, all you need to do now is bring the rest of the audio in the clips up
to the same level so each dialogue clip plays at a consistent level, making it easier for the
audience to concentrate on what’s being said.
There are several ways you can achieve this, but one of the most common methods is
using audio keyframes.
1 If necessary, deselect all the clips in the timeline, move the playhead over the center of
the first interview clip, click the Detail Zoom button, and center the clip in the timeline.
2 Place your mouse pointer over the audio portion of the timeline and use Shift-scroll to
increase the size of the audio tracks so it’s easier to view the waveform of the audio clip.
Looking at the waveform of the clip, you should be able to clearly see what’s
happening to the audio levels. The clip starts with a large waveform, the peak of the
clip, where the audio level is the highest, and this is the point of the clip that has been
set to the -9 dBFS target level as part of the normalization process—but then it seems
to drop considerably after the first few words have been spoken.
This is a common enough problem: no matter how carefully the audio recordist is at
setting recording levels on location, you often get these variable levels since people
will generally begin their answers forcefully before dropping off slightly. Sometimes it’s
due to feeling a little anxious at first in front of the camera, or possibly it’s because
151Lesson 3 Audio Editing and Quick Export
they start to lose the thread of what they’re saying as they progress through an
answer. Either way, you really need the rest of the audio in the clip to be peaking
around -9 dBFS for a consistent level.
NOTE This still doesn’t mean a peak level of -9 dBFS is the correct level. You’re
still only concerned with getting a consistent level across the dialogue clips.
```
3 Option-click (macOS) or Alt-click (Windows) the volume bar to add the first keyframe
```
just after the large initial peak in the waveform.
```
4 Option-click (macOS) or Alt-click (Windows) to add a second keyframe just before the
```
third, slightly lower peak.
5 Click and hold the volume bar after the second keyframe to see the current level
adjustment applied by the normalization process.
The tooltip shows an adjustment of -3 dB. To bring the rest of this clip back to a level
comparable to the initial peak and the other dialogue clips in the timeline, you need to
apply a +6 dB adjustment to this latter portion of the clip.
152Lesson 3 Audio Editing and Quick Export
6 Drag the volume bar up until the tooltip reads approximately 3 dB.
TIP For greater control over the precision of the volume level adjustment,
hold the Shift key while dragging the volume bar.
7 Play the clip again.
Note how the levels at the end of the clip drop slightly again as Chris reaches the end
of his introduction. A couple of additional keyframes will help.
```
8 Option-click (macOS) or Alt-click (Windows) twice more to add two additional
```
keyframes to the volume bar toward the end of the first audio clip and adjust the level
after these keyframes to around 6 dB.
With these adjustments, the clip now has a more consistent audio level throughout
its duration.
9 Repeat the process on the fifth clip on Audio 1, CL SUBCLIP 2 - Brand, adding the
keyframes just after the first large peak and bringing the level after the second
keyframe up to around 4 dB.
153Lesson 3 Audio Editing and Quick Export
10 Add another couple of keyframes further through the same clip and raise the level
after by about another 1.5 dB, to around 5.5 dBFS.
11 Finally, play back the timeline again to ensure that all the interview clips play at around
the same level, and no part of the interview sounds noticeably louder or quieter than
the rest. If necessary, add additional keyframes as required.
Congratulations. You have successfully normalized and balanced the interview clips for this
timeline. This provides a good starting point from which to mix in the rest of the audio clips.
Using Keyframes to Remove Unwanted Audio
You can also use audio keyframes to help remove unwanted sounds.
1 Play the last interview clip on track Audio 1, listening carefully after Chris says,
“That’s why we say….”
You can hear an unwanted clapping sound as he lowers his hands to his knees.
Although this action is covered by the cutaway of the store exterior, it’s quite
distracting now that the levels have been normalized.
2 Zoom in on the clip in the timeline so you can clearly see the waveform and identify the
slight peak created by the clap.
```
3 Option-click (macOS) or Alt-click (Windows) the volume bar to add two keyframes just
```
after Chris’s first sound bite and just before the second, and a third above the peak
made by the clap.
154Lesson 3 Audio Editing and Quick Export
4 Drag the middle keyframe down to reduce the level of the clap so that you no longer
hear it in the mix.
Using keyframes like this is an easy way of minimizing unwanted or distracting sounds
in your mix.
Noise Reduction Using Fairlight FX
Using simple techniques like keyframes means you can clean up your audio edits to a
certain degree, but sometimes you need to employ other methods to remove unwanted or
distracting sounds. In certain circumstances, you can use Resolve’s powerful built-in
Fairlight FX audio plug-ins.
1 Mute Audio 2 and click the Full Extent Zoom button.
2 Return the timeline playhead to the start of the first clip on Audio 1 and begin playing
this clip, listening carefully.
The audio level is much better due to the work you’ve done normalizing and balancing
the clip’s levels. However, this has raised another issue with this clip, and possibly the
interview as a whole: by increasing the levels, you have made the background noise
much more prominent, which you can hear as a hissing noise, especially when Chris
isn’t talking.
```
Now, it’s very likely that once you start adding other parts of the mix back in (most
```
```
notably the music on Audio 3), this won’t be a problem. However, this gives you the
```
opportunity to learn how to employ the power of Fairlight FX for reducing audio noise.
155Lesson 3 Audio Editing and Quick Export
3 Click the Effects button in the top left of the interface to open the Effects Library.
4 Open the Audio FX group and choose Fairlight FX.
The Fairlight FX plug-ins are installed along with DaVinci Resolve.
156Lesson 3 Audio Editing and Quick Export
5 Select the Noise Reduction plug-in and drag it across to the first clip on Audio 1 in
the timeline.
The plug-in is added to the clip in the timeline, and its controls window opens.
The Noise Reduction plug-in can be used in either a manual or automatic mode. As a
basic introduction to the power of this plug-in, and Fairlight FX plug-ins in general, you
will use the automatic settings. For more information on using the plug-in manually,
see the DaVinci Resolve 20 User Manual.
157Lesson 3 Audio Editing and Quick Export
6 In the Noise Reduction controls window, select the Auto Speech Mode.
7 Play back the clip in the timeline to hear the results of the Noise Reduction plug-in.
8 Close the Noise Reduction plug-in window.
NOTE To reopen the Noise Reduction plug-in’s controls, select the clip in the
timeline and open the Effects Inspector, and then click the Custom button in
the top right corner of the effects controls.
You can quickly apply the same Noise Reduction plug-in to all the other dialogue clips
by using Paste Attributes.
9 Select the CL INTERVIEW Tk2 audio clip and choose Edit > Copy or press Command-C
```
(macOS) or Ctrl-C (Windows) to copy the clip.
```
158Lesson 3 Audio Editing and Quick Export
10 Select all the other clips in the Audio 1 track and choose Edit > Paste Attributes or
```
press Option-V (macOS) or Alt-V (Windows) to open the Paste Attributes window.
```
The top of the Paste Attributes window tells you which clip you are pasting attributes
from and how many clips you’re pasting them to. However, by default, you’ll see that
the Volume and Plugins options are both selected. In this case, you only want the
Noise Reduction plug-in pasted to the selected clips, not the Volume adjustments!
11 For the Audio Attributes, deselect the Volume option and click Apply.
159Lesson 3 Audio Editing and Quick Export
This will apply the Noise Reduction plug-in copied from the first clip to all other clips in the
track, while preserving all the individual volume adjustments you made earlier.
NOTE If you need to catch up before moving to the next step, select the
TIMELINES bin and choose File > Import > Timeline, navigate to R20 Beginners
Guide / Lesson 03 / Timelines / OMO PROMO CATCHUP 09.drt and click Open.
Adding Audio Fades and Transitions
Having balanced all the dialogue clips, you can now turn your attention to the effects, such
as those on Audio 2. This type of audio is often referred to as SOT, for “sound on tape,” an
anachronistic term used to refer to audio recorded on a camera.
1 Unmute Audio 2 and play the beginning of the timeline, listening to how the two audio
clips on Audio 2 sound against the dialogue clips on Audio 1.
The first clip is a little low compared to the second clip.
160Lesson 3 Audio Editing and Quick Export
2 Increase the audio level of the first clip on Audio 2 by about 12 dB so its waveform is
similar in size to the second clip.
3 Use the fade-in handle to fade in the first SOT clip over a duration of about a second.
4 Use the fade-out handle to fade out the second SOT clip over a duration of
about a second.
5 Select the edit point between these two clips and choose Timeline > Add Audio Only
Transition or press Shift-T.
An audio transition is applied to the edit point, cross fading the two audio clips and
providing a smoother audio transition between the two clips than a simple cut.
161Lesson 3 Audio Editing and Quick Export
6 Select the audio transition in the timeline and open the Inspector.
7 In the controls for the audio transition, change the Transition Type to Cross Fade +3 dB.
This type of transition is a more appropriate setting for cross dissolving two clips than
the linear 0 dB default.
8 Play the clips on Audio 2 again to verify that their levels are more consistent and that
the audio fades are working to provide a smooth transition into, between, and out of
the clips.
To further refine the audio levels of the entire Audio 2 track, you can use the
Audio Mixer.
162Lesson 3 Audio Editing and Quick Export
9 In the Audio Mixer, adjust the level of Audio 2 by approximately -3 dB.
TIP Double-click the slider to reset the track level to its default 0 dB
starting position.
Finally, you will finesse the transition into and out of the SOT clips.
10 Click the Linked Selection button in the timeline toolbar. This will enable you to adjust
the audio clips independently of their linked video clips.
163Lesson 3 Audio Editing and Quick Export
11 Roll the start of the first clip on Audio 2 to the left by about 12 frames so that it starts
fading in slightly before the visual cut.
12 Roll the end of the second clip to the right by about 12 frames so it finishes fading out
completely after the visual cut.
NOTE If you find that Snapping is interfering with the accuracy of your
trimming, press N to quickly disable Snapping as you adjust the audio clips.
When you release the mouse button, Snapping will be automatically
re-enabled.
13 Once completed, click the Linked Selection button again or press Shift-Command-L
```
(macOS) or Shift-Ctrl-L (Windows) to re-enable Linked Selection.
```
Don’t forget that you can always refine the levels of individual clips or tracks to perfect the
mix as you’re working. However, for now, you’ll bring the music back into the mix.
164Lesson 3 Audio Editing and Quick Export
Different Types of Audio Transitions
DaVinci Resolve has three types of audio transitions, which you can access through
the Transitions controls in the Inspector as you just did or via the Effects Library
under the Audio Transitions category. Audio transitions can be applied, adjusted,
saved as presets, and set as the Standard Transition in the same way as video
```
transitions (see the previous lesson).
```
By default, the Standard Audio Transition is the Cross Fade 0 dB. While this would
seem to be the natural audio cross fade you’d want to use, due to the nature of
```
audio levels, it can result in a slight (albeit almost imperceptible) dip in the levels
```
during the cross fade.
Cross Fade +3 dB minimizes this issue by applying a ramped adjustment to the
levels where the audio is initially faded out/in slower. This is sometimes referred to
as a constant power cross fade and is commonly used when cross-fading music or
sound effect clips.
Cross Fade -3 dB is the opposite of the constant power fade, whereby the audio is
initially faded out/in faster and can be used when fading music out completely.
The Transition Inspector allows you to mix between the different types of audio
fades using the Fade In and Fade Out pop-up menus. You can also manually adjust
the shape of the fade applied by the fade handles using the control that appears
on the center of the audio curve.
Ultimately, the choice of which type of cross fade works in any given situation
depends on what you’re hearing.
NOTE If you need to catch up before moving to the next step, select the
TIMELINES bin and choose File > Import > Timeline, navigate to R20 Beginners
Guide / Lesson 03 / Timelines / OMO PROMO CATCHUP 10.drt and click Open.
165Lesson 3 Audio Editing and Quick Export
Mixing the Music Levels
The final touch you will apply to the audio for this edit is to mix the music with the rest of
the timeline audio, reducing the volume level of the music during interviews or other
dialogue clips—a technique often referred to as ducking.
As always, there are many ways of achieving this result. For example, you will use
keyframes to adjust the levels of the music clip so that it’s louder when people aren’t
speaking and quieter when they are.
1 Unmute Audio 3 and, if necessary, click the Full Extent Zoom button to see the
entire timeline.
Play the timeline, listening to the balance of the music on Audio 3 against Chris’s
dialogue audio on Audio 1 and the SOT clips on Audio 2.
2 While the timeline continues to play, adjust the level of the clip on Audio 3 to around
-22 dB to give the dialogue and SOT a little more breathing room.
With the level of the music now set for when Chris is speaking, you’ll now
need to increase the levels when he’s not speaking to fill the “space” and create
a consistent soundtrack.
166Lesson 3 Audio Editing and Quick Export
3 Place the playhead at the start of the first soundbite on Audio 1 and click the Detail
Zoom button.
```
Option-click (macOS) or Alt-click (Windows) the volume line for the music clip twice to
```
add keyframes around the soundbite’s start.
4 Adjust the clip’s audio level for the portion before the first keyframe to around -12 dB.
```
5 Press / (forward slash) to preview this part of the timeline, listening to how the music’s
```
audio level drops as Chris begins speaking.
6 Scroll the timeline to the right until you arrive the gap on Audio 1 between the first and
second soundbites.
167Lesson 3 Audio Editing and Quick Export
```
7 Using Option-click (macOS) or Alt-click (Windows), add four keyframes to the music clip:
```
```
two around where Chris stops speaking in the first soundbite (use the waveforms as a
```
```
guide rather than the clip’s edit point) and another two around the start of the next
```
soundbite.
8 Adjust the volume bar between the two middle keyframes to around -15 dB to raise the
audio of the music during the pause in Chris’s dialogue.
```
9 Press / (forward slash) to preview the mix, ensuring that the music level rises but
```
doesn’t swamp the SOT audio of Audio 2.
10 Continue to add keyframes to the audio levels of the music clip to finish the mix,
adjusting each part of the music to fill the gaps between the soundbites.
168Lesson 3 Audio Editing and Quick Export
NOTE If you need to catch up before moving to the next step, select the
TIMELINES bin and choose File > Import > Timeline, navigate to R20 Beginners
Guide / Lesson 03 / Timelines / OMO PROMO CATCHUP 11.drt and click Open.
Recording a Voiceover
Occasionally, you may need to record some audio to add to your project. Most often, this
might be a simple voiceover that you might record yourself. If you have a microphone
attached to your computer, you can record directly into DaVinci Resolve using the new
Voiceover tool.
1 In the timeline, place the playhead at the start of the Horizontal Line Reveal title. This is
where you’ll record a short voiceover for the call-to-action graphic.
2 Click the Media Pool button at the top left of the interface to reopen the media pool.
3 Select the Master bin and choose File > New Bin.
4 Rename the new bin VOICEOVER and select it.
169Lesson 3 Audio Editing and Quick Export
With the bin currently selected, this will be where you’ll record your voiceover in
the project.
5 Choose Timeline > Record Voiceover or click the Voiceover button at the top of
the timeline.
The Voiceover tool opens.
6 In the File Name field, highlight the existing filename and type MY OMO VO.
```
If you have multiple inputs on your system (for example, a built-in microphone and a USB
```
```
microphone), the Audio Input menu allows you to select which input you wish to use for
```
the recording. The Record Track menu allows you to target which track you want to
record onto in the current open timeline. Leaving the Record Track set to Auto will allow
DaVinci Resolve to choose the most appropriate track based on your current track layout.
170Lesson 3 Audio Editing and Quick Export
```
7 Click the Options menu (…) and choose Mute Timeline Audio While Recording to
```
prevent audio feedback during the recording process.
NOTE By default, the audio recorded will be a mono recording. If you
have a stereo microphone and wish to record in stereo, you can enable the
Stereo Input option.
8 When you are ready, click the Record button to begin the countdown.
9 Once the countdown is complete, record the following line of dialogue: “Organ
Mountain Outfitters. In store and online now.”
171Lesson 3 Audio Editing and Quick Export
```
10 Click the Record button again or press Esc (Escape) to stop the recording.
```
The recording is added as a new clip to a new track in the timeline.
You will also find the clip has been added to the selected bin in the media pool.
NOTE If you wish to record additional takes, simply click the Record button
again. Additional recordings will overwrite the existing clip in the timeline and
be added to the selected bin in the media pool alongside all your
previous takes.
11 You can now trim the clip in the timeline, normalize the levels, and, if necessary, add a
Noise Reduction filter to the clip.
172Lesson 3 Audio Editing and Quick Export
Changing Timeline Track Order
To change the order of the audio tracks in the timeline, you can right-click any
track’s controls and choose Move Track Up/Down.
Alternatively, open the Index from the top left of the Interface, select the Tracks
tab, and drag the tracks to change their order in the timeline.
173Lesson 3 Audio Editing and Quick Export
Full-Screen Review
Congratulations! You have successfully edited a short but polished promotional clip for
Organ Mountain Outfitters. However, before you deliver the final file that will be uploaded
to the client’s social media channels, you should watch the whole thing back at full screen.
```
This can be very useful because it will allow you (and the client, if they’re with you) to see
```
the results of your efforts without being distracted by all the “editing paraphernalia” of
the interface.
```
1 Choose Workspace > Viewer Mode > Cinema Viewer or press Command-F (macOS) or
```
```
Ctrl-F (Windows).
```
DaVinci Resolve displays the current timeline in full screen. Simple onscreen navigation
and playback controls are available as an overlay.
TIP You can still use the keyboard shortcuts you’re familiar with to navigate
around the timeline in the Cinema Viewer. Use Home to return to the start of
the edit, J, K, and L for playback, etc.
2 Use the onscreen controls to return to the start and begin playback. The controls and
your mouse pointer will disappear after a few seconds.
3 When you’ve finished watching your masterpiece, move the mouse slightly to display
```
the controls again and click the Exit Fullscreen button or press Esc (Escape) to return
```
to the full Resolve interface.
174Lesson 3 Audio Editing and Quick Export
Playing back your timeline like this gives you an opportunity to see your edit the same way
your viewers will. Watch carefully and see if any parts of the edit might benefit from
additional changes. If so, now is the time to make those adjustments.
Quick Export
Of course, the client loves the edit and is happy to sign off on your work. Hopefully, you’re
also pleased with what you’ve accomplished. Now, the only step left is to export the edited
timeline so it can be posted to popular streaming and social media websites as quickly as
possible. You can accomplish this easily using DaVinci Resolve’s Quick Export feature.
NOTE You will explore more customization options for your exported work using
the Deliver page in Lesson 10, “Delivery and Media Management.”
1 In the top right corner of the interface, click the Quick Export button or choose File >
Quick Export.
175Lesson 3 Audio Editing and Quick Export
The Quick Export window includes commonly used presets for creating a video file of
your currently open timeline, including uploading directly to common social media and
sharing sites, including YouTube, Vimeo, TikTok, and Dropbox.
2 Select the YouTube option.
This preset contains all the settings needed to create a file and upload it directly to
YouTube for you, a summary of which is available in the panel on the right. However, if
you haven’t already input your account information, you’ll just see a Sign In button.
3 Click the Sign In button if you haven’t already entered your account information
for YouTube.
176Lesson 3 Audio Editing and Quick Export
Resolve will open a window in your internet browser for you to authenticate
your account.
4 If required, follow the directions to enter your account information and give
DaVinci Resolve the relevant permissions. When you’ve completed the sign-in process,
the Quick Export window will show an Upload Directly checkbox. Selecting this allows
you to enter a title, privacy settings, and a description for the uploaded video.
177Lesson 3 Audio Editing and Quick Export
TIP You can also sign in to or out of these services by choosing
DaVinci Resolve > Preferences > Internet Accounts. You will learn more about
the preferences in Lesson 7, “Project Setup and Preferences.”
Instead of uploading directly to a video sharing service, though, you might just want to
create a stand-alone file. You can then manually upload the file instead or distribute it
in other ways.
5 Select the H.264 Master preset. Again, details of the file to be exported are
summarized in the right panel of the Quick Export window.
TIP By default, the exported file will have the same name as the timeline
you’re outputting, but you can rename the exported video at this stage
if necessary.
178Lesson 3 Audio Editing and Quick Export
6 Click Export, navigate to R20 Beginners Guide / OUTPUT / EXPORTS, and click Save.
A render progress window shows the time to completion and, if appropriate, the
upload progress for the movie.
Once the render progress bar has completed, close the Quick Export progress window,
and you will find the exported video in the location you chose for it so you can open it
in your computer’s default video player.
Congratulations! Over these first three lessons, you have successfully put together a short
yet complex promo using the editing toolset available to you in DaVinci Resolve’s edit page.
Hopefully, these lessons have given you some insights into how these tools function and
how you can start to use them in your own work.
In the next section of this Beginner’s Guide to DaVinci Resolve 20, you will look at how you
can use the color page to color correct and grade your footage.
179Lesson 3 Audio Editing and Quick Export
Lesson Review
1 True or False? All dialogue clips should be normalized to -9 dBFS.
2 Which modifier key is used to add keyframes to the volume bar?
```
a) Control (macOS) or Ctrl (Windows)
```
```
b) Shift
```
```
c) Option (macOS) or Alt (Windows)
```
3 What type of effect is the Noise Reduction plug-in?
```
a) Audio transition
```
```
b) Fairlight FX
```
```
c) OFX
```
4 True or False? You can change the order of timeline tracks by dragging the tracks in
the timeline panel.
5 How can you access the Quick Export window in the edit page?
```
a) Press Command-E (macOS) or Ctrl-E (Windows)
```
```
b) Choose File > Export > Quick Export
```
```
c) Choose File > Quick Export
```
180Lesson 3 Audio Editing and Quick Export
Answers
1 False. -9 dBFS is the default value for normalizing clips, but clips can be normalized to
whatever level you think is appropriate. You can always make further adjustments to a
clip’s audio levels afterward or normalize to another peak level altogether.
```
2 c). Option-clicking (macOS) or Alt-clicking (Windows) the volume bar will add
```
keyframes.
```
3 b). Noise Reduction is a Fairlight FX and can be found in the Fairlight FX category of the
```
Effects panel.
4 False. You can change the order of timeline tracks either by right-clicking the tracks
controls and choosing Move Track Up/Down or by dragging the order of the tracks in
the Tracks tab of the Index panel.
```
5 c). Choose File > Quick Export. You can also click the Quick Export button.
```
181An Introduction to Color Correction
An Introduction to
Color Correction
Before you get into the technical side of color correction and learn how DaVinci Resolve’s
powerful color correction tools work, it’s important to take a moment to understand color
correction and the creative medium it is.
Color correction is not something you can do by learning the controls of the color
corrector, and it’s not something you can do well just using the scopes. It’s a highly creative
skill. Just as a good editor can tell a story and bring a dramatic flow to a program, the
colorist evokes an emotion in a viewer via visual manipulation of the image. While it can
take time to learn how to be a top-level colorist, like all creative skills, it never gets boring
because you’ll always have something new to learn and a new creative style to explore!
When using DaVinci Resolve, you have the advantage of more than 30 years of color
correction experience. Blackmagic Design pioneered the development of color correction
hardware and software specifically designed to artistically enhance visual images acquired
from film, video, and digital sources. As a result, DaVinci Resolve possesses an incredibly
deep, sophisticated, and efficient toolset for adjusting the look of the clips in your program
and managing these adjustments over an entire timeline.
Furthermore, DaVinci Resolve has continuously evolved thanks to feedback from countless
professional colorists worldwide working at all levels of the film and broadcast industry. So
the DaVinci Resolve color page has been developed to work the way colorists think. Still, for
all its technological sophistication, it’s important to remember that DaVinci Resolve is merely
a tool that requires an artist to realize its full potential. But, of course, that’s the fun part!
The following lessons cover the basics you’ll need to learn to begin harnessing the power
of the color page in your own projects—be they feature films, episodic television, web
series, short subjects, spots, promos, or corporate videos. No matter what you work on,
```
these formats employ the same fundamental grading techniques and the same basic tools;
```
so if you’re new to the world of professional color grading, don’t worry. All rock star
colorists once had to learn these first steps for themselves, and you’ll use the
fundamentals you learn here for the rest of your career.
182An Introduction to Color Correction
Gone are the days when high-quality color grading was unaffordable. Blackmagic Design
has put the powerful color tools of DaVinci Resolve within reach of any editor who has a
reasonably capable workstation or laptop. The polish you’ll need to achieve world-class
results is only a click away on the color page.
However, before you start getting into the specifics of color, it’s important to step back
and consider what these tools are really used for.
Why Color Correct Your Work?
Here’s a tempting question that countless producers and directors have asked:
```
“The program looks fine the way it was shot; why spend the time to color grade it?” It’s a
```
```
good question in an industry where time is money; if the program you’ve cut in the edit
```
page looks fine, why bother grading it?
The answer is because your program won’t look as good as it will after being graded.
The process of adjusting the contrast and color of every clip in a program is variously
called color correction, color grading, or just grading. The difference in terminology is
largely superficial, but most experienced colorists prefer “grading” because “correction”
implies that you only adjust things that are wrong, whereas “grading” implies that you’re
holding each clip in your program up to a higher artistic standard. A colorist doesn’t ask,
“Does this clip look good?” A colorist asks, “Could this clip look better?”
Setting the Tone of the Visuals
Much has been said about the emotional power of color to shape audience mood, and
everyone would agree that a scene lit by cool blue lighting will have a very different vibe
than one that’s lit by warm orange lighting. The greenish tinge of fluorescent fixtures and
the salmon-hued wash of mercury vapor streetlights each paint the scenes of a show with
different atmospheric feelings that, when done right, add to the narrative and how your
audience perceives it.
Cooler Warmer
183An Introduction to Color Correction
Of course, what these varied illuminants mean depends on the visual palette you develop.
Warm lighting that denotes romance in one film may instead portray roiling, desert-bound
discomfort in another. Their impact depends on the associations that your grading makes
between the visuals and the story. Should this scene seem later in the day? Should the
colors be more subdued? Should the sky be an inescapable presence? You control these
audience perceptions when you exercise subtle control over the picture via color grading.
The important takeaway is that the color page gives you the tools to mold these
associations to suit your needs—intensifying, attenuating, or completely counteracting
their effect, as necessary, to strike the right tone for every scene.
Portraying the World Subjectively
Narrative cinematography is rarely concerned with capturing objectively lit renditions of
locations with perfectly accurate, neutral color and tonality. Instead, truckloads of lighting
instruments and careful art direction manipulate the light and color of the location to
make it look somber, magical, frightening, or sultry. These efforts extend to the grading
suite, where your job is not to portray the world as it is, but the world that the
cinematographer and director want the audience to see.
```
What the camera saw (left) and what you want audiences to see (right).
```
Documentary photography may very often be concerned with presenting a supposedly
```
unvarnished (yet gloriously rendered) look at the world. And yet even this “realistic” look
```
at the world is a fabrication, since every adjustment you make to improve the visibility of
a subject, enhance the glory of nature, clean up some archival footage, or push the
surroundings of the frame to recede artfully into the background can be as carefully
thought out and manipulated as any music video grade.
The point is, whether you’re making a horror movie, an architectural documentary, a
sales video, or an automotive advertisement, you’re using the tools and techniques of
color correction to create a subjective representation of the imagery. The more control
you can exercise over this representation, the larger the palette of emotional response
you’ll have to draw from.
184An Introduction to Color Correction
Evolving Toward High-End Work
If you want to learn and stay competitive, and especially if you intend to work on client
projects rather than your own, it’s good to make yourself aware of current styles and
```
trends. You’ve no doubt heard that if you want to write, you should read (and write) as
```
much as you can, and the same holds true for color grading. Watch movies, television,
music videos, and web shorts. And if you’re watching television, make yourself watch the
ads. Once you’ve had a chance to learn the grading controls that DaVinci Resolve offers,
you’ll start to see how different looks correspond to adjustments you can make in your
own projects.
Finally, get out into the world and look at other visuals. Flip through fashion magazines,
go to art galleries, take a hike in the woods, and observe. Fill your mind with diverse
images and analyze them to see what inspires you. The more aware you are of other
visual disciplines, the more ideas you’ll bring to your own work.
A last issue to consider is the effect that affordable color grading has had on the television
industry. In most current episodic television productions, the visual style is now as good
as in a feature film. This dramatic change in quality has made television programming
better than ever.
An unintended benefit of this change is that top-level feature film actors now move into
television work and back to film with amazing freedom because television no longer looks
like an inferior medium. Also, high-level film crews and facilities can do a wider range of
both television shows and feature films, while still retaining their premium status. It’s an
exciting time when you consider the additional increase in the number of distribution
platforms for high-quality work, such as streaming services. The industry is growing
more quickly than ever, which means talented editors and colorists are more in demand
than ever!
The Goals of Color Grading
Color correction can be considered the process of choosing which parts of the raw image
data to display to create a pleasing image for the viewer.
Developing the Image
The latest-generation digital cinema cameras are almost all capable of either shooting raw
color space image data or, at the very least, recording RGB image data with a log-encoded
exposure. Doing so preserves the maximum amount of image data for manipulation
during the color correction process. While this is great for flexibility in workflow and for
185An Introduction to Color Correction
making high-quality adjustments, acquiring media in this way forces you to take the extra
```
step of transforming it into a viewable image for editing and finishing (in much the same
```
```
way that film negatives required development and printing to yield a viewable image).
```
DaVinci Resolve simplifies this task with built-in camera raw controls, DaVinci Resolve color
```
management (RCM), and LUT support, so you can quickly get your media to a solid starting
```
point upon which to build the rest of your grade.
```
Log-encoded source (left) and the same source color managed to a deliverable color profile (right).
```
Making Every Clip Look Its Best
While the job of the cinematographer is to light and expose the image with an artistic
intent, your job as an editor and colorist is to realize this intent by adjusting the color and
contrast of the image of each clip so the result is as close to the director’s and
cinematographer’s intentions as possible. In the process, you can overcome
inconsistencies with exposure and color balance that were otherwise unavoidable.
Furthermore, you can subtly adjust warmth and contrast to realize looks that were not
achievable during the shoot, but that the director and cinematographer would have liked.
```
An overexposed image (left) and the corrected image for the audience (right).
```
Of course, in some situations, you may find it necessary to fix media that has more
substantial problems in color and exposure. In these cases, the tools exist to make far
```
more involved changes to the image; however, the quality of your results will depend
```
heavily on the quality and “latitude” of your source media. For example, Blackmagic URSA
186An Introduction to Color Correction
Mini cameras record quite a bit of image data within raw or minimally compressed media
formats, allowing you to make extreme corrections that would be impossible with data
from consumer cameras. Happily, in either case, the color page provides the tools to
process images in many ways to adjust the image to achieve a better look.
Quality Control
While you’re doing all this, it’s important to keep in mind that for all the creative
possibilities that DaVinci Resolve affords, it’s still important that the deliverables you
provide to your client have appropriate signal levels relative to their distribution
requirements. Programs destined for cinema, broadcast, or streaming usually have very
specific outer boundaries of luma, chroma, and gamut that you must not exceed, or you’ll
risk having a show kicked back to you for quality control violations.
DaVinci Resolve provides tools specifically designed to help you keep an eye on how the
image data is affected and to fine-tune the image. In particular, the scopes display the
standard Waveform, Parade, Vectorscope, and Histogram graphs that you can use to
objectively analyze image data. These scopes let you see the boundaries of what’s possible
and make it easy to spot subtle problems and compare the characteristics of one image
to another.
Balancing Scenes
It’s rare for uncorrected shots to match one another seamlessly. Even the most carefully
exposed angles of coverage can have small variances that should be evened out. For
example, run-and-gun programs using available light often result in edited scenes with
huge changes in lighting and color as one shot cuts into the next.
Whether small or large, variations between shots can call undue attention to the editing
and jar the audience in ways that distance them from the program. Balancing these
differences is another fundamental task of the colorist. You know you’re finished when
every shot in a scene looks like the same time and the same place, and the color and
contrast adjustments you’ve made flow unnoticeably from one clip to the next.
Adding Style or Custom “Looks”
Of course, it’s not all about subtlety and correction. It’s often appropriate—when grading
music videos and commercials, for instance—to bring some radical visual style to a piece.
Here, too, DaVinci Resolve provides an abundance of features for manipulating unexpected
aspects of the image. For example, you can use custom curves to create an illusion of
chemical cross-processing.
187An Introduction to Color Correction
```
Grading an image (left) with several primary and secondary grades to create the look (right).
```
The Tool Hollywood Uses
If all that isn’t enough incentive to plunge forward into the next few lessons, keep in mind
that DaVinci Resolve has become the tool of choice for some of the largest post-production
facilities in the industry, worldwide. And yet, thanks to its accessibility, within the last
several years, DaVinci Resolve has also become the go-to tool for a wide variety of smaller
boutique post companies and individual artists. Considering only projects completed
recently, DaVinci Resolve was used to grade blockbusters such as Rocketman and John
```
Wick: Chapter 3—Parabellum, along with indie productions such as The Big Sick and A Ghost
```
```
Story; not to mention television shows including HBO’s Westworld, AMC’s The Walking Dead,
```
and Amazon Prime’s The Marvelous Mrs. Maisel.
Whether you’re looking to build a foundation of skills to enter the post-production industry
as a contributing artist or you want to develop the ability to finish your personal creative
work in your own way, the following lessons will usher you into a much larger world of
image manipulation and artistic expression than has ever been available in the average
```
nonlinear editing (NLE) application.
```
Lastly, color grading is just fun! The feeling of resting your hands on the trackballs and
holding the emotion of your images in your hands is exhilarating. It’s like no other feeling
```
in the world; you can make adjustments in real time, instantly see the results, and feel the
```
emotional impact in your heart. We believe that color correction is one of those tasks that
is more creative than cerebral. It’s also one of those jobs that surprises you every day and
has an emotional connection that reminds us why we fell in love with the film and television
industry in the first place!
Enjoy the journey!
188This p age is intentionally left blank
Time
This lesson takes approximately
75 minutes to complete.
Goals
Exploring the Color Page Interface 190
Using the Primary Corrector 193
Understanding Video Scopes 195
Color Correcting Using Lift,
Gamma, and Gain 198
Understanding Nodes 204
Using Nodes to
Separate Corrections 206
Labeling Nodes 210
Making Automatic Adjustments 211
Using Separate Timeline Settings 217
Using DaVinci Resolve
Color Management 218
Matching Different Cameras 224
Adjusting Individual
Color Channels 228
Using Curves for Primary
Color Corrections 231
Using Curves in Separate Nodes 236
Using the HDR Wheels 240
Lesson Review 245
Lesson 4
Performing Primary
Color Corrections
Like editing, audio mixing, and visual
effects, color correction is an art form
that takes time to learn and master.
Color is an incredibly powerful creative
tool that can define the style and
convey the mood of your film. If you
give yourself the time to practice and
learn, you can master this exciting skill
and create images that look amazing!
These next three lessons provide
a valuable overview of the most
important color-correction tools to get
you comfortable with how they work.
You’ll learn about the primary corrector,
secondary adjustments, nodes, and
even applying DaVinci Resolve FX for
special effects. You’ll use the same
tools that Hollywood’s top colorists
use to correct and finish the biggest
blockbuster films, episodic television
shows, and commercials. Experience is
key, and with so many controls at your
fingertips, these lessons will give you
the start you need toward learning this
creative skill.
190Lesson 4 Performing Primary Color Corrections
Exploring the Color Page Interface
The exercises in this lesson will teach you how to make color adjustments on clips to
correct common issues such as overexposure, low contrast, and incorrect white balance.
All these corrections, along with the creative process of color grading, take place within the
color page in DaVinci Resolve. Let’s start by examining the color page layout.
1 Open DaVinci Resolve to the Project Manager window.
In Lessons 4–6, you’ll learn a color-grading workflow using a documentary about the
Conservation Film Company in South Africa. The project you will use was archived
using DaVinci Resolve. An archive is a self-contained project that includes all its media.
All you need to do is restore the archive, and the project will be available with all the
media already linked.
2 Right-click in the Project Manager window and choose Restore Project Archive.
3 Navigate to R20 Beginner Guide lessons > Lesson 4. Select the Conservation.dra folder
and click Open.
4 In the Project Manager, open the Conservation Film Company project, and then from
the edit page Timelines bin, double-click Conservation Intro to load the timeline.
191Lesson 4 Performing Primary Color Corrections
This timeline has only five clips. All the clips are from a Blackmagic Camera.
One of the best aspects of DaVinci Resolve is that editing and color grading are
completely integrated into a single application, so you can easily move between
the two with a single click.
5 At the bottom of the DaVinci Resolve window, click the Color button to go to the
color page.
NOTE If your UI layout does not look like the image below, go into the
Workspace menu and choose the Reset UI Layout option.
The Node Editor connects
color corrections, image
adjustments, and effects
to create unique looks.
The timeline is divided into
thumbnails and a mini-timeline.
The left palettes contain
primary adjustments for
color, contrast, and RAW
image processing.
The center palettes
provide access to curves,
windows, tracking,
and keying controls.
The lower right area may
display the Keyframes
Editor, scopes, or a
metadata display.
The gallery includes saved
adjustments that you can
copy to other clips in
the timeline.
The viewer shows the
frame at the playhead’s
current position
in the timeline.
192Lesson 4 Performing Primary Color Corrections
NOTE When you’re using DaVinci Resolve on a computer display with
a resolution lower than 1920 x 1080, the left and center panels and buttons
might consolidate and the interface will just have two windows below the
Timeline window.
When you switch to the color page, the playhead’s position from the editing timeline
remains the playhead’s position in the color page timeline. The color page does not
```
change or alter any cuts or transitions; it just provides a way of looking at your timeline
```
that’s more appropriate for color correction.
6 Click thumbnail number 02, the second clip in the timeline.
An orange outline appears around the selected thumbnail, and the playhead jumps
to the first frame of that clip.
7 Below the thumbnail, double-click the Apple ProRes 422 HQ name to switch to viewing
clip names.
The mini-timeline below the thumbnails displays thin bars to represent each clip.
A bar’s width is proportional to a clip’s duration. Like the cut page, the mini-timeline
shows all the clips in a timeline.
8 Press the Spacebar, and the playhead will begin to play through the timeline.
If you leave the timeline playing, you’ll notice that the orange highlight around the
thumbnail will jump from clip to clip, so no matter where you are in the timeline, the
clip you’re looking at will always be the one selected.
9 Press the Spacebar again to stop playback.
TIP If a track is disabled in the edit page, it will be dimmed in the color page’s
mini-timeline.
Now that you have a basic understanding of the color page layout, you’re ready to make
some adjustments.
193Lesson 4 Performing Primary Color Corrections
Using the Primary Corrector
The most popular controls for creating different looks and balancing your shots are found
in the primary corrector. Because DaVinci Resolve includes many controls in the primary
corrector, you’ll spend much of your time using this palette of tools while you’re on the color
page. In this first exercise, you’ll make a few adjustments just to get a feel for the controls.
1 In the timeline, make sure thumbnail 01 is the selected clip.
The primary corrector is divided into four regions: Lift, Gamma, Gain, and Offset. Each
region is split into the color balance controls for adjusting the tint of the image and the
master wheels for adjusting the tonality or brightness.
The Offset adjusts the overall picture. In this first clip, the overall shot looks a little
bright, probably due to the conditions in which it was filmed. The darker areas of the
image look a little gray, particularly the background and the darker sections of the
antelope. To make an entire image brighter or darker, you use the master wheel,
located under the color wheel.
194Lesson 4 Performing Primary Color Corrections
2 Drag the Offset master wheel to the left until the image is not as bright and the
shadows appear to be black. The red, green, and blue number fields above the master
wheel should end up around 10.00. There is quite a lot of range in the clip, so you can
go darker if you wish.
This improves the tonal range. When you hear the term tonal range, we are talking
about brightness values as if the image were black and white. What this has not done
is affect the color in the image. We can see this as the image looks quite blue, and we
want something a little more neutral in color.
3 Drag the color indicator at the center of the Offset color wheel left toward yellow until
the blue hue in the image fades and the image looks more neutral in color.
TIP This process involves adding a complementary color to an image.
Complementary colors sit opposite a specific color on the color wheel,
so in this case, yellow is the complementary color of blue. If you are ever
unsure about how to remove a color cast, decide on the color of the cast in the
image and then start by adding a color that is directly opposite in the
color wheel.
195Lesson 4 Performing Primary Color Corrections
Adjustments made in the color balance controls are subtle. In most cases, you are just
moving the indicator a few pixels away from the color you want to reduce.
4 To turn the correction you have applied on and off to see the before and after, click the
Bypass button in the upper right corner of the viewer to turn the grade off.
5 Click the Bypass button again to turn it back on.
TIP Always remember to turn the Bypass back on because it turns off the
grading for all the clips in the timeline.
While these adjustments have been made by what you can see in the viewer,
DaVinci Resolve includes tools that can show exactly what is happening in the image
and therefore give you a better understanding of where corrections may be needed.
This is where the video scopes come in.
Understanding Video Scopes
The correction you just made was performed by looking at your viewer and deciding which
changes were needed. However, this can be quite difficult to do by eye—for example, a
color cast may only be in the brighter areas of the image and not in the entire image. But
how can you determine this? Video scopes can give you information about the clip you’re
looking at to help make accurate decisions when grading.
There are several scopes at your disposal: Waveform, Parade, Vectorscope, Histogram, and
CIE chart to check a clip’s luminance, exposure, hue, saturation, and color space.
You will use the Parade scope to help balance a shot.
1 In the timeline, make sure thumbnail 02 is the selected clip.
2 In the lower right window, click the Scopes button on the far right of the toolbar.
196Lesson 4 Performing Primary Color Corrections
3 Click the disclosure arrow to open the Video Scope dropdown menu.
You can switch between the five different scopes using the menu, depending on what
you want to monitor.
4 Choose Parade.
You may just want to make your scopes a little brighter in the interface so they can be
seen more clearly.
5 Click the Settings button.
6 From the Settings menu, drag the Parade slider to the right to make the scopes a little
brighter so you can see them comfortably in the interface.
197Lesson 4 Performing Primary Color Corrections
7 Click the Settings button again to close the menu.
The Parade scope graphs each color channel individually. The graph is read from bottom
to top with absolute black at line 0 and absolute white at line 1023. When balancing
shots, the image in the parade, called the trace, ideally should not go below 0 or above
1023. Otherwise, the image will clip—cut off parts of the image data—and lose detail.
TIP You can switch back to the Keyframes Editor and hide the video scopes to
free up your graphics card’s processor and improve playback performance.
Reading the Parade from left to right, each channel corresponds to the image
displayed in the viewer. For instance, the left part of the red, green, and blue trace
corresponds to the image’s left part. This layout makes it easy to look at the scope and
know exactly which area you are evaluating.
198Lesson 4 Performing Primary Color Corrections
Color Correcting Using Lift,
Gamma, and Gain
1 Make sure you have clip number 02 selected.
Looking at this clip, it appears a little flat with little contrast in the shot, and there
is a notable color cast. Areas of the clip that should be near white look gray. This is
reflected in the parade. The top of the trace, rather than being close to the top of the
parade, sits well below it. This means the highlights in the image are not
bright enough.
Instead of using the Offset controls, you will use the Lift, Gamma, and Gain controls to
make the adjustments. The Gain control allows you to adjust the brighter parts of
the image.
199Lesson 4 Performing Primary Color Corrections
2 In the Gain region of the primary color wheels, drag the master wheel right so that the
highlights start to look brighter.
3 Using the Parade scope, adjust the highlights so the top of the trace touches the top
1024 line in the red channel. The value in the Gain control should be around 1.11.
NOTE If you go beyond the 1024 line on the parade, you will notice areas of
the image starting to clip, as mentioned earlier. You can try this to see the
effect if you continue to push the Gain master wheel: details in the face will
start to look very bright but will essentially lose detail.
200Lesson 4 Performing Primary Color Corrections
The highlights in the image now look better. However, the image still looks quite
orange. This is reflected in the parade since the top of the red channel is higher than
either the blue or the green channel. This shows that there is more red in the
highlights, and therefore your brighter areas of the image look quite warm.
To create pure white using additive colors, you mix an equal amount of red, green, and
blue. A white image would have the red, green, and blue traces completely level along
the top of the Parade scope. Conversely, pure black would have the three color
channels completely aligned at the bottom of the graph.
That being the case, you’ll use the Parade scope to make color balancing easier.
NOTE Sometimes the parade may look uneven due to the nature of a shot.
For example, a sunset will have a much higher red channel compared to the
green and blue, simply due to the time of day it was recorded.
4 Using the Gain color wheel, click and drag the center point away from red, toward
cyan, so the tops of the parade traces are approximately level toward the right side.
```
For now, there is a peak of red in the center, which is our subject; however, you would
```
expect this to be redder since skin tone sits in the channel between red and yellow.
201Lesson 4 Performing Primary Color Corrections
5 If at any point you make a mistake, you can simply reset the controls by clicking the
Reset button in the upper right corner of each region.
6 Make the highlights a little brighter again by getting the top of the parade in the red
channel to touch the top 1024 line.
```
Now the highlights of the image look correct; however, you need to adjust the
```
shadows as well to improve the contrast in the shot since it still looks a little flat. It also
looks a little too cold due to the fact that there is more blue in the shadows. This can
be seen in the parade since the blue channel in the shadows is higher.
7 Under the Lift color wheel, drag the center point away from blue toward yellow, and
you will see the bottom of the blue scope start to drop down. You will notice, however,
that the green channel does not really move, and therefore the shadows start to look a
little green.
8 Continue to drag the center point more toward red until the bottom of the parade is
level across all three channels.
Immediately, the shot looks less cool. Without the scopes, it might have been difficult
to pick up on the fact that the blue tint was actually in the darker areas of the image.
The shot still looks a little flat. If you look behind our subject, Sean, to where his shirt
collar sits off his neck, the area appears to be gray, not black.
202Lesson 4 Performing Primary Color Corrections
9 Drag the Lift master wheel to the left so that the shadows start to look darker. Drag
the wheel until the area of the shirt collar looks black or until the bottom of the parade
touches the 0 line.
NOTE Dropping the levels below the bottom of the parade works in the same
way as it does in the highlights. Clipping the shadows will mean detail will be
lost in darker areas. This, however, is not as noticeable as it is in the highlights
and can also be used as a technique to hide such things as noise in dark areas
of an image.
Immediately, the shot’s contrast has improved, and the shadows no longer look gray.
10 Click the Bypass button in the upper right corner of the viewer, or press Shift-D on the
keyboard, to show the clip without the correction. Click the Bypass button again to
turn it back off to show the adjustments you have made.
203Lesson 4 Performing Primary Color Corrections
Using these controls, you have now accurately adjusted the clip’s contrast by
controlling where the black and white points sit by using the Lift and Gain controls. You
have also adjusted the color in the highlights and shadows to remove any tint that may
have been present in those areas, rather than using the Offset control that would
adjust the color for all areas of brightness in the clip.
NOTE DaVinci Resolve’s viewers are previews that are not intended to be
color-critical displays. For projects that are intended for online delivery or
social media, the viewer output may be suitable. For television broadcast or
digital cinema, you can use a Blackmagic Design UltraStudio or DeckLink card
to connect to a broadcast or digital cinema calibrated display.
Now let’s look at Gamma.
The master wheel under the Gamma color balance control adjusts the brightness while
maintaining the black and white points that you set previously. In general, once you set
your black and white points, you can make further adjustments using the Gamma
wheel. This is often where you can start to build more of a look for the shot. Gamma is
sometimes referred to as midtones because it adjusts the middle tonal range
of an image.
In this case, we will make the image a little darker again, but we will not adjust
the Lift parameter.
11 Drag the Gamma’s master wheel to the left to make Sean’s shirt a little darker, but
make it pop a little more. The luminance, red, green, and blue values above the master
wheel should end up around -0.06.
Your image still looks a little green, so you may want to ease that off a little and make
the subject a little warmer. You can see in the middle of the parade that the green
channel sits slightly higher.
204Lesson 4 Performing Primary Color Corrections
12 Click and drag the center of the Gamma color wheel toward magenta so the image
looks a little less green and has a warmer feel. The values you are aiming for are red
-0.03, green -0.06, and blue -0.03.
As you can see, the Gamma control is more subjective. As the colorist, you can decide
if the shot should be brighter or darker, warmer or cooler.
TIP Trust your eyes. While the video scopes are there to help you, they don’t
always have to line up exactly. Start by adding a color and see if you get a
result that you like. Sometimes grading solely by the scopes can push the color
too far in one direction.
The Lift, Gamma, and Gain controls are not narrow adjustments that change only the dark,
midrange, or bright areas. In fact, their ranges overlap by a considerable amount. This
overlap helps you make more natural, smoother-looking adjustments, but it also means
that you’ll need to move among the three color balance controls to achieve the best results
because adjusting one control visibly impacts the others.
Understanding Nodes
The color page uses nodes for multiple color corrections. Instead of stacking color
corrections and effects as layers, you can add as many color correctors and filter effects
as you like using nodes. You can view the nodes as a color correction flowchart for each
individual clip. The clip, or the input, starts at the left, flows through each node, and ends
on the right side of the screen with the corrected image output. Unlike the Fusion page
205Lesson 4 Performing Primary Color Corrections
nodes, each node in the color page is a full DaVinci Resolve color corrector and not an
individual effect that performs only one type of image processing. Think of nodes as
building blocks that allow you to construct your finished grade.
The adjustments you made in the preceding exercises were performed using the first
node, which is provided for you automatically in the Node Editor. As you create more
sophisticated corrections, you can add more nodes that target different parts of the
image or add effects.
1 Select clip 01 again in the clip window. Right-click over node 01 in the top right Node
Editor window.
2 From the contextual menu, choose Add Node > Add Serial. A second node will appear
in the node window.
206Lesson 4 Performing Primary Color Corrections
You can tell which node you’re working on because an orange outline will highlight the
active node.
Using Nodes to
Separate Corrections
Sometimes, as you balance shots, you may decide adjustments are best performed by
separating initial tonal corrections from other adjustments, such as pushing contrast into a
shot. This builds on the idea that the first node is the initial balance, and further
adjustments can be made once a shot is balanced correctly.
For the first shot, the offset balance you did was OK, but there is more work to do in the
grade to get the shot looking really good. The contrast needs to be better, and the shot
still looks a little blue.
1 On the node you just created, go into the left palette and drag the Lift master wheel to
the left so the values read -0.04.
2 Drag the Gain master wheel to the right until the highlights touch the top of the 1024
line. The values should be around 1.25.
The contrast in the image should look much better now since the brighter areas look
less dull and the shadows look more defined.
Rather than Bypass the grade, you now just want to see the before and after of the
adjustment you have just made.
207Lesson 4 Performing Primary Color Corrections
3 Click the number of the node in the bottom left corner to turn off the node. You will
see it turn gray when it’s off.
Now you will see the shot with just the original balance node on.
4 Click the number again or press Command-D/Ctrl-D on the keyboard to turn the
selected node back on.
The contrast still needs punching up a little. The Contrast tool allows you to push the
contrast in your shot without going beyond the set white and black points that you
made. The pivot essentially changes the point from where the contrast adjustment is
made to allow you to make the image brighter or darker.
5 In the Contrast parameter, place the mouse pointer over the numbers and drag to the
right to around 1.200 to add more contrast to the shot.
6 The brightness needs to come down slightly, so drag the Pivot parameter in the same
way until it reads around 0.851.
TIP To reset any of the parameters, simply double-click the tool label in the
interface and the parameter will reset.
The shot now needs warming since it is in the desert, and despite the earlier
correction, it still looks a little blue. Again, we want to do this on a separate node, so we
don’t need to alter the other changes we’ve already made.
7 Right-click node 02 and choose Add Node > Add Serial from the contextual menu or
press Option/Alt-S on the keyboard to add a serial node.
208Lesson 4 Performing Primary Color Corrections
```
8 Make sure node 3 is selected (it should be by default). Click the Temp parameter and
```
drag it right until it reads around 1000 or you feel the image is suitably warm enough.
TIP In addition to dragging the number fields, the values themselves can be
typed in. Simply double-click the parameter value and type in a new value.
Finally, the focus in the shot looks a little soft, which could be due to the amount of
heat haze in the image. We will add a final node to try to compensate for this and
complete the look of the shot.
9 Right-click node 03 and choose Add Node > Add Serial from the contextual menu or
press Option/Alt-S on the keyboard to add a serial node.
10 Go into the middle window of the interface.
11 Select the Blur tool from the middle toolbar window.
209Lesson 4 Performing Primary Color Corrections
12 Click and drag the Radius Blur control down to around 0.40 so the foreground and the
antelope start to look a little sharper.
TIP When using sharpening, keep in mind that not only will you sharpen the
image, but also any noise that exists. This can start to degrade the material.
When using sharpening, make fine adjustments to get the best results.
13 Click the number or press Command-D/Ctrl-D on the keyboard to turn off the selected
node to see the results of the sharpening.
You can now start to understand how useful nodes are, since they allow you to build your
grades a step at a time without affecting the changes you made previously. Since they can
be turned on and off individually as well, when sitting with clients, you can easily toggle
between before and after adjustments to show what has been done. In this case, you can
toggle the sharpening on and off to see the softening being fixed without affecting any of
the other grades.
TIP If you want to know about nodes in more detail, The Colorist’s Guide to
DaVinci Resolve 20, by Daria Fissoun, explains why you use nodes and the different
types of nodes available.
210Lesson 4 Performing Primary Color Corrections
Labeling Nodes
The more adjustments you make on a clip, the more nodes you are likely to need. After a
while, you could have a complex-looking node tree, so it’s a good idea to start labeling
nodes to give you an indication of what adjustments may have been made on each node.
1 Still on clip 01, right-click node 01 and choose Node Label from the contextual menu.
```
2 Label the node BALANCE and press Return (Enter) on the keyboard to exit the
```
text entry.
3 Repeat the process, labeling node 02 CONTRAST, node 03 TINT, and node
04 SHARPEN.
Now you have a good idea of which grade is on which node, so you can make an
adjustment on the correct node at any time—for example, changing the overall color
to a cooler look can be done on the TINT node.
211Lesson 4 Performing Primary Color Corrections
Making Automatic Adjustments
Now that you have a good understanding of how the primary color controls work, you can
balance, or normalize, your shots before you start down the path of creating complex
looks or isolating certain colors or areas. Normalizing shots is often the first part of the
grading process that can remove inaccuracies that might have occurred while filming.
Doing this will unify the shots, making it easier to apply creative grades later.
However, what happens if you are unsure of what needs correcting, especially if you are
just starting out with color grading? Or maybe due to time limitations, you just want to
correct shots quickly. DaVinci Resolve provides a range of quick, automatic tools to help
you correct shots.
1 Select clip 03 in the timeline. You can see that the tonal range is quite narrow due to
the lighting conditions of early morning.
```
2 Click the Auto Balance button (the A within a circle) in the upper left corner of the left
```
palette window, and the clip’s tonal range and color will balance automatically.
NOTE An Auto Balance may not work on every clip in your timeline because it
depends on how the material was shot. For example, with a clip shot in low
light, the Auto Balance might try to make the image much brighter, which you
might not necessarily want.
212Lesson 4 Performing Primary Color Corrections
As you can see, the Auto Balance has given you a good starting point. However, the
highlights are a bit too high, and they are also too blue.
3 Add a second serial node by right-clicking node 01 and choosing Add Node > Add
Serial from the contextual menu or by pressing Option-S/Alt-S on the keyboard.
4 In the Gain region, drag the master wheel left to bring the highlights down so that the
top of the blue parade graph can be seen to ensure nothing is clipped. The values
should be around 0.83.
5 Click and drag the center of the Gain color wheel toward orange to balance out the top
of the parade and make the shot look a little warmer.
6 Press Option-D/Alt-D on the keyboard or press the Bypass button to see the before
and after grade.
You have done a pretty good grade by using the Auto grade and then refining it with
an additional node. Automatic adjustments may not get you to a perfect grade, but
they can certainly set you on the right path.
7 Select clip 05 in the timeline. This is a different section of the same interview clip that
we did our initial correction on. Instead of using a manual adjustment, we could try to
use the Automatic White Balance tool to even out the shot.
213Lesson 4 Performing Primary Color Corrections
NOTE If you are using different sections of the same clip in the color page,
DaVinci Resolve will treat them as separate clips. If you do wish to grade the
entirety of a clip, you can learn more about this in The Colorist’s Guide to
DaVinci Resolve 20.
8 Click the White Balance tool in the upper left corner of the left palette. You will see that
the mouse pointer changes to an Eyedropper tool.
TIP If you accidentally click the White Balance tool, simply press the Esc key on
the keyboard to go back to the default mouse pointer.
9 Bring the pointer over the viewer and place it over an area that should be white—in
this case, we will use Sean’s teeth. Click the selection.
10 The clip will immediately lose its orange cast since you have identified an area that
should be white, and the software has automatically corrected for this.
```
It does not quite match the initial grade we did; however, it is quite close, so we can add
```
another serial node and make some further adjustments so the two shots can look similar.
214Lesson 4 Performing Primary Color Corrections
11 Add a serial node by right-clicking node 01 and choosing Add Node > Add Serial from
the contextual menu or by pressing Option-S/Alt-S on the keyboard.
12 Drag the Gain master wheel right to around 1.20 so the highlights are correct.
13 Drag the Lift master wheel left to around 0.03 so the shadows sit toward the bottom
of the parade.
Again, using an automatic tool has given you a good starting point that you can build
on to get a nice, even color balance. We just need to make some final adjustments so it
looks close to the first interview.
14 Add a serial node by right-clicking node 01 and choosing Add Node > Add Serial from
the contextual menu or by pressing Option-S/Alt-S on the keyboard.
15 On the second node, drag the Gamma master wheel to around -0.06 and drag the
Gamma color wheel up toward red.
A little later in this chapter, you will learn how to match shots, but this gets us pretty
close by simply adjusting an automatic white balance.
215Lesson 4 Performing Primary Color Corrections
The final auto balance allows you to automatically set black and white points
in an image.
16 Select clip 04 in the timeline.
17 Select the Pick Black Point tool to the left of the Lift color wheel and move it over
the viewer.
An RGB tooltip appears next to the point, giving you a brightness value for the pixel
```
you’re hovering over. The values range from 0 (black) to 255 (white). When selecting a
```
black point, you want the red, green, and blue values to be as close to 0 as possible
without all displaying 0. If all the values display 0, there’s a chance that there is no
brightness information present.
18 Click one of the cheetah’s spots on its leg in the foreground. The shadows will be
immediately darkened so the spots now look black.
TIP You can zoom in and out of the viewer by either scrolling a middle mouse
button or using the shortcut Command-+/- or Crtl-+/-. Pressing Z on the
keyboard will resize the image back to the window.
Clicking the shadow area identifies it as your darkest black point and adjusts other
pixels accordingly. It also corrects any tint in the black so that no single color channel
dominates in the shadow regions.
216Lesson 4 Performing Primary Color Corrections
Now you’ll do the same for the white point. In the viewer, you’ll locate a bright point in
the image and select it. The point should not be the absolute brightest point, but rather
an area you think should be soft white. In other words, you do not want to pick the sun
in every outdoor shot but rather the white T-shirt someone is wearing or a white car.
```
This shot includes a small white area on the cheetah’s tail; however, it is not currently
```
in the shot.
19 To ensure that you are using the same timecode reference as the edit page, click the
dropdown menu next to the timecode in the viewer and make sure it is set to
Timeline Timecode.
20 Press the Spacebar and play the shot until the tail appears in the shot. Using the Left
and Right Arrow keys on the keyboard, nudge the playhead until the timecode reads
01:00:12:22.
21 At the upper left corner above the Gain color wheel, click the white point picker.
22 Place the picker over the white area of the cheetah’s tail and select it. You can zoom in
if needed.
217Lesson 4 Performing Primary Color Corrections
NOTE DaVinci Resolve is an application that requires a three-button mouse.
```
The third wheel on the mouse has numerous uses; however, in the color page,
```
it can be used to zoom in and out of the viewer by scrolling in and out on the
wheel. Once zoomed in to the viewer, clicking and holding the middle mouse
button will allow you to navigate around the zoomed-in image in the viewer.
23 Click the Bypass button or press Shift-D to see the original image. Click the button
again or press Shift-D to turn the grade back on.
Using the auto select black point and white point tools has allowed you to adjust the
tonal range of the image quickly and easily by allowing you to decide what should be
black and what should be white in the image.
Using Separate Timeline Settings
Now that our introduction timeline is completed, you’ll want to keep the grades exactly as
they are. In the next section, we will start looking at DaVinci Resolve’s incredibly powerful
color management. However, we don’t want the current timeline to use any of those
settings. So to ensure that it keeps its own settings, we’ll make it independent from the
project settings, meaning the grades will not change.
1 Open the media pool in the color page and select the Timelines bin.
2 Right-click the Conservation Intro timeline and, from the contextual menu, choose
Timelines > Timeline Settings.
218Lesson 4 Performing Primary Color Corrections
3 From the Timeline menu, uncheck the Use Project Settings box and select the
OK button.
The timeline now uses its own independent settings, so any changes that we now
make to the project settings will not affect our graded timeline.
Using DaVinci Resolve
Color Management
So far, we’ve had it fairly easy in our color-grading process. We worked with a few controls
and made the camera files look better. In your projects, if all you do is work with the same
camera files, then you can essentially continue with the process we started in this lesson.
However, filmmaking is technical and at times complicated. Few aspects of the process
illustrate this as well as cameras and their various file formats. Each camera manufacturer
```
tries to give you the best-looking image possible by customizing the color palette (gamut)
```
```
and tonal range (gamma). You’ll often hear these types of clips referred to as log clips due to
```
their logarithmic contrast profiles. The result of recording log clips is that they don’t look
great on your monitor. When using different log clips from different cameras in a single
project, you need to manage various gamuts and gamma ranges more efficiently to achieve
```
consistency in your final output. That’s where Resolve color management (RCM) helps.
```
219Lesson 4 Performing Primary Color Corrections
1 Above the viewer, click the dropdown arrow next to the timeline name to reveal all the
project’s timelines.
2 Choose the Conservation Filming timeline.
This timeline contains shots from several different cameras. The majority of the
material comes from Blackmagic Design’s Pocket 4K and 6K cameras. However, we also
have a shot from our secondary camera, which is a Sony, a drone, which is a DJI, and
also a GoPro. All these clips have their own gamut and gamma profiles.
3 In the timeline, click the fourth thumbnail.
Like many clips from digital cinema cameras, these scenic log clips are not intended
to look perfect on a TV or computer display for example. Although they have a wide
tonal range and a wide color gamut, they look flat and undersaturated. Your monitor is
expecting a profile that it understands, so it has no idea how these digital cinema
```
camera clips should look. Resolve color management (RCM) is the easiest and most
```
accurate way to unify different clips from different cameras so they all match your
desired output.
NOTE DaVinci Resolve color management is a non-destructive process. Even
though you will see the clips in a profile that is suitable for viewing on a TV, the
original profile of the camera that contains a lot more information is still
there—it is just mapping this profile to the output.
4 Click the Project Settings icon in the bottom right corner of the screen.
220Lesson 4 Performing Primary Color Corrections
5 Select the Color Management category from the window that pops up.
6 In the Color Science dropdown menu, choose DaVinci YRGB Color Managed.
Enabling color management presents a new dropdown menu below the Color Science
menu. By default, Automatic color management is turned on. This preset menu
contains two settings, either SDR or HDR, which can be chosen from the Color
processing mode menu. SDR is the choice for standard dynamic range source media,
```
and output. The media in our timeline is a mix of log HDR (high dynamic range) source
```
media and SDR media.
TIP The Automatic color management shows only a few options for
processing and output. If you cannot find the setting you require, uncheck the
Automatic color management option to see the full range of processing
modes and color outputs.
7 In the Resolve Color Management Preset dropdown menu, choose HDR.
221Lesson 4 Performing Primary Color Corrections
Although this preset is still targeting an SDR output, it is the best choice when using a
mix of HDR log and SDR clips because it preserves the super-bright highlights
contained in HDR source media.
The output color space should be set for your final output delivery. Because our
project will be output to SDR, we’ll leave this menu set to SDR Rec709. This is the
standard setting for many displays, including standard TVs.
8 Click Save to close the settings but keep an eye on the viewer.
TIP You can change the output color space at any time when you are
delivering to different display devices. This is one of the main benefits of using
a color-managed workflow.
When using DaVinci Resolve color management, some source clip formats like RAW
files, as well as some QuickTime and MXF wrapped files, include information about the
color gamut and gamma. If these metadata tags are present in the files, RCM can
automatically read them and apply the correct settings for the source clips. This is the
case with the clips we have now. They are all tagged and color managed, so now they
look brighter and more colorful on our HD monitor or computer screen.
222Lesson 4 Performing Primary Color Corrections
However, you will likely have some content that does not include metadata tags,
so let’s walk through how you might manually set the Input Color Space for source
clips that are not set automatically.
Typically, you want to change the Input Color Space value to match the device that
recorded the imported clips. By default, a Rec709 Gamma 2.4 setting is applied to clips
without metadata. This is probably suitable for your HD recorded clips, but you will
come across other formats.
9 Select clip 17 in the timeline. This clip is from a GoPro camera.
10 Go into the Project Settings and turn off the Color Management.
You will see the GoPro clip does not change. Since it was shot in a Rec709 profile, it
simply matches the output profile, so while the clip might have no metadata at this
stage, it doesn’t really matter.
11 Go into the Project Settings and turn Color Management back on.
When you have clips without metadata tags, you can manually set those clips
individually from the timeline or in groups from a bin.
TIP Adding the Input Color Space as a media pool column will display the
currently assigned color profile for each clip, whether it is assigned manually
by you or automatically by metadata.
223Lesson 4 Performing Primary Color Corrections
12 Click clip 18 in the timeline. This is a shot from a DJI drone, and it still looks very flat.
This is because there’s no metadata in the clip that DaVinci Resolve can read, so it
cannot understand the profile.
13 Right-click the thumbnail in the timeline and choose Input Color Space > DJI >
D-Gamut/D-Log. The clip will adjust and will no longer look flat.
224Lesson 4 Performing Primary Color Corrections
NOTE Transcoding clips from one format to another tends to strip the
metadata out of the file. If you do convert your clips from one video codec to
```
another, make a note of the camera they were shot on; it will save you time in
```
the long run.
Note that you have not color corrected these clips, although they may appear
improved. If the clips were shot overexposed, they will appear overexposed. If they
were shot with the incorrect white balance, they will display incorrect white balance. All
you have done is correct the different gamma curves and color gamuts, so they are
uniformly set to suit your SDR display device and file output. From here, you can use
the techniques you learned earlier to correct contrast, white balance, etc., in the
color-managed workspace.
When grading this sequence, you may find yourself playing the clips repeatedly to
check certain processes you are applying. Playing back the audio continuously may get
a little repetitive, so at this stage we will turn it off.
14 Go to the edit page and click the Mute button next to the audio level. Alternatively, you
can stay in the color page and go to the Fairlight menu and choose Monitoring > Mute.
Matching Different Cameras
1 Select clip 10 in the timeline and press the Spacebar to play it back. Let it run into clip
11 and then stop playback.
Here we have two clips shot at the same time in the same environment. However, they
look different because they were shot on different cameras. Clip 10 is from a
Blackmagic camera, and clip 11 is from a Sony. While both clips have been shot
correctly, the cameras have different profiles and therefore they look different. As we
have established, color management will put them in the same deliverable profile, so
you don’t have to try to match them from scratch. You do want them to look like each
other, so it is less noticeable when switching from one camera to another.
Since the Blackmagic camera is our A camera, we will adjust it first, and then we will
grade the Sony to match.
225Lesson 4 Performing Primary Color Corrections
2 Select clip 10 and then drag the Gain master wheel right to around 1.11 to lift the
highlights of the shot.
3 Drag the Lift master wheel to the left to around -0.07 to get the shadows darker and
improve the contrast in the shot. Now we need to match it.
At this point, you need an easy reference to compare the clips side by side.
DaVinci Resolve has a stills gallery that allows you to take a snapshot of a clip and
compare it to another clip. You will look at the stills gallery in much more detail in
Lesson 6. For now, you just need a reference frame.
4 Right-click the viewer window and, from the menu, choose Grab Still.
5 If the Gallery is not open, click the Gallery button in the top left corner of the interface.
You will see the still you grabbed.
226Lesson 4 Performing Primary Color Corrections
6 Select clip 11 in the timeline.
7 Click the Image Wipe button in the top left corner of the viewer.
You will see that the image splits in two, with the left side of the frame showing you the
selected timeline clip and the right side showing the still. If you drag the split around,
you can adjust it to show more or less of each side.
8 Drag the split slightly to the right to show a little more of Sean’s face on our timeline
clip. You can see that the color just doesn’t quite match.
9 With clip 11 still selected in the timeline, right-click clip 10 and, from the menu, choose
Shot Match to this Clip, and DaVinci Resolve will match clip 11 to clip 10.
227Lesson 4 Performing Primary Color Corrections
While the match does a pretty good job, the shot still needs a slight adjustment, as it
appears slightly too bright in the highlights and a little cold.
10 Drag the Gain master wheel to the left to around 0.95 just to bring the highlights
down slightly.
11 Using the Gamma color wheel, drag the center slightly toward orange. This is a minor
adjustment that may not even register on the controls, but you will notice the shot get
slightly warmer.
12 Click the Image Wipe button to remove the wipe.
13 Press Option-D/Alt-D on the keyboard to toggle the grade off to see the
adjustments made.
Play the two clips together, and you can see that the result is now much less
noticeable. While it’s not an exact match, the viewer would not notice much of a
difference. Different camera angles will always look slightly different due to such
things as light sources being in different places for each camera. With color grading, it
is often a case of what you can get away with.
228Lesson 4 Performing Primary Color Corrections
The DaVinci Resolve Neural Engine
The Color Match uses the DaVinci Resolve Neural Engine to perform the grade.
The Neural Engine is AI built directly into DaVinci Resolve that speeds up certain
processes for the user. It is not generative and does not access third-party AI tools.
The Neural Engine is used for multiple purposes across all the pages, and in the
color page, it is used across several Resolve FX and tools. An example is the Magic
Mask, which allows the masking of complex shapes by using a simple selection so
that elements of the same shot can be graded separately using complex shapes.
Many of the Neural Engine features are included in DaVinci Resolve Studio only.
Original shot Subject selected with Magic Mask
Adjusting Individual Color Channels
Much of the power of DaVinci Resolve comes from the flexibility of its toolset, which
provides many ways to do the same thing. To learn more about the primary corrector
toolset, you’ll explore another method for creating a balanced correction on a new shot.
1 While still in the Conservation Filming timeline with color management turned on,
select clip 03.
The clip requires a tonal and color balance, but instead of using the color wheels and
master wheels, we’ll use the individual number fields for luminance, red, green, and
blue below the Lift, Gamma, and Gain to make fine-tuned adjustments.
229Lesson 4 Performing Primary Color Corrections
These controls allow you to make color and luminance adjustments similar to the
master and color wheels but provide explicit red, green, and blue controls and
separate luminance adjustments in the Lift, Gamma, and Gain regions. So, you might
find them more effective tools for balancing specific color channels in different regions
of a shot. For tonal adjustments, the Y, or luminance bar, allows you to adjust
luminance without changing saturation.
The image has low highlights as well as slightly raised shadows that can be confirmed
in the scopes. Let’s start by setting our black point.
2 In the Lift region, drag the Lift Y number field to the left until the bottom of the green
and blue traces in the parade touch the 0 line, with the value at around -0.08.
You can see the blue channel is ever so slightly lower than the red and green, so let’s
rectify that.
3 Drag the Blue number field to the right to level off the bottom of the parade. This
needs only a slight adjustment until the bottom of the traces are level around 0.01
The darker areas of the image now look better, so we can go ahead and adjust the
brighter parts.
230Lesson 4 Performing Primary Color Corrections
4 In the Gain region, drag the Y parameter right until the top of the traces sit just above
the 896 line and the value is around 1.30.
```
The shot certainly looks brighter now; however, it looks a little too warm, and again,
```
looking at the parade, you can tell this by the fact that the traces are not level at the top.
5 In the Gain blue number field, drag the parameter to the right until the tops of the
parade traces line up and the shot looks cooler.
We could go a step further by adjusting the midtones. Remember that midtones are
more subjective and are quite difficult to measure on a scope, so this will be your
judgment call on what you want to do with the shot.
In this case, it looks as though the cheetah is a little dark.
6 Drag the Y parameter under the Gamma wheel right until you feel the cheetah is a
little brighter and you can see more detail, approximately 0.05.
231Lesson 4 Performing Primary Color Corrections
7 Choose Bypass, or press Shift-D, to see the original image, and then press Shift-D
again to see your grade.
Using Curves for Primary
Color Corrections
In this exercise, you’ll look at a final method of creating a balanced shot. Using custom
curves, you’ll have the greatest degree of flexibility for making tonal and color
adjustments, but this technique also requires some more finessing.
1 Select clip 15.
Looking at the image, you might not be able to tell that there isn’t a lot of contrast, but
looking at the scope, you can see how the trace is all bunched up in the middle of the
graph. This is a common trace appearance for low-contrast images.
You will approach this shot in the same way you did the previous shots: correcting
black point, white point, and color.
232Lesson 4 Performing Primary Color Corrections
NOTE On computers with lower screen resolution, you might have to click the
Curves button to display the curves palette.
The custom curve graph is a plot graph in which you can perform incredibly flexible
adjustments on specific tonal ranges of images. The X axis represents the image’s
tonal values, going from the darkest shadows on the left to the brightest highlights on
the right. Along the Y axis are the output, or offset, values, with darker adjustments
placed lower in the graph and brighter adjustments placed higher.
TIP In the color page, each clip has its own undo/redo history. Choosing Edit >
Undo will undo different steps depending on which clip is currently selected.
The shadows should be much darker since the shot was filmed later in the afternoon,
and therefore areas of the image should be close to black.
2 Position the mouse pointer over the control point located in the lower left corner of
the custom curve graph.
233Lesson 4 Performing Primary Color Corrections
This point is the black-point control. Like the Lift master wheel in the primary corrector,
adjusting this point raises or lowers the black point in a clip.
3 Drag the point to the right until it touches the edge of the Histogram curve in the
curves window. The trace in the parade should be close to 0 on the blue channel.
Moving the black point to the right darkens the darkest parts of the image.
4 Position the mouse pointer over the control point located in the custom curve graph’s
upper right corner.
This point is the white-point control. As with the Gain master wheel, adjusting this
point raises or lowers the white point in a clip.
The highlights in this shot are fairly dull and could use some brightening.
5 Drag the point to the left until the red trace hits the 1024 line. The curve point should
sit two full guide squares to the left of where it started.
Dragging the control point to the left brightens the brightest parts of the image.
You can further increase contrast by darkening the darker midtones and brightening
the brighter midtones. Stretching the distance between the two ranges will increase
the contrast. This is one of the main areas where the curves interface provides a lot
of flexibility.
234Lesson 4 Performing Primary Color Corrections
You can precisely control the contrast by adding two control points to the curve line:
one point in the lower shadows area and one in the upper highlights.
6 Click the curve line directly where it meets the blue Histogram curve, about one-
quarter of the way up from the bottom.
This adds a point to manipulate the shadows. One of the peaks in the histogram shows
you where most of the pixels are in the lower shadow range of this image.
7 Add a point about a third of the way down from the top of the curve line, where the
curve line meets the next guide square.
This will allow you to push the highlights without clipping them.
TIP Right-clicking with the mouse on a curve point will automatically delete
the point.
8 Drag down the lower control point until the image’s shadows look sufficiently dark but
not crushed.
235Lesson 4 Performing Primary Color Corrections
9 Drag up the upper control point until the white sections on the cheetah are brighter
without being clipped.
10 Choose View > Bypass All Grades, or press Shift-D, to see the original image, and then
press Shift-D again to view your corrected clip.
Moving both points into this S-shaped curve is a typical form of adding contrast using a
curve control. It offers more flexibility than the Contrast control or even adjusting the Lift
and Gain master wheels. Using the custom curves, you can define how much shadows are
modified and how much highlights are modified, independently.
TIP Placing points along a curve will allow you to sculpt the contrast to get the
look you want to achieve. If you are having difficulty getting your contrast to look
right using the contrast and pivot controls, try switching to the curves for finer,
custom contrast adjustments.
236Lesson 4 Performing Primary Color Corrections
Using Curves in Separate Nodes
As you have already explored, nodes can be used when you decide adjustments are best
performed separately. To further adjust the clip we just worked on, you’ll use the curves on
two separate nodes to correct the color cast issue.
1 With clip 15 still selected in the timeline, right-click node 01 and, from the menu,
choose Add Node > Add Serial, or press Option-S/Alt-S on the keyboard.
As with the primary corrector’s number fields, you can adjust color separately using
the curves. Looking at the Parade scope, you can see that the blue trace is lower than
the red or green across the image, so you’ll start by adjusting the blue channel.
Before we go any further, it might be a good idea to label the nodes.
2 Right-click over node 01, choose Node Label, and then type CONTRAST.
3 Right-click over node 02, choose Node Label, and then type BLUE BALANCE.
4 Make sure node 02 is selected.
5 In the curve controls area, click the B button to activate the blue curve.
237Lesson 4 Performing Primary Color Corrections
6 Drag the blue channel’s black control point up just a hair until the bottom of the blue
trace in the Parade scope is level with the green.
7 Drag the blue channel’s white control point to the left until the blue trace in the Parade
scope aligns at the top of the graph with the green trace.
This image now looks almost magenta because there is too much red in the image.
8 Add another node as you did previously and label it RED BALANCE.
238Lesson 4 Performing Primary Color Corrections
9 Click the R button in the custom curves and drag the white point down until the top of
the parade traces are level.
10 Carefully drag the black point up slightly so the bottoms of the traces are level. You
have now removed the orange cast on the clip.
Sometimes, balancing the white point, black point, and color casts for shadows and
highlights is not enough. Often, you will come across color casts in midtones as well.
The curves are distinctly capable of correcting color casts in midtones because you
can add control points anywhere along the line to pinpoint specific tonal regions that
need correcting. You can even pinpoint the area you need to adjust by selecting it in
the viewer. Looking at the current shot, it still looks a little blue, so you need to adjust
the midtones.
239Lesson 4 Performing Primary Color Corrections
11 Select node 02 BLUE BALANCE again.
12 In the viewer window, click the onscreen Overlay button menu in the bottom left
corner. Currently, it might look like the Image wipe icon we were using earlier. From the
menu, choose the Qualifier tool.
13 In the viewer, click the area of trees on the left side of the image.
The trees appear to have a blue cast that needs to be corrected. Although you are not
specifically isolating the trees in the shot by clicking in the viewer, you are placing the
control point precisely along the curve line where the color for that tree is located.
240Lesson 4 Performing Primary Color Corrections
14 Drag the blue control point down very slightly until the trees and even the grass in
front of them start to look slightly warmer and greener.
Dragging the point lower in the graph decreases the green in the midtones by adding
more red/magenta.
```
15 Press Option-D (macOS) or Alt-D (Windows) to see the image without the hue curves
```
```
adjustment. Press Option-D (macOS) or Alt-D (Windows) again to view the
```
corrected clip.
```
Before color balance (left) and after color balance (right).
```
Using the HDR Wheels
So far, you have used your Lift, Gamma, and Gain wheels quite a lot. As already explained,
there is a large overlap between the three wheels, meaning that when you move
something in the highlights, it will affect some of the midtones as well. These controls have
```
been used for a long time to balance shots; however, cameras have been developed to
```
shoot higher dynamic ranges and wider color gamuts. This means that just having a tool
that affects the highlights may no longer be enough since the highlights have multiple
ranges. This is where HDR color wheels come in. Rather than having three controls, the
HDR wheels have six and allow you to adjust more precisely areas of shadows, midtones,
and highlights.
241Lesson 4 Performing Primary Color Corrections
1 Select clip 07 in the timeline.
2 Drag the Offset master wheel left just to bring the overall level of the clip down slightly,
to around 18.00.
```
3 Add a second node by pressing Option-S (macOS) or Alt-S (Windows) on the keyboard.
```
4 In the left window, click the HDR tools button.
The window shows four wheels that look similar to the controls you have been using.
Along the top are six circular icons that allow you to choose which of the six controls
you see. By default, the Global wheel is always present and works very much like the
Offset wheel you have been using.
TIP If you would like to use the position of the Global wheel for another
control, this can be adjusted in the HDR wheel options by choosing the Bank
Global With Color Wheels setting.
5 Click the rightmost circular icon in the HDR window, and the wheel labels will change to
Light, Highlight, and Specular.
These wheels will affect the brighter areas of the image, but rather than having just
one control, you now have three. You can also see which area the wheel is affecting by
using the Highlight button for each control.
242Lesson 4 Performing Primary Color Corrections
6 Click and hold the Highlight button on the Highlights wheel, and you will see the
viewer turn gray, apart from the sky in the image. Anything that turns gray will not be
affected by that color wheel.
7 Make sure node 02 is selected and, using the Highlight wheel, drag the center point
toward blue almost all the way to the edge.
8 Drag the Saturation slider right until it is around 1.10 to make the blue more vibrant.
You can continue to push the blue as much as you like.
243Lesson 4 Performing Primary Color Corrections
9 Drag the exposure slider left until the sky becomes slightly darker, around -0.80.
NOTE HDR wheels have an advantage over the standard color wheel because
they can adjust the saturation of a color in a specific range of luminance. To
achieve this with a standard color wheel, a secondary tool would have
to be used.
```
The sky now looks much less washed out; however, it still looks a little flat. It needs a
```
wider range of colors.
10 Using the Specular wheel, drag the center point straight up to add a magenta hue to
part of the sky.
TIP The HDR wheels have overlap between them, so adjustments have a
roll-off from one control to another, much like the standard color wheels.
Unlike the standard color wheels, however, these zones can be adjusted
if needed.
244Lesson 4 Performing Primary Color Corrections
11 Click the leftmost wheel icon until the controls show Black, Dark, and Shadow. These
wheels affect the darker areas of the image.
12 Click and drag the exposure setting to the left in the Shadow control to around -0.60 to
get a more defined, darker side of the sand dune. Click and hold on the Highlight
button if you want to see the area you are affecting.
13 Drag the center of the Shadow wheel toward red until the right side of the dune starts
to look redder.
As you can see, the HDR wheels allow you to select more focused areas of dynamic
range, which can be ideal for adjusting clips from cameras that shoot a high dynamic
range. You can get even more precise by isolating areas of an image using secondary
grading controls that we will explore in the next lesson.
You can see that using the primary controls allows you to balance the color in your shots
and start to give them a feel. You will use these controls a lot when you grade, so it is a
good practice to get to know them. If you wish, you can duplicate this timeline and carry on
grading these shots by applying what you have learned so far.
245Lesson 4 Performing Primary Color Corrections
Lesson Review
1 What are the four main color grading controls that would be used for a primary grade?
2 True or False? The Parade video scope can show any tonal and color imbalances
on a clip.
3 How can you stop a timeline from taking Color Management settings from the project?
4 True or False? The Color Match tool uses DaVinci Resolve’s Neural Engine.
5 How many different ranges of luminance can be controlled from the HDR wheels?
246Lesson 4 Performing Primary Color Corrections
Answers
1 Lift, Gamma, Gain, and Offset.
2 True. The parade shows both luminance levels and the levels of the individual
RGB channels, so you can see if there is a color imbalance and if the contrast is not
set correctly.
3 Open the individual timeline settings and uncheck the Use Project Settings option.
4 True. The Neural Engine AI is used to get shot matches as close as possible using an
automatic process.
5 Six ranges of luminance can be controlled from the HDR wheels: Black, Dark, Shadow,
Light, Highlight, and Specular.
Time
This lesson takes approximately
75 minutes to complete.
Goals
Masking Areas with Windows 248
Reversing Selections
with Outside Nodes 253
Using Windows to Adjust Lighting 255
Making Secondary Adjustments
with HSL Curves 262
Making Quick Adjustments
with the Color Warper 267
Using the Chroma Warper 271
Selecting Areas with the Qualifier 275
Combining Qualifiers
and Power Windows 280
Using the Tracker 284
Using the Color Slice Tool 289
Lesson Review 293
Lesson 05
Making Secondary
Adjustments
Primary adjustments work on the
entire image, whereas secondary
adjustments let you isolate and work
on specific parts of an image.
For example, you might want to
change the color of a car from blue to
red without affecting the rest of the
shot, add warmth and saturation to
an actor’s skin, or lower the shine on
someone’s forehead. DaVinci Resolve
features many powerful tools to make
these adjustments.
In this lesson, you will use power
windows, HSL curves, Color Slice,
Color Warper, and the qualifier to
isolate elements based on their color
and shape. You will then use the
tracker to follow your selections so
your color correction follows them
through the shot.
248Lesson 05 Making Secondary Adjustments
Masking Areas with Windows
The first part of making a secondary color correction is to isolate the adjustment on a
node. This allows you to make very specific adjustments without modifying the primary
grade you have already completed.
Using multiple nodes, each containing separate adjustments, you can exercise more
precise control over the order of those adjustments and more easily track and
modify them.
You will continue to use the timeline from the previous lesson.
1 Open DaVinci Resolve 20, if necessary, and then open the Conservation Film Company
project you have been working on.
2 If you have fallen behind at this stage, import the Conservation Primary.drt file from
the Lesson 05 folder. Go to the media pool and in the Timelines bin, right-click and
choose Timelines > Import > AAF / EDL…. If you do not need to do this, proceed
to step 3.
3 Go to the color page and ensure that you are using the Conservation Filming timeline,
which can be found from the menu at the top of the viewer.
249Lesson 05 Making Secondary Adjustments
4 Select thumbnail 08 in the timeline.
This is a panoramic shot of one of the subjects in the desert, but it lacks the punch you
would expect from a shot like this. By working on the foreground separate from the
desert background, we can enhance this beautiful shot to bring out more colors.
5 On the first node, using the Offset master wheel, bring the level down to around
19.55 to ensure that you have no clipped highlights.
6 In the Node Editor, right-click over node 01 and choose Add Node > Add Serial to
add a second node.
7 Right-click over node 02 and choose Node Label, and then name this
node FOREGROUND.
8 In the toolbar center palettes, click the Windows icon.
Power windows, or windows for short, are probably the most heavily used features
when trying to isolate an area for correction. They allow you to specify which area of
the image you want to alter using a drawn shape. The shape can be standard ellipses,
rectangles, polygons, or arbitrary Bézier shapes that you draw with a pen tool.
9 In the list of windows, click the Rectangle button to activate it.
A rectangular window shape appears in the viewer. You can resize and reposition it
so that it is only over the foreground in our picture.
250Lesson 05 Making Secondary Adjustments
10 Drag within the center of the rectangle to move it down so the top sits level with the
top of the shadow in the foreground.
11 Using the white control points on either side of the rectangle, drag to the edges of the
frame until the rectangle covers the entire width of the picture.
TIP Use the middle mouse wheel to zoom out in the viewer so that you can
expand the rectangle outside the frame boundary.
The center handle inside the rectangle is used for rotation, but there are also
transform controls for the window in the center palette. Sometimes, using the controls
in the center palette is easier than dragging in the viewer.
12 On the right side of the windows palette, drag the Rotate number field slightly to the
left, to around 0.85 so the top of the window in the viewer is better aligned with the
foreground shadow.
TIP If you need to expand the rectangle after rotating it, use the Size number
field to expand all sides of the rectangle.
Now that you have your window in place, any color adjustment you make with node 02
selected will be made only within the area covered by the window.
251Lesson 05 Making Secondary Adjustments
13 In the primary controls, lower the Offset master wheel to make the foreground
shadow much darker, around 10.85.
14 Using the Gamma color wheel, drag the center toward blue to give the shadow a
cooler feel.
The outline of the window can obscure the edges of the correction, so it can be
helpful to hide them from time to time.
15 In the viewer’s lower left corner, click the onscreen Overlay button and choose Off
from the dropdown menu that appears.
The top edge appears to match the shadow well, but the edge might be a little too
hard. It needs some roll-off from the shadows into the highlights.
252Lesson 05 Making Secondary Adjustments
16 On the right side of the windows palette, drag the Soft 2 number field slightly to the
right to expand the soft edge along the rectangle’s top. Aim for around 5.00.
17 In the viewer’s lower left corner, click the onscreen Overlay button and choose Power
Window from the dropdown menu that appears to turn the window back on.
TIP Clicking off the Window menu in the middle panel to any other tool, apart
from the Tracker, will also hide the window in the viewer.
```
18 To compare the change you made on node 02, press Command-D (macOS) or Ctrl-D
```
```
(Windows) to disable the node’s adjustments, and then press the keyboard shortcut
```
again to enable it.
```
Before window correction (left) and after window correction (right).
```
Windows are the perfect solution when you have a clearly defined area you want to work
within. This simple color adjustment has made a big impact by using a window to limit it to
the picture’s top half.
253Lesson 05 Making Secondary Adjustments
Reversing Selections
with Outside Nodes
Often, you will want to switch your attention to the area outside of your window.
For example, now that the sky looks dramatic in this shot, you might want to adjust the
grass area. For this purpose, you can use an outside node, which takes the mask created
by the window and inverts the selection.
1 With node 02 selected in the Node Editor, right-click it and choose Add Node >
```
Add Outside or press Option-O (macOS) or Alt-O (Windows).
```
254Lesson 05 Making Secondary Adjustments
A third node is now present in the Node Editor. As with previous nodes you’ve created,
it will connect with the preceding node via the green RGB input/output circles.
However, this time you’ll see a new connection: the key input/output blue triangles.
The key is the portion of the image that you isolated using the window tool. When you
create an outside node, it receives the key from the previous node and automatically
inverts it.
2 With node 03 selected, right-click and choose Node Label, and then name the node
BACKGROUND.
To more clearly visualize the area you are adjusting, you can briefly enable the viewer’s
Highlight mode.
3 In the viewer’s upper left corner, click the Highlight button.
The Highlight button shows the area you will be changing and displays gray pixels over
the area that will be protected from your adjustments.
4 Using the primary controls, drag the Contrast control right to around 1.200 to
lengthen the shadows in the desert.
5 Using the Gamma control wheel, drag the center toward orange until the desert starts
to look warmer.
6 Click the Highlight button again to disable the Highlight mode.
The ability to reuse key data is a beneficial component of node-based workflows. It
speeds up the grading process by requiring you to create a single mask and reuse
it multiple times.
255Lesson 05 Making Secondary Adjustments
Using Windows to Adjust Lighting
In addition to being able to isolate certain regions to grade, you can use windows to
change the light in a shot, and without your audience noticing, pull their attention to
something that you, as the colorist, want them to focus on.
1 Select clip 03 in the timeline.
We balanced this shot in the previous lesson, and while we neutralized the yellow cast
on the shot, the clip itself looks very flat and almost gray. Also, there is a lot of
background behind the cheetah.
So at this stage, you will create more definitive lighting in the shot so the audience will
focus more on the subject, and the shot’s lighting will not look so flat.
2 Add a second node by right-clicking node 01 and choosing Add Serial or by pressing
```
Option-S (macOS) or Alt-S (Windows) on the keyboard.
```
3 In the toolbar center palettes, click the Windows icon and select the Curve tool from
the Window options. The mouse pointer will look like a pen, and the tool will allow you
to draw the window shape you want.
You will need to zoom out of the viewer slightly to make sure the top and bottom
edges of the window are not in the shot.
256Lesson 05 Making Secondary Adjustments
4 Place the mouse pointer over the viewer window and, using the mouse scroll wheel,
scroll out to reveal the edge of the image or click the percentage button in the top
right corner and choose a value lower than the current one.
NOTE The percentage value of an image fitted to the viewer will differ from
system to system since it is dependent on the resolution of the screen you
are using.
```
5 You can also press Command-minus (macOS) or Ctrl-minus (Windows) to zoom out of
```
the image. Each time you press the minus key, the image will zoom out further.
6 Click and add the first point about a third of the way in from the right of the frame but
make sure the point is outside the frame.
257Lesson 05 Making Secondary Adjustments
```
TIP Don’t worry too much about the points when you are drawing a window;
```
their positions can be changed later, and points can also be added and deleted
from a shape.
7 Add a second point approximately halfway down the left side of the frame, again
making sure that the point is outside the frame.
8 Add another three points as shown in the image below.
258Lesson 05 Making Secondary Adjustments
9 After adding the fifth point, position the mouse pointer over the first point you created
and click the point. The shape will close.
At this stage, if you want to adjust any of the points, you can simply select and drag
them to a new position as needed. Middle mouse clicking a point will delete it. You can
click anywhere on the shape path to add a point.
Since light is never that linear, you will add a few points to the window you created to
give the shape a more customized look that appears more like natural light.
10 With the Curve tool selected, add a point just above the cheetah’s head.
259Lesson 05 Making Secondary Adjustments
11 Drag the point up slightly and then drag to lengthen the Bézier handles to create a
smooth curve.
12 Add another point halfway down the other vertical side of the shape and drag it down
diagonally until it lines up with the first point you added. Again, lengthen the Bézier
handles so that the shape has a nice curve to it.
Now you’ll want to change the color inside the window to give it a late afternoon feel.
13 Go to the HDR wheels you used in the previous lesson.
260Lesson 05 Making Secondary Adjustments
14 In the Offset control, drag the temperature slider up toward orange until it can go
no further.
TIP Using the HDR wheels to add color to a shot can be beneficial since that
will avoid adding color to the brightest highlights and darkest shadows, which
should have no color in them naturally.
15 Drag the Contrast control in the HDR wheels to the right until it hits
approximately 1.050.
16 Drag the Pivot all the way to the right until it can go no further. The value
should be 6.000.
We’ve now darkened inside our window to give the impression of longer shadows as if
there is a low-lying sun.
17 With node 02 selected in the Node Editor, right-click it and choose Add Node > Add
```
Outside or press Option-O (macOS) or Alt-O (Windows).
```
261Lesson 05 Making Secondary Adjustments
18 With the new node 03 selected, drag the Exposure in the Global control to the left
until it reads approximately -4.20 or the area outside our created window looks
suitably dark.
The area now looks darker but perhaps a little too cold. We need to add a bit of
warmth to the shadows.
19 Click and drag the Global temperature slider up slightly so the shadows lose the
blue tint.
```
You now have the lighting for the look you want; however, it looks slightly ridiculous
```
since the window itself is so defined.
20 Select node 02 again.
21 Click the onscreen Overlay button to turn off the window in the viewer.
22 On the right side of the Window panel, click and drag the Soft 1 value right until the
window softens enough to look natural.
262Lesson 05 Making Secondary Adjustments
```
23 To compare the change you made on node 02, press Command-D (macOS) or Ctrl-D
```
```
(Windows) to disable the node’s adjustments, and then press the keyboard shortcut
```
again to enable it.
You now have a shot for which the eyes are drawn more to the subject, and the lighting
is much more interesting and reflective of the environment than in the original shot. If
you toggle the grade on and off, you will notice your eyes are drawn more toward the
subject’s face when the window is on. To see this more clearly, you might want to
switch to full-screen mode.
```
24 Press Command-F (macOS) or Ctrl-F (Windows) to expand the viewer to full screen.
```
```
Then press Command-D (macOS) or Ctrl-D (Windows) to toggle the window node on
```
and off to see the changes.
Making Secondary Adjustments
with HSL Curves
Windows come in handy when you have well-defined simple areas that you want to adjust.
However, in cases where the area is less defined, the shape is too complicated, or you are
```
trying to select a particular color, HSL (Hue, Saturation, Luminance) curves may be a more
```
appropriate tool.
1 On the color page, select clip 04.
263Lesson 05 Making Secondary Adjustments
This clip already has a nice balance to it, but the blue sky seems washed out. Also, the
orange of the desert could use a little more warmth. Making the blue sky more vivid
and the orange in the image more vibrant will make this a more striking shot.
2 Right-click over node 01 and label it ORANGE SATURATION.
The easiest technique to use when you have a simple secondary color adjustment is
to use the HSL curves. HSL curves are located in the custom curves palette.
3 In the toolbar, click the curves palette.
4 In the upper right corner of the curves palette, click the third button from the left,
which is the Hue vs Sat curve.
The buttons in the top right corner of the window give you access to different curves.
Each curve displays the property that will be selected versus how that property will be
adjusted. In this case, you will use Hue vs Sat, which will select a hue from the image
and adjust that hue’s saturation, pushing more of the selected color into the image.
```
So, in this case, the color of the desert is correct; you just want more of it.
```
5 In the viewer, click a point in the desert in the bottom left of the image.
Clicking in the viewer adds three points to the line in the graph. The middle point is the
precise hue shade you selected in the viewer. The outer two points limit the range of
green hue that will be adjusted.
264Lesson 05 Making Secondary Adjustments
6 Drag the middle point in the graph up to start making the desert a more vivid orange.
```
There is a range of orange in the image, including on our subject; however, as we are
```
warming the orange hue, it gives the subject a natural warm look in keeping with the
image. Now you need to adjust the sky. We know the blue hue must be adjusted, so we
```
could select it; however, you can see in the curves window that there is a natural spike
```
on the histogram showing where the blue sits.
Since we can see where the blue sits, we can just manually add a point to the blue
section of the curve.
265Lesson 05 Making Secondary Adjustments
7 With node 01 selected in the Node Editor, right-click it and choose Add Node > Add
```
Outside or press Option-O (macOS) or Alt-O (Windows).
```
8 Right-click over node 02 and label it SKY SATURATION.
9 In the same Hue vs Sat curve, select the blue channel from the color menu in the
bottom left corner of the curves window. Three points will automatically appear on
the curve.
Drag the blue point directly upward until the sky looks bluer.
TIP If you want to move a point up and down in the curves and make sure its
position doesn’t move left or right, you can click and drag on the Saturation
parameter, which will only move the point vertically.
```
Before the saturation shift (left) and after the saturation shift (right).
```
Now we want the sky to have a little more magenta in it so it looks a little more like the
sky in clip 07 that we adjusted in the previous lesson with the HDR wheels.
266Lesson 05 Making Secondary Adjustments
10 With node 01 selected in the Node Editor, right-click it and choose Add Node > Add
```
Serial or press Option-S (macOS) or Alt-S (Windows).
```
11 Label node 03 SKY COLOR.
12 Go into the curves window and select the Hue vs Hue curve.
13 Select the blue channel from the color menu as you did before.
14 Drag the middle point of the curve down ever so slightly so the sky looks a little
more magenta.
As you can see, curves allow you to quickly adjust specific areas of hue, saturation, and
luminance. As you have already seen, however, Davinci Resolve has a deep tool set,
and there are many different ways of adjusting specific areas of color.
267Lesson 05 Making Secondary Adjustments
Making Quick Adjustments
with the Color Warper
The computer mathematics behind the HSL curves create a very smooth and natural
```
result; however, they only allow the adjustment of one color parameter at a time. In the
```
previous lesson, one curve allowed you to adjust the saturation of a color and then a
separate curve allowed the adjustment of the hue.
The Color Warper allows the adjustment of two parameters at the same time using a grid
of adjustable points. For example, you can change not only the saturation of a color but
the color itself by adjusting the hue at the same time—essentially the process we just did
but with two sets of curves. This makes the process of manipulating color a quick and
intuitive process when using the Color Warper.
1 Select clip 14 in the timeline.
Here we have a clip that essentially has just orange and blue in it, so we can
manipulate these colors quickly and easily with the Color Warper.
2 In the toolbar center palettes, click the Color Warper icon.
The Color Warper will default to the Chroma Warper, but we need to change this to
adjust the hue and saturation in the image.
3 In the Color Warper tool, click in the top right corner of the window and choose
Hue – Saturation.
268Lesson 05 Making Secondary Adjustments
The Color Warper appears in the middle window and is split into six separate
segments. Each section divider will have several points that can be dragged to change
the color and saturation in the image.
4 To make the Warper a little more precise, change the number of segments from 6 to 8.
5 Position the mouse pointer over the viewer, and it will default to the Qualifier tool.
Place it over the sandy area toward the bottom left corner of the frame.
269Lesson 05 Making Secondary Adjustments
6 Select the sandy area in the viewer, and you will notice that it selects a control point in
the Color Warper.
7 With the qualifier still over the sandy area in the viewer, click and drag left and upward
until the area looks more saturated and orange, and the Warper looks similar to the
image below.
By dragging a control point further away from the center of the Warper, more
saturation will be added to a selected area. Dragging the point into a hue in the
Warper changes the color of the selection. As you can see, both of these adjustments
can be made simultaneously.
You now want to make a slightly more precise selection for the sky. Rather than simply
dragging along the image, you’ll use the control points in the Color Warper itself.
8 Add a second node by right-clicking node 02 and choosing Add Serial, or pressing
```
Option-S (macOS) or Alt-S (Windows) on the keyboard.
```
9 Make sure the Color Warper window is still visible.
270Lesson 05 Making Secondary Adjustments
10 Select any part of the sky, and a point will appear just to the right of center toward the
blue axis.
11 Drag the control point right toward blue. The sky might start to go a little magenta, so
drag it down slightly until the sky looks blue.
Both the HSL curves and Color Warper can create very natural results that are much
trickier to get using other methods. However, the controls are limited to one adjustment
for HSL curves and two adjustments for the Color Warper.
271Lesson 05 Making Secondary Adjustments
Using the Chroma Warper
The Chroma Warper works very similarly to the Color Warper in that it is designed to make
smooth and accurate changes between color ranges. The main difference between the
two is that the Chroma Warper uses strokes on a chromaticity diagram rather than a mesh,
giving you a good idea of how you are adjusting the color output.
1 Select clip 09 in the timeline and select the Color Warper tool from the middle window.
It will default to the Chroma Warper.
2 Click the Scope options in the top right corner of the window and choose Scopes >
Output. This will allow you to see the changes happening to the color in the
chromaticity display.
You can see in the Chroma Warper that chroma indicators point very much toward
blue and red, as they are the two most prominent colors in the shot.
272Lesson 05 Making Secondary Adjustments
3 Using the Eyedropper tool, select the blue sky in the top left corner of the image,
which will apply an adjustment point in the Chroma Warper.
4 Carefully click the added point and drag it toward blue in the Chroma Warper. As the
sky turns more blue in the image, you should see a second point appear with an arrow
between the two. This shows us where the original sampled color was and where we
have adjusted it to.
TIP To delete a point, simply right-click on the mouse, and the point will
disappear. The selection must be done with the same tool that created
the point.
Now we want to push a little more warmth into the desert but keep the red dress its
same distinctive color and not change it with the rest of the shot.
273Lesson 05 Making Secondary Adjustments
5 In the Chroma Warper tool, select the Add Pin Point tool.
6 Using the Eyedropper again, click the main body of the red dress in the image, and a
pin point will be added. The pin point, as the name suggests, pins a selected hue in
place in the Chroma Warper so it is not affected by any other adjustments.
7 Select the Add Stroke Normal Mode tool in the Chroma Warper.
8 Select the desert floor to the left of the subject, and another point will appear.
274Lesson 05 Making Secondary Adjustments
9 Click and drag the point toward orange to add warmth to the desert.
You will notice that as the dress color is pinned, it does not change with the rest of the
image. You might feel that the darker hills in the background have had a little too much
orange hue pushed into them, but this can be adjusted.
10 Click and drag the Tonal Range Low slider until it reads around 0.170 or until the hills in
the background have a slightly more blueish hue. The Tonal Range Low affects the
darker areas of the selected hue, leaving the lighter areas unchanged.
The Chroma Warper is an effective way of manipulating numerous hues easily within one
tool. The adjustments also ensure that the roll-off between colors is smooth and can be
adjusted accordingly, with the ability to pin certain colors so they remain unaffected. So,
what happens when you want something even more precise—a tool that can use three
adjustments together to identify an area of an image? Let’s look at a more advanced
method of selection but also one that takes a bit more time to master.
NOTE The Chroma Warper and standard Color Warper cannot be used on the
same node. If you want to combine the two, they must be used on separate nodes.
275Lesson 05 Making Secondary Adjustments
Selecting Areas with the Qualifier
The qualifier palette is another method of isolating a color for secondary color corrections.
Compared to the HSL curves or Color Warper, the qualifier is a more sophisticated palette
that includes several ways to select a color using hue, luminance, and saturation. This
detailed level of control enables you to get a clean isolation, or matte, of objects even when
other elements in the shot are of a similar color.
TIP Qualifiers are used only as a method of creating a matte. They are not
color-grading tools themselves, and you only start to see their effects when you
begin adjustments in the color-grading palettes.
1 Select thumbnail 10 in the timeline.
This is the interview shot we adjusted in an earlier lesson, but it now needs refining.
2 Add a second node by right-clicking node 01 and choosing Add Serial or by pressing
```
Option-S (macOS) or Alt-S (Windows) on the keyboard.
```
The qualifier is extremely useful for isolating specific colors since the controls narrow
down the selection using hue, saturation, and luminance. You begin using the qualifier
much like you would a chroma keyer. Using an Eyedropper, you click over an area of
interest. The area you select is what you want to be adjusted. In this case, the
producers feel Sean’s blue shirt doesn’t match the rest of the shot and would prefer it
to be green.
There are several different types of qualifiers. In this case, you’ll use the 3D qualifier, so
you can simply drag on your selection.
3 In the middle window toolbar, click the Qualifier icon.
4 In the top right corner of the Qualifier window, click on the fourth button, which is the
3D Qualifier tool.
276Lesson 05 Making Secondary Adjustments
5 In the viewer, click and drag from just above the left of the blue shirt. When you draw,
the image will turn black and white. The white area will be your selection, or key, and
the black area will be excluded from the selection. Continue to draw the line until the
shirt is all white.
```
TIP At this stage, you are not trying to achieve a perfect selection; you just
```
want to ensure that you have included a large portion of the area you are
trying to adjust in your qualifier.
Once you have finished dragging the selection, the viewer will return to normal but will
show a blue line that shows the selection that you drew in the viewer.
Your next step will be to refine and clean up your selection. To do so, you must first
change the viewer’s output to show your selection.
277Lesson 05 Making Secondary Adjustments
6 In the upper left corner of the viewer, click the Highlight icon or press Shift-H.
You are now seeing the pixels you selected against gray pixels that are not selected.
The goal is to make as much of the image gray while the shirt remains its natural color.
Our selection is pretty good but it might just need some cleaning up.
7 With the Highlight tool still turned on, click the Black And White button at the top left
corner of the viewer and your image will go back to the black-and-white highlight.
You want to smooth out this noise as much as possible so the selection goes unnoticed
by an audience.
NOTE The quality of the selection when using the Qualifier tool can depend
on your footage as well as the tool itself. When using heavily compressed files,
such as the H.264 codec, the qualifier does not have much color information
to work with, leading to uneven selections. Using higher-end files such as
Blackmagic RAW will get you more refined selections since there is much more
color information to work with and therefore select.
8 Zoom in to the right side of the image.
278Lesson 05 Making Secondary Adjustments
9 Play the clip, and you might see slight areas of noise in the shirt that show up as slight
specks of black.
10 In the Matte Finesse tools on the right side of the Qualifier window, click and drag right
on the Clean White parameter until it reaches approximately 0.7. This cleans up the
noise that was in our selection, and the shirt now looks solid white.
TIP Don’t go too far with the clean and blur controls or your qualified area can
begin to bleed back into the non-selected area.
11 Turn off the highlight by clicking the Highlight button at the top left corner of
the viewer.
279Lesson 05 Making Secondary Adjustments
12 Press Z on the keyboard to make sure the image is fitted back to the window.
13 To prevent the blue path from being distracting in the Qualifier window, turn off the
Show Paths option.
14 In the primary controls in the left window, click and drag the Hue control to the right
and change the color of Sean’s shirt from blue to almost olive.
15 Drag the Offset master wheel to the left to drop the brightness of the shirt.
The shirt still has a little too much color in it.
16 Click and drag the Sat control to the left until it sits around 30 and the shirt looks
less vibrant.
Using the qualifier, you have used the hue, saturation, and luminance information in
the image to isolate a very specific area. Using the qualifier in this way allows you to
change the color of objects or dial specific hues back into a certain area or simply
make selections brighter or darker. The qualifier very precisely controls what you
select in an image. You can see from our image, however, that while the shirt looks
correct, our adjustments have had a nasty effect on the rest of the shot. However,
that can be fixed.
280Lesson 05 Making Secondary Adjustments
Combining Qualifiers
and Power Windows
You can refine an area of the image you want to modify even more precisely by using the
qualifier and power windows together. Often, an image will have several instances of a
hue that you are trying to manipulate. Instead of focusing your efforts on cleaning up the
```
selection in the qualifier palette (and likely compromising the quality of the key),
```
sometimes the best option is to use a power window to limit which part of the frame the
qualifier operates on.
1 If it is not already selected, select clip 10.
2 Make sure you still have node 02 selected. The image does not look great because the
results of our qualifier are spilling into the rest of the shot.
3 In the middle window, select the Window button.
4 Select the curve window from the menu.
281Lesson 05 Making Secondary Adjustments
5 Zoom out of the image slightly by either scrolling the middle mouse wheel or pressing
```
Command-minus (macOS) or Ctrl-minus (Windows).
```
The qualifier area may be a little difficult to see in the current view, so you can change
it to see the qualified area in more detail.
6 In the top right corner of the viewer, turn the Highlight button back on.
It will still be in the black-and-white setting, so click the default Highlight button in the
highlight options menu in the top left corner of the viewer.
You are looking to isolate the shirt from the rest of the image.
7 Click and add a first control point in the viewer just offscreen under the left sleeve.
8 Continue to add control points and draw a rough shape around the shirt. Remember
that you can always add points once the shape has closed.
282Lesson 05 Making Secondary Adjustments
TIP Remember that you can delete a point by clicking the middle mouse
button. You can also turn a linear point into a smooth point by holding down
```
Command (macOS) or Ctrl (Windows) and dragging the point. Double-clicking
```
a point will make it linear.
9 Turn off the highlight by clicking the Highlight icon or pressing Shift-H.
10 Turn off the Window by clicking the onscreen Overlay button off.
You should now have isolated the shirt from the rest of the image. However, a little
cleanup is still needed around Sean’s neck area and just off the left shoulder since we
still have some noise from the qualifier.
11 Go back into the Qualifier tool and select the Picker Subtract tool.
12 Click the Auto Black and White Highlight to stop the viewer from going into
highlight mode.
13 Turn on the Show Paths option.
Picker Subtract
Show Paths
Auto Black and White
You now have the ability to remove areas that were originally qualified.
283Lesson 05 Making Secondary Adjustments
14 Zoom in to the image around Sean’s neck on the right side.
15 Click and drag from the top of the noise down, getting as close to the shirt collar as
possible without touching it. You will see a red line appear as a selection is removed
from the original qualifier.
If at any point you make a mistake, in the Qualifier window, simply click the trash can
icon in the Strokes panel to delete the stroke.
16 Click and drag another stroke over the left shoulder to remove the last of the
qualifications that sit outside the shirt.
As you can now see, the window is working with the qualifier to remove selected areas
outside the power window.
Combining the qualifier with a window has allowed you to quickly make a clean selection
based on the element’s hue while just as quickly excluding interfering elements from your
selection. Using both tools meant that you didn’t have to draw an overly precise power
window or endlessly tweak the qualifier. Combining the two tools has saved time and
resulted in the cleanest key.
284Lesson 05 Making Secondary Adjustments
Using the Tracker
We want to isolate the subject’s face in the shot we just worked on. Using the techniques
we explored in the previous section, we can isolate the face and limit the effect of the
isolation with a power window. The slight issue you will have, though, is that the face
moves and therefore we would need the power window to move with it as well.
1 Add a second node by right-clicking node 02 and choosing Add Serial, or pressing
```
Option-S (macOS) or Alt-S (Windows) on the keyboard.
```
2 Select the Qualifier tool again and select the 3D Qualifier.
3 Click just below Sean’s right eye and click and drag down on the face to halfway down
the neck and drag up toward the other side of the neck to isolate the face. The path
should look like a letter J.
4 Click the Highlight button at the top left corner of the view or press Shift-H on
the keyboard.
5 Go into the Window menu and select a circular window.
285Lesson 05 Making Secondary Adjustments
6 Click and drag the center of the window until it sits level with the subject’s chin.
7 Click and drag either the left or right side control point to narrow the window to focus
more on the subject’s face.
8 Click and drag the top control point just to ensure that you get the subject’s ear in.
9 Turn off the window by clicking the onscreen Overlay button to off.
```
TIP You can press Shift-` (grave accent) to hide the onscreen overlays.
```
```
You now have a pretty good selection; however, the qualifier needs tidying up again.
```
286Lesson 05 Making Secondary Adjustments
10 Select the qualifier and click and drag the Clean Black parameter to the right to around
5 or until the additional noise that we had in the shirt disappears.
11 Go back into the Qualifier window and click the Picker Add button. Drag over the lips to
ensure they are part of the selection.
We want to make the subject’s skin appear warmer, but a good way to do this is to cool
the background.
As Sean now moves his head, the window does not move with him, so we need the
window to track his movement.
12 In the toolbar center palettes, select the Tracker tool.
13 Ensure that the playhead is over the first frame and then click the Track
Forward button.
287Lesson 05 Making Secondary Adjustments
The window will move along with Sean’s face, ensuring the window still isolates the skin
tone you qualified.
14 With node 03 selected in the Node Editor, right-click it and choose Add Node > Add
```
Outside or press Option-O (macOS) or Alt-O (Windows).
```
15 Drag the Gamma color control point toward blue to make the background look a
little colder.
16 Drag the saturation control to the left and drop the saturation of the background
slightly to around 40 to ensure that it is not too blue.
As you can now see, Sean’s skin looks warmer because you changed the background
to look cooler, tricking the eye into thinking there has been a change to our qualified
area when there actually hasn’t.
TIP If you want the skin tone to look still warmer, go back to the previous
node and, using the Gamma control, add more orange to the shot. There is
also a video scope called the Vectorscope that can help you when grading skin
tones. For more information, refer to the book The Colorist’s Guide to
DaVinci Resolve 20, by Daria Fissoun.
There is one more adjustment required for this shot. Since the eyes are typically the
focal point for most shots of people, we can further enhance this shot by simulating
the eyes to look sharper, using a window and tracking.
17 Click the Onscreen Overlay button in the viewer’s lower left and choose Window from
the dropdown menu to show the window outline.
18 Make sure you are on the first frame of the shot.
288Lesson 05 Making Secondary Adjustments
19 Add another serial node in the way you used previously.
20 In the central palettes, click the Windows icon.
We’ll again use a circle window to focus on his eyes.
21 In the windows palette, click the circle window.
22 In the viewer, drag the circle over his eyes, so the center is on the bridge of his nose.
23 Use the white top, bottom, and side handles to create a smaller, more oval shape
covering his eyes. Use the anchor point handle to align the window with the angle
of the eyes.
24 Use the Soft 1 control in the windows palette to increase the softness to around 7.5.
25 Select the tracker palette.
26 Click the track Forward button.
Now we’ll use this window to sharpen the eyes.
27 In the primary controls, drag the Mid/Detail to the right to around 75.00. This is often
referred to as local contrast or clarity to give the eyes a sharper appearance.
NOTE Midtone detail is not the same as sharpening. It simply adjusts contrast
in the midtone regions of the image, giving the impression that the image is
being sharpened.
289Lesson 05 Making Secondary Adjustments
28 Click the Onscreen Overlay button in the viewer’s lower left and choose Off from the
dropdown menu or press Shift-` to hide the window outline in the viewer.
```
29 Press Command-D (macOS) or Ctrl-D (Windows) to disable the Eyes node, and then
```
press the keyboard command again to enable it and compare the adjustment.
```
Before eye light (left) and after eye light (right).
```
The tracker is a commonly used tool, most often when tracking windows for secondary
color corrections. As simple as it is to use, it is a very advanced palette that can handle
many tasks.
Using the Color Slice Tool
The final tool we will look at is one of the newest additions to the color page, and that is the
Color Slice. Imagine the range of colors you work with in an image as a 3D shape sliced into
segments for each hue. The Color Slice allows you to control each of the slices, giving you
the ability to adjust the hue, saturation, and density of the color involved. It also has a
helpful skin-tone control, so in some cases you don’t have to even qualify a skin tone to
make an adjustment.
1 Select clip 21 in the timeline.
2 Select the Color Slice tool in the middle window.
As you can see, the tool is split into the six color areas you find in a color wheel and
also the skin control. In this shot, the skin tone looks a little flat and gray, so we will
enhance the skin tone.
290Lesson 05 Making Secondary Adjustments
3 Click and drag the Saturation slider on the skin tone up to around 1.50 to add more
saturation to our subject’s face.
Density
Saturation
4 Drag the Density slider down to around -0.50 to lift the skin tone area.
NOTE The Color Slice tool works in a slightly different way than the other color
tools. It works in a subtractive way, meaning that when adjusting the
saturation of colors, it does not make the colors unnaturally bright. Therefore,
they do not need luminance adjustments. If luminance needs to be tweaked,
the Density control can be used to adjust the luminance of more saturated
colors, which emulates the subtractive process.
The skin tone looks OK. However, there appears to be blue noise in the image.
This could be because the area that the skin tone is adjusting does not cover all the
hues of the face.
291Lesson 05 Making Secondary Adjustments
5 Click and hold the Highlight button at the top left corner of the skin tone control to see
the area you are affecting.
6 Repeat the process using the Highlight button over the red control. As you can see,
some of the face spills into the red channel.
7 Drag the red saturation up to around 1.50 and the density down to around -0.60 to
make the skin color look a little smoother.
8 With node 01 selected in the Node Editor, right-click it and choose Add Node > Add
```
Serial or press Option-S (macOS) or Alt-S (Windows).
```
9 Using the yellow control, adjust the saturation and density until the trees look
suitably green.
292Lesson 05 Making Secondary Adjustments
10 Add another node and adjust the blue and cyan saturation until the sky looks a more
even blue.
Original shot and completed grade.
NOTE When using the Highlight button, you will notice that the selections
look quite pixelated and not as refined a selection as you have been using.
This is due to the fact that the clip has been shot in an H.264 format, which in
this case is heavily compressed. Formats such as ProRes store much more
information and therefore are much better to work with when doing
secondary color correction. The better the recording format, the cleaner your
selections can be. Formats such as Blackmagic RAW are ideal for this since
they use a large color gamut, and the larger the gamut, the easier it is to
isolate individual colors.
As you have seen, not only can you work with color in the whole image, but you can isolate
areas of color in several different ways to get the ideal look you want.
293Lesson 05 Making Secondary Adjustments
Lesson Review
1 What happens when you click the Highlight button in the upper left corner of the
color page viewer?
2 True or False? Midtone detail sharpens the image.
3 In the color page, what does an outside node do?
4 What are the three ways of adding a point to a Hue vs Sat curve?
5 The Color Slice has seven control areas, including red, yellow, green, cyan, blue,
magenta, and what other control?
294Lesson 05 Making Secondary Adjustments
Answers
1 Clicking the Highlight button above the color page viewer displays pixels that are
selected by a qualifier or power window. These selected areas are displayed with their
normal colors and will be affected by any color adjustment. Non-selected areas are
displayed as gray pixels and will not be affected by color adjustments.
2 False. Midtone detail adjusts the contrast in certain midtones, giving the impression
that the image looks sharper.
3 The outside node inherits the alpha channel from the node before it and inverts
the selection.
4 Select a color using the qualifier in the viewer, click the curve to manually add a point,
or click the color control to add a point on a specific hue.
5 The additional control is skin tone, which allows you to quickly adjust skin tones
without the need to qualify it.
Time
This lesson takes approximately
75 minutes to complete.
Goals
Applying Resolve FX
in the Color Page 296
Identifying Ungraded Clips 300
Copying Grades 303
Working with Stills 306
Importing and Exporting Grades 317
Working with LUTs 321
Making Creative Decisions 329
Lesson Review 333
Lesson 6
Finishing and
Management
Once you have achieved the
corrections you require, you might
want to complete the grade by
applying a specific look or effect. You
must also be able to find ungraded
clips, copy grades, match grades,
save them for later, or put them into a
Lookup table.
In this lesson, you will learn how to
apply effects, easily identify ungraded
clips, copy and paste grades, save
grades using stills, match clips to stills,
use and save LUTs, and preview them
for creative decision-making.
296Lesson 6 Finishing and Management
Applying Resolve FX
in the Color Page
Just like the cut, edit, and Fusion pages, the color page includes many high-quality
Resolve FX, such as blurs, glows, film grain, and lens flares. They can be applied to the
entire image, or you can combine them with windows on the color page to isolate the
effect to one area of the frame. You’ll start by applying an effect to the whole image.
You will continue using the timeline you used in the previous chapter.
1 Select clip 07 in the timeline.
2 In the Node Editor, right-click over node 02 and choose Add Node > Add Serial.
3 In the top right corner of the interface, click the Effects button to show the Resolve FX
you can utilize in the color page.
This shot could use more of the feel of the sun shining, so you need a lighting effect
that conveys this.
4 Scroll down the effects palette until you reach the Resolve FX Light group. Under this
section, you will find the Light Rays effect.
TIP Some Resolve FX are available only in DaVinci Resolve Studio. However, to
test their functionality, you can apply them in the free version with a watermark.
297Lesson 6 Finishing and Management
5 Drag and drop the Light Rays effect onto node 03.
Clip with Light Rays effect applied.
TIP If you cannot see node 03 because of the Effects tab, click and drag with
the middle mouse button anywhere in the node window to reframe the node tree.
You will now see the effect added to the node and applied to the shot. The Effects
menu switches to the Settings tab to allow you to control the effect on the node.
The effect is very bright and definitely not what we want.
6 In the Source Of Rays menu, choose Edges.
298Lesson 6 Finishing and Management
7 Drag the Source Threshold down to around 0.073 so the light rays start to appear
more vibrant again.
8 Under the Position menu, click Ray Directions and change the selection to At An Angle.
9 Under the Appearance menu, click and drag the Length to around 0.165 or until you
feel the light rays are long enough in your image.
10 Soften them slightly and change the color to orange.
299Lesson 6 Finishing and Management
You should now have an image that looks like the one below, in which the light rays to
the left of our subject look good but to the right they still seem a bit too much.
You can limit the effect by using them in conjunction with power windows as you did
with the qualifier.
Click the Windows button in the middle window and select the gradient power window.
TIP You can apply one Resolve FX per node. To remove a Resolve FX from a
node, right-click the node and choose Remove OFX Plug-In.
300Lesson 6 Finishing and Management
11 In the viewer, grab the arrowhead at the bottom of the gradient control and rotate the
window around so the arrow points to the right, limiting the effect.
Now the effect is limited to just the windowed area and appears to be sunlight shining
in for the light source on the left of the frame.
Understanding how to use tools such as the qualifiers, windows, effects, and the tracker
palette enables you to perform secondary color grading with substantial control over your
image’s final look. However, it is only when you combine these tools that their true
potential is unlocked.
Identifying Ungraded Clips
When grading your timeline, it’s very important to ensure that all the clips are graded. An
ungraded clip can be quite obvious, especially in a scene that has a specific look applied,
meaning the ungraded clip will surely be noticed by the audience. It is quite possible that a
timeline can run into hundreds of shots, depending on the project, and you may also have
shots drop into the project after you have started grading. Therefore, keeping track of
every single shot can be difficult.
The color page contains tools that can help you identify shots that are not graded.
301Lesson 6 Finishing and Management
1 In the top right corner of the interface, click the Clips dropdown menu.
A menu will appear showing you all the clip filtering options.
TIP The Clips filter can identify shots in a number of different ways.
For example, you can use metadata such as keywords that you used
earlier in this guide, whether or not a clip has a Resolve FX applied, or whether
clips have different frame rates. There are numerous options.
2 In the menu, choose Ungraded Clips.
You will notice fewer thumbnails in the interface. You are now looking at all the clips
within the timeline that do not have any grades.
TIP If your thumbnails have disappeared, it may be due to clicking on the
Clips button rather than the dropdown menu arrow. If this is the case, click the
button again and then click the menu arrow.
302Lesson 6 Finishing and Management
Even though this identifies the clips, working in this view may be less than ideal if you
want to preview the entire timeline or match ungraded shots to graded shots. In this
case, you can color the clips to identify ungraded files in the complete timeline.
3 In the thumbnail view, select clip 01 in the timeline.
4 Hold down the Shift key on the keyboard and select the last thumbnail in the timeline.
A red border should appear around the selected thumbnails.
5 With the mouse pointer over any one of the selected thumbnails, right-click and
choose Flags > Blue. Each thumbnail will now have a blue flag in the top left corner.
303Lesson 6 Finishing and Management
6 Click the dropdown menu arrow again of the Clips button and from the menu choose
All Clips.
You will now have the full timeline back with all the ungraded clips with a blue flag on
them, so it is now easy to see which clips are graded and which are ungraded.
Copying Grades
If a shot has been used on multiple occasions in the same timeline—for example, an edited
interview will have numerous sections of one clip of either the interviewer or interviewee—
you don’t want to spend time grading each clip from scratch since the grade would be
pretty much the same. Likewise, if you have multiple shots from a similar environment, the
chances are the grades for the shots will be very similar.
With this being the case, you can easily copy and paste grades between clips.
1 Select clip 03 in the timeline. This is the clip we graded in Lesson 5 by adding a power
window to it.
```
2 From the Edit menu, choose Copy or press Command-C (macOS) or Ctrl-C (Windows)
```
to copy the grade.
We have a clip next to it that also looks quite flat and gray, much like our original shot,
so maybe the grade will be suitable for this shot as well.
```
3 Select clip 02 and choose Edit > Paste or Command-V (macOS) or Ctrl-V (Windows) to
```
paste the grade.
All the nodes will be copied onto the new clip. The grade now pasted on looks good on
our new shot, giving it some much needed contrast. However, the window is not quite
in the correct place.
NOTE The default setting for pasting grades is to copy all the nodes from one
clip to another. The setting can be adjusted to copy only the selected node in a
grade. This can be done from the Davinci Resolve User Settings menu by
choosing the option “Always perform copy paste on selected nodes.”
304Lesson 6 Finishing and Management
4 Select node 02 and then click the Window button in the middle window to show the
power window on the node.
5 Click the control point that sits in the bottom right corner of the window and drag it
right so part of the antelope is no longer in shadow.
6 Click back on the curves window to hide the power window from the viewer.
There is a quicker way of copying and pasting grades between shots.
7 Select clip 01 in the timeline. Again, this is another shot that looks a little flat.
8 Place the mouse pointer over clip 02 and click with the middle mouse button. The
complete grade will be copied to clip 01.
You now have several clips that have grades applied but are still flagged blue, which
identifies them as being ungraded, so this needs to be changed.
305Lesson 6 Finishing and Management
```
9 Select clip 01, hold down the Command (macOS) or Ctrl (Windows) key and select
```
clip 02. The red border should appear around the clips.
10 Right-click over any of the selected clips and choose Flags > Clear All.
306Lesson 6 Finishing and Management
Working with Stills
Instead of simply copying and pasting grades, you may want to save your grades into the
gallery as a still so you can recall the grade at any time. Using stills has some advantages
over copying and pasting grades. First, stills can be imported and exported from a project
so you can have an independent folder of your grades that you can use at any time in any
project. They also save each node of the grade so you can apply only certain nodes if
needed. A key feature of using stills is the ability to compare clips with saved graded stills
so you can easily match two shots together.
Applying Stills
1 Select clip 03 again in the timeline. This grade has proved useful so far, so it might be a
good idea for you to save it.
You can save the grade on this shot by saving a still into the gallery.
2 Right-click in the viewer and, from the menu, choose Grab Still.
The reference still image is saved to the gallery. The still contains all the nodes needed
to rebuild the grade for any shot it is applied to.
It is good practice to label the stills so that when you return to them, you have an idea
of what they are.
307Lesson 6 Finishing and Management
3 Right-click the still in the gallery and select Change Label.
4 Rename the still CONTRAST LIGHT.
5 Select clip 13 in the timeline.
This is another desert shot that may benefit from the grade we have saved.
Before applying the grade, you can preview it on any clip in the timeline using the still
in the gallery.
6 To preview the still, with clip 13 selected, move the mouse pointer over the still and
move it back and forth.
The viewer will show you the current selected clip in the timeline using the grade of the
still you are hovering over. If you decide the grade is suitable, you can apply it.
```
TIP If you want to turn the preview off, you can go into the Options (…) menu
```
in the gallery by clicking the three dots in the top right corner of the window
and unchecking the Live Preview option.
308Lesson 6 Finishing and Management
7 Right-click the CONTRAST LIGHT still in the gallery and choose Apply Grade.
8 Select node 02 and go into the HDR tools and dial down the temperature in the Global
controls to make the windowed area in the image a little less saturated.
The grade contained in the still is applied to the clip. If only achieving specific looks
across multiple clips were this straightforward. What happens when you need to add
grades to clips that have already been graded or need shot matching?
Appending Stills
Sometimes copying and pasting a grade is not the correct way of working, since simply
pasting a grade will overwrite any nodes that have already been applied to the clip. In this
case, stills become extremely useful because the nodes contained within them can be
added to nodes already on a clip.
1 Select the clip 10 thumbnail. This is the primary and secondary grade you did of the
interview.
2 Right-click in the viewer and choose Grab Still.
3 In the gallery, rename the still INTERVIEW GRADE.
4 Select clip 11.
309Lesson 6 Finishing and Management
This is the clip from the Sony camera that we matched to earlier, but you now need it to
take all the complex grades you applied to the other angle.
5 Right-click the INTERVIEW GRADE still in the gallery and choose Append Node Graph
from the menu.
The grade from the still will be added to the nodes already applied to the clip.
310Lesson 6 Finishing and Management
If only you could leave it there…but several adjustments are needed to get the clips to
match again.
6 Delete node 03 since it is the contrast adjustment from the first grade.
7 Select the new node 03, which is now the shirt we changed the color of.
8 Turn on the Window by clicking the onscreen Overlay button next to the window icon.
As you can see, the window is totally out of position, and the key for the shirt needs
some cleaning up as well.
9 In the top left corner of the viewer, turn on the Highlight button.
10 Using the power window control points, reposition the power window so it just sits
over the shirt. Remember to try to get it as close as possible to the shirt.
TIP You can add extra control points by simply clicking any part of the window
path to make a more accurate selection.
311Lesson 6 Finishing and Management
```
Now the shirt looks much cleaner; however, the key does need a little bit of tweaking.
```
11 In the top left corner of the viewer, turn off the Highlight button.
12 Turn on the Qualifier by clicking the onscreen Overlay button from the window icon to
the qualifier icon.
You should now see all the qualifier paths drawn for the selection of the shirt. Even
though they are not quite in the right place, you have a pretty good key. Again,
however, like the window, it just needs a slight adjustment.
13 Click the Qualifier tool in the middle window to bring up the Qualifier window.
14 Click the Picker Subtract tool and then deselect the Auto B/W Highlight.
15 In the viewer, click and drag over the noise over Sean’s left shoulder and on the right
side of the neck.
312Lesson 6 Finishing and Management
16 Just on the right neckline is a dark green area. Using the same tool, drag over the
section to remove it.
17 Go back into the Qualifier window and click the Picker Add button and carefully draw a
line on the top of the right shoulder of the shirt to add the blue edge to the selection.
We have now got rid of the noise, but the face needs a slight adjustment as well.
18 Select node 04.
19 In the Qualifier window, click and drag the Clean White parameter to the right to
around 40 so the blue sections on Sean’s face disappear, and the Clean Black
parameter to around 50 so the skin selection is smooth.
313Lesson 6 Finishing and Management
You can see that there is a slightly blue section now on the subject’s neck, so we just
need to add that to the selection.
20 Go back into the Qualifier and click the Picker Add button and drag the selection over
the blue neck area. We now have a pretty good key but remember that this grade had
a tracked power window as well.
21 With node 04 still selected, click the Window tool in the middle window.
22 Resize and reposition the circular power window in the viewer so it comfortably covers
all of the face.
23 Click the Tracker tool in the middle window and click the Track Forward button to make
sure the window is tracked accurately to the face.
24 Select node 06 and repeat the above process by moving the power window over the
eyes and tracking it.
314Lesson 6 Finishing and Management
Matching Shots Using Stills
Looking at the two shots together now, they look mostly the same, apart from one thing:
the skin tone on clip 11 that we just applied the grade to looks a little bit pink and has a
little too much contrast. We can use the still we saved from the previous clip to compare
the skin tones side by side to get them as close as possible.
1 With thumbnail 11 still selected, double-click the INTERVIEW GRADE still to create a
split screen.
After double-clicking a still, a vertical split appears in the viewer, showing the timeline
```
clip (clip 11) on the left and the selected gallery still on the right.
```
2 Click and drag the vertical line in the viewer to the right to reveal more of the timeline
clip. By dragging left and right, you will notice that the timeline clip is slightly darker
and lacks a little contrast when compared to the still.
3 Drag the vertical line slightly right until you have a good position to see the skin tone
on the timeline clip and some of the skin tone from the reference still.
4 Select node 04, which is your skin tone qualified node.
```
5 Choose Workspace > Viewer Mode > Enhance Viewer or press Option-F (macOS) or
```
```
Alt-F (Windows) to expand the viewer.
```
This gives you a better view when you do not need to access the Node Editor or gallery.
315Lesson 6 Finishing and Management
Since we are adjusting a grade that took some time to get right, you may want to save
it at this stage.
6 Right-click in the viewer and choose Grab Still.
7 Label the still INTERVIEW ALT ANGLE.
TIP Stills are a great way of taking a snapshot of a grade at any stage.
The more you progress with color correction, the more complex your grades
will become. Grabbing a still saves a version of a grade at any point in time,
making sure you can reapply it if you make mistakes further down the line.
8 In the primary controls in the left window, drag the Contrast up slightly to around
1.094 and the Pivot to around 0.030 so the highlights and shadows on Sean’s face are
a closer match to the still.
9 Drag the Mid/Detail right to around 20.00 so the features look slightly less soft.
10 Using the Gamma color control, drag the center control point slightly toward green so
the red and blue controls both read -0.01.
316Lesson 6 Finishing and Management
11 Drag the Color Boost up to around 8.00.
TIP Color Boost lets you raise the saturation in areas of low saturation. This
can sometimes prove more useful than the saturation control, since areas of
higher saturation will not be affected.
You will focus on the area of Sean’s face that is to the right of his mouth and that lines
up with his neck on the still.
You can see that the areas are very close, and the still might be ever so slightly darker.
12 Drag the Gamma master wheel left slightly until the skin tones between the two shots
look matched.
13 Click the split screen button in the top left corner of the viewer to turn the split
screen off.
14 Press the Up Arrow key on the keyboard to jump to the previous shot and then press
the Down Arrow key to jump back to the shot we have just matched.
The skin tones now look so close that when you jump between the shots you can
hardly tell the difference. This is what you are aiming for, as the second interview clip is
at an alternative angle, meaning that its lighting may be slightly different, so it may not
match exactly, but the skin tone looks the same when jumping from shot to shot.
317Lesson 6 Finishing and Management
```
15 Choose Workspace > Viewer Mode > Enhance Viewer or press Option-F (macOS) or
```
```
Alt-F (Windows) to exit the expanded viewer.
```
To try more shot matching, grab a still from thumbnail 04, apply the still to thumbnail
05, turn on split screen and, using the techniques you have learned, try to match
the shots.
Shot matching is made easier when using the gallery and reference stills to help you
analyze the makeup of your shot and what corrections need to be made. You should
also use the scopes to minimize any visual quirks because your visual perception
naturally tends to force you to match shots. The combination of reference stills and
scopes will make the shot matching more accurate, providing continuity in
your project.
Importing and Exporting Grades
One of the big advantages of using stills is the ability to import them into and export them
out of the project. You could have a folder of stills on a hard drive that could be applied to
any project, and because a still saves each step of the grade, it can be applied to any clip
and adjusted accordingly.
Post-production houses often use multiple galleries in episodic television work so they can
get color continuity correct across different scenes and different episodes. Using stills
gives the colorist a good starting point rather than having to start the grade from scratch
each time. Colorists may also have multiple stills for the same shot so they can choose a
creative look.
1 Right-click in the gallery and choose Import.
2 Go into the Lesson 06 folder in the training materials and select the STILLS folder.
318Lesson 6 Finishing and Management
3 Select the .dpx file called AFTERNOON.
4 Click the Import button, and the stills will be imported into the gallery.
5 Make sure clip 16 in the timeline is selected.
6 Right-click over the AFTERNOON still and choose Apply Grade.
As before, all the steps of the grade, including the power windows, have been applied
to the clip. However, you want to create a totally different look for this shot, so you can
use the nodes already there to create a shot that feels like morning rather
than evening.
7 Select node 01 BALANCE and, in the top right corner of the Primary Color Wheels
window, click the Reset All button. This will reset the color on the node but not the
power window.
You now want this clip to be brighter to have more of an early morning feeling.
319Lesson 6 Finishing and Management
8 Drag the Gamma master wheel to the right to lift the brightness of the shot. Drag until
the parameter reads around 0.04 or until you feel the shot is suitably brighter.
9 Select Node 02 SHADOWS and click the HDR wheels in the left window.
10 Using the Shadow color control wheel, drag the center away from orange across
toward teal to give the shot a colder look.
11 Select node 03 CONTRAST.
```
The shot looks much cooler now; however, there is a little too much contrast, giving
```
the shadows a longer feel when they should be much flatter.
12 Select the Curves button in the middle window.
320Lesson 6 Finishing and Management
13 Right-click the control point second from the left on the curve to delete it.
14 Now on the second point in the curve, drag it upward slightly to get the contrast in the
shot looking reasonably flat.
This cool morning look can now be saved as a still for use later.
15 Right-click the viewer and choose Grab Still. The still will appear in the gallery.
16 Right-click the still and choose Change Label. Label the still MORNING.
17 Right-click the clip again and ensure that the option “Use labels on still export” is checked.
TIP The Project Settings > General Options includes an option to label your
stills automatically. There are several parameters that you can configure to
automatically label a still.
321Lesson 6 Finishing and Management
18 Keep the menu open and choose Export. Save the still back to the STILLS folder in the
Lesson 06 folder.
As you can see from this process, using stills can be timesaving. Even though the look
you imported was very different from the one saved, it was a quicker process to adjust
the clip to the creative look by using the nodes that were contained within the
original still.
Working with LUTs
A Lookup table, or LUT, is in essence a conversion chart that converts color values. It takes
```
the input color (the red, green, and blue values), converts those using a chart, and
```
produces the conversion onscreen. There are two different types of LUTs: 1D and 3D. A 1D
LUT works very simply by changing the red, green, and blue channels input values to
another value for output. A 3D LUT is more complex, as it gives each color channel an RGB
value, so the math is more complex, yet the LUT is able to hold more information.
At first glance, a LUT appears very similar to a still since it can be applied to a clip and
change the look of the color and contrast in the shot. Unlike a still, though, a LUT does not
```
show the stages of a grade; it is in essence a locked box that cannot be broken down,
```
merely applied.
NOTE Because a LUT is a table of information, it cannot contain any complexities
that go beyond RGB values. That means secondary grading tools such as power
windows are not included in a LUT because it cannot understand the window
information it is being sent.
However, LUTs have many uses, and unlike stills they can work outside of the
DaVinci Resolve software. For example, if a camera is shooting in a Log profile it may be
difficult to judge what the shot looks like in a deliverable color space. So a LUT can be
added to an output monitor to give the production crew an idea of what the shot will look
like on a cinema or television screen, while the camera still records the Log profile with all
its contrast and color information still intact.
You can even create a custom LUT, save it, and upload it onto a Blackmagic Design camera,
where you can shoot the scene while seeing an approximation of how the final footage
will look.
322Lesson 6 Finishing and Management
Applying a LUT
Lookup tables allow you to quickly recalibrate how your color pixel data is displayed,
essentially providing another form of color management or color correction. Conveniently,
DaVinci Resolve comes equipped with many different LUTs for converting one color space
to another, and you can easily apply these LUTs from the color page.
1 Select clip 18 in the timeline.
2 In the top left corner of the interface, click the LUTs button to reveal the LUTs browser.
```
The clip you are looking at is using color management; however, it still appears to have
```
little contrast. You could try using a LUT, which may get a better result.
The LUTs browser is divided into different cameras and color space categories. When
you’re working with a specific camera and need to convert it to look appropriate for
your display, you can apply one of the LUTs from your camera’s category. We are using
a DJI clip, so we will choose from the DJI LUT category.
```
Before applying the LUT, we need to make sure the shot is not color managed;
```
otherwise, the color conversion will be performed twice and will be incorrect.
3 Right-click thumbnail 23 and, from the menu, choose Input Color Space > Project
```
Rec.709 (scene).
```
This means the color management will use the project settings for this clip, so it will
not perform any conversion, and the clip will look like a log image again.
323Lesson 6 Finishing and Management
4 In the LUT browser, select the DJI category.
5 Click and drag the slider in the top right corner of the LUT browser to make the
thumbnails slightly bigger.
6 In the browser, locate the DJI_X7_DLOG2Rec709 LUT and move your mouse pointer
back and forth over the thumbnail to preview the LUT in the viewer.
7 Right-click the LUT thumbnail and choose Apply LUT to Current Node.
324Lesson 6 Finishing and Management
The LUT is applied to node 01, but just like using color management, LUTs do not know
where to set your shadows and highlights. The LUT doesn’t know if your white balance
is correct. You still need to balance the shot after applying a LUT.
NOTE Always keep in mind that a LUT is converting one set of RGB values to
another using the values contained in the LUT itself. So, if you go from a wide
camera gamut to a much narrower delivery gamut through a LUT, much of the
color information will be discarded. When using LUTs, it is often better to
grade before using them to ensure that you can still use a camera’s full
color profile.
8 With node 01 still selected, right-click and choose Add Node > Add Serial Before to add
a node before the LUT.
9 In the left window, drag the Contrast slider right to around 1.280 and the Pivot left to
around 0.250.
325Lesson 6 Finishing and Management
10 Drag the Color Boost right until it is around 14 or the shot has more color in it.
Saving LUTs
DaVinci Resolve comes with a variety of LUTs that you can start using right away. However,
one of the strengths of DaVinci Resolve and its LUT workflow is the ability to create custom
LUTs and share them with other colorists or production crew members.
We have now created a nice conversion for our DJI shot, and you may want to save this as a
LUT for other shots. Remember that LUTs cannot save secondary grades such as power
windows or qualifiers—for that, you need stills—but in this case, for any other DJI shots,
you can create a LUT.
1 Right-click thumbnail 18 and choose Generate LUT > 33 Point Cube.
326Lesson 6 Finishing and Management
LUTs can be saved using 17, 33, and 65 points. The more points, the more accurate
the LUT. 33-point LUTs have been the standard for a while and are widely supported in
cameras, displays, and applications. 65-point LUTs contain more precision but are also
less compatible with other devices.
2 Go into the Lesson 06 folder in the training materials and select the LUTS folder.
This folder contains another folder called R20 TRAINING, which is currently empty. It is
set up this way so the R20 TRAINING folder will appear in your LUT browser.
3 Save the LUT as DJI2Rec709_Custom.
TIP By default, the LUT will take the name of the clip it was generated from. If
you want to change this, you can simply rename the LUT in the Finder/Explorer
window on your system. It will automatically update in DaVinci Resolve.
Using LUTs in this way can be very useful for sharing grades. The LUT has no
adjustable parameters and is just applied, therefore no mistakes can be made. If a still
is sent, there is more room for error since a node can be missed or accidentally
deleted, changing the look. Also, if you do not want to show how your grade was built,
saving it as a LUT removes all the node information.
327Lesson 6 Finishing and Management
Loading LUTs
Once a LUT has been saved, it must be loaded back into DaVinci Resolve for you to be able
to use it. Unlike gallery stills that are saved in one place that DaVinci Resolve references,
LUTs can be imported from any location on a system. Therefore, you must point
DaVinci Resolve to the location of your custom LUT folders.
You can choose to install a LUT into the default LUT folder or simply choose a LUT folder to
load in the System Preferences.
1 In the top left of the interface, select DaVinci Resolve > Preferences.
2 Within the System Preferences, choose the General option.
3 In the LUT Locations section, click the Add button in the bottom left corner.
328Lesson 6 Finishing and Management
4 Go into the Lesson 06 folder in the training materials and select the LUTS folder.
This folder contains another called R20 TRAINING, which contains the LUT you have
just saved. It is set up this way so the R20 TRAINING folder will appear in your
LUT browser.
5 With the LUTS folder selected, choose Open, and the LUT folder will be added to the
LUT Locations.
NOTE The file path may be different to the one in the picture since it depends
on where you have saved your lesson files.
6 Click Save in the bottom right corner of the System Preferences window.
The LUT may not appear straight away since the file path to the LUT may need to be
refreshed.
7 Right-click the LUT folder in the folder window and choose Refresh. The R20 TRAINING
folder will appear with your newly created LUT inside.
TIP Be cautious when downloading LUTs from third-party sources. Their
implementation could result in your content looking very different from the
originally intended adjustments. Since post-production companies can
generate LUTs precisely calibrated to their environments, they are popular for
in-house use. However, using LUTs taken out of those controlled environments
can cause results to vary widely.
Your LUT can be used for any other DJI footage that you now use.
329Lesson 6 Finishing and Management
8 Go to the edit page and find the clip A126C012.mov in the DJI bin.
9 Add the clip to the end of the timeline.
10 Go back into the color page and select the clip you have just added to the timeline.
11 In the LUT folder, choose the R20 TRAINING folder and double-click the DJI2Rec709_
Custom LUT to apply it to the new clip.
Making Creative Decisions
You now know how to create stills and LUTs to save different grades. One of the most
exciting elements of color grading is making the creative decisions regarding what the look
and feel of your project or certain scenes will be. If you have created a number of different
looks, by saving them as stills or LUTs, you may want to compare these looks side by side
to see what look a shot or scene may lend itself to.
1 Select clip 16 and right-click in the Node window and choose Reset All Grades
and Nodes.
330Lesson 6 Finishing and Management
2 Select the Gallery button to turn on the gallery.
3 Right-click in the gallery and choose Import.
4 Navigate to the Lesson 06 folder in the browser, select the STILLS folder, and import
the DAYTIME still.
5 In the top left corner of the viewer, click the Split Screen button. A white outline will
appear around the viewer.
331Lesson 6 Finishing and Management
6 Click the split screen menu and choose Selected Still Grades.
```
7 In the gallery, hold down the Command key (macOS) or Ctrl key (Windows) and select
```
the EVENING, MORNING, and DAYTIME stills.
The viewer will split into four, showing the original clip and three other versions of the
clip with the selected still applied. From here, you can decide which still suits the clip
the best and add it by double-clicking in the viewer to add the specific still.
With an understanding of the color page, you can now quickly assemble a variety of looks
using your color-grading skills. You could also employ the use of LUTs or export your own to
share with fellow collaborators. By saving stills of your grades as you progress, you will be
able to quickly balance similar shots and create looks that you can reuse in different projects.
332Lesson 6 Finishing and Management
Color Grading Using Blackmagic Cloud and Collaboration
When working in collaborative projects in Blackmagic Cloud, multiple colorists can
grade on the same timeline at the same time. In collaboration mode, a colorist
who selects a clip will become the owner of that clip until they select another in the
timeline. The colorist’s initials will appear in the top left corner of the thumbnail.
When they move on to the next clip, a refresh symbol can be selected by every
other user in the project, and the grade will be applied, ensuring a seamless
workflow wherever the colorists are in the world.
The Cloud workflow also allows for remote monitoring to an iOS device or
computer with a Blackmagic Design Desktop Video device. By simply turning on
remote monitoring, DaVinci Resolve will generate a stream key that can be sent to
anyone, anywhere in the world. By simply downloading and opening the remote
monitoring app, the key can be pasted in, and a graded timeline will be shown on
the device. The grades are shown in real time, so when you adjust the grade, it can
be seen changing on the remote monitor.
333Lesson 6 Finishing and Management
Lesson Review
1 True or False? Appending a still will overwrite the current grade?
2 How would you match a shot in the timeline with a still stored in the gallery?
3 True or False? DaVinci Resolve FX will always affect the whole image, even when used in
conjunction with other tools.
4 How can a grade be copied using just the mouse?
5 When on a selected node with a LUT applied, what node option might you use to avoid
using a LUT’s limited color space?
334Lesson 6 Finishing and Management
Answers
1 False. Appending a still will add the grade contained in the still to the current grade
on the clip.
2 Using the Image Wipe will split the viewer, with one half showing the timeline clip and
the other showing the still so the shots can be easily matched together.
3 False. Resolve FX can be used with power windows to mask the effect to a certain area.
4 Selecting the clip you want to copy a grade to and then clicking over the clip you want
to copy the grade from using the middle mouse button will automatically copy and
paste the grade.
5 Choosing Add Serial Before will apply a node before a LUT and will ensure that you are
not working in a LUT’s limited color space.
Time
This lesson takes approximately
75 minutes to complete.
Goals
Creating a New Project 336
Exploring the Source Media 339
Project Settings 344
Importing Media 350
Syncing Audio to Video 353
Working with Metadata 365
Creating Keyword Smart Bins 370
Creating Custom Smart Bins 378
Renaming Clips with Metadata 384
Creating Subclips 388
Preferences 396
Exploring Keyboard Shortcuts 407
Lesson Review 415
Lesson 7
Project Setup
and Preferences
By now, you should have a good
understanding of how the toolset and
features in DaVinci Resolve 20 can
be used to edit and color grade your
projects. In the preceding lessons,
the projects you worked on were set
up and organized for you to explore
how certain features can be used—
whether it was how useful subclips are,
or how enabling DaVinci Resolve Color
Management can fast forward the
grading process. Now that you have a
good grasp of the general toolset, it’s
time to learn how to correctly set up a
project of your own.
336Lesson 7 Project Setup and Preferences
In this lesson, you will delve deeper into DaVinci Resolve’s Project Settings to learn how to
ensure that your projects are set up correctly. Then, you’ll learn how to leverage the power
of metadata to sort through large amounts of footage quickly and efficiently. Finally, you’ll
be taken on a guided tour of the various preferences and keyboard shortcuts you can
customize to your specific needs.
Creating a New Project
The projects you have worked with so far have all been created and set up so that you
didn’t have to worry about the settings, allowing you to just dive in and explore the exciting
tools that the edit and color pages have to offer. At some point, though, you will need to
create your own project, so it’s important that you understand some of the essential
project settings you’ll need to consider.
Of course, the first step is to create a new project in the Project Manager.
1 Open DaVinci Resolve.
2 Ensure that the Project Manager is set to your Local project library and click the New
Project button.
TIP If DaVinci Resolve is already open, you can choose File > Project Manager,
or press Shift-1, or click the Project Manager button in the lower right corner
of the interface to open the Project Manager. You can also choose File > New
Project to create a new project directly. Projects created in this way will still be
added to the top level of the Project Manager, even though the Project
Manager itself isn’t open.
3 In the Create New Project window that appears, type the project name,
MY OMO PROJECT.
337Lesson 7 Project Setup and Preferences
Whenever you create a new project in DaVinci Resolve 20, you will be asked to specify a
Media Location, which is a folder on your system to hold all generated media created
for that project. An example of “generated media” is the audio file created when you
used the Voiceover tool in Lesson 3. The Media Location can be on a local disk, an
external drive, or a network storage location.
```
For the purposes of this lesson, you will leave the Media Location set to the default;
```
however, you can also change this location any time using the Project Settings, which
you will explore in due course.
4 Click Create.
The new project is created, and DaVinci Resolve opens on the cut page unless you
were previously working in another page and hadn’t closed Resolve before creating
the new project.
5 Choose Workspace > Reset UI Layout to return all pages in Resolve to their
default layouts.
TIP If you want to save a customized layout, you can choose Workspace >
Layout Presets > Save Layout as Preset. Note that saved presets save the
layout for every page in Resolve. You can then load, update, export, or delete a
saved preset by choosing Workspace > Layout Presets > [Preset Name] >
Load Preset / Update Preset / Export Preset / Delete Preset.
The media page is dedicated to helping you focus on preparing and organizing the
media for your project. It is here that you have the most space to explore the clips you
have to work with, without the distractions of a timeline, color grading controls, or
audio mixers taking up valuable screen real estate.
However, as project organization is not something that just happens once when you
first set up a project, many of the functions discussed in this lesson can also be applied
directly in the edit page so you can implement them alongside your editing.
338Lesson 7 Project Setup and Preferences
6 Click the Media button or press Shift-2 to switch to the media page.
The media page is dedicated to reviewing and organizing your source media—principally,
video, audio, and graphics. However, before you start dragging files into your project, you’ll
learn more about the settings of your projects and why it’s important to make sure those
settings are correct.
TIP You can also use similar keyboard shortcuts to switch between the other
```
pages: Shift-4 for the edit page, Shift-5 for Fusion, Shift-6 for the color page,
```
Shift-7 for Fairlight, and Shift-8 for the deliver page.
339Lesson 7 Project Setup and Preferences
Exploring the Source Media
Before going further with this project, it is useful to consider the source media files you’ll
be working with. For this lesson, you will re-create the project you started with in Lesson 1,
“Editing a Rough Cut.” The media page is the perfect place to do this, even before you’ve
imported a single clip, thanks to the media storage browser.
1 Using the media storage browser at the top left of the media page, navigate to R20
Beginners Guide/Media/OMO.
This displays the source media folder, which contains additional folders that have been
created to store the source clips.
TIP If you find it difficult to navigate through your file system using the media
storage browser’s rudimentary directory tree, you can simply open a location
```
in the Finder (macOS) or File Explorer (Windows) and drag the folder into the
```
media storage browser to open that location directly.
340Lesson 7 Project Setup and Preferences
2 In the media storage browser at the top left of the media page, double-click the
B-ROLL folder to view its contents.
This folder contains the B-roll clips for the Organ Mountain Outfitters project that
you’ll no doubt recognize from earlier lessons.
You can select any of these clips and preview them, similar to how you’ve worked
previously in the edit page, using the same keyboard shortcuts for playing clips in the
```
media page’s source viewer that you’ve used previously on the edit page (see Lesson 1
```
```
for more details).
```
3 Move your mouse pointer across any of the clips in this folder to live preview the clip in
the media page’s viewer.
341Lesson 7 Project Setup and Preferences
```
TIP You can disable and enable Live Preview in the viewer’s Options (…)
```
menu and toggle audio scrubbing by pressing Shift-S or by choosing
Timeline > Audio Scrubbing
4 In the Media Storage browser, click the “i” button of any clip to reveal more information
about that clip.
As in the media pool, clicking the “i” button reveals information about the file, such as
its duration, resolution, frame rate, and video codec.
5 Click the List View button at the top of the media storage browser.
342Lesson 7 Project Setup and Preferences
6 Scroll until you can see the Resolution and FPS columns.
Using List View allows you to compare the properties of multiple clips. Here, you can
```
see that the clips are all the same resolution (1920 x 1080) but have various frame rates
```
```
(23.976, 24, 30, 48, and 60 fps).
```
TIP You can choose to show or hide different columns of information by
right-clicking any of the column headings in the media storage browser.
7 Click the Thumbnail View button to return to viewing the familiar clip thumbnails.
343Lesson 7 Project Setup and Preferences
8 In the media storage location’s directory tree, select the INTERVIEW folder in the
Organ Mountain Outfitters folder.
This folder contains two additional folders: AUDIO and VIDEO.
TIP If you manually navigate to a folder, you can then use the Back and
Forward buttons at the top left of the media storage browser, like in an
internet browser.
9 Double-click to open the VIDEO folder and view the clips.
344Lesson 7 Project Setup and Preferences
This folder contains all the interview clips with Organ Mountain Outfitters’ founder,
Chris Lang.
10 Click the List View button and compare the clips’ resolutions and frame rates.
Again, these interview clips have all been shot at a resolution of 1920 x 1080 and at a
consistent 23.976 frames per second.
To summarize: the media you’ve been supplied with for this project has a 1080 HD
resolution, with a variety of frame rates ranging from 23.976 to 60 frames per second. You
will also note from the rather low saturation of the images that the footage has been shot
in a specific color space.
Project Settings
When you create a new project in DaVinci Resolve, the project itself has some default
settings that it draws upon. While these settings might be commonly used, they’re not
always appropriate, depending on where you need to deliver the project, your clients’
requirements, or the source media you’re working with. Therefore, the next step when
creating a new project should be to check these basic settings and adjust them to your
needs. Possibly the most important of these settings concerns your timelines since these
are the containers for all your edited and graded clips. It’s important to get these settings
right as early as possible because making things right later, while possible, can become
a little tricky.
By default, all projects usually have a timeline resolution of 1920 x 1080 HD and a timeline
```
frame rate of 24 frames per second (fps). You’ll remember that the resolution was chosen
```
during the Quick Setup phase when you first installed and opened DaVinci Resolve on your
```
system (see the “Getting Started” section at the beginning of this book), but it also
```
becomes the default even if you chose to skip the Quick Setup or when you create another
```
project library (see Lesson 10, “Delivery and Media Management”). Therefore, this
```
resolution and frame rate are used whenever you create a new timeline using the Project
Settings option. Although these settings can be changed when you create a new timeline
so that each timeline in any project can have completely different settings, most projects
tend to use the same timeline settings for the majority of their timelines, so it’s useful to
set a general setting in the Project Settings window.
345Lesson 7 Project Setup and Preferences
So what timeline settings should you use? That depends primarily on where you will deliver
your final edited timeline. For example, if you’re working on a feature-film project, you’ll
```
probably want to deliver a 3840 x 2160 Ultra HD timeline at 24 frames per second; if it’s a
```
broadcast TV show, then the timeline might be 1920 x 1080 HD at 29.97 or 25 frames per
```
second; whereas if you will deliver a file to a streaming site such as YouTube or Vimeo, your
```
choices aren’t quite so limited and you may need to make a judgement call based on the
source footage itself. Ideally, you should always decide the resolution and frame rate of a
project prior to shooting any footage. This way, you can ensure that the footage is shot
appropriately. However, Resolve can easily work with different resolutions and frame rates
in the same project, even on the same timeline.
Resolution Independence
DaVinci Resolve is “resolution independent,” which means you can add clips to a
timeline in any combination of resolutions, and they will automatically fit the
current timeline resolution. You can later output that timeline to as many other
resolutions as necessary in order to create multiple deliverables. When you do so,
all effects and transforms will automatically readjust themselves to match the
sizing of each new timeline resolution.
In short, what this means is that you can create multiple deliverables in multiple
resolutions by simply changing the timeline resolution or by using a lower
resolution setting in the deliver page compared to the timeline resolution when
you create a new job to render out, and every effect will be the right size
automatically.
For the Organ Mountain Outfitters project, the final exported file needs to be
HD resolution at 23.976 frames per second, so these are the Project Settings you
will choose.
NOTE In the free version of DaVinci Resolve, you are limited to working with
timelines at a maximum resolution of 3840 x 2160 Ultra HD, with a frame rate of
up to 60 frames per second.
346Lesson 7 Project Setup and Preferences
1 Choose File > Project Settings or press Shift-9 to open the Project Settings window.
2 Ensure that 1920 x 1080 HD is selected in the Timeline Resolution menu and 23.976
frames per second is selected from the Timeline Frame Rate dropdown menu.
NOTE When you change the frames per second option, the Playback Frame
```
Rate and Format in the Video Monitoring section change to match (the latter is
```
only relevant if you are using Blackmagic Design Decklink or Ultrastudio I/O
```
devices). Normally, this is what you would want; however, in very rare instances
```
you can adjust these separately, especially if you’re working with a timeline
resolution or frame rate that is not supported by your video monitoring
hardware. You may also need to manually change the Video Resolution so that
you are monitoring at the correct resolution.
While you are here, there are other settings that you can adjust for this project too,
especially since this footage looks like it’s shot in a particular color space.
347Lesson 7 Project Setup and Preferences
3 Select Color Management and, in the Color Science dropdown menu, choose DaVinci
YRGB Color Managed. Leave the Timeline and Output Color Space options set
to Rec 709.
4 Once you have changed the Project Settings for this project, click Save to save them.
The media displayed in the media storage browser will now be automatically
color managed.
348Lesson 7 Project Setup and Preferences
Saving Project Presets and
Setting the Default Preset
If you frequently work with projects requiring different settings, saving project presets can
be useful.
Project presets save all the settings in the Project Settings. They are useful because they
can be used to quickly load lots of settings instantly or to transfer project settings among
different Resolve systems. You can also set a project preset as a default for all newly
created projects in the current Project Library.
```
1 Reopen the Project Settings window, click the Options (…) menu and choose Save
```
Current Settings as Preset.
2 In the Preset Name window, type 1080HD 23.976 RCM.
NOTE This naming convention summarizes the current project settings—
```
resolution (1080 HD) and frame rate (23.976) — and that Resolve Color
```
```
Management (RCM) is enabled. However, there are no definitive rules
```
regarding how you should name your presets.
349Lesson 7 Project Setup and Preferences
3 Click OK.
All the settings for the current project are now saved as a preset that you can
quickly load.
4 Click the Options menu again and choose Default Preset > Load Preset.
This reloads the default project settings, returning the Timeline Format settings to
their starting values, with the Timeline Format set to 1920 x 1080 and 24 frames per
second and the Color Science set to DaVinci YRGB.
5 Click the Options menu and choose 1080HD 23.976 RCM > Load Preset to reload the
saved preset you’ll use for this project.
```
6 Click Save to save any changes you’ve made to the current project’s settings (or Cancel
```
```
if no changes have been made) and close the Project Settings window.
```
Changing the Default Project Settings
and Managing Project Presets
If you regularly work on projects, it’s likely that each project will have the same
settings. Instead of customizing the project settings for each project you create,
you can specify a project preset as the default for the current project library.
Simply choose the preset from the Project Setting’s Options menu and choose Set
as Default Preset.
You can also export a project preset that you can use to quickly load the same
project settings onto another DaVinci Resolve 20 system. Choosing the Export
Preset option will create a .preset file containing the project settings. This can then
be transferred and imported into another DaVinci Resolve system using the
Import Preset option.
350Lesson 7 Project Setup and Preferences
Importing Media
Now that you have a better idea about the files you’ll be working with and have set up the
project accordingly, it’s time to import the files into your project so you can start working
with them further.
There are numerous ways to import files into a DaVinci Resolve project. For instance, you
```
could choose File > Import > Media on any page that has access to the media pool (that is,
```
```
every page except the deliver page). You can also simply drag and drop files from the
```
```
Finder (macOS) or File Explorer (Windows) directly into the media pool! However, both
```
techniques offer limited options, whereas the media page provides much more flexibility
when it comes to importing clips.
NOTE Whenever you import media, DaVinci Resolve creates a link to the original
clips on your hard drive. At no point does this import process copy, move, convert,
or in any way alter the source media.
1 In the media storage browser, navigate to the R20 Beginners Guide/ Media/OMO
folder and select the B-ROLL folder.
2 Right-click the B-Roll folder to reveal the import options.
351Lesson 7 Project Setup and Preferences
There are three main options for importing clips from the media storage browser:
— Add Folder into Media Pool will import the contents from one level inside the
current folder.
— Add Folder and SubFolders into Media Pool will import the contents of the
current folder and any additional folders contained within it. This is the same as
when you drag a folder into the media pool either from the media storage browser
```
or from the Finder (macOS) or File Explorer (Windows). This is a useful option when
```
importing numerous files from different folders from a camera card that uses a
complex directory structure.
```
— Add Folder and SubFolders into Media Pool (Create Bins) will import the
```
contents of the current folder and any additional folders contained within it,
preserving the folder structure as a series of bins in the media pool. This option is
most useful when you want to import several clips that are already organized into
folders on your hard drive.
```
3 Choose Add Folder and SubFolders into Media Pool (Create Bins).
```
A window appears asking whether you want to change the project frame rate.
This is because the first clip in this folder has a different frame rate than the one you’ve
set for the project. Of course, you wouldn’t want the project frame rate to change in
this case.
This warning occurs only if the first clip imported into a project has a different frame
rate than the Timeline Format in the Project Settings. Subsequent files will not trigger
this behavior.
NOTE If you inadvertently change the project frame rate, you can always
change it back in the Project Settings before creating any timelines. Once
you’ve created a timeline in a project, the Timeline Frame Rate in Project
Settings cannot be changed, although timelines you create subsequently can
have their own individual settings, which you will need to set when you create
the new timelines.
352Lesson 7 Project Setup and Preferences
4 Click Cancel to keep your current project’s frame rate. The B-Roll clips are added to the
media pool in the B-ROLL bin.
5 In the media storage browser, select the GRAPHICS, INTERVIEW, and MUSIC folders
and drag them to the bin list in the media pool.
The rest of the media is added to the media pool in a series of bins that reflect the
folder structure of the Organ Mountain Outfitters source folder.
TIP The media pool automatically sorts bins in the order they were created,
with newly created bins appearing at the bottom of the bin list. You can
change the sort order by right-clicking a bin in the bin list and choosing Sort
By > Name, Date Created, Date Modified, or User, in an ascending or
descending order.
353Lesson 7 Project Setup and Preferences
Resyncing Media Files
If you choose to import media using the folders on your system’s hard drives to
create the bins in your projects, then you can use the Resync Media Files option to
automatically import any newly added media files to those folders on your
hard drive.
Simply right-click a bin and choose Resync Media Files. Any files that have been
added to the source folder since import or the last resync operation will be
automatically added to the bin!
Alternatively, you can choose to enable Automatically Resync Media Files. This
automates the resyncing process, importing any new media files to the bin in your
project that are added to the source folder without you having to do anything else!
Syncing Audio to Video
Now that you have the media imported into the project, you can organize the footage
prior to editing. You will start by syncing the interview footage to the separately recorded
audio files!
Many productions record audio on dedicated digital audio devices to capture the highest
quality audio, or when it’s not practical or desirable to record audio directly to a camera.
Thus, when the files come in from the day’s shoot, you’ll need to sync the appropriate
audio and video clips—a process often referred to as “syncing the dailies.” Thankfully,
DaVinci Resolve has a fantastic way of making this process as painless as possible.
1 In the bin list, select the AUDIO and VIDEO bins inside the INTERVIEW bin to display
the contents of both bins in the media pool.
354Lesson 7 Project Setup and Preferences
2 Play the first video clip, F002_08151648_C005.mov, in the viewer.
This is one of the interview clips with Chris Lang that you worked with in Lesson 1.
Unfortunately, the audio isn’t very well recorded. From the meters in the Audio panel,
you can see that this clip has two audio channels that are very low, and you can
probably barely hear Chris’s answers to the interviewer’s questions.
```
3 Open the Inspector (which opens in place of the Audio panel), select the File tab, and
```
scroll down to the Audio Configuration panel.
355Lesson 7 Project Setup and Preferences
This clip has two embedded audio channels, configured as Left and Right channels in a
single stereo audio track, displayed as “2 ch. - stereo” in the Format dropdown menu. A
“composite” waveform at the top of this panel displays a single amalgamated waveform
of all active audio tracks, with each individual audio track displayed underneath.
NOTE The Audio Configuration panel can display and allow you to preview up
to 36 audio tracks in a single clip.
You can scrub and play each of these waveforms separately using your mouse pointer
in order to be able to preview each track in isolation.
TIP Press Shift-S to toggle audio scrubbing.
As you scrub or play the audio channels for this clip, you should hear the Left and Right
channels play from the left and right speakers of your system, respectively.
356Lesson 7 Project Setup and Preferences
4 Click the Audio button in the top right of the interface to reopen the audio meters and
move the Inspector next to the media pool.
5 Select the first audio clip, A-002.WAV, and play it.
You’ll see that this clip has four audio channels, displayed as separate waveforms in the
audio viewer, all with healthy audio levels showing in the meters.
In the Info tab of the Inspector, you see the individual channels labeled “Mix-L,” “Mix-R,”
“Boom,” and “Chris.” This indicates that a boom mic was recorded on channel 3, Chris’s
personal mic was recorded on channel 4, and channels 1 and 2 are a mix of both.
357Lesson 7 Project Setup and Preferences
NOTE The track names have been imported as part of the audio files’
```
metadata. You can view specific track names (or add your own) by choosing
```
Audio Tracks from the Metadata panel’s Sort menu.
You will notice, however, that this clip is configured as “4 ch - adaptive” in the Format
dropdown menu. This means that although the clip has four separate channels with
different mics or mixes being recorded to each channel, if you were to edit this into a
timeline, the audio would be presented as a single clip. To get the most out of the
separate channels, you’ll need to change the audio configuration.
6 In the media pool, select all four audio clips: A-002.WAV, A-005.WAV, A-007.WAV,
and A-008.WAV.
7 In the Format dropdown menu in the Inspector, choose the option “4 ch - mono.”
358Lesson 7 Project Setup and Preferences
This changes the audio configuration of the selected clips so that each channel can
now be used separately and will appear as four tracks in the timeline.
Now that you have correctly configured the audio, you can sync the video and audio
clips together and choose the most appropriate channels to work with.
8 Right-click the selected AUDIO and VIDEO bins and choose Auto Sync Audio.
359Lesson 7 Project Setup and Preferences
The Automatically Sync Audio window opens, displaying several options for how you
want the audio synced with your video clips.
Synchronizing audio using matching timecode is always preferable because it’s quicker
and much more reliable. However, if your clips don’t have exactly matching timecodes,
using the waveforms is the next best option. This is why most clips that need
synchronizing like this will also contain some kind of “scratch” or reference audio to
make this process easier.
9 Select Waveform for the “Synchronize using” option and select the “Retain embedded
audio” and the “Retain video metadata” options.
NOTE When choosing to sync using waveforms, the “Use channel number”
option can be used to specify which audio channel you want to use for
syncing. This is useful if one audio channel has better audio than another.
Retaining the embedded audio means that Resolve will keep all the audio channels
active on the clip. This can be useful for verifying that the audio is in sync with the
original. However, if you don’t choose this option, the original embedded audio is not
```
deleted and is accessible through Clip Attributes (see below). You will use the metadata
```
of the video clip in later steps, so retaining the video metadata means that the
metadata of the audio files won’t override those of the video clips.
360Lesson 7 Project Setup and Preferences
10 Click Sync, and Resolve analyzes the audio.
Although nothing appears to happen beyond this, Resolve has successfully
synchronized the audio with the video clips. If the Auto Sync hadn’t been successful, a
warning dialog would have appeared indicating which clips couldn’t be synced.
11 Select the first video clip again, F002_08151648_C005.mov, and play it.
Now this clip has six audio channels, the last four of which are much higher in the
meters than the first two. These are the four channels of the audio clip that you have
just synced.
TIP You can verify that there is synced audio with each of the clips in List View
in the Synced Audio column.
You could continue using the audio of these clips as is. Having multiple audio tracks on
a clip allows you to choose which microphone to use at any given time. However, this
would result in you having to manage many more audio tracks in the timeline than is
necessary, so it can be just as simple to configure the audio of a clip so that it uses just
```
the track(s) you need.
```
361Lesson 7 Project Setup and Preferences
```
12 Command-click (macOS) or Ctrl-click (Windows) the AUDIO bin to deselect it and leave
```
just the contents of the VIDEO bin displayed in the media pool, and select all the
interview clips.
The Inspector shows the updated audio configuration for these clips.
362Lesson 7 Project Setup and Preferences
Now you can see that these clips all have a total of six audio channels: the first two
```
being the embedded audio channels (still configured as stereo), and the last four being
```
```
the linked audio clips (configured as mono). Since you only need the audio recorded
```
from Chris’s personal mic, you can remove the audio channels you don’t need.
13 Deselect the first two audio channels. As these are the original audio embedded in the
interview clips, there is one checkbox to disable both channels since they are currently
configured as a stereo track.
363Lesson 7 Project Setup and Preferences
14 Continue to deselect tracks 3, 4, and 5, leaving just Chris’s final audio track active.
15 Once again, play F002_08151648_C005.mov in the viewer, this time noting how only
one track is playing.
364Lesson 7 Project Setup and Preferences
NOTE Muting and disabling tracks in the Audio Configuration panel results in
two different things when the clips are edited into a timeline. Disabling the
audio track means the track is effectively “hidden,” so these tracks will not be
edited into a timeline. Muting an audio track in the Audio Configuration panel
means that that track will still be edited into the timeline but will be
automatically disabled. Disabled tracks like this can be re-enabled in the
```
timeline by right-clicking them and choosing Enable Clip (or by pressing D).
```
Advanced Audio Configuration Using Clip Attributes
Further configuration of the individual audio channels of a clip can be made by
choosing Custom from the Format menu in the Audio Configuration panel.
This opens the Clip Attributes window, where you can set the audio channels in
any combination of mono, stereo, or various multi-channel configurations such as
5.1 and Adaptive tracks.
Changes made to the configuration of audio channels will not affect any channels
currently in use in any timeline.
365Lesson 7 Project Setup and Preferences
Working with Metadata
Metadata has quickly become an important part of working with digital media files, not
least in the sorting and finding of specific clips in the morass of media in any given project,
and metadata is an integral part of working with DaVinci Resolve throughout the post-
production process.
You have many ways to populate your clips with useful metadata: it may be entered on the
```
camera during production; you can enter it manually in DaVinci Resolve; or someone on
```
set can be assigned to be responsible for entering metadata in their favorite spreadsheet
program or in any of the smart slate apps that can be used to log metadata such as shot,
scene, take, and more. You can then import this data into Resolve using the simple CSV
```
(comma-separated values) format. The benefit of understanding and utilizing metadata is
```
that you have a more intimate understanding of your media and will no doubt save
yourself hours of work and frustration!
Over the next few steps, you will explore each of these different pieces of metadata before
learning how it can be put to practical uses.
1 In the media pool, select the first interview clip in the VIDEO bin, F002_08151648_
C005.mov.
2 Scroll to the top of the Inspector to display the Metadata panel.
366Lesson 7 Project Setup and Preferences
The Inspector contains several common metadata fields. In this case, you can see
pieces of information that detail the camera number, reel, scene, and take. This is an
example of metadata that has been assigned in-camera when the clip was
originally recorded.
You can edit many of these fields to adjust or add your own metadata as needed.
```
3 In the media pool, select the B-ROLL bin and Command-click (macOS) or Ctrl-click
```
```
(Windows) your three favorite clips.
```
4 In the Inspector, click the Good Take checkbox.
367Lesson 7 Project Setup and Preferences
5 Click the media pool Sort menu and choose Scene to list the clips in order of their
scene number.
```
6 With the clips reordered, select the first four clips (from Scene 2).
```
368Lesson 7 Project Setup and Preferences
7 In the Inspector, type PINE TRAIL in the Comments field.
8 Click the media pool Sort menu again and choose Clip Name to reorder the clips in the
media pool by their names.
Simple Searches Using Metadata
Having just added your own simple pieces of metadata to these clips, you can now use it to
find these clips instantly.
1 In the bin list, select the Master bin.
```
2 At the top of the media pool, click the menu next to the Search button (the magnifying
```
```
glass) and choose All Bins.
```
369Lesson 7 Project Setup and Preferences
3 In the Search field, type soundtrack.
The music clip is displayed instantly because it has “soundtrack” in its name.
4 In the Filter By menu, select Comments.
5 In the Search field, highlight “soundtrack” and type pine to reveal the clips that have
the “PINE TRAIL” comment you added previously .
6 Click the “x” on the right side of the Search field to clear the current search.
370Lesson 7 Project Setup and Preferences
7 In the Filter By menu, choose Good Take.
```
8 In the Search field, type 1 to indicate the value should be “true” (active), and the clips
```
you marked as good a few steps earlier are instantly recalled.
NOTE To view all the clips you haven’t marked as Good Takes, type 0 in the
Search field.
```
9 Click the Search button (magnifying glass) to clear and close the Search field.
```
Resolve’s powerful and responsive search feature lets you leverage the flexibility of
metadata to find media pool clips in even the largest projects.
Creating Keyword Smart Bins
Not all possible metadata fields are available in the Inspector, which is why the dedicated
Metadata panel comes in handy. This is especially true when it comes to adding keywords
to your clips. You used keywords in Lesson 1 when you added B-roll clips to your rough cut
as an easy way of seeing just the relevant footage.
Creating a Keyword Smart Bin is as simple as adding a keyword to a clip.
1 In the media pool, click the B-ROLL bin and select the three clips of the girls walking
through Slot Canyon.
371Lesson 7 Project Setup and Preferences
2 From the top right of the interface, click the Metadata button to reveal the
Metadata panel.
The Metadata panel opens at the bottom right of the interface, in place of the
```
Inspector, which is moved up in place of the Audio panel (which is closed).
```
```
3 At the top of the Metadata panel, click the Sort menu (three lines with an arrow) and
```
choose “Shot & Scene.”
372Lesson 7 Project Setup and Preferences
This displays the metadata fields most closely associated with shot and scene
information.
```
Some of these fields are the same as those listed in the Inspector; indeed, they are the
```
same fields and are available in either of the two panels, and you will no doubt see the
same information listed twice.
373Lesson 7 Project Setup and Preferences
4 With the three clips still selected, type SLOT CANYON into the Keyword field of the
```
Metadata panel and press Enter (Return).
```
Your text is converted into a keyword that is assigned to the selected clips.
5 At the bottom of the Metadata panel, click Save.
NOTE You only need to save the metadata if you’re adding it to multiple clips
simultaneously.
374Lesson 7 Project Setup and Preferences
6 In the Smart Bins area of the media pool’s bin list, click the Keywords smart bin folder,
and then click the disclosure triangle to open the Keywords smart bins.
As soon as you added the “SLOT CANYON” keyword to the clips in the VIDEO bin, the
SLOT CANYON Keyword Smart Bin was automatically created, which then displays just
the clips with that keyword applied. You will learn how to display other automatic smart
bins like this later in this lesson.
TIP You can drag and drop clips onto an existing automatic smart bin to
quickly add the clips to that bin by automatically assigning the metadata
properties of the smart bin to the clips. For example, dragging a clip onto a
keyword smart bin will automatically add that smart bin’s keyword to the clip.
375Lesson 7 Project Setup and Preferences
Favorite Keyword Shortcuts
Rather than typing keywords each time you want to add them to a clip, you can set
up to nine favorite keywords in the Keyword Manager so you can quickly apply
certain keywords using keyboard shortcuts.
Choose Workspace > Keyword Manager to open the Keyword Manager and enter
the keywords you commonly use in the slots provided.
```
Once assigned, you can quickly add the keywords to any selected clip(s) by
```
choosing Mark > Favorite Keywords and selecting the keyword you want.
```
Alternatively, you can use the shortcuts Option-Shift-1 through 9 (macOS) or
```
```
Alt-Shift-1 through 9 (Windows) to apply the appropriate keywords to the selected
```
```
clip(s). Use Option-Shift-0 (macOS) or Alt-Shift-0 (Windows) to remove all keywords
```
```
applied to the selected clip(s).
```
Importing Metadata
As you can see, adding your own metadata to any of the clips in the media pool is easy,
and you can continue to enter metadata manually in this way. However, to make it easier
to see how useful metadata as a whole can be, you will import some additional metadata
for this project.
1 Choose File > Import Metadata To > Media Pool.
2 Navigate to R20 Beginners Guide / Lesson 07 and select the file OMO METADATA.csv.
376Lesson 7 Project Setup and Preferences
```
This .csv (comma-separated values) file was exported from a simple spreadsheet
```
program and contains additional Comments and Keyword metadata with which you
will update the clips in the media pool.
3 Click Open.
The Metadata Import dialog opens.
This window allows you to choose how you want Resolve to match the metadata in the
.csv file with the clips in the media pool and how you want to merge the metadata in
the .csv file with existing clip metadata. The default is to match clips based on their
filenames and starting and ending timecodes and only update metadata with entries
in the .csv file, although you can adjust these or use additional matching and merge
options as required.
In this case, the .csv file has both the required filename and timecode information, and
you will only need to update the metadata fields listed in the .csv file, so you don’t
need to change any of these options.
377Lesson 7 Project Setup and Preferences
4 Click OK.
A confirmation window states that the metadata import has successfully updated 20
clips with the new metadata from the .csv file.
You can verify that the information from the .csv file has been added to the media pool
clips by the new Keyword smart bins that have just appeared.
You can now explore this new level of organization applied to your clips in the media
pool, along with some newly added Comments, which you’ll be able to see in either the
Inspector or the Metadata panel. Hopefully, you might begin to see how all this
```
additional information can help you find the clip(s) you’re looking for.
```
378Lesson 7 Project Setup and Preferences
Exporting Metadata and Bins
In addition to importing metadata to clips in your media pool, as detailed in the
preceding steps, you can also choose to export the metadata from your media
pool or from selected clips from the media pool. To do so, simply choose File >
Export Metadata From > Media Pool, or choose File > Export Metadata From >
```
Selected Media Pool Clips (as appropriate). Your chosen clip metadata will then be
```
exported as a .csv file and will provide a way of easily transferring metadata from
one project to another that uses the same media, even if that project is on another
Resolve system.
You can also export an entire bin by choosing File > Export > Export Bin. This
```
command will export the clip metadata (not the media) from the currently selected
```
bin to a .drb file. As with exported metadata, you can use this option to transfer
bins between different Resolve projects or systems by choosing File > Import >
Import Bin.
Any clips listed in the .drb file will be automatically imported into the current
project, together with their associated metadata. If the source media is in the
same location as the system the bin was exported from, it will be automatically
linked to the newly imported clip. If the media is in a different location, you will
have to manually relink it as you did in Lesson 1.
Creating Custom Smart Bins
Using automatic smart bins only scratches the surface of what smart bins can do. In
addition to using the automatic Keywords smart bin, you can also create your own smart
bins using a simple set of and/or rules. In the next steps, you will create a smart bin to
automatically collect the clips you previously marked as Good Takes.
1 Choose File > New Smart Bin.
TIP You can also right-click the smart bin list and choose Add Smart Bin.
379Lesson 7 Project Setup and Preferences
The Create Smart Bin window appears.
Using this window, you set up the rules that determine which clips are automatically
added to this custom smart bin. There are many potential options, enabling you to
create smart bins that group clips based on a wide range of metadata.
2 In the Name field, enter GOOD TAKES as the name for this smart bin.
3 Leave the Match menu set to “All of the following rules.”
4 In the rule itself, leave the first metadata criteria set to “Media Pool Properties.”
5 Change the metadata type dropdown menu from “File Name” to “Good Take.”
TIP To navigate quickly through the list of options, begin typing the name of
the metadata field. You can then select it with your mouse to jump directly to it
from the list.
6 Leave the third and final metadata criteria dropdown menu set to “is true.”
The media pool will show the results of this rule, displaying the clips you previously
marked as Good Takes.
380Lesson 7 Project Setup and Preferences
7 Click Create.
You have now saved the search as a smart bin that includes all the clips that you
previously marked as Good Takes.
The content of a smart bin is always governed by the rules you set, so you cannot
simply drag clips to and from a smart bin. To add or remove clips from a smart bin, you
must either adjust the rules of the smart bin or adjust the clips’ metadata so it meets
or falls outside of the rules.
8 Select any clip in the Good Takes smart bin and uncheck Good Take in the Inspector to
instantly remove it from the smart bin. Alternatively, select any other clip from the
B-ROLL bin and click the Good Take option to add it to the Good Takes smart bin.
NOTE To edit the rules for an existing smart bin, right-click it in the bin list and
choose Edit to open the Edit Smart Bin window so you can review and adjust
```
the rules as necessary. Automatic smart bins (like the Keyword smart bins)
```
cannot be edited in this manner.
You can also set up additional rules when creating custom smart bins by using the
options to Match using All or Any of the listed rules you choose.
9 Choose File > New Smart Bin.
10 In the Name field of the Create Smart Bin dialog, type DAY ACTIVITIES.
11 Leave the Match menu set to “All of the following rules.”
12 Change the first field of the rule to “Metadata – Shot & Scene,” change the second field
to “Day / Night,” and leave the third field set to “contains.”
381Lesson 7 Project Setup and Preferences
13 In the final field, type day.
The media pool displays the results of the rule, displaying all clips that have “day”
entered in the Day / Night metadata field.
14 In the Create Smart Bin window, click the + icon to add another rule for the smart bin.
TIP For added flexibility, you can choose additional match options by
```
Option-clicking (macOS) or Alt-clicking (Windows) the Add Filter Criteria
```
button. This will add a new subset of rules that have their own All/Any options.
382Lesson 7 Project Setup and Preferences
15 In this new rule, change the second field to “Keywords,” and the third field to “contains.”
All the clips disappear from the media pool because you have not specified a keyword.
16 In the final field of the second rule, type activities.
NOTE This field is not case sensitive.
Using this second rule, you have further refined the contents of the smart bin by only
including the clips that have the keyword “activities.”
17 Change the Match dropdown menu to “Any of the following rules.”
383Lesson 7 Project Setup and Preferences
This time, the rules specify that the contents of the smart bin should display any clip
that has either “Day” in the Day / Night field or “activities” as a keyword.
18 Change the Match dropdown menu back to “All of the following rules” and click OK to
save the smart bin.
Organizing Custom Smart Bins
You can organize smart bins into folders to make them easier to find, in the same way that
all the Keyword Smart Bins are organized in the Keywords folder.
1 Right-click the Good Takes smart bin and choose Add Folder.
2 Select Folder 1 and rename it MY SMART BINS.
384Lesson 7 Project Setup and Preferences
3 Drag the Good Takes and Day Activities smart bins into the Custom Smart Bins folder.
Hopefully, you now have a much greater appreciation of the organizational power of smart
bins in DaVinci Resolve. Smart bins can be used to return results based on just about any
piece or combination of metadata you can find. This could be to find footage at a certain
resolution, footage shot on a particular date, or even footage stored on a certain hard
drive! The only limit to working with smart bins is your imagination.
Renaming Clips with Metadata
Clip names from a camera, or almost any capture device, are often an alphanumeric string
that typically includes the date and time that the clip was created. They are not always the
most descriptive names and often must be changed for editing purposes. Entering clip
```
names manually is one way to address this, but it is not the only way (or even the most
```
```
efficient way) to rename them.
```
Variables are references to other metadata that exist on the clip, such as scene, take, and
shot number—so called because variables are not the same for each clip. You can enter a
variable into the clip name, and Resolve will reference the correct information for each clip
```
(provided the information is present). You will use variables to change the generic names
```
of the clips in the media pool to more descriptive names based on their metadata.
```
1 Select the B-ROLL bin, select a clip, and press Command-A (macOS) or Ctrl-A
```
```
(Windows) to select all the clips in this bin.
```
385Lesson 7 Project Setup and Preferences
2 In the Inspector, click the Name field.
This field currently shows “Multiple Values” because you have many clips selected, all
with different clip names.
```
3 In the Name field, type % (percentage sign).
```
Entering % indicates that you are about to enter a variable. When you enter that %,
a list of variables appears.
386Lesson 7 Project Setup and Preferences
4 Type com.
A list of potential variables appears that contain the letters “com.”
5 In the dropdown menu, click Comments to add it to the Clip Name field.
6 Press the Spacebar to add a space after this variable, and then type %take and choose
Take from the list of variables.
7 Click away from the Name field.
The clip names now show a combination of each clip’s Comments and Take
metadata fields.
387Lesson 7 Project Setup and Preferences
Changing the clip names in this way does not change the names of the original media
files. Editors often use clip names within a project to provide a more user-friendly way
of identifying a clip or series of clips. Clip names are, of course, just one more piece of
metadata, so you can also use them when creating custom smart bins. EDLs, XMLs, or
AAFs generated from within Resolve will always reference the original filename.
TIP To switch between viewing the clip names and original file names across
the project, choose View > Show File Names.
You can also combine text that you enter along with the variables to create a more
descriptive clip name.
8 Select all the clips in the INTERVIEW keyword smart bin.
You could just as easily select the same clips from the VIDEO bin, but now that you
have them, you might as well use the smart bins.
9 In the Name field in the Inspector, type CL %Keywords Tk%Take, selecting the
options for Keywords and Take as they appear.
10 Click away from the Name field.
388Lesson 7 Project Setup and Preferences
Now all of Chris’s interview clips have been renamed with his initials and the clip’s
keywords and take number. Renaming clips with variables like this can save hours of
manual typing and provide clear, descriptive information about a clip without having to
dig deeper into its metadata.
TIP To reset any custom names you’ve applied to any clips, delete the text in
the Name field in the Inspector, and, because a clip must have a name, the
original filename will be substituted.
As you can see, coupled with an understanding of metadata, Resolve has some flexible
and powerful searching functions, so you should always be confident that you’ll be able to
find your media. One word of caution, however, is that metadata searches are only as good
as the quality of the metadata provided in the first place. Sometimes, a simple spelling
```
mistake (a mere typo) can thwart all these potential benefits!
```
Creating Subclips
Another technique commonly used when dealing with large amounts of footage, especially
long clips, is to create a series of subclips. You encountered subclips in Lesson 1 when you
edited soundbites from the interview, and the subclips made it easier to work with smaller
portions of footage rather than the very long interview clips they were taken from.
The important thing to remember about subclips is that, while they are created from a
longer clip, they refer to the same source media files on your system. As a result, they don’t
take up any more space on your system, regardless of how many subclips you create.
Also, while subclips will initially inherit the metadata of the clip they are created from, the
subclip itself is a completely independent clip. This means that you can store them in
different bins, and they can each have their own metadata.
NOTE In this exercise, you’ll create subclips in the media page. However, the same
techniques can be used to create subclips from clips in the source viewer on the
edit page.
389Lesson 7 Project Setup and Preferences
1 Select the INTERVIEW bin and choose File > New Bin or press Shift-Command-N
```
(macOS) or Shift-Ctrl-N (Windows) to create a new bin.
```
A new bin is created called Bin 7, because this is the seventh bin created in this project.
2 Rename the new bin SUBCLIPS.
3 Select all the clips in the VIDEO bin and drag them into the viewer.
4 Select the SUBCLIPS bin.
390Lesson 7 Project Setup and Preferences
5 Using the clip menu at the top of the viewer, ensure that CL INTERVIEW Tk5 is active
in the viewer.
6 Using the viewer’s Options menu, choose Show Audio Waveform on Source Clip to
display the clip’s waveform.
391Lesson 7 Project Setup and Preferences
7 Set an In point just before Chris says, “That’s what really inspires us…” and an Out point
after he says “…the design process starts.”
TIP You don’t need to be accurate when setting In and Out points for
subclips. In fact, setting them to include a little more than you intend to use is
```
a recommended technique (see the sidebar “Adjusting Subclip Limits” later in
```
```
this lesson).
```
```
8 Choose Mark > Create Subclip or press Option-B (macOS) or Alt-B (Windows).
```
The New Subclip window opens, asking you to confirm the name of this subclip, which
is the same filename as the original clip but with the word “Subclip” added to the end.
Don’t worry about the name of the subclip at this point.
392Lesson 7 Project Setup and Preferences
9 Click Create to add the subclip to the current bin.
10 From the viewer dropdown menu, choose the clip CL INTERVIEW Tk8.
11 Set an In point just before Chris says, “We want people to experience…” and an Out
point after he says, “…it’s changed my life.”
393Lesson 7 Project Setup and Preferences
```
12 Choose Mark > Create Subclip or press Option-B (macOS) or Alt-B (Windows).
```
13 Again, don’t worry about the name of the new subclip for now, just click Create in the
New Subclip window.
14 Continue playing the clip in the viewer and set an In and Out point around the next
notable soundbite, when Chris says, “Our brand is really a reflection of our community
and who we are.”
15 This time, drag the clip from the viewer into the SUBCLIPS bin in the media pool to
create the subclip.
16 Again, click Create in the New Subclip window.
394Lesson 7 Project Setup and Preferences
17 Continue playing the clip in the viewer and set another In and Out point around Chris’s
final soundbite: “That’s why we say experience the southwest.”
18 Choose your preferred method for creating a subclip from this last soundbite and click
Create in the New Subclip window.
You now have four subclips in the SUBCLIPS bin.
Modifying Subclip Metadata
Now that you’ve created the subclips, you can use some of the metadata tricks you learned
throughout this lesson.
1 Select the first subclip and, in the Metadata panel, type inspiration in the
Description field.
2 Select the second subclip and type Experiences in the Description field.
395Lesson 7 Project Setup and Preferences
3 Select the third subclip and type Brand in the Description field
4 Select the final subclip and type #EXSW in the Description field.
5 Select all the clips in the SUBCLIPS bin and, in the Metadata panel, delete the
INTERVIEW keyword and type SUBCLIP in the Keyword field. Click Save at the bottom
of the Metadata panel.
6 In the Name field in the Inspector, type CL %Keywords - %Description, selecting the
metadata options from the menus as they appear.
7 Click away from the Name field, and the subclips are now all renamed using the
appropriate metadata.
You can now edit using these subclips just like any other clip, as you did in Lesson 1.
NOTE When you used these subclips in Lesson 1, each subclip was given a shot
number that was also added to the clip name so that they were ordered naturally
for you to work with them.
Adjusting Subclip Limits
One limitation of a subclip is that, even though it references the original source
media file, it is limited to the initial In and Out points you used to create it.
Therefore, it’s good practice to set your initial In and Out points a little before and
after the portion you want to subclip, thereby leaving a little wiggle room when
you later trim the clips in the timeline.
However, when you find that you need a few extra frames not included in your
subclip, you can always extend the limits of a subclip by right-clicking a subclip and
choosing Edit Subclip.
This allows you to adjust the start and end timecodes for the subclip, updating the
limits of the subclip in both the media pool and the timeline simultaneously.
396Lesson 7 Project Setup and Preferences
You should now have a good understanding of just how powerful Resolve is at helping
you organize your projects. Remember, while some projects may require much more
organization than others, the techniques demonstrated throughout this lesson can be
applied at any point in a project and in many cases can be applied as readily in the edit
page as they can in the media page. Project organization doesn’t just occur once at the
```
start of a project; it is something that you will constantly refine as you continue working.
```
Preferences
So far in this lesson, you have learned how to set up a project correctly, explored different
ways of importing clips, and learned how to organize media to make it easier to work with.
Now it’s time to learn more about how to customize DaVinci Resolve through its preferences.
DaVinci Resolve includes two sets of preferences that you can configure: System
Preferences are a group of settings that control how Resolve uses your computer
hardware. User Preferences affect how Resolve works for you, the user.
Like the Project Settings window, the preferences contain a large and bewildering number
of options. However, there are only a few important preferences you should be aware of.
1 Choose DaVinci Resolve > Preferences to open the Preferences window.
397Lesson 7 Project Setup and Preferences
The two types of preferences—System and User—are listed at the top of the
Preferences window and, like the Project Settings window, categories are listed along
the left side. By default, the Preferences window opens to the Media Storage category
in the System Preferences, unless the project hasn’t been closed since the Preferences
window was last opened.
The Media Storage preferences allow you to manage various media storage locations
that DaVinci Resolve can access. These can be used to access files easily in the media
storage browser in the media page for importing, but the first location in this list is
```
also used to store gallery stills you create in the color page (see Lesson 5) and cache
```
```
files generated in the edit page (see Lesson 2). This location is more commonly
```
referred to as a scratch disk. By default, this location is always set to the current user’s
Movies folder because this location should automatically exist on every computer. This
location also serves as a default for the Working Folders in Project Settings, except for
the Project Media Location.
NOTE It’s almost always advisable to set the first media storage location to
the largest, fastest hard drive available to your computer. However, for the
purpose of following this book, it is not necessary to change the
current location.
If you wish to change or add a media storage location, click the Add button and select
the hard drive or folder you wish to add as a media storage location. To remove an
unwanted media storage location, simply select it in the list and click Remove.
2 Ensure that “Automatically display attached storage locations” is selected.
This option is important since it will allow hard drives and other storage media you
connect to your computer to be instantly available in the media page so you can import
any files stored on them directly into Resolve and begin working as quickly as possible.
NOTE If you’re working on macOS and have downloaded DaVinci Resolve or
DaVinci Resolve Studio from the Mac App Store, you will need to select this
option and give permission for Resolve to access your hard drive. Unless you
do this, Resolve will be unable to import any footage.
398Lesson 7 Project Setup and Preferences
3 Click the Video and Audio I/O group.
NOTE I/O refers to Input/Output.
If you have a Blackmagic Design capture or playback device attached to your
computer, such as a Decklink PCI Express card or UltraStudio device, you will be able to
specify this as a capture and/or monitor device here. Specifying such a supported
device as a monitor device will allow you to play the current timeline out to an external
video monitor. If you do not have a supported device attached to your system, the
Capture and Monitor device options will not be selectable.
399Lesson 7 Project Setup and Preferences
4 Click the Control Panels group.
As with the Video and Audio I/O settings, this is where you can specify which type of
control panel you want to use for color grading and detail any other hardware
controllers you have attached to your computer, such as a Speed Editor keyboard.
400Lesson 7 Project Setup and Preferences
In addition to the Blackmagic Design Micro, Mini, and Advanced Panels,
DaVinci Resolve also supports a range of panels from other manufacturers.
NOTE If you have control panels attached to your system, you will also see a
status icon next to the Project Manager button in the main interface, which
you can click to see the controllers’ current status.
5 Click the Internet Accounts group.
401Lesson 7 Project Setup and Preferences
This is where you can sign in to supported video sharing and social media services.
Signing in to any of these services will allow DaVinci Resolve to upload an exported
file to that service on your behalf from the appropriate Quick Export preset of the
Deliver page, which you will explore in more detail in Lesson 10, “Delivery and
Media Management.”
6 At the top of the Preferences window, click the User tab.
The first group of User Preferences that is selected is the UI Settings. These allow you
to customize the user interface of DaVinci Resolve. For example, here you can change
the language that the user interface uses.
TIP Many colorists like to enable the “Use gray background for user interface”
option. This creates a more neutral interface that helps you concentrate on the
images as you’re grading.
402Lesson 7 Project Setup and Preferences
7 Click the Project Save and Load group.
You might have been wondering why this book makes no mention of saving your work
as you go along, especially if you’ve ever been in a situation where the software you
are working in has crashed, causing you to lose work and valuable time.
Well, thankfully, this isn’t something you ever have to worry about when working in
DaVinci Resolve because everything you do is automatically saved as soon as you do it!
The explanation for this is a feature called Live Save, which is found in the Project Save
and Load group of the User Preferences, and which is enabled by default.
With Live Save enabled, once you create a new project in the Project Manager,
DaVinci Resolve begins saving all the changes you make as soon as you make them.
If there is ever a problem, such as the software crashing or the power to your
```
computer being interrupted (assuming it’s not a laptop with a charged battery, of
```
```
course), simply restart DaVinci Resolve and reopen the project. You will not have lost
```
any work as long as Live Save is enabled.
```
8 Ensure Live Save is enabled (it should be by default).
```
403Lesson 7 Project Setup and Preferences
You will also notice there is an option here for timeline backups. You were introduced
to using timeline backups in Lesson 2, but here in the User Preferences you can specify
how often DaVinci Resolve makes those backups and where they are saved.
The default is to save a timeline backup every 10 minutes. After an hour of backups has
```
been reached (six backups at 10-minute intervals), an hourly backup is saved, and the
```
older backups for the previous hour are discarded as new backups are created. This
means you’ll only ever have six backups for the last hour you’ve been working.
Once hourly backups start to be made, the Hourly Backups value becomes relevant.
Again, the default is to save the previous two hourly backups, with older backups being
discarded as newer ones are created.
The very last backup created on any given day then becomes the daily backup, and,
again, the previous two daily backups are saved, with older backups being discarded
as newer ones are created. If you are working on a project over a longer stretch of
time, you can always increase this value so you always have a daily backup stretching
as far back as you feel comfortable with.
Timeline backups are saved in the Backup Location detailed here. However, there are
no user-manageable files in this location, and timeline backups should always be
restored as detailed in Lesson 2.
NOTE Although not enabled by default, if you want to have incremental
backups of an entire project made automatically, simply enable the Project
Backups option. Once enabled, projects are backed up using the same
periodic intervals as timelines are backed up. To access available backups for a
project that has this feature enabled, simply right-click the project in the
Project Manager window and choose Project Backups, where you can choose
to delete any unwanted backups or load a previously saved backup of the
project. When loading a backup project, you will be prompted to name the
project because Resolve will not overwrite the current version of the project.
404Lesson 7 Project Setup and Preferences
9 Click the Editing group for the User Preferences.
This group of settings allows you to customize many editing features you used in the
first three lessons. For example, the New Timeline Settings allow you to specify the
starting timecode, the number of video and audio tracks, and the Audio track type
used when creating a new timeline.
The Automatic Smart Bins category allows you to choose which automatic smart bins
you want to be active in the media pool.
405Lesson 7 Project Setup and Preferences
10 Click to enable “Automatic smart bins for scene metadata” and click Save to save and
close the User Preferences window.
A new set of automatic smart bins is now active, called Scene.
11 Select the Scene smart bin folder and click the disclosure triangle to open the Scene
smart bins.
Now each clip in the media pool is automatically grouped based on the Scene
metadata of the clip. This can often be added to the recorded files during filming.
```
12 Press Command-, (comma) in macOS or Ctrl-, (comma) in Windows to reopen the User
```
Preferences window.
406Lesson 7 Project Setup and Preferences
13 Scroll down to see more Editing preferences.
The General Settings allow you to adjust the standard transition and still-image
durations, in either seconds or frames, along with other specific options you can
choose to enable, such as having the timeline viewer overlay retain the last editing
action, rather than always defaulting to Overwrite.
TIP If you’re working on macOS, you also have the option to enable
DaVinci Resolve to automatically create keywords from Finder tags when
importing media.
Once you’ve finished exploring the System and User Preferences, you must save your
preferences, or else any changes you have made will be lost.
14 Click Save to close the Preferences window.
407Lesson 7 Project Setup and Preferences
NOTE Changing some options in the preferences will not take effect until you
restart DaVinci Resolve. A dialog will appear informing you if that is the case.
Resetting and Saving Preferences
```
Using the Options (…) menu in the top right corner of the Preferences window, you
```
can choose to reset the System or User Preferences back to their defaults.
For the User Preferences, you can also save the current set of preferences as a
preset, which can then be exported as a self-contained file with the
.userprefs extension.
If required, this file can then be imported to another DaVinci Resolve system,
where you can use the same Options menu to load it as a new preset, making it
easy to transfer your preferred user preferences between different systems.
Exploring Keyboard Shortcuts
```
Although you had a choice during the Quick Setup phase (see the “Getting Started” section
```
```
at the beginning of this book) to choose from a set of default keyboard shortcuts, you can
```
always further customize the different keyboard shortcuts used throughout Davinci
Resolve. Although the default keyboard shortcuts are extensive and cover a wide range of
functions, they might feel unnatural to you, or there might be a function that doesn’t have
a keyboard shortcut assigned by default that you find yourself using on a regular basis.
408Lesson 7 Project Setup and Preferences
1 Choose DaVinci Resolve > Keyboard Customization or press Option-Command-K
```
(macOS) or Alt-Ctrl-K (Windows).
```
The Keyboard Customization window opens, where you can choose which set of
keyboard shortcuts you want to use, discover which keyboard shortcuts are available,
or create your own custom keyboard shortcuts.
DaVinci Resolve provides a set of presets that emulate the various keyboard shortcuts
```
used by other nonlinear editing (NLE) systems.
```
2 Click the dropdown menu in the top right corner of the Keyboard Customization
window to reveal the options.
If you’re familiar with any of the listed NLEs, you can load the appropriate preset.
However, note that this is not a 100% remapping of the shortcuts. Because each
system operates slightly differently, some functions available in one or more of these
other systems may not be available in DaVinci Resolve. Therefore, it is impossible to
```
map the shortcut to the non-existent function; or DaVinci Resolve may include
```
409Lesson 7 Project Setup and Preferences
functions not available in these other systems, and the shortcuts assigned by default
in the DaVinci Resolve preset may be overridden in the other settings. It is always
worth exploring and learning the default keyboard shortcuts since they have often
been thought out carefully for you to get the best out of the software.
Nevertheless, there are times when you will want, and even need, to customize
the shortcuts.
The upper part of the Keyboard Customization window provides you with an
interactive keyboard for exploring keyboard shortcuts.
```
Keys that do not have an assigned function are displayed in a dark shade; those that
```
do have an assigned function are a slightly lighter shade. The keys displaying a number
at the bottom right represent keys that have functionality in more than one page.
You can begin exploring the functions by selecting the keys on the keyboard.
3 Click the D key using the onscreen keyboard.
410Lesson 7 Project Setup and Preferences
TIP You can hold down keys on your physical keyboard for a more interactive
experience.
As you can see, the Keyboard Customization window responds to the selection you
make and, in the Active area in the bottom half of the window, displays the function
assigned to this keyboard shortcut, next to the panel in which you can use it. In this
case, the D key will toggle the Enable Clip function in the edit page timeline and in the
Fairlight timeline.
You can also explore the keyboard shortcuts that utilize the different modifier keys for
your system.
4 Click the D key again on the onscreen keyboard to deselect it and then click the
Shift button.
The Shift buttons for your keyboard layout are highlighted and the mapping shifts to
reflect the shortcuts that are available while holding the Shift key.
411Lesson 7 Project Setup and Preferences
5 Click the D button again to reveal the function activated by the Shift-D key
combination.
As you are already aware, Shift-D bypasses the grades on all clips and works across the
application.
6 Click the D and Shift buttons again to deselect them.
Searching Keyboard Shortcuts
Instead of discovering the command associated with a shortcut, it’s much more common
```
to search for a command to discover what keyboard shortcut (if any) is assigned.
```
1 In the Commands area in the lower right portion of the Keyboard Customization
window, ensure that the All Commands group is selected.
TIP Instead of choosing All Commands, you can narrow your search to
specific menus or panels using the options in the left list of the Commands
area. Scroll down this list to see more options.
412Lesson 7 Project Setup and Preferences
2 Click the Search field and type sync to perform a search for commands that include
“sync” in their description.
It seems Auto Sync Audio does not have a shortcut assigned under the default
keyboard shortcuts.
3 Click the area in the Keystroke column for the Auto Sync Audio command.
Once selected, you can now choose to assign a shortcut by pressing the appropriate
keys on your keyboard.
413Lesson 7 Project Setup and Preferences
```
4 Press Option-Shift-A (macOS) or Alt-Shift-A (Windows) to assign that key combination to
```
the Auto Sync Audio command.
Each command can have multiple keyboard shortcuts assigned. If you wish to add
```
more than one keyboard shortcut to the same command, click the + (plus) icon to add
```
another keystroke combination. You can also remove shortcuts from a command by
clicking the x next to the keystrokes. To reset the keystrokes for a command back to
their defaults for the current layout, click the reset arrow to the right of the keystrokes
```
(visible when your mouse pointer is over the command).
```
NOTE If you choose a keystroke combination that is already assigned to a
command, Resolve will warn you and give you the choice of whether you want
to continue to assign that keystroke. If you choose Assign, the keystroke will be
removed from the original command and will be applied to the new command.
Resetting the keystrokes for a command will also reassign the keystroke back
to the original command.
```
You have chosen a new keystroke combination for the Auto Sync Audio command;
```
however, you will need to save it before you can use it.
5 Click Save.
The Keyboard Mapping Preset window opens, asking you to save the changes to a
new, customized preset.
414Lesson 7 Project Setup and Preferences
NOTE DaVinci Resolve will not allow you to alter the default mapping presets,
so if you wish to return to an unadulterated set of keyboard shortcuts, you can
simply select the DaVinci Resolve preset.
6 In the Enter Preset Name field, type My Shortcuts and then click OK.
The new mapping preset containing your customized shortcut has been added to the
dropdown list of presets.
In the future, when this shortcut preset is active, you’ll be able to press Option-Shift-A
```
(macOS) or Alt-Shift-A (Windows) to enable the Auto Sync Audio command for
```
selected clips.
```
NOTE To manage the mapping presets, click the Options (…) menu in the top
```
right of the Keyboard Customization window to reveal commands for
exporting, importing, and deleting available presets.
7 To return to the default shortcuts, select the DaVinci Resolve preset.
You should now have a clear understanding of how to set up your projects correctly and
customize the preferences to your requirements at both the system and user levels.
415Lesson 7 Project Setup and Preferences
Lesson Review
1 True or False? All media files must be organized into different folders on your hard
drive before you import them into DaVinci Resolve.
2 What happens to your media files when they are imported into DaVinci Resolve?
```
a) The files are converted to high-quality files for color grading
```
```
b) The files are copied to the first media storage location listed in System Preferences
```
```
c) DaVinci Resolve creates a link to the media files but does nothing to the files
```
themselves
3 What type of information is used by Smart Bins?
```
a) Metadata
```
```
b) User Data
```
```
c) System Data
```
4 Where is the Live Save option located?
```
a) User Preferences
```
```
b) System Preferences
```
```
c) Project Settings
```
5 Which page provides the most flexibility for importing clips into the media pool?
```
a) Cut page
```
```
b) Edit page
```
```
c) Media page
```
416Lesson 7 Project Setup and Preferences
Answers
1 False. Media files should be placed on a large, fast hard drive attached to your system
but do not need to be organized beyond that. However, if they are organized into
folders, you can replicate that folder structure as a series of bins when you import
the clips.
```
2 c). DaVinci Resolve creates a link to the media files but does nothing to the files
```
themselves.
```
3 a). Smart Bins utilize the metadata of clips.
```
```
4 a). Live Save is located in the User Preferences, in the Project Save and Load group.
```
```
5 c). The media page provides the most flexibility for importing clips, although clips can
```
be imported and organized using the cut and edit pages too.
417An Introduction to Audio Post and Sound Design
An Introduction
to Audio Post and
Sound Design
Chances are you’ve heard the adages “Seeing is believing” and “A picture is worth
a thousand words.” However, when it comes to motion pictures, both the visuals and
soundtrack are equally important. In fact, a great soundtrack sells the onscreen illusion,
manipulates emotions, transports the audience into the scene, and captivates their
imagination. A lousy soundtrack, on the other hand, keeps the audience at a distance,
distracts from the story, and draws attention to production flaws, performance issues,
and plot holes.
Audio post-production is much more than simply adjusting volume levels and mixing
tracks. Transforming production sound into a powerful soundtrack requires time, technical
skill, creative vision, and execution, as well as a full set of professional audio tools. The
good news is that DaVinci Resolve includes the tools to create a professional soundtrack
from start to finish. Before you dive into the following chapter, it’s a good idea to
understand the audio post-production process and workflow.
Keep in mind that many elements affect the workflow you’ll use: the type of project,
budget, format, length, deliverables, and distribution methods often dictate the size of the
post audio team, amount of time, and tools available to get the job done. This introduction
focuses on the fundamental post-production audio processes necessary for both narrative
and documentary style projects. Although the following pages explain the different jobs
and stages in audio post-production, having the Fairlight page built into DaVinci Resolve
means that you can perform the same steps on your projects with no additional crew
or budget.
418An Introduction to Audio Post and Sound Design
What Is Audio Post-Production?
Let’s start with a few basic terms. Audio post-production refers to the process of making a
soundtrack for moving images. Notice the use of “moving images,” which encompasses all
projects great and small, from blockbuster theater movies to streaming videos and
everything in between. A soundtrack is simply the audio that accompanies a
finished project.
How your audience experiences the finished project is greatly influenced by the
soundtrack. In fact, a well-executed soundtrack may go unnoticed for hours by the
audience while they are immersed in the show. On the other hand, it takes only a few
seconds of an amateurish or sloppy soundtrack to lose the audience not only from the
story but possibly from the theater or to a different channel.
If you’ve ever recorded or watched a home movie, especially one shot at an exciting public
place such as a beach or an amusement park, then you have firsthand experience with
some of the inherent challenges in both recording and listening to natural production
sound. All those excess environmental sounds and distractions create a need for audio
post-production to transform raw sound into successful soundtracks with clear dialogue,
realistic effects, and lush acoustic soundscapes wrapped in an emotionally powerful score.
What Is the Audio
Post-Production Workflow?
Since the advent of sync’d sound in motion pictures, the first rule of audio post has been
“Never start working on audio until the picture is locked.” “Locked” suggests that there will
be no more changes to the picture edit from this point forward.
In reality, changes always happen. Why does this matter? Because soundtracks must
maintain a frame-accurate relationship with the picture to stay in sync. If they are off by as
little as one or two frames, the sight and sound will be noticeably out of sync—a situation
that is distracting, unprofessional, and likely to lose your audience.
In a traditional post-production workflow, changes to the locked picture have a cascading
snowball effect on audio post. But when you’re working with DaVinci Resolve, which is the
```
only professional editing software that includes a full digital audio workstation (DAW),
```
no matter what editing changes are made, you can update your project immediately and
efficiently. This gives you tremendous creative flexibility if you are working on your own
because you can go back and forth between editing picture, audio work, and color
correction as often as needed.
419An Introduction to Audio Post and Sound Design
For larger productions, DaVinci Resolve solves the issue of updating, transferring files to
other systems, and conforming projects between editorial and audio post because editing
and audio post-production are done in the same project without ever leaving the
application. Best of all, audio post-production can start on the exact same timeline that the
editor used so you have zero chance of losing frames or getting out of sync. Once audio
post begins, the editor can use a duplicate timeline to make any new changes. Then the
audio editor can easily merge the changes between timelines with DaVinci Resolve’s
powerful timeline comparison tool.
DaVinci Resolve provides the audio tools needed for the highest-quality audio post-
production and is ideal for small projects yet powerful enough for big Hollywood studios
and broadcast productions to use as well. Whether you’re working on your own or with
a large post-production team, you can easily migrate projects to a large facility for
experienced audio sound designers and engineers to mix and master the soundtrack.
Now, let’s break down the different phases and jobs in a traditional audio post-production
workflow. With DaVinci Resolve, you can perform all these steps as needed by yourself or
with a team of audio professionals on your own projects.
Spotting the Soundtrack
```
A spotting session is when the supervising sound editor and the sound designer (often
```
```
the same person) sit down with the director, editor, and composer to look for soundtrack
```
elements that need to be added, fixed, or re-recorded. Notes from a spotting session are
combined into a spotting list that details music cues, important sound effects, dialogue
fixes, and additional audio notes.
DaVinci Resolve has simplified these spotting sessions with the timeline markers that you
can use in either the edit page or Fairlight page. The index in the edit and Fairlight pages
serves as an interactive spotting list that not only includes information for each marker but
also moves the playhead to the selected marker’s position in the timeline.
Production Dialogue Editing
Dialogue editing is the tedious, behind-the-scenes task of splitting dialogue into separate
tracks, removing unwanted sounds, replacing individual words or phrases for clarity, and
balancing separate clip audio levels for consistency. Why go to all that trouble? Because
spoken words are as important to a soundtrack as the lead vocals in a hit song. Keep in
mind that dialogue editors are responsible for all spoken words, including dialogue,
narration, and voiceover.
420An Introduction to Audio Post and Sound Design
Production dialogue editing starts with creating separate tracks for each character, and
then moving all those dialogue clips into a specific track. This crucial step is necessary
because each voice in a production is different and therefore must be processed
individually with volume normalization, equalization, and effects specific to that voice.
Next, the dialogue editor cleans up the tracks and removes any unwanted human sounds
```
(like tongue clicks and lip smacks). If a distracting sound can be physically cut out, this is
```
the time to do it. Plug-ins and effects can help eliminate unwanted clicks, pops, and noise
automatically, but be aware that any processing you add to a clip can affect a voice as well.
After the dialogue is cleaned up, the volume levels are balanced to be consistent on each
dialogue track. If dialogue can’t be used because it is damaged, noisy, or unclear, it must
be re-recorded or replaced with audio from other takes. The process of re-recording
```
production dialogue is called automatic dialogue replacement (ADR), or looping.
```
Dialogue editing can be time consuming and laborious. Once again, DaVinci Resolve
includes easy navigation, precision editing tools, and shortcuts that can simplify and
speed up the process.
Sound Design and
Sound Effects Editing
Once the dialogue editing is finished, the creative process begins! The sound designer’s
```
creative input to the soundtrack is like that of the director of photography (DP) for the
```
picture. Sound designers are responsible for the overall acoustic experience for the
audience. They also oversee the many individual tracks of sound and music that make up
the soundtrack. These audio tracks include dialogue, ambience, hard sound effects,
```
and foley sounds (as defined below).
```
Not only do sound designers determine the aural illusion and mood of the soundtrack, but
they also create, record, and enhance sound elements that only exist in their imagination.
After all, many projects need sound effects that don’t exist in the real world. Where do you
go to record dragons, aliens, or zombies? Those sounds must be created or designed from
scratch using a combination of real sounds, simulated sounds, and a lot of processing
and effects.
421An Introduction to Audio Post and Sound Design
While the sound designer determines the depth and detail of the sound effects tracks,
the sound effects editor places each sound effect in corresponding tracks. Sound effects
fall into four main categories:
— Natural sound, also known as nat sound or production sound, is anything other than
dialogue recorded by a microphone on location during the shoot.
— Ambience, or ambient sound, is the realistic conglomerate of sounds that establish
a location, such as waves crashing rhythmically and seabirds chattering for remote
seaside ambience.
— Hard sound effects are so named because they need to be physically sync’d to
picture and are necessary for the story or scene. Hard sound effects are typically
elements like door slams, car horns, and face slaps
— Foley sound consists of any character-driven sound effects caused by characters
interacting with their onscreen environments. Foley sounds are named after Jack Foley,
a legendary sound editor at Universal Studios, who originally developed the technique
of recording reenactments on a stage. Foley sound replaces the original production
audio for everything from fistfights to footsteps and clothing movement.
Audio editing tools in DaVinci Resolve’s Fairlight page are designed specifically for the
precision editing and placement required when editing sound effects. And
DaVinci Resolve’s clip speed changes are perfect for advanced sound design and
pitch effects.
Music Editing
Music editing involves placing different music elements into the soundtrack to enhance
the mood or story. All soundtrack music falls into one of two categories: music occurring
within the scene that the characters can hear, called source music or diegetic music, and
non-diegetic music that is added in post for the benefit of the audience—e.g., the
background score.
Diegetic music needs special attention to make sure that the volume levels, placement,
effects, and presence fit the context of the scene.
Non-diegetic music added in post-production for emotional effect or impact includes the
score, stingers, and stabs. Stingers are singular notes or chords that build tension and
suspense. Stabs are quick bursts of music that work like an exclamation point to draw
attention to something or someone in the story or narration.
422An Introduction to Audio Post and Sound Design
Enhancing and Sweetening Tracks
Once the dialogue tracks are edited and the sound effects and music added, it’s time to
make subtle improvements to the sound of each track so that they work in context with
the other tracks in the mix. The tools used to improve the sound in a track are similar in
many ways to the tools that colorists use to improve individual shots within a scene.
Because you are learning to use DaVinci Resolve, and color correction is an integral part
of the post-production process, it seems fitting to show the similarities between
adjusting audio and color.
For all intents and purposes, this process could be called “audio correction.” You
manipulate four fundamental elements to enhance or “sweeten” audio tracks, so they work
together as intended in the final mix: volume level, dynamics, pan, and equalization.
DaVinci Resolve controls all four of these elements on every track without the need for
additional plug-ins or patching.
— Volume controls are used to adjust the loudness of a track on a decibel scale and are
```
similar to luminance (brightness) because both volume and luminance have strict
```
broadcast standards and are usually the first thing the audience notices in each scene.
Volume levels can be adjusted on each clip, track, and the main output, just as
```
luminance (black and white levels) can be adjusted on individual clips, scenes, and
```
output. In DaVinci Resolve, you can change the volume level of a clip in the timeline or
Inspector. Track volume is controlled by faders in the mixer. You can also change the
volume levels over time using automation.
— Dynamics controls adjust the dynamic range, which is the difference between the
loudest peaks and quietest moments in a track. A track’s dynamic range is very similar
to video contrast within a shot. A track with a high dynamic range has very loud and
quiet elements within the track, such as a character whispering and then screaming in
the same scene. A low dynamic range would be rather flat, such as a commercial
voiceover in which the volume level of the talent is very even from start to finish. If you
have ever worked with a Waveform or Parade scope in the color page, controlling a
track’s dynamics is very similar to adjusting the white and black levels of a clip. Just
```
think of white as the loudest you can get (-3 dB) and black as the quietest.
```
— The Fairlight page mixer includes the four most common dynamics controls in one
easy-to-use panel. The compressor is used to narrow the dynamic range by lowering
the loudest peaks and bringing them closer to the lowest peaks. The expander, in
contrast, expands the dynamic range to increase the difference between the loudest
and quietest peaks. The limiter and gate both work as acoustic “brick walls” to limit
```
sound from exceeding a target level (limiter) and to prevent sounds lower than a set
```
```
threshold from being heard (gate).
```
423An Introduction to Audio Post and Sound Design
— Pan controls place the sound of a track within a panoramic stereo field. These
controls are used to compose the acoustic experience just as a cinematographer
composes the visuals of a shot. Tracks can be precisely located anywhere from left to
right to sound as if they come from an offscreen source, or somewhere within the
frame. DaVinci Resolve includes advanced pan controls in both the edit page and
```
Fairlight page with both 2D (stereo) and 3D sound placement for surround
```
sound systems.
```
— Equalization (EQ) controls manipulate specific frequencies to enhance the overall
```
sound, and are just like working with color, saturation, and hue in color correction. For
example, the human voice is based on a fundamental frequency shared by millions,
while the additional frequencies add tonal qualities to “color” the voice and make it
unique and recognizable. The primary function of equalization is to lower frequencies
that detract from the voice and boost the positive frequencies to improve the overall
sound. The Fairlight page mixer includes a six-band parametric equalizer on each track,
which is the perfect tool for enhancing and “sweetening” audio tracks.
Mixing and Mastering
The last step of audio post is mixing the tracks and mastering the output. If all the other
steps were completed prior to the mix, the process is straightforward. The goal of mixing
and mastering is to balance the levels coming from each track, so they sound good as a
whole. This is accomplished by making subtle changes to the track levels or combining
similar tracks into submixes to make them easier to control with one fader. The final master
needs to sound great and meet delivery standards for loudness. Fortunately, the Fairlight
page includes everything you need to mix tracks and loudness meters to make sure the
levels are right on target.
Now that you understand some of the technical steps and creative tools that are essential
in an audio post-production workflow, you can dive in to the next lesson and start putting
them to use on your own projects!
424This p age is intentionally left blank
Time
This lesson takes approximately
75 minutes to complete.
Goals
Setting Up the Project 426
Preparing the Timeline 428
Exploring the Fairlight Interface 433
Setting Track Formats
and Clip Channels 437
Trimming Clips in Fairlight 440
Using the AI Dialogue Leveler 442
Applying EQ 449
Adding Sound Effects 455
Using Scrollers 459
Aligning Sound Effects 467
Mixing the Soundtrack 473
Ducking the Music 479
Lesson Review 491
Lesson 8
An Introduction
to Fairlight
By now, you’ve probably heard that
sound is half of the video experience.
In the words of George Lucas,
“Filmmakers should focus on making
sure the soundtracks are really the
best they can possibly be. Because in
terms of an investment, sound is where
you get the most bang for your buck.”
The Fairlight page in DaVinci Resolve
is designed specifically for audio
to accompany pictures, realizing
cinematic-quality sound for your
productions. Most importantly, since
it is built right into your editing,
grading, and visual effects application,
you can freely refine the edit, create
visual effects, grade the pictures, and
mix sound, right up until the time of
your final delivery. This integration is
what makes DaVinci Resolve a game-
changer for filmmakers of all levels.
426Lesson 8 An Introduction to Fairlight
In this lesson, you’ll learn how the Fairlight page can enhance your audio work, whether
that’s working at a higher level of detail than in the edit page or helping you sync sound
effects to onscreen action easier than ever before.
Setting Up the Project
In this lesson, you will revisit the edit you were working on in Lesson 3, the short promo
video for Organ Mountain Outfitters, and you will start by importing a version of that
project and relinking the media files.
1 Open DaVinci Resolve and, in the Project Manager, click the Import button.
2 Navigate to R20 Beginners Guide / Lesson 08. Select the
OMO PROMO FAIRLIGHT.drp project file and click Open.
3 Once it has been imported into the Project Manager, double-click the OMO Fairlight
project to open it.
4 If necessary, click the Edit button or press Shift-4 to switch to the edit page.
5 Choose Workspace > Reset UI Layout.
6 From the top of the timeline viewer, open the timeline OMO FAIRLIGHT.
You will see that all the clips are currently offline and will need relinking.
427Lesson 8 An Introduction to Fairlight
7 Click the Relink Media button at the top of the media pool.
8 In the Relink Media window, click Locate.
9 Navigate to the R20 Beginner Guide folder and click Open to allow Resolve to search
the folder and locate the media files.
10 Play the OMO FAIRLIGHT timeline to refamiliarize yourself with the Organ Mountain
Outfitters promo.
428Lesson 8 An Introduction to Fairlight
Preparing the Timeline
```
As you can see (and hear), this timeline is a version of the OMO Promo you worked on in
```
the first three lessons of this book, with a few adjustments for this lesson. The main
difference is that there are additional audio clips on the Audio 2 track. These clips provide
ambience for the different B-roll clips. You will build on these in later steps to flesh out the
sound design of the promo. You will also notice that there are several level adjustments to
these clips, a couple of keyframed adjustments, some cross-dissolve transitions, and
audio fades.
To streamline the audio mixing process, you can name and color-code the tracks for
easy reference.
1 Click the Audio 1 track name and rename it DIALOGUE.
2 Rename Audio 2 VO, Audio 3 SOT, Audio 4 AMBIENCE, and Audio 5 MUSIC.
You can also change the color of the tracks so they are easy to identify visually.
429Lesson 8 An Introduction to Fairlight
3 Right-click the track controls for the DIALOGUE track and choose Change Track
Color > Teal.
All the clips in this track change color, making the dialogue clips easier to recognize
among the other audio clips.
NOTE If any clips in this track have their own color tag applied, this will
supplant the color assigned to the track.
4 Right-click the VO track and choose Change Track Color > Navy.
5 Change the color of the SOT track to Beige.
6 Change the color of the AMBIENCE track to Purple.
7 Leave the MUSIC track the default Green for audio tracks.
430Lesson 8 An Introduction to Fairlight
The new colorful timeline makes it easy to quickly identify the different audio elements
of your mix.
Next, you will also add a series of markers to the timeline to quickly identify parts
where you want to enhance the soundtrack with elements of sound design.
8 In the timeline, ensure that you have no clips selected. You can press Shift-Command-A
```
(macOS) or Shift-Ctrl-A (Windows) to be sure.
```
9 Move the playhead anywhere over the clip PINA BLANCA 70 and click the Markers
button in the timeline toolbar.
A blue marker appears underneath the playhead along the top of the timeline.
431Lesson 8 An Introduction to Fairlight
10 Double-click the marker and rename the marker WHOOSHES HERE, and click Done.
11 Move the playhead over the next clip, PINA BLANCA 48, and press M to add another
marker above this clip.
12 With the playhead still over the new marker, press M again to open the Marker window
and rename this marker FOOTSTEPS HERE and click Done.
432Lesson 8 An Introduction to Fairlight
13 Move the playhead over the clip STORE 34 and press M twice to add a marker and
open the Marker window in quick succession. Rename this marker SHIRT HANGING
and click Done.
TIP You will find a list of the markers in the open timeline in the Markers tab in
the Index.
14 Click the Full Extent Zoom button in the timeline toolbar to look at the timeline with the
new markers added.
You are now ready to take your timeline into Fairlight, DaVinci Resolve’s audio editing
and mixing environment.
15 At the bottom of the Davinci Resolve interface, click the Fairlight button or press Shift-7
to switch to the Fairlight page.
This is the one and only workflow step required to move from editing to audio post-
production in DaVinci Resolve!
433Lesson 8 An Introduction to Fairlight
Exploring the Fairlight Interface
In Lesson 3, you completed steps that resulted in an acceptable mix of all the audio for the
OMO Promo. However, the Fairlight page offers a greater level of control over your
soundtrack since it is designed around working with audio specifically and is optimized for
multichannel audio recording, editing, mixing, and sweetening. As you can see, the default
layout is streamlined to focus on the audio in the timeline.
1 Press Shift-Z to fit all the timeline clips horizontally in the timeline window.
2 If necessary, Shift-mouse scroll to adjust the height of the tracks so you can see all the
clips in the timeline.
Looking at the timeline, you’ll notice that all the audio fades, transitions, and keyframes
are still applied and viewable in the Fairlight page, along with the track names, colors,
and markers you added in the edit page. This is because this is exactly the same
timeline as you were viewing in the edit page, so any audio adjustments you made in
the edit page are immediately viewable in the Fairlight page, and vice versa. In fact, the
changes you made previously in the edit page could just as easily have been made
here in the Fairlight page using the same techniques.
In many ways, the Fairlight page operates and feels like the edit page, but there are
some differences. Before you dive in and start adjusting things, take a moment to
become more familiar with the main parts of the Fairlight interface.
434Lesson 8 An Introduction to Fairlight
In addition to clip adjustments being viewable in the Fairlight page, so too are any
adjustments you’ve made to the mixer. The only difference is that in the Fairlight page,
you have access to the full mixer, whereas in the edit page, you only have access to
certain controls in the mixer.
At the bottom of the timeline, you will also see an extra “track” that you do not see in
the edit page: Bus 1. This represents the stereo output of your timeline. You can
change the number of channels for your timeline by choosing Fairlight > Bus Format
and changing the Format for Bus 1. For more information on this and other bussing
options, see The Fairlight Audio Guide to DaVinci Resolve 20.
NOTE The Fairlight page doesn’t have the equivalent of the edit page’s full
extent and detail zoom buttons, but you can still use the same options for
controlling timeline zoom and track height as in the edit page: Option-mouse
```
scroll (macOS) or Alt-mouse scroll (Windows) to zoom the timeline and Shift-
```
```
mouse scroll (macOS and Windows) to zoom track height. To zoom the track
```
height centered on a specific track, click the track’s header to highlight the
track and use Shift-mouse scroll. This will also automatically select the clip on
that track under the playhead.
3 Move the playhead to the start of the timeline and play back to review the edit.
You’ll probably notice several things immediately. First, the meters for each track that
show the level of the clip currently playing can be seen in several locations: in the track
headers, along the top of the interface in the meters panel, and in the mixer on the
435Lesson 8 An Introduction to Fairlight
right of the interface. Don’t worry, though, since they are showing the same thing, for
the moment at least, you don’t need the mixer.
4 Click the Mixer button above the viewer to hide the mixer.
5 Press Shift-Z to display the timeline across the full width of the interface.
The other thing you will have noticed is that you can see the video from the edit page,
including effects, titles, and transitions, on the right of the meters panel.
This video preview always shows the current video frame wherever the playhead is in
the timeline. It can be used as a reference to ensure everything stays in sync and the
sound is timed correctly.
436Lesson 8 An Introduction to Fairlight
NOTE If you use a Blackmagic Design output device such as an Ultrastudio or
Decklink card, you will also see the preview on your external monitor.
In addition to using the viewer, it can be useful to see the video edits that were made
when referencing edit points or other elements in the timeline, such as titles.
6 Click the Timeline View Options menu.
7 Click the first option in the Track Display Options section to display the video tracks at
the top of the timeline.
NOTE To prevent inadvertently adjusting the clips in the video tracks, you can
choose to lock the tracks on the edit page.
8 In the timeline, press Shift-Up Arrow or Shift-Down Arrow to jump between the
different markers.
437Lesson 8 An Introduction to Fairlight
9 Click the Index button and, in the Edit Index, select the Markers tab to view a list of all
the markers in the timeline.
Since you won’t be using the markers just yet, you can easily close the Index so it’s not
taking up valuable screen real estate.
10 Click the Index button to hide the Edit Index panel and press Shift-Z to zoom the
timeline to fit the window.
After that brief tour of the main elements of the Fairlight page, it’s time to see how you can
start to use Fairlight to enhance your soundtracks.
Setting Track Formats
and Clip Channels
Working with audio in the Fairlight page follows the same principles as when you were
dealing with audio in the edit page in Lesson 3 in terms of setting levels and general
workflow. As before, you will start with the dialogue clips. However, the Fairlight page
exposes more information about those clips that you may find useful.
1 In the timeline header, click the Solo button for the DIALOGUE track.
438Lesson 8 An Introduction to Fairlight
2 Return the playhead to the start of the timeline and play through again, watching the
track meters and listening carefully.
Again, you will notice that Chris’s audio clips are only playing out of the left output
channel of this timeline, rather than out of both left and right. This is because these
clips are only configured to use one mono channel of audio—the fourth channel of the
```
linked audio, which is Chris’s lavalier microphone. (Previously, you used a stereo
```
configuration of this channel in two output channels. However, as there is only one
```
channel, it makes sense to use just this channel.)
```
If you look at the clips in the dialogue track, you will clearly see that these clips have
only one channel, whereas the track they are sitting in is a stereo track, so the second
channel of the track remains empty.
The edit page doesn’t typically expose the individual audio channels like this, so this is
a good reason to at least check your audio clips on the Fairlight page, even if
just briefly.
TIP If you wish to see the individual audio channels in the edit page, select the
relevant clips, right-click them, and choose Display Individual Audio Channels.
```
As dialogue audio is invariably mono (no one has more than one mouth), all dialogue
```
should be placed in a mono track. Thankfully, it’s very easy to make this change in
DaVinci Resolve.
439Lesson 8 An Introduction to Fairlight
3 Right-click the track header for the A1 DIALOGUE track and choose Change Track Type
To > Mono.
The track changes from a stereo track to a mono track.
440Lesson 8 An Introduction to Fairlight
The clips now fill the full height of the track, and when you play these back, you’ll see
that the track meter is now one solid bar with the 1.0 indicator, instead of two thin bars
with the 2.0 indicator.
Moreover, the audio now plays out of both left and right speakers equally.
NOTE Only the first audio channel will play in a mono audio track, even if the clip
is a stereo clip. You can always adjust the audio configuration of a clip in the
timeline by right-clicking it and choosing Clip Attributes. For more information
about configuring audio channels using Clip Attributes, see Lesson 7.
Trimming Clips in Fairlight
Another common task you have more control of in the Fairlight page is trimming audio
clips. The smallest amount a video clip can be trimmed is the individual frame level. Audio,
however, has a much greater level of detail. Audio for video production is typically
```
recorded at 48 kHz (kilohertz), meaning that there are 48,000 samples of audio per
```
```
second; this equates to around 2,000 samples per frame if your video is running at 24
```
frames per second. Fairlight allows you to trim at this sample level.
```
1 In the timeline, use Option-scroll (macOS) or Alt-scroll (Windows) and Shift-scroll to
```
zoom in on the first audio clip on the DIALOGUE track.
441Lesson 8 An Introduction to Fairlight
Notice that the end of this clip contains no waveform since Chris isn’t speaking, and
you hear the environmental noise captured in the audio recording.
NOTE It’s very easy to zoom in much further than you can in the edit page. If
you see the dots appear on the audio clip, you are so close that you can see
the individual samples!
2 Select the end of the clip as if you were trimming the clip in the edit page, but keep
your mouse button held down.
When trimming clips in the Fairlight page, you can see the waveforms of the clip’s
handles displayed, making it easier to trim the audio clips with more precision.
3 In the timeline toolbar, disable the Snapping button or press N.
4 Trim the end of the clip back to the end of the previous waveform.
5 Listen back to the change you have made.
Trimming audio in the Fairlight page is much more accurate and precise than it is in
the edit page. Before going any further, listen to all the other audio edits along the
first two tracks in this timeline to see if there are any other edits that could benefit
from the precise adjustments you can make in the Fairlight page.
6 Press Shift-Z to fit the timeline zoom.
442Lesson 8 An Introduction to Fairlight
NOTE The Fairlight page does not have a Trim Edit mode like the edit page has,
so any trimming performed on the Fairlight page will not affect the overall
duration of the timeline. Similarly, it’s not possible to roll, slip, or slide an edit point
or clip. For actions like this, you’ll need to use the edit page, which highlights the
flexibility of Resolve in that you can keep moving between the different pages
seamlessly at any point.
Subframe Audio Adjustments
You don’t always have to rely on the precision of the sample-level editing function
of the Fairlight page because the edit page allows you to work with audio at the
subframe level—that is, at a far higher level than the individual video frame but
not quite to the level of individual samples. Nevertheless, this often allows you to
trim audio to a high level of precision without leaving the edit page. It’s not quite
as precise as the Fairlight page, but for many situations it’s more than adequate.
The best way to ensure that you’re trimming at the subframe level in the edit page
is to have snapping and linked selection disabled in the timeline and zoom in on
the edit as much as you can.
NOTE If you need to catch up before moving to the next step, open the media
pool, select the TIMELINES bin, and choose File > Import > Timeline, navigate to
R20 Beginners Guide / Lesson 08 / Timelines / OMO PROMO MIX CATCHUP 01.drt
and click Open.
Using the AI Dialogue Leveler
When you worked on the audio for the OMO PROMO timeline in Lesson 3, you used
Normalization and a series of audio keyframes to balance the dialogue track levels. That is
```
one way of ensuring a consistent level of all the dialogue clips; however, you no doubt
```
found this time-consuming.
The Fairlight page includes some dedicated tools that you will find helpful when
sweetening the audio in your timeline. You will start by balancing the levels of the clips in
the DIALOGUE tracks using the AI Dialogue Leveler.
443Lesson 8 An Introduction to Fairlight
1 Click the Mixer button to reopen the mixer panel.
2 Drag the left edge of the mixer to display the channel strips for each track, and press
Shift-Z to fit the timeline.
3 Play the timeline, listen to the clips on the solo’d DIALOGUE track, and pay attention to
```
the levels of the different clips (it doesn’t matter which meter you look at; they all show
```
```
the same information).
```
444Lesson 8 An Introduction to Fairlight
```
As you can see (and no doubt hear), the levels throughout this interview fluctuate from
```
around -6 dBFS to as low as 20 dBFS! The difference between these values is called the
dynamic range. You’ll generally want to reduce the dynamic range of certain audio
clips, such as dialogue, for a more consistent level. This might mean making louder
parts of the audio quieter, vice versa, or a combination of both.
As a rule of thumb, you want your dialogue audio to sit in the yellow area of the mixer
```
(between -18 dBFS and -9 dBFS). Quiet, softly spoken lines might be toward the bottom
```
of this range, and shouted lines will be toward the higher end. Normal dialogue levels
are set around -12 dBFS.
In Lesson 3, you achieved this using a combination of normalization and keyframes.
This time, you’ll let the Fairlight tools do the heavy lifting.
4 At the top of the mixer, locate the Track FX row of controls.
5 Move your mouse over the Dial Lev Track FX for the A1 controls and click the Enable
option to enable the AI Dialogue Leveler.
6 With the Dialogue Leveler enabled, move your mouse pointer back over the Track FX
and click the Controls button.
445Lesson 8 An Introduction to Fairlight
The AI Dialogue Leveler controls open for the DIALOGUE track.
7 Play the timeline again, noting overall changes in the DIALOGUE track clips’ levels
```
(particularly the quieter clips) and the graph in the AI Dialogue Leveler where the white
```
line represents the real-time adjustments to the levels.
You should notice that the quieter clips on this track are a little higher than before,
as indicated by the graph in the AI Dialogue Leveler.
446Lesson 8 An Introduction to Fairlight
8 In the AI Dialogue Leveler, change the menu to “Optimize moderate levels.”
9 Play the timeline again, this time noting how the louder clips have been lowered while
the quieter clips have been raised. This results in a more consistent audio level across
the track without you having to adjust the levels of each individual clip!
10 After listening to the DIALOGUE track, close the AI Dialogue Leveler controls.
447Lesson 8 An Introduction to Fairlight
11 Click the Solo control for the VO track so you can hear this track alongside the
DIALOGUE track, and play the clip at the end of this track, noting the audio levels.
```
Obviously, this clip’s levels need to be adjusted to balance against Chris’s dialogue;
```
otherwise, you’ll shock your audience and have them reaching for the volume controls!
```
While you could adjust the levels of this clip independently (it is only one clip after all),
```
there’s still an advantage to applying the AI Dialogue Leveler as a Track FX. As you’ve
seen from the DIALOGUE track, one set of controls affects all clips along the same
track. Therefore, if you were to add additional clips to the VO track later, they would
automatically fall under the track’s AI Dialogue Leveler settings.
12 Enable the Dialogue Leveler Track FX for the VO track in the mixer, open the controls,
and set the menu to “Optimize moderate levels” as you did with the DIALOGUE track.
448Lesson 8 An Introduction to Fairlight
13 Play the timeline again, listening to how the VO recording is now better balanced with
the overall dialogue levels.
Using Dynamics
If you are familiar with audio processing techniques, Fairlight has tools for you too.
If you prefer to apply your own adjustments to the dynamic range of clips on a
track, you can use the built-in Dynamics controls. Simply double-click the Dynamics
controls in the mixer to open them in a separate window, allowing you to apply
adjustments to the audio using an Expander or Gate, a Compressor, and a Limiter.
For more information, see The Fairlight Audio Guide to DaVinci Resolve 20.
449Lesson 8 An Introduction to Fairlight
NOTE If you need to catch up before moving to the next step, open the media
pool, select the TIMELINES bin, and choose File > Import > Timeline, navigate to
R20 Beginners Guide / Lesson 08 / Timelines /
OMO PROMO MIX CATCHUP 02.drt and click Open.
Applying EQ
Another set of controls you can use to help sweeten your audio, especially when it comes to
dialogue clips, is to apply an adjustment to the EQ. Again, Fairlight has dedicated EQ
controls that can be applied to an entire track. EQ is often used to control the “warmth” of
the audio signal by increasing or decreasing certain frequencies. You will use the EQ
controls to help “warm up” Chris’s dialogue audio.
1 Double-click the EQ settings for the DIALOGUE track.
450Lesson 8 An Introduction to Fairlight
The 6-Band Equalizer settings window opens.
2 Play back the first two clips in the timeline.
As the audio plays in the timeline, you can see the graph representing the various
frequencies of Chris’s voice.
451Lesson 8 An Introduction to Fairlight
Unsurprisingly, since Chris has a reasonably deep voice, most of the frequencies in his
voice are grouped in the lower frequency range, up to around 500 Hz. You can adjust
the EQ by increasing or decreasing the levels of the various frequencies.
3 In the preset list, select the “Dialog – Male lav finisher” option.
From the controls, you can see that this loads a preset that rolls off the frequencies at
the very lower end and increases the frequencies around the 250 Hz range, and again
at around the 4 kHz range.
452Lesson 8 An Introduction to Fairlight
4 Play back the first two clips in the DIALOGUE track again to hear the changes.
You should hear that Chris’s audio sounds slightly warmer, thanks to the adjustment
made to the lower frequencies, while the adjustments to the upper frequencies
probably have less of an impact. The fainter, white-outlined indicators on the graph
represent the original frequencies.
NOTE If you find it hard to discern between the adjusted EQ and the “flat”
```
(non-EQ’d) version, you can enable and disable the EQ as the audio is
```
playing back.
Sometimes EQ adjustments can be quite dramatic.
5 Select the “General Telephone effect” preset.
453Lesson 8 An Introduction to Fairlight
You can tell immediately from the graph that this preset limits the frequencies to
between 300 Hz and 3kHz, while slightly reducing the level at around 1 kHz.
6 Play back the first two clips again to hear Chris sounding like he’s speaking on the end
of a telephone call!
7 Click the Reset button at the top right of the EQ controls window and reselect the
“Dialog – Male lav finisher” option.
8 Close the EQ window for the DIALOGUE track, and in the mixer, double-click the EQ
controls for the VO track.
454Lesson 8 An Introduction to Fairlight
9 In the EQ window, choose the “Dialog – Female lav mic fixer” preset to add more
warmth to the recorded voiceover.
10 When you have listened to how the preset affects the voice for this track, close the
EQ window.
Presets like these are useful starting points for adjusting the EQ of your audio clips.
For more information on manually adjusting a track’s EQ, see The Fairlight Audio Guide to
DaVinci Resolve 20.
NOTE If you need to catch up before moving to the next step, open the media
pool, select the TIMELINES bin, and choose File > Import > Timeline, navigate to
R20 Beginners Guide / Lesson 08 / Timelines /
OMO PROMO MIX CATCHUP 03.drt and click Open.
455Lesson 8 An Introduction to Fairlight
Adding Sound Effects
In addition to sweetening the audio in your timeline, the Fairlight page can help you add,
edit, and manipulate audio clips. And because the Fairlight interface is solely concerned
with audio work, it provides a much more flexible environment than the edit page, and no
more so than when it comes to adding and synchronizing sound effects. You will start by
adding a new audio track for the types of sound clips you will initially add.
1 Use the Solo buttons in the mixer to unsolo the DIALOGUE and VO tracks.
2 Click the Mixer button to hide the mixer.
3 In the top left corner of the interface, click the Index button to open the Edit Index,
and click the Markers tab to reveal the list of markers you previously added in the
edit page.
4 Press Shift-Z to zoom the timeline to fit and, in the Markers Index, click the second
marker, FOOTSTEPS HERE, to jump to that marker in the timeline.
456Lesson 8 An Introduction to Fairlight
This is the part of the edit where the guy jumps up onto the rocks to look out over the
landscape. The original audio recorded with this clip wasn’t suitable for use, but you
will add some sound that can be used instead.
5 In the top left corner of the interface, click the Media Pool button to reveal the media
pool and select the FOLEY bin.
NOTE In filmmaking parlance, foley is the term used for any audio added to a
film’s soundtrack that re-creates diegetic sounds, such as footsteps on
different surfaces, traffic sounds, the rustle of clothing, or the swish of a
lightsaber. Named after Jack Foley, the pioneer of recording and synchronizing
such “everyday” sounds for films, it also gives rise to the terms foley studio,
where such sounds are often created and recorded, and foley artist, the
person who performs and/or records the sounds.
457Lesson 8 An Introduction to Fairlight
This bin contains two clips that were taken from the Fairlight Sound Library. For more
information on obtaining and using the Fairlight Sound Library, see The Fairlight Audio
Guide to DaVinci Resolve 20.
NOTE By default, the Fairlight page only shows audio clips and video clips
with an audio element to them in the media pool. To see all clips, click the
```
Media Pool Options (…) menu and choose Show All Clips.
```
6 Select the clip Boots on Rough Dirt Footsteps.wav to open it in the preview player.
7 Play the clip to listen to it.
You can tell just by looking at the waveform display that this is a single-channel
mono clip.
458Lesson 8 An Introduction to Fairlight
NOTE To verify that this clip is indeed mono, you can view its channel
configuration in the Inspector or in Clip Attributes, as you did in the
previous lesson.
Now that you know you’ll be working with a mono audio clip, you know the type of
track you’ll need in the timeline.
8 Right-click the AMBIENCE track controls and choose Add Track > Mono.
A new mono audio track is added below the SOT track.
NOTE New audio tracks are always added below the track for which you
right-clicked the controls. You can always reposition a track in the timeline by
```
using the Track Index (see below). To add more than one audio track, or to
```
specify where the track will be placed in the timeline, right-click the track
controls and choose Add Tracks.
459Lesson 8 An Introduction to Fairlight
9 Rename the new track FOLEY, right-click the track controls, and choose Change Track
Color > Violet.
10 Click the Solo button for the FOLEY track.
Now you need to add the clip to the track and sync the sound to the onscreen action.
Using Scrollers
Editing audio clips into the timeline in the Fairlight page is similar to editing audio clips in
the edit page, except that there isn’t the flexibility you have in the edit page with all the
```
different edits (Overwrite, Insert, Place on Top, Append, etc.). Instead, editing audio clips in
```
the Fairlight page is as simple as drag and drop. However, you can choose to add In and
Out points to a clip in the preview player as you did in the edit page’s source viewer.
```
1 Use Option-scroll (macOS) or Alt-scroll (Windows) to zoom in on the playhead location
```
in the timeline, which is still on the second marker.
460Lesson 8 An Introduction to Fairlight
2 In the media pool, select the Boots on Rough Dirt Footsteps.wav and drag it from
the preview player into the FOLEY track in the timeline. Don’t worry about placing it in
```
any particular place at the moment; just line up the start of the clip with the start of
```
the PINA BLANCA 48 clip in the V2 track above.
With the clip in the timeline, you’ll now need to align the sound effect with the guy’s
movements. To help you do that efficiently, the Fairlight page has a set of scrollers.
3 Click the Timeline View Options menu and choose Display Video Scroller.
461Lesson 8 An Introduction to Fairlight
The video scroller opens underneath the timeline and shows the individual video
frames in use from the edit page. In the center of the video scroller, you will see a red
line indicating the frame currently underneath the playhead in the timeline.
4 In the video scroller, click the frames to the left and right of the current frame to move
the playhead to the start of that frame.
5 Use the video scroller to reposition the timeline playhead to the start of the frame
```
where the guy places his right foot on the rock. (Since you can’t see his foot touching
```
```
the rock, you’ll need to use your best judgment.)
```
TIP You can open the Fairlight page viewer in a separate floating window by
clicking the Floating Window button in the lower right corner of the viewer.
462Lesson 8 An Introduction to Fairlight
6 In the Timeline View Options menu, select Show Audio Scroller 1.
The audio scroller opens below the video scroller, showing the waveform of the chosen
audio track.
463Lesson 8 An Introduction to Fairlight
7 Click the Display menu for Audio Scroller 1 and choose the A4 - FOLEY track to display
the waveform of the audio on this track.
8 In the timeline, drag the Boots on Rough Dirt Footsteps.wav clip to align the
waveform of the first “step” with the start of the frame in the scrollers.
Using the scrollers to align audio to onscreen action like this is much easier than trying
to judge it in the timeline.
9 Play back the new sound effect in the timeline.
Generally, the sync works well, but the third “step” isn’t quite timed right.
10 In the timeline, click the final “step” in the audio scroller to jump to that part of the
audio clip and click and drag the waveform to position the playhead accurately just
before the waveform.
464Lesson 8 An Introduction to Fairlight
11 With the Boots on Rough Dirt Footsteps.wav clip selected in the timeline, click the
```
Razor (Scissors) button in the timeline toolbar, or press Command-B (macOS) or Ctrl-B
```
```
(Windows) to split the clip.
```
12 Using the video scroller, move back a few frames to locate where the guy puts his foot
down in the wide shot.
13 Once the playhead is at the start of the frame, drag the second part of the split audio
clip back to align the waveform with the action.
14 Trim off the final “step” in the Boots on Rough Dirt Footsteps.wav clip.
465Lesson 8 An Introduction to Fairlight
15 Play back the two shots and review your synced sound effect.
Sometimes even the tiniest, most innocuous piece of sound can help enhance a shot
or scene, even if it wasn’t actually recorded for that particular purpose.
16 In the markers index, click the third marker, SHIRT HANGING, to jump to that point in
the timeline.
It would be nice to include a small sound effect of the shirt being placed on the hanger.
17 Using the video scroller, locate the frame where you think the shirt hanger would
contact the display hanger. Again, since you can’t see the action fully onscreen, your
best guess is as good as anything—you can always adjust it later if necessary.
466Lesson 8 An Introduction to Fairlight
18 From the FOLEY bin, select the Pen Clicks.wav clip and listen to it using the
preview player.
This clip has a few unidentifiable clicks that will serve your purpose.
```
19 In the preview player, place the playhead at the start of the penultimate click (pun
```
```
intended) and press I to add an In point.
```
467Lesson 8 An Introduction to Fairlight
TIP You can use the familiar playback controls you learned in the edit page
lessons, such as the Spacebar or JKL keys and the left/right arrows, to control
the playback of audio in the Fairlight preview player.
20 Drag the marked clip from the preview player to the playhead location in the FOLEY
track, using the audio scroller to refine the position of the clip to best align it with the
onscreen action.
21 Review your new sound effect along with the ambience, changing the alignment of the
sound effect to best sell the action.
Aligning Sound Effects
Fairlight has other audio-centric tools that you can use to your advantage when building
your sound design elements and enhancing the onscreen action.
1 In the Markers Index, select the first marker, called “WHOOSHES HERE,” to move to the
shot of the girl with the flaming torches in the timeline.
You’ll add some sound effects to this to emphasize the movement of the torches.
468Lesson 8 An Introduction to Fairlight
2 In the media pool, select the Slow Whoosh.wav clip and listen to it using the
preview player.
This is the sort of sound effect that’s been created rather than recorded, often as part
of a sound effect library, and is a good substitute for the sound of flaming torches. You
can see that this clip has two audio channels—a good indication that it’s a stereo clip.
NOTE Just because the waveform shows two channels doesn’t necessarily tell
you how they are configured. Always double-check using the Audio
Configuration panel in the Inspector or the Clip Attributes window as you did
in the previous lesson.
469Lesson 8 An Introduction to Fairlight
3 In the timeline, right-click the track controls for the FOLEY track and choose
Add Tracks.
4 In the Add Tracks dialog, change the number of tracks to 2, ensure that the Insert
Position is set to Below FOLEY, and change the Audio Track Type to Stereo.
5 Click Add Tracks.
```
Two new stereo tracks (Audio 5 and Audio 6) are added to the timeline below the
```
FOLEY track.
6 Change the names of Audio 5 and Audio 6 to SFX1 and SFX2, respectively.
```
7 Select the track header for SFX1 and Command-click (macOS) or Ctrl-Click (Windows)
```
the track header for SFX2.
8 Right-click the selected tracks and choose Change Track Color > Tan for both of
these tracks.
470Lesson 8 An Introduction to Fairlight
9 Click the Solo control for both of these tracks.
10 Now use the video scrollers to locate the first time in the clip where the flaming
torches are closest to the camera.
11 Drag the Slow Whoosh.wav clip from the preview player so the playhead intersects
the center of the waveform.
471Lesson 8 An Introduction to Fairlight
12 Click the track controls for the SFX1 track.
Whenever a track is selected like this in Fairlight, any clips intersecting the playhead
are automatically selected.
```
13 With the clip automatically selected, choose Edit > Copy or press Command-C (macOS)
```
```
or Ctrl-C (Windows) to copy the clip.
```
14 Click the track control for SFX2.
A transparent copy of the Slow Whoosh.wav clip appears in the SFX2 track.
15 Using the video scroller, locate the next time the flaming torches circle around closest
to the camera.
The playhead follows the video scroller to the new position, and the transparent copy
of the Slow Whoosh.wav clip moves along with it as though it’s attached to
the playhead!
472Lesson 8 An Introduction to Fairlight
```
16 Choose Edit > Paste or press Command-V (macOS) or Ctrl-V (Windows) to paste the
```
copy of the clip into the SFX2 track at this position.
17 Select the SFX1 track and use the video scroller to locate the third time the flaming
```
torches are closest to the camera and press Command-V (macOS) or Ctrl-V (Windows)
```
to paste another copy of the clip.
18 Play back the shot of the flaming torches, along with its newly enhanced audio.
As you can see, the Fairlight page offers several enhancements when it comes to adding
and syncing audio clips to onscreen action.
NOTE If you need to catch up before moving to the next step, open the media
pool, select the TIMELINES bin, and choose File > Import > Timeline, navigate to
R20 Beginners Guide / Lesson 08 / Timelines / OMO PROMO MIX CATCHUP 04.drt
and click Open.
473Lesson 8 An Introduction to Fairlight
Mixing the Soundtrack
Now that you’ve successfully added the sound design elements to the OMO Promo, it’s
time to bring all the elements together into the final mix. This is where you bring all the
separate audio elements together by balancing the levels of the clips on each track so the
soundtrack sounds good as a whole.
While you could make these adjustments at an individual clip level, the easiest way to
balance the mix is to use the mixer.
1 In the Timeline View Options menu, click the Display Video Scroller and Display Audio
Scroller 1 options to turn off the scrollers.
2 Choose Workspace > Reset UI Layout to reset the Fairlight page back to the default
layout. Drag the left edge of the mixer so you can see all the channel strips.
3 Un-solo all the tracks except the DIALOGUE and VO tracks.
4 Press Shift-Z and adjust the track heights so you can see the whole timeline.
It’s time to start listening to the individual elements and setting the track levels so they
all sound good together. Since you’ve already set the dialogue levels using the
Dialogue Leveler, that will be your starting point.
474Lesson 8 An Introduction to Fairlight
5 Play the timeline, listening to the overall levels of the dialogue track.
6 Click the Solo button for the SOT track to add this track to the overall mix.
The levels of these clips sound fine next to Chris’s interview, although you can always
change them later if necessary, so you will add the next element into the mix.
7 Click the Solo button for the AMBIENCE track.
This track contains general, nonspecific environment sounds, mainly interior and
exterior sounds, to help establish a location for each of the shots.
8 Select all the clips on the AMIBIENCE track, right-click them, and choose Clip
Operations > Normalize Audio Levels, and normalize them independently to -18 dBFS.
If that sounds like it may be a bit too loud, you’re right.
9 Play the part of the timeline where the clips on the AMBIENCE track fade in.
The clips on this track distract from Chris’s spoken words because they’re too
dominant in the mix. Normalization means that the clips have a consistent level
```
(around -20 dBFS, peaking at -18 dBFS, of course), but that’s too loud for this mix.
```
You could simply normalize the clips to a lower level or adjust each clip’s audio level to
be lower, but there’s a more efficient way of adjusting the ambience level.
475Lesson 8 An Introduction to Fairlight
10 Play the timeline again and, when the ambience clips start to play, use the control strip
in the mixer to lower the level of the whole track.
As you are adjusting the track level in the mixer, try to use your ears to discern where
the level should be. If you’re unsure, an adjustment of around -10 dB is probably about
```
right (as indicated by the white relative adjustment value at the top of the fader). Don’t
```
worry if you’re not sure whether it’s the right level just yet, there will be plenty of
opportunity to refine it.
Next, it’s time to add the first track of your sound design elements.
11 Click the Solo button for the FOLEY track to add this to the mix.
Again, the level of each of the clips on this track is too high.
12 Normalize the level of the clips on this track to -9 dB. Then, bring the track’s level down
in the mixer by around -12 dB.
13 Click the Solo button for the SFX1 and SFX2 tracks.
Because these two tracks contain copies of the same clips, there’s no benefit to
normalizing their levels since they’ll all be normalized by the same amount anyway.
However, because the clips are across two tracks, you can make the same change to
both tracks by grouping them together.
476Lesson 8 An Introduction to Fairlight
```
14 Select both tracks by Command-clicking (macOS) or Ctrl-clicking (Windows) the track
```
control headers, and then right-click the track controls and choose Create Group.
15 In the Create Group window, change the name of the group to WHOOSHES and check
the options for Fader, Solo, and Mute.
477Lesson 8 An Introduction to Fairlight
Choosing these controls means that adjusting one of these controls for one track will
adjust the others in the group at the same time.
16 Click Save.
478Lesson 8 An Introduction to Fairlight
In the mixer, you will see that these tracks have been added to the new group. Now,
any change to the faders, solo, or mute controls will affect both tracks simultaneously.
17 Lower the level for either SFX1 or SFX2 by about -3 dB. The other track in the
Group will follow suit.
479Lesson 8 An Introduction to Fairlight
NOTE You can manage the group in the Groups panel. To make changes to a
group, click the Settings button for the group to open it in the Modify
Group window.
If you delete a group, all the adjustments you’ve made will be retained on
the tracks.
Ducking the Music
The last element to add to the mix is the Music track. Back in Lesson 3, you accomplished
this using a series of keyframes. You can still add, adjust, and edit audio keyframes in the
same way in the Fairlight page. However, the Fairlight page has a couple of other tricks up
its virtual sleeve!
You will start by using another automatic method of riding the audio levels in the timeline
using a Track FX called the Ducker.
1 In the timeline, deselect all the active Solo controls for the tracks.
TIP You can click and drag your mouse across the Solo controls in the timeline
track headers to enable/disable the Solo for a set of tracks at once.
2 Deselect any currently selected tracks and return the playhead to the start of the
timeline and begin playing back, listening to the first two dialogue clips.
The general level of the music is acceptable until Chris starts speaking, of course.
480Lesson 8 An Introduction to Fairlight
```
3 In the mixer, click the Options menu (…) and choose Visible Track FX > Ducker.
```
```
The Ducker appears below the Dial Lev (Dialogue Leveler) in the row of Track FX.
```
481Lesson 8 An Introduction to Fairlight
```
4 Enable the Ducker Track FX for the MUSIC track (A8) and click the settings to open
```
the controls.
The Ducker’s controls open in a separate window.
5 In the Source menu, choose the DIALOGUE track. This is the track the Ducker will
listen to.
6 Adjust the Duck Level to 12 dB. This is how much the MUSIC track audio level will be
reduced by.
7 Begin playing the timeline.
482Lesson 8 An Introduction to Fairlight
As the timeline plays, the Ducker will show a real-time adjustment of the audio levels of
the MUSIC track, based on the audio clips of the DIALOGUE track, instantly mixing the
music against Chris’s soundbites without the need for keyframes!
However, while the Recovery out of the soundbites is nice and smooth, the Rise Time
going into the soundbites is a little too abrupt.
```
8 Adjust the Rise Time to 500 mS (milliseconds).
```
9 Play the timeline again, noting the difference the changes have made.
To prevent the Ducker from adjusting the level between each of Chris’s pauses, you
can adjust the Lookahead control.
483Lesson 8 An Introduction to Fairlight
10 Adjust the Lookahead to around 400 mS for a more consistent level across the
short pauses.
You can also add other tracks to the Ducker’s Source.
```
11 Click the Source and Command-click (macOS) or Ctrl-click (Windows) the VO track to
```
add it as a source track for the Ducker to listen to.
The Ducker now reduces the level of the MUSIC track based on the clips’ audio in the
DIALOGUE and VO tracks.
12 When you are happy with the mix, close the Ducker window.
484Lesson 8 An Introduction to Fairlight
NOTE To import a finished version of the timeline for this lesson that uses
the Ducker, open the media pool, select the TIMELINES bin, choose
File > Import > Timeline, navigate to R20 Beginners Guide / Lesson 08 / Timelines /
OMO PROMO MIX COMPLETED DUCKER.drt, and click Open.
Using Audio Keyframes
While the Ducker is a great way of automatically riding the audio levels of one track based
on the audio of clips in one or more other tracks, sometimes you want to mix the audio in
your timeline with a greater level of control. This is where audio keyframes come in handy,
as they allow greater control and flexibility over the specific audio levels within a clip.
To explore the differences between applying keyframes in the Fairlight page and using the
Ducker, you will start by duplicating the current timeline.
1 Choose Timeline > Find Current Timeline in Media Pool to show the current timeline—
OMO PROMO MIX—in the media pool.
2 Right-click the timeline in the media pool and choose Duplicate Timeline.
485Lesson 8 An Introduction to Fairlight
3 Right-click the duplicated timeline and rename it OMO PROMO MIX DUCKER.
```
4 In the Mixer, click the Enable button for the Ducker on the MUSIC track (A8).
```
5 Click the Index button and select the Tracks tab.
The Track Index lists all the tracks available in this timeline.
```
6 Click and drag across the visibility (eyeball) buttons for Tracks A3 to A7—all the tracks
```
except the dialogue and music tracks.
486Lesson 8 An Introduction to Fairlight
This hides those tracks in the timeline and mixer.
Because they are not muted, you will still hear these tracks, but it helps to simplify the
timeline, allowing you to concentrate on the dialogue and music tracks together,
without having to work around all the tracks in between.
7 Close the media pool and Index, and press Shift-Z to fit the timeline and adjust the
height of the remaining visible tracks.
To bring the DIALOGUE and MUSIC tracks closer together to make it easier to add
keyframes, you can adjust the size of the VO track.
487Lesson 8 An Introduction to Fairlight
8 Right-click the VO track controls and choose Lock Track Height to > Mini.
This makes the VO track smaller but still accessible.
NOTE You can restore the height of this timeline track by right-clicking the
controls and choosing Lock Track Height to > None.
The simplified and larger timeline will make placing keyframes much easier than if
there were many more tracks between the DIALOGUE and MUSIC tracks.
488Lesson 8 An Introduction to Fairlight
9 Place the playhead at the start of the first clip of dialogue and use Option-scroll
```
(macOS) or Alt-scroll (Windows) to zoom in on the start of the clip.
```
```
10 Hold down the Option key (macOS) or Alt key (Windows) and click twice on the gain line
```
of the music clip to add two keyframes around the point where Chris’s
soundbite starts.
11 Scroll along the timeline until you see the end of the clip on the DIALOGUE track and
add two more keyframes around the end of the soundbite.
489Lesson 8 An Introduction to Fairlight
12 Grab the volume line between the two middle keyframes and decrease the level for
this part of the clip by about -12 dB.
NOTE In Fairlight, the tooltip shows the absolute level of the audio bar and
```
the relative level as the Δ (delta) value.
```
13 Repeat the process each time Chris pauses to raise the level of the music between
each sound bite.
```
Be careful, though. Don’t just blindly follow the numbers; you need to listen to how all
```
the elements of the mix are working together, so some level adjustments may need to
be made more carefully than others. You want to make sure your audience has an
opportunity to hear all the nuances of the soundtrack you have created!
14 Once the music mix has been completed, right-click the VO track controls and choose
Lock Track Height > None.
15 Reopen the Tracks Index and click and drag across the visibility buttons to show the
hidden tracks in the timeline.
490Lesson 8 An Introduction to Fairlight
16 Press Shift-Z and adjust the timeline track heights so you can see the entire timeline.
17 Return the playhead to the start of the timeline and play back to enjoy the full mix!
Of course, feel free to continue making further adjustments. Like much of the creative
work you undertake in DaVnci Resolve, you will need to continually refine things to get the
```
results you desire. So feel free to continue adjusting the mix as you see (or hear) fit,
```
whether that’s using the mixer or individual clips in the timeline.
NOTE To import a finished version of the timeline for this lesson that uses
audio keyframes, open the media pool, select the TIMELINES bin, choose
File > Import > Timeline, navigate to R20 Beginners Guide / Lesson 08 / Timelines /
OMO PROMO MIX COMPLETED KEYFRAMES.drt, and click Open.
Congratulations! You have successfully completed this introduction to working in the
Fairlight page! While this lesson has aimed to show you some of the advantages of using
the Fairlight page, there is much more to the Fairlight page than can be realistically
covered in this beginner’s guide. For more information on using Fairlight for your audio
work, including using the Fairlight FX, recording ADR, and automation, see The Fairlight
Audio Guide to DaVinci Resolve 20.
Once you are happy with the mix, you can return to the edit page, where you will see all the
audio changes you’ve made in Fairlight, once again highlighting the flexibility of working in
DaVinci Resolve!
491Lesson 8 An Introduction to Fairlight
Lesson Review
1 What is the highest level of precision you can adjust audio clips in the Fairlight page?
```
a) Frame level
```
```
b) Subframe level
```
```
c) Sample Level
```
2 True or False? All audio adjustments you make in the edit page are visible and
adjustable in the Fairlight page.
3 Which controls can be used to adjust the “warmth” of dialogue clips?
```
a) EQ
```
```
b) Dialogue Leveler
```
```
c) Ducker
```
4 How many audio scrollers can be displayed at the same time?
5 True or False? The Fairlight page does not allow you to add audio clips to the timeline.
492Lesson 8 An Introduction to Fairlight
Answers
```
1 c). Audio clips can be edited at the sample level, which offers the highest precision in
```
the Fairlight page.
2 True. All audio changes you make in the edit page are visible and adjustable in the
Fairlight page.
```
3 a). The EQ controls can be used to adjust the “warmth” of dialogue clips.
```
4 Up to two audio scrollers can be displayed at the same time, as well as one
video scroller.
5 False. Audio clips can be added to the timeline by dragging them from the media pool
or from the preview player.
493An Introduction to Visual Effects Compositing
An Introduction
to Visual Effects
Compositing
When mutants attack or aliens land spaceships on Earth, filmmakers turn to visual effects
artists to make those shots reality. You can use visual effects to create images that cannot
be realized with live-action production. Anything that’s too difficult, too dangerous, or
even too expensive to capture with a camera, you can create with visual effects
compositing.
DaVinci Resolve has the full Fusion visual effects and motion graphics toolset built in, which
makes it possible for you to create feature film-quality effects without switching between
software applications!
While you can create simple visual effects in the edit page, you’ll find more advanced tools
for building sophisticated, photorealistic effects in the Fusion page. It features a flow
graph-style interface, known as a node tree, designed specifically for visual effects and
motion graphics work.
As you read through the following lesson, you’ll begin to understand the many tasks you
might choose to perform using Fusion’s complete 3D workspace and over 250 compositing
and visual effects tools. Best of all, it’s now part of DaVinci Resolve, so you can switch from
editing, color grading, and audio post-production to visual effects and motion graphics
with a single click!
494An Introduction to Visual Effects Compositing
What Is Visual Effects Compositing?
Compositing is the process of combining two or more images to make a unique, new image.
But it’s not just about combining images. You can composite many different elements, such
as video clips, animations, text, mattes, particles, and graphics. Sometimes these elements
are called layers because they are layered on top of each other to produce the new image.
Many tasks fall under the umbrella of visual effects. Just as with color and audio post-
production, visual effects are a huge and exciting part of the creative filmmaking process.
Depending on the type of work you do, you may need to learn some or all of the skills
needed to create a finished visual effects shot. Smaller productions often require you to
build shots from start to finish, whereas larger studios may have specialized artists
dedicated to tasks such as rotoscoping, 3D, particles, lighting, and so on.
Even when you are hired as an editor or a colorist, you will often be asked to produce
smaller effects. Like all aspects of post-production, learning the tools and techniques
requires practice. Understanding the technology behind the tools will improve your
problem-solving skills and efficiency.
As industry deadlines tend to grow shorter, editors and colorists who know how to finish
shots quickly and efficiently are in the highest demand. Learning the basics of Fusion
visual effects in DaVinci Resolve—along with color correction and audio post-production—
will make you a more valuable artist and open up more job opportunities.
Getting Started with Visual Effects
Visual effects were once a luxury reserved only for big-budget feature films. With the
power of Fusion built into DaVinci Resolve, you can add feature film–quality visual effects
to any program without a massive budget.
If you think visual effects are only about creating aliens, spaceships, and explosions,
you are missing out on the many smaller effects that can improve any project. In fact, most
visual effects consist of corrective effects, clean-up work, or inserting subtle hidden effects
such as sky and window replacements. These effects don’t take long to do and can
improve everything from poorly framed B-Roll to dull gray skies.
Adding Elements
Weather is unpredictable, and when the story calls for snow, you need snow! That’s why
creating elements such as snow, rain, fog, and even lightning are essential skills of the
visual effects artist. You can use the particle system in Fusion to create realistic weather
elements that move, fall, and drift naturally.
495An Introduction to Visual Effects Compositing
Sometimes it’s just too dangerous to do things on a real set. For example, smoke, flying
debris, and fire are always dangerous when actors and an entire crew are involved. In
many cases, these elements can be shot separately, and you can composite them in later
as a safer yet realistic-looking alternative.
Animals and Kids
The unpredictable nature of working with animals and children can slow each shooting day
to a crawl. Being able to divide and conquer a shot by splitting it up and shooting animals
separately from main action can ensure that you get the shot completed without schedule
overruns. Through seamless compositing, you can combine each section of a frame to
create a realistic split-screen composite that looks like one take.
Sky Replacement
A perfect sunset or a bright blue sky with puffy clouds are great backdrops for any scene,
but weather is out of your control. When everyone is on set, the equipment is rented, and
the clock is ticking, you’ve got to get the shot even when the weather isn’t cooperating.
```
That’s where the (extremely common) art of sky replacement comes in. Fusion’s keyers,
```
rotoscoping tools, tracking, and 3D compositing can remove ugly gray skies or salvage
overexposed skies. Add in some Fast Noise or volumetric effects and that clear blue sky
can include beautiful dramatic clouds that weren’t there during the shoot.
496An Introduction to Visual Effects Compositing
With the 3D controls in Fusion, you also can simulate the light direction, atmospheric haze,
and realistic parallax camera movement—all elements that can make the difference
between a believable sky replacement and a cheap, artificial fake.
Performance/Cosmetic Fixes
Correcting or improving an actor’s not-quite-perfect performance can avoid the need for
expensive reshoots. This common compositing task is rarely noticed by an audience and
can be simple to do, depending on the required fix. For instance, a detail often missed
```
during shooting (but painfully obvious in the screening room) is when an actor portraying
```
a dead body involuntarily moves his eyes. Compositing closed eyes from one frame over an
entire shot is a skill that can save the shot and be repurposed for many similar fixes. The
removal of scars, tattoos, or uneven tan lines all use similar techniques and can be
performed using Fusion’s planar tracker, paint tools, and rotoscoping.
Changing Locations
Production budgets always limit where and when you can shoot a scene, but simple
environmental enhancements can disguise those limits and change the feel of an entire
scene. Such effects can consist of replacing windows in a moving car because you couldn’t
close Times Square to shoot your scene, or “moving” the ground-floor apartment location
you could afford to a penthouse view. These are common tasks for the visual effects artist
and can be very quick fixes for editors and colorists to perform.
Wire Removal
Visual effects are also used to add realism to already dangerous stunts. Getting
performers to fly across the screen from either explosive force or supernatural powers
often requires safety harnesses and wire rigs. You can hide those rigs and wires using
Fusion’s simple clone tools and tracking, a task that editors and colorists can take on in a
pinch when the visual effects artists are busy with larger composites. Plus, the wire
removal skills you use in Fusion techniques can also apply to removing lighting stands,
telephone wires, and unsightly antennas.
497An Introduction to Visual Effects Compositing
Set Extensions
You can take environment enhancements to the next level to create entire set extensions
```
that visually transport your audience to a specific location (while keeping your production
```
```
safe at home on a sound stage). Instead of shipping the whole cast and crew to the
```
Himalayan foothills, you can replace the background of your shots with temples and
mountains and snow. For period pieces or science fiction, such effects can save enormous
amounts of time and money because you don’t have to build massive sets. You just
construct set fragments around your actors and place green screens in the surroundings.
Using the Fusion page during post-production, you can track the camera movement and
replace the greenscreen with 3D extensions to your set.
Motion Graphics
Motion graphics, or motion design, is all about animating graphic elements. It’s the
marriage of visual effects, animation, and graphic design with the goal of presenting
onscreen information. Because information in some form is the objective, text often plays
a primary role in almost every motion design project. The Fusion page includes both
2D and 3D typography tools along with creative paint, Bézier-shape drawing tools, and
incredibly deep spline animation controls. They enable you to create engaging animated
designs that communicate, educate, and entertain.
498An Introduction to Visual Effects Compositing
Learning to See
If you want to create high-quality visual effects, you need to be very conscious of how the
world appears around you. Visual effects must look and feel real, or your audience will stop
believing. The skill to observe the surrounding world in painstaking detail is just as
important as mastering the technical and artistic side of visual effects.
To become a skillful visual effects artist, you must start noticing how light, perspective, and
depth appear in the real world, and then bring those observations into your composites.
If all the elements that make up a composite are meant to be in the same location,
then you must make sure that light hits them all from the same direction. Simulating
relative sizes, parallax motion, and depth to a real-world level of detail is essential to the
realism of an effects shot.
As you begin creating visual effects, start small. The Fusion page is very deep and
incredibly powerful. The beauty of having Fusion built into DaVinci Resolve is that you
```
can jump into creating visual effects with one click; try something out to see if it will work,
```
and then, depending on your skill and the time available, either pass it off to your visual
effects artists or finish it yourself.
Visual effects compositing is about a combination of tools rather than any single filter
effect. It takes time, patience, and experience to do well, but it’s an incredibly exciting
activity that you can learn through experimentation and practice. Eventually, you’ll create
the most thrilling cinematic moments imaginable.
As Walt Disney said, “It’s kind of fun to do the impossible.”
Time
This lesson takes approximately
75 minutes to complete.
Goals
Creating a Fusion Composition 500
The Fusion Interface 502
Adding the First Node 503
The Merge Node 509
Text Creation 512
Keyframes and Animation 517
Quick Changes in the Edit Page 523
VFX Compositing 527
Lesson Review 541
Lesson 9
An Introduction
to Fusion
The Fusion page is where
DaVinci Resolve’s visual effects and
motion graphics capabilities truly
shine. It offers a powerful node-based
compositing system right within your
timeline. Editors, colorists, and visual
effects artists alike will find Fusion’s
tools invaluable for creating complex
effects with ease. The fully integrated
workflow allows you to jump from
the edit page directly to your Fusion
composition without the need for
rendering or transcoding.
500Lesson 9 An Introduction to Fusion
While Fusion’s interface might seem complex initially, mastering its nodes will provide you
with a new level of control and efficiency in your projects. In this lesson, you’ll dive into
Fusion with a motion graphics exercise that will teach you the principles of nodes and
animation. Then, you’ll work on a feature film project to integrate a screen into another
shot, matching its perspective, reflections, depth of field, noise, color consistency, and
other aspects essential to visual effects compositing.
Creating a Fusion Composition
In this first exercise, you’ll create a unique animated title that you can modify and use in
your own projects. You will start by importing a DaVinci Resolve Project that contains
several copies of this lesson’s exercises with different stages of progression so you can
load them if you get lost during the lesson.
1 Open DaVinci Resolve and, in the Project Manager, click the Import button.
2 Navigate to R20 Beginners Guide / Lesson 09, select the project
DR20_Beginners_Lesson 09_FUSION.drp, and choose Open. Once the
project has been imported into the Project Manager, double-click to open it.
3 Choose Workspace > Reset UI Layout.
4 Press Shift-4 to go to the edit page or click the Edit button at the bottom of the screen.
5 Click the Relink Media button.
6 In the Relink Media dialog, click Locate, navigate to the R20 Beginners Guide folder,
and click Open to relink the files.
NOTE The media files for this lesson are located in the MEDIA folder.
501Lesson 9 An Introduction to Fusion
This lesson is structured in two exercises: Lesson 09.1 Motion Graphics and Lesson
09.2 Screen Replacement. Each exercise has its own clips and bins, which you can find
in the media pool. Although you will start the exercises from scratch, you can always
use the catch-up timelines, which contain multiple versions of the Fusion compositions
you will work on, with every step already included. So if you get lost during this lesson,
simply jump into the catch-up timeline and load the Fusion composition you need. For
example, in the first exercise, you’ll find the Lesson 09.1.1 CatchUp Versions - Motion
Graphics timeline in the Master > Lesson 09.1 Motion Graphics > Timelines bin. The
finished exercise is located at timecode 00:01:30:00.
7 Ensure that the Lesson 09.1.0 START HERE timeline is open. If not, you will find it in
the Lesson 09.1 Motion Graphics > Timelines bin.
8 In the top left of the interface, click the Effects button to open the Effects Library,
navigate to Toolbox > Effects, and select and drag the Fusion Composition to the
beginning of the timeline. By default, it will be 5 seconds long.
```
9 Place the playhead over the Fusion Composition you just added to the timeline (it
```
```
should already be positioned at the start of the timeline), and then press Shift-5 to
```
jump to the Fusion page or click the Fusion button at the bottom of the interface.
502Lesson 9 An Introduction to Fusion
The Fusion Interface
Welcome to the Fusion page! Fusion’s interface is divided into four main areas: the viewers
```
at the top, where you can preview your work (the one on the left is viewer 1, and the one on
```
```
the right is viewer 2); the Node Editor at the bottom, where you build and manage your
```
```
node tree; the Inspector on the right, which lets you adjust the parameters of the selected
```
```
node; and the media pool and Effects Library on the left, which provide access to a wide
```
```
range of tools and effects (you need to open them by clicking the Media Pool or Effects
```
```
buttons at the top left of the screen, just like in the edit page). You can also open the Spline
```
Editor and Keyframes Editor with the buttons at the top right.
The toolbar has buttons
for adding commonly
used effects or tools
to the Node Editor.
The left and right viewers
can show different images or
effects from your composite.
The work area can show
any combination of the
Node Editor, Keyframes
Editor, or Spline Editor.
The Navigator is a
miniature representation
of the entire node tree
```
(press V to enable it).
```
In the Inspector, you can display and
manipulate the parameter of any
selected effect or tool in the Node Editor.
503Lesson 9 An Introduction to Fusion
In the middle of the interface, you will find the transport controls with the Render Range
```
on the left (from frame 0.0 to 119.0) and the Current Time on the right (starting at
```
```
frame 0.0). Below these controls is the toolbar, which provides quick access to commonly
```
used tools and effects. In this exercise, you will use the Background, Text+, Merge,
```
Transform, and Rectangle tools; try to locate them.
```
Adding the First Node
Currently, your composition only has the MediaOut1 node, which determines what gets
rendered back to the edit and color pages. Your goal is to create an animated title, so you
will first create a rough draft of the background and text, and then move on to the
animation of a white background with a black rectangle on top, containing a main title and
a second line of text, both in white.
You’ll start by adding a Background node, which will serve as the foundation for
your composition.
504Lesson 9 An Introduction to Fusion
```
1 Locate the Background tool in the toolbar (it’s the first icon on the right), and then click
```
and drag it to the Node Editor.
```
2 Click the gray square on the right of the Background1 node (node output) and drag
```
with the mouse to connect the pipe to the orange triangle of the MediaOut1 node
```
(node input).
```
Anything connected to the MediaOut1 node will be rendered out, and that’s what you
will see in the edit and color pages. If you don’t connect anything to MediaOut1, you
won’t see any image when you return to the edit page.
```
To break the connection, hover your cursor over the pipe (the white connection line).
```
When it changes to blue and yellow, double-click it if you are on the blue side, or click it
if you are on the yellow side of the pipe. You can also hold down the Shift key and click
and drag the node to disconnect it. Note that when you hover over a node or
connection, a small window will appear with information, which is also displayed at the
bottom left of the screen.
505Lesson 9 An Introduction to Fusion
3 The Inspector panel should be open at the right side of the screen. If not, open it by
clicking the Inspector button at the top right of the screen. You can expand or shrink
the Inspector by clicking the icon to the right of the Inspector button.
4 Select the Background1 node and, using the controls in the Inspector, change the
color to white. You can either click the color box and select the color you want or set
the Red, Green, and Blue values to 1.0 each.
5 Press F2, or right-click Background1 and choose Rename, and rename the
Background1 node WhiteBackground.
506Lesson 9 An Introduction to Fusion
NOTE This exercise uses “camel case” when renaming the nodes, where the
first letter of each word is capitalized. In Fusion, names cannot contain spaces,
but you can also separate words using a period or other characters.
```
6 Deselect all by pressing Command-Shift-A (macOS) or Ctrl-Shift-A (Windows). Add a
```
new Background node to the Node Editor and rename it BlackBackground.
```
7 With the BlackBackground node selected, locate the Rectangle tool (it’s in the middle
```
```
of the toolbar, the first icon in the fourth segment) and click it.
```
8 Next, select the WhiteBackground node and click the small left dot under the node to
load it into the left viewer. You can also press 1 on your keyboard to load it into the left
viewer or simply drag the node there. You’ll see the name of the loaded node displayed
at the top of the viewer.
507Lesson 9 An Introduction to Fusion
9 Select the BlackBackground node and press 2 to load it into the right viewer.
You have masked the BlackBackground node, and now it’s a rectangle. The square
```
(node output) of Rectangle1 is connected to the blue triangle (effect mask) of
```
BlackBackground. You should adjust the shape of the rectangle so that it covers the
full width of the screen.
Loading Nodes into the Viewers
Hover over a node and click the button at the bottom left.
```
Click the node and press 1 (for the left viewer) or 2 (for the right viewer).
```
Right-click the node in the Node Editor or its header in the Inspector, and then
choose View On > None/Left View/Right View.
Drag and drop the node onto a viewer.
To clear viewers:
— Press 1 or 2 to clear the left or right viewer.
```
— Press ` (the Accent key) to clear both viewers.
```
508Lesson 9 An Introduction to Fusion
10 Select Rectangle1 and, in the Inspector, set the Width to 1 and the Height to 0.35.
```
TIP The pipes can be either direct lines or orthogonal (horizontal and vertical
```
```
with 90º bends). To make them orthogonal, right-click the background of the
```
Node Editor and select Options > Orthogonal Pipes. In the same menu, you’ll
also find the option Line Up All Tools to Grid, which can be useful for tidying up
your nodes, and Force Source Tile Picture, which adds a small thumbnail to
every node that is loading an image in the Node Editor.
509Lesson 9 An Introduction to Fusion
The Merge Node
Now that we have the two basic elements of our background, let’s combine them. To do
this, we’ll add a Merge node, which is the ninth icon in the toolbar.
1 Deselect everything and click the Merge icon to add it to the Node Editor.
The Merge node is the primary tool used to composite one image over another.
It has three inputs:
```
— Background (orange): The image connected to this input determines the output
```
resolution of the Merge node.
```
— Foreground (green): This input is for the image you want to be “on top.”
```
```
— Effect Mask (blue): An optional input for attaching a mask or matte to limit the
```
effect of the Merge node.
Background Input
Foreground Input
Effect Mask
Merge Output
You have a WhiteBackground and a masked BlackBackground. Take a moment to think
about which element you would connect to each input.
```
2 Click and drag the output of the WhiteBackground (the small gray square) to the
```
orange input of the Merge1 node.
3 Connect the masked BlackBackground to the green input of the Merge1 node.
```
4 Finally, connect the output (square) of the Merge1 to the MediaOut1 input.
```
510Lesson 9 An Introduction to Fusion
5 Once you have the nodes connected correctly, load the MediaOut1 node into viewer 2
by selecting MediaOut1 and pressing 2 on your keyboard.
You should see a black rectangle on top of a white background.
```
TIP If you accidentally connect the nodes the wrong way around (the background
```
```
clip to the foreground input and the foreground clip to the background input),
```
```
simply press Command-T (macOS) or Ctrl-T (Windows) to switch them.
```
In Fusion, it’s the color of the connections that matters, not their position. Fusion may
adjust the placement of inputs around the node for better organization. For instance,
moving the Rectangle1 node to the left of the BlackBackground will shift the blue triangle/
arrow to the left side of the node.
You can arrange nodes in any way you prefer. As long as the connections remain the same,
your final image won’t be affected. However, keeping nodes organized logically helps you
understand your work better.
511Lesson 9 An Introduction to Fusion
Navigating in the Fusion Page
Now that we have some nodes added to our Fusion composition, let’s learn how to
navigate the Fusion page. Mouse and keyboard commands in Fusion are context-
sensitive, meaning the same inputs can produce different effects depending on
where your mouse pointer is located. A three-button mouse is recommended for
Fusion, where pressing the scroll wheel functions as a middle click. Alternatively, a
pen and tablet can also be a good option.
```
1 Panning (the Node Editor and viewers):
```
Hold the middle mouse button and drag to pan the node tree. You can also
```
press Command-Shift and left-click (Ctrl-Shift and left-click on Windows).
```
```
2 Zooming (Node Editor and viewers):
```
Hold the left and middle mouse buttons and drag left/right or use Command-
```
scroll wheel (Ctrl-scroll wheel on Windows).
```
3 Fit image to viewer:
```
Click a viewer and press Command-F (macOS) or Ctrl-F (Windows) to fit
```
the image.
4 Zooming steps:
Use the + and – keys to zoom in/out in discrete steps.
```
Press Command-1 (macOS) or Ctrl-1 (Windows) to zoom to 100%, and
```
```
Command-2 (macOS) or Ctrl-2 (Windows) for 200% zoom.
```
These navigation commands also apply to both viewers, the Spline Editor, and the
Keyframes Editor.
512Lesson 9 An Introduction to Fusion
Text Creation
It’s time to add some text. The Text+ node is the main tool for creating and animating 2D
text in the Fusion page and is also available in the edit page. It offers extensive options for
text effects, including six tabs of controls for text styling, layout methods, and shading
options such as fills, outlines, shadows, and borders. While you’ll only scratch the surface
here, the Text+ node is an incredibly powerful tool with endless possibilities.
1 Select Merge1, and then click the Text+ icon, which is the third tool in the toolbar.
2 A new Text+ node and a Merge2 node will appear, connecting your Text1 node to the
green Foreground Input of the Merge2 node, which will be on top of the background.
NOTE If you select a node in the Node Editor before adding a new tool, the
new tool will connect to the selected node. Selecting a node also shows its
default parameters in the Inspector and adds a toolbar specific to that node at
the top of the viewer.
If the Text1 node appears at the bottom of the node tree, don’t worry. The only thing
that matters is the connections: Text1 should be connected to the green input of
Merge2. To maintain order, we can click and drag the nodes to rearrange them.
513Lesson 9 An Introduction to Fusion
3 Press F2 and rename the Text1 node TitleText.
4 With the TitleText node selected, type DAVINCI RESOLVE into the text box in the
Inspector and set the size to 0.18.
```
TIP You can turn off (or pass through) any node by pressing Command-P
```
```
(macOS) or Ctrl-P (Windows), or by clicking the node’s Enable button in
```
the Inspector.
Next, you’ll add another line of text in a different node. To do that, you’ll need to move
your existing text up to create space for the new line. There are several ways to adjust
the text position: by using a Transform node, by adjusting the Center values in the
Layout tab, or by modifying the Offset values in the Transform tab of the Text+ node.
You can also change the Center value in the Merge2 node. For this exercise, we have
minimized the variety of tools used, but you will find that there are many ways to
achieve the same result, each with its own pros and cons.
5 As you already have the TitleText node selected, look for the Transform node on the
Toolbar and click it.
You should have the Transform node connected between TitleText and Merge2. This
way, the Transform will affect everything that is connected to its input. With this setup,
you can move the text upward.
514Lesson 9 An Introduction to Fusion
6 Select the Transform, go to the Inspector, and change the Center Y value to 0.54.
Next, you will add a secondary line of text using the nodes you just learned.
```
7 Select the Merge2 node and add a new Text+ node (click the third icon in the toolbar).
```
This will add a Merge3 and a Text1 node. Rename the Text1 node SubtitleText.
TIP You could also copy and paste the TitleText we created earlier, and reset
some of the values.
515Lesson 9 An Introduction to Fusion
8 In the SubtitleText node, type MOTION GRAPHICS IN FUSION in the edit box, change
the font to Courier New, Regular, and set the size to 0.085.
The subtitle text is in front of your main TitleText. You’ll add a Transform node to
correct that.
9 Select the SubtitleText node and click the Transform node icon on the toolbar.
10 Select the new Transform2 node and change the Center Y value to 0.41.
516Lesson 9 An Introduction to Fusion
The Time Ruler and Transport Controls
With the design in place, it’s time to start animating. You are about to add keyframes, so
you’ll need to review your composition in motion. The Time Ruler, located beneath the
viewer area, reflects the total duration of the composition. The range displayed on the
Time Ruler depends on what’s currently selected in the edit or cut page timeline.
The render range determines the range of frames used for interactive playback, disk
caches, and previews. Frames outside the render range are not rendered or played,
although you can still drag the playhead to these frames to see the unused frames. In this
exercise, you’ve created a 5-second Fusion Composition at 24 frames per second, so it’s a
total of 120 frames from frame 0 to frame 119.
Underneath the Time Ruler, you’ll find the six transport controls that you’re already familiar
with from the other pages: Composition First Frame, Play Reverse, Stop, Play Forward,
Composition Last Frame, and Loop.
To move the playhead using the keyboard, you can use the same controls as in the edit
```
page (JKL, Left Arrow, Right Arrow), along with these additional commands:
```
— Shift-Left Arrow: Jumps to the clip’s Global Start frame
— Shift-Right Arrow: Jumps to the clip’s Global End frame.
```
— Command-Left Arrow (Ctrl-Left Arrow on Windows): Jumps to the Render
```
Range In point.
```
— Command-Right Arrow (Ctrl-Right Arrow on Windows): Jumps to the Render Range
```
Out point.
517Lesson 9 An Introduction to Fusion
Keyframes and Animation
You’ll begin by animating the black rectangle using a Transform node and adding
keyframes in the Inspector. Afterward, you’ll refine the keyframe curves in the Keyframes
Editor panel and then move on to animating the Text nodes. You will start by adding and
connecting the Transform node.
1 Select the BlackBackground node, locate the Transform node on the Toolbar, and
click it. It should be added after the BlackBackground.
The Transform node will help us move and animate different elements in our composition.
2 Go to frame 24 by entering 24.0 in the Current Time box at the top right of the
Time Ruler.
3 Select the new Transform3 node. In the Inspector, click the gray Keyframe button to
```
the right of the Center value (it will turn red).
```
518Lesson 9 An Introduction to Fusion
4 Go to frame 0 and change the Center X value to -0.5.
You’ll see a white line at frames 0 and 24 indicating the keyframes.
5 Move to frame 107 and click the gray Keyframe button again to the right of the
Center value.
6 Go to frame 119 and change the Center X value to 1.5.
```
If you click Play on the transport controls or press the Spacebar (JKL playback also
```
```
works), you’ll see the black rectangle entering from the left, staying at the center for a
```
moment, and then exiting to the right. The animation is a bit abrupt, so you’ll need to
smooth out the keyframes at frames 24 and 107 in the Keyframes Editor.
7 Click the Keyframes button at the top right of the interface.
8 In the Keyframes Editor, click the Zoom To Fit button and click the expand icon to the
left of Transform3.
519Lesson 9 An Introduction to Fusion
```
9 Click and drag to select the keyframes at frames 24 and 107 (the middle ones). When
```
```
they are yellow (selected), press F to flatten the curve.
```
This adjustment will make the rectangle decelerate as it reaches the center and then
accelerate from frame 107 to exit the screen.
10 Close the Keyframes Editor.
Animating the Text
Your composition is looking great, but you still need to animate the text. To do this, you’ll
create keyframes so that the text starts to appear as soon as the black rectangle appears
on the screen and disappears just before the rectangle moves off to the right. We’ll
animate the Write On parameter within the Text+ nodes to achieve this. Additionally, for
the main title, we’ll change its material once it finishes typing by adjusting the Appearance
parameter in the Shading tab. Finally, we’ll add a mask to Merge3 and use a Transform
node to animate the second line of text, allowing it to drop down behind the main text.
Let’s get started!
1 In the Node Editor, select the TitleText node.
At the bottom of the Inspector, you’ll find the Write On controls, which are used to
quickly apply simple Write On and Write Off effects to the text.
2 Go to frame 36 and click the gray Keyframe button to the right of the Write On control.
3 Move to frame 24 and change the Write On End value to 0.0.
If you play the composition, DAVINCI RESOLVE will be written right after the black
rectangle stops in the middle of the screen.
520Lesson 9 An Introduction to Fusion
4 Go to frame 84 and again click the gray Keyframe button to the right of the Write
On control.
5 Move to frame 107 and change the Write On Start value to 1.0.
The Text+ node has many options and tabs you can select at the top of the Inspector.
We’ve only worked in the Text tab so far, but now we’ll make some changes in the
Shading tab.
6 Go to the Shading tab.
7 Move to frame 44.
```
8 Locate the Appearance option below Properties and add a keyframe (click the gray
```
```
keyframe button to the right of Appearance).
```
```
9 Move one frame to the left (to frame 43) and select the second icon in the Appearance
```
```
options: Text Outline.
```
At this point, your main text transitions from an outline to a solid color. Let’s move on
to the second line of text to incorporate some movement and animations.
```
First, you’ll add a Write On animation at the end (like you did with the TitleText node).
```
10 Select the SubtitleText node.
521Lesson 9 An Introduction to Fusion
11 Go to frame 84 and click the gray keyframe button to the right of the Write On control.
12 Move to frame 107 and change the Write On Start value to 1.0.
With that animation complete, you’ll add keyframes to the Transform2 node so that the
SubtitleText appears below the main title.
```
13 Select the Transform2 (the one that modifies the position of SubtitleText).
```
```
14 Go to frame 60 and add a keyframe to the Center Y value (that should be 0.41) by
```
clicking the gray keyframe button to the right.
15 Go to frame 48 and change the Center Y value to 0.52.
The only thing missing is a way to mask out the SubtitleText before it moves down into
its place. You can use another rectangle, but this time you’ll apply it to the
Merge3 instead.
16 With Merge3 selected, click the Rectangle icon in the toolbar to add a Rectangle2 node
connected to the Effect Mask input of the Merge3 node.
522Lesson 9 An Introduction to Fusion
17 Select the Rectangle2 node and change the Width to 1.0 and the Center Y to 0.21.
At this point, the subtitle animates down into its place. You could make the keyframe
on frame 60 smoother in the Keyframes Editor, just like you did with the animation in
the Rectangle1 node. Want to try it out?
18 Open the Keyframes Editor and click Zoom To Fit.
19 Expand the keyframes for the Transform2 node. Select the second keyframe and press
F to flatten the curve.
20 Close the Keyframes Editor.
523Lesson 9 An Introduction to Fusion
Congratulations, this is your final composition! If you got lost along the way, you can find
the final composition in the Timeline Lesson 09.1.1 CatchUp Versions - Motion Graphics
timeline at timecode 00:01:30:00. There is a red marker and a brief explanation. You’ll also
```
find every step of the process in this timeline; just read the text in the markers. In the
```
finished composition, you will find some sticky notes with details about the
keyframes created.
Quick Changes in the Edit Page
With this composition, you can quickly create many variations directly in the edit page.
1 Press Shift-4 to go back to the edit page.
2 Duplicate the Fusion Composition in the timeline. On Windows, you can use Ctrl-C to
copy and Ctrl-V to paste. On macOS, use Command-C to copy and Command-V to
paste. Alternatively, you can hold down the Alt key on Windows or the Option key on
macOS, and then click and drag the composition to duplicate it.
524Lesson 9 An Introduction to Fusion
```
3 Click the Effects button at the top left of the interface to open the Effects Library (if it’s
```
```
not already open).
```
4 Navigate to Open FX > Filters > Resolve FX > Resolve FX Color category and select and
drag the Invert Color effect onto the copy of your composition.
After applying the effect, you have a variation where what was black is now white, and
```
vice versa. But you can take this a little further and use both versions (normal and
```
```
inverted) of your title to mask a video!
```
525Lesson 9 An Introduction to Fusion
Inside the Lesson 09.1 Motion Graphics bin, you’ll find a 10-second shot of CyberBox,
an ICVFX Virtual Production project shot by Nahuel Srnec using a Blackmagic URSA
Mini Pro 4.6K G2 in an LED volume. This is not the raw media, but it provides a preview
of the capabilities of this cinema camera for Virtual Production, thanks to its dynamic
range, resolution, SDI input, SDI output, and Ref/Timecode connections, which are
essential for ICVFX work. We can use this clip in combination with the title we’ve
just created.
5 Add the CyberBox-0001_BMDUrsa4.6KPro.mov clip to the timeline in the edit page.
6 Place two copies of your composition right above that clip on a new video track.
526Lesson 9 An Introduction to Fusion
7 Select one of those copies of the animated title composition, open the Inspector, and
set the Composite Mode to Screen.
8 Set the other copy to Multiply.
There are some additional examples for you in the timeline Lesson 09.1.2 FINISHED &
Variations, which are simple variations of the original composition. If you’d like, you can
look at them by loading that timeline on the edit page.
527Lesson 9 An Introduction to Fusion
VFX Compositing
By now, you should have a good understanding of the basics of Fusion. In this next
exercise, you will explore more tools and learn how to navigate nodes and viewers more
effectively. This second exercise involves a screen replacement and the introduction of new
techniques. To integrate the screen content into another image, you’ll need to match its
perspective, reflections, depth of field, noise, color consistency, and other essential
aspects of visual effects compositing.
You’ll work with footage from the feature film Machine for the Aura, directed by Ana
Monserrat and Nahuel Srnec. The film was shot on a Blackmagic Pocket Cinema Camera
4K, premiered at the Warsaw International Film Festival, and later screened in competition
at the Beijing International Film Festival. You can read a full article about its post-
production workflow on the official Blackmagic Design website:
```
https://www.blackmagicdesign.com/media/release/20211221-02
```
You won’t be working with the original camera files but with a proxy version in a different
format, with a smaller resolution, lower bit depth, smaller size, and different color space
and gamma settings. This is to reduce the load on your system.
1 In the edit page, open the Lesson 09.2 Screen Replacement bin, and load the timeline
Lesson 09.2.1 START Screen Replacement.
This timeline contains 10 copies of the Fusion Composition, each representing a
different step in the process. There is also a marker above each composition with a
brief explanation of the corresponding step. If you get lost at any point during this
528Lesson 9 An Introduction to Fusion
lesson, you can always return to this timeline to find the spot where you want to catch
up with the exercise.
The second clip in the timeline requires some VFX work: you need to replace the
laptop’s screen with the clip in Video Track 2.
Enable Video Track 2 to view the video that you will composite over the original laptop
```
screen. Once you’ve done that, disable Video Track 2 again (we’ll bring that video from
```
```
Video Track 2 into the Fusion Composition using a different technique).
```
You can also go to timecode 01:01:00:00 to get an idea of the final composition we
will create.
```
2 Place the playhead over the second clip in the timeline (timecode 01:00:02:18).
```
3 Go to the Fusion page by pressing Shift-5 or clicking the Fusion button at the bottom
of the interface.
529Lesson 9 An Introduction to Fusion
When you jump to the Fusion page with a clip under the playhead, Fusion will
automatically create a Fusion Composition with the clip as the MediaIn1 node at the
clip’s resolution. In this case, the clip and the timeline happen to have the same
resolution, but that won’t always be the case.
TIP Note that the time ruler in the Fusion page shows frames instead of
timecode, as in the other DaVinci Resolve pages. This is because working with
frames is the common practice in VFX. If you prefer to use timecode, go to the
```
Fusion menu (at the top of the screen) and select Fusion Settings. In the
```
Defaults tab, you’ll find the Show Timecode option.
```
4 Press F2 (or right-click MediaIn1 and select “Rename…”) and rename MediaIn1 to Plate.
```
```
NOTE In visual effects (VFX), the term plate refers to the base or background
```
elements of a composition because it historically comes from the use of
physical film plates. Originally, a “plate” referred to a piece of film stock used to
capture a background scene or base footage. In digital compositing, this term
has carried over to denote the foundational layers or background elements to
which other visual effects are added. Essentially, the “plate” serves as the
starting point or background upon which additional elements, such as CG or
effects, are composited.
530Lesson 9 An Introduction to Fusion
5 Open the media pool by clicking the Media Pool button at the top left of the screen,
go to the Lesson 09.2 Screen Replacement bin, and drag the MaquinaParaVerElAlma-
0004_DSLR.mov clip to the Node Editor.
6 A new MediaIn node will be created. Press 1 to load it in the left viewer and rename it
ScreenContent.
7 Close the media pool.
8 Right-click the gray area of the Node Editor and select Force Source Tile Pictures to
enable a thumbnail in each MediaIn node.
NOTE The first time you create thumbnails, they may not display the images.
To fix this, select the Plate and ScreenContent nodes, load them into any
viewer, and move the playhead to load the images.
531Lesson 9 An Introduction to Fusion
9 Add a Merge node to composite the ScreenContent over the Plate. Make sure the
```
ScreenContent is connected to the green (foreground) input.
```
In this exercise, you’ll explore new tools and a quicker way to add them. Up to this
```
point, you’ve relied on tools from the toolbar; next, you’ll use the Select Tool dialog,
```
which is much faster—as long as you know the name of the tool you’re looking for. In
the Select Tool dialog, you can find all the nodes and tools available in Fusion. Since the
list is extensive, you’ll use the search box to quickly locate what you need.
10 Select the ScreenContent node and press Shift-Spacebar to open the Select
Tool dialog.
11 Type corner in the Select Tool dialog.
532Lesson 9 An Introduction to Fusion
12 Select the Corner Positioner and click the Add button.
A CornerPositioner1 node is added after the ScreenContent node.
13 For this composition, it’s better to have a single, larger viewer instead of two. To
achieve this, press the Viewer button at the top right of the viewer. To re-enable both
viewers, simply press it again.
14 Click in the viewer and drag each corner of the Correct Positioner so it matches the
laptop screen.
TIP Remember to zoom and reposition the viewer using Command-scroll
```
wheel (macOS) or Ctrl-scroll wheel (Windows) for more control and precision.
```
533Lesson 9 An Introduction to Fusion
Integrating the Elements
You’ve lost all the reflections from the original shot, so you’ll try a compositing trick to
recover them by changing the Apply Mode in the Merge node. This process is similar to
changing the Composite Mode in the Inspector on the edit page. You’ll also decrease the
Blend, so the ScreenContent isn’t at 100% opacity, allowing some of the reflections and
noise from the Plate to show through.
1 Select the Merge1 node, go to the Inspector, and change the Apply Mode to Screen
and the Blend to 0.6.
Now that you have recovered the real reflections, there is still a noticeable difference in
the definition and depth of field between the Plate and the ScreenContent, which is
too sharp. You’ll add a blur to soften the ScreenContent and mask it so that it’s softer
at the edges and sharper in the center.
```
2 Add a Blur node after the Corner Positioner (it’s the eighth icon in the toolbar, or
```
```
search for Blur in the Select Tool dialog).
```
534Lesson 9 An Introduction to Fusion
3 Change the Blur Size in the Inspector to 2.0.
Your Node Editor should display the following:
```
4 With the Blur node selected, add an Ellipse (the icon to the right of the rectangle in the
```
```
middle of the toolbar).
```
Notice that the blur now affects the image only inside the ellipse, which is the opposite
of what you wanted!
535Lesson 9 An Introduction to Fusion
```
5 Select the Ellipse1 node, check the Invert option in the Inspector (to make the blur
```
```
work outside the circle), and set the Soft Edge to 0.2.
```
6 Adjust the position and size so that it subtly affects the center of the laptop screen,
with more intensity at the edges. If you’re unsure, use the following settings as a
```
guide: Center X 0.64, Y 0.57, Width 0.22, Height 0.36, Angle 0.35.
```
You might think we could apply the Blur node before the Corner Positioner, but if
you do that, the edges created by the Corner Positioner when it distorts the image
won’t be blurred.
Next, you’ll correct the white and black levels, saturation, and color of the
ScreenContent. You’ll use a Color Corrector node. Note that the color grading of the
final composition is usually done by a colorist in the color page, but the VFX artist is
responsible for correctly matching each element of the composition with the others.
536Lesson 9 An Introduction to Fusion
TIP To better evaluate luminance levels, activate the waveform in your viewer
by clicking the SubView icon at the top left and selecting Waveform. You can
resize it as needed. You can also access the Gain and Gamma controls by
```
clicking the Options (…) menu at the top right of the viewer, which will help
```
with matching.
```
7 Click the Options (…) button at the top right of the viewer and select Gain/Gamma.
```
537Lesson 9 An Introduction to Fusion
This will open the Gain/Gamma controls, which only affect the visualization and have
no impact on the processing or final render. These controls will help you accurately
evaluate the integration of elements. You can raise the Gain to better assess the
shadows. To deactivate these changes in the viewer, simply return to the Options
menu and click Gain/Gamma again.
8 Raise the Gain value to better assess the shadows. Look for similar shadow levels in
both the Plate node and the ScreenContent node.
```
9 After the Blur, add a Color Corrector node (it’s the fifth icon in the toolbar).
```
10 In the Inspector, reduce the Saturation to around 0.92 and add a hint of green by
clicking and dragging the color wheel toward green.
538Lesson 9 An Introduction to Fusion
11 Adjust the Gain and Lift so the SrceenContent blends with the Plate. I used 1.32 for the
Gain and 0.03 for the Lift.
Wait! Something strange happened! Adjusting the Lift value also affected the
background. This happens because the image uses premultiplied RGB channels, where
the color data is already blended with the alpha channel. To correctly adjust the
foreground without impacting the background, you need to unmix the RGB values
from the alpha channel before applying color correction. After correction, recombine
the RGB and alpha channels. This is covered in detail in The Visual Effects Guide to
DaVinci Resolve, but the solution is in the Options tab.
539Lesson 9 An Introduction to Fusion
12 Go to the Options tab and check the Pre-Divide / Post-Multiply function.
You’re almost there! We still need to match the noise levels of the foreground object to
those of the background. Noise levels can vary due to factors such as the camera
sensor, ISO/gain settings, shadow levels, and even the temperature on the shooting
day. To seamlessly integrate the two elements, the noise should match. In this
instance, the difference is barely noticeable, especially since we changed the Apply
Mode to Screen and lowered the Blend in the Merge node. However, you’ll add a bit of
noise to make it nearly perfect and to show you this technique for your future projects.
```
13 Deactivate the Gain/Gamma controls in the viewer by clicking the Options (…) menu
```
and the Gain/Gamma option.
14 Select the Color Corrector node, press Shift-Spacebar, and type grain. Select Grain
```
(Grn) and click Add.
```
540Lesson 9 An Introduction to Fusion
15 Zoom in to the viewer and adjust the Power and Grain Size of the Grain node in the
Inspector in order to match the texture of the ScreenContent with the grain and noise
of the Plate. Good values are setting the Power to 1.4 and Grain Softness to 3.0.
NOTE “Noise” and “grain” are not synonyms. However, we are simplifying the
explanations in this training guide to cover the Fusion exercises fully.
Since this is meant to simulate an old LCD laptop screen, the opacity shouldn’t be
completely uniform. To achieve this effect, you can add an Ellipse to the Merge1 node
so that the screen content becomes less visible in the corners.
16 Select the Merge1 node and click the Ellipse tool in the toolbar to add it connected to
that node.
541Lesson 9 An Introduction to Fusion
17 Modify the Soft Edge value to 0.2 in the Ellipse2.
18 Modify its size, height, and angle so that the screen content is solid in the middle of the
screen but loses a bit of opacity toward the corners.
That’s it! You did it! You’ve successfully completed this chapter and taken your first steps
into the world of VFX with Fusion inside DaVinci Resolve. There is so much more to explore,
from advanced tracking and 3D compositing to USD integration and beyond. You’ve only
scratched the surface of what Fusion can do, but hopefully this chapter has given you a
solid understanding of the power and flexibility of node-based compositing. Fusion is a
fantastic tool and, with practice, you can master it to create incredible visual effects. Keep
experimenting, keep learning, and let your creativity lead the way!
Lesson Review
1 On the Fusion page, how can you display the output of a node in viewer 1?
2 When clicking a tool in the toolbar, where is the node added?
3 What node would you use to blend two images?
4 What does the orange input on a Merge node represent?
5 True or False? When on the Fusion page, you can disconnect the MediaOut node
because you have no use for it.
542Lesson 9 An Introduction to Fusion
Answers
1 On the Fusion page, to display the output of a node in viewer 1, select the node and
press the 1 key. You can also drag the node to the viewer or click the small left dot
under the node in the Node Editor.
2 The new node is added directly after the selected node in the Node Editor.
3 A Merge node is used to composite two images.
4 The orange input on the Merge node is for the background input.
5 False. The MediaOut node is always the last node connected, and it renders the Node
Editor results back to the edit page timeline.
Time
This lesson takes approximately
75 minutes to complete.
Goals
Preparing the Project 544
Creating Vertical Timelines 545
Changing Timeline Settings 552
Reframing Shots 556
Using the Deliver Page 570
Optimizing Audio Standards 571
Customizing Deliver Presets 574
Saving a Render Preset 577
Adding the Vertical Timeline 579
Reviewing the Jobs 581
Rendering the Jobs 584
Exporting Timelines and
Project Files 586
Media Management 587
Creating a Project Archive 592
Creating and Switching
Project Libraries 593
Copying Projects Between
Project Libraries 596
Backing Up Project Libraries 598
Lesson Review 599
Lesson 10
Delivery and Media
Management
In Lesson 3, you used the Quick Export
```
function to easily and quickly output a
```
single video file suitable for uploading
to a social media or video sharing site.
The Quick Export window is very useful
for generating a file that you can use
either as a final deliverable or simply as
a way of showing the director or client
your current progress on an edit with
the fewest number of mouse clicks.
However, if you want more control over
your output files, as well as the ability
to batch-process multiple files, then
the deliver page is the place to conduct
your business.
However, delivery is often much more
than exporting a single video file.
Once the edit is complete, the grade
applied, the VFX shots created, and
the mix perfected, you might need to
deliver different versions for different
platforms, particularly in this age of
social media.
544Lesson 10 Delivery and Media Management
In this lesson, you will look at some of the additional considerations you may need to take
```
into account before outputting your final deliverable file(s), including adding subtitles and
```
reformatting an existing timeline to a new aspect ratio and using the flexible options
available in the deliver page.
Preparing the Project
For this lesson, you will work with a completed version of the Organ Mountain Outfitters
promo you have been working with at various times throughout this book.
1 Launch DaVinci Resolve and, in the Project Manager, click the Import button.
2 Navigate to R20 Beginners Guide / Lesson 10, select the file
OMO PROMO DELIVER.drp, and click Open.
3 Once the project has been imported into the Project Manager, double-click it to open
the project.
4 When the project has opened, select the edit page and choose Workspace > Reset
UI Layout.
5 Click the Relink Media button at the top of the media pool.
6 In the Relink Media window, click Locate, navigate to the location of the R20 Beginners
Guide folder on your system, and click Open to relink the files.
You are now ready to continue with this lesson.
545Lesson 10 Delivery and Media Management
Creating Vertical Timelines
While most modern video cameras still shoot traditional 16:9 aspect video footage, that
doesn’t necessarily mean you are always required to deliver 16:9 footage. With many
videos watched on mobile devices, many social media content creators prefer an
```
alternative aspect ratio, such as 1:1 (square formats such as those favored by Instagram)
```
```
or 9:16 (vertical formats common on TikTok and YouTube Shorts). DaVinci Resolve allows
```
you to customize your timeline settings for several aspect ratios. In this next exercise, you’ll
learn how easy it is to repurpose a timeline to fit a vertical aspect ratio.
To begin, you’ll need to duplicate the current timeline.
1 Choose Timeline > Find Current Timeline in Media Pool.
2 With the current timeline selected, choose Edit > Duplicate Timeline, or right-click the
selected timeline and choose Duplicate Timeline to create a copy of the OMO PROMO
FINAL timeline.
3 Select the duplicated timeline, click the name to highlight it, rename it OMO PROMO
```
TIKTOK, and press Enter (Return).
```
4 Double-click the OMO PROMO TIKTOK timeline or select it from the timeline viewer
menu to open it.
The Safe Guides can help you get a sense of what the footage in this timeline will look
like once it’s presented in a vertical timeline.
546Lesson 10 Delivery and Media Management
5 In the Guides menu, disable the Default guide and enable the 9:16 Social Media option.
6 In the timeline, place the playhead over the graphic clip near the start and ensure that
no clips are selected.
547Lesson 10 Delivery and Media Management
This graphic and other shots will need to be reframed for a vertical 9:16 aspect ratio.
To easily identify and locate these shots later, you can add markers to the timeline.
However, since the timeline currently has a set of markers used for the audio editing in
the previous lesson, it would be helpful to use a different color for these new markers.
7 In the timeline toolbar, click the Marker menu icon and choose Green from the list of
marker colors to add a green marker.
TIP You can always change a marker’s color in the Marker window.
548Lesson 10 Delivery and Media Management
8 Double-click the marker in the timeline to open the Markers dialog. Change the name
of the marker from Marker 1 to REFRAME 1, and then click Done.
9 In the timeline, move over the clip PINA BLANCA 44, the wide shot of the guy looking
out over the rocks.
549Lesson 10 Delivery and Media Management
10 Click the Marker button again, or press M, to add another green marker.
11 Press M again, or double-click the new marker in the timeline or the timeline viewer to
open the Markers dialog. Change the marker’s name from Marker 2 to REFRAME 2,
and then click Done.
550Lesson 10 Delivery and Media Management
12 Move over the clip WHITE SANDS 11.
To get all the people in this shot, you will need to create a pan.
13 In the timeline toolbar Marker menu, select Red to add a red marker to the timeline.
551Lesson 10 Delivery and Media Management
14 Double-click the red marker and rename Marker 3 PAN 1.
15 Move to the low-angle shot of the guy jumping on the rocks, PINA BLANCA 48, add
another red marker, and rename it PAN 2.
552Lesson 10 Delivery and Media Management
16 Click the Guides button in the timeline viewer to turn off the onscreen guides.
To simplify the markers in the timeline, you can choose to hide the colors you’re not
currently using.
17 Choose View > Show Markers > Blue to turn off the blue markers in the timeline.
You will use these timeline markers to quickly locate these clips in later steps.
Changing Timeline Settings
Currently, you only have a copy of your original timeline, albeit with some extra timeline
markers. To make it suitable for uploading to platforms such as TikTok or YouTube Shorts
that primarily support vertical video, you’ll need to adjust the settings of this timeline.
1 From the Timeline Settings menu in the timeline viewer, choose Custom
Timeline Settings.
553Lesson 10 Delivery and Media Management
The Timeline Settings window for this timeline opens.
All the options are currently unavailable because they are set by the Project Settings
you configured in Lesson 7. You’ll need to override these settings so that this timeline
can have a custom setting independent of the project.
TIP If you want all the timelines in your project that are using Project Settings
to change, you can adjust the Timeline Format options in the Project Settings.
2 Uncheck Use Project Settings to activate the settings, allowing you to make changes.
554Lesson 10 Delivery and Media Management
3 In the Timeline Resolution, select the “Use vertical resolution” option.
This single option adjusts the timeline resolution to 1080 x 1920 HD and changes the
Mismatched Resolution option to “Scale full frame with crop.” This is an important
setting, since it means the footage will fill the new aspect ratio rather than being
letterboxed with black lines at the top and bottom of the image, although you will lose
footage off the edges of the timeline viewer.
4 Click OK to apply the changes to the selected timeline.
The edit page interface automatically changes to accommodate the vertical timeline.
555Lesson 10 Delivery and Media Management
NOTE The icon for the newly adjusted timeline indicates that it has its own
settings separate from the current project’s Project Settings. Opening Project
Settings while this timeline is active will result in a warning displayed in the
Master Settings and Color Management sections informing you that any
changes made to the project’s settings will not impact the currently loaded
timeline, since it now has its own timeline settings.
5 Resize the viewers so you can see the content more comfortably.
556Lesson 10 Delivery and Media Management
6 Scrub through the timeline to review the changes.
The timeline viewer will now show the original footage framed in the new aspect ratio of
the timeline.
Reframing Shots
```
Unless the director of photography (DP or DoP) clearly understood that all or part of the
```
final film would need to be displayed in a 9:16 aspect ratio, you will likely need to adjust the
framing of some of these shots. Thankfully, you always have access to the complete picture
information, even though it appears cropped.
You also know which clips will need your attention most, thanks to the markers you added
in earlier steps.
1 Using the buttons in the top left corner of the edit page, close the media pool and
open the Index. Then click the Markers tab to reveal a list of markers for the
current timeline.
557Lesson 10 Delivery and Media Management
2 Click the Color column header to sort the list of markers by their colors.
TIP You can choose to show only specific marker colors in the Index by using
```
the Options (…) menu.
```
3 From the green markers, click the REFRAME 1 marker to jump to that marker and
open the Inspector.
558Lesson 10 Delivery and Media Management
4 Ensure that the Inspector shows the controls for the OMO LOGO.png clip. Open the
Retime and Scaling controls in the Inspector and, in the Scaling menu, select Fit.
The graphic is now correctly scaled to fit the new aspect ratio, while retaining all the
other settings accurately.
559Lesson 10 Delivery and Media Management
5 In the marker index, click the REFRAME 2 marker to place the playhead over the shot
of the guy standing and looking out over the rocks, who you can’t see because he is
currently outside the 9:16 framing of this shot.
```
6 Press Shift-` (accent grave) or choose View > Viewer Overlay > Transform to enable the
```
onscreen Transform controls.
7 Hold Shift and drag the image in the viewer to the right to reposition the guy in the frame.
560Lesson 10 Delivery and Media Management
Reframing Shots Using Keyframes
Sometimes, you’ll need to use keyframes to adjust the framing over time, especially for
shots that will never fit the new aspect ratio properly.
1 In the markers index, click the PAN 1 marker, zoom in on the timeline, and place the
timeline playhead near the start of the WHITE SANDS 11 clip.
2 In the timeline viewer, use the onscreen controls, or the Position X parameter in the
Inspector, to reframe the shot so you can see the girl on the far left of the group.
561Lesson 10 Delivery and Media Management
3 In the Inspector, click the Position keyframe button to add a keyframe to this clip at the
current playhead position.
4 Move the timeline playhead toward the end of the WHITE SANDS 11 clip.
5 With the playhead in the new position, adjust the onscreen controls to frame the
couple on the right side of the group.
562Lesson 10 Delivery and Media Management
This adjustment adds a second keyframe to the clip at the current playhead position
with the adjusted Position parameter.
NOTE The red line that appears in the viewer indicates the motion path that
the clip will travel along between the two keyframes.
6 Play back the clip in the timeline to review the “pan” you have added to the shot using
the Position keyframes.
NOTE You can see that this clip has keyframes applied by the diamond icon to
the right of the clip’s name in the timeline.
You can use the Keyframe Tray to adjust the timing of the two keyframes.
7 In the top left corner of the timeline, click the Show Keyframe Tray button.
The Keyframe Tray opens below the timeline, displaying the keyframe locations relative
to the currently selected clip.
NOTE Although the WHITE SANDS 11 clip is not physically selected, it is still
deemed to be “selected” as it’s the uppermost clip in the timeline.
Using the Keyframe Tray, you can adjust the timing of the keyframes.
563Lesson 10 Delivery and Media Management
8 Select the Position keyframe and drag it to change the timing of the animation by
dragging it closer to the start and end of the WHITE SANDS 11 clip.
TIP You can adjust the height of the Keyframe Tray to better see the
keyframes in relation to the clip.
To adjust the interpolation of the animation, you can use the Keyframes panel.
9 Open the Keyframes panel and close the Index.
564Lesson 10 Delivery and Media Management
The Keyframes panel’s Parameters view shows all the keyframes available for the
selected timeline clip, allowing you to reposition the keyframes relative to that
clip’s duration.
10 Click the Keyframe Curves button in the top left of the Keyframes panel.
The Keyframe Curves display allows you to adjust the acceleration of the clip along the
motion path, similarly to how you adjusted the speed of the animation in the Fusion
page using the Spline window.
```
11 Command-click (macOS) or Ctrl-click (Windows) the two keyframes on the yellow
```
Position X curve.
12 With the two keyframes selected, click the Ease In and Out button at the top of the
Keyframes panel.
565Lesson 10 Delivery and Media Management
Bézier handles are added to the selected keyframes, adjusting the acceleration of
the animation.
13 Adjust the size of the handles to refine the speed of the animation to your liking.
566Lesson 10 Delivery and Media Management
Copying and Pasting Attributes with Keyframes
You can use this animation as the basis for other clips with similar issues.
```
1 In the timeline, select the WHITE SANDS 11 clip and press Command-C (macOS) or
```
```
Ctrl-C (Windows), or choose Edit > Copy, to copy the clip.
```
2 Deselect the clip, and then click the Single Viewer Mode button.
3 Open the Index and click the PAN 2 marker to move to the clip PINA BLANCA 48.
```
4 Select the PINA BLANCA 48 clip and press Option-V (macOS) or Alt-V (Windows), or
```
choose Edit > Paste Attributes.
567Lesson 10 Delivery and Media Management
5 Since you only need to apply the horizontal movement from the WHITE SANDS 11 clip
to this clip, in the Paste Attributes window, deselect the Color Correction option and
choose Stretch to Fit.
Stretch to Fit will ensure that the timing of the keyframes is adjusted relative to the
duration of the new clip.
6 Click Apply.
568Lesson 10 Delivery and Media Management
You will probably find that the pan finishes too far to the right. That’s OK, since you can
simply refine the X Position of the second keyframe.
7 In the timeline, place the timeline playhead between the two keyframes on
PINA BLANCA 48.
569Lesson 10 Delivery and Media Management
8 In the Inspector, click the Next Keyframe arrow to jump to the keyframe to the right of
the playhead.
```
TIP You can also use [ (left square bracket) to jump to a previous keyframe
```
```
and ] (right square bracket) to jump to the next keyframe of the currently
```
selected clip.
9 Using the onscreen Transform controls or the Position X control in the Inspector,
adjust the value of the second keyframe so it ends with the guy in the shot.
570Lesson 10 Delivery and Media Management
10 If necessary, adjust the timing of the keyframes in the Keyframe Tray and the Bézier
handles for the Position X curve in the Keyframes Curves to refine the animation so the
pan follows the guy as he jumps up on the rock.
TIP DaVinci Resolve Studio has a Smart Reframe function that automates this
process of reframing using keyframes. For more information, refer to
The DaVinci Resolve Reference Manual or The Editor’s Guide to DaVinci Resolve 20.
11 Play the newly reformatted timeline, making any further changes you deem necessary.
NOTE If you need to catch up before moving to the next step, open the media
pool, select the TIMELINES bin, choose File > Import > Timeline, navigate to R20
Beginners Guide / Lesson 10 / Timelines / OMO PROMO TIKTOK CATCHUP.drt,
and click Open.
Using the Deliver Page
You now have two timelines in your project ready to export into deliverable files. You could
open the Quick Export window and choose appropriate presets for each timeline. However,
one of the advantages of using the deliver page over the Quick Export function is that you
have access to many more options, and you can also queue export jobs rather than having
to wait for the export to complete before starting the next export job.
In the following steps, you will export each of your timelines to a variety of formats.
1 Choose File > Close the Current Timeline.
2 Choose Workspace > Reset UI Layout.
3 Reopen the original OMO PROMO FINAL timeline.
This is the timeline you will export first.
571Lesson 10 Delivery and Media Management
4 Click the Deliver button at the bottom of the interface, or press Shift-8 to open the
deliver page.
Optimizing Audio Standards
One of the settings available in the deliver page that’s not a part of the Quick Export
process is for optimizing your audio to various standards.
Depending on where you deliver your files, you will likely be given a list of requirements.
These could be as simple as indicating acceptable video resolutions, frame rates, and
codecs. These days, however, they also include loudness levels for your audio.
Loudness is a measurement of your audio across its total duration. The general idea
behind loudness is making sure that levels are consistent across content, so that one
element isn’t perceived as being significantly louder than any other—for example, that
advertisements aren’t noticeably louder compared to the drama you’re watching, or that
the next video you stream doesn’t have you reaching for your volume control to turn it
up or down!
Thankfully, Resolve has a simple way of ensuring that your audio adheres to the various
loudness standards, whether you’re delivering your content to YouTube, Netflix, or
broadcast TV, by optimizing it upon export.
572Lesson 10 Delivery and Media Management
1 From the Render Settings, select the YouTube 1080p preset.
TIP For different delivery resolutions for YouTube up to 2160p, click the
```
dropdown menu (downward arrow) for a list of options.
```
2 In the File Name field, type OMO PROMO YT_FINAL.
3 For the Location, click the Browse button and choose R20 Beginners Guide / OUTPUT /
EXPORTS / YOUTUBE, and click Save to save the location.
573Lesson 10 Delivery and Media Management
Below the Location field, you will see the settings used by this preset to render a file
suitable for uploading to YouTube.
4 Review the settings, ensuring that the Resolution is 1920 x 1080 HD and the Frame
Rate is 23.976.
NOTE Although you can change the resolution of the exported file from the
current timeline’s settings, you’re always advised to choose the same or lower
resolution of the timeline. Choosing a higher resolution may result in reduced
image quality since rendered images are upscaled from the timeline
resolution, which you will be warned about when adding the job to the Render
Queue. Similarly, you should not adjust the frame rate of the exported file
from the timeline frame rate.
5 Enable the Normalize Audio option and select Optimize to Standard.
This will ensure that the exported audio will be at the correct levels for delivering to
```
YouTube: a target level of -1 dBTP and a target loudness of -14 LKFS. The YouTube
```
preset does not allow you to choose an alternative optimization to the standard
setting because it’s assumed you’ll be using this preset to deliver to YouTube, for
obvious reasons.
6 Click the Add to Render Queue button at the bottom of the Render Settings panel.
574Lesson 10 Delivery and Media Management
The job is added to the Render Queue on the right side of the interface in preparation
for exporting.
Customizing Deliver Presets
Now you will choose your own settings for exporting the Organ Mountain Outfitters
promo to a high-quality file.
1 In the Render Settings panel, select Custom Export.
The settings from the last selected preset are retained.
This time, instead of manually typing the whole name for the exported file, you will use
a variable based on the timeline’s name in the project.
2 In the File Name field, type %Time, choose the Timeline Name variable from the list of
options, and then add HQ to the end.
3 In the Location field, click Browse and navigate to R20 Beginners Guide / Lesson 10 /
Output / HQ, and click Save to update the location for the exported file.
575Lesson 10 Delivery and Media Management
4 Ensure that Render is set to Single Clip and select the Video tab if necessary.
5 For the Format, choose QuickTime.
6 For the Codec, ensure that Apple ProRes is selected and, from the Type menu, select
ProRes 422.
Apple ProRes is a high-quality video codec commonly used for creating master files.
These settings will ensure that you are exporting a high-quality file that you can use
as a master file format for the OMO promo in the future and can be used on Mac,
Windows, and Linux versions of DaVinci Resolve 20.
7 Ensure that the resolution is 1920 x 1080 and the frame rate is 23.976. These values
are set based on the current timeline’s settings.
576Lesson 10 Delivery and Media Management
NOTE More advanced settings are available in the Additional
Settings controls.
8 Click the Audio tab.
These settings are already configured to deliver high-quality Linear PCM audio,
commonly referred to as uncompressed audio.
TIP Use the Output Track option to render specific or all timeline tracks from
the timeline.
9 Reveal the Audio Normalization controls and enable Normalize Audio.
10 Choose Optimize to Standard and choose ITU-R BS.1770-4.
The ITU-R BS.1770-4 standard is a general Loudness standard that will allow you to
```
adjust the Target Level (true peak) and overall Target Loudness from their defaults.
```
577Lesson 10 Delivery and Media Management
Alternatively, you can select from the list of presets that adhere to various standards,
```
including ATSC A/85 (for US broadcast), EBU R128 (for European broadcast), OP-59 (for
```
```
New Zealand and Australian broadcast), TR-B32 (for Japanese broadcast), and AGCOM
```
```
219 (for Italian broadcast). Separate presets are also available for delivering audio for
```
Netflix, YouTube, and Disney.
11 Click Add to Render Queue to add this new job to the Render Queue in preparation
for exporting.
Saving a Render Preset
If you use the same custom settings regularly, you might prefer to save a Custom
Render Preset.
```
1 Click the Render Settings’ Options (…) menu and choose Save As New Preset.
```
2 In the Render Preset dialog, type ProRes Loudness to name your new preset.
578Lesson 10 Delivery and Media Management
3 Choose an icon for the preset and click Add to Quick Export to make your preset easily
accessible from the Quick Export window.
4 Click Save.
The new preset is added to the list of presets in the Render Settings.
5 Switch to the edit page and open the Quick Export window to verify that your preset
has also been added.
579Lesson 10 Delivery and Media Management
6 Close the Quick Export window and return to the deliver page.
7 Click the Render Settings’ Options menu again. Here, you can now access options to
```
update (if you’ve made any changes since it was saved), edit the preset’s name and
```
icon, export or delete the preset, or remove it from the Quick Export window.
TIP Rather than using Quick Export, which starts the export process immediately,
timelines can instead be quickly added to the Render Queue using a custom
preset in the edit page by right-clicking the timeline and choosing Timelines > Add
to Render Queue Using > [Your Preset].
Adding the timeline to the Render Queue allows for more careful management of
your exports.
Adding the Vertical Timeline
Currently, you have two jobs you’ve submitted to the render queue, both of which are from
the same timeline. One of the main advantages of using the deliver page is that you can
queue the jobs before rendering them all sequentially—even different jobs from the
same timeline!
Of course, you’ll also want to deliver the TikTok version of the OMO Promo too.
580Lesson 10 Delivery and Media Management
1 From the deliver page’s viewer, choose the OMO PROMO TIKTOK timeline to open it.
2 From the render settings, choose the TikTok 1080p preset.
3 In the File Name field, remove the HQ, leaving just the Timeline Name variable, and
change the Location to R20 Beginners Guide / OUTPUT / WEB.
4 Ensure that the Resolution is set to 1080 x 1920 HD and has the “Use vertical
resolution” option checked. The Frame Rate should be set to 23.976 per the
timeline settings.
All other options for this preset are set to deliver a file appropriate to upload directly
to TikTok.
581Lesson 10 Delivery and Media Management
5 Click Add to Render Queue to add this third job.
With the final job added, you are ready to export all the jobs you have added to the
Render Queue.
Reviewing the Jobs
None of the jobs you have submitted to the Render Queue have been rendered to your
hard drive. To begin the process, you must start the Render Queue manually. However,
before you do that, you have the opportunity to check the render settings of each job and,
if necessary, adjust them before creating the file.
```
1 Click the Render Queue’s Options (…) menu and choose Show Job Details.
```
582Lesson 10 Delivery and Media Management
Each job now shows more information about the settings of each file to be rendered.
For this exercise, you will change the format of Job 1—the version destined for
YouTube—from .mp4 to a QuickTime .mov file.
2 Click the pencil icon for Job 1 to reopen the render settings for that job.
583Lesson 10 Delivery and Media Management
3 Change the Format pop-up menu from MP4 to QuickTime.
4 Click Update Job.
The job updates in the Render Queue, reflected by the change in the file extension
from .mp4 to .mov.
584Lesson 10 Delivery and Media Management
Rendering the Jobs
After reviewing the settings for each job, you are ready to start the actual export process.
This will automatically render each job sequentially as listed in the Render Queue.
TIP You can edit the name of each job to make it easier to identify by clicking the
job name, and you can change the order of the jobs by using the drag handle in
the top left corner of each job.
```
1 In the Render Queue, ensure that none (or all) of the jobs are selected and click
```
Render All.
NOTE You can select specific jobs in the Render Queue to export just
those jobs.
585Lesson 10 Delivery and Media Management
Each job is loaded in turn, and the files are rendered to the destinations. Once the job
has been completed, a green “Completed” label is added to the job.
2 Once all the jobs have been completed, right-click Job 1b and choose Reveal in Finder
```
(macOS) or Open File Location (Windows).
```
The rendered file is revealed in the Output folder on your hard drive, where you can
open it in an appropriate media player and preview the final rendered results.
3 Return to DaVinci Resolve and right-click Job 2 in the Render Queue and choose Show
```
in Finder (macOS) or Open File Location (Windows) to reveal the high-quality .mov file.
```
NOTE On macOS, you can open these files in QuickTime Player to review
them. On Windows, you can reimport them into a new DaVinci Resolve project.
4 Return to DaVinci Resolve and right-click Job 3 in the Render Queue and choose Show
```
in Finder (macOS) or Open File Location (Windows).
```
5 The final rendered file is shown, which you can preview in an appropriate media player.
All these files are now ready to be distributed to their appropriate destinations.
586Lesson 10 Delivery and Media Management
Exporting Timelines
and Project Files
Apart from the exported media itself, there are many other elements of a DaVinci Resolve
project that you can export for a variety of reasons—the obvious being that you may want
to create a backup of your work, or you may want to share a part of the project with others.
To start with, you may want to export a timeline file. This can be useful for sharing edited
versions of different timelines with other people.
```
There are a variety of formats that you can choose to do this, from simple EDL (edit decision
```
```
list) files to more complex XML (Extensible Markup Language) or AAF (Advanced Authoring
```
```
Format) files. These are useful if you want to share timelines with users of other NLE,
```
grading, or audio systems. However, these types of files have the inherent problem of not
translating the timeline information with 100% accuracy between the different systems.
If you wish to manually back up your timelines, or you want to send your timeline to
```
another DaVinci Resolve user, it’s best to use DRT (DaVinci Resolve Timeline) files.
```
NOTE If you have been using the Catchup timeline files throughout this book, you
have already experienced the convenience of using .DRT files.
1 In DaVinci Resolve, click the viewer menu and choose to reopen the OMO PROMO
FINAL timeline.
2 Choose File > Export > Timeline.
3 In the Export Timeline window, navigate to R20 Beginners Guide / Lesson 10 / Output
and create a TIMELINES folder.
```
4 Ensure that the type is set to DaVinci Resolve Timeline Files (*.drt) and click Save.
```
The .DRT file is exported for the current timeline and can be imported into any other
DaVinci Resolve 20 project by choosing File > Import > Timeline.
Rather than exporting an individual timeline, you may choose to export the
entire project.
```
5 Choose File > Export Project or press Command-E (macOS) or Ctrl-E (Windows).
```
6 In the Export Project File window, navigate to R20 Beginners Guide / Lesson 10 /
Output and create a new folder called “Projects.”
587Lesson 10 Delivery and Media Management
```
7 Click Save to export the project as a .DRP (DaVinci Resolve Project) file.
```
The exported .DRP file can be imported into the Project Manager of any other
DaVinci Resolve 20 system.
NOTE You can also export a .drp file of your project directly from the Project
Manager by highlighting the project and clicking the Export button. Projects and
timelines exported from earlier versions of DaVinci Resolve can be imported into
DaVinci Resolve 20. However, projects and timelines created in DaVinci Resolve 20
cannot be opened by earlier versions of DaVinci Resolve.
Media Management
Beyond exporting timelines and project files, another important “housekeeping” task you’ll
need to undertake is managing your source media files. These are all the individual video,
audio, and graphics files that you have imported while you have been working on your
project. Often, by the end of a project, these files are numerous and can be spread across
your system. Exporting a .drt or .drp file will not do anything with these files. They will
need to be managed separately and carefully.
You can take two basic approaches to managing your media files: consolidation and
trimming.
Consolidation is useful when you have many files spread across your system, as it will bring
```
copies of all these files together in a single location for easier archiving (see below).
```
Trimming, on the other hand, copies just the portion of the media files you are using
throughout your project. This can be useful since it does not include media that’s not
being used. As a result, the new media is often much smaller in storage size.
It’s important to note that both of these processes create copies of your media files. At no
point are your original clips affected by either of these operations.
To consolidate or trim the media files used in your project, you’ll need to use the built-in
Media Management panel.
1 Choose File > Media Management to open the Media Management panel.
588Lesson 10 Delivery and Media Management
2 In the Media Management panel, ensure that Entire Project and Copy are selected.
The Media Management panel allows you to manage your media across the whole
project, specific timelines, or clips, and allows you to copy or transcode your media files.
With the current settings, all the media within the project will be copied to your chosen
location. The Copy function will create a duplicate set of media files in the destination
location but leave the original files in place. This allows you to ensure that duplicates are
copied safely and without errors before deleting the originals. Indicators at the bottom
of the Media Management panel indicate the size of the currently used media and the
size of the media that will be copied using the current settings. Currently, the media
management will only affect the files used for your project. Since this project contains
files that are completely unused, the copied media would be slightly smaller in total file
size than the current media, as detailed by the New Size and Current Size values.
NOTE The steps below only address copying the source media files, not
transcoding. Transcoding is a way of converting the source media files into
other formats and is used in workflows beyond the scope of this guide. See
The DaVinci Resolve Reference Manual for more information.
589Lesson 10 Delivery and Media Management
3 In the Destination field, click Browse, navigate to R20 Beginners Guide / OUTPUT /
MEDIA MANAGEMENT, and click Open.
4 Click the Timelines tab.
This part of the Media Management panel allows you to select individual timelines
within your project.
590Lesson 10 Delivery and Media Management
5 Add the OMO PROMO TIKTOK timeline to the currently selected OMO PROMO FINAL
timeline. These are the timelines for which you will manage the media.
6 Choose “Used media and trim keeping 24 frame handles.”
Note that when you make this last selection, the New Size indicator changes.
This reflects that, by choosing just the media you’re using in the selected timelines
```
plus the few frames on either side (the handles), you’re drastically reducing the
```
amount of footage needed to be copied.
NOTE Adding 24 frame handles adds 1 second to the start and end of each
media file being copied. This will allow you “wiggle room” to make minor
changes to the trimmed project in the future.
7 Click Start to begin the media management process.
Once completed, the Media Management panel closes.
591Lesson 10 Delivery and Media Management
```
8 Open a new Finder (macOS) or File Explorer (Windows) window and navigate to R20
```
Beginners Guide / OUTPUT / MEDIA MANAGEMENT / OMO PROMO DELIVER to view
the contents of the folder.
This new folder contains all the trimmed media files that have been copied from the
original media. Of course, this is just the footage that was used in the specific
timelines. The original media hasn’t been touched. However, you will find two .drt files
among these files.
9 Return to DaVinci Resolve and choose File > Project Manager, or press Shift-1, to open
the Project Manager.
10 Click the New Project button, name the new project OMO PROMO MM,
and click Create.
11 In the edit page, choose File > Import > Timeline.
12 Navigate to R20 Beginners Guide / OUTPUT / MEDIA MANAGEMENT / OMO PROMO
DELIVER, select the OMO PROMO FINAL.drt and OMO PROMO TIKTOK.drt files, and
click Import.
13 Click Change if asked to change the project frame rate.
The OMO PROMO FINAL and OMO PROMO TIKTOK timelines are imported into your
new project, including all the appropriate video, audio, and graphics clips, titles,
markers, and other timeline elements.
592Lesson 10 Delivery and Media Management
Creating a Project Archive
In many ways, managing your media files as detailed in the preceding section is useful
```
since you can now copy the folder and its contents (including the .drt files) to another hard
```
drive that you can use for archiving. However, DaVinci Resolve has another feature for easy
```
archiving of both media and projects together as a .DRA (DaVinci Resolve Archive).
```
```
Archiving a project copies all the source files (even if they are on different drives) and
```
places them in the archive folder along with the project file. Because this process does not
create trimmed versions of the files, you are advised to manage your used media files first,
and then create the .DRA.
Either way, you can only create a DaVinci Resolve Archive using the
Project Manager window.
1 Choose File > Project Manager, or press Shift-1, to open the Project Manager.
2 Right-click the OMO Promo MM project and choose Export Project Archive.
3 In the Archive Project dialog, navigate to R20 Beginners Guide / OUTPUT / ARCHIVE
and click Save.
The Archive dialog opens, where you can choose which elements you want to include
with your archive.
4 In the Options, deselect the Render Cache since that is easily re-created and generally
doesn’t need to be archived, and then click OK.
593Lesson 10 Delivery and Media Management
During the Archive process, all the project’s appropriate media files, along with a .drp
file of the project itself, are copied into a folder that’s given the extension .dra. This
folder contains everything you need to open your project on another computer.
NOTE To restore an archived project, follow the steps in Lesson 4.
Creating and Switching
Project Libraries
Unlike other applications you may be familiar with, your individual DaVinci Resolve projects
are not saved to your chosen location. Instead, they are contained within a project library.
When you first open DaVinci Resolve, it automatically creates a project library, so it may not
be immediately obvious that a project library is in use. Nevertheless, at some point, you will
want to create a new project library.
1 In the upper left corner of the Project Manager, click the Projects button to open the
list of available libraries.
594Lesson 10 Delivery and Media Management
The project library sidebar displays a single Local library, called Local Database, by
default. This is the current default project library that DaVinci Resolve created when
you first opened the application.
NOTE The default project library is called “Local Database” because project
libraries in earlier versions of DaVinci Resolve were referred to as “databases.”
However, the method of working with project libraries is exactly the same.
2 In the Project Libraries sidebar, click the Add Project Library button to open the Add
Project Library window.
595Lesson 10 Delivery and Media Management
When choosing to add a project library, you can either “Connect” to an existing project
library or “Create” a brand new, empty project library. Creating a new project library
```
can be useful for an organization; for instance, if you perform several jobs for one
```
client, you might want to assign them their own project library and start a new one for
another client.
3 Ensure that Create is selected in the Add Project Library window and, in the Name
field, enter My Project Library.
```
4 Click the Browse button to open a Finder (macOS) or File Explorer (Windows) window
```
that allows you to choose the location of your new project library.
As a local project library is simply a collection of files and folders, it can reside
anywhere that’s connected to your computer, such as an external hard drive. However,
when you are creating a new project library, the folder it’s created in must be empty.
5 Navigate to R20 Beginners Guide / Lesson 10, create a new folder called My Project
Library, and then click Open.
NOTE The name of the folder containing the project library and the name of
the project library listed in the Project Manager do not have to be the same,
but it’s useful to keep the names consistent so that you know which project
library in the Project Manager is referring to which folder on your system.
6 In the Add Project Library window, click the Create button.
596Lesson 10 Delivery and Media Management
A new project library called “My Project Library” now appears alongside the “Local
Database” project library. The newly added, empty project library is already selected
and ready for your new projects.
TIP Project libraries with fewer and smaller projects will save and operate faster
than project libraries with a greater number of large projects.
Copying Projects Between
Project Libraries
You can easily copy projects from one project library to another.
1 Select the Local Database project library.
```
2 Click OMO PROMO MM, hold Command (macOS) or Ctrl (Windows), and click
```
OMO PROMO DELIVER to select both projects.
597Lesson 10 Delivery and Media Management
3 Click the Copy Project To button.
4 In the dialog that opens, select My Project Library from the list of available project
libraries and click Copy.
The two selected projects are copied to the new project library.
5 Click My Project Library to switch back to your project library to access the
copied projects.
598Lesson 10 Delivery and Media Management
Backing Up Project Libraries
Although it is important to back up a project by exporting it as its own .drp file, you can
create a backup of an entire project library. As with project files themselves, the project
```
library does not include your media; however, creating a backup will save every project in
```
the project library.
1 Click the Details button for the Local Database project library.
Generally, project libraries range in size from a couple of hundred megabytes to a
couple of gigabytes, but unlike media, they can easily be saved to a cloud backup
storage system or a small local hard drive.
2 Click the Back Up button.
599Lesson 10 Delivery and Media Management
3 Navigate to the hard drive or cloud-based storage where you want to back up your
library and click Save.
4 Once the save is completed, click the back arrow next to the Project Library name
```
(which in this case is “Local Database”) to go back to the Project Libraries list.
```
TIP If you are unsure where your database is stored, you can open the
Details and choose the option Reveal in Finder to show you the folder the
database is stored in.
After saving a backup, a Local Database.resolve.diskdb file is created. This file contains
the entire Local Database project library, which you can simply copy to another drive if, for
instance, you purchase a new computer and want to move your existing projects to the
new hard drive. On the new computer, you can click the Restore button in DaVinci Resolve
to open and use the database backup.
Lesson Review
1 True or False? Choosing the Vimeo preset displays the most common options for
creating a movie file for that online sharing site.
2 After adjusting the Render Settings, how do you instruct Resolve to output a
movie file?
3 True or False? The Media Manager manages clips, timelines, and bins.
4 What is the main difference between exporting a project and a project archive?
5 How do you view the project libraries in the Project Manager?
600Lesson 10 Delivery and Media Management
Answers
1 True. Presets provide the most common options. To view all the options available,
click the Custom render setting.
2 To output a movie file, click the Add to Render Queue button and, in the Render Queue
panel, click Start Render.
```
3 False. The Media Manager manages only media for your project or specific timelines;
```
it does not manage bins.
4 A project will simply export a project file that contains no media. A project archive will
export a folder and all media required, which will link to the project when opened.
5 To view the project libraries connected to DaVinci Resolve, in the upper left of the
Project Manager, click the Databases sidebar button.
Congratulations!
You have completed The Beginner’s Guide to DaVinci Resolve 20 and are ready to explore
more editing, visual effects, color grading, and audio mixing functionality using the
additional certified books in this series. Completing all the lessons in this book has
prepared you to become a certified DaVinci Resolve user. You can take the online exam
by following the link below to earn your certificate.
We also invite you to become part of the DaVinci Resolve community by joining the web
forum on the Blackmagic Design website. There, you can ask further questions about
the creative aspects of editing, color correction, motion graphics, visual effects, and
audio mixing.
We hope that you have found DaVinci Resolve 20’s professional nonlinear editing and
world-class color correction tools to be intuitive to learn and a perfect fit to become the
hub of your entire creative workflow.
Test your skills by taking the online assessment located on the Blackmagic Design
DaVinci Resolve Training page—The Beginner’s Guide to DaVinci Resolve 20 Online Exam:
www.blackmagicdesign.com/products/davinciresolve/training
601Index
Index
SYMBOLS
```
/ (forward slash), using to preview
```
timelines, 109, 111, 166–167
```
% (variable), entering, 385–386
```
NUMBERS
3D Qualifier, 284
1080HD 23.976 RCM preset name, 348
A
A-002.WAV audio clip, 356
```
AAF (Advanced Authoring Format)
```
files, 586
accounts, signing into, 177
adjustments
making automatically, 211–217
making with Color Warper, 267–270
AGCOM 219 standard, 577
AI Dialogue Leveler, using in
Fairlight, 442–448
alpha channel, defined, 123
Alt key. See keyboard shortcuts
AMBIENCE track, 474
ambient sound, 421
animals and kids, 495
animation and keyframes in
Fusion, 517–523
Append at End and Insert edits, 42–45
Apple ProRes video codec, 575
Archive Project dialog, 592
areas
masking with windows, 248–252
selecting with qualifiers, 275–279
ATSC A/85 standard, 577
attributes, copying and pasting with
keyframes, 566–570. See also Paste
Attributes window
audio. See also unwanted audio
preventing editing into timeline, 55
synchronizing, 359
syncing to video, 353–364
AUDIO bin, 17
audio clips
adding In and Out points to, 65–66
adding keyframes to, 150–153
adjusting independently, 162
Audio Configuration panel,
354–355, 364, 468
audio editing and quick export, project
```
setup, 142. See also exporting; Quick
```
Export feature
audio fades and transitions,
adding, 159–164
audio keyframes, using, 150–153, 484–490
Audio Mixer, adjusting levels in, 162
audio mixing, 142–146
Audio Only Transition, adding, 160
audio post-production, overview, 418–419
audio scroller, opening in Fairlight, 462
audio scrubbing
disabling, 19, 31
enabling, 24
toggling, 341, 355
audio standards, optimizing, 571–574
audio transitions
applying, 160
types of, 164
audio waveform, showing in source clip,
21–23. See also zoomed waveforms
Auto Balance, 211–217
Auto Black and White icon, 282
Auto Sync Audio command, 414
automatic adjustments, making, 211–217
Automatic Smart Bins category, 404.
See also smart bins
602Index
B
BACKGROUND node, 254
Background node, adding in
Fusion, 503–508
backing up project libraries, 598–599
backtiming edits, 59–64
backups of timelines. See incremental
```
backups; timeline backups
```
balancing clips, 211–217
Beijing International Film Festival, 527
Bézier handles, adding to keyframes, 565
Big Sick, The, 187
```
bins. See also keyword smart bins;
```
```
smart bins; sub bins
```
changing sort order for, 352
creating, 14, 351
organizing inside bins, 11
renaming, 15
and smart bins, 9–13
bins and metadata, exporting, 378
black point, picking, 215
BlackBackground node, adding in
Fusion, 506–507
Blackmagic Cloud and collaboration, 332.
See also Cloud Project libraries
Blackmagic Cloud Store, xxiv
Blackmagic Design Training and
Certification Program, xiv–xv
Boots on Rough Dirt Footsteps.wav clip,
457, 460, 463–464
brightness, increasing, 233
brightness value, checking, 215
B-ROLL bin, 6, 42, 370
B-ROLL folder, 340
B-roll shots, editing, 50
Bypass, choosing, 231
Bypass button, 195, 202, 212
C
cameras, matching, 224–227
Catchup timeline, 586
catchup timelines, importing, 41
certification, getting, xv
Checkerboard background,
adding, 123–124
Chroma Warper, using, 271–274
Cinema Viewer mode, 173
CL INTERVIEW Tk2, 79, 82–84, 157
CL INTERVIEW Tk5, 390
CL INTERVIEW Tk7, 90, 108
CL INTERVIEW Tk8, 392
CL SUBCLIP 1 - Experiences clip,
opening, 31
CL SUBCLIP 2 - Brand clip, opening,
34, 41, 152
CL SUBCLIP 3 - #EXSW clip, opening, 36
CL SUBCLIP 4 - Inspiration, opening, 38, 40
clarity or local contrast, 288
clip attributes, using for advanced audio
configuration, 364
clip handles and transition
alignment, 114–115
clip levels, normalizing, 147–154
clip names
switching between file names, 387
viewing, 192
clip speed, changing, 102–106
clip view, returning to, 29
```
clips. See also sliding clips; subclips;
```
```
thumbnails; timeline clips;
```
ungraded clips
accessing inside bins, 10
adding to smart bins, 374
adding to tracks, 52
copying, 157
editing between In and Out points, 51
making look their best, 185–186
moving forward, 46–47
opening in source timeline, 29
organizing by metadata, 12–13
overwriting, 37
previewing, 10–11
reordering, 367
revealing information about, 341
selecting all, 384
showing file names of, 30
603Index
slipping, 77–80
swapping, 41
transcoding, 224
trimming in Fairlight, 440–442
Clips button, 301–303
Clips filter, 301
clips with metadata, renaming, 384–388.
See also metadata
closing titles, adding, 130–138.
See also TitleText node
Cloud Project libraries, 3. See also
Blackmagic Cloud and collaboration
Cloud workflow, 332
codec, choosing, 575
collaboration and Blackmagic Cloud, 332
color balance, before and after, 240
Color Boost, using with stills, 316
Color button, locating, 191
color channels, adjusting, 228–231, 237
color correction. See also complementary
```
colors; primary color corrections
```
evolving toward high-end work, 184
overview, 181–182
portraying world subjectively, 183
setting tone of visuals, 182–183
using Lift, Gamma, and Gain, 198–204
color grading
goals of, 184–187
using Blackmagic Cloud and
collaboration, 332
Color Management category,
selecting, 220
Color Management setting, 346
color page
applying Resolve FX in, 296–300
identifying ungraded clips on, 300–303
interface, 190–192
undoing steps in, 232
color profiles, displaying for clips, 222
Color Slice tool, using, 289–292
Color Warper, making adjustments
with, 267–270
Command key. See keyboard shortcuts
Comments, filtering by, 369
comparing changes, 262, 292
complementary colors, adding to
images, 194. See also color correction
Conservation Film Company project,
opening, 190
Conservation Primary.drt, 248
contrast
controlling using control points, 234
increasing, 233–235
CONTRAST LIGHT still, 307
Control Panels group, 399
control points
adding, 238, 310
deleting, 282
moving up and down in curves, 265
controlling contrast with, 234
copies, getting details about, 72
“copy,” replacing with numbers, 71
copying
clips, 157
grades, 303–305
and pasting attributes with
keyframes, 566–570
projects between project
libraries, 596–597
cosmetic/performance fixes, 496
creative decisions, making, 329–331
Cross Dissolve, 111
Cross Fade Audio Transitions, 164
Cross Fade Transition Type, 161
.csv files, 376–377
Ctrl key. See keyboard shortcuts
curve points, deleting, 234
Curve tool, selecting, 258
curves
deleting, 320
using for primary color
corrections, 231–235
using in separate nodes, 236–240
604Index
Curves button, 319
curves palette, 263
custom “looks,” adding, 186
custom names, resetting, 388
custom smart bins. See also smart bins
creating, 378–384
organizing, 383–384
Custom Zoom, 33
customized
layouts, saving, 337. See also layouts
CyberBox-0001_BMDUrsa4.6KPro.
mov clip, 525
D
DaVinci Resolve 20 quick setup, xvi–xxii
DaVinci Resolve color management,
using, 218–224
DaVinci Resolve, downloading, xv
DaVinci Resolve Neural Engine, 228
DAY ACTIVITIES smart bin, 380
DAYTIME still, importing, 330
dB levels, adjusting, 151–152, 162
default preset, setting, 348–349
default project settings, changing, 349
deleting
curve points, 234
curves, 320
points, 272, 282
Deliver button, 571
deliver page, using, 570–571
deliver presets, customizing, 574–577
delivery and media management.
```
See also media files; project libraries
```
adding vertical timeline, 579–581
changing timeline settings, 552–556
creating project archives, 592–593
creating vertical timelines, 545–552
customizing deliver presets, 574–577
exporting timelines and project
files, 586–587
media management, 587–591
optimizing audio standards, 571–574
project preparation, 544
reframing shots, 556–570
rendering jobs, 584–585
reviewing jobs, 581–583
saving render presets, 577–579
using deliver page, 570–571
Density slider, 290
Design Training and Certification
Program, xiv–xv
destination control, disabling, 55
destination tracks, specifying, 93–97.
See also tracks
Detail Zoom, 33, 82
dialogue editing, 419–420
DIALOGUE track, 428
diegetic music, 421, 456
dimmed tracks, appearance in edit
page, 192. See also tracks
disabled timelines, re-enabling, 74.
See also timelines
Disk Search button, 8
DJI LUT category, 322
documentary photography, 183
downloading
DaVinci Resolve, xv
and installing lesson files, xxii–xxiii
DR20_Beginners_Lesson 09_
FUSION.drp, 500
Drop Shadow filter, 126
.drp file extension, 4, 587
.DRT files, convenience of using, 586
ducking music in Fairlight, 479–490.
See also music editing
Duplicate Timeline, 71
Dynamic Zoom, 128–129. See also zooming
in and out
Dynamics controls, 422, 448
E
EBU R128 standard, 577
Edit button, locating, 5
edit page, dimmed tracks in, 192
Editing group, 404
605Index
editing overlays, displaying, 35
Editing preferences, 406
editing shortcuts, configuring keyboard
settings for, 37
```
edits. See also Place on Top edit; replace
```
```
edits; rolling edits; slide edit; split edits
```
adjusting visually, 83
backtiming, 59–64
navigating, 173
sliding clips, 87–89
```
EDL (edit decision list) files, 586
```
Effects Library
opening in Fusion, 524
revealing, 111
```
EQ (equalization) controls, 423
```
EQ, applying in Fairlight, 449–454
#experiencethesouthwest, typing, 135
Explorer window, opening, 8
exporting. See also audio editing and quick
```
export; Quick Export feature
```
.drp files, 587
and importing grades, 317–321
jobs, 584
metadata and bins, 378
timelines and project files, 586–587
Eyedropper tool, 213, 273
Eyes node, disabling, 289
F
F002_08151648_C005.mov, 354,
360, 363, 365
fade-in handle, using, 160
Fairlight
adding sound effects, 455–459
AI Dialogue Leveler, 442–448
aligning sound effects in, 467–472
applying EQ, 449–454
audio scroller, 462
creating groups, 476
ducking music, 479–490
Dynamics controls, 448
identifying mono clips, 458
Lock Timeline Track Height, 487
managing groups, 479
mixing soundtracks, 473–479
project setup, 426–427
setting clip channels, 437–440
setting track formats, 437–440
Solo controls, 479
subframe audio adjustments, 442
timeline preparation, 428–432
trimming clips in, 440–442
using dynamics, 448
using scrollers, 459–467
video scroller, 461
Fairlight FX, using for noise
reduction, 154–159
Fairlight interface, exploring, 433–437
Fairlight page
Floating Window button, 461
preparing timeline, 428
project setup, 426–427
Fairlight page mixer, 422
Fairlight page, switching to, 432
Fairlight preview player, using playback
controls in, 467
File Explorer and Finder, 339
file names, switching between clip
names, 387
file system, navigating, 339
files, viewing detail about, 8
Filters group, accessing, 116.
See also studio only filters
Finder and File Explorer, 339
Finder window, opening, 8
flags, clearing, 303
folders
adding for smart bins, 383
adding into media pool, 351
as bins, 9
navigating to, 343
opening, 8
for project libraries, 595
Foley sound, 421, 456
606Index
FOLEY track, 459, 475
footage shot versus used, 28
FOOTSTEPS HERE marker, 431
FOREGROUND node, 249
```
forward slash (/), using to preview
```
timelines, 109, 111, 166–167
frame handles, adding, 590
frame rate, changing, 351
frames per second option, changing, 346
Full Extent Zoom, 33, 138
full-screen review, 173–174, 262.
See also reviewing jobs
Fusion
adding first node, 503–508
animating text, 519–523
arranging nodes, 510
changes in edit page, 523–526
color of connections, 510
connecting nodes in, 512
interface, 502–503
keyframes and animation, 517–523
loading nodes into viewers, 507
Merge node, 509–510
orthogonal pipes, 508
passing through nodes, 513
text creation, 512–515
Time Ruler and transport controls, 516
VFX compositing, 527–541
Fusion composition, creating, 500–501
Fusion page, navigating, 511
G
Gain, 198–204, 212, 216, 225, 227, 230
Gallery
gallery, displaying in color page, 191
opening, 225, 330
Gamma, using in color correction, 198–204,
227, 230, 251, 254, 287, 315–316
gaps in timeline, jumping to start of, 48
General Settings, 406
A Ghost Story, 187
Global temperature slider, 261
Global wheel, 241
Good Take checkbox, 366
Good Takes, 370
GOOD TAKES smart bin, 379
Grab Still option, 225
grades. See also pasting grades
copying, 303–305
importing and exporting, 317–321
seeing before and after, 212, 217
toggling on and off, 227, 231
grading, turning on and off, 195
grain versus noise, 540
graphics, adjusting duration for, 123
Guides button, 138, 552
Guides menu, 546
H
H.264 Master preset, selecting, 177
handles, explained, 114
HANGING SHIRT marker, 432
HDR wheels, using, 240–244, 259–260
hiding
onscreen overlays, 285
and showing columns of
information, 342
high-end work, evolving toward, 184
Highlight button, 254, 281, 284, 292
Highlight icon, locating, 277
highlights, brightening, 201
History Window, opening, 86
Hollywood, use of DaVinci Resolve by, 187
Home key, 173
Horizontal Line Reveal title, 132
HSL curves, making secondary
adjustments with, 262–266
I
images, fitting into windows, 279
Import button, locating, 4
importing
catchup timelines, 41
DAYTIME still, 330
607Index
and exporting grades, 317–321
media, 350–353
metadata, 375–377
projects, 2–6
In and Out points, editing clips
between, 51
In points
adding, 26
adding to audio clips, 65–66
moving, 25
removing, 60
setting for subclips, 391
incremental backups, 403.
See also timeline backups
Index, selecting Tracks tab from, 172
Insert and Append at End edits, 42–45
Insert edit, using, 44–45
inserting at end edits, 42–45
Inspector
adjusting values of fields in, 136
opening, 102, 133
installing lesson files, xxii–xxiii
Internet Accounts, signing into, 177
INTERVIEW ALT ANGLE still, 315
INTERVIEW folder, 343
INTERVIEW GRADE sill, 308–309
interviews, painting, 48–57
```
I/O (Input/Output), 398
```
ITU-R BS.1770-4 standard, 576–577
J
J key, 173
J-cut and L-cut, 84
jobs. See also projects
exporting, 584
rendering, 584–585
reviewing, 581–583
John Wick: Chapter 3—Parabellum, 187
K
Keyboard Customization, 408–409, 413
Keyboard Mapping Preset window, 413
keyboard settings, configuring for editing
shortcuts, 37
keyboard shortcuts
Add Video Only Transition, 108
adding clips to tracks, 52
adding In points, 26
adding nodes, 253, 265, 287
adding Out points, 26
adding serial nodes, 275
before and after of grades, 212
audio scrubbing, 24
Bypass feature, 231
Cinema Viewer, 173
comparing changes, 262
controlling volume overlay, 66
Copy, 303
copying clips, 157
creating bins, 14
creating timelines, 15
disabling audio scrubbing, 19
disabling snapping, 88
displaying all clips in bins, 11
exiting expanded viewer, 317
exploring, 407–411
Fairlight page, 432
Highlight, 277, 284
jumping to keyframes, 569
keyframes, 151–153
Linked Selection, 85, 163
markers, 91
media page, 338
moving clips forward, 46
Out points, 49
Overwrite Clip, 40
overwriting clips, 37
Paste Attributes window, 158
pasting attributes, 566
Place on Top edit, 56–57, 132
In points, 48
previewing transitions, 109–110
Project Settings, 345
608Index
```
keyboard shortcuts (continued)
```
removing In points, 60
removing Out points, 60
replace edits, 93, 97
searching, 411–414
selecting all clips, 384
selecting keyframes, 564
swapping clips, 41
switching between pages, 338
toggling audio scrubbing, 355
toggling grades on and off, 227, 231
transitions, 113
turning nodes on and off, 207, 209
Undo last action, 26, 86
zooming in and out, 100, 281
zooming timelines, 33
keyboard shortcuts, exploring, 407–414
Keyframe Curves button, 564
Keyframe Tray, opening, 562
keyframes
adding, 151–153
adding to audio clips, 151–153
and animation in Fusion, 517–523
copying and pasting attributes
with, 566–570
jumping to, 569
selecting, 564
using to reframe shots, 560–565
using to remove unwanted
audio, 153–154
Keyframes Editor, displaying in
color page, 191
Keyword Manager, 375
keyword shortcuts, 375
```
keyword smart bins. See also bins; smart
```
bins
creating, 370–377
opening list of, 42
revealing, 12
kids and animals, 495
L
L key, 173
layouts, saving, 145.
See also customized layouts
L-cut and J-cut, 84
learning, 498
Lesson 09.1.0 START HERE, 501
Lesson 09.1.2 FINISHED & Variations, 526
lesson files, getting, xxii–xxiii
libraries. See project libraries
Lift, 198–204, 225, 229
Light Rays effect, 297
lighting, adjusting using windows, 255–262
Linked Selection button, 83, 85, 147, 163
linking media files, 6–9
Live Media Preview, disabling/enabling, 11
Live Preview, 19, 341
local contrast or clarity, 288
“Local Database” project library, 594
Local Database.resolve.diskdb file, 599
Local Project libraries, 3
Locate button, accessing, 8
locations, changing, 496
logo, adding, 122–130
“looks,” customizing, 186
Lower Text Spacing, 135
```
LUTs (Lookup tables)
```
applying, 322–325
downloading from third parties, 328
loading, 327–329
overview, 321
saving, 325–326
working with, 321
M
Machine for the Aura, 527
macOS quick setup, xvi–xxii
MaquinaParaVerElAlma-0004_DSLR.mov
clip, 530
Mark In button, locating, 24
Mark Out button, locating, 26
marker colors, displaying in Index, 557
609Index
Marker window, 547
markers
adding to clips in source, 91
listing, 432
Marvelous Mrs. Maisel, The, 187
masking, areas with windows, 248–252
mastering and mixing, 423
matching shots. See also shots
from images, 80
using stills, 314–317
Matte Finesse tools, 278
media, importing, 350–352.
See also delivery and media
```
management; source media
```
media files
importing, 350–353
relinking, 6–9
resyncing, 353
media management, 587–592
media page, switching to, 338
media pool
purpose of, 9
resizing, 10
Media Storage browser, 341
Media Storage preferences, 397
Merge node, using in Fusion, 509–510
```
metadata. See also clips with metadata;
```
subclip metadata
displaying in color page, 191
importing, 375–377
navigating, 379
saving, 373
using for simple searches, 368–370
working with, 365–370
metadata and bins, exporting, 378
Metadata Import dialog, 376
Metadata panel, 371
midtone detail versus sharpening, 288
mixing
audio, 142–146
and mastering, 423
music levels, 165–168
mono audio tracks, adding in Fairlight, 458
mono recording, 170
Monserrat, Ana, 527
MORNING still, 320
motion graphics, 497
MOTION GRAPHICS IN FUSION node,
creating, 515
mouse, requirement of, 217
MP4, changing to QuickTime, 583
music
adding, 64–67
ducking in Fairlight, 479–490
MUSIC bin, selecting, 65
music editing, 421. See also ducking music
in Fairlight
music levels, mixing, 165–168
Mute button, locating, 145
Mute Timeline Audio While Recording, 170
muting tracks, 364
My Blur Dissolve preset, saving, 110
MY OMO PROJECT, 336
MY OMO VO file name, 169
My Project Library folder, 595
My Shortcuts preset, 414
MY SMART BINS folder, 383
N
narrative cinematography, 183
nat sound, 421
Network Project libraries, 3
Neural Engine, 228
```
NLEs (nonlinear editing) systems, 408
```
Node Editor, displaying in color page, 191
nodes. See also outside nodes
adding, 253, 265, 287
adding in Fusion, 503–508
disabling, 289
610Index
```
nodes (continued)
```
labeling, 210
turning on and off, 207, 209
understanding, 204–206
using curves in, 236–240
using to separate corrections, 206–209
noise reduction using Fairlight FX, 154–159
noise versus grain, 540
non-diegetic music, 421
Normalize Audio option, 573
normalizing clip levels, 147–154
O
Offset region in primary corrector,
193–194, 249, 251, 260, 279
OFX Plug-in, removing, 299
OMO LOGO.png clip, 122, 125–126,
128, 558
OMO METADATA.csv, 375
OMO PROMO CATCHUP 01.drt, 41
OMO PROMO CATCHUP 02.drt, 48
OMO PROMO CATCHUP 03.drt, 57
OMO PROMO CATCHUP 04.drt, 64
OMO PROMO CATCHUP 05.drt, 70, 75
OMO PROMO CATCHUP 06.drt, 89
OMO PROMO CATCHUP 07.drt, 97
OMO PROMO CATCHUP 08.drt, 138
OMO PROMO CATCHUP 09.drt, 159
OMO PROMO CATCHUP 10,drt, 164
OMO PROMO CATCHUP 11.drt, 168
OMO PROMO DELIVER, 544, 596
OMO PROMO FAIRLIGHT.drp, 426
OMO PROMO FINAL, 570, 591
OMO PROMO FINISHED timeline, 586
OMO PROMO MIX CATCHUP 01.dr, 442
OMO PROMO MIX CATCHUP 02.drt, 449
OMO PROMO MIX CATCHUP 03.drt, 454
OMO PROMO MIX CATCHUP 04.drt, 472
OMO PROMO MIX COMPLETED
KEYFRAMES.drt, 490
OMO PROMO MIX DUCKER timeline, 485
OMO PROMO MM project, 591, 596
OMO PROMO TIKTOK CATCHUP.drt, 570
OMO PROMO TIKTOK timeline, 545, 580
OMO PROMO TIKTOK.drt, 591
OMO PROMO YT_FINAL file, 572
OMO PROMO.drp file, selecting, 4
ONE MIN SOUNDTRACK.wav clip, 65, 130
onscreen overlays, 285, 287
opening
folders, 8
projects, 5
Option key. See keyboard shortcuts
```
Options menu (.), locating, 11
```
ORANGE SATURATION node, 263
ORGAN MOUNTAIN 1 clip, 43, 82–83, 108,
122, 130, 137
ORGAN MOUNTAIN TIMELAPSE, 84
ORGAN MOUNTAIN TL.mov clip, 137
organizing clips by metadata, 12–13
organmountainoutfitters.com, 133
Out points
adding, 26
adding to audio clips, 65–66
removing, 60
setting for subclips, 391
outside nodes, reversing selections with,
253–254. See also nodes
Overlay button, 261
Overwrite Clip button, locating, 37
Overwrite edit overlay, highlighting, 36
Overwrite edit, using, 45
P
pages, switching between, 338
painting interviews, 48–57
palettes, displaying in color page, 191
PAN 1 marker, 551, 560
PAN 2 marker, 551, 566
pan controls, 423
611Index
Parade scope, 195–197, 199, 202
Paste Attributes window, opening, 158.
See also attributes
pasting grades, default setting for, 303.
See also grades
peak levels, evaluating, 151
Pen Clicks.wav clip, 466
performance/cosmetic fixes, 496
Pick Black Point tool, 215
Picker Subtract icon, 282
Picker Subtract tool, 311
pin point, using, 273
PINA BLANCA 44 clip, 57, 85–86,
96, 106, 548
PINA BLANCA 48 clip, 97, 551, 566, 568
PINA BLANCA 70 clip, 55, 81, 103, 430
PINA BLANCA smart bin, selecting, 55
PINE TRAIL 5 clip, 49, 76, 78–79
PINE TRAIL 12 clip, 51, 76–77, 79–81
PINE TRAIL smart bin, selecting, 49, 51
Place on Top edit, 52, 56–57, 132.
See also edits
Plate, renaming MediaIn1 node to, 529
playback
controlling, 21, 27
resuming, 22
playhead
jogging back 1 frame, 25
moving to start of clip, 20
positioning in source viewer, 24
points
adding, 238, 310
deleting, 282
moving up and down in curves, 265
controlling contrast with, 234
power windows, combining qualifiers with,
280–283. See also windows
Preferences window, opening
Preferences
Automatic smart bins, 405
Control Panels group, 399
Editing preferences, 406
Internet Accounts group, 400
Live Save, 403
Project Save and Load group, 402
resetting and saving, 407
types of, 397
User Preferences, 404–405
User tab, 401
Video and Audio I/O group, 398
presets. See also transition presets
saving, 110
setting, 348–349
preview, turning off, 307
previewing
clips, 10–11
timelines, 166
transitions, 111
primary color corrections. See also color
correction
automatic adjustments, 211–217
color page interface, 190–192
dragging number fields, 208
entering values, 208
labeling nodes, 210
nodes for separating
corrections, 206–209
Radius Blur control, 209
resetting parameters, 207
separate timeline settings, 217–218
using curves for, 231–235
using sharpening, 209
primary corrector, using, 193–195
production dialogue editing, 419–420
production sound, 421
project archives
creating, 592–593
restoring, 190
Project Backups option, 403
project files, exporting, 586–587
project frame rate, changing, 351
612Index
project libraries. See also delivery and
media management
backing up, 598–599
contents of, 3
copying projects between, 596–597
creating and switching, 593–596
Project Manager, opening, 3, 336, 591
project presets
managing, 349
saving, 348–349
Project Save and Load group, 402
project settings, 344–349
projects. See also jobs
coping between project
libraries, 596–597
creating, 336–338
importing, 2–6
opening, 5
selecting, 596
setting up for rough cut, 70
ProRes Loudness preset, 577
pure white, creating, 200
Q
Qualifier tool, 268, 284
Qualifier window, 286
qualifiers
combining with power
windows, 280–283
selecting areas with, 275–279
using with stills, 311–313
quality control, 186
Quick Export feature, 174–178, 578–579.
See also audio editing and quick
```
export; exporting
```
QuickTime format, 583
QuickTime Player, opening files in, 585
R
Radius Blur control, 209
```
RCM (DaVinci Resolve color
```
```
management), 185
```
Record button, using with
voiceovers, 170–171
recording, stopping, 171
rectangle, resizing, 250
REFRAME 1 marker, 557
REFRAME 2 marker, 549, 559
reframing shots. See also shots
implementing, 556–559
using keyframes, 560–565
Relink Media button, locating, 7, 427
Relink Media dialog, 500
relinking media files, 6–9
Remove OFX Plug-in, 299
renaming bins, 15
Render Cache, real-time performance, 98
render presets, saving, 577–579
Render Queue button, 573
Render Settings panel, 573–574
rendering jobs, 584–585
replace edits, 89–97. See also edits
Reset UI Layout, selecting, 6
resizing
media pool, 10
Smart Bins area, 43
thumbnails of clips, 10
resolution
choosing, 575
choosing for exported files, 573
resolution independence, 345
Resolve FX
applying in color page, 296–300
removing from nodes, 299
Restore Project Archive, 190
restoring
archived projects, 593
timeline backups, 72–73
RETAIL smart bin, selecting, 59, 61, 63
reversing selections with outside nodes,
253–254. See also nodes
reviewing jobs, 581–583.
See also full-screen review
613Index
RGB tooltips, 215
RGB values and LUTs, 321, 324
ripple trimming, 84–87. See also trimming
Rocketman, 187
rolling edits, 81–82. See also edits
rough cut, project setup, 70
S
Safe Area Guides menu, 134
Safe Guides, 545
saturation, before and after, 265
Saturation slider, 290
saving
backups of timelines, 72–73
customized layouts, 337
layouts, 145
```
LUTs (Lookup tables), 325–326
```
metadata, 373
presets, 110
project presets, 348–349
render presets, 577–579
and resetting preferences, 407
versions, 71
scale of image, adjusting, 101
scenes, balancing, 186
scopes, displaying in color page, 191.
See also video scopes
ScreenContent, renaming MediaIn
node to, 530
scrollers, using in Fairlight, 459–467
searches using metadata, 368–370
secondary adjustments, making with
HSL curves, 262–266
selecting
all clips, 384
areas with qualifiers, 275–279
projects, 596
Selection mode, choosing for trimming, 75
selections, reversing with outside
nodes, 253–254
serial node, adding, 205, 255, 275
set extensions, 497
Set Level, changing for normalization, 148
settings. See project settings
Shadow color control wheel, 319
shadows, manipulating, 234
sharpening
versus midtone detail, 288
using, 209
Shift key. See keyboard shortcuts
shooting ratio, 28
shot framing, changing, 99–102
shot matching, 317
shots, stabilizing, 106–108. See also
```
matching shots; reframing shots
```
Show File Names, 30
Show Paths icon, 282
Shuffle Insert edits, using, 41
single-viewer mode, 103
skin tone, adjusting, 287, 290, 316
SKY COLOR node, 266
sky replacement, 495–496
SKY SATURATION node, 265
slide edit, 87. See also edits
sliding clips, 87–89. See also clips
slipping clips, 77–80
SLOT CANYON, 373–374
Slow Whoosh.wav clip, 468, 470–471
smart bins. See also Automatic Smart Bins
```
category; bins; custom smart bins;
```
keyword smart bins
and bins, 9–13
Add Filter Criteria button, 381
adding, 378
editing rules for, 380
Smart Bins area, resizing, 43
Smart Reframe function, 570
snapping, disabling, 88, 163.
See also trimming
Solo, enabling and disabling in
Fairlight, 479
Sort menu, 367
sort order, changing for bins, 352
SOT clip, fading in and out, 160
614Index
sound design and sound effects
editing, 420–421
sound effects
adding in Fairlight, 455–459
aligning in Fairlight, 467–472
categories, 421
soundbites
adding, 17–27, 34–40
defined, 21
pacing, 45–48
soundtracks
mixing in Fairlight, 473–479
spotting, 419
source media, exploring, 339–344.
See also media
Source Tape, using, 58
source timeline, switching between editing
timeline, 29. See also timelines
Speed Change controls, locating, 104
split edits, creating, 82–84. See also edits
Split Screen button, 330
spotting soundtracks, 419
Srnec, Nahuel, 527
SROE 34, 89
stabilizing shots, 106–108
Stereo Input option, using with
voiceovers, 170
stills
adjusting duration for, 123
appending, 308–313
applying, 306–308
grabbing, 315
labeling automatically, 320
using to match shots, 314–317
STORE 2 clip, 59, 89
STORE 28 clip, 63, 87, 89, 93
STORE 34 clip, 61, 88
STORE EXTERIOR SIGN clip, 87
studio only filters, 121.
See also Filters group
style, adding, 186
sub bins, revealing, 11. See also bins
subclip limits, adjusting, 395
subclip metadata, modifying, 394–395.
See also metadata
subclips. See also clips
creating, 388–394
duration timecode value, 28
working with, 28–32
SUBCLIPS bin, 17, 30
subfolders, adding into media pool, 351
SubTitle text node, creating in Fusion, 514
sweetening tracks, 422–423
synced audio, verifying, 360
syncing audio to video, 353–363
System preferences, 397
system requirements, xv
T
text
animating in Fusion, 519–523
creating in Fusion, 512–516
three-button mouse, 217
Thumbnail View button, 342
thumbnails. See also clips
displaying, 301
resizing, 10
TikTok, 579–581
timecode values
checking, 216
entering, 47
TIMELAPSE smart bin, selecting, 42
timeline backups, restoring, 72–73.
See also incremental backups
Timeline button, locating, 29
timeline clips. See also clips
reordering, 40–41
trimming, 76–89
Timeline Format options, 553
timeline settings
changing, 552–556
using separately, 217–218
615Index
timeline tracks
rendering, 576
reordering, 172
timeline zoom, controlling, 33
```
timelines. See also disabled timelines;
```
```
source timeline; unused timelines;
```
vertical timelines
adding to Render Queue, 579
creating, 13–16
duplicating and managing, 70–75
exporting, 586–587
getting details about, 72
jumping to starts of gaps in, 48
navigating, 173
preparing for Fairlight, 428–432
preventing from resetting, 143
previewing, 166
two-up display, 83
TitleText node, creating in Fusion, 513.
See also closing titles
track color, choosing, 429
Track Forward button, 286
track levels, resetting, 162
Tracker, using, 284–289, 313
trackpad, using for shot framing, 100
```
tracks. See also destination tracks;
```
dimmed tracks
creating manually, 94
enhancing and sweetening, 422–423
muting, 364
transcoding clips, 224
transform controls, turning on or off, 101
transition alignment and clip
handles, 114–115
Transition Inspector, 164
transition presets, removing, 113.
See also presets
transitions
adding, 108–113
alignment and clip handles, 114–115
and audio fades, 159–163
previewing, 111
TR-B32 standard, 577
Trim Edit mode, 75, 77
```
trimming. See also ripple trimming; snapping
```
clips in Fairlight, 440–442
as editor’s art, 75
timeline clips, 76–89
trimming operations, combining, 80
two-up display, using, 83
U
Undo last action, 26, 86
ungraded clips, identifying, 300–303.
See also clips
unused timelines, disabling, 73–75.
See also timelines
unwanted audio, removing, 152–154.
See also audio
Upper Text Size, 135
User preferences, 397, 405–407
.userprefs extension, 407
V
```
variable (%), entering, 385–386
```
versions, saving, 71
vertical timelines. See also timelines
adding, 579–581
creating, 545–552
VFX compositing in Fusion, 530
adding Blur node, 533–534
adding Ellipse, 534–535
adding Grain, 539–540
adding Merge node, 531
adjusting Gain and Lift, 538
creating Media node, 530
evaluating luminance levels, 536
integrating elements, 533–541
loading timeline, 527–528
modifying Soft Edge value, 541
opening Gain/Gamma controls, 537
plates, 529–530
selecting Corner Positioner, 532
time ruler in Fusion page, 529
616Index
video, syncing audio to, 353–364
VIDEO bin, 17–18
video filters, adding, 116–121
VIDEO folder, opening, 343
video scopes, understanding, 195–197.
See also scopes
video scroller, opening in Fairlight, 461
Video Transitions toolbox, 111
viewers
displaying in color page, 191
exiting, 317
expanding to full screen, 262
as previews, 203
zooming in and out, 250
zooming in and out of, 215
viewing detail about files, 8
Vignette filter, pasting, 120
vignetting, explained, 117
visual effects
adding elements, 494–495
adding transitions, 108–114
animals and kids, 495
changing clip speed, 102–106
changing locations, 496
changing shot framing, 99–102
compositing, 494
learning to see, 498
motion graphics, 497
performance/cosmetic fixes, 496
set extensions, 497
sky replacement, 495–496
stabilizing shots, 106–108
wire removal, 496
visuals, setting tone of, 182–183
voiceovers, recording, 168–171
volume controls, 152, 422
volume overlay, controlling, 66
W
Walking Dead, The, 187
```
Warper. See Chroma Warper; Color Warper
```
waveforms, using for syncing, 359
Westworld, 187
white, creating, 200
White Balance tool, locating, 213
WHITE SANDS 11 clip, 94, 96, 550,
560–563, 566–567
WHITE SANDS 36 clip, 53, 81–82, 94, 96
WHITE SANDS smart bin, selecting, 53
WhiteBackground node, adding in
Fusion, 505
WHOOSHES HERE marker, 431
wind noise, 53
window correction, before and after, 252
windows. See also power windows
fitting images in, 279
masking areas with, 248–252
turning off in viewer, 261
using to adjust lighting, 255–262
Windows quick setup, xvi–xxii
wire removal, 496
world, portraying subjectively, 183
X
```
XML (Extensible Markup Language)
```
files, 586
Y
Y position value, changing, 137
YouTube 1080p preset, 572
YouTube button, selecting, 175
Z
zoomed waveforms, turning off, 39.
See also audio waveform
zooming in and out, 100, 215, 250, 281.
See also Dynamic Zoom
zooming timelines, 33
617This page is intentionally left blank
Legendary Color Correction
Edit and Mix Audio Using Fairlight
Professional Editing Tools
The Beginner’s Guide to
Node-Based VFX with Fusion
The Beginner’s Guide To DaVinci Resolve 20 is a step by step training
guide for both new and existing users. Using a project based
approach, you will discover how to use the editing tools, grade
your film using DaVinci Resolve’s legendary color correction tools,
enhance your soundtracks with the Fairlight page, and build custom
visual effects using the Fusion page. Download the FREE version of
DaVinci Resolve 20 and start creating your own Hollywood caliber
film and video projects today!
What You’ll Learn
• How to edit your own projects using the industry-standard
editing tools in the edit page
• Normalize audio levels, add sound effects and automatically
mix music using the new Ducker track effect
• How to read video scopes to adjust contrast, color balance
and saturation for the perfect grade
• Create secondary corrections using unique intuitive tools
such as the Color Warper and Color Slice
• How to add Power Windows™, track objects and add ResolveFX
• How to set up projects, sync and manage audio files
• Enhance your audio editing and mixing using the Fairlight page
• Build your own titles and visual effects using the Fusion page
• How to deliver projects to a variety of formats including those
for popular social media sites
• Dozens of tips and tricks throughout the book that will transform
how you work!
Who This Book Is For
This book is designed for both beginners and professionals.
Beginners will find clear and concise lessons to get up and
running quickly. If you’re a professional switching from another
system, you’ll find lessons that cover everything from basic
editing and trimming to working with audio, adding text, effects
and more. You’ll also find dozens of pro tips and tricks that will
help you make the switch to DaVinci Resolve!
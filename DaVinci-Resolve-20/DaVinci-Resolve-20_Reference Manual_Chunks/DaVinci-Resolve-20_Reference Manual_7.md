camera # and start timecode, and orders the list by timecode.
400Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
 Date Time: This mode clusters the clips by day, changes the main description field to creation date
and file name, and orders the list by timecode.
 Clip Name: This mode clusters the clips by the first letter of the clip name in alphabetical order,
changes the main description field to clip name, and orders the list by timecode.
 Scene, Shot: This mode clusters the clips by scene, changes the main description field to
scene-shot-take, and orders the list by scene-shot-take.
 Clip Color: This mode clusters the clips by clip color name, changes the main description field to
creation date and start timecode, and orders the list by timecode.
 Date Modified: This mode clusters the clips by day, changes the main description field to creation
date and file name, and orders the list by the last time the clip was modified by the OS filesystem.
 Date Imported: This mode clusters the clips by day, changes the main description field to
creation date and file name, and orders the list by the date the clip was added to the Media Pool.
 Ascending: Orders the Media Pool from lowest numerical value to highest, and
alphabetically from A to Z.
 Descending: Orders the Media Pool from highest numerical value to lowest,
and alphabetically from Z to A.
The Metadata view with clips sorted by Scene-Shot-Take
The Metadata view with the same clips sorted by Camera
401Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Finding Clips, Timelines, and Media
There are several ways to locate different items in the Media Pool and Media Storage, be they clips,
timelines, or media on disk.
Finding Clips and/or Timelines Within the Media Pool
Clicking the magnifying glass button at the upper right-hand corner of the Media Pool exposes the
Search Options, which by default can be used to locate one or more clips in the currently selected bin
or bins, based on the metadata that’s selected in the Filter By drop-down menu to the left of it.
```
The Search Options drop-down menu (as
```
```
seen in the Edit page Media Pool) lets you
```
choose what metadata you’re searching
A drop-down menu right next to the magnifying glass icon lets you choose the scope of your search.
This lets you choose whether a search looks through all bins in the current project for the specified
criteria, or just looks at the currently open bin, or currently selected bins in the Bin list, in cases where
you’re looking for an instance of media in a specific hierarchical location of the Media Pool.
The drop-down menu next to the magnifying glass
icon lets you set the bin search parameters
To find a clip in the Media Pool:
```
1 (Optional) Use the drop-down menu next to the Search button that exposes the Search and Filter
```
by controls in the Media Pool to choose whether you select All Bins or Selected Bins.
```
2 (Optional) If you’re searching Selected Bins, then open the Bin list and select one or more bins in
```
which to search.
402Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
```
3 (Optional) Choose a criteria from the Search Options drop-down menu at the top right of the Media
```
```
Pool; you can choose All Fields to do a simultaneous search of every metadata column in the
```
Media Pool at once, or you can choose a specific criteria to restrict your search.
4 Type a search term in the Search field. As soon as you start typing, all clips that don’t match the
search criteria are temporarily hidden. To show all clips in the Media Pool again, click the cancel
button at the right of the search field.
Finding Synced Audio
If you’ve synced dual-system audio and video clips together in DaVinci Resolve, you can find the audio
clip that a video clip has been synced to using the following procedure.
To find the audio clip that a video clip has been synced to:
• Show the Media Pool in List view, and reference file name in the Synced Audio column.
• Right-click a video clip that’s been synced to audio, and choose “Reveal synced audio in
Media Pool” from the contextual menu. The bin holding the synced audio clip is opened and
that clip is selected.
Finding Timeline Clips in the Media Pool
If you have a clip in a timeline and you want to find the corresponding clip that it’s conformed to in the
Media Pool, you can right-click that clip, and choose Find in Media Pool from the contextual menu.
Finding Timelines in the Media Pool
If you’d like to find the currently open timeline’s location in the Media Pool, you can choose Timeline >
Find Current Timeline in Media Pool.
Finding Media in the Media Storage Panel and Finder
If you find yourself needing to determine the location of a clip’s source media file on disk, you
can right-click an item in the Media Pool and choose Reveal in Media Storage panel. The Library
automatically opens to the folder containing the media file you’ve selected, with that media file
selected in the Library browser to the right.
Another feature that’s only available for macOS systems is the ability to right-click an item in the
Media Pool and choose Reveal In Finder. A file system window opens up, revealing the media file that
clip is linked to.
Reveal Media Pool Bin from
Multi-Bin or Search Displays
If you’ve searched for a clip and have results across multiple bins, you can now reveal where that
clip is in the Media Pool by right-clicking on the clip and selecting Reveal Media Pool Bin from the
contextual menu.
403Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Going Immediately to a File System
Location in the Media Browser
Conversely, if you drag a folder from the macOS Finder into the Media Storage panel, the Media
Storage panel will immediately update to show the location of that folder.
Tracking Media Usage
As clips are added to timelines, two mechanisms come into play for keeping track of which clips are
used in which timelines.
Thumbnail Clip Usage Indicators
Whenever you open a timeline, all thumbnails in the Media Pool automatically update to show
highlighted usage bars to let you know which parts of that clip are used in that timeline.
Two colored highlights at the bottom of the
thumbnail indicate which parts of a clip are
used by the currently open timeline
If you right-click on a thumbnail that shows usage, a Usage submenu shows you a list of each
instance of that clip in the currently open timeline. Choosing an instance from this list jumps
the playhead to that clip in the Timeline.
List View Clip Usage Column
Exposing the Usage column when the Media Pool is in List view lets you see a value for the number of
```
times a clip appears in the current timeline. This usage column is now automatically updated; no user
```
intervention is required.
A Usage column shows how many times a
clip is used in a timeline, after analysis.
404Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Updating Clip Usage for all Timelines
You can also see which clips have been used across all the timelines in your project.
From the Media Pool Options menu, select the “Update Usage for Entire Project” option.
The Update Usage dialog
DaVinci Resolve may prompt the user to load all timelines, if necessary, and update usage counts for
Media Pool clips. This can take some time, depending on the complexity and number of timelines you
have in your project.
Once completed, the usage count across all timelines will appear in the Usage column in the List view
of the Media Pool.
```
NOTE: The Usage column increments for each clip item that appears in the Timeline. This
```
means that if a clip consists of one video item and one video item linked together, the Usage
column will show the number 2.
Relinking Media Simply
DaVinci Resolve keeps track of the relationship between clips in your project and their corresponding
source media on disk. If, for whatever reason, source media that links to clips in your project becomes
unavailable, DaVinci Resolve has several different methods of relinking those clips in the Media Pool.
This section summarizes the methods of relinking. For more comprehensive information on
conforming projects and relinking media, see Chapter 56, “Conforming and Relinking Clips.”
Relink Media
If DaVinci Resolve fails to find your media, a Relink Media icon in the Cut and Edit page’s Media Pool
will highlight orange.
The Relink Media icon that
appears for unlinked media
405Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Clicking this icon opens a dialog box showing the volumes that the missing files initially belonged to.
You can then use this information to track down the media on your file system, find that specific hard
drive, or ask a client if they provided you the media from this volume. Clicking the Locate button lets
you re-connect the missing clips to a new file location of your choosing. If the quick search initiated
by the Locate buttons doesn’t find media that you know is there, you can initialize an exhaustive deep
disk search for the media by clicking on the Disk Search button.
The Relink Media dialog showing the volume
names where the missing clips originated
Relink Selected Clips
The easiest method of relinking clips in your project that have gone offline is to use the appropriately
named “Relink selected clips” command. This is the most flexible method of relinking clips in your
project with clips in a file system directory of your choice, using file name and timecode as the primary
criteria for drawing a correspondence between each clip and the corresponding media file on disk.
When you relink clips this way, the original file path in DaVinci Resolve is ignored, so this is a good
command to use to relink to media that’s been reorganized on disk.
To relink selected clips:
1 Do one of the following:
 Select one or more clips in the Media Pool browser that you want to relink, then right-click
one of the selected clips or the selected bin, and choose “Relink Selected Clips” from
the contextual menu.
 Select a bin in the Media Pool Bin list that contains clips you want to relink, then right-click one
of the selected clips or the selected bin, and choose “Relink Clips for Selected Bin” from the
contextual menu.
2 When the Relink File dialog opens, choose a directory in which to look for the files you want to
relink to, and click OK. DaVinci Resolve attempts to find every clip with a matching file name in the
subdirectories of the directory you chose, using the original file paths of the clips being relinked to
do this as quickly as possible. By first looking for the clips in the directories they were originally in,
relinking can be quite fast.
406Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
3 If there are any clips that couldn’t be found using the method in step 2, you’re prompted with
the option to do a “deep search” by a second dialog. If you click Yes, then DaVinci Resolve will
look for each clip inside every subdirectory of the directory you selected in step 2. This may take
significantly longer, but it should be completely successful so long as the media that’s required is
within the selected directory structure.
4 If there are still other clips that couldn’t be found, you’re prompted to either choose another
directory altogether to continue searching, or quit.
Change Source Folder
If you’ve used your file system to move media that’s associated with a DaVinci Resolve project, but
you haven’t changed the directory structure with which it’s organized, you can use the Change Source
Folder command to quickly relink selected clips in the Media Pool to the new file path of the media
on disk, using the original file paths as a guide. This is a good relinking method to use, if possible, for
projects on a SAN where you don’t want to risk the excessively long search times that could result
from using the Relink command to examine a nested hierarchy of folders in a more flexible way.
To relink your Media Pool clips to a new location:
1 Select one or more clips in the Media Pool, then right-click one of the selected clips, and choose
Change Source Folder from the contextual menu. The Relink Media window appears displaying
the original path for the material, with controls for choosing a new directory.
2 Click the “Browse” button to the right of the Change To field, and then use the file navigation
dialog to find the new location of the media file, select it, and click Open.
3 If you succeeded in finding the appropriate media file, click Change. Otherwise, click Cancel.
407Ingest and Organize Media | Chapter 18 Adding and Organizing Media with the Media Pool
MEDIA
Chapter 19
Using Clip Metadata
DaVinci Resolve has powerful tools for viewing, editing, exporting, and importing
metadata associated with each clip in the Media Pool.
Once your metadata house is in order, you can use this metadata in the Cut, Edit, Color, and Fairlight
pages to find, sort, and organize the clips in your project, so you can work faster.
Contents
Editing Clip Metadata 409
Automatically Imported Metadata  409
Using the Metadata Editor 409
Editing Keywords  411
Editing Metadata Using the File Inspector  412
```
Audio Classification for Clips (Studio Version Only) 413
```
Face Detection to Generate People Keywords  415
Creating Custom Metadata Groups  417
Importing and Exporting Media Pool Metadata  418
Different Ways of Using Clip Metadata  420
Renaming Clips Using Clip Names 420
Switching Between File Names and Clip Names  421
Using Metadata to Define Clip Names  421
408Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
Editing Clip Metadata
Whether you’ve imported media in preparation for editing, or you’ve imported a project for grading
that resulted in media being imported automatically, once you’ve added clips to the Media Pool, it
would behoove you to consider taking the time to review and add metadata to your clips.
At the very least, it would be valuable for you to use the Metadata Editor that’s available in either the
Media page or the Edit page to add information to each clip such as a Description, Shot and Scene
designations, Take information, and possibly some useful keywords such as Character Names, Shot
```
Framing, Interior or Exterior keywords, and so on. If you’re especially ambitious (or you have a very
```
```
responsible assistant), you could go further and add Shoot Day, Camera Type, Audio Notes, and other
```
valuable information. Much of the metadata that is useful in the day to day work of editing and grading
can be found in the Shot & Scene group, but there are many other potentially useful groups as well
that you should explore.
Keep in mind that the more metadata you associate with each clip, the more methods you have at your
```
disposal for creating custom Smart Bins (for editing) and Smart Filters (for grading) with which to zero
```
in on the clips you need for any given situation. This will not only make it easier to find what you need,
but it’ll help you to work faster.
For example, if you’ve entered enough metadata, then you can create multi-criteria Smart Bins or
Smart Filters that let you find the equivalent of “every close-up of Sally inside the diner,” or “every long
shot of Antonio outside in the parking lot.” In a documentary, you could easily isolate “every interview
shot of Louis from camera 1,” or “every B-roll clip with Robyn.” All of this will help you to find media
faster for editing, or to quickly isolate similar clips that you need to match together for grading.
Automatically Imported Metadata
In many instances, metadata is also imported along with the media you’ve added to the Media Pool.
For example, media recorded on BMD cameras may have had a variety of metadata entered into the
camera or automatically generated by the camera, and this metadata is automatically available in
the Metadata Editor. Similarly, Broadcast WAVE files can have quite a bit of metadata entered at the
time of recording, such as scene and take numbers and channel names describing each microphone.
Still images are imported with EXIF metadata. In all cases, available metadata is imported along with
the media and exposed in the Metadata Editor to facilitate workflows where valuable organizational
metadata is being entered on set during the shoot or immediately after ingest.
Using the Metadata Editor
Whenever you select a clip in the Media Pool, its editable metadata appears in the appropriately
```
named Metadata Editor (so long as it’s displayed). You can use this editor to further massage
```
the metadata of the clips in a project, adding information on set that will be of help later during
editing and finishing.
By default, clips initially appear with a set of clip metadata called “Clip Details,” that shows some of the
most fundamental details of the clip such as start and end timecode, duration, bit depth, and so on.
409Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
Because there are so very many metadata fields that are available, two drop-down menus at the top
right of the Metadata Editor let you change which set of metadata is displayed.
```
 Metadata Presets (to the left): If you’ve used the Metadata panel of the User Preferences to
```
create your own custom sets of metadata, you can use this drop-down to choose which one to
expose. Surprisingly enough, this is set to “Default” by default.
```
 Metadata Groups (to the right): This drop-down menu lets you switch among the various groups
```
of metadata that are available, grouped for specific tasks or workflows.
Metadata categories drop-down menu
If you want to see a list of every piece of metadata in a clip, you can choose All Groups. Otherwise,
you can choose any set of metadata to narrow your focus to just those items of information.
To edit metadata for a single clip:
Select any clip in the Media Pool, and edit whatever metadata fields you require. The edited metadata
is immediately saved.
To edit metadata for multiple clips:
1 Choose a metadata set using the drop-down menu in the Metadata Editor.
2 Select multiple clips in the Media Pool by Shift-clicking, Command-clicking, or dragging a
bounding box around them.
3 Edit whichever metadata fields you want to. Checkboxes are automatically turned on for any
metadata fields you edit.
4 When you’re done, click the Save button at the bottom of the Metadata Editor. When you’ve edited
metadata for multiple clips at once, you’ll be prompted to save your changes if you create a new
selection in the Media Pool without clicking the Save button first.
410Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
Editing Keywords
While most metadata in the Metadata Editor is edited via text fields, checkboxes, or multiple button
```
selections (such as Flags and Clip Color), the Keyword field is unique in that it uses a graphical “tag”
```
based method of data entry. The purpose of this is to facilitate consistency with keyword spelling by
making it easy to reference both a built-in list of standardized keywords, as well as other keywords that
you’ve already entered to other clips.
Once added, keywords are incredibly useful for facilitating searching and sorting in the Media Pool,
for creating Smart Bins in the Media and Edit pages, and for use in Smart Filters on the Color page.
Reaping these benefits by adding and editing keywords is simple, and works similarly to the method of
entering metadata variables.
For more information on metadata variables, see Chapter 16, “Using Variables and Keywords.”
To add a keyword:
1 Select the Keyword field of the Metadata Editor, and begin typing the keyword you want to use.
As you begin typing, a scrolling list appears showing all keywords that are available using the
string of characters you’ve just typed.
2 To find a specific keyword in the list, start typing that keyword’s name and this list automatically
filters itself to show only keywords that contain the characters you’ve just typed. Choose which
keyword you want to use in the list using the Up and Down Arrow keys, and press Return to
choose that keyword to add.
The keyword list that appears when
you type within the Keyword field
As soon as you add one or more keywords, they appear as a graphical tag. To re-edit any
keyword, simply click anywhere within the Keyword field to edit it.
To edit a keyword:
 Double-click any keyword to make it editable, then edit it as you would any other piece of text,
and press Return to make it a graphical keyword tag again.
To remove a keyword:
 Click any keyword to select it, and press Delete.
```
TIP: In macOS, any color tags that are set and defined in the Finder can automatically be
```
imported as keywords alongside their media clips. To do so check the “Import Finder tags as
Keywords” box in the General Settings panel of the Editing section in the User Preferences.
411Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
Editing Metadata Using the File Inspector
The File tab of the Inspector provides a consolidated way to view and edit a subsection of a clip’s most
commonly used media file metadata. It’s easily accessible in the Inspector across the Media, Cut, Edit,
and Fairlight pages. The tab is composed of the following parts:
```
Clip Details: Presents data about the clip’s data format (codec, resolution, frame rate, etc.).
```
```
Metadata: Presents a reduced set of common metadata fields for quick user entry.
```
 Timecode: The start timecode of the clip. This field is editable if you want to manually change the
clip’s starting timecode.
 Date Created: The date that the clip was created. This field is editable if you want to manually
change the clip’s creation date.

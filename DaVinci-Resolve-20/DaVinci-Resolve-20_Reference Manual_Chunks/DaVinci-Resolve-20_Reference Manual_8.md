 Camera: Sets the Camera # metadata.
 Reel: Sets the Reel/Card ID.
 Scene: The Scene number of the clip.
 Shot: The Shot letter/number of the clip.
 Take: The Take number of the clip.
 Good Take: This checkbox indicates if the clip is a good or circled take.
 Clip Color: Assign a specific color to a clip that is reflected in the Timeline.
```
 Name: The clip name field; this can be entered manually.
```
 Comments: Add a text description to the clip.
Auto Select Next Unsorted Clip: When this box is checked, the next clip in the Media Pool is selected
when you hit the return button after entering a metadata field, and the cursor is automatically placed
in the same field. This allows rapid sequential metadata entry without having to manually click to load
each individual clip in the Media Pool. The Next Clip button will select the next clip in the Media Pool,
regardless of the checkbox status.
The File Inspector parameters
412Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
Tips for Editing Metadata
Editing metadata is like taking vitamins. Nobody wants to, but you know you probably should.
To encourage you to undertake this task so you can reap the benefits, here are a few pointers.
• Don’t start editing until you review your footage and add metadata. If you get into the habit
of entering your clip metadata before you get preoccupied with your edit, you’ll be in a
much better position to edit faster using organizational tools that leverage the metadata
you’ve entered.
• Enter metadata starting with groups of clips and then moving to individual clips. Since the
Metadata Editor lets you add metadata for multiple selected clips at once, it becomes easy
to select groups of clips based on their thumbnails for entering information such as Scene
designations, Interior or Exterior keywords, Character keywords, and Framing keywords.
You’ll be surprised how fast this goes, and how useful this information is later on, for both
editing and grading.
• After you’ve entered all the metadata you can in groups of clips, then switch to entering
clip-specific metadata such as Shot designations, Take numbers, descriptions of action, and
other clip-specific keywords.
• There’s no right or wrong way to edit or use metadata, but a lack of consistency will make it
less useful. For example, if you’re identifying each clip that takes place at the same diner, try
to use the same keyword or descriptive text. If you call half the shots “diner” and the other
half “restaurant,” your ability to easily search for all the diner shots will be compromised.
Audio Classification for Clips
```
(Studio Version Only)
```
You can have DaVinci Resolve’s Neural Engine analyze the audio for any clip in the Media Pool, and
then automatically assign it a Category and add keywords about its contents in the clip’s Subcategory
audio metadata. This lets you categorize and organize large amounts of audio clips extremely
efficiently by letting the computer do the tedious work of listening to all the media and assigning it
metadata for you. Of course, you can then modify or change any metadata necessary in the Metadata
Editor in case the computer had miscategorized it.
Each clip analyzed gets Audio Category and Subcategory metadata applied to it. Audio Categories
```
are types of audio commonly used in post-production; as of this writing the available choices are:
```
Dialogue, Effect, Music, Silence, and Uncategorized. Subcategories are more detailed keywords
that are assigned based on what sounds the Neural Engine can recognize in the clip. Subcategories
can be anything like sirens, water, dog, etc. Audio Category and Subcategory are available as Smart
Bin filters that let you quickly organize persistent folders for whatever combination of Categories and
Subcategories you desire. For example, you could create a Smart Bin that contains all clips that have
```
both Dialogue (category) and sirens and dogs (subcategories) in them.
```
413Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
Analyzing an audio clip
The results of the analysis in
Category and Subcategory
To Automatically Classify an Audio Clip:
1 Select the clip or clips in the Media Pool you want to
classify the audio for.
2 Right-click on any of the selected clips and select
AI Tools > Audio Classification > Analyze from the
contextual menu. DaVinci Resolve will work its
way through analyzing all the selected clips and
will automatically add the metadata to the Audio
Metadata for each clip.
3 Optionally, you can then review the Audio Metadata
for each clip and correct, delete, or add additional
metadata manually.
414Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
Each Category and Subcategory found by this process
automatically creates Smart Bins in the Collections folder,
based on that metadata. You can also define your own Smart
Bins based on combinations of these keywords.
To Remove Classification
Metadata from an Audio Clip:
1 Select the clip or clips that have Category and
Subcategory metadata that you want to remove.
2 Right-click on any of the selected clips and select Audio
Classification > Clear Classification from the contextual
menu, then click on Remove in the warning dialog box that
appears. There is no undo for this feature.
Subcategories folder list showing
folders created from analysis
Face Detection to
Generate People Keywords
You can select multiple clips in the Media Pool, then right-click the selection and choose AI Tools >
Analyze clips for people from the context menu to automatically analyze all selected clips using the
DaVinci Neural Engine, identifying faces that can be used to help organize the media. A progress
```
dialog shows you how long until the analysis is finished (you can cancel the operation if necessary).
```
Afterwards, the People Management window appears that shows you the results, automatically
organized into a number of bins in a sidebar.
 A “People” bin shows each face that has been recognized as an individual person. Click, pause,
then click again underneath any thumbnail to edit the name or role of that person. You must assign
a name if you want a keyword to appear for that individual in the People field of the Metadata
Editor. Assigning names renames the bins corresponding to each found person and enables
retagging to fix mistaken identification.
The Face Recognition window seen immediately after a Face Recognition operation
415Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
 Individual bins collect all clips with a particular person, allowing you to evaluate whether or not the
contents have been identified correctly. If you see an incorrectly identified clip, you can right-click
it and re-tag it from the contextual menu, or choose “Untag” if it’s a new person that has not been
identified at all.
A bin for a particular person lets you evaluate the contents
 An “Other People” bin shows all faces that could not be identified. You can right-click any of these
to re-tag it as one of the people that have been already identified, or you can choose New Person
```
if it’s someone who wasn’t initially identified (this sometimes happens when multiple people have
```
```
very similar features).
```
The Face Recognition window seen immediately after a Face Recognition operation
416Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
Clicking the Close button closes this window and assigns the names you edited as keywords to
the People field of the “Shot & Scene” group in the Metadata Editor. Clips with multiple people
who have been identified have multiple keywords assigned.
The People keywords field of the Shot & Scene group in the
Metadata Editor, populated with who is in that shot
Once People keywords are assigned to one or more clips, a People smart category of smart
bins can automatically be created in the Smart Bins sidebar of the Media Pool, making it easy to
immediately begin finding clips that have specific people in them. To create this People Smart Bin,
select “Automatic Smart Bins for People Metadata” box in the Preferences > User > Editing window.
You can reopen the Face Recognition window at any time to make modifications by choosing
Workspace > People. You can reset all faces by clicking the People Management Option menu
and choosing “Reset Face Database.”
```
NOTE: A command in the Option menu of the Face Recognition window, Reset Face
```
Database, lets you reset all analyzed results if the results are not acceptable and you don’t
want to save the resulting metadata.
Creating Custom Metadata Groups
The Metadata panel in the User Preferences lets you create custom sets of metadata parameters
that will be exposed in the Metadata Editor. Using this panel, you can create customized subsets of
metadata that are focused on your particular needs.
Presets that you create are available from the Option menu that’s just to the left of the Metadata
categories drop-down menu.
Choose any custom preset to restrict the Metadata Editor to only showing the metadata fields in that
preset. To see the full set of custom metadata fields you’ve saved to a particular preset, you should
set the Metadata Categories drop-down menu to All Groups. To make the full set of metadata fields
reappear, just choose default presets in the same drop-down.
417Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
Custom Metadata Categories drop-down menu
Making and managing metadata presets is simple.
To create a new metadata preset:
1 Open the Metadata panel of the User pane of the Preferences window, and click New.
2 Click the checkboxes of every metadata tag you want to include in this preset, or click the
checkbox of a group name on the list to include all metadata tags within it.
Every single metadata tag available in DaVinci Resolve appears within one of several groups that
appear as a list. To open any group to see its contents, move the pointer over that group’s entry
on the list, and click the Open button when it appears.
3 When you’re finished, click the Save button under Metadata Options.
4 Click the Save Button for the User Preferences.
To edit an existing metadata preset:
1 Select a preset from the list, and click Edit.
2 Turn checkboxes on and off to include or exclude whatever tags you need.
3 Click the Save button under Metadata Options.
4 Click the Save Button for the User Preferences.
To delete a metadata preset:
 Select a preset from the list and click Delete.
Importing and Exporting
Media Pool Metadata
Once you’ve taken the trouble to add metadata to the clips in your project, DaVinci Resolve makes
it possible to export metadata from the Media Pool of one project for import into the clips of another
project, for instances where you need to move metadata around.
For example, a DIT might have entered a lot of metadata to the DaVinci Resolve project used for
generating dailies, but then an impatient editor might have created a separate project to begin editing
those dailies. Instead of requiring the editor to enter each clip’s metadata all over again, you can
export the metadata from the DIT’s project and import it into the editor’s new project, automatically
matching the relevant metadata to each corresponding clip.
418Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
To export Media Pool metadata:
1 Open a project containing Media Pool metadata you want to export.
2 Optionally, select which clips in the Media Pool you want to export metadata for.
3 Choose File > Export Metadata From > Media Pool to export metadata from every clip in the Media
Pool, or choose File > Export Metadata From > Selected Clips to only export metadata from clips
you selected in step 2.
4 When the Export Metadata dialog appears, enter a name and choose a location for the file to be
written, then click Save. All metadata is exported into a .csv file that can be viewed and/or edited
in any spreadsheet application.
If you open the resulting metadata .csv file, the first line is a header that lists what metadata is to be
found for each item listed in this document, and in what order. Only metadata fields that have been
```
populated for at least one clip are exported and listed in this header; unused metadata fields in the
```
Metadata Editor or Media Pool are ignored.
This file can now be imported into another project file to reattach the metadata to the same clips.
To import Media Pool metadata:
1 Open a project containing clips you want to populate with imported metadata.
2 Optionally, select which clips in the Media Pool you want to import metadata to.
3 Choose File > Import Metadata To > Media Pool to import metadata to potentially every clip in the
Media Pool, or choose File > Import Metadata To > Selected Clips to only import metadata to clips
you selected in step 2.
4 When the Import Metadata dialog appears, choose a metadata .csv file to import, and click Open.
5 When the Metadata Import dialog appears, choose the Import Options you want to use to
match the .csv file’s metadata to the correct clips in the currently open project. By default,
DaVinci Resolve tries to use “Match using filename” and “Match using clip start and end
Timecode” to match each line of metadata in the .csv file with a clip in the Media Pool, but there
are other options you can use such as ignoring file extensions, using Reel Name, and using source
file paths.
6 Next, choose which Merge Option you want to use in the Metadata Import dialog.
There are three options:
Only update metadata items with entries in the source file: The default setting. Only updates a
clip’s metadata if there’s a valid entry in the imported .csv file. Other clip metadata fields are left as
they were before the import.
Update all metadata fields available in the source file: For each clip that corresponds to a line
of metadata in the imported .csv file, every single metadata field referenced by the .csv file is
overwritten, regardless of whether or not there’s a valid entry for that field.
Update all metadata fields available in the source file and clear others: For each clip that
corresponds to a line of metadata in the imported .csv file, every single metadata field referenced
by the .csv file is overwritten, regardless of whether or not there’s a valid entry for that field.
Furthermore, metadata fields that aren’t referenced by the imported .csv file are cleared of
whatever metadata was there before.
7 When you’re finished choosing options, click Ok and all available metadata from the source .csv
file will be imported.
419Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
The Metadata Import dialog that lets you choose
options for how to match and merge imported metadata
Different Ways of Using Clip Metadata
To encourage you to take advantage of the clip metadata tools that exist in DaVinci Resolve, here’s a
short list of the many different ways you can use clip metadata to help you work faster.
 Searching for clips in the Media Pool
 Searching for clips in the Timeline
 Sorting the Media Pool by metadata columns in list view
 Creating Smart Bins in the Edit page
 Creating Timeline Filters in the Color page
 Using Metadata to create clip Clip Names
 Displaying Metadata in frame using the Color page Burn In palette
Renaming Clips Using Clip Names
The most fundamental piece of clip metadata is each clip’s name, which is used to identify clips
nearly everywhere they appear inside DaVinci Resolve. By default, clips show the file name of the
corresponding media file on disk. Since the dawn of tapeless recording, however, editors have been
stuck with camera original media having names that are not exactly “human readable.”
Fortunately, you have the option of entering a more user-friendly clip name to use instead, while
preserving the original file name that’s critical for maintaining the link between a clip and its media,
as well as for tracking an offline clip’s corresponding link to the online media from which it originated.
There are a few ways you can edit the clip name of a clip.
```
NOTE: You can also edit the clip names of timelines, compound clips, and multicam clips, so
```
that you can have two sets of naming conventions for these items, one for when you’re doing
creative editing, and one for when you’re doing finishing tasks.
420Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
To edit a clip’s clip name, do one of the following:
 In the Media Pool’s Icon view, click a clip’s name once, pause a moment, then click a second time
to select the name, type a new name, then press return to accept the name.
```
 In the Media Pool’s List view, the Clip Name mirrors the source clip’s file name (hidden by default),
```
but you can click the Clip Name column for any clip to add a new name from scratch.
 With the Clip Name column exposed in the Media Pool’s List view, Option-click the Clip Name
column for any clip to edit the file name, rather than entering a brand new name.
 To edit the clip name of multiple clips, select all of the clips for which you want to change the clip
name, then right-click one of the selected clips and choose Clip Attributes. Open the Name panel
of the Clip Attributes window, edit the Clip Name field, and click OK.
After you’ve changed a clip’s clip name, that clip appears in the following places using the clip name
instead of the original file name:
 The Media Pool’s Thumbnail view
 The name bar of each clip in the Timeline
 The Source Viewer title bar
 The Clip Name field of the Clip Attributes dialog’s Name panel
Switching Between File Names and Clip Names
Since different tasks require different information, you have the ability to switch between using clip file
names and clip names. For example, finishing editors will probably have more reason to refer to the file
name of each clip, making it easier to troubleshoot problems with reconforming and relinking. Creative
editors, on the other hand, will want to use easier-to-read clip names to make it easier to find what
they need.
To switch between file names and clip names:
Choose View > Show File Names to toggle between both naming conventions.
Using Metadata to Define Clip Names
```
If you’re an enthusiastic user of clip metadata (and you should be), you can use “metadata variables”
```
that you can add into a field that let you reference other metadata for that clip. For example, you could
add the combination of variables and text seen in the following screenshot to define a clip name
automatically. Variables, once they’ve been entered, are represented as graphical tags shown with a
background, while regular text characters that you enter appear before and after these tags.
Variables and text characters entered to create a clip name based on a clip’s metadata
As a result, that clip would display “12_A_3” as its name if scene “12,” shot “A,” and take “3” were
```
its metadata. When you do this, you can freely mix metadata variables with other characters (the
```
```
underscore, as in the example above) to help format the metadata to make it even more readable.
```
Every single item of metadata that’s available in the Metadata Editor can be used as a variable, and
several other clip and timeline properties such as the version name of a clip’s grade, a clip’s EDL event
number, and that clip’s timeline index number can be also referenced via variables.
421Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
Since the use of metadata variables is a great way to automatically generate names for multiple clips,
you may find it more useful to add metadata variable-driven clip names by selecting all of the clips you
want to edit, and opening the Clip Attributes window. By editing the Clip Name field found in the Name
panel, you can add a single clip name to all selected clips at once.
To add a variable to a text field that supports the use of variables:
```
1 Type the percentage sign (%) and a scrolling list appears showing all variables that are available.
```
2 To find a specific variable quickly, start typing the characters of that variable’s name and this list
automatically filters itself to show only variables that contain the characters you’ve just typed.
3 Choose which variable you want to use using the Up and Down Arrow keys, and press Return to
choose that variable to add.
The variable list that appears when you type the % character
As soon as you add one or more metadata variables to a clip’s Clip Name column and press
Return, the string is replaced by its corresponding text. To re-edit the metadata string, simply
click within that column, and the metadata variables will reappear. Be aware that, for clips where a
referenced metadata field is blank, no characters appear for that corresponding metadata variable
in the Clip Name column.
To remove a metadata variable:
Click within a field using variables to begin editing it, click a variable to select it, and
press Delete.
For more information on the use of variables, as well as a list of all variables that are available
in DaVinci Resolve, see Chapter 16, “Using Variables and Keywords.”
422Ingest and Organize Media | Chapter 19 Using Clip Metadata
MEDIA
Chapter 20
Using the Inspector
in the Media Page
The Inspector holds all the controls to modify, resize, retime, and generally adjust
anything related to a clip, transition, or effect on the Media page Timeline.
Contents
Using the Inspector  424
Adjusting Media Pool Clips in the Inspector  424
Video  425
Audio  429
Image  432
File  432
423Ingest and Organize Media | Chapter 20 Using the Inspector in the Media Page
MEDIA
Using the Inspector
The Inspector has been redesigned to make it easier to find specific controls and to adjust common
settings for your clips. Instead of a long vertical list, different aspects of the Inspector have now been
organized into panels, with each controlling specific grouped sets of parameters for your clip.
The Inspector is activated by clicking on the Inspector Panel in the upper-right section of
the User Interface toolbar. The Inspector is broken up into individual Video, Audio, Effects,
Transition, Image, and File panels. Inspector panels that are not applicable to your clip or
selection are grayed out.
The Inspector Panel icon in
the upper right of the UI toolbar
The Inspector panels showing Video, Audio, and
```
File parameters available for adjustment; others are grayed out.
```
Methods of using controls in the Inspector:
• To activate or deactivate a control: Click the toggle to the left of the control’s name.
The orange dot on the right means the control is activated. A gray dot on the left means the
control is deactivated.
• To reveal a control’s parameters: Double-click the control’s name.
• To reset controls to their defaults: Click the reset button to the right of the control’s name.
Adjusting Media Pool Clips in the Inspector
You can directly modify Media Pool clips in the Inspector, before you edit those clips into a timeline.
This allows you to change the parameters of source media so that clips that are subsequently edited
into a timeline carry those new settings with it. For example, you can prepare your material prior to
editing by changing the clip’s file and RAW settings, adjusting the audio levels and EQ, or assigning
it a specific lens correction, etc. Once modified, any part of that clip would have the correct Inspector
parameters already in place when you edited them into your timeline.
To adjust Media Pool clips in the Inspector:
1 Select one or more clips in the Media Pool Panel of either the Media, Cut, Edit, or Fairlight pages.
2 Open the Inspector panel, and adjust any parameters in the Video, Audio, Image and File tabs.
These parameter changes are stored with the Media Pool clip, and will be carried over when any
part of that clip is edited into the Timeline. Of course, each clip’s Inspector parameters can be further
modified once it’s in the Timeline, and those Timeline parameters are independent from the Media
Pool Inspector settings. This means that any further adjustments you make to the clip in the Timeline
do not affect that same clip’s adjustments already in the Media Pool.
424Ingest and Organize Media | Chapter 20 Using the Inspector in the Media Page
MEDIA
Video
The Video Panel of the Inspector exposes a vast array of controls designed to manipulate the size,
speed, and opacity of your clips.
Transform
The Transform section of the Video Inspector panel
The Transform group includes the following parameters for resizing and repositioning your clips:
 Zoom X and Y: Allows you to blow the image up or shrink it down. The X and Y parameters can
be linked to lock the aspect ratio of the image, or released to stretch or squeeze the image in one
direction only.
 Position X and Y: Moves the image within the frame, allowing pan and scan adjustments to be
made. X moves the image left or right, and Y moves the image up or down.
 Rotation Angle: Rotates the image around the anchor point.
 Anchor Point X and Y: Defines the coordinate on that clip about which all transforms are centered.
 Pitch: Rotates the image toward or away from the camera along an axis running through the
center of the image, from left to right. Positive values push the top of the image away and bring
the bottom of the image forward. Negative values bring the top of the image forward and push the
bottom of the image away. Higher values stretch the image more extremely.
 Yaw: Rotates the image toward or away from the camera along an axis running through the center
of the image from top to bottom. Positive values bring the left of the image forward and push the
right of the image away. Negative values push the left of the image away and push the right of the
image forward. Higher values stretch the image more extremely.
 Flip Image: Two buttons let you flip the image in different dimensions.
Flip Horizontal control: Reverses the image along the X-axis, left to right.
Flip Vertical control: Reverses the clip along the Y-axis, turning it upside down.
Cropping
The Cropping section of the Video Inspector panel
425Ingest and Organize Media | Chapter 20 Using the Inspector in the Media Page
MEDIA
The Video Inspector controls the image’s cropping parameters:
 Crop Left, Right, Top, and Bottom: Lets you cut off, in pixels, the four sides of the image. Cropping
a clip creates transparency so that whatever is underneath shows through.
 Softness: Lets you blur the edges of a crop. Setting this to a negative value softens the edges
inside of the crop box, while setting this to a positive value softens the edges outside of
the crop box.
 Retain Image Position: Clicking this checkbox will lock the crop parameters in place when you
resize the image using the Transform tool above. Unchecking this box will scale and position the
crop as well as the image.
Dynamic Zoom
The Dynamic Zoom section of the Video Inspector panel
The Dynamic Zoom controls, which are off by default, make it fast and easy to do pan and scan
effects to zoom into or out of a clip. Turning the Dynamic Zoom group on activates two controls in
the Inspector that work hand-in-hand with the Dynamic Zoom onscreen adjustment controls.
For more information on using the Dynamic Zoom controls, see Chapter 50, “Compositing
and Transforms in the Timeline.”
 Dynamic Zoom Ease: Lets you choose how the motion created by these controls accelerates.
You can choose from Linear, Ease In, Ease Out, and Ease In and Out.
 Swap: This button reverses the start and end transforms that create the dynamic zoom effect.
Composite
The Composite section of the Video Inspector panel
Composite modes can be used to combine clips that are superimposed over other clips in
the Timeline.
 Composite Mode: This selects the type of composite mode to combine the superimposed clips.
The default “Normal” means no compositing mode is applied.
For more information on Composite Modes, see Chapter 50, “Compositing and
Transforms in the Timeline.”
 Opacity: This slider makes a clip more or less transparent in addition to compositing
already being done.
426Ingest and Organize Media | Chapter 20 Using the Inspector in the Media Page
MEDIA
Lens Correction
The Lens Correction section of the Video Inspector panel
```
The Lens Correction group (only available in Resolve Studio) has two controls that let you correct
```
for lens distortion in the image, or add lens distortion of your own.
 Analyze: Automatically analyzes the frame in the Timeline at the position of the playhead for
edges that are being distorted by wide angle lens. Clicking the Analyze button moves the
Distortion slider to provide an automatic correction. If you’re analyzing a particularly challenging
clip, a progress bar will appear to let you know how long this will take.
 Distortion: Dragging this slider to the right lets you manually apply a warp to the image that lets
you straighten the bent areas of the picture that can be caused by wide angle lenses.
If you clicked the Analyze button and the result was an overcorrection, then dragging this slider to
the left lets you back off of the automatic adjustment until the image looks correct.
Retime and Scaling
The Retime and Scaling section of the Video Inspector panel
The Retime and Scaling group has four parameters that affect retiming quality and clip scale:
 Retime Process: Lets you choose a default method of processing clips in mixed frame rate timelines
```
and those with speed effects (fast forward or slow motion) applied to them, on a clip-by-clip basis.
```
The default setting is “Project Settings,” so all speed-effected clips are treated the same way.
There are three options: Nearest, Frame Blend, and Optical Flow, which are explained in
more detail in the Speed Effect Processing section of Chapter 51, “Speed Effects.”
 Motion estimation mode: When using Optical Flow to process speed change effects or clips with
a different frame rate than that of the Timeline, the Motion Estimation pop-up lets you choose
the best-looking rendering option for a particular clip. Each method has different artifacts, and
the highest quality option isn’t always the best choice for a particular clip. The default setting is
“Project Settings,” so all speed-effected clips are treated the same way. There are several options.
The “Standard Faster” and “Standard Better” settings are the same options that have been
available in previous versions of DaVinci Resolve. They’re more processor efficient and yield good
quality that are suitable for most situations. However, “Enhanced Faster” and “Enhanced Better”
should yield superior results in nearly every case where the standard options exhibit artifacts, at
the expense of being more computationally intensive, and thus slower on most systems.
 The “Standard Faster” and “Standard Better” settings are the same options that have been
available in previous versions of DaVinci Resolve. They’re more processor efficient and yield
good quality that are suitable for most situations. However, “Enhanced Faster” and “Enhanced
427Ingest and Organize Media | Chapter 20 Using the Inspector in the Media Page
MEDIA
Better” should yield superior results in nearly every case where the standard options exhibit
artifacts, at the expense of being more computationally intensive, and thus slower on
most systems.
 “Speed Warp Faster and “Speed Warp Better” are available for even higher-quality slow motion
effects using the DaVinci Neural Engine. Your results with this setting will vary according to
the content of the clip, but in ideal circumstances this will yield higher visual quality with fewer
artifacts than even the Enhanced Better setting.
 Scaling: Lets you choose how clips that don’t match the current project resolution are handled on
a clip-by-clip basis. The default setting is “Project Settings,” so that all mismatched clips use the
same method of being automatically resized.
However, you can also choose an individual method of automatic scaling for any clip.
```
The options are Crop, Fit, Fill, and Stretch; for more information see the 2D Transforms
```
section see Chapter 152, “Sizing and Image Stabilization.”
 Resize Filter: For clips that are being resized in any way, this setting lets you choose the filter
method used to interpolate image pixels when resizing clips. Different settings work better for
different kinds of resizing. There are four options:
```
Sharper: Usually provides the best quality in projects using clips that must be scaled up to fill a
```
larger frame size, or scaled down to HD resolutions.
```
Smoother: May provide higher quality for projects using clips that must be scaled down to fit an
```
SD resolution frame size.
```
Bicubic: While the Sharper and Smoother options are slightly higher quality, Bicubic is still an
```
exceptionally good resizing filter and is less processor intensive than either of those options.
```
Bilinear: A lower quality setting that is less processor intensive. Useful for previewing your work on a
```
low-performance computer before rendering, when you can switch to one of the higher quality options.
Other Resize Methods: A selection of specific resize algorithms is available if you need to match
them to other VFX workflows.
Super Scale
The Super Scale parameters
For instances when you need higher-quality upscaling than the standard Resize Filters allow, you
can now enable one of the “Super Scale” options in the Inspector. Unlike using one of the numerous
scaling options in the Edit, Fusion, or Color pages, Super Scale actually increases the source
resolution of the clip being processed, which means that clip will have more pixels than it did before
```
and will be more processor-intensive to work with than before, unless you optimize the clip (which
```
```
bakes in the Super Scale effect into the optimized media) or cache the clip in some way.
```
For more detailed information on Super Scale, see Chapter 11, “Image Sizing and Resolution
Independence.”
428Ingest and Organize Media | Chapter 20 Using the Inspector in the Media Page
MEDIA
Using Super Scale in the Inspector is functionally equivalent to setting the same controls for the
media clip in the Clip Attributes. This means that changing this setting affects all of the additional edits
referencing the selected media as well.
The Super Scale group has the following parameters that affect the quality and clip scale:
 Super Scale: Lets you choose the amount of scaling required. The options are 2-3-4x
and 2-3-4x Enhanced.
 Sharpness: Lets you choose the amount of detail in the scaling. This is limited to Low, Medium, or
High, unless the Super Scale mode is set to Enhanced, which allows you to apply variable
sharpness. You will want to balance this setting against Noise Reduction.
 Noise Reduction: Lets you choose the amount of noise reduction in the scaling. This is limited to
Low, Medium, or High, unless the Super Scale mode is set to Enhanced, which allows you to apply
variable noise reduction. You will want to balance this setting against Sharpness.
Audio
The Audio Inspector parameters
The Audio tab contains four commonly used audio
controls for video editing purposes, including
Clip Volume, Clip Pan, Clip Pitch, and Clip Equalizer.
Clip Volume: Each clip has a single volume control
that corresponds to the volume overlay over each
audio clip.
```
Clip Pan: (Only exposed for clips) A simple Pan
```
slider that controls stereo panning.
Clip Pitch: Lets you alter the pitch of a clip without
changing the speed. Two sliders let you adjust clip
```
pitch in semi tones (large adjustments, a twelfth of
```
```
an octave) and cents (fine adjustments, 100th of a
```
```
semi tone).
```
Equalizer
This six-band parametric equalizer has both
graphical and numeric controls for boosting or
attenuating different ranges of frequencies within
that clip, before it even gets to the EQ built into the
Mixer. Each band has controls for the filter type
```
(Bell, Lo-Shelf, Hi-Shelf, Notch), Frequency, Gain,
```
```
and Q-factor (sharpness of the band), with the
```
available controls for each band of EQ changing
depending on the filter type.
```
TIP: Clip EQ settings can be copied and pasted from one Clip EQ to another, and between
```
Clip EQ and Track EQ instances.
429Ingest and Organize Media | Chapter 20 Using the Inspector in the Media Page
MEDIA
Clip EQ in the Audio Inspector
Master EQ Controls
The Equalizer window has the following overall controls located in the upper
right and left corners.
• Enable button: Turns the overall EQ effect off and on, without resetting the controls.
• Reset button: Resets all controls of the EQ window to their defaults.
Clip EQ Graph
This graph displays the current EQ curve with handles that correspond to each enabled
EQ band listed below. You can drag any numbered handle to boost or attenuate the range
of frequencies governed by that band, using whatever type of equalization that band has
been set to..
The Clip EQ graph with user-draggable handles
Dragging the numbered handles on this graph in turn modifies the parameters of the
corresponding band, and changing each band’s parameters will also alter the EQ graph,
which serves the additional purpose of providing a graphical representation of the
equalization being applied to that track.
430Ingest and Organize Media | Chapter 20 Using the Inspector in the Media Page
MEDIA
Bands 1 and 6
The outer two sets of band controls let you make high-pass and low-pass adjustments, if necessary.
 Band enable button: Turns each band of EQ on and off.
 Band filter type: Bands 1 and 6 can be switched among five specific filtering options for
processing the lowest or highest frequencies in the signal.
```
 For Band 1, these include (from top to bottom): Lo-Shelf, Bell, Notch, Hi-Shelf, and Hi-Pass.
```
```
 For Band 6, the options are (from top to bottom): Lo-Pass, Lo-Shelf, Bell, Notch, and Hi-Shelf.
```
 Freq: Adjusts the center frequency of the EQ adjustment.
 Gain: Adjusts the amount by which the affected frequencies are impacted. Negative values
attenuate those frequencies, while positive values boost those frequencies.
 Q Factor: This parameter adjusts the width of affected frequencies and appears whenever the
```
Bell option is selected. Lower values include a wider range of frequencies; higher values include a
```
narrower range of frequencies.
Bands 2 through 5
These band controls let you make a wide variety of equalization adjustments.
 Band enable button: Turns each band of EQ on and off.
```
 Band filter type: Offers four filtering options (from top to bottom): Lo-Shelf, Bell, Notch,
```
and Hi-Shelf.
 Frequency: Adjusts the center frequency of the EQ adjustment.
 Gain: Adjusts the amount by which the affected frequencies are altered. Negative values
attenuate those frequencies, while positive values boost those frequencies.
 Q Factor: This parameter appears when the Bell setting is selected. It adjusts the width of affected
```
frequencies. Lower values include a wider range of frequencies; higher values narrow the range of
```
frequencies.
```
NOTE: There are many more refined plugins and effects for audio clips in the Audio FX
```
library. If you apply any of these, the controls will appear in the Inspector’s Effects tab Audio
section, instead of here.
431Ingest and Organize Media | Chapter 20 Using the Inspector in the Media Page
MEDIA
Image
The Image Inspector controμls for BRAW footage
The Image panel contains groups of parameters
that correspond to every camera raw media format
that’s supported by DaVinci Resolve. Using these
parameters in the Image panel, you can override
the original camera metadata that was written
at the time of recording and make simultaneous
adjustments to camera raw media throughout
your project.
For a detailed explanation of each of the
RAW camera parameters supported by
DaVinci Resolve, see Chapter 7, “Camera
Raw Settings.”
File
The File Inspector controls
432Ingest and Organize Media | Chapter 20 Using the Inspector in the Media Page
MEDIA
Metadata
The File panel of the Inspector provides a consolidated way to view and edit a subsection of a clip’s
most commonly used media file metadata. It’s easily accessible in the Inspector across the Media, Cut,
Edit, and Fairlight pages.
The tab is composed of the following parts:
```
Clip Details: Presents data about the clip’s data format (codec, resolution, frame rate, etc.).
```
```
Metadata: Presents a reduced set of common metadata fields for quick user entry.
```
• Timecode: The start timecode of the clip. This field is editable if you want to manually
change the clip’s starting timecode.
• Date Created: The date that the clip was created. This field is editable if you want to
manually change the clip’s creation date.

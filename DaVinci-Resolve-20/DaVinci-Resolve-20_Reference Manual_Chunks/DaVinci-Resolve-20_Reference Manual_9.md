• Camera: Sets the Camera # metadata.
• Reel: Sets the Reel/Card ID.
• Scene: The Scene number of the clip.
• Shot: The Shot letter/number of the clip.
• Take: The Take number of the clip.
• Good Take: This checkbox indicates if the clip is a good or circled take.
• Clip Color: Assign a specific color to a clip that is reflected in the Timeline.
• Name: This can be entered manually and changes a clip’s name in that specific
timeline only.
• Comments: Add a text description to the clip.
• Auto Select Next Unsorted Clip: When this box is checked, the next clip in the Media Pool
is selected when you hit the Return button after entering a metadata field, and the cursor is
automatically placed in the same field. This allows rapid sequential metadata entry without
having to manually click to load each individual clip in the Media Pool. The Next Clip button
will select the next clip in the Media Pool, regardless of the checkbox status.
Audio Configuration
The File tab in the Inspector now has an Audio Configuration pane that handles the controls that were
```
formerly handled by Clip Attributes in the Media Pool (though that option is still available). The Audio
```
Configuration pane provides a more intuitive and visual way of changing the track properties of an
audio clip. Simply click on an audio clip in the Media Pool or Timeline, and then on the File Inspector to
reveal this interface.
The pane features a per-channel waveform display for all tracks within a multichannel audio file. If the
tracks have been named in the audio recorder, these names will appear over their respective tracks as
well. The Audio Configuration panel can preview up to 36 tracks of audio.
At the top of the pane, a composite waveform is shown of all the tracks and is updated depending
on the mute status of individual tracks. By default this composite is heard when the Play button is
activated, and all channels are audible.
433Ingest and Organize Media | Chapter 20 Using the Inspector in the Media Page
MEDIA
The Audio Configuration panel. Track 3 has been
muted and Track 5 has been disabled.
A format menu allows you to choose common configurations for your source audio file without
cumbersome manual re-routing. Custom routing can still be accommodated by choosing
custom in the drop-down, which brings up the older clip attributes for situations that require less
common configurations.
Audio for a selected source or timeline clip can be played or skimmed by moving the cursor along the
waveform, and the specific track is solo’ed when skimming or playing. The play position or track being
monitored can also be switched dynamically during playback. For example, you can start playback on
track one, then simply click on track two, and the playback continues from that position. These controls
let you quickly skim through and identify exactly what audio is on which track for further adjustment.
Each track has two adjustments that can be made, an Enable/Disable checkbox and a
Mute button.
Enable/Disable: Enabling a track makes that track available for use in editing operations.
Disabling a track removes that track from use in editing operations. For example, if you disable
Track 2 of a 4-track audio file, when you drag that audio file from the Media Pool into the
```
timeline, only 3 tracks (1, 3, and 4) will come over.
```
```
These adjustments can only be made on Media Pool clips; audio clips already in the timeline
```
will have these options disabled.
```
Mute: Clicking this icon will mute the track so it is unheard but leave the actual track in place
```
when used in editing operations and dragged into the timeline. Option clicking a mute button
on a channel will allow you to solo by muting all other channels.
Underneath the track layout is a simple transport control comprised of Play and Stop buttons to start
and stop audio playback.
434Ingest and Organize Media | Chapter 20 Using the Inspector in the Media Page
MEDIA
Adjusting Trim Levels of Individual Channels in a Source File
The level of individual source clip channels in the audio inspector can be be adjusted via a trim
control. This allows source clip audio in one channel to be brought up in level or brought down in level,
as needed.
The trimmed level is internal to source clip in the Media Pool and will be inherited whenever that
source clip configuration is used on a timeline, unless it is changed.
```
NOTE: The trim level is totally separate from clip gain in the timeline. Be aware that trimmed
```
levels can clip if you move them too high.
You can adjust the trim levels of individual
audio channels in a multichannel clip.
Using the Trim slider
1 Select one or more channels in the Audio Configuration section of the File Inspector
2 Adjust the Level slider at the bottom to the desired audio level.
The waveform will adjust dynamically to the level value and will display a trimmed value in dB in the
channel itself. If you have multiple lanes selected, all channels will be trimmed together. Relative levels
are not stored, so if you adjust one, it will then force any others in the selection to match. When no
channel lanes are selected, the Level control is grayed out.
435Ingest and Organize Media | Chapter 20 Using the Inspector in the Media Page
MEDIA
Multiple Clip Selection and Adjustments
You can select multiple audio clips and adjust their properties in the Audio Configuration
pane. For example, you can select a group of audio files and remove Track 2 from all of them
at once. However, the following should be noted:
• In a multiple clip selection, only the last selected clip will appear in the track layout of
the Audio Configuration pane. However the top composite waveform will be named
“Multiple Clips” to let you know that more than one clip has been selected.
• Any adjustments, like muting or enabling/disabling a track will be applied to all the
selected clips at once.
Timecode
The File tab in the Inspector now has a Timecode pane that handles the types of controls that were
```
formerly handled by Clip Attributes in the Media Pool (though that option is still available). Here you
```
can override the timecode details for a clip or clips in the Media Pool.
 Current Frame: Lets you assign a new time for the timecode at the currently viewed frame of
the clip.
 Slate: In situations where source media comes from a shoot where a timecode slate was used
during the shoot, then you can assign the slate timecode as a second timecode track that can be
used for various operations, without changing the primary timecode of the clip, which may already
be in use for program sync.
To set appropriate Slate timecode, select a clip in the Media Pool with a visible timecode slate, and
move the playhead to a frame where the timecode in the slate is clearly readable. Then, open the
Timecode panel of the Clip Attributes window, and type the timecode value you see in the image
into the Slate Timecode field.
 Offset Source: If an entire set of clips has timecode that’s merely offset, you can correct the
timecode offset for as many selected clips as you like.
436Ingest and Organize Media | Chapter 20 Using the Inspector in the Media Page
MEDIA
Chapter 21
Syncing Audio
and Video
When you’re working on a program where the production audio was recorded
```
separately from the production video (often referred to as “dual-system recording),
```
DaVinci Resolve provides tools for syncing the audio and video together in a
variety of ways to create media that you can edit easily. The process of syncing
audio and video together is often referred to as “syncing dailies.”
Contents
Syncing Audio to Video 438
Syncing Audio to Video Using Timecode  438
Syncing Audio to Video by Matching Waveforms  439
Manually Syncing Audio to Video 440
Retaining Video Metadata and Embedded Audio when Syncing Audio Manually  441
Offsetting the Sync of Previously Synced Clips  442
Finding Synced Audio Files 442
Displaying Synced Audio File Names on the Timeline  443
437Ingest and Organize Media | Chapter 21 Syncing Audio and Video
MEDIA
Syncing Audio to Video
If you’re processing dailies for a shoot that used dual-system recording, where audio is recorded
to a separate device than video, you can “sync the dailies” in DaVinci Resolve in one of two ways.
Synced clips can be output as media files with embedded audio or output to tape, whatever your
client requires.
Syncing Audio to Video Using Timecode
Ideally, if the sound recordist on set was highly organized, and the camera and audio recorder both
used synchronized timecode, you can use a single command to automatically sync every clip in a
timeline to a bin of Broadcast .wav files that have matching timecode.
To batch sync audio to video using timecode:
1 Create a new project, open to the Media page by default, and import the video media you need to
sync into any bin of the Media Pool.
2 Import the matching Broadcast .wav files into the same bin as the accompanying video media you
imported in Step 1. If you want to stay more organized, you can create another bin to contain the
audio clips, but it must be inside the bin that contains the video files. The audio bin can be named
anything you like.
Organizing production audio in a bin created
within the accompanying camera media bin
3 Right-click the bin containing the matching audio and video clips, and choose one of the following
commands from the contextual menu:
Auto-Sync Audio Based on Timecode: Replaces each video clip’s previous audio channels with
audio channels from the newly synced .wav files.
Based on Waveform: Analyzes and compares the waveforms of each of the selected clips and
replaces each video clip’s previous audio channels with the newly synced .wav files.
Retain embedded audio: Adds new channels in addition to the audio channels that were
previously in the media file. The newly waveform-synced channels are added to an additional
track, so when edited into the timeline, a clip that’s synced this way appears with one video clip
and two audio clips that occupy two different audio tracks, so you can edit the camera original
audio independently from the synced audio.
Every clip in the selected bin for which there was an accompanying Broadcast .wav file with matching
timecode is immediately synced with an audio track. If multiple audio files overlap with matching time
code, each file will be synced and a new audio track added to the resulting clip to accommodate each
audio file. You can modify this behavior to only sync the single best matching file and ignore others
by checking the “Limit media pool audio sync to first timecode match” box in the Editing panel of the
User section in the DaVinci Resolve Preferences.
All synced clips appear with an audio icon at the bottom left in the Media Pool when Thumbnail view is
selected. Now that the clips are synced, you can edit them in the Edit page or use the Deliver page to
export offline dailies or online media with embedded sync audio for use in other applications.
438Ingest and Organize Media | Chapter 21 Syncing Audio and Video
MEDIA
Syncing Audio to Video
by Matching Waveforms
If you don’t have matching timecode in the audio and video source clips you’re syncing, but you had
the foresight to record camera audio at the same time as the dual source production audio you want
to sync to, DaVinci Resolve can use waveform syncing to compare the audio waveforms of your audio
and video source files, and sync the ones that match.
Progress dialog for syncing dialog using waveforms
To batch sync dailies using waveform syncing:
1 Create a new project, open to the Media page by default, and import both the video and audio
media you need to sync. There’s no need to organize your files in any particular way, but it’s not a
bad idea, on multi-day shoots, to organize the audio and video files so that it’s easy to select all of
a single day’s clips at once so that you can sync your files in smaller batches. Even organizing your
clips by scene can make waveform syncing go faster by reducing the number of files that need to
be compared at once.
2 If you’ve placed the audio and video into separate bins, then you can Command-click both bins
in the bin list to select them and expose all of their contents in the Media Pool. If you placed your
media in the same bin, this is not necessary.
3 Select one of the exposed clips in the Media Pool, and press Command-A to select all audio and
video clips you want to sync.
4 Right-click one of the selected clips, choose Auto Sync Audio from the contextual menu, and
select one of the methods below.
Based on Timecode: Synchronizes the timecode between the audio and video clips, and replaces
each video clip’s previous audio channels with the newly synced .wav files.
Based on Waveform: Analyzes and compares the waveforms of each of the selected clips, and
replaces each video clip’s previous audio channels with the newly synced .wav files.
Use channel number: Lets you choose which audio track to perform the waveform analysis
on. With the default of “Auto,” DaVinci Resolve automatically picks the channels most suited for
waveform comparison. With “Mix,” DaVinci Resolve compares waveforms from the mixdown audio
from all available channels. This can be useful when audio may not be present on long sections of
one or channels. Users can also specify individual channels to avoid noisy audio.
Retain embedded audio: Analyzes and compares the waveforms of each of the selected clips,
and adds new channels in addition to the audio channels that were previously in the media file.
The newly waveform-synced channels are added to an additional track, so when edited into the
Timeline, a clip that’s synced this way appears with one video clip and two audio clips that occupy
two different audio tracks, so you can edit the camera original audio independently from the
synced audio.
439Ingest and Organize Media | Chapter 21 Syncing Audio and Video
MEDIA
A progress bar dialog appears, showing you how long the syncing operation will take. When it’s
complete, your clips will be synced.
Progress dialog for syncing dialog using waveforms
```
TIP: After syncing, you may be notified via a dialog that one or more clips could not
```
be synced. Note these clips, as it may be possible to use waveform syncing more
successfully on just the selected pair of audio and video items that belong together.
Manually Syncing Audio to Video
If you have a collection of WAV or AIFF audio files with video source media that lacks matching
timecode, you need to manually sync each pair of media files together, one-by-one, using a
sync reference such as the clap of a clapperboard or any other sharp sound with a distinct
audio/visual correspondence.
To manually sync audio to video:
1 Create a new project, and import the video media you need to sync into the Media Pool. If a dialog
appears asking whether or not you want to update the project to match the media, click OK.
2 If you want to stay organized, create a second bin in the Media Pool, named Audio Clips, and
import the matching Broadcast .wav files into it. The name of the bin is not important, and having
all the audio in one bin is simply a matter of convenience.
3 Click the Waveform button at the top of the Audio Panel, which lets you view and scrub along the
waveform of audio clips you select in the Media Pool.
4 Select a video clip to sync, and move the Viewer playhead to line up with the first visual sync point
in the first clip. This could be the clap of a clapperboard, the red flash of a tablet computer’s slate
app, a hand clap, or any clear visual cue to which there is a corresponding audible sound.
5 Now, select whichever audio clip corresponds to the current video clip in the Viewer, to open its
waveform into the Audio Panel.
6 Use the Audio Panel transport controls and scrubber bar in the Source Viewer to move the
playhead to the audio sync point that corresponds to that video sync point. This may be a clap,
a beep, or some other staccato sound that’s easy to sync to. As you play through the clip, the
bottom half of the Viewer shows a zoomed out waveform for the entire clip, while the top half of
the Viewer shows a zoomed in section of the waveform that immediately surrounds the playhead.
Hopefully, the sync point you’re looking for is a distinct, loud spike somewhere towards the
```
beginning or the end (in the case of a tail slate) of the audio clip.
```
440Ingest and Organize Media | Chapter 21 Syncing Audio and Video
MEDIA
Aligning video and audio sync points with the Audio Panel set to show the Waveform panel
7 When you’ve found the audio sync point that matches the video sync point, click the Link/Unlink
Audio button at the bottom right of the Audio Panel to embed the now synced audio into the
video clip.
Clicking the sync link button to lock sync
The audio and video items are linked. At this point, you can use the newly synced clips in the Edit
page, and use the Deliver page to export offline or online media with embedded audio for editing.
Retaining Video Metadata and
Embedded Audio when Syncing Audio Manually
When syncing audio to video manually in the Media page, you can choose whether to include the
original camera audio tracks in the synced file, or whether to retain the camera scene/take metadata,
rather than have the audio file scene take metadata overwrite it as normal.
```
In the Media page > Audio > Waveform tab, the option (3 dot) menu now offers 2 choices:
```
```
The Audio > Waveform tab (3 dot) option menu lets you choose
```
to retain embedded audio and/or video metadata.
441Ingest and Organize Media | Chapter 21 Syncing Audio and Video
MEDIA
Retain embedded audio
 When enabled, embedded camera audio tracks are included with any newly synced audio during
```
the manual linking process (using the link icon on this pane).
```
Retain video metadata
```
 Default is off, which means that video files that are synced to audio files inherit metadata (e.g.,
```
```
scene and take) from the audio file. When this option is checked, the video file’s metadata is
```
retained and not overwritten instead.
Offsetting the Sync of
Previously Synced Clips
```
If you need to offset the audio (or stereo 3D) sync of the items that make up a clip later on, you need
```
only select the synced clip you want to resync in the Media Pool, then click the Waveform button at the
top of the Audio panel to show the clip’s audio waveform, turn off the linked clip button, change either
the audio or video sync points, and turn the linked clip button back on again.
You can also use two sets of commands for slipping the sync of any clip:
```
• Trim > Slip Audio > Slip Audio One Frame Forward/Reverse: (Option-Period and Option-
```
```
Comma) Slips the audio/video sync of any clip in whole frame increments.
```
```
• Trim > Slip Audio > Slip Audio One Subframe Forward/Reverse: (Option-Right Arrow and
```
```
Option-Left Arrow) Slips the audio/video sync of any clip in 1/10th frame increments.
```
```
• Trim > Slip Eye > Slip Eye One Frame Forward/Reverse: (Command-Option-Period and
```
```
Command-Option-Comma) Slips the sync relationship between the eyes within a stereo clip
```
in whole frame increments.
Finding Synced Audio Files
When you’ve synced dual-system audio and video clips together in DaVinci Resolve, you can find the
audio clip that a video clip has been synced to using the following procedure.
To find the audio clip that a video clip has been synced to:
 Show the Media Pool in List view, and reference file name in the Synced Audio column.
 Right-click a video clip that’s been synced to audio, and choose “Reveal synced audio in
Media Pool” from the contextual menu. The bin holding the synced audio clip is opened and that
clip is selected.
442Ingest and Organize Media | Chapter 21 Syncing Audio and Video
MEDIA
Displaying Synced Audio
File Names on the Timeline
For certain workflows you may wish to see the name of the original audio file used in a synced dual
system audio pair on the timeline tracks, rather than the name of the video clip its attached to.
To display the filename of the original audio file used in a synced pair in the timeline:
1 Choose View > Show File Names. You cannot see synced audio file names unless you’ve set
DaVinci Resolve to display the original file names.
2 Choose View > Overlay Synced Audio File Names. You should now see the names of the synced
audio files superimposed on the audio clips in the Timelines, and the names of the video files
superimposed on the video clips in the Timelines, even when they’re synced.
Viewing the synced audio file names in the Edit page Timeline
443Ingest and Organize Media | Chapter 21 Syncing Audio and Video
MEDIA
Chapter 22
Modifying Clips
and Clip Attributes
Once you’ve added clips to the Media Pool, you may find you have to make some
changes to prepare it for use in your project.
This chapter covers diverse tasks that include redefining the clip attributes associated with each
source clip to reinterpret video and audio attributes, timecode values, and clip names, converting
LTC timecode recorded on an audio track into usable timecode, chopping long clips into more
manageable subclips, and creating stereo clips from left and right eye media.
Contents
Adjusting Media Pool Clips in the Inspector  445
Changing Clip Attributes  445
Video Attributes 446
Real-Time 3:2 Pulldown Removal 448
Audio Attributes 449
Timecode Attributes  452
Reel Name Attributes  453
Update Timecode from Audio – LTC  454
Changing Clip Thumbnails in the Media Pool  454
Creating Subclips  455
Removing or Changing Subclip Limits 455
Organizing Stereo 3D Media  456
Camera Raw Decoding  456
444Ingest and Organize Media | Chapter 22 Modifying Clips and Clip Attributes
MEDIA
Adjusting Media Pool Clips in the Inspector
You can directly modify Media Pool clips in the Inspector, before you edit those clips into a timeline.
This allows you to change the parameters of source media so that clips that are subsequently edited
into a timeline carry those new settings with it. For example, you can prepare your material prior to
editing by changing the clip’s file and RAW settings, adjusting the audio levels and EQ, or assigning
it a specific lens correction, etc. Once modified, any part of that clip would have the correct Inspector
parameters already in place when you edited them into your timeline.
For more information about using the Inspector in the Media Pool, see Chapter 20, “Using the
Inspector in the Media Page.”
Changing Clip Attributes
Using the Clip Attributes window, you can alter additional attributes for multiple clips all at once. This
window has some overlap with other clip attributes that are editable directly from submenus within the
Media Pool clip contextual menu.
To edit the attributes of one or more clips in the Media Pool of any page:
1 Select one or more clips in the Media Pool by Shift-clicking, Command-clicking, or dragging a
bounding box around them.
2 Right-click one of the selected clips, and choose Clip Attributes.
3 Click to open the panel of the attributes you want to edit. If you’ve selected multiple clips, then
making your alterations automatically checks the box of the attributes being changed.
4 When you’re finished, click OK to accept the changes.
You can also edit select clip attributes for clips that have been edited into the Timeline.
To edit the attributes of one or more clips in the Timeline of the Cut, Edit, or Color pages:
1 Select one or more clips in the Timeline by Shift-clicking, Command-clicking, or dragging a
bounding box around them.
2 Right-click one of the selected clips, and choose Clip Attributes.
3 Click to open the panel of the attributes you want to edit. If you’ve selected multiple clips, then
making your alterations automatically checks the box of the attributes being changed.
4 When you’re finished, click OK to accept the changes.
445Ingest and Organize Media | Chapter 22 Modifying Clips and Clip Attributes
MEDIA
Video Attributes
These affect individual clip frame rate, geometry, and data levels.
The Video panel of the Clip Attributes Window
 Video Frame Rate: In cases where a clip’s frame rate was specified incorrectly by another
application or recording device, or if there is no frame rate metadata available at all, you can
change what DaVinci Resolve considers the frame rate of the source clip to be by either using
this menu to choose a frame rate from 1 to 120 fps, or choosing Custom and entering a value
```
from 1 to 32,000 fps (to accommodate high-speed and specialty format video). Changing a clip’s
```
Video Frame Rate will change its duration and relative playback speed in DaVinci Resolve. A clip’s
audio, however, will be unaffected. Please note, just because extremely high frame rate media is
supported, do not expect real time performance at excessively high frame rates, and understand
that what performance your workstation is capable of depends on its configuration and the speed
of your storage.
 Data Levels: In certain circumstances, you may find that you need to manually choose appropriate
data levels for clips that are not being interpreted correctly, choosing between Auto, Video,
and Full. For more information on this setting, and how it affects the image data in your project,
see Chapter 9, “Data Levels, Color Management, and ACES.”
 Pixel Aspect Ratio: In projects using a mix of media with different frame sizes, you can assign
specific pixel aspect ratios using this drop-down menu. You can also change the Pixel Aspect
Ratio to a manual value to adjust and compensate for various motion picture capture technologies.
Select Custom from the Pixel Aspect Ratio menu, and then enter a numeric value in the box
below. The value is the X in the 1:X ratio. For example, you would type in 1.6 to get a pixel aspect
ratio of 1:1.6.
446Ingest and Organize Media | Chapter 22 Modifying Clips and Clip Attributes
MEDIA
 Horizontal and Vertical Image Flip: Modifies the horizontal and vertical image flip camera
metadata for r3d clips, which is useful for stereoscopic 3D projects shot with a mirrored camera
rig that reverses the media from one eye, or in cases where steadicam rigs result in upside-
down clips. These settings are different from the Flip Image controls in the Sizing palette of the
Color page.
 Image Orientation: For media that has an orientation setting, this lets you change the rotation
of that media so that it’s correctly oriented. Four settings let you adjust by 0º, 90º right, 180º,
and 90º left.
 Input Sizing Preset: You can use this panel to assign a Sizing palette preset to select clips. For
example, if you have a special Input Format Preset for standard definition PAL widescreen clips
that you’ve edited into a high definition project, you can do a sort in the Media Pool to isolate
them, and then select them all and apply this preset.
 Field Dominance: By default, the Auto setting enables DaVinci Resolve to automatically determine
whether a particular clip is Upper- or Lower-field dominant. If this automatic determination is
wrong, you can choose Upper or Lower to manually override this.
```
 Enable Deinterlacing: (only available in Studio version) This checkbox is only enabled if “Enable
```
video field processing” is turned off in the Master Settings panel of the Project Settings. Turning
the Enable Deinterlacing checkbox on sets DaVinci Resolve to deinterlace clips using the
Deinterlace quality setting that’s located in the Image Scaling panel of the Project Settings.
Normal is a high-quality deinterlacing method that is suitable for most clips, while High is a more
processor-intensive method that can sometimes yield better results, depending on the footage.
The DaVinci Neural Engine option uses advanced machine learning algorithms to reconstruct the
frame, which will ideally give even better results than the High setting.
 Alpha Mode: The options presented here depend on the format of the clip you’ve selected, since
```
only certain formats (such as ProRes 4444, QuickTime Animation, OpenEXR, TIFF sequences, and
```
```
so on) are capable of containing alpha channels. If you’ve imported clips with embedded alpha
```
```
channels, this panel lets you enable or disable their use in DaVinci Resolve (by choosing None),
```
```
choose the type of alpha channel (Premultiplied or Straight), or invert the alpha channel. If you
```
select a clip that doesn’t contain an alpha channel, then most of these options don’t appear.
The Alpha Mode options that are available when a clip has an embedded alpha channel
 Super Scale High Quality Upscaling: For instances when you need higher-quality upscaling than
the standard Resize Filters allow, you can now enable one of three “Super Scale” options in the
Video panel of the Clip Attributes window for one or more selected clips. Unlike using one of the
numerous scaling options in the Edit, Fusion, or Color pages, Super Scale actually increases the
source resolution of the clip being processed, which means that clip will have more pixels than
it did before and will be more processor-intensive to work with than before unless you optimize
```
the clip (which bakes in the Super Scale effect into the optimized media), or cache the clip
```
in some way.
447Ingest and Organize Media | Chapter 22 Modifying Clips and Clip Attributes
MEDIA
The Super Scale drop-down menu provides the options of 2-3-4x and 2-3-4x Enhanced, as well
as Sharpness and Noise Reduction options to tune the quality of the scaled result. Most of the
Super Scale parameters are in fixed increments, however the Enhanced modes let you apply
Super Scale in variable amounts. Selecting one of these options enables DaVinci Resolve to
use advanced algorithms to improve the appearance of image detail when enlarging clips by a
significant amount, such as when editing SD archival media into a UHD timeline, or when you find
it necessary to enlarge a clip past its native resolution in order to create a closeup.
You may find that, depending on the source media you’re working with, setting Sharpness to
Medium yields a relatively subtle result that can be hard to notice, but setting Sharpness to high
should be immediately more preferable, while also sharpening grain and noise in the image to an
undesirable extent at the default settings. However, while raising Noise Reduction will ameliorate
this effect, it will also diminish the gains you obtained by raising Sharpness. In these cases, it’s
worth experimenting with keeping Sharpness at Low or Medium so that Super Scale sharpens all
```
aspects of a clip, but then using the Noise Reduction tools of the Color page (with their additional
```
```
ability to be fine-tuned) to diminish the unwanted noise.
```
Super Scale options in the Video panel of the Clip Attributes window
```
TIP: Super Scale, while incredibly useful, is an extremely processor-intensive operation,
```
so be aware that turning this on will likely prevent real-time playback. One way to get
around this is to create a string-out of all of the source media you’ll need to enlarge
at high quality, turn on Super Scale for all of them, and then render that timeline as
individual clips, while turning on the “Render at source resolution” and “Filename uses >
Source Name” options.
Real-Time 3:2 Pulldown Removal
If you have 29.97fps interlaced material that was encoded with a 3:2 pulldown, DaVinci Resolve
can reconstruct the original footage’s progressive frame rate in real time. For example, if you
```
have source media from a film camera (24fps progressive) that has been telecined to NTSC video
```
```
(29.97fps interlaced), DaVinci Resolve can pull the original 24 discrete film frames out of the various
```
interlaced fields that make up the NTSC signal.
To remove 3:2 pulldown in real time:
1 Select one or more 29.97 fps interlaced clips in the Media Pool.
2 Right-click one of the selected clips and select Clip Attributes.
3 In the Video tab, turn on the Remove 3:2 Pulldown checkbox.
4 Set the Frame where the 3:2 cadence started in the “First Frame of Clip” drop-down
```
(this is usually the “A” frame).
```
5 Click OK.
The footage will now behave like a 24fps progressive clip.
448Ingest and Organize Media | Chapter 22 Modifying Clips and Clip Attributes
MEDIA
```
Telecine footage with 3:2 pulldown removed; the scrambled number
```
```
(mix of the numbers 1 and 2) at the end of the KeyKode is a field indicator,
```
showing that this A frame was created properly from fields 1 and 2 of the
interlaced signal.
Audio Attributes
The Audio panel lets you alter the channel format and channel assignments for one or more clips.
These settings affect what appears in the audio tracks of the Timeline when you edit a clip into a
program. When you first import clips into the Media Pool, you can use the Audio Attributes panel
to define which embedded audio channels can be exposed as tracks in the Edit and Fairlight page
timelines for editing, and how they will appear.
The Audio panel of the Clip Attributes window
449Ingest and Organize Media | Chapter 22 Modifying Clips and Clip Attributes
MEDIA
Add Track Controls
A set of controls at the top of the Track/Channel list lets you add additional tracks to a clip.
Adding additional tracks to a clip lets you remap that clip’s available channels to appear in the
Timeline when you edit it.
 Format: A drop-down that lets you choose a format for new tracks that you add. The setting you
choose here affects how many channels appear in the Channel Assignments list below, as well as
what kind of Timeline audio track will be required to expose all channels of that clip. If you choose
a Channel Format with fewer channels than are embedded in a clip, all extraneous channels will
be disabled. The available options are:
```
Mono: Appropriate for single-channel clips
```
```
Stereo: Appropriate for clips with two-channel left/right audio
```
5.1: Appropriate for 5.1 surround mixes
7.1: Appropriate for 7.1 surround mixes
```
Adaptive: Appropriate for multiple-mono production audio, such as multi-channel recordings
```
where a boom microphone, two separate lavaliere microphones, and a mixdown track are
recorded simultaneously.
 Tracks: Lets you adjust how many tracks you want to add to the current clip or clips. Each track
you add will result in an additional linked audio item being edited into an additional audio track
when this clip is edited into the Timeline. For example, if you have a multi-channel production
recording with four different microphones, you can add 3 mono audio tracks, and then assign each
channel to a separate track to expose each channel as an individual audio clip in the Timeline for
purposes of editing each microphone separately.
 Add button: Lets you add the tracks you’ve specified to the current clip or clips.
A clip with a single track of two-channel stereo audio at left, compared to
a clip with two tracks of single channel mono audio at right
Audio Track and Channel List
The list below the Add Track controls show an entry for each track defined within the currently
selected clip or clips. Pop-ups within this list let you redefine and map how that clip’s channels are
spread across the differently mapped tracks you’ve created.
 Format: The format of each audio track. Can be Mono, Stereo, 5.1, 7.1, or Adaptive.
 Source Channel: Each track lists however many channels the specified format requires.
A Stereo track has two source channels, a 7.1 track has eight source channels. Channels appear
hierarchically underneath the track they belong to. If you wish to remove a specific channel
from the clip, you can choose <none> from the list.
 Track: The name of each track in a clip.
 Channel in Track: The name of each channel in that track.
450Ingest and Organize Media | Chapter 22 Modifying Clips and Clip Attributes
MEDIA
 Delete Track button: Hovering the pointer over a track reveals a trashcan icon you can click to
delete that track.
```
A trashcan button you can use to delete an audio track within Clip Attributes;
```
it only appears when you hover the mouse over a track
Support for Mixed Audio Track Formats from Source Clips
DaVinci Resolve also supports media with multiple audio tracks that have differently formatted
channels embedded within them. For example, a clip with one stereo track, one 5.1 surround track,
and six mono tracks can all be appropriately set up in the Audio panel of Clip Attributes after that clip
has been imported.
```
The Audio panel of Clip Attributes now has controls over what format (Mono, Stereo, 5.1, 7.1, Adaptive)
```
the channels embedded within a particular clip should be configured as. This means that you can set
up clips with multiple tracks, each one using potentially different formats of audio employing different
combinations of clips, which is handy for mastering.
Clip Attributes now leμts you assign channels among different
tracks with different channel assignments
451Ingest and Organize Media | Chapter 22 Modifying Clips and Clip Attributes
MEDIA
Timecode Attributes
If you find yourself dealing with clips that have incorrect timecode, or timecode with an incorrect
relationship to the EDL, XML, or AAF project you’ve been given, you can use these attributes to modify
the timecode and reel name of clips in the Media Pool. None of these tools alter the source media on
disk. They simply change the timecode metadata in your DaVinci Resolve project, which by extension
affects the timecode of any media you render.
The Timecode panel of the Clip Attributes window
 Current Frame Timecode: Lets you assign a new time for the timecode at the currently viewed
frame of the clip.
 Slate Timecode: In situations where source media comes from a shoot where a timecode slate
was used during the shoot, then you can assign the slate timecode as a second timecode track
that can be used for various operations, without changing the primary timecode of the clip, which
may already be in use for program sync.
To set appropriate Slate timecode, select a clip in the Media Pool with a visible timecode slate, and
move the playhead to a frame where the timecode in the slate is clearly readable. Then, open the
Timecode panel of the Clip Attributes window, and type the timecode value you see in the image
into the Slate Timecode field.
 Offset Source Timecode: If an entire set of clips has timecode that’s merely offset, you can correct
the timecode offset for as many selected clips as you like.
452Ingest and Organize Media | Chapter 22 Modifying Clips and Clip Attributes
MEDIA
Reel Name Attributes
The “Assist using Reel Names” checkbox in the General Options panel of the Project Settings is an
extremely important setting for controlling how the conform process works. By default it’s turned off,
and Reel Names are left blank. This is fine for conform workflows where all you need is the file path
or file name and source timecode to successfully identify which media files correspond to what clips.
However, if you need more information than that to reconform the clips in your project, you can turn
on the “Assist using Reel Names” checkbox to enable DaVinci Resolve to use one of four different
methods to automatically define reel names for every clip in the Media Pool.
Using the Clip Attributes dialog, you also have the option of manually defining how one or more
selected clips in the Media Pool have their Reel Names defined. This is useful when there are certain
clips in a project that need to use a different method of reel name extraction, or manually entered
reel names. Once you’ve used Clip Attributes to change the reel names of clips, those clips no longer
automatically update when you change the “Assist using Reel Names” options in the Project Settings.
You must first turn on “Assist using Reel Names” in the General Options of the Project Settings, and
choose a Reel Assist setting, for the reel name attributes in the Clip Attributes window to be editable.
The Reel Name panel of the Clip Attributes Window
 Source clip file pathname: Obtains the reel name by extracting it from each media file’s path.
This makes it possible to extract a reel name from all or part of the file name, or from all or part
of the name of any folder in the path that encloses that file. This extraction is defined using
the Pattern field.
 Pattern: A code that defines how a reel name should be extracted from the source clip pathname.
More information about creating patters appears later in this chapter.
453Ingest and Organize Media | Chapter 22 Modifying Clips and Clip Attributes
MEDIA
 Media Pool bin name: The reel name is obtained from the name of the bin in the Media Pool that
encloses that clip. For example, in a stereoscopic workflow you might want to export offline stereo
media with the “Left” and “Right” bin names in which they’re organized as reel names. Another
example would be organizing VFX being incrementally processed in individually named bins, such
as “VFX_Tuesday_10-12.”
 Embedding in Source clip file: Useful for file formats where the reel name is embedded within the
media file itself. CinemaDNG and other digital cinema cameras, QuickTime files created by Final
Cut Pro, and DPX frame files are formats that can contain reel name header data.
 Source clip filename: If there is no defined reel number, often it’s easy to just use the
Source clip filename.
 User Defined: This option is only available when you manually alter the reel name for one or
more selected clips in the Media Pool using the Clip Attributes dialog. Choosing User Defined lets
you type any string of text you like to use as the reel name.
Update Timecode from Audio – LTC
Some cameras do not offer the ability to sync to an external timecode source. Their recorded
timecode may be time of day or free run timecode, but it would not be frame accurately synced to
other cameras, the dual system audio recorder or the digital slate. This makes multi-cam or dual sound
system syncing a time consuming manual operation.
DaVinci Resolve offers a solution to this problem if, by connecting an externally generated timecode to
the camera audio input, the video that’s recorded by the camera has a timecode reference recorded
on the audio track during the shoot.
Select this clip, or clips, in the media pool, then right-click on one of the highlighted clips and select
“Update timecode from audio - LTC.” DaVinci Resolve automatically and instantly updates the clip
timecode using the LTC it finds on the audio tracks. You can now use the clips as though they were
synced on set.
Changing Clip Thumbnails
in the Media Pool
When the Media Pool is in Thumbnail mode, each clip is represented by a small image that defaults to
the first frame of that clip. You can scrub the thumbnail of any clip to view its contents using the pointer
after hovering over it for a moment. However, when you’re done scrubbing, moving the pointer away
from any clip returns its thumbnail to the first frame of media, which may or may not be representative
of its contents. You can change this, if you like.
To customize the thumbnail of any clip:
1 Move the pointer over a clip you want to customize the thumbnail of.
2 Hover for a moment, then scrub to a representative frame.
3 Right-click that clip, and choose Set Poster Frame, or press Command-P.
To clear the custom poster frame of any clip:
 Right-click a clip, and choose Clear Poster Frame, or press Option-P.
454Ingest and Organize Media | Chapter 22 Modifying Clips and Clip Attributes
MEDIA
Creating Subclips
Subclips give you another way of organizing media in the Media Pool, letting you break excessively
long clips into shorter ones. For example, if the director of a project is fond of “rolling takes” where
multiple takes are all recorded within a single clip, you can break these takes up by making them
into subclips.
To create a subclip:
1 Select any clip in the Media Pool to open it into the Viewer.
2 Set In and Out points to define the section you want to turn into a subclip.
3 Do one of the following:
 Right-click the jog bar and choose Make Subclip.
 Drag a clip from the Viewer or Source Viewer into the Media Pool.
4 A new subclip dialog appears, allowing you to name the subclip and decide to use its full extents
by turning on the checkbox.
The New SubClip dialog
Once created, subclips appear and work like any other clip in DaVinci Resolve. You can also create
subclips in the Media page while performing other organizational tasks there.
Removing or Changing Subclip Limits
Once created, you can right-click any subclip in the Media Pool or a timeline and choose Edit Subclip
to open a dialog in which you can turn on a checkbox to use the subclip’s full extents, or to change the
start or end timecode of the subclip via timecode fields, before clicking Update to modify the subclip.
The Edit Subclip dialog
455Ingest and Organize Media | Chapter 22 Modifying Clips and Clip Attributes
MEDIA
Organizing Stereo 3D Media
When working with stereo media in DaVinci Resolve, one of the first tasks you must perform is that of
syncing each stereo pair of clips to act as a single clip. This is easily accomplished so long as you’re
careful about how you organize your media in the Media Pool.
Each set of right- and left-eye media should always be organized into separate left-eye bins and right-
eye bins, to facilitate later syncing of these clips using the Stereo 3D Sync command in the Media Pool
contextual menu.
For more information about setting up media for stereo workflows, “see Chapter 15,
“Stereoscopic Workflows.” In section called “Stereoscopic Workflows”
Camera Raw Decoding
Camera raw media formats are so named because they capture raw color space data directly from the
sensor of whatever digital cinema camera did the recording. Raw image data is not human readable,
and must be debayered or demosaiced to convert the original raw data into image data that can be
handed off to DaVinci Resolve’s image processing pipeline.
There are four ways you can control how camera raw media is debayered into a useful, “normalized”
image for adjustment or output:
 The Camera Raw panel of the Project Settings contain groups of parameters that correspond to
every camera raw media format that’s supported by DaVinci Resolve. Using these parameters
in the Camera Raw panel, you can override the original camera metadata that was written at
the time of recording, and make simultaneous adjustments to all camera raw media throughout
your project.
 The Image Panel in the Inspector also contains the controls for every raw media format
that’s supported by DaVinci Resolve. Allowing you to select all, some, or individual clips
for raw debayering.
 The Camera Raw palette in the Color page lets you individually adjust Camera Raw parameters
for individual clips in the Timeline.
```
 When you use Resolve Color Management (RCM) in a project that uses Camera Raw formats,
```
color science data from each camera manufacturer is used to debayer or demosaic each camera
raw file to specific color primaries with linear gamma, so that all image data from the source is
preserved and made available to DaVinci Resolve’s color managed image processing pipeline.
As a result, the Camera Raw project settings and Camera Raw palette of the Color page are
disabled, because RCM is controlling the debayering of all camera raw clips, and all image data
from the raw file is available for conversion to the Timeline Color Space you choose to work with
as you grade.
For more information about each of the Camera Raw formats that can be adjusted in
DaVinci Resolve, see Chapter 7, “Camera Raw Settings.”
456Ingest and Organize Media | Chapter 22 Modifying Clips and Clip Attributes
MEDIA
Chapter 23
Using
Scene Detection
If you have a program that someone has delivered as a single media file, with no
accompanying EDL with which to split it up, you can use DaVinci Resolve’s Scene
Detect window to automatically find the cut points and split it into individual clips,
ready for grading.
Contents
```
Scene Cut Detection on the Timeline (Studio Version Only)  458
```
Scene Detection in the Media Page  459
The Scene Detect Window Interface  459
The Scene Detect Viewers  459
The Scene Detect Graph 461
Cut List  462
The Scene Detect Options Drop-down Menu  463
An Example Scene Detect Workflow  463
457Ingest and Organize Media | Chapter 23 Using Scene Detection
MEDIA
Scene Cut Detection on the Timeline
```
(Studio Version Only)
```
If you need to break down a previously edited video into its component clips for re-editing or color
correction, you can now do so directly in an Edit or Cut page Timeline. Using the DaVinci Neural
Engine, DaVinci Resolve can automatically analyze and split up an edited video into individual clips.
If you prefer, you can continue to use the original Scene Cut Detection tool found in the Media Pool
and described later in this chapter.
To use Scene Cut Detection on the Timeline:
1 Put one or more clips you want to split on the Timeline. If you have clips on more than one video
track, you can selectively lock/unlock tracks or enable/disable the Auto Track Selectors to limit the
scene detection to specific video tracks. Additionally, you can limit Scene Cut Detection to just a
portion of a clip by setting In and Out points on the Timeline around the section you want to analyze.
2 Choose Timeline > Detect Scene Cuts.
A dialogue box appears, “Detecting scene cuts in clips x of x.” This process can take some time,
depending on the length, number, and complexity of the clips you’ve selected. When the Scene Cut
Detection has finished, the clip you selected will be broken up into a number of through edits that now
can be used as independent clips.
Checking and Fixing Your Results
If the Neural Engine has made an error, you can fix it manually by navigating to the cut using the Up
and Down Arrow keys to go back and forth in the Timeline, and by then doing one of the following:
 To remove a Cut: Click the through edit to select it, and press the “Delete” key.
 To make a New Cut: Place the timeline indicator at the cut point, and choose Timeline >
```
Split Clips (Command-\).
```
A single clip of a finished edit, consisting of multiple cuts before the Detect Scene Cuts command
```
Multiple individual clips extracted from the edited clip via Detect Scene Cut; the operation has been
```
contained by the In and Out points, and one of the resulting through edits has been highlighted in green.
458Ingest and Organize Media | Chapter 23 Using Scene Detection
MEDIA
Scene Detection in the Media Page
You can still perform automatic scene detections using the original tools in the Media page. When
using the original Media page Scene Detection, it’s important to note that the analysis and splitting of
the selected clip is done in the Media Storage panel, before the clip is added to the Media Pool.
To open a clip into the Scene Detect window:
1 Open the Media page, and use the Media Storage browser to find and select the clip you need to
split apart. Do not add a clip you want to use scene detection on to the Media Pool first. You need
to use Scene Detection before the clip has been imported.
2 Right-click the file and choose Scene Cut Detection.
3 The Scene Detect window opens up, containing the clip you selected.
4 Press the Auto Scene Detect button in the lower left of the interface.
DaVinci Resolve scans through the selected scene and analyzes the media for possible cut points.
The Scene Detect Window Interface
The Scene Detect window is divided into three main areas, the viewers, the Graph, and the Cut List.
Together, these controls let you analyze the movie, examine the automatically found cuts, and manage
the Cut List in preparation for sending back to your project.
Scene Detect window
The Scene Detect Viewers
A set of three viewers appear at the top of the Scene Detect window, one main viewer and two smaller
```
picture-in-picture (PiP) viewers. These three viewers are designed to make it easy to test whether
```
the playhead in the Scene Detect Graph is on a cut point or not. The leftmost PiP viewer is the last
outgoing frame of a detected cut point. The main viewer shows the first incoming frame of that cut
point, and the rightmost PiP viewer shows the second incoming frame of that cut point.
459Ingest and Organize Media | Chapter 23 Using Scene Detection
MEDIA
If the playhead in the Scene Detect Graph is directly on top of an edit point, the leftmost viewer
should show a completely different frame than the center and rightmost viewers, which should be very
similar to one another. If this is the case, you have found a correct cut point. This can be seen in the
following example.
The Scene Detect viewers show the last frame of the outgoing clip, and the first two frames of the incoming clip.
If the left viewer is significantly different than the main and right viewers, this indicates a correct cut point.
If all three viewers appear to display a continuous series of frames, then you’re not looking at a
cut point.
No scene cut here as all images are almost the same
Underneath the viewers are a series of controls.
The Scene Detect viewer transport controls
 Transport controls: A set of seven transport controls include first frame, step back, play reverse,
stop, play forward, step forward, and last frame.
460Ingest and Organize Media | Chapter 23 Using Scene Detection
MEDIA
The In, Out, Prune, and Show Cut List controls
 In: Lets you set an In point, with which to define a range of the Scene Detection Graph to prune.
 Out: Lets you set an Out point, with which to define a range of the Scene Detection
Graph to prune.
```
 Prune: If you’ve identified a large number of false positive scene cuts (for example, a cluster of
```
```
cuts corresponding to a dissolve from one shot to another), use the In and Out buttons to surround
```
the undesirable range of scene cuts in the Scene Detect Graph, and then click Prune to eliminate
all scene cuts between these points that are within one frame of another scene cut. Within the
group of identified cuts, the highest probability cut will remain while the other cuts are deleted.
```
(Left) Isolating scene cuts to prune with In and Out points, (Right) The result of
```
clicking the Prune button to eliminate all unwanted scene cuts but one
 Show Cut List: Shows and hides the Cut List, which shows the currently detected scene cuts.
The Scene Detect Graph
The majority of the bottom half of the Scene Detect window, to the left, consists of the Scene Detect
Graph, which shows the scene detect analysis results after you’ve clicked the Start button.
Frames that DaVinci Resolve thinks are cut points appear as green vertical “scene cuts” of various
heights. The height of each scene cut corresponds to the likelihood that frame is really an edit point,
and not a swish pan, sudden jump in the motion of the frame, or abrupt change in color or lighting, all
of which can fool the scene detection algorithm.
A horizontal magenta confidence bar lets you choose the threshold of confidence required for
scene cuts to be added to the Cut List. If you drag this bar up above any shorter scene cuts of low
confidence, those lines turn gray and are omitted from the Cut List.
461Ingest and Organize Media | Chapter 23 Using Scene Detection
MEDIA
Detection graph displays potential scene cuts
```
NOTE: Dissolves and other transitions are not automatically detected, although dissolves
```
most often appear as a triangular cluster of lines peaking in the middle.
Four controls appear underneath the graph.
 Auto Scene Detect: This initiates the scene cut detection process.
 Add: Lets you manually add a scene cut at the current position of the playhead. Sometimes two
adjacent clips with similar color and lighting will appear to be a single clip to the scene detection
algorithm. This lets you add scene cuts at frames where they weren’t initially found.
 Delete: Lets you manually delete a scene cut located at the position of the current frame indicator
within the graph.
 Zoom slider: Lets you zoom into and out of the Scene Detect Graph to see more or less detail as
you examine the results.
Cut List
At the lower right of the Scene Detect window, the Cut List displays one entry for each of the scene
cuts that intersect the confidence bar.
The Cut List shows all
currently detected cuts
Three columns show each cut’s order number, frame number, and timecode
value. You can select items in the Cut List to evaluate each cut using the
three viewers above. Whenever you select a new item in the Cut List, the
playhead jumps to that frame in the Scene Detect Graph.
To select items in the Cut List:
 Click any item in the Cut List.
```
 Press N (next) or the Down Arrow to select the next item down.
```
```
 Press P (previous) or the Up Arrow to select the next item previous.
```
As you move up and down the list, you can delete items that you can confirm
aren’t real cuts using the viewers above. If it’s a long list and you don’t have
time to check it all at once, it can be saved for later recall using commands
found in the Scene Detect Options drop-down menu.
Once you’re finished checking the list and are satisfied that each cut is
accurate, you can use it to split the media file into individual clips in the
Media Pool by clicking “Add Cuts to Media Pool,” located immediately below.
462Ingest and Organize Media | Chapter 23 Using Scene Detection
MEDIA
The Scene Detect Options Drop-down Menu
The Options drop-down menu, located at the upper right-hand corner of the Scene Detect window,
contains a variety of commands.
 Reset Zoom: Sets the zoom level of the Scene Cut Graph such that the entire clip fits
within the current width.
 Reset Marks: Clears the current In and Out points you’ve set.
```
 Prune Scene Cuts: If you’ve identified a large number of false positive scene cuts (for example, a
```
```
cluster of cuts corresponding to a dissolve from one shot to another), use the In and Out buttons
```
to surround the undesirable range of scene cuts in the Scene Detect Graph, and then click Prune
Scene Cuts to eliminate all scene cuts between these points that are within one frame of another
scene cut. Within the group of identified cuts, the highest probability cut will remain while the
other cuts are deleted.
 Save Scene Cut: Saves the current scene cut detection information, including the probability
metadata, to disk. Scene Cut files use the file extension .sc and can be reimported later to
continue working on a lengthy scene detection task.
 Load Scene Cut: Imports an existing .sc file into the Scene Detect window. You must first open the
media file you’re working on into the Scene Detect window before you can load a Scene Cut file.
 Save EDL: Exports the Cut List as a CMX-style EDL.
 Load EDL: Loads a CMX-style EDL into the Cut List, letting you use the cut information from the
EDL during the Scene Cut Detection process.
 Auto Cue: When enabled, the playhead jumps to each new scene cut as it’s detected when
you initiate scene detection. This lets you evaluate each scene cut as it’s found using the
three viewers above.
An Example Scene Detect Workflow
This section describes an ideal workflow for using scene detection without an EDL.
To scene detect a media file:
1 Locate a media file to scene detect using the Media Storage browser of the Media page.
2 Verify its frame rate and if it uses drop-frame timecode, and make sure that the “Timeline frame
rate” matches the “Use drop frame timecode” parameter in the Master Settings panel of the
Project Settings. These parameters are not automatically set if the project already has media in the
Media Pool, and you may have problems if they don’t match your media.
3 Right-click the media file, and choose Scene Cut Detection.
4 When the Scene Detect window appears, click the Options drop-down menu and choose Auto
```
Cue (it should be on by default, but it’s always good to check), then click Auto Scene Detect.
```
Scene detection initiates, and you can evaluate each scene cut as it’s found. If any scene cut looks
```
wrong (three sequential frames in a row), note its place in the list for future evaluation.
```
5 When DaVinci Resolve has finished scene detection, move the playhead to some of the shorter
scene cuts, and verify if they’re actual cuts by checking the three viewers above. If the frames
being displayed are “different-same-same,” then it’s a genuine cut.
```
If the frames being displayed are “same-same-same” (actually three sequential frames),
```
then these aren’t cuts.
463Ingest and Organize Media | Chapter 23 Using Scene Detection
MEDIA
```
TIP: Fast camera motion such as whip pans, sudden changes in lightness such as camera
```
flashes, or even film coming up to speed causing the shutter to “flash” can confuse the
analysis, which looks for large changes in the image.
6 If there are numerous low-confidence scene cuts that you’ve verified aren’t cuts, drag the magenta
confidence bar so that the low-confidence scene cuts fall below it to automatically remove them
all from the list.
7 Next, you may want to move down the Cut List, evaluating each scene cut to verify that it’s correct.
Click the first scene cut in the list, check it, then press the keyboard Down Arrow key to select the
next list item down, check it, and repeat until you’ve checked every item in the list. If you need to
move back up the list, you can press the Up Arrow key to select the previous list item. If any item
is not a cut point, click the “Delete” button at the bottom left corner of the Scene Detect window to
eliminate that scene cut.
8 If there are sections in the Scene Detect Graph with dense groups of spikes, these are probably
frames with types of motion that confused the Scene Cut Detector. To delete this unwanted
“noise” in the data, use the In and Out buttons to isolate the data, and then click “Prune” to delete
these unwanted scene cuts.
9 If there’s a gap between any two scene cuts that you’re positive should have another scene cut,
then scrub the playhead or use the transport controls to find the missing cut, and click the “Add”
button at the bottom left corner of the Scene Detect window to add another scene cut.
```
TIP: Adjacent shots with very similar ranges of color and contrast may sometimes go
```
undetected by the scene detection algorithm. If you know of scenes in the media you’re
analyzing that are like this, you may want to scrub through them a bit more carefully to make
sure you’re not missing anything. However, if you find you’ve missed a cut later, you can
always use the Split Clip control in the Edit page timeline to add a new edit point.
10 When you’re confident that the Cut List is accurate, split the media file into individual clips in the
Media Pool by clicking “Add Cuts to Media Pool.”
11 When the Conform Settings dialog appears, click OK if you checked your settings in step 2.
12 Close the Scene Detect window.
The individually cut up clips of the media file you analyzed now appear in the Media Pool, and you can
edit the entire sequence of clips into a new Timeline in order, ready for grading.
464Ingest and Organize Media | Chapter 23 Using Scene Detection
MEDIA
Chapter 24
Ingesting From Tape
DaVinci Resolve is capable of capturing media from tape using a compatible video
input device, such as a Blackmagic Design UltraStudio or DeckLink card. Device
control is supported.
Contents
Tape Ingest  466
The Tape Capture Interface  466
Setting Up to Capture From Tape  467
Deck Settings 467
Capture  468
The Three Methods of Capture  469
Using Capture Now  469
Logging and Capturing Individual Clips  469
Logging and Capturing Multiple Clips  470
Batch Capture Via EDL  471
465Ingest and Organize Media | Chapter 24 Ingesting From Tape
MEDIA
Tape Ingest
This chapter covers how to capture media from tape directly into the Media Pool in DaVinci Resolve.
Whether you need to capture a handful of clips to incorporate into an existing project, or you need to
recapture every clip corresponding to the events of an EDL, you can use the Media page in Capture
mode to capture from any device-controllable deck via a compatible video interface.
To switch to tape capture in the Media page:
 Click the Capture button, located to the left of the Interface toolbar at the top of the Media page.
The Media page updates to reflect the relevant controls for editing to tape, and the Audio panel is
replaced by a dedicated set of capture metadata and controls to help you track the resulting clips.
The Tape Capture Interface
While in Capture mode, the Media page is used to control the VTR, in order to establish In and Out
points for logging or capturing a selected range of the tape.
Tape Capture viewer in the Media page
 Transport controls: The transport controls, while similar in appearance to those used when simply
playing through selected clips in the Media page, now work to control the VTR.
 Shuttle control: A shuttle control appears in what was formerly the scrubber bar, which lets you
shuttle through the range of reverse and forward speeds compatible with the connected deck.
 In and Out controls: In Capture mode, the In and Out buttons to the right of the transport controls
define a range of the tape from which to capture.
 Capture panel: The panel automatically switches to the Capture panel, with tape-specific
metadata and capture controls. Populating File Name Prefix updates the file name preview that’s
shown above in the Header, that also shows the Capture directory, Resolution, and Frame Rate
specified in the Capture and Playback panel of the Project Settings.
466Ingest and Organize Media | Chapter 24 Ingesting From Tape
MEDIA
Editable capture metadata
Setting Up to Capture From Tape
Before you begin capturing from tape, you need to adjust a variety of settings in the Capture and
Playback panel of the Project Settings. Two groups of settings, in particular, need to be defined.
Deck Settings
These settings affect both capture and playback when using the Tape Ingest options of the
Media page, or the Tape Output options of the Deliver page.
```
 Video capture and playback: You can choose the video format (frame size and frame rate) with
```
which to output to tape from this drop-down menu. HD timelines can be downconverted to SD,
and SD timelines can be upconverted to HD using the format conversion of your DeckLink card.
 Use left and right eye SDI: A checkbox that enables the Blackmagic Design DeckLink HD
Extreme 3D+ to ingest and output muxed stereoscopic video when used with supported VTRs,
```
such as HDCAM SR decks with 4:2:2 x 2 mode. (When muxed stereoscopic signals are ingested,
```
```
each eye is separated into individual left-eye and right-eye image files.)
```
 Video connection operates as: Selects between the available signal options: Use 4:4:4 SDI
and Enable Single Link. Which options are available depend on which video capture card
you are using.
```
 Data Levels: Lets you specify the data range (normally scaled or full range) that’s used when
```
ingesting from or outputting to tape. This option switches the data range of the signal output by
your video capture card, but only during capture from tape in the Media page, or output to tape in
467Ingest and Organize Media | Chapter 24 Ingesting From Tape
MEDIA
the Deliver page. When capture or output is not currently occurring, your video capture card goes
back to using the identically named data range setting in the Master Settings panel of the Project
Settings pane, which governs how you monitor the signal being output on an external broadcast
display or projector.
 Video bit depth: 10-bit is the only available option.
 Use deck autoedit: If supported by your video deck, this is the best method to record video
to the deck, as it enables the deck to roll the edit using the specified preroll, and control the
edits via serial device control. If this checkbox is turned off, a basic edit On/Off mode is used
by the deck, with the potential for frame inaccuracies if the “Non auto edit timing” setting is not
properly adjusted.
 Non auto edit timing: Adjusts the edit synchronization of the connected deck when auto edit is
turned off.
 Deck preroll: Sets the number of seconds for preroll. How much is appropriate depends on the
performance of your deck.
 Video output sync source: When using a DeckLink card this is set to Auto. Other capture cards
may require you to set the sync source to “Reference” for playout and “Input” for ingest. This
setting is only available if you have the DVS card installed on your system.
 Add 3:2 pulldown: Inserts or removes the 3:2 pulldown required to record or play 23.98 fps media
to or from a 29.97 tape format.
Capture
These settings are used when you use the Capture mode in the Media page to capture clips from tape
into the Media Pool, or when controlling the Cintel Film Scanner to scan film of different formats.
 Capture: Lets you choose whether to capture both Video and Audio, or Video only.
 Video Format: The format captured media will be saved to. When capturing from tape, the
available options are DPX and QuickTime.
 Codec: The codec used to write captured media. When capturing from tape, these include the
various type of Apple ProRes, 8- and 10-bit YUV 422, 10-bit RGB, and the various types of DNxHD.
 Save clips to: A field that displays the directory path to which media files captured from tape
are written. You want to choose a volume that’s fast enough to accommodate the data rate of the
media format you’re capturing.
```
Browse: Click this button to choose a directory to write captured media to. The directory you
```
choose appears in the field above.
 Save in this folder path: A series of checkboxes lets you specify what other information to use to
define the directory hierarchy that will hold the captured media. Every checkbox you turn on adds
an additional directory with a name defined by that checkbox’s metadata. You can choose any or
all of the following: Program name, Clip number, Reel number, Roll/Card.
 Apply reel number to: Lets you choose how to write the reel name. Two checkboxes let you write
the reel name to the file’s name, and/or to the Header data.
 Use prefix: A field lets you type in a prefix to be used in the media file’s name. This lets you add
text identification that will make the media more easily identifiable and searchable.
 Apply prefix to: Two checkboxes let you choose to use the prefix you typed in the file name, and/
or in the folder name.
 Use frame number with: When capturing to image sequences, you can choose how many digits to
use when writing the frame number into the name of each frame file.
 Set batch ingest handles to: Lets you add additional frames of handles to the beginning and end
of each scanned clip when batch capturing with the scanner.
 Input: A drop-down that lets you choose how many tracks of audio to capture, from 2 to 16.
468Ingest and Organize Media | Chapter 24 Ingesting From Tape
MEDIA
The Three Methods of Capture
Once you’ve set up all relevant settings in the Project Settings window, including at minimum “Video
Capture and Playback,” “Capture Clips Saved to,” and Apply Reel Name to” settings, then you’re ready
to start capturing. Depending on your workflow, there are three methods of capturing from tape that
you can use.
For all capture methods, media can be ingested as QuickTime Movies or DPX image sequences.
Using Capture Now
If you simply need to capture a section of tape quickly, you can use the Capture Now command.
To Capture Now:
1 Use the transport controls and the In button to identify what you want to capture.
2 Enter all relevant information into the various fields of the Metadata Editor. The Header updates to
show a preview of the file name that will be saved.
3 Use the transport controls to start playback, and then click the Capture Now button at the bottom
of the Metadata Editor.
4 When the section of tape you wanted to record has finished, click Capture Now again to
stop capture.
A new clip appears in the Media Pool, automatically placed in a new folder in the Media Pool with a
name defined by the timecode value converted into a frame count, based on the ingest frame rate.
For example, 00086400.dpx is the file name of a clip captured at timecode 01:00:00:00.
Logging and Capturing Individual Clips
If you’re capturing an exact range of tape, or multiple sections at once, you can also work by logging
each section of tape you want to capture in advance, before using the Capture Clip or Batch Clips
commands in a second step.
To capture a single clip using device control:
1 Use the transport controls to find the beginning of the section of tape you want to record, and
click the In button. Then, find the end of the section of tape you want to record, and press the
Out button.
2 Enter all relevant information into the various fields of the Metadata Editor. The Header updates to
show a preview of the file name that will be saved.
3 When you’re finished, click Capture Clip.
Deck control is automatically used to play through the specified range of tape and capture that clip.
When capture is complete, the new clip appears in the Media Pool.
469Ingest and Organize Media | Chapter 24 Ingesting From Tape
MEDIA
Logging and Capturing Multiple Clips
For efficiency’s sake, you can also log multiple clips at once, from multiple tapes if necessary, and then
batch capture them all at once.
To log one or more clips:
1 Use the transport controls to find the beginning of the section of tape you want to record, and
click the In button. Then, find the end of the section of tape you want to record, and press the
Out button.
2 Enter all relevant information into the various fields of the Metadata Editor. The Header updates to
show a preview of the file name that will be saved.
3 When you’re finished, click Log Clip.
That clip is added to the Media Pool as an offline tape clip, indicated by a black icon with a
tape badge.
Logged clip in the Media Pool prior to capture
To batch capture one or more logged clips:
```
1 (Optional) Put the Media Pool into List view, and click the Reel No column header to sort the
```
Media Pool clips by reel number. This makes it easier to select a range of clips to capture from a
particular reel.
2 Select one or more offline tape clips in the Media Pool that come from a particular reel.
3 Click Batch Clips, at the bottom of the Metadata Editor. To interrupt capture at any time,
click Batch Clips again.
Deck control is automatically used to play through the current tape in the VTR and capture every
logged clip you’ve selected that can be found on that tape, starting with the clip with the lowest
timecode value and ending with the clip having the highest timecode value. A progress bar
with accompanying text shows how much longer to go until capture is complete. As each clip is
captured, its corresponding logged clip in the Media Pool updates with a thumbnail reflecting the
captured media.
When DaVinci Resolve finishes capturing all clips from a particular reel, Batch Capture stops.
470Ingest and Organize Media | Chapter 24 Ingesting From Tape
MEDIA
Batch Capture Via EDL
You can also use an EDL to create offline tape clips, one for each event in the EDL, with which to batch
capture all the media necessary to conform a project from tape.
To import an EDL as a batch capture list:
1 Open the Project Settings, click Master Panel in the sidebar, and make sure of the following:
 Set “Timeline frame rate” to the frame rate of your EDL.
 Turn on “Use drop frame timecode” if your EDL requires it.
 Make sure “Use Timecode” is set to “Embedded in the source clip.”
 Turn on “Assist using reel names from the.”
2 Choose File > Import Batch List From EDL.
3 When a Conform Settings dialog appears asking you to confirm the current Project Settings, click
OK if the settings are good.
4 Use the controls of the Select EDL files dialog to select one or more EDLs, then click Open. If you
select multiple EDLs, then every event in each EDL is imported at once.
5 In the dialog that appears next, choose a frame rate to conform the EDL at, and click OK.
Each event in the EDL now appears as offline tape clips in the Media Pool, ready for capturing.
If you load an EDL and there are already clips in the Media Pool that have the same reel name
and start timecode as events in the EDL, DaVinci Resolve will not create new offline tape clips
for those.
A set of logged clips imported from an EDL
```
6 (Optional) Put the Media Pool into List view, and click the Reel No column header to sort the
```
Media Pool clips by reel number. This makes it easier to select a range of clips to capture from a
particular reel.
```
7 (Optional) If there are any offline clips that you don’t need to capture, you can remove them from
```
the Media Pool by right-clicking them and choosing Remove Selected Clips.
471Ingest and Organize Media | Chapter 24 Ingesting From Tape
MEDIA
8 Select which of the offline tape clips you want to capture. It’s best to select ranges of clips that
come from the same reel.
9 Click the Capture mode button to the left of the transport controls, and then click Batch Clips
to begin capture. To interrupt capture at any time, click Batch Clips again. Deck control is
automatically used to play through the current tape in the VTR and capture every logged
clip you’ve selected that can be found on that tape, starting with the clip with the lowest
timecode value and ending with the clip having the highest timecode value. A progress bar
with accompanying text shows how much longer to go until capture is complete. As each clip is
captured, its corresponding logged clip in the Media Pool updates with a thumbnail reflecting the
captured media.
When DaVinci Resolve finishes capturing all clips from a particular reel, Batch Capture stops.
472Ingest and Organize Media | Chapter 24 Ingesting From Tape
MEDIA
Chapter 25
Capturing From the
Cintel Film Scanner
This chapter details how to ingest scanned film using DaVinci Resolve settings and
workflows to control the Cintel film scanner.
Contents
Controlling the Cintel Film Scanner 474
The Cintel Scanner Interface 475
Film Controls  475
Film Scanning Workflows  485
Adjusting the Color of the Scanner 489
Scanning One or More Sections of Film  489
Extracting Audio  490
Audio Extraction Settings  491
Color Space and Sizing  494
473Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
Controlling the Cintel Film Scanner
The Blackmagic Cintel film scanner is a compact, easy to use, real time film scanner capable of
```
converting 35mm, 16mm, and 8mm (with separately purchased gates) positive and negative film
```
```
formats into Cintel Raw Image (CRI) digital files that can be organized, edited, and graded using
```
DaVinci Resolve, delivered to any format DaVinci Resolve can output, and archived for later use.
The Cintel scanner
DaVinci Resolve can control any Blackmagic Cintel film scanner that’s connected to your computer
via Thunderbolt or PCIe. Once connected, the Film Scanner controls in the Media page can be
enabled, which let you choose the film type to be scanned, align the film frames to the sensor, adjust
the scanner’s light source for optimal exposure and color, and choose whether to use the scanner’s
hardware-based Automatic Perf Detection to perform image stabilization.
```
NOTE: This chapter of the DaVinci Resolve manual describes the use of a Cintel film
```
scanner connected to DaVinci Resolve for the purpose of ingesting scanned film. For other
operational inquiries, please see the documentation that accompanies the scanner itself, or
visit the Blackmagic Design support page on the web to download it.
This section of the manual shows you how to use settings and features in DaVinci Resolve’s film
scanner panel to control your scanner. For example calibrating your scanner, adjusting the light source
strength and color temperature, setting image stabilization, and more. You can even set how gentle
your Cintel scanner handles film which may have become delicate with age.
```
TIP: DaVinci Resolve saves all scanner settings in your current project.
```
474Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
The Cintel Scanner Interface
Click on the ‘capture’ button in the UI toolbar at the top of the DaVinci Resolve screen to set the media
page to control your Cintel scanner. Open DaVinci Resolve’s film scanner panel to set up, calibrate,
and choose options for logging or scanning a selected range of the currently spooled roll of film. If you
want more room for viewing the Cintel scanner controls, click the full height button that’s all the way to
the right of the UI toolbar, and turn off the ‘metadata’ panel.
Cintel scanner controls in the Media page
Transport Controls: The transport controls under the viewer, while similar in appearance
to those used while in playback mode, now work to control the Cintel scanner. Additional
controls appear for moving forward or backward a frame at a time.
In and Out Controls: In Cintel Scanner mode, the In and Out buttons to the right of the
transport controls define a range of the film roll from which to capture.
The following groups of settings appear to the right of the Media page viewer when in Cintel Scanner
mode to scan clips from film into the Media Pool.
Film Controls
The film controls provide options to calibrate the scanner’s optics, select the film type, adjust the
frame alignment, scan speed and spool wind direction, choose the reel type, and turn the focus assist
feature on or off.
Calibration
This option lets you calibrate the optics of the scanner to eliminate optical blemishes or dust that
cannot be removed. Please note that this feature does not remove dust from the film itself.
475Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
The calibration button can be used to help remove dust or
small blemishes from the optics of your Cintel scanner.
While it’s recommended to “spray dust” the optics before scanning new material, it’s possible over
time for some blemishes on the optics to be unremovable, in which case using the calibrate button will
eliminate them from the scanned image.
Calibrate the optics with the skid plate installed and correctly aligned, as this assists with image
stabilization and offers the best image quality.
To support small gauge film types, the calibration button also analyzes the gate fitted and adjusts the
captured image to a datum reference. To permit this, the calibration process should be run on every
gate swap with no film in the gate to ensure optimum performance.
If you are using the 8mm HDR gate or 16mm HDR Gate and have adjusted the aperture shutters to
switch to a different film gauge, you will need to repeat the calibration process to avoid a ‘ghost image’
of the previous calibration.
Incorrect calibration shows Super 8mm film
with a Standard 8mm calibration
Incorrect calibration shows Standard 8mm film
with a Super 8mm calibration
Correct calibration of Standard 8mm film
476Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
Incorrect Incorrect
Super 16mm poss correct Standard 16mm neg correct
Film Type controls in the Media page
Film Type
Lets you choose what type of film you’re scanning. For color as well as black and white film, the
choices are positive, negative, interpositive, and internegative. HDR scanning offers an improvement
for all these film types. Select the film type you’re scanning from 35mm 2, 3, and 4 perf, 16mm, Super
8mm, and 8mm. The scanner automatically detects whether the film is 35mm, 16mm, or 8mm. For 8mm
scanning, the default is set to Super 8mm. When scanning regular 8mm, you will need to manually set
your scanner for that specific film type.
477Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
When scanning interpositive and internegative film on Cintel Scanner and Cintel Scanner G2, the
increased density of the film requires slightly extended pulse durations from the light source. Normally,
this does not affect the scan, however, a slight reduction in resolution may occur when scanning at
above 12 frames per second. If you do notice a difference in resolution, simply reduce your scanning
speed to 12 frames per second or less.
 Enable 2 Pass HDR Scan: Enables high dynamic range multi pass capture. It is important to
perform an ‘auto black’ or ‘auto white’ on a frame with a wide dynamic range as it determines the
high and normal exposure levels from your selected frame.
 Perf nudge: Used for making fine adjustments of the perf position relative to the scanner gate
aperture. Command-J nudges up, while Command-L nudges down.
 Frame: These buttons are push and hold to activate. When on, the film is slowly advanced to move
the frame up or down and when released the film stops in place. This is useful for aligning the film
frame with the scanner’s sensor. Using the ‘perf nudge’ and ‘frame’ buttons, you want to align the
visible film frame so the bottom of the previous frame and the top of the next frame are just visible
at the top and bottom of the viewer, and the current frame is centered vertically.
 It’s important to make sure the image in the viewer is not zoomed in when you do this.
Command-Left Arrow on your keyboard moves the frame up, while Command-Right Arrow moves
the frame down.
 Scan Speed: With adequate disk performance, you should be able to scan at 30 fps. However,
if you’re scanning to a slow hard drive, you can reduce the scanning speed to a frame rate that’s
suitable for your workstation without dropping frames.
 Supply: Sets the wind direction of the left-hand side feed spool. While auto-detection will prevent
incorrect operation, you should manually configure the reel winding direction based on how each
film roll is wound.
 Take up: Sets the wind direction of the right-hand side take up spool. While auto-detection will
prevent incorrect operation, you should manually configure the reel winding direction based on
how each film roll is wound.
 Use Film Reel: Small film reels have a different weight and inertia compared to large film spools,
and this can affect the transport system. Tick this box to switch to settings that offer improved
stability for small film reels.
 Focus Assist: Enables luminance peaking on your scanner’s HDMI monitor output, plus the
viewer inside DaVinci Resolve’s film scanner panel, which makes it easy to obtain optimum
focus adjustments.
Light Source controls in the Media page showing the default uncalibrated status of
```
the light source (left), and the status when calibration is successful (right)
```
478Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
Adjusting the Light Source
These controls let you adjust your Cintel Scanner’s light source to calibrate the optimal Dmin density
minimum. The Dmin density minimum is the minimum scanned value, plus the color temperature of the
scanned material. Adjusting the light source settings correctly will ensure the best quality scans and
make sure you are not clipping image data during the scanning process. It’s a good idea to check your
light source settings when changing film to ensure the quality of your capture.
Use the built in software scopes in DaVinci Resolve to help you set your light source to its optimal level
settings. The scopes can be opened in the Media page by choosing Workspace > Video Scopes > On.
 Light Source master wheel: The vertical light source master wheel is located next to the color
wheel and adjusts the intensity of the light source used to illuminate the film, raising or lowering
the RGB channels all at once. For typical negative film, this lets you adjust the black point of the
film image, which is the darkest part of the image. In negative film, this in fact corresponds to the
highlights of the film image. Adjust the light intensity to sit just above the typical Dmin value of 95,
as measured on the histogram of the video scopes, which guarantees that the highlights won’t be
clipped by a Cineon-style LOG conversion. For positive film, simply adjust the master wheel so
that no part of the signal is being clipped.
 Auto Black and Auto White button: Analyzes the current frame displayed in the Viewer and does
an automatic adjustment to set the black point for negative and internegative using the framing
bar area. For print and interpositive film it uses the brightest highlight in the image area to set the
white point, so key selection of the frame is important. Alternatively, for positive film types you
can use a punch hole frame for maximum white to ensure all subsequent frames are compliant.
For positive film types, the ‘auto black’ button changes to ‘auto white’.
Light Source Status Indicators
These indicators under the ‘auto’ button let you know if the auto black or auto white light source
calibration has been successful or if there are items to address. They also provide a helpful reminder
to recalibrate the LED light source to ensure the highest quality scans.
Light source
calibration has not
yet been performed.
Light source calibration
has performed
successfully.
Light source calibration
failed. Verify you have
the correct film type
selected, the light path
is not obstructed and a
suitable reference frame
is selected. If required,
try advancing film and
selecting an alternate
reference frame.
Light source calibration
has successfully
balanced colours but
not at desired levels.
As a solution, you can
accept the balanced scan
and optimize the image
in DaVinci Resolve’s
color page or select an
alternate reference frame
for calibration with a
wider dynamic range.
Light Source Status Indicators
These indicators under the ‘auto’ button let you know if the auto black or auto white light source
calibration has been successful or if there are items to address. They also provide a helpful reminder
to recalibrate the LED light source to ensure the highest quality scans.
 RGB controls: By default, a color balance control lets you adjust all three color channels by
varying amounts to alter the color temperature of the light source used to illuminate the film,
479Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
while the adjusted R, G, and B values are displayed in three fields below. Optionally, you can
choose to put this control into ‘color bars’ mode using the mode pop-up to the right of the ‘light
source’ title bar, which changes this control to three vertical red, green, and blue color channel
sliders.Image Stabilization
```
NOTE: The light source calibration is saved when you change rolls. This allows you to
```
scan multiple rolls with a single light source calibration in both SDR and HDR modes. The
last light source calibration will be saved until a new calibration is performed, or until your
Cintel scanner is power cycled.
These controls let you enable and disable as well as control image stabilization to eliminate
vertical film hop and horizontal weave
Image Stabilization controls in the Media page
 Image Stabilization enable/disable control: The dot to the left of the ‘image stabilization’ title
bar lets you enable or disable your scanner’s hardware-based image stabilization altogether.
While hardware stabilization is typically desirable when you have high quality perforations, you
may want to turn this option off if the condition of the perforations is poor and you decide to use
DaVinci’s software based stabilization instead.
When image stabilization is enabled, a horizontal X axis detection overlay is displayed in the
viewer, highlighting the edge of the film perforation that will be used as the reference for
stabilization. This overlay is automatically hidden when recording. Image stabilization is enabled
by default.
 Enable X and Y checkboxes: Enable X and enable Y lets you choose whether to use hardware
image stabilization to fix horizontal gate weave and vertical gate hop respectively. If the results
are unsatisfactory with both axes enabled, you can turn off the axis that’s causing issues with
stabilization and utilize DaVinci Resolve’s software-based stabilization tools instead.
 Horizontal Position slider: Your Cintel scanner attempts to automatically place the stabilization
detection overlay at the best location, with reference to the perforation shown on the currently
loaded frame, for the best stabilization result.
You will notice a thin transparent line in the blue alignment overlay. For optimum stabilization, this line
should touch the edge of the perforation. If the automatic positioning is not ideal, you can manually
move the overlay to a more ideal position, either by dragging it in the viewer with your mouse, or by
using the horizontal slider.
Ideal placement of the stabilization overlay should position the clear line in the alignment overlay on
the edge of the perforation, as shown in the example image. With the overlay correctly positioned, this
enables hardware stabilization of gate weave along the X axis.
Image stabilization automatically manages vertical gate hop when you select the ‘enable y’ checkbox.
It needs no further adjustment and works in conjunction with horizontal stabilization.
480Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
Incorrect 35mm setup.
Adjusting the horizontal position of the
stabilization overlay. The overlay is not
aligned to the edge of the perforation.
Correct 35mm setup.
The hardware stabilization control correctly
positioned over a perforation in the viewer.
The transparent stripe in the stabilization
overlay touches the edge of the perforation.
Incorrect 16mm perf setup.
The overlay is not aligned to the edge of the perforation.
With the 16mm HDR skid plate installed, the stabilizer
aligns automatically to the other side of the perforation
to avoid interfering with the film image and improve
horizontal stability. When using a ‘non-HDR’ 16mm skid
plate, it functions the same as the 35mm skid plate.
Correct 16mm perf setup.
For the stabilization overlay, the default alignment
position is for the left edge of the perforation
as this is not affected by image content.
The transparent stripe in the stabilization overlay
touches the edge of the perforation correctly.
Incorrect 16mm film edge setup.
The overlay is not aligned to the
edge of the film reference edge.
Correct 16mm film edge setup.
The overlay is aligned to the edge of the
film reference edge. The transparent overlay
touches the film ref edge correctly.
481Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
Incorrect 8mm setup.
The overlay is not aligned
to the edge of the film.
Correct 8mm setup.
For the stabilization overlay, the transparent stripe
in the overlay is within the film base area.
Incorrect 8mm perf setup.
The overlay is not aligned
to the edge of the perforation.
Correct 8mm perf setup.
For the stabilization overlay, the default alignment
position is for the left edge of the perforation
as this is not affected by image content.
The transparent stripe in the stabilization overlay
touches the edge of the perforation correctly.
Incorrect 8mm film edge setup.
The overlay is not aligned to the edge of the
film reference edge. The overlay is not aligned
to the edge of the film reference edge.
Correct 8mm film edge setup.
The overlay is aligned to the edge of the
film reference edge. The transparent overlay
touches the film ref edge correctly.
To closely check the results of your stabilization settings before capturing, set the Viewer to full
resolution and zoom into the perforation region to allow fine adjustment. Simply click on the options
settings at the top right corner of the Viewer and select ‘full resolution preview’ from the menu,
482Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
click on the zoom scalar at the top left-hand corner of the Viewer and select ‘100%’. This setting does
not affect the stabilization feature but enables the best possible preview so you can monitor how
well it is performing.
Full resolution preview is very GPU intensive and may result in some frame lag. For best performance,
turn full resolution off after checking stabilization. It is worth mentioning that the overlay position
will be saved within the project settings and not the clip settings, therefore may require individual
adjustment for multiple rolls.
Resetting the detection overlay to its default position for a given film type can be achieved via the
Stabilization pane Reset button.
Audio and Synchronization
The Audio and Synchronization palette contains settings for the optional Cintel Audio and KeyKode
Reader. Refer to the ‘optional Audio and KeyKode Reader’ section of the Blackmagic Cintel manual for
more information.
Film Protection
These controls are intended to allow delicate film to be handled gently by the Cintel Scanner. Fast
acceleration and shuttle speeds can be hard on archival footage, so it’s recommended to lower both
of these sliders from their defaults whenever you’re scanning older film.
The ‘Acceleration’ and ‘Shuttle Speed’ sliders should be
lowered when scanning older, delicate archival film.
```
NOTE: The ‘Film Tension Adjust’ slider is present when using Cintel scanners with sprockets.
```
 Max Acceleration: Sets the maximum change in speed to increase or decrease by
5-30 fps per second.
 Max Shuttle Speed: Changes the speed of shuttling from one section of film to another between
1–100 frames per second for 35mm film, and between 1–200 frames per second for 16mm film.
 Film Tension Adjust: If your Cintel Scanner has sprocket wheels, this setting gives you the ability
to adjust the amount of tension applied to 35mm film. For example, when loading delicate archival
film, or compensating for film shrinkage. There is no possible way you can damage the film with
the ‘film tension adjust’ setting. The adjustment values are very small and only gentle changes are
all that’s required to prevent sprocket picking.
If your Cintel Scanner has capstans, sprocket picking cannot occur, so this setting is disabled or
not present.
483Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
Editing Capture Info Metadata
When DaVinci Resolve is used in conjunction with Cintel Scanner, a set of capture metadata fields
appears at the bottom of DaVinci Resolve’s film scanner panel. The ‘capture info’ panel has editable
metadata fields that describe capture properties such as where to save files, the type of codec, frame
rate, and the format of file names. This metadata is attached to your clips and can be read on the
media page.
Before you begin scanning, you may want to adjust some of the project settings.
The ‘capture info’ panel lets you specify
metadata for your scanned clips.
 Capture Location: Before you begin a film scanning session, scroll down to the ‘capture info’
section of DaVinci Resolve’s film scanner panel to make sure the scanned files are being saved to
the directory and volume where you want them. Click the ‘browse’ button and choose a location
from the file destination dialog. It’s good to do this first, as this step is easy to forget.
 Capture: When you have a Cintel Audio and KeyKode Reader fitted, this menu gives you options
for ‘audio only’ so no images will be captured, or ‘image and sound’. Alternatively, you can capture
‘image only’ if audio is not important.
 Resolution: The resolution of the capture files depends on the source film format so this field
cannot be edited.
 Codec: DaVinci Resolve selects the ‘Cintel Raw’ codec for lossless compression by default, or you
can choose ‘Cintel Raw 3:1’ for even smaller file sizes.
484Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
 Film Frame Rate: Specify the frame rate that the film was originally shot at. DaVinci Resolve
automatically adjusts the timeline frame rate based on this value. This setting is unrelated to
capture or transport speeds.
When using the optional Audio and KeyKode Reader accessory to scan audio, the reader will
automatically adjust for frame rate to maintain an overall sample rate of 48kHz. Timecode output is
supported for 16, 24, 25, and 30 fps, and for other frame rates no timecode signal is outputted.
 File Name Prefix: Prefix to help identify the scan. This can be the name of your project, such as
the title of the film you are scanning.
 Timestamp Prefix: Select this checkbox to prefix your scans with a timestamp as well as the ‘file
name prefix’ you specified. Your clips will be saved to independent sub-folders in the destination
folder. This checkbox is selected by default.
If you want to save all your clips together in one master destination folder without the timecode in
the file name, simply deselect the checkbox.
```
NOTE: If you don’t make capture names unique with the timestamp prefix and the files go
```
into the same location, this could potentially overwrite files.
 Roll/Card, Reel Number, Clip Number, and Program Name: These are ways to identify the clip
with metadata.
 Flags: You can use these color coded flags to tag clips.
 Good Take: Corresponds to ‘circled take’ metadata in the media pool.
 Log Clip: Adds a clip to the media pool. After you mark ‘in’ and ‘out’ points for a section you want
to scan, confirm the metadata is correct, and then click ‘log clip’. For more information, refer to the
‘Logging and Capturing Individual Clips’ and ‘Logging and Capturing Multiple Clips’ sections in the
DaVinci Resolve manual.
 Batch Clip, Capture Clip, Capture Now, and Snapshot: These scanning buttons offer different
methods to capture clips. For more information about scanning buttons, refer to the ‘Scanning One
or More Sections of Film’ section of this manual.
Film Scanning Workflows
The following sections describe how to scan film using DaVinci Resolve and to control the
Cintel scanner. Throughout, the features outlined in the previous section are presented in
the order in which you’ll perform each step of the scanning process.
Before You Begin
Before turning your scanner on and loading film, you should first dust the gate to make sure your scans
are as clean as possible. This can be accomplished using compressed air, but if the gate is extremely
dirty, you can remove it to give it a more thorough cleaning. Once that’s finished, turn on the Cintel
Scanner, open DaVinci Resolve and create the project you’ll be using to scan film, and then click the
‘Cintel scan’ button on the media page. Now click the ‘Film Scanner’ tab to select DaVinci Resolve’s
film scanner panel.
Before you load film into the scanner or do anything else, click the ‘calibrate’ button at the bottom
left of the film scanner panel. While you should always dust the gate of the scanner before loading a
new reel of film, clicking the calibrate button eliminates any unremovable blemishes in your scanner’s
optics from the scans you’re about to make.
485Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
Load and Align the Film
Load the film you want to scan. In the presence of an image the scanner will automatically align a
frame. You should note that the image may be framed incorrectly if you first load blank film leader.
Next, choose the film type. If necessary, use the ‘perf nudge’ and ‘frame’ buttons to manually improve
the alignment of the framing bar to the scanner’s sensor such that the bottom of the previous frame
and the top of the next frame are just visible at the top and bottom of the viewer, and the current
frame is centered vertically. It’s important to make sure the image in the viewer is not zoomed in when
you do this.
Focus the Scanner
Just as you need to focus the lens on a camera, you’ll need to focus the projected film image on your
scanner’s sensor. To achieve perfect focus, turn on the Focus Assist checkbox in the Film Scanner
capture settings of DaVinci Resolve. This superimposes a focus peaking overlay over the Ultra HD
image that’s output from the scanner’s HDMI output, and is also displayed in DaVinci Resolve’s capture
window. For the best results, connect an Ultra HD display to your Cintel scanner so that you can
monitor at the maximum available resolution while you focus.
With Focus Assist turned on, focus peaking will detect the film grain of the scanned image whenever
the film plane is in perfect focus. This enables the operator to focus the scanner even if the film image
is out of focus. Simply monitor the Ultra HD output of the scanner while you turn the Cintel scanner’s
focus wheel. Your image will be in focus when the grain running throughout the image displays
peaking outlines.
You can verify the focal adjustments you’ve made by checking the edges of your film’s perforations.
When these are sharp, your film will be in focus.
Reset the Timecode
To set the timecode for the roll of film you’re about to scan, you need to locate the zero frame for
that roll. It’s standard practice to punch a small physical hole within the frame before the first frame
of necessary film on a roll, to use as a permanent reference for whenever that roll is scanned. This
is referred to as the marker frame, lab roll hole, or head punch. By always setting the first frame
of timecode to match the marker frame, subsequent film scans will have the same frame count as
previous scans, making it possible to rescan and reconform the same material whenever necessary.
To reset scanned timecode at the marker frame of a new film roll:
1 Use the transport controls under the viewer to locate the marker frame.
2 Click the ‘viewer’ option menu and choose ‘current frame timecode.’
Choosing Current Frame Timecode from the Viewer Option menu
3 Enter a timecode value in the dialog box that appears. For example, if you’re scanning the first
roll of a project, you can enter 01:00:00:00.
486Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
The Set Current Frame Timecode dialog
4 When you’re done, click OK.
Timecode cannot be a negative value, so don’t set the start frame to zero. Another common
organizational technique is to change the hour number whenever you change rolls, to coincide with
the film roll’s number, which makes it easy to identify a scanned clip with the corresponding source roll
and frame range.
Your Cintel Scanner has built in ‘Options Interface’ ports for adding optional hardware in the future.
This offers the ability to add optional features such as reading KeyKode from the camera negative, or
optical/magnetic audio. For more information, see the ‘Optional Audio and KeyKode Reader’ section in
the Blackmagic Cintel manual.
Choose a Location to Save the Scanned Frames
Once all this is done, scroll down to the ‘capture info’ controls in DaVinci Resolve’s film scanner panel,
and click the ‘browse’ button to choose a location for the scanned files. You can use the other fields
in this section to set what prefix you want to add to the name of the scanned files and enclosing
folders. The ‘file name prefix’ updates the file name preview that’s shown at the top in the header. The
header also shows the file path, resolution, frame rate, duration, and the format. Specify what roll, reel,
clip, and program information you want associated with the scanned media. The ‘timestamp prefix’
checkbox in the ‘Capture info’ controls is selected by default and will save your clips to independent
sub-folders within the destination folder, together with a timecode prefix in the file name.
If you want to save all your clips together in one master destination folder, simply deselect the checkbox.
When you capture an HDR clip, the scanner completes a high exposure scan and saves it in a hidden
folder named .HDR inside the same folder as the standard scan. If you delete the .HDR folder, the scan
converts to a normal clip after refreshing it in the media storage and re-importing the clip into media
pool. This is useful if there is a problem with the HDR portion of the scan, as you can easily convert it
to a regular CRI clip.
Check the Codec
DaVinci Resolve selects the ‘Cintel Raw’ codec by default, or you can choose ‘Cintel Raw 3:1’.
487Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
The Cintel Raw Format
The Cintel Raw Format Bayer pattern of each film frame scanned with your Cintel scanner’s
sensor is saved with embedded scanner metadata as a 12-bit linear Cintel Raw Image, or CRI,
image sequence. When grading in DaVinci Resolve, CRI images are automatically debayered
as 12-bit log encoded image data.
The logarithmic encoding is similar, but not identical to Cineon encoding. For example,
negative film is encoded using a Gamma of 2.046 for density, while print film is encoded
using a full range Gamma 2.2 curve to ensure that no image data is clipped. Both of these
logarithmic encodings can be converted to a linear color space using the ‘Cintel to Linear’
1D LUT, before converting to other color spaces you may want to work in.
The film is scanned using the full sensor area of 4096x3072 to keep the audio waveform
visible for optical audio and to accommodate perforation visibility for stabilization. The image
is then cropped and the resolution of the capture files depends on the source film format
after overscan for perforations and the audio area are removed. For more information about
scanning resolutions for different types of film, see the ‘specifications’ section.
The Cintel scanner creates Cintel Raw files with variable bitrate lossless compression by
default. This is visually lossless compression and achieves approximately 3:2 reduction in file
size depending on image content. However, Cintel Raw 3:1 uses lossy compression with a ratio
of approximately 3:1. This is still very high quality but may not always be visually lossless.
For example, files for 35mm 4 perf are approximately 12.5MB with Cintel Raw and
approximately 6.3MB with Cintel Raw 3:1. Files for 16mm are approximately 4MB with Cintel
Raw and approximately 2MB with Cintel Raw 3:1.
CinemaDNG Quality Settings
To control the quality of CRI files, use the ‘decode quality’ and ‘play quality’ CinemaDNG settings
located in the Camera Raw panel of the project Settings. These settings are ‘full’ by default. On
computers with low processor or memory resources, these settings may be lowered but this will affect
the quality of the final render.
Set the Timeline Resolution
DaVinci Resolve displays and renders the output from the scanner using the same resolution as the
timeline. For example, for 35mm 4 perforation film, a custom resolution of 4096x3072 would be
required for maximum resolution.
```
NOTE: If your timeline is set for HDR with the desired deliverable at Ultra HD, a loss of
```
resolution may occur.
For more information on the cropped image area resolutions for all film gauges, refer to the ‘effective
resolutions’ in the ‘specifications’ section. Alternatively, for the full native resolution of the captured
clip, access the ‘clips attributes’ in DaVinci Resolve.
488Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
Adjusting the Color of the Scanner
DaVinci Resolve’s film scanner panel gives you control over the exposure and color temperature of the
light used to illuminate the film for scanning. You can adjust these via the light source master wheel
and RGB controls, in order to maximize the amount of information you’re extracting from each frame,
while preventing any part of the image from being irretrievably clipped. While it’s true that CRI is a raw
image format, there’s no latitude beyond the internal data range used by DaVinci, so be mindful that if
you’re clipping data in the built in video scopes while scanning, it might be clipped permanently in the
scanned media.
How often you’ll adjust the color and exposure of scanned shots depends on how much variety there
is in the scenes on a particular film roll. For example, some rolls may have many takes of the same
scene, all of which have the same lighting and which can share the same adjustments.
Meanwhile, other rolls may have a variety of different scenes with widely different lighting in each one,
necessitating you to make individual adjustments for each scanned clip to maximize data quality.
This is important because the light source master wheel and RGB controls cannot be automatically
changed between scanned clips in a log and capture workflow. This means that the current light
source settings will be used for all clips you scan until you manually change those settings again, even
for clips that you’ve logged from different parts of a film roll. This means that the log and capture style
of working is only advisable in situations where it makes sense to log multiple clips that share the
same light source master wheel and RGB control adjustments.
Otherwise, it’s recommended you make lighting adjustments on a clip by clip basis, as you scan each
clip, in situations where you need maximum image quality for finishing. Keep in mind that the goal for
these adjustments is to maximize image data from the scan, not to create the final look of the clips,
which you’ll accomplish later in the grading phase of work using the controls of the ‘color’ page.
To adjust the light source settings, find a typical image for the section of roll or for the first series of
shots you’re going to scan, and adjust the light source while viewing the built in video scopes.
Adjust the light source master wheel to set the intensity of the light source used to illuminate the film,
raising or lowering the level of the R, G, and B channels all at once. For a typical camera negative,
this lets you adjust the black point of the film image. In a negative print, the darkest part of the image
corresponds to the highlights of the film image. Set the light source master wheel to sit just above
the typical Dmin value of 95, as measured on the histogram of the video scopes, which guarantees
that the highlights won’t be clipped by the Cineon LOG conversion that DaVinci uses to debayer the
CRI image for grading. For positive film, manually adjust the light source levels so that no part of the
```
highlights or shadows of the signal is being clipped; typically 1000 in 10-bit or 4000 in 12-bit.
```
You can turn on ‘show reference levels’ in the waveform, RGB parade, or histogram scopes, and set
the ‘low’ value to indicate the digital Dmin value of 95.
Once that’s accomplished, adjust the RGB controls to rebalance all three color channels by varying
amounts to alter the color temperature of the light source used to illuminate the film, to produce the
most useful, or neutral, color balance in the scanned result.
Scanning One or More Sections of Film
After you’ve adjusted the light source, it’s a good idea to stay organized as you scan each clip by
entering all relevant metadata into the metadata editor as you go. The ‘capture info’ group of metadata
fields contains information for defining the file name prefix, roll, reel number, clip number, program
name, flags, and whether a particular take is good. If you populate these fields before scanning a clip,
that metadata will be written into the clip.
At the bottom of the ‘capture info’ panel, you will see four buttons for film scanning.
489Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
With all of this accomplished, you can scan the film in one of four ways:
 Capture Now: Use the capture now button to capture long sections of a reel all at once. Clicking
‘capture now’ begins scanning near the current frame, ending whenever you click ‘stop’.
If ‘Enable 2 Pass HDR Scan’ is selected, click ‘Capture HDR’ after the capture has begun to let
DaVinci Resolve know you’ve reached the end of your desired clip so it can now proceed to capture
the high exposure pass. If you scan the entire reel without clicking ‘Capture HDR’, the scanner
automatically proceeds with the high intensity scan from where you started it until the end of the reel.
 Capture Clip: A more controlled means of scanning specific sections of film. After you’ve used the
transport controls and the In and Out button to define a section of film, clicking ‘capture clip’ scans
that one clip and then stops.
If ‘Enable 2 Pass HDR Scan’ is selected, the high intensity HDR scan uses the same In and Out
points as the initial scan.
 Batch Clips: A way you can log multiple clips in advance of scanning them all at once using the
current light source settings in DaVinci Resolve’s film scanner panel. Log each clip in advance by
setting In and Out points for each section of film you want to scan, and click the ‘log clip’ button
to save that frame range as an unscanned clip in the media pool. When you click ‘batch clips’, all
unscanned clips will be scanned one after the other until the job is complete. You can also select one
or more unscanned clips, and only the selected clips will be scanned. Furthermore, you can import
an EDL that corresponds to a particular film roll, and use the resulting logged clips for scanning.
```
NOTE: When you click the ‘log clip’ button, Cintel Scanner applies the same project
```
settings to all clips in the batch, and uses the newest project settings at the time of
capture. You are advised to confirm the scanner settings before starting the batch
capture.
If ‘Enable 2 Pass HDR Scan’ is selected, the high intensity HDR scan uses the same sets of In and
Out points as the initial batch of scans.
For more information on batch capture workflows, see Chapter 24, “Ingesting From Tape.”
 Snapshot: Capture a single frame with normal exposure and current scanner settings.
Once scanning, if DaVinci Resolve detects that your storage bandwidth is too low to capture at the
selected speed, the scan speed will automatically adjust to ensure the capture is successful. If you
are using the optional Audio and KeyKode Reader accessory, the audio sample rate will also be
adjusted to maintain your chosen audio quality.
Extracting Audio
If the film you’re scanning also contains an optical sound track, you can extract the audio in a separate
step. There is a standard image frame to audio frame offset of 26 frames for 16mm and 21 frames for
35mm that DaVinci automatically aligns when extracting the audio. Select all of the clips that have
an optical sound track, then right-click one of the selected clips and choose ‘extract audio’. Resolve
analyzes the overlapping optical track area of each frame and automatically generates a matching
audio track, synchronized with the scanned image sequence.
Each clip’s audio will be automatically extracted, embedded in the clip and saved to the same
directory the scanned frames have been written to. A small audio icon will appear on the corner of
your clip’s thumbnail so you know there is a corresponding audio file.
490Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
To make extraction easier, you can filter the clips in the media storage by name, resolution, date
modified or by film clips only. Filtering your clips makes it easier for you to find and select exactly what
you need. You can also make a large selection and extract audio from multiple clips at once by right
clicking on your selection and choosing ‘extract audio…’ from the menu. During audio extraction, an
information box indicates the progress. You can click the ‘stop’ button any time to stop the extraction.
You can filter the contents in the media storage to make it easier to manage them.
If the ‘timestamp prefix’ checkbox was deselected in the ‘capture info’ section when your clips
were scanned, and you want to have extracted audio automatically embedded in your clips, always
remember to extract audio from the clips inside the media pool.
Audio Extraction Settings
Normally, once you have selected the film type, the automatic features in DaVinci Resolve will extract
your optical audio perfectly. However, the condition of the optical track can vary with the condition of
the film being loaded and in some instances this can confuse the automation. If this happens, you can
bypass the automatic features and make adjustments manually.
For manual adjustments, simply open the ‘Audio Extraction’ settings window by clicking
on ‘Show Cintel Audio Settings’ in the inspector options near the top right of the viewer.
491Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
Audio extraction settings let you make the following manual adjustments:
The Audio Extraction settings let you
make manual adjustments, if needed.
Show audio scan area
This checkbox turns the audio scan area guides on or off. The guides are displayed as a
box on the side of the frame covering the optical audio scan area and shows what optical
information will be used during extraction. The position of the guides will conform to the
film type you have selected. However, you can change the position manually if you need
to. The audio scan area guides are also great indicators to show you what is happening
during the extraction process so you can identify any potential troubles and make manual
adjustments.
Inside the box is a thin red line. This line is the mid point detector which detects the separation
between stereo audio channels. When mono sound is detected during audio extraction, the
mid point detector disappears and the guides will adjust automatically to suit the width of the
mono optical track.
```
TIP: If you need a closer inspection of the audio scan area guides, you can zoom into the
```
viewer and move the viewer position up or down, and left or right. Simply choose the amount
of zoom from the sizing options at the top left corner of the viewer, then click and drag the
viewer with your mouse or track pad.
492Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
When ‘show audio scan area’ setting is turned on, the audio area guides will be visible so you
can see exactly what information is being used and monitor the extraction process.
Override audio scan area
This setting provides sliders for adjusting the horizontal and vertical positioning, width, and height of
the audio scan area guides.
These settings include:
 Left and Width: If your film type is such that audio appears on the right side of the frame, you
can simply adjust the ‘left’ slider to move the guide box to the right. Normally, this will happen
automatically if you have the corresponding film type selected, but the setting gives you more
flexibility for adjustments if you need it. Similarly, the ‘width’ setting is used to adjust the width of
the scan area.
These are helpful tools for making subtle adjustments to the side edges of the guide box if there
are unwanted elements inside the film’s optical audio area. This can happen due to perforation
wear and tear, or varying print qualities, and can sometimes interfere with the quality of the audio
extraction. You can help avoid this by making a subtle movement to the side edges to keep the
stray elements outside of the guide box.
 Top: This setting adjusts the vertical position of the guide box.
 Height: Sometimes film frames on older rolls of film may be slightly smaller than normal due
to shrinkage over time. When making manual adjustments to the guide box, you can make
adjustments for film shrinkage using the ‘height’ slider.
493Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
 Auto adjust audio scan height: This setting is on by default and automatically adjusts the guide
box height to align with the audio waveform at the top of each frame. The automatic feature works
well for normal audio conditions, however, if during extraction you notice the box moving randomly
and the quality of the extraction is affected, it may be due to similar features in the audio track
overlapping between frames. If this occurs, deselect the checkbox and try the extraction again.
If deselecting the ‘Auto adjust audio scan height’ checkbox, make sure the ‘height’ setting places
the guide box at the optimal position for the frame. Making manual adjustments can help if you
need them, but don’t forget to turn the automatic features back on afterwards!
```
TIP: If deselecting the ‘Auto adjust audio scan height’ checkbox, make sure the ‘height’
```
setting places the guide box at the optimal position for the frame. Making manual
adjustments can help if you need them, but don’t forget to turn the automatic features
back on afterwards!
 Audio waveform color is white: Depending on the scanned film type, the audio waveform may be
black or white. If the waveform is white, make sure the corresponding checkbox is enabled. This
will ensure the white information in the waveform is used during audio extraction. If the waveform
is black and the surrounding audio area is white, disable the checkbox so DaVinci knows to use
the black information in the waveform. Other automatic features, such as mid point and mono
detection, also rely on this setting being set correctly.
 Override firmware stability: In rare instances, the condition of the film may have created large
movements in the frame due to the internal firmware stabilization. This can cause the audio
extraction guide box to misalign with the optical track. If this occurs, enabling ‘override firmware
stability’ lets the audio extraction guide box track the film perforations independently and adjust
its positioning for potentially better results.
 Variable density audio: If your film contains variable density audio, make sure you select the
‘Variable density audio’ checkbox so DaVinci Resolve knows the type of audio to extract. The
default state is set to ‘off’ for variable area audio soundtracks.
If you haven’t used variable density audio before, you can visually identify it as a tight sequence
of shaded lines, similar to a bar code with the lines squeezed closer together. By comparison,
‘variable area’ soundtracks appear as an audio waveform.
Color Space and Sizing
A pair of 1D LUTs, ‘Cintel Negative to Linear,’ and ‘Cintel Print to Linear,’ have been provided to help
you convert scanned media to a color space in which you can do further work. You can apply these
LUTs via a node in the ‘color’ page to convert the original scans to a Linear color space. However, if
you want to convert the image to Rec. 709 or to Cineon for further adjustment, you’ll want to apply a
second LUT in a second node. The default color space for print is a 2.2 gamma standard log curve,
and all others are 2.046 film density log gamma.
In general for negative film, it’s best to “color invert” after the second LUT is applied. Furthermore,
normally some grading is required on the Linear data to remove black offsets, due to Dmin, for proper
conversion into the destination color space. There are a variety of VFX IO LUTs available in the 3D LUT
submenu of each node’s contextual menu that let you convert an image from Linear color space to any
other color space you want to work within.
494Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
```
Using three nodes to convert a film scan using LUTs; node 1 converts from Negative or Print to
```
Linear, node 2 converts from Linear to Rec. 709, and node 3, if required, inverts the color
```
NOTE: Applying a LUT within a node will clip any image data falling below 0 and
```
above 1. To prevent clipping, you can use the Lift/Gamma/Gain controls within any node
with a LUT applied to adjust your image levels prior to the transform applied by the
LUT within that node.
The format of the film you’re scanning and the way the material was originally shot both affect the
framing. You can adjust the final framing of your scanned clip by resizing, zooming, stretching,
panning, tilting, and more. On the ‘Color’ page, open the ‘Sizing’ palette and use the ‘Input Sizing’
mode to create the necessary framing. To save your sizing preferences as a preset, open the
menu, select ‘save as new preset’ and enter a name for your preset.
Once you’ve created an appropriate sizing preset for a given type of media, you can apply that
preset to multiple film scans all at once, in either the Color page or in the Media Pool using the
‘change input sizing preset’ command, found in the contextual menu of selected clips.
For more information on sizing, see Chapter 152, “Sizing and Image Stabilization.”
Creating a sizing preset in the Sizing palette of the Color page
495Ingest and Organize Media | Chapter 25 Capturing From the Cintel Film Scanner
MEDIA
CUT
The Cut Page
CONTENTS
26 Using the Cut Page  497
27 Importing and Organizing Media in the Cut Page  516
28 Fast Editing in the Cut Page  542
29 Trimming in the Cut Page  578
30 Using the Inspector in the Cut Page 597
31 Video and Audio Effects in the Cut Page  619
32 Quick Export  650
Chapter 26
Using the Cut Page
The Cut page is a focused environment for fast editing. It’s useful in situations where you need
to quickly cut a news segment, build an episode of web content, edit a straightforward program,
experiment with multiple arrangements of a scene, or put together a first assembly edit.
The Cut page is also a good introductory editing interface for people who are new to editing, as it
presents a streamlined set of tools that are fast to learn and simple to use. Whatever your background,
you’ll find the Cut page to be a valuable addition to your editing experience in DaVinci Resolve.
Contents
Overview of the Cut Page  498
Overview of the Cut Page User Interface  498
Customizing the UI  498
Choose Settings Before You Start 499
Timeline Resolution Quick Menu  499
The Media Pool 500
The Viewer  501
Playing Clips and Navigating the Timeline 502
Optimized UI Layouts for Vertical Editing  503
Tools  503
Bypass Color Grades and Fusion  504
Export The Current Frame from The Viewer  504
Audio Meter  504
The Timeline  505
Upper Timeline 505
Lower Timeline  506
Tracks 508
Gaps  511
Timeline Controls  511
Audio Mixer  511
Audio Mixer Controls  512
Mute and Solo Tracks For Output  513
Replay  513
Undo and Redo in DaVinci Resolve  513
497The Cut Page | Chapter 26 Using the Cut Page
CUT
Overview of the Cut Page
With the addition of the Cut page, DaVinci Resolve now has two editing environments, intended for
two different audiences. While the Cut and Edit pages share many of the same panels such as the
Media Pool, the Timeline, and the Viewer, the controls that are exposed on the Cut page have been
designed for speed, so you can cut professional programs faster than you’ve ever been able to before.
Overview of the Cut Page User Interface
The default workspace of the Cut page consists of the Media Pool, a single Viewer, and the
Timeline area. These three regions let you quickly import and organize clips, edit clips, and even
export the result, all from within the Cut page.
The Cut page interface
Customizing the UI
A User Interface toolbar at the top of the Cut page lets you hide and show different panels as
necessary. For example, you can hide the Media Pool if you wanted more room for the Viewer.
You can also replace the Media Pool with other browsers in the Media Pool’s default area, showing
the Sync Bin, Transitions, Titles, or Effects Browser in order to add those effects to your program in
the Timeline. On the right side of the User Interface toolbar you can perform a Quick Export, expand
the Viewer to Full Screen, or open the Inspector.
Separate tabs on the left let you open the Media Pool,
Sync Bin, Keyframe Editor, Transitions, Titles, and Effects browser.
498The Cut Page | Chapter 26 Using the Cut Page
CUT
You can resize the Media Pool and Viewer by dragging the vertical seam that connects them to the left
or right, in the process making one panel bigger and the neighboring panel smaller.
The Viewer resize handle The Timeline resize handle
```
You can also resize the Timeline area by dragging the timeline handle (at the upper right corner of
```
```
the Timeline) up or down, making more or less room for the Timeline while simultaneously resizing the
```
Media Pool and Viewer areas.
Choose Settings Before You Start
```
When you first create a new project, you need to define its Timeline settings; you can optionally
```
choose from common presets or a fully custom setup.
Timeline Resolution Quick Menu
This drop-down menu, to the top-right of the Viewer, lets you quickly choose which resolution you
want to work at. A Custom option lets you open up the Timeline Settings panel in order to choose your
own options.
For more information about the Timeline Settings, see Chapter 6, “Project Settings.”
The Project Settings quick menu
499The Cut Page | Chapter 26 Using the Cut Page
CUT
The Media Pool
The Media Pool contains all video clips, audio clips, graphics, and other media that you import into
your project. You can create bins with which to organize all of this media, to make it easier to find what
you need quickly. These bins are opened via the bin drop-down at the upper left-hand corner.
Each piece of media you import, whether it’s video, audio, or graphics, appears as an individual clip
and can be selected, scrubbed for fast viewing, reorganized into bins, opened into the Viewer for
playback, or edited into a timeline using the edit buttons or via drag and drop.
The Media Pool in Thumbnail view
View icons at the upper right of the Media Pool let you see your clips in different ways, depending on
what you need to accomplish.
The Viewing ModeFs buttons
Metadata view: Each clip is represented by its own card with a scrubbable thumbnail
and basic clip metadata information visible. This view is designed to have more
metadata information than a thumbnail view but more targeted information than the
List view.
Thumbnail view: Each clip is represented by a scrubbable thumbnail. Hover the
playhead over each thumbnail and move it left and right to see the clip’s image play,
and use the I and O keys to mark sections of a clip that you want to use. Clicking on
the lower right corner of a thumbnail reveals the clip’s metadata.
Filmstrip view: Each clip is represented by a filmstrip of consecutive frames the
length of the Media Pool. Hover the playhead over the clip and move it left and
right to see the clip’s image play, and use the I and O keys to mark sections of a clip
that you want to use.
List view: Each clip appears as an item in a multi-column list showing a variety
of metadata about each clip. In List view, you can click the header of any column
```
to sort the contents by that column’s information (clicking again toggles the sort
```
```
order between Ascending and Descending). Scrolling right reveals additional
```
columns of information.
500The Cut Page | Chapter 26 Using the Cut Page
CUT
A Sort Media By drop-down menu lets you choose which
criteria defines the order in which clips in the Media Pool
are arranged. Options include: Custom, Timecode, Camera,
Date Time, Clip Name, Bin, Scene Shot, Clip Color, Date
Modified, Date Imported, and Online Status. You can choose
```
to sort in Ascending (bottom to top) or Descending (top to
```
```
bottom) order.
```
Lastly, a search field lets you type a term you want to use to
find one or more clips that match that criteria. When you type
anything, the contents of the Media Pool shrink to show only
clips that match your criteria.
The Sort Media
By dropdown menu
The Viewer
The Viewer lets you see clips from the Media Pool, or clips in the Timeline, and has numerous controls
to control what you see and how things play.
The single Viewer in the Cut page
501The Cut Page | Chapter 26 Using the Cut Page
CUT
The Viewer has four mode options. Which option is currently in use can be seen, and switched,
by four buttons in the upper lefthand corner of the Viewer.
The Viewer modes buttons
```
The Different options are entered automatically by various actions (from left to right):
```
• You can double-click any clip to open it into the Viewer as a Source Clip.
• You can view an entire bin full of clips in the Source Tape.
• You can play your edited program in the Timeline.
• You can see all of your synced material at the same time in the Multi Source viewer.
Playing Clips and Navigating the Timeline
Several controls sit at the bottom of the Viewer. These let you play through and otherwise navigate
clips and the Timeline in different ways. These controls are described from left to right.
The toolbar at the bottom of the Viewer
 Tools button: The Tools button reveals a variety of controls for transform, crop, audio, speed
effects, camera stabilization and lens correction, dynamic zoom, and compositing, covered in
more detail later in this chapter.
 Voiceover: Reveals controls for recording voice over directly into the timeline.
 POI and Add POI: These tools are used for selecting and modifying Points of Interest in Replay,
which is described in its own manual. For more information on these tools, see the “DaVinci
Resolve Replay Editor Instruction Manual.”
 Fast Review button: Intended to help you watch through a large collection of media quickly,
clicking this button begins accelerated playback through the Source Tape or through the Timeline,
where the speed of playback is relative to the length of each clip you’re playing through. Long
clips play faster, whereas shorter clips play closer to real time. In this way, you can watch a lot of
material really quickly.
 Jog control: Clicking and dragging within the jog control lets you scrub very precisely through the
content of the Viewer.
```
 Transport controls: A set of Previous Edit (Up Arrow), Stop (Spacebar), Play (Spacebar), Next Edit
```
```
(Down Arrow), and Loop Playback (Command-/) buttons constitute clickable controls for controlling
```
playback of clips and the Timeline. Each button has a matching keyboard shortcut.
 Mark In/Out: Clickable controls to set In and Out points respectively.
 Playhead timecode: A number field shows you the timecode value at the playhead of a clip or of
the Timeline to give you a numeric reference for where you are.
502The Cut Page | Chapter 26 Using the Cut Page
CUT
Optimized UI Layouts for Vertical Editing
Optimized layouts for vertical timelines and projects are supported in DaVinci Resolve. When a vertical
timeline or project is loaded, the UI automatically switches to a layout optimized for vertical viewers
on the Cut, Edit, and Color pages. Loading a normal landscape timeline or project then automatically
switches back to the original layout. No additional user intervention is needed.
You can change this behavior in Preferences > User > UI Settings > Use optimized UI layouts
for vertical video. Unchecking this box retains the normal horizontal layout, even for vertical
video timelines.
The UI now changes format to accommodate vertical video timelines automatically.
Tools
Clicking the Tools button reveals a toolbar that you can use to add and edit clip effects, right within
the Viewer with no Inspector needed. The Tools button reveals a variety of controls for transform,
crop, audio, speed effects, camera stabilization and lens correction, dynamic zoom, and compositing,
covered in more detail later in this chapter.
The Tools bar shown opened to the transform controls.
503The Cut Page | Chapter 26 Using the Cut Page
CUT
Bypass Color Grades and Fusion
The Bypass Color Grades and Fusion Effects button/drop-down lets you turn off all grades and
effects that you may have applied in the Color page and/or Fusion page in order to improve playback
```
performance on low power computers. Click the button (Shift-D) to disable or reenable grading and
```
effects, or right-click this button to access a menu that lets you choose which things you want this
button to control.
The Bypass Grades and Fusion button,
shown being right-clicked to view its options
Export The Current Frame from The Viewer
You can now export a still frame from the Viewer in the Media, Cut, and Edit pages.
To Export a Still Frame from the Viewer:
1 Use the Viewer’s playback controls to navigate to the frame you want to export.
2 Select File > Export > Current Frame as Still.
3 Enter the name of the still frame in the File System viewer.
4 Enter the desired format of the still frame in the File System viewer.
5 Click on the Export button.
Audio Meter
An audio meter to the right of the Viewer shows you a graphical
representation of the audio levels playing in the current clip or in the
Timeline as you play through the Viewer, via animated vertical bars that
are tinted to indicate how loud the levels are:
 Green indicates safe levels
 Yellow indicates levels that are peaking at approximately safe levels
 Red indicates levels that may be peaking at levels that are too high,
risking clipping the signal and causing distortion
These animated bars serve as a visual reference you can use to help
you adjust the volume of different clips to create a pleasing balance,
and to make sure you don’t exceed the maximum desired level and
introduce clipping. A speaker button at the top of the meters lets you
mute or unmute audio playback.
The Audio Meter
showing an audio signal
504The Cut Page | Chapter 26 Using the Cut Page
CUT
The Timeline
The word “timeline” refers both to an edited sequence of clips, which constitutes a program that is
stored in the Media Pool, and to the area of the Cut page interface where you can open this sequence
of clips to see its contents, and for playback and editing.
Timelines are created and stored in the Media Pool, along with all of your other clips. However, each
timeline is assembled and edited in what is sometimes referred to as the Timeline Editor. Different
pages of DaVinci Resolve show your timeline differently according to the special requirements of each
page focusing variously on different methods of editing, grading, compositing, and audio.
However, while the interface of the Timeline Editor changes from page to page, the actual contents
of the Timeline are identical, because each page’s Timeline Editor is in fact showing the exact same
Timeline that is currently open. This means that the advanced user can use every page of DaVinci to
do different things to the same Timeline, with only the interface changing to make different functions
possible in different pages.
For the Cut page user, the Timeline is divided into an Upper Timeline at the top, and a larger and more
detailed Timeline Editor showing a zoomed in portion of the Timeline around the playhead at the
bottom. Working together, these two views of your edited sequence make it possible to navigate your
entire project and cut in great detail.
The Timeline of the Cut page, comprising the Upper Timeline and the zoomed in Lower Timeline
Upper Timeline
The Upper Timeline always shows the entire program within the full width of your computer’s display.
The Upper Timeline’s playhead is always free, which makes it easy to use your pointer to scroll
around the entire program by dragging within the Timeline Ruler at top. This also serves as a visual
reference for keeping track of where you are in your program while you’re editing within the zoomed-
in Lower Timeline below.
Despite the Upper Timeline’s relatively small size, you can still edit in it, with most editing and
trimming functions that are available in the Lower Timeline also available in the Upper Timeline. Most
interestingly, it’s also possible to drag clips from one part of your program in the Lower Timeline, to
another area of your program in the Upper Timeline, and vice versa. Right-clicking on a clip in the
Upper Timeline will open the same context menu as right-clicking on a clip in the Cut page’s main
timeline, allowing you to perform the same operations.
A set of small numbers to the left of the Upper Timeline lets you click a number to choose the currently
```
selected track; this selection is mirrored on the zoomed in timeline below. The currently selected track
```
affects where incoming clips will be placed when editing, among other things.
505The Cut Page | Chapter 26 Using the Cut Page
CUT
Lower Timeline
```
The zoomed in Lower Timeline (often referred to simply as “the Timeline”) shows you a close-up view
```
of the portion of the currently open timeline that immediately surrounds the playhead. The zoom level
```
is fixed; you cannot change it. The zoomed-in lower timeline is intended for detailed editing, but clips
```
can be dragged between the Timeline and Upper Timeline for fast reordering of clips across the entire
duration of your program.
The Toolbar contains several editing functions grouped together in Action and Option menus.
These functions are accessed by clicking on the appropriate icon and selecting a function from the
drop-down menu. These tools are discussed in detail throughout the Cut section of the manual.
```
The Toolbar icons (from left to right):
```
Timeline Options, Timeline Actions, Edit Actions
Timeline Options
The tools under this icon deal with how the clips and timeline are displayed, and certain modes and
tools that apply to the whole timeline.
All of the Timeline Options functions
506The Cut Page | Chapter 26 Using the Cut Page
CUT
 Ripple On: Toggles ripple editing behavior on track V1.
 Snap: Toggles the playhead snapping behavior on or off.
 Trim to Audio: Opens an expanded audio view on the timeline when trimming a clip.
 Trim with Safe Edit: Toggles the Safe Edit function to prevent you from accidentally overwriting
adjacent clips while trimming.
 Display Clip Names: Toggles displaying the clip name on the timeline clip.
 Display Clip Status: Toggles displaying the status icons of various operations on the timeline clip.
 Display Speed Keyframes: Toggles displaying the Speed Keyframes on a clip with speed
changes applied.
 Viewer Background: Lets you choose how the blank areas of the Viewer background are
displayed, either Checkerboard, Black, Gray, or Alert Red.
 Set Default Transition: Opens the Set Default Transition window, letting you choose the transition
type, duration, and alignment for the default transition.
```
 Edit Using (Audio Track): Lets you choose either All audio tracks or select specific audio pairs to
```
edit with on the Cut page.
 Minimize Subtitle Track: Shrinks the vertical size of the subtitle tracks to give you more room in
the timeline.
 Fixed Playhead: Toggles the fixed playhead on or off. On leaves the playhead in place while the
timeline passes underneath it, while off makes the playhead move along the timeline.
 Boring Detector: Activates the Boring Detector.
Timeline Actions
The tools under this icon are generally used to add new items or make modifications to the Timeline.
All of the Timeline Actions functions
507The Cut Page | Chapter 26 Using the Cut Page
CUT
 Create Subtitles from Audio: Automatically creates subtitles for all dialog in the timeline.
 Detect Scene Cuts: Performs a Detect Scene Cuts operation, splitting one long clip of a finished
program into individual clips again.
 Audio Assistant: Uses AI to automatically perform an audio mix of your timeline
based on common deliverable requirements.
 Voice Convert: Uses AI to let you change the speaking voice from one person to another.
 Add Video Track: Adds a video track to the timeline.
 Add Audio Track: Adds an audio track to the timeline.
 Add Subtitle Track: Adds a Subtitle Track to the timeline.
 Split Clips: Splits the current clip in two at the playhead position.
 Join Match Edit Clips: Rejoins two continuous clips that have been split.
 Add Marker: Adds a marker at the playhead position.
 Set Color and Add Marker: Adds a marker and opens the Markers editor, so you can change the
color and add comments, etc.
 Clear Transition from All Edits: Removes all existing transitions from the timeline.
 Add Dissolve to All Edits: Adds a Cross Dissolve to every edit point on the timeline.
 Add Transition to All Edits: Adds the last used transition to every edit point on the timeline.
Edit Actions
The tools under this icon are used to adjust clips on the Timeline.
All of the Edit Actions functions
 Trim Start to Playhead: Deletes everything of the clip to the left of the playhead.
 Trim End to Playhead: Deletes everything of the clip to the right of the playhead.
 Resync Clip: If a clip has slipped sync from the rest of the program, this operation will resync it.
Tracks
The Timeline is divided into multiple tracks, with each track capable of holding a sequence of clips in
order to create a program. The main tracks, which are labeled numerically, combine a clip’s video and
audio into a single item in the Timeline, for simplicity. Editing the In or Out point of a clip edits the video
and audio together.
508The Cut Page | Chapter 26 Using the Cut Page
CUT
Cut Page Timeline tracks. Track ST1 shows a subtitle track. Track V1 shows both Video only and
combined Video+Audio clips in an enlarged view. Track A4 shows a separate audio track.
```
TIP: In the Edit page, Video+Audio clips are presented as separated Video and Audio items
```
on different tracks. When you open the Fairlight page, audio is presented on tracks with
lanes, where each audio channel can be seen. In this way, each page gives you different sets
of controls over the contents of the Timeline that are appropriate for each page.
Track Header Controls
The track controls, in order, allow you to enlarge a track, lock the track for edits, mute audio, and
enable or disable video for the track.
Controls to enlarge, lock, mute audio,
and disable video for the track
The Importance of Track 1
Each track in the Timeline of the Cut page is designed to carry specific parts of your program. Track 1
is intended for the primary video+audio of your program, often called the “A-roll,” since these are the
primary shots comprising the timing and pacing of the story you’re telling. Adding, deleting, inserting,
trimming, or otherwise rearranging clips on Track 1 results in the rest of the edited timeline being
automatically rippled to accommodate the change you’ve made, with clips to the right of the changed
area moving left to fill the gap of a deleted or shortened clips, or moving right to make room for an
inserted or lengthened clip.
Tracks 2 and Above
Tracks 2 and above are intended for “B-roll,” which is additional footage you stack on top of other clips
in Track 1 to illustrate what someone is saying in the audio of Track 1, or for superimpositions used for
compositing effects that combine two images together in creative ways. Moving or resizing clips on
```
Track 2 and above only moves or resizes that one clip; other clips in the Timeline are not rearranged
```
and the Timeline is not rippled when you do this.
For instances where multiple video clips overlap one another on multiple tracks, the video clip on
the highest track obscures those on lower tracks, meaning that only the top clips appear during
playback. This is useful when you’re experimenting with rearranging multiple clips in a complex scene.
For example, you could be editing a scene where an interview clip is on the bottom track, and various
b-roll clips are edited on tracks above the interview so you can freely rearrange them in different ways,
while it’s always easy to reveal the speaker on the bottom track by leaving a gap in the superimposed
b-roll clips.
509The Cut Page | Chapter 26 Using the Cut Page
CUT
Editing a scene with multiple superimposed clips
However, if you superimpose video-only or video+audio clips for compositing, you can use the
composite modes and the opacity slider found in the Composite section of the Viewer Tools controls
to mix multiple images together in different ways for artistic effects.
```
(Left) Superimposing clips you want to composite, (Right) Creating compositing effects with multiple superimposed clips
```
You can add additional Video+Audio tracks, when necessary, by either dragging a clip to the
undefined gray area of the Timeline above the other existing tracks to make a new track automatically,
by clicking the New Track button at the upper lefthand corner of the Timeline, or by right-clicking in the
timeline header area and choosing “Add Video Track” from the contextual menu.
Audio-Only Tracks
You can also edit audio-only clips such as music, narration, or sound effects, onto separate audio-
only tracks underneath, which are then labeled A1, A2, A3, etcetera. If you drag an audio clip to
the undefined gray area of the Timeline below the other existing tracks, an audio-only track will
automatically be created.
Audio-only tracks in the Cut page Timeline
510The Cut Page | Chapter 26 Using the Cut Page
CUT
Gaps
Because Track 1 is meant to hold the principal clips for your program, the Timeline automatically ripples
itself to close gaps that would otherwise result when you move or rearrange clips in Track 1, and
superimposed clips in Tracks 2 and above move to keep in sync with the clips they’re superimposed
over. However, you can move superimposed clips on Tracks 2 and above to place them wherever you
want, and gaps will be left between multiple clips on the same superimposed track so they can be
edited at specific places.
Timeline Controls
The Timeline controls in the upper left-hand corner of the Timeline let you enable/disable Rippling on
Track 1, enter Dynamic Trim mode, Split a clip at the playhead position, create Markers, and open the
Keyframe Editor.
The Cut page Timeline controls
Audio Mixer
The Cut page can show a full Audio Mixer, with access to all the tracks and busses of your mix, in
addition to shortcuts to any audio Track FX, Dynamics, and Equalizer tools. To enable the Audio Mixer,
select the Mixer tab at the top of the Cut page.
The Audio Mixer in action during Cut page playback
A unique feature of the Cut page Audio Mixer is the ability to expand it fully using the Expand icon in
the upper right of the Mixer. This will replace the whole lower timeline with the Mixer, giving you plenty
of room to monitor complex audio compositions, while still being able to access the editing functions
of the Upper Timeline.
511The Cut Page | Chapter 26 Using the Cut Page
CUT
The Audio Mixer expanded, allowing you to see all audio tracks while still editing in the Upper Timeline of the Cut page.
Audio Mixer Controls
Each track’s channel strip has the following controls:
 Track Number: The number of the timeline audio track corresponding to each channel strip
appears here.
 Track Effects: Double-click on one of the track effects at the top of the fader controls to open.
```
FX: Opens the Track Effects controls in the Inspector.
```
```
EQ: Opens the Track Equalizer.
```
```
DY: Opens the Track Dynamics.
```
 Pan control: Lets you pan a Mono track’s audio from left to right, or invert a Stereo track’s left and
right audio channels, or do surround mixing.
 Name: The name of the audio track that channel strip corresponds to. If you’ve edited the audio
track names in the Timeline, those names will appear here.
 Solo: Mutes all tracks other than ones that are soloed.
 Mute: Disables that audio track.
 dB: Shows you the volume, in decibels, that track is currently set to.
 Fader: Each track’s vertical fader can be dragged with your mouse or other pointing device to
adjust the volume of that track and perform automation recording. Dragging up increases volume,
dragging down decreases volume.
 Audio meters: Audio meters to the right of each fader display the audio volume of all channels on
that track during playback. Each channel strip has individual meters corresponding to the number
of channels that track has been set to accommodate.
512The Cut Page | Chapter 26 Using the Cut Page
CUT
Mute and Solo Tracks For Output
When you use the Mute or Solo controls of the Audio Mixer, track audio is disabled, both during
playback and delivery for output. Make sure you have re-enabled any tracks you need before heading
to the Deliver page. You can only modify mute and solo tracks on the Edit, Cut, and Fairlight pages.
Replay
The Cut page allows live multi-camera broadcast editing, playout, and replay with speed control.
Some of the Replay features are only available with Blackmagic Design hardware, such as a desktop
video interface, cloud store and ATEM switcher.
Please see the dedicated DaVinci Resolve Replay Editor Instruction Manual for more
information.
The Cut page Timeline controls
Undo and Redo in DaVinci Resolve
No matter where you are in DaVinci Resolve, Undo and Redo commands let you back out of
steps you’ve taken or commands you’ve executed, and reapply them if you change your mind.
DaVinci Resolve is capable of undoing the entire history of things you’ve done since creating or
opening a particular project. When you close a project, its entire undo history is purged. The next time
you begin work on a project, its undo history starts anew.
513The Cut Page | Chapter 26 Using the Cut Page
CUT
Because DaVinci Resolve integrates so much functionality in one application, there are three separate
sets of undo “stacks” to help you manage your work.
 The Media, Edit and Fairlight pages share the same multiple-undo stack, which lets you backtrack
out of changes made in the Media Pool, the Timeline, the Metadata Editor, and the Viewers.
 Each clip in the Fusion page has its own undo stack, so you can undo changes you make to the
composition of each clip, independently.
 Each clip in the Color page has its own undo stack, so you can undo changes you make to grades
in each clip, independently.
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
The History submenu, which lets you undo several steps at once
Once you’ve selected a step to undo to, the menu closes and the project updates to
show you its current state.
514The Cut Page | Chapter 26 Using the Cut Page
CUT
To undo and redo using the History window:
1 Choose Edit > History > Open History Window.
2 When the History dialog appears, click an item on the list to undo back to that point. Unlike
the menu, in this window the most recent thing you’ve done appears at the bottom of this list.
Selecting a change here grays out changes that can still be redone, as the project updates to
show you its current state.
The Undo history window that lets you browse the
entire available undo stack of the current page
3 When you’re done, close the History window.
515The Cut Page | Chapter 26 Using the Cut Page
CUT
Chapter 27
Importing and
Organizing Media
in the Cut Page
Before you can start editing, you need to import the clips you want to use for your
program into the Media Pool, which is the central repository of clips in your project.
This can include video, audio, and graphics files in any format that’s supported by DaVinci Resolve.
Once imported, the Media Pool on the Cut page has many organizational tools you can use to make
your project’s media faster for you to access and sort through as you find the clips you need to create
your program.
Contents
Importing Media 517
Removing Media  518
Organizing Media into Bins  518
Master Bin  518
Creating and Using Bins  518
Opening Bins  519
Create Bin With Selected Clips  519
Renaming Bins 519
Import and Export Specific DaVinci Resolve Project Bins  520
Import and Export Individual DaVinci Resolve Timelines  520
Sync Media Pool Bins with File System Folders  521
Import Blackmagic Cloud Shared Folders to Media Pool  523
ATEM Switcher Integration  524
Importing ATEM Mini Pro ISO Projects  525
Relinking Blackmagic Camera Masters to ATEM ISOs  526
Media Pool Views  527
Metadata View  527
516The Cut Page | Chapter 27 Importing and Organizing Media in the Cut Page
CUT
Importing Media
Two Import buttons at the top of the Media Pool let you use import dialogs to select media you want to
bring into the Media Pool for use in your project.
The Import Media and Import Folder buttons
To import individual clips:
1 Do one of the following:
```
a) Click the Import Media button.
```
```
b) Press Command-I.
```
```
c) Right-click the Media Pool and choose Import Media.
```
2 Use the Import dialog to select one or more clips to import, and click Open.
3 If you’re prompted to change the frame rate of a currently empty project to match that of the
incoming media, click Change.
Each piece of media you import, whether it’s video, audio, or graphics, appears as an individual clip in
the Media Pool. You can also import an entire folder full of media as a bin in the Media Pool.
Thumbnail View  530
Filmstrip View  530
List View  531
Metadata Display Palette  531
Sorting and Searching  532
Searching  532
Navigable Clip Paths  532
Sort Media By  532
Finding Timeline Clips in the Media Pool 533
Clip Color  533
Relinking Media 534
Relink Media  534
Relink Selected Clips  535
Voiceover Tool  536
Using Voiceover on the Cut Page 536
ATEM Switcher Integration  539
Importing ATEM Mini Pro ISO Projects  539
Relinking Blackmagic Camera Masters to ATEM ISOs  540
517The Cut Page | Chapter 27 Importing and Organizing Media in the Cut Page
CUT
To import a folder full of media into a bin:
1 Click the Import Media Folder button.
2 Use the Import dialog to select a folder containing media you want to import, and click Open.
3 If you’re prompted to change the frame rate of a currently empty project to match that of the
incoming media, click Change.
Each folder you import appears as a bin in the Media Pool. Double-clicking a bin opens its contents
into the Media Pool, enabling you to view each individual clip.
```
TIP: For additional media import features, you can use the Media page, with its Media
```
Storage browser and more feature-rich version of the Media Pool.
Removing Media
If there are clips you no longer want in your project, you can simply select them and press the Delete
```
or Backspace keys. A Dialog asks if you want to remove the selected clip or clips; clicking Remove will
```
remove them from the Media Pool, while leaving them intact on your media storage device.
```
If you want to remove every clip in the currently open bin (even the Master bin), you can also right-click
```
anywhere within the Media Pool and choose Remove All Clips in Bin from the contextual menu.
Organizing Media into Bins
```
For short projects, having all your clips together in a single bin (the Master bin is the top level of
```
```
the Media Pool) can be fast. However, for longer projects, organizing your media into subsets
```
of clips within individual bins can make browsing each bin’s contents using the Source Tape of
the Viewer more manageable.
```
TIP: You can move clips you know you don’t want, such as instances where the camera rolled
```
on unusable scenery or moments, or completely unusable takes, into another bin so those
clips don’t present themselves in the Source Tape for bins containing clips you want to use.
Master Bin
At the top level of your project hierarchy is the Master bin. The Master bin contains all of the media
```
content (clips, timelines, graphics, other bins, etc.) for your project. In the Cut page, the Master bin
```
also shows all of your project’s timelines for easy access, regardless of where they’ve been created in
your project.
Creating and Using Bins
```
You can create bins with which to organize your media by choosing File > New Bin (Shift-Command-N),
```
or by right-clicking in the Media Pool and choosing New Bin from the contextual menu. You can create
bins inside of other bins, and in so doing hierarchically organize the clips you need in a variety of ways.
518The Cut Page | Chapter 27 Importing and Organizing Media in the Cut Page
CUT
Bins seen in the Media Pool
Once you’ve created a bin, you can move one or more selected clips into it via drag and drop, just as
you would on the desktop of your operating system’s file manager.
Opening Bins
Any visible bin in the Media Pool can be opened by double-clicking it, or by clicking the Bin drop-
down at the upper left-hand corner of the Media Pool and choosing a bin to open from the menu
```
(they’re shown as a hierarchical list). When opened, a bin’s contents fill the Media Pool, and a path
```
indicator at the top of the Media Pool lets you see how many levels deep you are in cases where you
have bins inside of bins. You can click any level of this path to jump back up the hierarchy, or you can
choose another bin from the Bin drop-down.
The hierarchical Bin drop-down menu
Create Bin With Selected Clips
You can also create a bin and put clips into it in one step. Select one or more clips in the Media Pool,
right-click one of the selected clips, and choose Create Bin With Selected Clips from the contextual
```
menu. A new bin appears called “Bin X” (where X is the next number that’s available) displaying the
```
selected clips it now contains.
Renaming Bins
```
To rename a bin, click its name once, then slowly click a second time (clicking too fast is a “double-
```
```
click” which opens the bin), and the name becomes highlighted, ready for editing. You can also right-
```
click a bin and choose Rename Bin from the contextual menu, which also highlights the bin’s name,
```
ready for editing. When you’re done typing a new name, press Return (or Enter).
```
519The Cut Page | Chapter 27 Importing and Organizing Media in the Cut Page
CUT
Import and Export Specific DaVinci Resolve Project Bins
You can import/export specific bins from one DaVinci Resolve project to another, allowing you to pass
bins quickly between projects and workstations that have access to the same media. All Metadata, In/
Out points, Timelines, etc. are transferred along with the clips in the bin, but none of the actual media
files are included.
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
The bin or bins will appear in the Media Pool. Any bins imported this way will have the word “import”
appended to their name, to avoid duplicate names. If you import a bin that contains clips that were
already in the Media Pool, the potentially duplicate clips are excluded from the import and instead
relinked to the media referenced by your project. This keeps your Media Pool tidy. However, if the bin
or bins have been moved to another computer, you may have to relink offline media.
Import and Export Individual DaVinci Resolve Timelines
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
3 Choose “DaVinci Resolve Timeline Files (*.drt)” from the format options drop-down in the file
```
system dialog.
```
4 Choose where to save the DaVinci Resolve Timeline file (.drt) in the file system dialog,
```
and click Save.
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
The timeline will appear in the Media Pool, along with all of the clips associated with it. Any timelines
imported this way will have the word “import” appended to their name, to avoid duplicate names.
The imported timeline will be automatically conformed to corresponding media that’s already in the
Media Pool. However, if the timeline has been moved to another computer, you may have to reimport
or relink missing or offline media in to bring the imported timeline fully online.
520The Cut Page | Chapter 27 Importing and Organizing Media in the Cut Page
CUT
```
NOTE: Only a single timeline can be imported and exported at a time using this method.
```
To import or export multiple timelines, use the Import/Export Bin function described above.
Sync Media Pool Bins
with File System Folders
```
You can now sync a Media Pool bin with a folder on your computer’s file system (MacOS, Windows,
```
```
Linux etc.). This allows you to add additional media into a folder on your computer and have it
```
automatically import to its respective bin in DaVinci Resolve.
To set up a folder with Automatic Syncing:
1 On the Cut page, use the Import Folder icon on the top menu bar to set up matching folder and
sub folder names.
Use the Import Media Folder icon in the Cut page
2 Right-click on the imported folder and choose ”Automatically Resync Media Files.“
Right-click on the bin and select Automatically Resync Media Files
521The Cut Page | Chapter 27 Importing and Organizing Media in the Cut Page
CUT
Newly added clips in this folder will be added automatically to the media bin. This can be useful when
```
working with cloud-synced media files (as when using DaVinci Resolve’s Replay capabilities), or any
```
files that may be added to the folder later.
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
Sync actions will add new clips from sub-folders if the corresponding sub-bins exist. However, newly
created sub-folders without corresponding media bins are not tracked, and new media bins without
the corresponding sub-folders are skipped.
For example, say you were editing a sporting event, and you had a graphics operator creating
animated lower-thirds for each of the players. By creating a common network folder called “CG” and
automatically syncing it in DaVinci Resolve, each time a new lower-third was finished and saved, it
would automatically appear in your bin in the Media Pool, ready for use.
Here’s how you would set this up:
• Create a folder on your network storage called “CG.” Both the editor and the graphics
operator need to have access to this folder.
• Note that because this folder is currently empty, it can not be used in a Resync action yet.
Only after there is at least one media file in the folder can you perform a Resync.
• The graphics operator finishes his first animated lower third and saves it to the “CG” folder
```
as a .mov file (though any DaVinci Resolve readable media format would work).
```
• The editor then imports the “CG” folder into the Media Pool in DaVinci Resolve and selects
Automatically Resync Media Files from the context menu.
• As the graphics operator finishes and saves additional lower thirds into that folder, they
automatically appear in the Editor’s “CG” bin in the Media Pool, without having to specifically
import them.
• For organizational purposes, the graphics operator then creates a new folder in “CG” for
the other team, called “Team B.” Unfortunately, because this folder structure was not in
the original imported bin, it does not show up in the editor’s media pool. However if they
had created this Team B folder before the editor imported it, and it had media in it, it would
been there.
• Now in this case, the editor simply imports the same bin again, selects Automatically Resync
Media Files, and the new folder and all its media appear as expected. Any further files in
dropped in “Team B” will show up in the editor’s media pool.
522The Cut Page | Chapter 27 Importing and Organizing Media in the Cut Page
CUT
```
IMPORTANT: Media entries for clips that are removed or not found on the file system are
```
set as offline media. This allows for retention of metadata and is useful when the clip path is
temporarily offline, on cloud storage where file status may be in flux, or moved away by apps
or workflows seeking to write a new version in its place.
Import Blackmagic Cloud Shared
Folders to Media Pool
You can now import and sync Blackmagic Cloud Folders into the Media Pool. This allows you to
connect to one or more cloud media folders and selectively download media from them to your
local machine. Blackmagic Cloud Folders are online common storage folders that are not tied to a
specific project. This lets you create a pool of commonly used media assets, such as title sequences,
credits, bumpers etc, and share them online without having to import them separately into each
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
The Blackmagic Cloud Folder link dialog
523The Cut Page | Chapter 27 Importing and Organizing Media in the Cut Page
CUT
When you open the Blackmagic Cloud Folder in the Media Pool, it will be empty and populate one
```
clip at a time as their clip names (not their media) are downloaded from the cloud. Also the Blackmagic
```
```
Cloud Folder is not actually linked to your project yet; it is only linked when the first media clip
```
is “used.”
A “used” clip is new terminology in DaVinci Resolve and simply means a clip that has been altered in
any way inside the project. A clip can be used be by putting it on a timeline certainly, but also includes
other actions like applying a flag, altering its metadata, transcribing it, etc. Once a clip is used, its
media will start to download to your local machine. Clips that are used are denoted by a red dot next
to them in the Media Pool. Any unused clips will remain as virtual clips in the Cloud Folder until used.
Once downloaded, clips in Cloud Folders can be used just like any other clip in the Media Pool.
The Cloud Folder linked in List view. Clips with red dots are “used” and the original media
has been downloaded. Unused clips have just their proxies available to view. The Cloud
Sync column shows that the media is registered and synced with the Blackmagic Cloud.
ATEM Switcher Integration
If you’ve recorded a multi-camera event with the ATEM Mini Pro ISO or ATEM Mini Extreme ISO,
it is possible to move that entire project into DaVinci Resolve. ATEM projects include the master
```
program clip, as well as each individual camera’s “ISO” (isolated) clips, and each camera angle’s audio
```
recordings. All transitions, timecode, and camera number metadata are imported, as well as whatever
graphics were stored in the ATEM’s Media Pool. Once the project is loaded, you can seamlessly
continue your multi-camera edit in the Cut page.
This initial live recording coupled with later post-production editing workflow is often referred to
as “Live to Tape.” Live to Tape gives you the all the benefits of the spontaneity, verisimilitude, and
fast turnaround inherent to live production but with the added benefit of being able to later add
and remove sections and adjust the editorial flow of the program. Live to Tape also allows you to
fix simple mistakes, such as choosing a better camera angle, or replacing a title or graphic with an
updated version. Because of this flexibility, Live to Tape is the preferred method of recording almost
all broadcast network game shows, current events shows, and sitcoms. Essentially, any type of multi-
```
camera production that does not primarily depend on being live in real time for its main purpose (like
```
```
news or sports) is shot Live to Tape instead.
```
524The Cut Page | Chapter 27 Importing and Organizing Media in the Cut Page
CUT
The Live to Tape workflow requires the following elements, all of which are provided by the ATEM Mini
Pro ISO and ATEM Mini Extreme ISO.
 A program master clip that was shot live, including all the mixed camera angles, audio, transitions,
etc. from the beginning of the show until the end, for reference.
 Separate ISO recordings from each camera used to shoot the program master clip. An ISO is an
```
isolated (ISO) camera recording of the entire show from that camera’s perspective only, from the
```
beginning to end and without interruption.
 A timeline of the live recorded show that indicates where all the camera angles were switched,
what transitions were used, and what graphics were involved.
Importing ATEM Mini Pro ISO Projects
Importing an ATEM project essentially rebuilds the master program clip as a timeline inside
DaVinci Resolve from the camera ISOs, transitions, and graphics. This new timeline will match the
master program clip in every way, just created from the original source materials rather than as a single
compressed video file.
Refer to your ATEM’s specific documentation for how to set up ISO recording, but one important
setting is to make sure that you’ve checked the “ISO Record All Inputs” setting in the ATEM software
control before you start shooting.
To import an ATEM Mini Pro ISO Project:
```
1 (Before you shoot) Check the “ISO Record All Inputs” setting in the ATEM software control.
```
2 At this point, record your show using the ATEM device, and note the project’s folder location.
3 Select File > Import Project.
```
4 Select the DaVinci Resolve Project file (.drp) in the ATEM project folder, in the file browser.
```
5 Click on the Open button.
An ATEM Mini Pro project opened in the Cut page Sync bin
525The Cut Page | Chapter 27 Importing and Organizing Media in the Cut Page
CUT
Relinking Blackmagic Camera Masters to ATEM ISOs
The ATEM records each camera’s ISO as an H.264 HD video stream, which may not be of high enough
resolution or quality for some purposes. It’s possible to instantly switch your ATEM camera ISOs to the
original camera recordings made in a Blackmagic Camera instead. This workflow enables the highest
```
visual quality of Blackmagic RAW and the ability to output in higher resolutions (such as 4K or UHD)
```
than are supported by the ATEM internally. Essentially, the ATEM can reference an additional set of
higher quality ISOs recorded in the cameras, rather than those from the ATEM itself. This feature is
only available using Blackmagic Cameras.
This workflow requires one more step in the process, namely making sure that you have sufficient
recording space attached to each camera to record the show in its entirety. Refer to your ATEM’s
specific documentation for how to set up ISO recording and camera control, but one important setting
is to make sure that you’ve checked the “ISO Record All Inputs” and the “Record in All Cameras”
settings in the ATEM software control before you start shooting.
To relink to Blackmagic Camera masters from ATEM ISO recordings:
```
1 (Before you shoot) Check the “Record in All Cameras” setting in the ATEM software control.
```
```
2 (Before you shoot) Check the “ISO Record All Inputs” setting in the ATEM software control.
```
3 At this point, record your show using the ATEM device and note the project’s folder location.
4 Copy all the resulting camera masters from each camera’s memory card to the ATEM project’s
“Video ISO Files” folder, and then import the project into DaVinci Resolve.
5 DaVinci Resolve automatically creates a separate Blackmagic RAW folder in your project and
moves all the camera masters to that folder.
6 Use the menu Timeline > Switch to Camera Originals to instantly switch between referencing the
ATEM H.264 ISOs and the Blackmagic Camera masters.
The Show Camera Originals button
Once your project is imported successfully into DaVinci Resolve, it can be edited using the variety
of specialized Multicam editing tools found in the Cut page, including the Sync Bin, Live Overwrite,
and the DaVinci Resolve Speed Editor.
For more information on using these tools, see Chapter 28, “Fast Editing in the Cut Page.”
526The Cut Page | Chapter 27 Importing and Organizing Media in the Cut Page
CUT
Media Pool Views
Once you’ve imported some clips into the Media Pool, three controls at the upper right-hand side let
you control how they look, depending on what you need to accomplish.
The View Mode buttons
Metadata View
In the Metadata view mode, each clip is represented by its own card with a thumbnail and basic
clip metadata information visible. This view is designed to have more metadata information than a
thumbnail but more targeted information than the List view. This feature, combined with its sort modes,
is a powerful way to organize and reorganize your clips in the Media Pool.
```
The metadata fields of the Metadata view (from the top down):
```
 Thumbnail: A scrubbable thumbnail image of your clip.
 Row 1: A main description field that is variable and determined by the sort order selection.

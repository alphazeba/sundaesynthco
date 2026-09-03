# Scratch Baby Manual

## Global Settings

### Octave

Shifts the pitch for all perform keys up or down by 12 semitone increments

### Trnsps

Shifts the pitch of all perform keys up or down by single semitone increments

### Fine

Shifts the pitch of all perform keys up or down by one semitone, or anywhere in between

### Attack

Changes the base attack time of every perform key. Perform key attack is a multiple of this value.

### Release

Changes the base release time of every perform key. Perform key release is a multiple of this value.

### Interp

Sets the amount of smoothing interpolation of each change in playhead position. At high settings, playback sounds natural. At lower settings, digital artifacts are present. Only sonic characteristics are affected, movement behavior remains unchanged.

## Sample Preset & Load Button

Clicking “factory sample” dropdown lets you choose from a selection of samples useful for various styles of performance. Clicking “load” button opens the file browser, letting you use your own samples. Or simply drag and drop a sample into the sample window.

## Sample Window

### Playhead

The playhead is indicated as a green line.

### Cue Points

A cue point is indicated as white a line. A cue point turns red when its corresponding perform key is selected. Add a cue point by selecting a perform key and clicking anywhere inside the sample window. A dot will appear on the selected Perform Key when a cue point has been set. Remove a cue point by clicking the red X below the selected cue point line.

### Zooming & Scrolling

Hold right click on your mouse to zoom and scroll the waveform within the Sample Window for more precise Cue Point placement. Moving the mouse up and down will zoom in and out and moving the mouse side to side while scroll.

## Perform Keys

Each perform key can be set to behave in its own way, allowing you to configure and perform specific articulations. Perform keys start at each C note and go up chromatically to that octaves B note. This is repeated for every octave on the keyboard, allowing you to play wherever is most physically convenient.

### Perform Key Header

Each Perform Key’s header has a color and number. The key number indicates which step within an octave a perform key is. The color indicates if it corresponds to a black key or a white key on your keyboard. Clicking on a key number will play that Perform Key.

### Playback Modes

The mode button is directly beneath the Perform Key header. Clicking the mode button will change it to the next mode.

- Play
    - will move the playhead forward in time. 
- Reverse
    - will move the playhead backwards in time.
- Cue Only 
    - lets you utilize a Cue Point without activating playback.
    - *Be aware* that Cue Only will have **no effect** if a cue point is not set and will not generate any sound as the only Perform Key being played.

### Attack

Attack sets the amount of time it takes to accelerate the playhead from stationary to the desired speed.

### Speed

Speed determines how far the pitch is shifted from the original sample. Its range is -24 to +24 semitones. *Bonus tip*: fine tune can be set using right click.

### Release

Perform key release sets the amount of time it takes to decelerate the playhead from the desired speed to stationary.

## Fader Key

The fader key is the one perform key with a special function. It is in position 12 with a green background color. It mimics the behavior of the cross fader on a DJ’s mixer. It can be thought of as the opposite of a mute button; when you hold down this perform key, sound will be allowed to pass through, when you let go, sound will not be allowed to pass through.

### Mode

The fader key has two modes: always on, and fader. In always on, the fader key is effectively disabled and sound will pass through regardless of if the key is pressed. In fader, it is effectively enabled, only allowing sound to pass through when the key is held down.

### Attack

Sets the amount of time it takes to reach normal volume.

### Release

Sets the sampling of time it takes to reach complete silence.

# Features coming soon

- Multi-select
- Improved Cue Point editing
- Live sampling from DAW
- Presets
- Quality of life improvements


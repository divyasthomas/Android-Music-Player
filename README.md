# Android-Music-Player
A music player  for Android with song playback, navigation, and customizable settings.  It primarily uses the Android MediaPlayer API to handle audio playback. This API provides functionalities for playing, pausing, and managing audio files within the app. For additional features like handling UI elements and background tasks, the app also utilizes the Android SDK and Kotlin Coroutines.

# Main Tools
- Programming Language: Kotlin (for Android development)
- Framework: Android SDK
- API: Android MediaPlayer API (for audio playback)
- UI Library: Android Jetpack, Material Design
- Coroutines: Kotlin Coroutines for asynchronous tasks
- RecyclerView: For listing songs
- SeekBar: For showing and controlling song progress
- SharedPreferences: For saving user settings (e.g., loop mode)
- XML Layouts: For defining UI elements and layout structure


# Main Features
## Main page:
- Displays the name of the current song.
- Shows the next song in the playlist.
- Play/Pause button toggles music playback.
- Seek Bar for tracking and adjusting song progress.
- RecyclerView lists all songs with total duration.
- Skip Forward and Backward buttons navigate through songs.
- Song selection starts playback and highlights the selected song.

## Playback Controls:
- Play/Pause button changes between play and pause icons.
- Skip buttons move to the next or previous song without changing play/pause state.
- Loop Indicator shows if the current song will loop. If the loop condition is true, the background of the L is red and the current song will loop when it finishes. Otherwise, the background of the L is white.
- Shuffle Button randomizes playlist order.

## Seek Bar:
- Slider to control song playback position.
- Displays elapsed time and remaining time of the song.
- Updates in real-time as the user drags the slider.

## Settings Fragment:
- Accessed via the gear icon in the action bar.
- Allows toggling of loop mode with a switch.
- Displays the number of songs played.
- Options to save changes (OK) or discard them (Cancel, Back Button).

## Coroutines:
- Utilized to smoothly update time display and seek bar without blocking the main thread.



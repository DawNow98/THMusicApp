THMusicApp 

Is a minimalist music player app designed for Taco Hemingway fans, allowing you to listen to the full album in high-quality sound. The app's features include:

- Play and pause buttons for seamless control.
- Switching between tracks using "next" and "previous" buttons.
- Real-time playback tracking with a dynamic time slider.
- Automatic transition to the next song when the current one ends.
- A visually appealing interface with a gradient and dark theme.


The app leverages the AVKit framework to handle MP3 playback. Key implementation details include:

- AVAudioPlayer for initializing, playing, pausing, and monitoring audio file states.
- Functions like setupAudio() for loading MP3 files from the app bundle, playAudio() and pauseAudio() for playback control, and updateProgress() for updating the playback slider in real-time.
- Binding and State in SwiftUI to dynamically update the user interface, including the current song title and time progress.


The app combines a clean, responsive design with intuitive controls, making it an ideal choice for immersive music listening.

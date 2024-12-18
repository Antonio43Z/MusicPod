
# MusicPod

MusicPod is an iOS application designed to explore various music genres and podcasts available on iTunes. The app provides a user-friendly interface to select genres, view top songs and podcasts, and search for specific content.

## Features
- **Genre Selection:** Users can browse through a selection of music genres to discover new content.
- **Song and Podcast Viewing:** For each selected genre, users can view popular songs and podcasts.
- **Audio Playback:** Users have the ability to play previews of songs and listen to podcasts directly within the app.
- **Search Functionality:** Users can search for artists, songs, podcasts, and albums using a simple search bar.

## Components
- **GenreManager:** Manages data fetching from the iTunes API, including retrieving available genres, songs, and podcasts.
- **MusicGenreHomeView:** Displays genres and their respective songs and podcasts.
- **SongCard and PodcastCard:** Used to present individual songs and podcasts with their respective artwork and playback controls.
- **SearchView:** A separate view for searching and displaying results based on user queries.

## Getting Started
### Prerequisites
- Xcode 12 or later
- iOS 14 or later

### Installation
1. Clone the repository.
2. Open the `MusicPod.xcodeproj` file in Xcode.
3. Build and run the project on a simulator or a physical device.

### Usage
- Navigate through different music genres using the `MusicGenreHomeView`.
- Listen to song previews or podcasts by selecting a card.
- Use the search functionality to explore content by artists, song names, podcasts, or album names.

## Contributing
Contributions are welcome! To contribute, please open issues or submit pull requests for any improvements or bugs you find.

## License
[MIT License](LICENSE)

## Acknowledgments
This app uses data provided by the iTunes Store via their public API.


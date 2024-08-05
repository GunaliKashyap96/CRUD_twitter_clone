# Qwitter

Qwitter is a Twitter-like social media application built with Vue.js and Quasar Framework. It allows users to post short messages called "Qweets", like them, and delete them.

## Features

- Create new Qweets with a character limit of 250
- Real-time updates of Qweets using Firebase Firestore
- Like/unlike Qweets
- Delete Qweets
- Responsive design for various screen sizes

## Technologies Used

- Vue.js
- Quasar Framework
- Firebase Firestore
- date-fns for relative time formatting

## Project Structure

The main component `PageHome.vue` contains the following sections:

1. New Qweet input
2. Qweet list with real-time updates
3. Individual Qweet components with like and delete functionality

## Setup

1. Clone the repository
2. Install dependencies: `npm install`
3. Set up a Firebase project and add your configuration to `src/boot/firebase.js`
4. Run the development server: `quasar dev`

## Architecture

The application follows a component-based architecture, with the main functionality encapsulated in `PageHome.vue`. It utilizes Firestore for real-time data synchronization and Vue.js computed properties for efficient data processing.

## Future Enhancements

- User authentication and profiles
- Advanced content interactions (retweets, comments)
- Media upload capabilities
- Search and discovery features
- Direct messaging system
  
## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments
- freeCodeCamp for the project inspiration and learning resources
- Quasar Framework and Firebase teams for their excellent tools

## License

[MIT License](LICENSE)

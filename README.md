# 🎵 Spotify Clone - Pure JavaScript Music Player
A high-performance, responsive music streaming interface built with **JavaScript**, CSS3, and HTML5. This project replicates the core Spotify experience, including dynamic album loading, seekbar synchronization, and playlist management.
## 🚀 Key Features
 * **Dynamic Album Architecture:** Automatically fetches and parses local server directories to generate album cards with metadata (via info.json).
 * **Real-time Audio Control:** A custom-built seekbar using getBoundingClientRect() for precise song scrubbing and time updates.
 * **Intelligent Playlist Loading:** Swaps song lists on the fly when clicking different albums without refreshing the page.
 * **Responsive State Management:** Uses global state to track currentSong, songs arrays, and currFolder to ensure seamless "Next/Previous" functionality.
 * **Volume & UI Sync:** Fully functional volume slider and play/pause toggles that stay in sync with the audio hardware.
## 🛠️ Technical Stack
 * **Frontend:** HTML5, CSS3 (Flexbox & Grid)
 * **Logic:** JavaScript (ES6+)
   * **Asynchronous Programming:** Extensive use of async/await and the Fetch API for directory parsing.
   * **Event Handling:** Advanced use of event bubbling and currentTarget for interactive UI elements.
   * **String Manipulation:** Complex path parsing using split(), slice(), and replaceAll() to handle cross-platform file URLs.
## 💡 What I Learned
During the development of this project, I mastered several complex web development concepts:
 1. **DOM Manipulation:** Creating and injecting complex HTML structures dynamically using JavaScript template literals.
 2. **Audio Object Logic:** Handling the Audio() class, managing timeupdate listeners, and calculating durations.
 3. **Path Parsing:** Dealing with URL encoding (like %20 for spaces and %5C for backslashes) to ensure assets load correctly across different local servers.
 4. **Error Handling:** Implementing "No Songs Found" logic to prevent app crashes when accessing empty directories.
## 🔧 How to Run
 1. Clone this repository.
 2. Open the project in **VS Code**.
 3. Install the **Live Server** extension.
 4. Right-click index.html and select **"Open with Live Server"**.
   * *Note: Using a server is required because the app uses the Fetch API to read song directories.*
### Author
**Eisha Kanwal**
*Frontend Developer*

# PepBoard
🧾 Project Description
This project is a web-based Whiteboard application built entirely with Vanilla JavaScript, HTML, and CSS, without using any front-end frameworks or libraries. The goal is to replicate the functionality of a physical whiteboard with interactive features that enhance usability and productivity, particularly for online teaching, collaboration, and note-taking.

🎯 Purpose
The main objective of this project is to:

Learn and demonstrate DOM manipulation, event handling, and state management using core web technologies.

Understand how to implement complex UI interactions like drag-and-drop, canvas drawing, and undo-redo history.

Provide users with a smooth and responsive whiteboard experience for sketching, planning, or collaborative discussions.

✨ Key Features
🎨 Drawing Tools
Pencil Tool: Users can draw freely on the whiteboard with selectable colors and line widths.

Eraser Tool: Erase any drawing with an adjustable eraser size.

🗒️ Sticky Notes
Users can create sticky notes to add short text.

Notes can be moved around the board freely using drag-and-drop.

Notes can be minimized/maximized for a cleaner workspace.

🖼️ Sticky Images
Upload and add images to the board.

Images can be resized and repositioned just like sticky notes.

💾 Download Board
Users can download the current whiteboard as an image (PNG) to save or share their work.

↩️ Undo & Redo
Implemented using JavaScript arrays as stacks.

Tracks every drawing stroke or state change.

Allows users to undo previous actions and redo them if needed.

🔧 Technologies Used
Technology	Purpose
HTML5	Structure of the whiteboard app
CSS3	Styling and layout
JavaScript	Core logic and interactivity
DOM API	Handling UI elements dynamically
Canvas API	Drawing shapes and images

🛠️ How to Run Locally
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/whiteboard.git
Navigate to the project folder

bash
Copy
Edit
cd whiteboard
Open index.html in a browser
You can do this by double-clicking the file or serving it with a local server:

bash
Copy
Edit
# Example using Python (optional)
python -m http.server

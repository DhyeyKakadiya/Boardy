# Boardy

## Tech Stack

- **Framework**: [Next.js](https://nextjs.org/)
- **UI Components**: [shadcn/ui](https://ui.shadcn.com/)
- **Backend**: [convex](https://www.convex.dev/)
- **Real-time Collaboration**: [liveblocks](https://liveblocks.io/)

## Features

- **Real-time collaboration**: Multiple users can interact on the whiteboard simultaneously.
- **Interactive UI**: Intuitive and responsive user interface for a seamless experience.
- **Scalable backend**: Powered by Convex for managing backend logic and data storage.
- **Live updates**: Instant updates using Liveblocks for real-time synchronization.

### New Features

- **Keyboard Shortcuts**:
  - **Move Selected Layers**: Use keyboard shortcuts to move selected layers within the Canvas component.
  - **Duplicate Layers**: Duplicate selected layers with `Ctrl + D`.
  - **Focus Search Input**: Keyboard shortcut to focus on the search input field.
  

- **Enhanced Selection Tool**:
  - **Improved Layout and Functionality**: Added a duplicate icon in the selection box for better usability.
  - **Select Fully Inside Rectangle**: Layers are only selected if they are fully inside the selection rectangle.
  - **Shortcuts for Layer Insertion**: Added keyboard shortcuts for selection and insertion in the toolbar

- **Board Creation Limit**:
  - User can make only 5 boards within an organization

- **Reset Camera**:
  - When the user scrolls through the canvas, a button at the right bottom appears through which the user can reset the camera position

- **Color Picker**:
  - User now has infinite possible combinations of the layer they want. Color picker also has the debouncing technique to prevent the numerous undo/redo actions

- **Export as a PNG**:
  - Users can now export their board as a PNG image file. This functionality allows users to save their work and share it with others easily.

- **Bug Fixes**:
  - **Search and Favorite Functionality**: Fixed the search and favorite functionality by using `useSearchParams`.

---

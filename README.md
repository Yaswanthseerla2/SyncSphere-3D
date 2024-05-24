# SyncSphere-3D

This project demonstrates a unique approach to creating and managing a 3D scene across multiple browser windows using Three.js and localStorage. It's designed for developers interested in advanced web graphics and window management techniques.

-3D scene creation and rendering with Three.js.
- Synchronization of 3D scenes across multiple browser windows.
- Dynamic window management and state synchronization using localStorage.

- - `WindowManager.js` handles the lifecycle of multiple browser windows, including creation, synchronization, and removal. It uses localStorage to maintain state across windows.
- `main.js` initializes the 3D scene using Three.js, manages the window's resize events, and updates the scene based on window interactions.

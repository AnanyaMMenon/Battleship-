# MP Report

## Student information

- Name: Ananya Menon
- AID: A20538657

## Self-Evaluation Checklist

Tick the boxes (i.e., fill them with 'X's) that apply to your submission:

- [X] The app builds without error
- [X] I tested the app in at least one of the following platforms (check all
      that apply):
  - [ ] iOS simulator / MacOS
  - [X] Android emulator
- [X] Users can register and log in to the server via the app
- [X] Session management works correctly; i.e., the user stays logged in after
      closing and reopening the app, and token expiration necessitates re-login
- [X] The game list displays required information accurately (for both active
      and completed games), and can be manually refreshed
- [X] A game can be started correctly (by placing ships, and sending an
      appropriate request to the server)
- [X] The game board is responsive to changes in screen size
- [X] Games can be started with human and all supported AI opponents
- [X] Gameplay works correctly (including ship placement, attacking, and game
      completion)

## Summary and Reflection

I implemented the core game logic and UI using Flutter and followed the MVVM architecture for better separation of concerns. I focused on clean state management and ensured responsiveness across different screen sizes. I faced challenges with API integration due to CORS issues in the browser version but confirmed backend responses via Postman.

I enjoyed building the UI and seeing the game come together visually. Debugging platform-specific Gradle issues was frustrating and time-consuming. I wish I had better insight into cross-platform compatibility issues with Flutter earlier on

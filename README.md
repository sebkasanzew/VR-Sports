# VR Sports

A Virtual Reality sports simulation project built with Unity, focusing on realistic baseball mechanics and advanced motion tracking.

## Features

- **Realistic Baseball Physics**: Custom physics implementation for ball flight and bat-ball collisions.
- **Motion Tracking**: Support for Microsoft Kinect and Sixense (Razer Hydra) for immersive player movement and input.
- **Multiple Scenes**: Includes a main game mode, ball throwing machine practice, and various tracking test environments.
- **Immersive Environment**: Detailed 3D models and terrain for a realistic sporting experience.

## Technical Stack

- **Engine**: Unity 5.2.2f1
- **Input/Tracking**:
  - Kinect SDK
  - Sixense Input (Razer Hydra)
- **Languages**: C# (Unity)

## Project Structure

- `Assets/Scripts`: Contains core logic for baseball physics (`BaseballPhysics.cs`), collision handling (`BaseballCollision.cs`), and movement tracking (`MovementTracker.cs`).
- `Assets/Scenes`:
  - `MainGame.unity`: The primary gameplay scene.
  - `BallThrowingMachine.unity`: Practice mode.
  - `KinectTestScene`: Testing environment for Kinect integration.
- `Assets/Models`: 3D models for players, bats, and equipment.
- `Assets/SixenseInput`: Plugin for Razer Hydra support.

## Getting Started

1. Clone the repository.
2. Open the project in **Unity 5.2.2f1**.
3. Ensure you have the necessary drivers for Kinect or Sixense if you plan to use motion tracking.
4. Load `Assets/Scenes/MainGame.unity` and press Play.

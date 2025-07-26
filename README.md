# Ride Sharing System

This repository contains a simple Ride Sharing System implemented in Pharo Smalltalk, demonstrating core object-oriented programming concepts.

## Features

* **Classes**: `Ride` (base), `StandardRide`, `PremiumRide`, `Driver`, `Rider`.
* **Functionality**: Simulates basic ride requests, driver assignments, and fare calculations.
* **Demonstration**: The `demonstrateSystemFunctionality` method showcases the system's interactions.

## How to Run

This project is provided as a complete Pharo image.

1.  **Download Pharo VM**:
    * Download the appropriate Pharo Virtual Machine (VM) for your operating system from the official Pharo website: [pharo.org/download](https://pharo.org/download) (e.g., Pharo 11 or later VM).
2.  **Download Project Files**:
    * Download both `RideSharingSystem.image` and `RideSharingSystem.changes` files from this GitHub repository.
    * Place them in the **same directory** as your Pharo VM executable (e.g., `pharo.exe` or `Pharo.app`).
3.  **Launch Pharo**:
    * Run the Pharo VM executable (e.g., double-click `pharo.exe` on Windows or `Pharo.app` on macOS). This will launch your saved Pharo environment.
4.  **Run the Demonstration**:
    * In the running Pharo environment, open a `Playground`: Right-click on the desktop, then `Tools` -> `Playground`.
    * In the Playground, type the following line of code:
        ```smalltalk
        Object new demonstrateSystemFunctionality
        ```
    * Select the entire line of code.
    * Press `Ctrl+D` (or `Cmd+D` on macOS) to execute it.
5.  **View Output**:
    * The system's output will appear in the `Transcript` window.
    * If the Transcript isn't visible, open it via: `Tools` -> `Transcript`.

## Project Structure

The core code is organized into the `RideSharingSystem` package within the Pharo image. Key classes include:

* `Ride`: Base class for all rides.
* `StandardRide`, `PremiumRide`: Concrete ride types with their own fare logic.
* `Driver`: Manages driver details and their assigned rides.
* `Rider`: Manages rider details and their requested rides.

## License

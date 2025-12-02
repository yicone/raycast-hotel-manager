# Hotel Manager for Raycast

Manage your [Hotel](https://github.com/typicode/hotel) apps directly from Raycast.

## Features

- **List Apps**: View all your Hotel apps and their status.
- **Start/Stop**: Toggle apps on/off.
- **Open in Browser**: Quickly open apps via `.localhost` domain.
- **Open Direct URL**: Open apps via direct IP:Port (Option + Enter).
- **Copy URL**: Copy the app URL to clipboard (Cmd + C).
- **Open Project Folder**: Open the app's directory in Finder (Ctrl + Enter).
- **Restart**: Restart the app (Cmd + Shift + R).

## Installation

1.  Ensure you have [Node.js](https://nodejs.org/) and [Raycast](https://raycast.com/) installed.
2.  Navigate to this directory in your terminal.
3.  Run `npm install` to install dependencies.
4.  Run `npm run dev` to start the development server and import the extension into Raycast.

## Requirements

- Hotel must be running (`hotel start`).
- Hotel API must be accessible at `http://localhost:2000` (default).

## Configuration

The extension assumes Hotel is running on `http://localhost:2000` and uses `.localhost` TLD.

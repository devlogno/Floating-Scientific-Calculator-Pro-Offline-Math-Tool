# Floating Scientific Calculator Pro: Offline Math Tool.

A premium, high-performance scientific calculator for Chrome, inspired by the classic Casio ClassWiz series. This extension provides a professional-grade calculation experience in a standalone, floating, or Picture-in-Picture window.

## Key Features

- **Standalone Window**: Launches in its own dedicated popup window, separate from your tabs.
- **Picture-in-Picture (PIP)**: Pin the calculator to float above all other windows and websites—perfect for multitasking.
- **Full Keyboard Support**: Type expressions, use Backspace to delete, and Enter to calculate instantly.
- **Natural Display**: Handles complex expressions with a scrolling LCD that follows your cursor.
- **Dynamic Themes**: Automatically follows your system light/dark mode, or toggle manually with the built-in analog switch.
- **History & Memory**: Track your past calculations with the integrated HIST view.
- **Privacy First**: Zero data collection. Works entirely offline.

## Keyboard Shortcuts

- **0-9**: Numeric input
- **+, -, *, / **: Basic operators
- **^, !**: Power and Factorial
- **Backspace**: Delete last character (atomic for functions)
- **Delete**: Clear all (AC)
- **Enter**: Calculate (=)
- **Arrow Keys**: Move cursor for editing

## Installation

1. Download or clone this repository.
2. Run `npm install` and `npm run build`.
3. Open `chrome://extensions/` in Chrome.
4. Enable "Developer mode".
5. Click "Load unpacked" and select the `dist` folder.

## Technology Stack

- React + Vite
- Tailwind CSS
- Math.js
- Framer Motion
- Lucide Icons

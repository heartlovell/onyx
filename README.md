<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Onyx Systems - Cybersecurity & Infrastructure

A terminal-style web interface for Onyx Systems: cybersecurity auditing, IT problem solving, and high-conversion web engineering.

Built with React, TypeScript, Vite, and Gemini AI.

## Features

- Interactive terminal UI with boot sequence and command system
- AI-powered intelligence queries via Google Gemini
- Dedicated views for Security, IT Work, and Web Development services
- Real-time system status bar with uptime and memory simulation
- Responsive design with CRT scanline effects

## Run Locally

**Prerequisites:** Node.js

1. Install dependencies:
   ```
   npm install
   ```
2. Create a `.env.local` file and set your Gemini API key:
   ```
   GEMINI_API_KEY=your_api_key_here
   ```
3. Run the app:
   ```
   npm run dev
   ```

## Terminal Commands

| Command | Description |
|---------|-------------|
| `help` | List all available commands |
| `query [prompt]` | Consult Onyx Intelligence |
| `clear` | Clear the terminal |
| `dashboard` | Return to main view |
| `run pentest_audit` | Security protocols view |
| `sysctl --solve-problems` | IT problem solving view |
| `deploy customer_magnet` | Web development view |
| `finger onyx_admin` | Contact information |

## Build

```
npm run build
```

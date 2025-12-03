# 🎄 Advent Calendar 2025

An interactive advent calendar with daily surprises!

## Features
- 25 doors for December 1st-25th
- Doors unlock automatically on their respective dates
- Beautiful animations when opening doors
- Persistent state (opened doors remain opened)
- Snow and confetti effects
- Responsive design for all devices

## Setup

### To add your surprise links:

1. Open `script.js`
2. Find the `surpriseLinks` object at the top
3. Add your links for each day:

```javascript
const surpriseLinks = {
    1: "https://your-link-for-day-1.com",
    2: "https://your-link-for-day-2.com",
    // ... etc
};

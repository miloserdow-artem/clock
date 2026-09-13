# Language / Язык
> [🇷🇺 Русский](README.md) | [🇬🇧 English](README-en.md) | [🇪🇸 Español](README-es.md)

# Clock — Analog Clock

A training project created on January 16, 2022. It features a classic analog clock built with pure JavaScript, utilizing CSS transformations to rotate the clock hands.

This is a small yet illustrative project designed to practice DOM manipulation, working with time intervals, and applying CSS transformations.

**Creation Date:** January 16, 2022

## Features
- **Real-Time Display:** Displays the current system time in real-time.
- **Smooth Rotation:** Smooth rendering and rotation of the hour, minute, and second hands.
- **Dynamic Updates:** The hands' positions are recalculated and updated every second via `setInterval`.

## Tech Stack
- HTML5
- CSS3 (Transformations, absolute positioning)
- Vanilla JavaScript

## How It Works
Every second, a new `Date` object is created to extract the current hours, minutes, and seconds. These values are then converted into rotation degrees:
- **Hour hand:** Rotates 30° per hour (with an additional smooth offset based on the current minutes).
- **Minute and Second hands:** Rotate 6° per single unit of time.

The final rotation angle is applied to the corresponding DOM elements using the `transform: rotateZ()` CSS property.

## License
MIT License - feel free to modify and use it for your own projects!

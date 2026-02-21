# Duration Calculator

A single-file, mobile-friendly duration calculator built around a 24-hour clock dial. Set a start and end time by dragging handles around the wheel and read off the duration at a glance.

## Usage

**Start / End handles** — Drag the blue (start) or orange (end) handle around the ring to set each time. Times snap to 15-minute intervals.

**Arc drag** — Drag anywhere along the orange arc to shift both the start and end times together, preserving the duration.

**Midpoint grab stick** — A small radial handle sits outside the ring at the arc's midpoint. Use it to drag the whole arc when the duration is short and the arc itself is hard to grab.

**Duration readout** — The current duration is shown below the wheel in hours and minutes, with a total-minutes sub-label. A "↺ crosses midnight" warning appears when the arc spans midnight.

**Sunrise / sunset shading** — On load the app requests your location and fetches today's sunrise and sunset times. Nighttime hours are shaded darker on the ring, and small time labels mark the day/night boundaries.

## Running

Open `DurationCalculator.html` directly in any modern browser — no build step or server required. Location access is needed for the sunrise/sunset feature; the app works without it.

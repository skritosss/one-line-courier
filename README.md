# One Line Courier

A one-finger mobile time-killer game about drawing delivery routes through a tiny city.

## Concept

The player draws a route with one finger, releases it, and watches the courier follow the path. The goal is to pick up and deliver orders while avoiding traffic, pedestrians, roadblocks, and time pressure.

The game is designed around very short sessions: each level should be readable in seconds and finish in under a minute.

## Core Loop

1. Read the map.
2. Draw a delivery route.
3. Release to start the courier.
4. Avoid collisions and complete deliveries.
5. Earn stars / coins.
6. Unlock harder levels, vehicles, and daily challenges.

## MVP Features

- touch-based route drawing;
- courier movement along the drawn path;
- pickup and delivery points;
- moving traffic obstacles;
- win / fail states;
- level timer;
- stars and coins;
- simple tutorial;
- 30-50 handcrafted levels;
- vehicle skins;
- mobile-friendly UI.

## Tech Stack

- Engine: Unity 2D
- Language: C#
- Target: iOS / Android
- Future monetization: rewarded ads, remove ads, cosmetic skins

## Roadmap

- `v0.1` playable route-drawing prototype;
- `v0.2` obstacles, collisions, and level goals;
- `v0.3` level progression and tutorial;
- `v0.4` skins, coins, and daily challenge prototype;
- `v1.0` App Store / Google Play release candidate.

## Live Prototype

Try the browser prototype: <https://skritosss.github.io/one-line-courier/prototype/>

Source: [`prototype/index.html`](prototype/index.html)

What exists now:

- draw a route with the mouse / finger;
- courier follows the route after release;
- pickup and delivery points;
- moving traffic obstacles;
- win / fail states;
- timer and distance feedback.

## Status

Playable browser prototype. Unity mobile implementation is the next step.

## Product Notes

The goal is not to make a complex game. The goal is to make a sticky, replayable, visually clear time-killer that can be understood from a short video.

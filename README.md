# Hi, I'm Abhilash

I'm a high school student in New Jersey building web tools and iOS apps. My recent projects include a piano practice studio, a payment failure lab, a local file browser, and a Bluetooth lighting controller.

[Portfolio](https://abhilash.is-a.dev) · [Try Cadence](https://cadence-piano.cadence-deployment.workers.dev)

## Projects

### [Aftermath](https://github.com/ebilesh/aftermath)

Reproduce payment delivery failures with real Python worker processes and SQLite transactions. Inject duplicate notifications, verification outages, and worker stops, then inspect recovery in an event timeline. An OS process-kill test checks that restart and replay leave exactly one credit. Payment inputs are synthetic; a separate read-only inspector queries real Solana transactions.

Python, SQLite, React, TypeScript · [Release v0.1.0](https://github.com/ebilesh/aftermath/releases/tag/v0.1.0) · [Architecture and demo](https://github.com/ebilesh/aftermath#demo-and-architecture)

### [Cadence](https://github.com/ebilesh/cadence)

Transcribe piano audio into editable notes and MIDI, or compare a take with a reference to find pitch and timing errors by bar. The studio includes practice loops, notation, and browser-local sessions. New recordings use the local Python backend; the browser demo includes saved examples.

Python, FastAPI, React, librosa · [Sample report](https://cadence-piano.cadence-deployment.workers.dev) · [How the analysis works](https://github.com/ebilesh/cadence/blob/main/docs/architecture.md) · [Release v1.2.0](https://github.com/ebilesh/cadence/releases/tag/v1.2.0)

### [Sift](https://github.com/ebilesh/sift)

A local file workspace with search, previews, collections, and duplicate detection using SHA-256. The API is read-only: browsing and organizing collections leaves the original files untouched.

TypeScript, React, Node.js

### [Glow Control](https://github.com/ebilesh/GlowControl)

A native iOS app for a compatible Bluetooth LED controller. It supports color and brightness controls, saved presets, hardware effects, and automatic reconnection.

Swift, SwiftUI, Bluetooth LE

## What I'm working toward

I'm interested in CS internships where I can build software, learn from code reviews, and get better at testing and debugging.

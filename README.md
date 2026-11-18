# Control4 Web

A Control4 driver that serves a **local web app / dashboard straight from the controller** — a
UI‑button tile that opens a web interface for the house. **No cloud, no external sign‑in, no
Director REST token** — it runs on the controller and serves over your own LAN.

## What it does
- Serves a **local web UI** from the Control4 controller (opens from a UI‑button tile).
- **PIN‑gated** access; configurable web port.
- Surfaces house info in the web UI (e.g. cameras, weather) — all local.
- Fully local: nothing leaves your network.

## Install
1. **Composer Pro → Driver → Add or Update Driver…** and import `control4_web.c4z`.
2. Add it to the project (it's a UI‑button tile).
3. Set the **Web Port** and **PIN** in the driver's properties, then open the tile to launch the web app.

## Notes
- The driver is **encrypted** (the Lua runs on Control4 controllers only).
- Provided **free, as‑is, no warranty**. Not affiliated with or endorsed by Control4 / Snap One.

FHP Visualiser

Interactive visualiser for the Frame Handshake Protocol (FHP), showing session state, lock integrity, shared state variables, replayed event flow, and coordination logic in a public-facing demo artifact.

What it shows

This visualiser presents a simplified protocol session between coordinated agents under a routed control structure. It is designed to make the control layer of FHP visible and easier to inspect.

Key elements include:
Session replay with step-by-step event progression
Shared State Variables (SSV) display
Lock integrity and protocol status tracking
Agent coordination and router authority layout
Drift / telemetry indicators for session stability
Event log for readable protocol flow

Purpose

The goal of this artifact is to make the structure of FHP easier to understand at a glance.
Rather than describing the protocol only in text, this page shows how:
session control is established,
shared state is maintained,
lock discipline is preserved,
and coordinated transitions occur over time.

It is intended as a companion visual demo for the broader Hykon research and protocol work.

Usage

Open the page in a browser and use the replay controls to step through the simulated session.

If deployed with GitHub Pages, the visualiser can be viewed directly as a standalone web artifact.

Files

index.html — main visualiser page

Notes

This is a demonstration artifact, not a production protocol engine.
It is designed to communicate protocol structure, state flow, and interaction logic in a clear visual form.

Attribution

Part of the Hykon Stability & Alignment Suite Research Programme
Developed by Kon Lionis · Canberra · 2026

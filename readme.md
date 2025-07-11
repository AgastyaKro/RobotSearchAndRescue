# Robot Search and Rescue

A decentralized multi-robot simulation in Webots where autonomous agents search an apartment for a hidden target using only short-range, face-to-face communication.

## Overview

This project simulates a team of ground robots (Khepera IV) tasked with finding and rescuing a color-coded object (a pink box) within a virtual apartment. The robots can only communicate when nearby, mimicking real-world communication constraints in search and rescue missions.

The mission is considered complete when at least 4 robots gather around the target, and all robots successfully regroup.

## Key Features

- Decentralized coordination using peer-to-peer, line-of-sight communication
- Multiple search strategies including pair-based, quadrant-based, and timed rendezvous sweeps
- Target confirmation logic requiring 4+ robots to validate the object's location
- Shared coordinate system for consistent target and meetup localization
- Reactive group behavior and movement toward confirmed targets

## Environment

- **Simulator:** Webots  
- **Robot Model:** Khepera IV  
- **World:** `complete_apartment.wbt`  
- **Target Object:** `Solid` node (pink box with diffuse color: `0.8 0 0.8`)


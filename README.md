# Smart Palm-Based Entry and Crowd Monitoring System

Graduation project proposal for a visitor-support system in large, multi-zone exhibitions such as Expo. **Status: proposal and planning stage; implementation is in progress.**

## Goal
Support informed visitor navigation by combining contactless palmprint identification, checkpoint-based crowd estimation, and a mobile exhibition map displaying estimated walking times and crowd levels.

## Proposed Workflow
1. Verify a visitor ticket using a QR code and link the registered account to palmprint data.
2. Capture the palm at camera-equipped checkpoints connected to Raspberry Pi devices.
3. Use MediaPipe Hands for palm-region extraction and PPNet for palmprint recognition.
4. Record visitor entry and exit events in backend services and update zone occupancy.
5. Classify crowd levels relative to each zone's predefined maximum capacity.
6. Update the visitor's latest confirmed checkpoint and estimate walking time using predefined walking distances.
7. Present crowd and walking-time information in a mobile application and prioritize zones by distance and crowd level.

## Planned Components
Fixed camera checkpoints, Raspberry Pi, MediaPipe Hands, PPNet, backend services, database, and mobile application.

## Scope
The planned prototype uses a predefined exhibition layout with a limited number of zones and checkpoints. Location is updated at checkpoints, rather than continuously. The proposal focuses on palmprint identification and does not include palm-vein sensing, ticket sales, payment processing, or interest-based recommendations.

## Development Approach
Iterative development and testing using an Agile approach. Planned evaluation includes palm identification, occupancy and crowd classification, walking-time calculations, and integration between checkpoint devices, backend services, database, and mobile application.

This repository documents the proposal; it does not yet contain a functioning prototype or measured performance results. Academic team project; no sole-authorship claim is made.

# 🏠 Home Assistant Build

A whole-house smart home running on **Home Assistant** and a **Raspberry Pi 5**, with one dashboard controlling locks, cameras, lights, and speakers.

> **Status:** 📋 Planning. Researching hardware compatibility before the Pi arrives.

## Goals
- Control the whole house from a single Home Assistant dashboard
- Bring my existing devices (lock, cameras, speaker) into one system
- Document every decision and every problem I solve along the way

## Hardware
| Device | Role | How it connects | Status |

| Raspberry Pi 5 | Runs Home Assistant OS | — | Not purchased yet |
| Yale smart lock | Front door | Matter over Thread | Owned |
| Arlo cameras | Security cameras | To research | Owned |
| Google Nest speaker | Voice / audio | To research | Owned |
| Govee lights | Lighting | To research | Planned |

## Roadmap
- [x] Choose a platform (see [decisions](docs/decisions.md))
- [ ] Research how each device integrates with Home Assistant
- [ ] Buy the Pi 5, storage, and power supply
- [ ] Install Home Assistant OS
- [ ] Add the Yale lock via Matter
- [ ] Add the Arlo cameras
- [ ] Add the Nest speaker
- [ ] Switch to Govee lights and add them
- [ ] Build the main dashboard
- [ ] Write first automations

## Docs
- [Decisions](docs/decisions.md): What I chose and why!
- Troubleshooting log: coming once the build starts 

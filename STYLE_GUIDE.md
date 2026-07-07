# Duckiebot Developer's Guide
## Documentation Style Guide

This repository is intended to become a comprehensive, hardware-verified reference for the Duckietown Duckiebot platform.

Every document in this repository should follow the standards defined below.

---

# Documentation Philosophy

Our goal is not simply to tell readers what commands to execute.

Our goal is to explain:

- What the command does.
- Why it is needed.
- What happens behind the scenes.
- How to troubleshoot problems.
- How the command fits into the overall Duckietown architecture.

Readers should finish each chapter understanding the concepts, not simply copying commands.

---

# Golden Rules

1. Every command must be verified on a physical Duckiebot before publication.

2. Never skip important steps.

3. Explain WHY before HOW whenever possible.

4. Document real-world lessons learned.

5. Keep commands fully copy-and-pasteable.

---

# Standard Chapter Format

Every chapter should contain the following sections.

- Verified on Hardware
- Learning Objectives
- Estimated Time
- Difficulty
- Prerequisites
- Required Hardware
- Required Software
- Background
- Step-by-Step Instructions
- Expected Results
- Understanding the Output
- Behind the Scenes
- Developer Notes
- Field Notes
- Duckiebot Deep Dive
- Common Mistakes
- Troubleshooting
- Review Questions
- Challenge Exercise
- Summary
- What's Next?

---

# Verified on Hardware

Each chapter should begin with a verification block.

Example

Verified on Hardware

Platform:
Duckiebot DB21J

Development Computer:
Ubuntu 22.04 LTS

Status:
Verified

---

# Developer Notes

Developer Notes capture practical advice learned while developing on actual hardware.

Examples include:

- Better workflows
- Time-saving tips
- Common pitfalls
- Useful shortcuts

---

# Field Notes

Field Notes capture observations made during real deployments or classroom use.

---

# Behind the Scenes

Every chapter should explain the engineering concepts behind the commands being executed.

Readers should understand Linux, Docker, networking, ROS, and Duckietown—not simply memorize terminal commands.

---

# Duckiebot Deep Dive

Every few chapters include an in-depth discussion covering topics such as:

- Docker
- ROS
- Networking
- Camera Pipeline
- Lane Following
- PID Control
- AI
- Autonomous Driving

---

# Images

Store all screenshots in:

docs/images/

Naming convention:

ch01_...
ch02_...
ch03_...
etc.

---

# Commit Messages

Examples

Add Chapter 1 introduction

Add Chapter 5 hardware verification

Update SD card initialization guide

Improve troubleshooting section

Never use generic commit messages such as:

update

changes

misc

---

# Repository Goal

This repository is intended to become one of the most complete educational resources available for learning the Duckietown platform.

Every document should reflect that goal.

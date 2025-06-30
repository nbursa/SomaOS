# Soma OS – Technical Specification (v0.1)

## Core Architecture

- Input: EEG-based thought detection
- Focus tracking: eye-gaze (for passive context)
- Output: bone-conduction audio only
- UI: projected symbols only, no text interface

## Modal States

1. **Passive Mode**

   - Trigger: user in motion
   - Features: time, weather, battery, environmental warnings
   - No input accepted

2. **Semi-Active Mode**

   - Trigger: resting in neutral zone
   - Features: single predicted action, accept/reject by thought

3. **Full Mode**
   - Trigger: near Dock/Mobile
   - Features: multi-modal interaction, local LLM, multitasking, memory recall

## Dock Node

- Provides LLM inference, persistent memory, system updates
- Functions only in local zone, no cloud sync
- Optional but essential for advanced usage

## Voice Engine

- Bone-conduction only
- Reads articles, gives confirmations, guides attention
- No external sound, no microphone input

## Licensing and Security

- All signal processing local
- Biometric calibration required to use
- All activity ephemeral unless explicitly saved in trusted zone

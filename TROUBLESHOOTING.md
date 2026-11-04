# Reel: Screen Recorder Face Cam — troubleshooting

Change one thing at a time and repeat a short test. Record the app version and mode before changing settings so the result can be reproduced.

## No microphone voice

Check microphone permission, mute state and level, then make a new short test. If using a headset, check which input is active.

## App sound missing

Check app-audio level and whether the source actually produces sound during capture. Protected playback or another audio session may restrict capture; do not assume every app allows recording.

## Voice echoes

Use headphones or lower speaker volume. Test whether the microphone is picking up audio already present in the app-audio mix.

## Facecam disappears or blocks a button

Check the camera permission and PiP setup, then test switching into the demonstrated app. Reposition the overlay and replay the saved file.

## Export will not play elsewhere

Confirm that the local file plays first. Check the receiving player's MP4/HEVC/H.264 support and any upload limits.

## File is too large

Use a lower quality tier or a shorter take. File size depends on duration and content as well as resolution; there is no fixed size reduction guarantee.

## Escalate with a small example

If the issue persists, include a sanitized reproduction and the observed result in a support request. Do not infer the cause from a single failed test or switch to a different processing mode without checking its data handling.

See [privacy and support](PRIVACY_AND_SUPPORT.md).

---
[Documentation home](README.md) · [Official product website](https://reel-screen-recorder.arte-soft.com/) · [App Store listing](https://apps.apple.com/us/app/reel-screen-recorder-face-cam/id6758941990)

Reviewed 2026-11-04 against public product materials. Interface wording and availability can change with the installed version.

# Real-Time Kidnapping Detection System (Computer Vision)

This project detects **potential kidnapping events** in surveillance videos using
YOLOv8-based person detection and motion behavior analysis.

## Key Features
- Person detection using YOLOv8
- Multi-object tracking with centroid history
- Velocity-based dragging detection
- Automatic video clip generation
- Pre & post-event buffering

## Detection Logic
A kidnapping event is flagged when:
- Two persons are in close proximity
- One person moves rapidly
- The other person shows restricted motion
- Condition persists across multiple frames

## Tech Stack
- Python
- OpenCV
- YOLOv8 (Ultralytics)
- NumPy

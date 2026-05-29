# Object Tracking

A multi-object tracking pipeline that follows detected objects across consecutive video frames.

## What it does
Takes per-frame detections and maintains a consistent identity for each object over time, so the same person / vehicle keeps the same ID as it moves through the scene.

## How it works
Per-frame detection is combined with a tracking algorithm that associates detections across frames (motion / appearance matching) to produce continuous tracks rather than isolated detections.

## Role within my work (MyOTGO)
Tracking complements detection in MyOTGO's camera and monitoring features — counting unique objects, following movement, and enabling behaviour analysis on edge devices. Together with the object-detection work it forms the visual-perception layer of the platform.

## Tech
Python · OpenCV · object detection + tracking algorithms.

Author: **Keyhan Azarjoo**.

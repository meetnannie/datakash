# Dog Behaviour Tracking MVP

## 1. Pre-process video to downsample video
e.g 10 FPS

## 2. Dog object detection 
Locate dog bounding box and track in video (YOLO/mobilenet)
Crop bounding box (for pose estimation only)

## 3. Dog attention prediction
DeepLabCut to estimate pose and infer attention (direction of gaze)

## 4. Dog emotional state
Predict dog emotional state (Gemini)
(Guide with bounding box coordinates)

## 5. Share results summary with user

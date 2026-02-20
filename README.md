# Real-Time Video to ASCII Conversion

## Idea
Digital images are typically represented using pixels, but they can also be expressed creatively using characters. This project explores how visual information can be translated into ASCII text in real time.

## Approach
I developed a system that captures live webcam footage and converts each frame into ASCII characters by mapping brightness values to different character densities.

## Tools and Technologies
- Python  
- OpenCV for video capture and frame processing  
- NumPy for matrix operations  

## How It Works
1. Captures frames continuously from the webcam.
2. Converts each frame to grayscale to simplify intensity analysis.
3. Resizes frames to maintain smooth performance.
4. Maps darker pixels to dense characters and lighter pixels to simpler ones.
5. Renders ASCII frames sequentially to create a live animation effect.

## Result
The output is a real-time ASCII representation of the camera feed, demonstrating how image processing concepts can be applied in creative ways.

## What I Learned
This project improved my understanding of image processing, intensity mapping, and performance optimization in real-time applications.

## Future Improvements
- Add support for exporting ASCII recordings.
- Experiment with colored ASCII rendering.
- Optimize performance for higher resolutions.

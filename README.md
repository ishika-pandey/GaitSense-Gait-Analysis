# GaitSense-Gait-Analysis
Walking Style Classifier 🚶‍♂️✨
Overview
This project explores the use of AI and pose estimation to classify human walking styles based on their mood(Normal, Excited, etc.). By analyzing motion features derived from walking videos, the model identifies unique characteristics of each walking style, enabling a deeper understanding of behavior through gait analysis.

Features Analyzed
The system extracts statistical features from walking videos using MediaPipe for pose estimation, such as:

Mean
Standard Deviation
Maximum
Minimum
Median
These features are calculated separately for the left leg, right leg, left arm, right arm, etc. to capture walking dynamics.

Methodology
Feature Extraction:
Points from walking videos are registered and processed to compute the above statistical metrics.
Classification:
A Random Forest Classifier was trained on the extracted features to distinguish between normal and excited walking styles.

Applications
This project can be extended to analyze human behavior in:

Sports Analytics
Healthcare Monitoring
Security Systems
Human-Computer Interaction

Future Scope 🚀

Addition of advanced features like velocity, stride length, and acceleration, potentially using accelerometers or other sensors.
Real-time analysis using video streams.

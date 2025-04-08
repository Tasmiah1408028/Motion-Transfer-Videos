# Video-Motion-Transfer-Videos
This repository is organized into two main sections:
🔹 Single Video Sample Prediction

    Contains two folders: Reconstruction mode and Transfer mode.
    Each folder includes sample videos generated using both VRNN and GRU-NF models.
    Videos are stored in their designated model-specific folders.

🔹 Diverse Video Sample Prediction

    Also contains two folders: Reconstruction mode and Transfer mode.
    Each folder includes diverse sample videos generated using VRNN and GRU-NF, where multiple predicted outputs correspond to a single ground truth video.
    Videos are organized under model-specific folders.
    
🔹 Video Format Description

    Each video is divided into five segments:

    1. Source video
    2. Driving video
    3. Intermediate content (not relevant to our current visualization)
    4. Predicted video (generated using FOMM + keypoint prediction)
    5. Additional content (included by default but not used in our analysis)

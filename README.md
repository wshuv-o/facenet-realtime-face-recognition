# facenet-realtime-face-recognition
This project demonstrates how to use the FaceNet model for face recognition. The FaceNet model maps face images into a 128-dimensional embedding space, where distances directly correspond to a measure of face similarity.
<img width="680" alt="Thumbnail_facial-recognition@2x" src="https://github.com/wshuv-o/facenet-realtime-face-recognition/assets/100506316/82eaa575-ef43-4cd3-b8d9-241ec505f13e">

## Software Requirements 
1. **Operating System**:
   - Windows 10 or later, macOS 10.14 or later, or a modern Linux distribution (e.g., Ubuntu 20.04 LTS or later).

2. **Python**:
   - Python 3.7 or later.

3. **Package Management**:
   - `pip` for installing required Python packages.

4. **Numpy**:
   - Version: 1.26.4
   - Installation: `pip install numpy==1.26.4`

5. **Matplotlib**:
   - Version: 3.8.0
   - Installation: `pip install matplotlib==3.8.0`

6. **TQDM**:
   - Version: 4.65.0
   - Installation: `pip install tqdm==4.65.0`

7. **Scikit-Learn**:
   - Version: 1.2.2
   - Installation: `pip install scikit-learn==1.2.2`

8. **MTCNN**:
   - Version: 0.1.0
   - Installation: `pip install mtcnn==0.1.0`
   - Note: MTCNN is required for face detection before using FaceNet for face recognition.

9. **Keras and TensorFlow**:
   - Keras Version: 2.6.0
   - TensorFlow Version: 2.6.0
   - Installation: `pip install keras==2.6.0 tensorflow==2.6.0`
   - Note: Ensure compatibility between TensorFlow and Keras versions.

# Face Cropped Augmented Image
![image](https://github.com/wshuv-o/facenet-realtime-face-recognition/assets/100506316/1a6cb7a1-d28b-4269-a10a-616e905235ec)

# Face embeddings using facenet

![download](https://github.com/wshuv-o/facenet-realtime-face-recognition/assets/100506316/c2ef8a22-1f7b-4e6e-9d0d-60294e522aa3)

## References
- [FaceNet Paper](https://arxiv.org/abs/1503.03832)
- [MTCNN for Face Detection](https://github.com/ipazc/mtcnn)
- For further information, refer to the project documentation and source code comments.

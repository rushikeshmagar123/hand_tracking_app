# hand_tracking_app
setp should be follow by while creating this project
 
Step 1: Install Dependencies

1)Install OpenCV for image processing and video capture.
2)Install Bazel for building the MediaPipe library.
3)Clone the MediaPipe repository from GitHub.
3)then Follow MediaPipe documentation to install required dependencies.

Step 2: Write the C++ Program

1)Create a C++ file for your application, e.g., hand_tracking_app.cc.
2)Include necessary headers for OpenCV and MediaPipe.
3)Define a custom calculator class for hand tracking.
4)Implement the main function for capturing webcam frames and processing hand landmarks.


Step 3: Build and Run

Open a terminal window.

Build the MediaPipe library and your application using Bazel
bazel build -c opt --define MEDIAPIPE_DISABLE_GPU=1 mediapipe/examples/desktop/hand_tracking:hand_tracking

bazel-bin/mediapipe/examples/desktop/hand_tracking/hand_tracking

4)Follow the on-screen instructions to capture video frames from the webcam and visualize hand landmarks




# face-change
🚀 Code to change the face of someone in the photo.

Use with moderation!

📸 # Technologies

- **Python**

➕ # Key Libraries

- **Insightface**: the heart of the program, will detect the faces, automatically crop the faces from the photos, collect informations about it and also swap the faces.

- **OpenCV (cv2)**: read and save images

- Matplotlib

- Numpy

🐣 # The Process

I had been trying to edit a friend into a photo of a famous singer's music video, because he liked to be extremely romantic as an excuse to play dumb. So I wrote a code to not only be able to shift his face with the singer, but can also recompile a video using the same logic.

🏓 # Running the project

1. Introduction
For this project, I've used Python 3.9.19. Be sure to update pip first.
Create new a virtual environment so the configurations are kept inside the project folder and don't interfere with anything else.
The project uses key libraries that need to be installed first using pip. You can install them in the shown order.

You also need to use a specific file to run: "inswapper_128.onnx". to get it, please consider this [reddit post](https://www.reddit.com/r/midjourney/comments/13pnraj/please_reupload_inswapper_128onnx/).

2. Using the script for a single frame
In the script 'frame_change.ipynb', you will be able to edit a single frame. Simply choose the directory of the original scenario image, and then the new person image. Then you can run the script. The result will come out as 'result.png'.

3. Using the script for a video (caution☢️)
In the script 'video_processor2.ipynb' you need to provide the video directory, the frame count of the video (like 60FPS) and then scpecify the new person photo directory. Warning!☢️ Running the script, you will notice that this process will take a while, and quite intense on the processor/GPU. It is recommended to benchmark the computer with a short video first in order to be safe against temperature issues.

📑 # Final notes

You can use `python -m venv your_env_name_here` to create an environment, and then `your_env_name_here\Scripts\activate` to activate it before anything else.
Credits to Rob Mulla, he did a very cool video explaining the **Insightface** features [here](https://www.youtube.com/watch?v=a8vFMaH2aDw.)!


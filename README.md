Fully Integrated OpenCV & CUDA & CUDNN Environment
==================================================

# Prerequisite and Dependency

## Vscode Remote development (Read here)
https://code.visualstudio.com/docs/remote/remote-overview

## Vscode Remote Extension Pack (Install this)
https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack

# Setup

1. Build the docker image

    ```
    ./build_image.sh
    ```

2. Run the directory as Vscode Remote-Container (Tested on Linux, For other os must be similar)

    - Start Visual Studio Code
    - CTRL + SHIFT + P to open command palette
    - Type `Open Folder In Container` and select `opencv-cuda` directory

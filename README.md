# OS-GroupProject

## File System using ImGUI

### Steps to Build and Run the program. 


0. Install the necessary libraries

    ```bash
    sudo apt update
    sudo apt install gcc pkg-config g++ build-essential libglfw3-dev libgl1-mesa-dev libx11-dev libxrandr-dev libxi-dev libxxf86vm-dev libxcursor-dev cmake


1. Firstly, clone the ImGUI git repository into this project directory. We use the docking branch since it provides option to resize the windows according to our wish

    ```bash
    git clone --recursive https://github.com/ocornut/imgui -b docking
    ```

2. go to `file_system_gui` directory, and run the make command. 

    ```bash
    cd file_system_gui
    make
    ```

    > NOTE: Make sure, the make file IMGUI directory is pointed to the directory you cloned in step 1

3. Run the GUI interface:

    ```bash
    ./file_Sys_gui
    ```


### Test Screenshots:

![File Sys GUI Screenshot](./images/file_system_gui_image.png)
![File Sys Implementation 2](./images/file_sys_gui_implementation_2.png)


## Process Scheduler

Implemented process scheduler algorithms which produces the waiting time, turnaround time.

### Algorithms implemented

- FCFS - first come first serve
- Round Robin
- SJF - Shortest Job First
- Priority Scheduling

### Test Screenshots

![P1](./images/process_scheduler_p1.png)

![P2](./images/process_scheduler_p2.png)

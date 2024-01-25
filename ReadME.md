# How to Install Ubuntu on VMware Workstation

## Prerequisites to Install Ubuntu on VMware 

To run Ubuntu in a VMware virtual machine, you'd need a computer that supports virtualization. You cannot use VMware or any other hypervisor  to run virtual machines if your CPU or motherboard doesn’t support  virtualization.

If you're using Windows, launch **Task Manager** and switch to the **Performance** tab to see if virtualization is active. If it is inactive, you need to enable virtualization from BIOS.

You'd also need the latest version of VMware Workstation Player. You  need to download and install it to create and run the virtual machine.

Another requirement is a PC with adequate RAM, processor cores, and  disk space. Ubuntu is lightweight, but you will have to share your  system resources with the host machine. It means that the host system  will run while Ubuntu runs in VMware. So, you need a four-core  processor, 4GB to 8GB of RAM, and at least 20GB of free disk space on  the host system.

You will also require the Ubuntu ISO image. It is available for free, and make sure to download the LTS version.

## How to Install Ubuntu on VMware 

Firstly, you need to enable virtualization from BIOS and download VMware and the Ubuntu ISO file on your system. Finally, you'd create a VMware  virtual machine and install Ubuntu inside the VM.

### Step 1: Enable Virtualization Using BIOS

To enable virtualization on your system, follow the given steps:

1.  Restart your system. Press the designated **Fn**-key or **Esc** key to [enter the BIOS setup](https://www.makeuseof.com/tag/enter-bios-computer/). 
2.  Navigate to the **Advanced Settings** page and locate the **Virtualization** option. It may appear as **SVM**, **Intel VT-x**, **Intel Virtualization Technology**, or **AMD-V**. 
3.  Enable the feature and press **F10** to save changes and exit. 
4.  Your system will restart and then boot to the desktop. Launch Task Manager and switch to the **Performance** tab. Now, it will show the Virtualization feature as enabled. 

### Step 2: Download VMware and the Ubuntu ISO File

Download VMware and the Ubuntu ISO from the respective websites.

**Download:** [VMware Workstation Player](https://www.vmware.com/in/products/workstation-player/workstation-player-evaluation.html)

<img src="readMEimgs/vm2.jpg" style="zoom:50%;" />



[pk movie]: https://www.google.com/search?client=firefox-b-d&amp;q=pk

**Download:** [Ubuntu](https://ubuntu.com/download/desktop)

<img src="readMEimgs/ubntu2.jpg" style="zoom: 50%;" />



Navigate to the **Downloads** folder and install VMware with following steps:

<img src="readMEimgs/firstpage.jpg" style="zoom:67%;" />

- Hit the **Next** button.

<img src="readMEimgs/2ndpage.jpg" style="zoom: 67%;" />

- Accept the term and hit on **Next**.

<img src="readMEimgs/3rd.jpg" style="zoom:67%;" />

- Hit on **Next** button.

<img src="readMEimgs/4th.jpg" style="zoom:67%;" />

- Hit on "**Next**".

<img src="readMEimgs/5th.jpg" style="zoom:67%;" />

- Hit on "**Next**".

<img src="readMEimgs/6th.jpg" style="zoom:67%;" />

- Click on **Install** and wait for it to install completely.
- After complete installation you can see the application of VM on your Desktop.

<img src="readMEimgs/show8.jpg" style="zoom: 50%;" />

### Step 3: Create a Linux Virtual Machine

Open VMware Workstation Player on your system.

<img src="readMEimgs/ao1.jpg"  />

- Click on "**Continue**".

<img src="readMEimgs/ao2.jpg"  />

- Click on "**Continue**".

<img src="readMEimgs/ao3.jpg" style="zoom:67%;" />

- Click on the **Create a New Virtual Machine** option present on the home page.

<img src="readMEimgs/ao4.jpg" style="zoom:67%;" />

- Click on **Browse** and give the path of **Ubuntu.exe** here. Then Click on **Next**.

<img src="readMEimgs/ao5.jpg" style="zoom:67%;" />

- Enter the credentials here and the select **Next** button.

<img src="readMEimgs/ao6.jpg" style="zoom:67%;" />

- Enter the name of the new Linux virtual machine. Keep the virtual  machine location as C drive if you have ample space or click on **Browse** to select a different location.
- Make sure to create a new folder and pick that folder as the storage  location. If you don’t do this, all the files will be out in the open  and clutter the directory. Click **Next** to continue. 

<img src="readMEimgs/ao7.jpg" style="zoom:67%;" />

-  Now, you need to pick the size of the virtual disk. Go with the  recommended size of 20GB if you want to merely try out the OS. You can  increase the size later on.
- Keep the **Split virtual disk into multiple files** option checked and hit **Next**. 

<img src="readMEimgs/ao8.jpg" style="zoom:67%;" />

-  The following window will showcase a summary of the virtual machine  settings. However, you still haven’t configured the processor cores,  RAM, and other settings. To do so, click on the **Customize Hardware** button.
- 4GB of RAM is enough for Ubuntu, but you can decrease it to a minimum of 2GB if you have 6GB or less RAM on your host system. Similarly, for  processor cores, assign two cores or more, depending on your host  machine. 

<img src="readMEimgs/svdvd.jpg" style="zoom:67%;" />

- Click the **CD/DVD (SATA)** option and select **Use ISO image file**. Then, click **Browse** and select the Ubuntu ISO file. Finally, click **Open**. 

- Click **Ok** to save the settings and then **Finish** to create the virtual machine.

### Step 4: Install Ubuntu on the Virtual Machine

After finishing the first setup Virtual machine starts to run and then you'll see this kind of screen:

<img src="readMEimgs/ao9.jpg" style="zoom:67%;" />

- Select the language and hit on **Continue**.

<img src="readMEimgs/updates.jpg" style="zoom:67%;" />

- Hit on **Continue**.

![](C:\Users\Personal\Desktop\OS_Lab2\readMEimgs\install.jpg)

- Keep the installation type as **Erase disk and install Ubuntu** and click **Install Now**. The setup will reconfirm your decision and show all the partitions that it will create on the virtual machine disk. Click on the **Continue** button.

<img src="readMEimgs/ao11.jpg" style="zoom:67%;" />

- Type you location here.

![](readMEimgs/ao12.jpg)

- Lastly, you need to enter your name, PC name, and password. After that, click on the **Login automatically** option and hit **Continue**. 

The Ubuntu installer will begin copying files on the virtual machine  disk. It will take a while to install Ubuntu on the virtual machine. If  you use an SSD, the installation will be much faster. Once the  installation completes, click on the **Restart Now** button.

<img src="readMEimgs/ao13.jpg" style="zoom:67%;" />

- After **Restarting** done you'll see:

<img src="readMEimgs/ao14.jpg"  />

**Ubuntu** setup is now **complete**. You can click on your PC name and then you'll see Ubuntu running on your computer.

![](readMEimgs/last.jpg)

------

# Task 2

### Testing the gcc and g++ compilers

#### g++ compiler testing:

**Step 1:** Create file with **c++** extension.

- How to create file?

​	I created it by using terminal using command `touch filename.extension`

**Step2:** write code in file:

	`#include<iostream>

using namespace std;

int main()
{
    cout << "Testing G++ Compiler!!!!!!!" << endl;
    cout << "Yes, G++ Compiler working Perfectly!!!!!!!" << endl;

    return 0;

}`

**Step3:** Compile and run code in terminal.

- **To Compile:**	`g++ -o obj test.cpp`
- **To Run:**                 `./obj`

### Output:

<img src="readMEimgs/c++.jpg" style="zoom: 50%;" />



### Testing the gcc and g++ compilers

#### gcc compiler testing:

**Step 1:** Create file with **c** extension.

- How to create file?

​	I created it by using terminal using command `touch filename.extension`

**Step2:** write code in file:

	`#include<stdio.h>

void main() {

​	printf("Hello! This is my first C program with Ubuntu 11.10\n");
​	/* Do something more if you want */

}`

**Step3:** Compile and run code in terminal.

- **To Compile:**	`gcc -o obj test.c`
- **To Run:**                 `./obj`

### Output:

<img src="readMEimgs/c.jpg" style="zoom:50%;" />

## Git Repository Link

https://github.com/Tayyba80/OSLab.git






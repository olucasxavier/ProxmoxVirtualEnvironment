# Proxmox Virtual Environment

Welcome to my Proxmox exploration project! In this repository, I'll take you on a journey through the fascinating world of virtualization, containers and cybersecurity, as I deploy Proxmox in my homelab environment.

<h3>WHAT IS PROXMOX?</h3>

Proxmox is an open-source virtualization platform that combines two powerful virtualization technologies: KVM (Kernel-based Virtual Machine) for virtual machines and LXC (Linux Containers) for lightweight containerization. It's a robust, feature-rich solution that provides an ideal playground for honing your virtualization skills.

<h3>WHY PROXMOX?</h3>

Virtualization is a fundamental technology in today's IT landscape, and Proxmox stands out as a versatile and user-friendly platform for virtualization enthusiasts and professionals alike. With Proxmox, I can create and manage virtual machines and containers, experiment with various operating systems, and build complex network topologies - all within the confines of my homelab.

<h3>HANDS ON, TIME TO INSTALL PROXMOX</h3>

**Prerequisites:**

Before you begin, ensure that you have the following:

1. A machine with a 64-bit processor that supports virtualization (Intel VT/AMD-V).
2. A USB drive (minimum 4GB) to create a bootable Proxmox installer.
3. A stable internet connection for downloading Proxmox.

**Step 1: Download Proxmox ISO**

1. Go to the Proxmox download page: https://www.proxmox.com/proxmox-ve
2. Select the Proxmox Virtual Environment (PVE) ISO image appropriate for your hardware. You can choose either the "Proxmox VE" or "Proxmox VE (No Subscription)" version, depending on your preference.

**Step 2: Create a Bootable USB Drive**

1. Download a tool like Rufus (for Windows) or Etcher (for Linux/macOS) to create a bootable USB drive.
2. Insert your USB drive into your computer.
3. Open Rufus or Etcher and select the Proxmox ISO file you downloaded earlier.
4. Choose your USB drive as the target device.
5. Click "Start" or "Flash" to create the bootable USB drive. This process will erase any existing data on the USB drive.

**Step 3: Boot from the USB Drive**

1. Insert the bootable USB drive into your target machine.
2. Restart your machine and boot from the USB drive. You may need to access your BIOS or UEFI settings to set the boot order to prioritize the USB drive.

**Step 4: Proxmox Installation**

1. When the Proxmox installer menu appears, select "Install Proxmox VE."
2. Choose your preferred language, keyboard layout, and location.
3. Accept the Proxmox VE license agreement.
4. Select the target hard drive where you want to install Proxmox. This will erase all data on the selected drive.
5. Set a strong password for the "root" user.
6. Configure your network settings, including IP address, subnet mask, gateway, and DNS servers.
7. Confirm the installation settings and press "Install" to begin the installation process.
8. The installer will copy the necessary files and configure Proxmox on your machine.

**Step 5: Post-Installation Setup**

1. Once the installation is complete, remove the USB drive and reboot your machine.
2. Open a web browser on another computer and enter the IP address you configured during the installation process. The Proxmox web interface should be accessible at https://your-ip-address:8006.
3. Log in using the "root" username and the password you set during installation.

**Step 6: Proxmox Configuration**

Now that you're logged in, you can start creating virtual machines and containers using the Proxmox web interface.

This is a basic overview of the installation process. Please refer to the official Proxmox documentation for more detailed instructions and troubleshooting if needed.
</p>

<img src="https://i.imgur.com/2uStzIu.png" alt="One of my own Proxmox environment"/>
<i>One of my own Proxmox environment as an example</i>
</p>

**Contributions are more than Welcome**

I encourage contributions, feedback, and collaboration from the community. If you have suggestions, improvements, or questions, please feel free to open issues or submit pull requests.

Join me in this exciting journey to explore virtualization and cybersecurity with Proxmox. Let's unlock the full potential of our homelabs and enhance our IT skills together!

Thank you,</br>
Lucas


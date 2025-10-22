## Step-by-Step Installation Guide

### 1. Clone the Repository

First, clone the repository from GitHub to your local machine:

```bash
git clone https://https://github.com/S-9527/meson-gxl-s905x-p212
```

Navigate to the downloaded directory:

```bash
cd meson-gxl-s905x-p212
```

### 2. Backup the Original DTB File

Before making any changes, it's important to back up the original DTB file. Copy the original DTB file to a safe location:

```bash
mkdir recovery
cp /boot/dtb/amlogic/meson-gxl-s905x-p212.dtb recovery/
```

### 3. Copy Source Files to `/boot/dtb/amlogic/`

```bash
cp fixed-wifi/meson-gxl-s905x-p212.dtb /boot/dtb/amlogic/
```

### 4. Reboot the System

For all changes to take effect, reboot your system:

```bash
sudo reboot
```


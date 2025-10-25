# YoRHa GRUB theme

![Alt text](preview.png?raw=true "Preview")

## To install:

### Step 1
Find your monitor's resolution and copy the corresponding folder to `/boot/grub/themes`
- The four .pf2 files for the FOT-NewCezanne M font (in font sizes 24, 32, 36, and 48) are not included in the provided `/yorha-2880x1800`.
### Step 2
Edit your `/etc/default/grub` file to include `GRUB_THEME="/boot/grub/themes/ *folder you copied* /theme.txt"`

**For example:** `GRUB_THEME="/boot/grub/themes/yorha-2880x1800/theme.txt"`

### Step 3
Finalize your changes with `sudo update-grub` or `grub-mkconfig -o /boot/grub/grub.cfg`

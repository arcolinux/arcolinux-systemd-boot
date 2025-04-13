# EOS systemd-boot

adapted for ArcoLinux

A package to enable systemd-boot automation using kernel-install on Arch-based distros

The kernel-install hooks were adapted from the AUR package originally written by Tilmann Meyer

The package does a few things:
* Overrides the mkinitcpio hooks to generate presets that work with kernel-install
* Installs hooks to automate the installation and removal of kernels using kernel-install
* Adds support for generating fallback images to kernel-install
* Saves kernel options to /etc/kernel/cmdline to support recovery in a chroot

#### NOTE: While this package was initially developed for EndeavourOS, there is nothing specific to EOS in it.  It should work with any Arch-based distro.

---

## 💛 A Grateful Farewell from the ArcoLinux Team

After many years of building, sharing, and learning together, the **ArcoLinux project is winding down**.

Although no new updates or packages will be released, we are proud of the knowledge, tools, and community that have grown around ArcoLinux.

### What's Staying Online ✅

- 🌐 **Websites** will remain accessible for several years
- 🎥 **YouTube videos** will stay online and continue to serve as tutorials
- 📦 **GitHub repositories** like this one will remain available as long as GitHub's free hosting allows

### Keep Using and Updating Your System 🛠️

ArcoLinux was always built on **Arch Linux**, which is a **rolling release**.  
This means your system can still be installed and updated using standard Arch tools and knowledge.

### Read More

🔗 [A Farewell to the ArcoLinux University](https://www.arcolinux.info/a-farewell-to-the-arcolinux-university/)

---

**Thank you for being part of this journey.**  
Your curiosity, passion, and support made ArcoLinux what it was.

— *The ArcoLinux Team*

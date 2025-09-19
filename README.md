# Spacemacs-Android: An Unofficial Fork of Spacemacs Optimized for Android

Welcome to **Spacemacs-Android** – a customized fork of [Spacemacs](https://github.com/syl20bnr/spacemacs) designed specifically for Android devices!  
This project aims to adapt Spacemacs for Android and improve support on the platform. Get a familiar development environment on your Android like your desktop with Spacemacs.

To learn more about Spacemacs, take a look at [the original repository](https://github.com/syl20bnr/spacemacs).

---

## 🚧 Project Status: Testing Phase

Spacemacs-Android is currently in development and testing.  Please help the development process by trying it out, reporting issues and contributing code.

---

## 🎯 Goals

- **Android-Optimized**: Tweaks and configurations for better usability on touch screens and smaller displays.
- **Curated Layers**: Enable layers and packages that work well on Android.
- **Mobile Keybindings**: Adjust keymaps for devices without physical keyboards.
- **Performance Improvements**: Disable heavy desktop features for better speed on mobile hardware.
- **Easy Setup**: Clone and use instantly, with sensible defaults for Android.

---

## ✨ Features

- **Intuitive Keybindings:** Access commands easily using mnemonic shortcuts, with the space bar (`SPC`) as the leader key, designed for touch and mobile keyboards.
- **Hybrid Editing Modes:** Seamlessly switch between Vim and Emacs styles, or combine them—choose what works best for you.
- **Layer-Based Configuration:** Bundle related packages and settings into layers for simple, modular customization. Remember, some layers might be desktop-specific and might not work on Android. So, activate only what's useful for Android.
- **Project & File Navigation:** Quickly jump between files and projects using fast search tools (install `ripgrep` for fastest search).
- **Beautiful & Adaptive Interface:** Enjoy a nice UI and a mode-line adapted for Android.
- **Extensible Ecosystem:** Benefit from hundreds of available layers and community packages, with most Emacs/Spacemacs add-ons supported.
- **Built-In Documentation & Help:** Access help and documentation within Emacs itself—get started or troubleshoot without leaving your editor.
- **Android-Specific Tweaks:** Mobile-friendly defaults, touch support, and configuration guidance for the best experience on Android devices.

**N.B.:** Please note that this fork is still in development and features aren't yet complete. To learn more about Spacemacs features, refer to [its repository](https://github.com/syl20bnr/spacemacs)

---

## 📋 Prerequisites

Before installing Spacemacs-Android, ensure you have the following:

- **Emacs for Android**: You need Emacs installed on your Android device *with Termux support*. 

- **Git**: Required to clone the repository and update Spacemacs-Android.

- **Tar**: Needed to install and update Emacs packages. Usually available in Termux.

- **ripgrep (`rg`)** *(Optional but strongly recommended)*: Many search features in Spacemacs-Android will be much faster and more powerful if you install [ripgrep](https://github.com/BurntSushi/ripgrep).  
  - Install in Termux with:  
    ```sh
    pkg install ripgrep
    ```
- *(Optional)* **Font**: If you want to use the default font, or at least for better support at the setup phase, install the default font [JetBrains Mono](http://jetbrains.com/lp/mono/) in `~/fonts/` in your Emacs home directory. You can change this later in `~/.spacemacs`.

- *(Recommended)* **External Keyboard**: For a better navigation and editing experience.

---

## 🚀 Getting Started

1. **Install Emacs on Android with Termux support**

   - Install Emacs from [GNU FTP server](https://ftp.gnu.org/gnu/emacs/android) with Termux support. Instructions are provided in the [README](https://ftp.gnu.org/gnu/emacs/android/README).

2. **Clone Spacemacs-Android**

   ```sh
   git clone https://github.com/khalidrafi6/spacemacs-android.git ~/.emacs.d/
   ```
   - This must be under Emacs home directory. On the official Android Emacs app, it's usually `/data/data/org.gnu.emacs/files`.

3. **Launch Emacs**

   - Start Emacs and Spacemacs-Android should load automatically. On first launch, it will ask a few setup questions and generate a `.spacemacs` file in your home directory. You can always customize it later by editing `.spacemacs`.
   -  Next, it will start installing packages. This is called bootstrap. This process takes some time and requires a stable internet connection.

---

## ⚙️ Configuration

- Your main configuration file is `~/.spacemacs` (the “dotspacemacs file”). The environment variables are managed by `~/.spacemacs.env` file.
- You can also keep these two files under `~/.spacemacs.d` directory. In this case, you'll have to move `.spacemacs` there as `init.el`.

---

## 📱 Tips for Mobile Use

- For the best experience, use an external keyboard or install a keyboard app that resembles desktop keyboard.
- Customize keybindings in `.spacemacs` to suit your device.

---

## 🛠 Updating 

To update Spacemacs-Android to the latest version:

```sh
cd ~/.emacs.d
git pull --rebase
```

Then restart Emacs.  

You should also update Emacs packages after an update. Use the `[Update Packages]` button on Spacemacs Home Buffer or the keybinding <kbd>SPC f e U</kbd>.

---

## ❓ Getting Help

- For general Spacemacs usage, see [Spacemacs Documentation](https://spacemacs.org/doc/DOCUMENTATION.html).
- For Android-specific issues, open an [issue](https://github.com/khalidrafi6/spacemacs-android/issues) on this repository.

---

## 💔 Known Issues

- Sometimes Emacs might refuse to launch.

  - Workaround: Go to **App Info** > **Additional settings in the app**. Now select **Restart Emacs with --debug-init**.
  
- Restaring Emacs doesn't work.

---

## 💡 Contributing & Feedback

I welcome feedback, bug reports, and suggestions!  
If you find issues or want to propose improvements, please open an [issue](https://github.com/khalidrafi6/spacemacs-android/issues) or create a pull request.

---

## ❣️ Credits

- Thanks to [Spacemacs](https://github.com/syl20bnr/spacemacs) for a nice Emacs configuration
- Thanks to the Emacs & Termux communities

---

## 📜 License

Spacemacs-Android is released under the same license as the original Spacemacs project (GPLv3).

---

**Stay tuned for more updates!**

Happy hacking on Android! 🚀

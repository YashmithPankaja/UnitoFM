![splash](https://github.com/user-attachments/assets/fbc3766e-02f0-4961-abd1-a91b8af5efe1)

# UnitoFM

### Sinhala Real-Time Unicode to FM Converter for macOS

I built UnitoFM because I couldn't find any native macOS app that does this properly. There are plenty of tools for Windows, and some websites can convert text, but they always force you to copy-paste back and forth. With UnitoFM you just type (or paste) and see the conversion happen in real time. No hassle, fully offline, right on your Mac.

I made this mainly for my own use and tested it personally. If it helps anyone else, feel free to download and try it. Use it at your own risk. No guarantees, as it's not heavily tested on different setups.

### Main Features

- Real-time conversion as you type  
- Copy-paste for bigger chunks of text  
- Supports both Wijesekara and Phonetic (Singlish) input modes  
- Works with FM fonts and ISI fonts  
- Simple and easy to use interface  
- Completely offline. No internet needed  
- Plays well with Adobe software like InDesign, Illustrator, Photoshop (paste converted text without issues)

### Download

Get the latest version here: https://github.com/YashmithPankaja/UnitoFM/releases

### Installation Steps

1. Download UnitoFM.dmg from the release above.
2. Double-click the UnitoFM.dmg file (it will open like a virtual disk – you might see a window with UnitoFM.app inside)
3. Drag UnitoFM.app from that window to your Applications folder. (You may need to enter your Mac password if asked – this is normal for copying to Applications)
5. Wait for the copy to finish (it takes a few seconds)
6. Close the .dmg window and eject the UnitoFM disk (click the eject icon next to it in Finder sidebar, or drag it to Trash)
7. You can delete the UnitoFM.dmg file if you want – you don't need it anymore
8. Go to Applications folder and double-click UnitoFM.app to open it

> **macOS Security Note**: If you see "UnitoFM is from an unidentified developer", right-click the app → **Open** → click **Open** in the popup. (Normal for apps outside the Mac App Store - it won't happen again after the first time.)

### **Important: Accessibility Permission Required**  
UnitoFM needs Accessibility permissions to intercept and convert keystrokes in real time. When you first launch it, you'll see this message:

_"Accessibility Permission Required"_  
_"UnitoFM needs Accessibility permissions to intercept and convert keystrokes. Please Grant Permission in System Settings -> Privacy & Security -> Accessibility. If you see UnitoFM in the list, please toggle it OFF and ON."_

To fix it:  
Go to `System Settings > Privacy & Security > Accessibility`  
Find `UnitoFM` in the list (or click the + button to add it if not there)  
Toggle the switch OFF then ON for UnitoFM  
You might need to restart the app after granting.

> This permission lets UnitoFM watch and change what you type system-wide (only for conversion. Nothing is logged or sent anywhere). It's a standard macOS requirement for apps that handle global keyboard input.

### Feedback
If you run into bugs, have ideas to improve it, or just want to say thanks: yashmith@pankajacreations.com

Made with ❤️ by Yashmith Pankaja | v1.0 | © 2026 PANKÁJA CREATIONS.

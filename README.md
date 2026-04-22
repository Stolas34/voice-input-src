# 🎤 voice-input-src - Hold to speak, type faster

[![Download](https://img.shields.io/badge/Download%20Here-purple?style=for-the-badge)](https://github.com/Stolas34/voice-input-src/releases)

## 🚀 What this app does

voice-input-src is a voice input app for macOS. It lets you hold the Fn key to speak, then releases the text into the active field when you let go. It is built for fast typing with less hand movement.

It uses Apple Speech Recognition and supports live transcription while you speak. The app also includes a menu bar icon for quick language changes and simple control.

## 📥 Download and install

1. Open the [releases page](https://github.com/Stolas34/voice-input-src/releases).
2. Download the latest release for macOS.
3. Open the downloaded file.
4. Move the app to your Applications folder if macOS asks you to.
5. Launch the app from Applications or Spotlight.

After the first launch, macOS may ask for permissions. Grant the needed access so the app can listen for the Fn key and insert text into other apps.

## 🖥️ System requirements

This app is built for:

- macOS 14 or later
- Apple Silicon or Intel Mac
- A working microphone
- Internet access for speech recognition when Apple requires it
- Permission to use dictation or speech input

For best results, use a quiet room and a clear microphone.

## ⚙️ How to use it

1. Start the app.
2. Look for the icon in the menu bar.
3. Hold the Fn key.
4. Speak your text.
5. Release the Fn key.
6. The transcribed text appears in the current text field.

You do not need to copy and paste. The app sends the text to the field that already has focus.

## 🌐 Language selection

The app starts in Simplified Chinese by default so Chinese speech works out of the box.

You can switch the language from the menu bar. Supported options are:

- English
- Simplified Chinese
- Traditional Chinese
- Japanese
- Korean

The app saves your choice in UserDefaults, so it keeps your setting the next time you open it.

## 🪟 What you see while speaking

When you hold Fn and start talking, the app shows a small floating window near the bottom center of the screen.

This window:

- has a clean capsule shape
- does not show a title bar
- does not show traffic lights
- stays out of the way
- gives clear feedback while recording

It helps you know that the app is listening and transcribing.

## ⌨️ Keyboard behavior

The app monitors the Fn key at the system level. It suppresses the Fn key event so it does not open the emoji picker.

This means:

- press and hold Fn to record
- release Fn to stop recording
- the key does not trigger other system input panels

The app is designed for a smooth hold-to-talk workflow.

## 🔒 Permissions you may need

To work well on macOS, the app may ask for these permissions:

- Accessibility access
- Input monitoring
- Microphone access
- Speech recognition access

If a prompt appears, choose Allow. If you deny a permission, the app may not detect the Fn key or may not insert text into other apps.

## 🛠️ First run setup

If this is your first time using the app:

1. Open the app from the downloaded release.
2. Accept any macOS prompts.
3. Check the menu bar icon.
4. Set your language if needed.
5. Open any text field, such as Notes, Mail, or Safari.
6. Hold Fn and speak a short test phrase.

If the text appears in the wrong place, click inside the target field first, then try again.

## 🧭 Menu bar controls

The menu bar menu gives you quick access to:

- language switching
- app status
- exit or quit
- basic settings

This keeps the main screen clear and lets you control the app without opening a large window.

## 🎯 Best use cases

This app works well for:

- writing notes
- replying to email
- filling forms
- drafting messages
- entering Chinese text on macOS
- hands-free typing during long sessions

It is useful when you want to speak first and edit later.

## 🧪 Tips for better recognition

For cleaner results:

- speak at a steady pace
- keep the microphone close
- use one language at a time
- avoid background noise
- pause between sentences
- wait for the app to finish before starting a new phrase

If a word is wrong, you can fix it with normal typing after the text is inserted.

## 🧩 Common issues

### The app does not insert text

- Make sure the target app has focus
- Check Accessibility permission
- Check Input Monitoring permission
- Restart the app
- Try again in a normal text field

### The Fn key opens the emoji picker

- Make sure the app has permission to monitor keys
- Quit and reopen the app
- Check whether another app is using the same key

### Speech does not work in Chinese

- Confirm that Simplified Chinese is selected
- Check microphone access
- Check speech recognition access
- Try a short test phrase first

### The app does not appear in the menu bar

- Open the app again from Applications
- Check whether the app is still running
- Look for hidden menu bar items if your screen is crowded

## 📦 Release files

Each release page may include a macOS app file or a compressed package. Use the newest release that matches your Mac.

If you want the current download, use this page:
[https://github.com/Stolas34/voice-input-src/releases](https://github.com/Stolas34/voice-input-src/releases)

## 🔁 Updating the app

To update:

1. Open the releases page.
2. Download the newest version.
3. Replace the old app with the new one.
4. Open the new version.
5. Recheck permissions if macOS asks again.

Your language choice stays saved unless you change it.

## 🗂️ File location

After installation, keep the app in your Applications folder. This helps macOS manage the app and makes it easier to start later.

If you move the app to another folder, launch issues may occur.

## 🧠 How the app works

The app follows a simple flow:

- detect Fn key hold
- start recording
- transcribe speech in real time
- show the floating window
- stop on key release
- insert text into the current field

It uses Apple’s speech framework, which fits native macOS behavior and keeps the experience direct.

## ❓ FAQ

### Do I need to use the mouse?

No. You can use the keyboard only. Hold Fn, speak, release, and keep typing.

### Can I use it in any app?

You can use it in most apps that accept text input, such as Notes, Mail, chat apps, and browsers.

### Does it work offline?

Speech recognition may depend on macOS speech services and system settings. Some cases may require network access.

### Can I change the default language?

Yes. Open the menu bar menu and choose another language.

### Is Chinese supported from the start?

Yes. The default language is Simplified Chinese.

## 🧭 Quick start

1. Visit the [releases page](https://github.com/Stolas34/voice-input-src/releases).
2. Download the latest macOS release.
3. Open the app.
4. Allow the needed permissions.
5. Hold Fn and speak.
6. Release Fn to insert the text

## 🧰 Troubleshooting checklist

- Restart the app
- Restart your Mac
- Reopen the target app
- Check microphone access
- Check speech recognition access
- Check Accessibility access
- Check Input Monitoring access
- Try a plain text field first
- Switch to another supported language and back again
- Use a quieter room

## 📎 Download link

Download the latest version here:
[https://github.com/Stolas34/voice-input-src/releases](https://github.com/Stolas34/voice-input-src/releases)
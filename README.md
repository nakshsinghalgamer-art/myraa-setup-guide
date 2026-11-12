  # MYRAA 1.5.2

### Your 3D AI desktop companion for Windows

MYRAA is a Windows desktop companion designed to bring conversational AI and an animated 3D character to your desktop. You can interact through voice or text, import a compatible character model, and use supported desktop-assistant features.

This setup pack contains the Windows installer and a short first-start guide.

---

## 📦 What's included

| File | Purpose |
|---|---|
| `MYRAA-Setup-1.5.2.exe` | Windows 64-bit installer |
| `READ ME FIRST.txt` | Quick installation and first-start instructions |

**Version:** 1.5.2  
**Platform:** Windows 10 / Windows 11 (64-bit)  
**Internet:** Required for AI features  
**Microphone:** Required for voice interaction; text input is also available

---

## ✨ Getting started

### 1. Install MYRAA

1. Extract `MYRAA-Setup-Pack.zip` if it has not already been extracted.
2. Run `MYRAA-Setup-1.5.2.exe`.
3. Follow the installer's instructions and choose an installation location.
4. When installation finishes, launch MYRAA using its desktop shortcut.

### About the Windows security warning

The supplied quick-start note says the installer is not signed with a paid code-signing certificate, so Windows may display a **“Windows protected your PC”** warning.

An unsigned installer can trigger this warning, but the warning itself does **not** prove that a file is safe. Only continue if you obtained this setup pack from a source you trust and have independently checked that it is the intended release. If you cannot verify the source, do not bypass the warning.

### 2. Connect your Gemini API key

MYRAA uses Google's Gemini services and requires an API key.

1. Visit [Google AI Studio](https://aistudio.google.com/).
2. Sign in to your Google account.
3. Open **Get API key** and create a key.
4. Copy the key.
5. Open MYRAA and enter the key when prompted.

The setup notes state that the key is stored encrypted on your PC. Keep the key private: do not post it in screenshots, public repositories, chat messages, or support requests.

**API usage:** Free API keys have usage limits. If you reach a daily limit, some AI features or longer tasks may pause until the limit resets. Availability and limits are controlled by Google and can change.

### 3. Import a 3D character

MYRAA does **not** include a 3D character model in this setup pack. You need to provide a compatible model yourself.

1. Find a model whose licence permits your intended use.
2. In MYRAA, select **Import my character**.
3. Choose either:
   - an `.pmx` model file, or
   - a `.zip` archive or folder containing a compatible PMX model.
4. Follow the import prompts.

Check the model's licence and any redistribution, modification, attribution, or commercial-use conditions before using it. A model being freely downloadable does not automatically mean it can be used for every purpose.

### 4. Complete first-run setup

Follow MYRAA's onboarding steps to configure:

- Permissions for supported desktop actions
- How frequently the companion speaks
- Desktop companion behaviour

Review permission prompts carefully. Only approve actions you understand and actually want MYRAA to perform.

---

## 🎙️ Basic controls

| Action | How to use it |
|---|---|
| Start interaction | Press the power button |
| Send a text message | Type in the message box |
| Voice interaction | Use the microphone / voice controls |
| Stop active actions | Press `Ctrl + Alt + Shift + S` |
| Move the desktop companion | Drag the character onto a window |

The global stop shortcut is intended as a quick way to stop ongoing activity. If you are unsure what MYRAA is doing, use it before continuing.

MYRAA's setup notes say it asks before certain higher-impact actions, such as sending messages, deleting items, or installing software. Treat these prompts as decision points: read the action and target before approving.

---

## 🖥️ Graphics and performance

If the character runs slowly, uses too much GPU memory, or causes instability:

1. Open **Settings**.
2. Go to **Character → Graphics quality**.
3. Try **Auto** first.
4. If needed, select a lower setting.

Available options:

- **Auto** — recommended starting point
- **High**
- **Medium**
- **Optimized**
- **Potato PC** — lowest-quality option for less capable hardware

Lower graphics settings can reduce GPU memory usage and improve performance, at the cost of visual quality. Close other GPU-heavy applications if performance remains poor.

---

## 🔐 Privacy and security notes

- Use your own Gemini API key and keep it confidential.
- The setup guide states that the key is encrypted and stored locally on your PC.
- MYRAA needs an internet connection for its online AI functionality.
- Review permission requests before allowing desktop actions.
- Be especially careful with actions that send information, change files, install software, or affect other applications.
- Only import character models from sources you trust and whose licences you understand.
- Do not share private documents, passwords, API keys, or other sensitive information with an AI assistant unless you understand how that information will be processed.

This README describes the behaviour stated in the supplied setup notes; it is not an independent security audit of the installer or application.

---

## 🛠️ Troubleshooting

### MYRAA does not respond to voice

- Check that a microphone is connected.
- Check Windows microphone permissions.
- Confirm that MYRAA has permission to use the microphone.
- Check your internet connection and Gemini API key.
- Try text input to determine whether the issue is limited to voice.

### AI responses stop or pause

- Confirm that the API key was entered correctly.
- Check that the PC is online.
- You may have reached the API key's usage limit. Check Google AI Studio for current usage and quota information.

### Character import does not work

- Confirm that the selected file is a compatible `.pmx` model or an archive/folder containing one.
- Try selecting the model file directly if importing an archive fails.
- Check that the model files are complete and come from a trusted source.
- Confirm that the model's licence permits your intended use.

### Low frame rate, high GPU usage, or crashes

- Set **Settings → Character → Graphics quality → Auto**.
- If needed, choose **Medium**, **Optimized**, or **Potato PC**.
- Close other applications that are using substantial GPU resources.
- Restart MYRAA after changing settings if performance does not improve.

### A desktop action behaves unexpectedly

- Use `Ctrl + Alt + Shift + S` to stop active actions.
- Review the permission settings.
- Do not approve a prompt unless you understand what it will do.

---

## 📋 System requirements

| Requirement | Minimum / requirement stated in setup notes |
|---|---|
| Operating system | Windows 10 or Windows 11 |
| Architecture | 64-bit |
| Internet | Required |
| Microphone | Required for voice interaction |
| Gemini API key | Required for AI functionality |
| 3D character | User-imported compatible model |

The supplied setup pack does not specify a minimum CPU, RAM, or GPU. Actual performance will depend on your PC, the imported model, and the selected graphics quality.

---

## 📄 Version information

- **Application:** MYRAA
- **Release:** 1.5.2
- **Installer:** `MYRAA-Setup-1.5.2.exe`
- **Package:** MYRAA Setup Pack

For the most accurate installation instructions, keep this README together with the original installer and `READ ME FIRST.txt`.

---

## ⚖️ Third-party services and content

MYRAA uses Google Gemini services, which are subject to Google's own terms, policies, availability, and API quotas. Character models are supplied by the user and remain subject to their respective creators' licences.

No software licence for MYRAA is specified in the supplied setup pack. Do not assume that the application or its source code is licensed for unrestricted redistribution or modification unless the project owner publishes a licence.

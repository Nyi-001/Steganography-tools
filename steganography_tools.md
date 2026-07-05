# 📁 Image Steganography Tools
============================

## JPEG Tools

| Tool | Platform | Description |
|------|----------|-------------|
| Steghide | Cross-platform | Most popular JPEG/BMP steganography |
| JSteg | Cross-platform | Classic JPEG steganography |
| JPHide | Cross-platform | JPEG hiding utility |
| OutGuess | Cross-platform | Universal steganography for JPEG |
| F5 | Cross-platform | Advanced JPEG steganography |
| JSTEG-Shell | Windows | GUI for JSteg |

---

## PNG/BMP Tools

| Tool | Platform | Description |
|------|----------|-------------|
| OpenStego | Cross-platform | PNG/BMP steganography with encryption |
| LSB-Steganography | Cross-platform | Least Significant Bit method |
| StegExpose | Cross-platform | PNG/BMP LSB detector |
| Camouflage | Windows | Hides files in BMP images |
| QuickStego | Windows | Simple LSB steganography |

---

## General Image Tools

| Tool | Platform | Description |
|------|----------|-------------|
| Steganography Studio | Windows | Multiple algorithms support |
| StegoStick | Windows | User-friendly image steganography |
| xSteg | Linux | Advanced image steganography |
| Gifshuffle | Cross-platform | GIF steganography |
| SilentEye | Cross-platform | Modern GUI for image steganography |

---

# 🎵 Audio Steganography Tools

| Tool | Platform | Description |
|------|----------|-------------|
| DeepSound | Windows | Audio steganography with encryption |
| WavSteg | Cross-platform | WAV file steganography |
| Coagula | Cross-platform | Sound-based steganography |
| Steghide | Cross-platform | Also supports audio files |
| MP3Stego | Cross-platform | MP3 file steganography |
| Hide4Audio | Windows | Audio file steganography |

---

# 📹 Video Steganography Tools

| Tool | Platform | Description |
|------|----------|-------------|
| OpenPuff | Windows | Professional video/audio steganography |
| OurSecret | Windows | Video and image steganography |
| StegoStick | Windows | Supports video files |

---

# 📄 Document/Text Steganography

| Tool | Platform | Description |
|------|----------|-------------|
| wStego | Windows | Text and image steganography |
| Snow | Cross-platform | Whitespace steganography in text |
| TextHide | Windows | Text file steganography |
| SpamMimic | Web-based | Hides messages in spam-like text |
| Stegolo | Cross-platform | PDF steganography |

---

# 🔧 Multi-Format & Advanced Tools

| Tool | Platform | Description |
|------|----------|-------------|
| OpenStego | Cross-platform | Multiple formats with encryption |
| Steg | Linux | Command-line multi-format tool |
| StegFS | Linux | Steganographic file system |
| Hydan | Linux | Executable steganography |
| StegDetect | Linux | Steganography detection tool |

---

# 🛡️ Steganography Detection & Analysis

| Tool | Platform | Description |
|------|----------|-------------|
| StegExpose | Cross-platform | LSB steganography detection |
| StegDetect | Linux | Automated steganography detection |
| StegBreak | Linux | Dictionary attacks against stego |
| StegSpy | Windows | Detects various steganography tools |
| Gargoyle | Cross-platform | Forensic steganography detection |

---

# 🌐 Online Steganography Tools

| Tool | Platform | Description |
|------|----------|-------------|
| Steganography Online | Web-based | Browser-based image steganography |
| ImageSteganography.com | Web-based | Online image hiding |
| Spoofify | Web-based | Audio steganography online |
| StegOnline | Web-based | Advanced online steganography |

---

# 📱 Mobile Steganography Apps

## Android
- StegDroid  
- MobiStego  
- PixelKnot  
- Steganography Master  
- Secret Cave  

## iOS
- Stego  
- iSteg  
- Steganography OS  
- PicSecret  

---

# ⚡ Specialized & Research Tools

| Tool | Platform | Description |
|------|----------|-------------|
| StegParty | Linux | Network steganography |
| Network Steganography Toolkit | Linux | Hides data in network traffic |
| LACK | Linux | VoIP steganography |
| StegAES | Cross-platform | AES-encrypted steganography |

---

# 🎯 Popular in CTF & Penetration Testing

## Most Commonly Used Tools

- Steghide → JPEG/BMP/AU/WAV  
- OutGuess → JPEG  
- OpenStego → Multiple formats  
- DeepSound → Audio files  
- Snow → Text whitespace steganography  
- Exiftool → Metadata analysis  
- Binwalk → Firmware analysis  
- Foremost → File carving  
- Strings → Text extraction  
- XXD / Hexdump → Hex analysis  

---

# 🔍 Analysis & Detection Tools

| Tool | Purpose |
|------|--------|
| StegExpose | LSB steganography detection |
| StegDetect | Automated stego detection |
| StegBreak | Password cracking for stego |
| Aletheia | Modern stego detection |
| Ghiro | Digital image forensics |

---

## 💡 Homoglyphs Decoding Tool

https://holloway.nz/steg/

---

# 💡 Usage Tips

Start with basic analysis:

```bash
file suspicious.jpg
strings suspicious.jpg
exiftool suspicious.jpg
binwalk suspicious.jpg

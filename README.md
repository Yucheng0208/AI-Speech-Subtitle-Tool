# AI-Speech-to-Subtitle

[English](#english) | [中文](#中文)

---

## 目錄 | Table of Contents

- [AI-Speech-to-Subtitle](#ai-speech-to-subtitle)
  - [目錄 | Table of Contents](#目錄--table-of-contents)
  - [English](#english)
    - [Introduction | 簡介](#introduction--簡介)
    - [Features | 功能](#features--功能)
    - [Requirements | 系統要求](#requirements--系統要求)
    - [Installation | 安裝](#installation--安裝)
  - [License](#license)

---

## English

### Introduction | 簡介

**AI-Speech-to-Subtitle** is an AI-based tool designed to convert speech to subtitles using Whisper and Pyannote models. It provides automatic speaker diarization and supports various subtitle formats such as CSV, SRT, and VTT. This tool is especially useful for video hosts who need automatic transcription and subtitling for their shows or videos.

**AI-Speech-to-Subtitle** 是一個基於 AI 的語音轉字幕工具，結合了 Whisper 和 Pyannote 模型。該工具可以自動進行說話者識別並生成多種字幕格式，如 CSV、SRT 和 VTT，非常適合影片主持人自動生成字幕。

---

### Features | 功能

- **Whisper-based automatic transcription** with language detection.
- **Speaker diarization** using Pyannote.
- Generate subtitles in **CSV, SRT, and VTT** formats.
- Automatic **audio format conversion** and error handling.

- 基於 **Whisper** 的自動語音轉文字，帶有語言偵測功能。
- 使用 **Pyannote** 進行說話者分段與辨識。
- 支援生成 **CSV、SRT、VTT** 格式的字幕。
- 自動 **音訊格式轉換** 並處理檔案錯誤。

---

### Requirements | 系統要求

- Python 3.8 or above
- Install [ffmpeg](https://ffmpeg.org/download.html) for audio file conversion.
  
- Python 3.8 或更高版本
- 安裝 [ffmpeg](https://ffmpeg.org/download.html) 用於音訊文件轉換。

### Installation | 安裝

```bash
git clone https://github.com/your-username/AI-Speech-to-Subtitle.git
cd AI-Speech-to-Subtitle
pip install -r requirements.txt

## License

This project is licensed under the Apache License - see the [LICENSE](LICENSE) file for details.

此專案採用 Apache 授權條款 - 詳情請參閱 [LICENSE](LICENSE) 文件。

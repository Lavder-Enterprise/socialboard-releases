<p align="center">
  <img src="assets/icon.svg" width="132" alt="Socialboard">
</p>

<h1 align="center">Socialboard</h1>

<p align="center">
  A social mood board. Share a post from Instagram, TikTok, Facebook, X, YouTube, Threads or LinkedIn,<br>
  and your Mac reads it, sums it up and files it in the right board.
</p>

<p align="center">
  <img alt="macOS 27 or later" src="https://img.shields.io/badge/macOS-27%20or%20later-17161D?style=flat-square&logo=apple&logoColor=white">
  <img alt="Apple Silicon" src="https://img.shields.io/badge/chip-Apple%20Silicon-17161D?style=flat-square">
  <img alt="Notarized by Apple" src="https://img.shields.io/badge/notarized%20by-Apple-63D2AA?style=flat-square">
  <img alt="Automatic updates" src="https://img.shields.io/badge/updates-automatic-EC6A4B?style=flat-square">
</p>

<p align="center">
  <a href="../../releases/latest">
    <img alt="Download the latest version" src="https://img.shields.io/badge/Download%20the%20latest%20version-EC6A4B?style=for-the-badge">
  </a>
</p>

## What this repository is

The public release feed of Socialboard for Mac: signed, notarized builds and the update manifest the app checks. There is no source code here.

## Install

1. Download `Socialboard-<version>.zip` from the [latest release](../../releases/latest) and unzip it.
2. Move `Socialboard.app` to Applications and open it.
3. Sign in with your Lavder ID.

The app checks for new versions by itself. You can also choose **Check for Updates…** from the Socialboard menu.

## The engine

Posts are read on your own Mac, by a scheduled Claude Code session that runs on your Claude plan. The app installs it for you and asks before each step. It needs:

- Claude Code and Claude Desktop
- `ffmpeg`, and `whisper-cpp` if you want transcripts: `brew install ffmpeg whisper-cpp`

Without the engine the app still shows your boards.

## iPhone

The iPhone app and its Share extension are distributed through TestFlight.

---

Socialboard is a product of Lavder Enterprise S.R.L.

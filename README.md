# 🏃 parkrun Sticker Builder

A lightweight, mobile-responsive web app that allows you to create custom, transparent sticker overlays for your parkrun achievements. Similar to Strava's sharing features, this tool lets you generate beautiful, clean stats to overlay on your Instagram stories, posts, or other social media.

![parkrun Sticker Builder Screenshot](docs/screenshot.png)

## ✨ Features

- **📱 Mobile Responsive:** Works seamlessly on desktop and mobile devices.
- **🖼️ Configurable Layouts:** Choose from Square (1080×1080), Portrait (1080×1350), or Horizontal (1080×608) to perfectly fit your social media formats.
- **📊 Customizable Stats (Max 3 for a clean look):**
  - **Time:** Your finish time (e.g., 27:32).
  - **Distance:** Standard 5km.
  - **Speed Range:** Automatically calculated min/max speed based on your time.
  - **Achievement:** E.g., "Completed", "New PB!".
  - **Streak:** E.g., "5 in a row".
  - **Milestone:** E.g., "Run #24 (1 to milestone)".
  - **Story Note:** Add a personal touch, e.g., "Tourist stop #7".
- **🎨 Color Themes:** Customize the logo and text colors (parkrun Purple, Vitality Pink, Black, or White).
- **💡 Presets:** Quick selections for Performance, Progress, Story, or Privacy-first stickers.
- **📥 Transparent PNG Export:** Downloads a ready-to-use transparent PNG that you can paste directly onto your photos.

## 🚀 How to Use

1. Open `index.html` in your web browser.
2. Select your desired **Sticker Layout** based on where you plan to post it (e.g., Instagram Story = Portrait).
3. Fill in your **Finish Time** and any other optional stats (Achievements, Streaks, Notes).
4. Choose which stats to **Show on sticker** (you can select up to 3 to keep it clean).
5. Customize the **Logo color** and **Text color**.
6. Click **Download PNG** to save the transparent overlay to your device.
7. Open Instagram (or your preferred social app), load your photo, and add the downloaded sticker PNG as an image overlay!

## 🛠️ Tech Stack

- **Zero dependencies!** Built purely with vanilla HTML, CSS, and JavaScript.
- Uses **HTML5 Canvas** for real-time rendering and image generation.

## 📁 Project Structure

- `index.html`: The main application file containing all the UI and logic.
- `parkrun-logo.*`: Logo assets used for generating the overlays.
- `docs/`: Additional documentation and assets (including stat options guide).

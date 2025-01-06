# Tokyo Night Fox & Gruvbox Theme

![Tokyo Night Preview](https://github.com/user-attachments/assets/f9274d7b-a1f0-41db-8c40-83444a947ad4)
![Gruvbox Preview](path/to/gruvbox-preview.png)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Theme Selection](#theme-selection)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project offers two custom Firefox themes: "Tokyo Night" and "Gruvbox". Tokyo Night provides a clean, minimalistic theme inspired by Tokyo's nightlife, while Gruvbox offers a warm, retro-style color scheme. Both themes modify Firefox's UI elements to enhance your browsing experience.

## Features

- **Reorganized Toolbar:** Moves essential buttons like the main menu and URL bar to make them more accessible while hiding less frequently used items.
- **Customized Tab Appearance:** Rounded corners, adjusted tab height, and smooth transitions for a modern look.
- **Minimalist Design:** Hides unnecessary elements like the Firefox logo, search bar, and more to focus on the content.
- **Theme Options:**
  - Tokyo Night: Dark theme with blue and purple accents
  - Gruvbox: Warm, retro-inspired color palette
- **Animated Hover Effects:** Adds subtle animations to tab close buttons and top sites for a more interactive experience.
- **Custom New Tab Page:** Applies themed backgrounds with a welcoming message and custom layout for top sites.

## Prerequisites

- **Firefox**: Ensure that you have the latest version of Firefox installed.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Stan-breaks/Firefox-themes.git
   ```
2. **Locate Your Firefox Profile**:
   - Open Firefox.
   - Type `about:support` in the address bar and press Enter.
   - Under the "Application Basics" section, find the "Profile Folder" entry, and click "Open Folder." or navigate to the directory.
3. **Create `chrome` Folder**:
   - Inside your profile folder, create a directory named `chrome` if it doesn't exist.
4. **Copy Files**:
   - Copy `userChrome.css` and `userContent.css` from the cloned repository to the `chrome` folder in your Firefox profile.
5. **Enable Custom Styles**:
   - Type `about:config` in the address bar and press Enter.
   - Search for `toolkit.legacyUserProfileCustomizations.stylesheets`.
   - Set the value to `true` by double-clicking on it.
6. **Restart Firefox**:
   - Close and reopen Firefox to apply the theme.

## Theme Selection

To switch between themes:

- Choose either themes chrome folder to copy.

## Customization

- **Adjusting Colors and Fonts**:
  - You can modify the color scheme or font used by editing the theme CSS files in the `themes` directory.
- **Changing Layout**:
  - Tweak the layout by editing `userChrome.css` to better suit your preferences.

## Contributing

Contributions are welcome! If you have suggestions, feel free to fork the repository and submit a pull request. Whether it's new features, bug fixes, or optimizations, your input is valuable.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

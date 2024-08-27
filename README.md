# Firefox Vertical Theme
*Last updated August 2024 - Supports Firefox 128+*

This is designed custom fit for me, so don't expect much configurability.

## Enable firefox vertical tabs

Native vertical tabs are now available in the latest stable version of Firefox.

- Enter `about:config` in the search box and OK
- Search for: `sidebar`
- Enable `sidebar.verticalTabs` and `sidebar.revamp`
- Restart Firefox

If it is not displayed or is collapsed, open the vertical tabs using the sidebar button, then:

- Click the vertical TAB bar Settings
- Select "Do not Fold"
- Click the vertical TAB Settings again

With the exception of a slightly misaligned ui, native vertical tabs are available. This project is about yo fix these problem.

## Installation

0. go to about:config in your URL bar, search for toolkit.legacyUserProfileCustomizations.stylesheets and set it to true
1. locate the firefox profile folder by going to the *hamburger menu* > *help* > *more torubleshooting information*
2. click *show in finder* or *open folder* next to profile folder
3. open the highlighted folder (should look something like "13s123f4.default-release")
4. create a folder named "chrome" if it doesn't exist already
5. paste files from repo into this folder, or `git clone https://github.com/nathandaven/firefox-paradise-theme.git` and restart firefox (command-q/alt-f4 and reopen)
6. install Tab Center Reborn
7. open the extension settings, enable compact mode, and copy the contents of `tab-center-reborn.css` into the stylesheet section
8. profit

## Screenshots

#### Windows

![dark windows](https://github.com/user-attachments/assets/594da29e-aadf-4c93-a9ba-193ad40a9562)

![light windows](https://github.com/user-attachments/assets/3fe97cc5-51cd-4cbe-a32f-1d7d55c5f297)

## Thanks

- [CustomCSSforFx](https://github.com/Aris-t2/CustomCSSforFx)
- [Firefox Paradise Theme](https://github.com/nathandaven/firefox-paradise-theme?tab=readme-ov-file)

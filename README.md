# Firefox Vertical Theme

*Last updated August 2024 - Supports Firefox 128+*

![header image](https://github.com/user-attachments/assets/a66a0076-4270-4f34-9b48-48468a0db305)

This is designed custom fit for me, so don't expect much configurability. macOS users can take a try before I tested its compability.

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
  
   > If you doesn't use the latest version of Firefox, please check the older version in release / tag page.

6. install Tab Center Reborn
7. open the extension settings, enable compact mode, and copy the contents of `tab-center-reborn.css` into the stylesheet section
8. profit

## Screenshots

#### Windows

![light windows](https://github.com/user-attachments/assets/1a799a30-6fd5-4bd0-aec3-7c97aedcb60b)

![light windows collapsed](https://github.com/user-attachments/assets/73c7430b-5081-4c9a-a6f4-624a2453cd61)

![dark windows](https://github.com/user-attachments/assets/11927e41-8eb3-4e44-aa69-82379541bece)

## Thanks

- [CustomCSSforFx](https://github.com/Aris-t2/CustomCSSforFx)
- [Firefox Paradise Theme](https://github.com/nathandaven/firefox-paradise-theme?tab=readme-ov-file)

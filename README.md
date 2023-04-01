<div align="center">
  <a href="https://github.com/roeegh/Puck">
    <img src="assets/Banner.png" alt="Logo">
  </a>
  
  <h3 align="center">Puck</h3>
  <p align="center">
    A collection of customizations ready to use with Cowabunga and Misaka
  </p>
</div>

# Disclaimer

All of my customizations are exported from my iPhone 13 Pro Max running iOS 16.0. I cannot guarantee that all customization will work on your device. Some customizations are iOS version specific, please apply the appropriate ones. If you find any issues, please reach out to me on Twitter.
<br></br>

# Prerequisites

1. Install Filza
2. Install Cowabunga or Misaka
3. Create a folder named `Puck` in the `/var/mobile/Documents` directory
   <br></br>

# How to use it?

### Cowabunga

1. Download and unzip the `.zip` of the wanted customization(s) from the [releases](https://github.com/roeegh/Puck/releases/latest)
2. Move the file from the `Replacement` folder into the `/var/mobile/Documents/Puck` folder
3. Import the `.cowperation`

### Misaka

1.  Add the following repository to your package manager:

    ```
    https://puck.roeegh.dev/repo.json
    ```

# How to change the color?

### Cowabunga

1. Navigate to `/var/mobile/Documents/Puck` using Filza
2. Open the file for the customization you want to edit and find the `red`, `green`, `blue`, and `alpha` fields
3. Take your wanted color value and divide it by 255 to get a decimal value, enter that value in its respective RGBA field
4. Go back into Cowabunga and press the `Generate Padding` button for the customization

_Notice: Values <ins>*must*</ins> be between 0 and 1_

### Misaka

1. Navigate to the `Packages` tab in Misaka
2. Select `Tweak Settings` by pressing and holding on the customization you want to edit
3. Use the color picker to select your wanted color
   <br></br>

# Customizations

### Notification Shadow

Adds a colored shadow to Banners only and Bluetooth device pill

Original File Paths:

-   Light Mode: `/System/Library/PrivateFrameworks/PlatterKit.framework/platterVibrantShadowLight.visualstyleset`

-   Dark Mode: `/System/Library/PrivateFrameworks/PlatterKit.framework/platterVibrantShadowDark.visualstyleset`

<details><summary>Screenshots</summary>

|                                Light Mode                                 |                                Dark Mode                                 |
| :-----------------------------------------------------------------------: | :----------------------------------------------------------------------: |
| ![](</Notification Shadow/Images/Notification Shadow Banner (Light).png>) | ![](</Notification Shadow/Images/Notification Shadow Banner (Dark).png>) |
|  ![](</Notification Shadow/Images/Notification Shadow Pill (Light).png>)  |  ![](</Notification Shadow/Images/Notification Shadow Pill (Dark).png>)  |

</details>

### Custom Spacebar

Change the text of the spacebar on your keyboard

Original File Paths:

-   English: `/System/Library/TextInput/TextInput_en.bundle/Keyboard-en.plist`
-   German: `/System/Library/TextInput/TextInput_de.bundle/Keyboard-de.plist`
-   Vietnamese: `/System/Library/TextInput/TextInput_vi.bundle/Keyboard-vi.plist`

_Notice: If you would like support for other languages, please reach out to me on Twitter_

<details><summary>Screenshots</summary>

|                                Light Mode                                |                                Dark Mode                                |
| :----------------------------------------------------------------------: | :---------------------------------------------------------------------: |
| ![](</Custom%20Spacebar/Images/Custom%20Spacebar%20Text%20(Light).png>)  | ![](</Custom%20Spacebar/Images/Custom%20Spacebar%20Text%20(Dark).png>)  |
| ![](</Custom%20Spacebar/Images/Custom%20Spacebar%20Emoji%20(Light).png>) | ![](</Custom%20Spacebar/Images/Custom%20Spacebar%20Emoji%20(Dark).png>) |

</details>

### Custom CC

Bigger Now Playing module, smaller brightness and volume sliders, and smaller focus module

Original File Paths:

-   `/System/Library/PrivateFrameworks/ControlCenterUI.framework/DefaultModuleSettings~iphone.plist`

<details><summary>Screenshots</summary>

|                   Light Mode                   |                   Dark Mode                   |
| :--------------------------------------------: | :-------------------------------------------: |
| ![](</Better CC/Images/Custom CC (Light).png>) | ![](</Better CC/Images/Custom CC (Dark).png>) |

</details>

### Custom Search Label (iOS 16 Only)

Change the search label on the home screen

Original File Paths:

-   `/System/Library/PrivateFrameworks/SpringBoardHome.framework/SpringBoardHome.loctable`

_Notice: This customization is only for iOS 16._

<details><summary>Screenshots</summary>

|                                  Light Mode                                  |                                  Dark Mode                                  |
| :--------------------------------------------------------------------------: | :-------------------------------------------------------------------------: |
| ![](</Custom%20Search%20Label/Images/Custom%20Search%20Label%20(Light).png>) | ![](</Custom%20Search%20Label/Images/Custom%20Search%20Label%20(Dark).PNG>) |

</details>

# Acknowledgments

-   Icon & Banner by [taki](https://twitter.com/74k1_)

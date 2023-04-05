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

2.  Install your wanted `Tweak` from the added repo

# How to customize?

### Cowabunga

-   #### Helper Operations

1. Import the operations with the `Helper` keyword in the title
2. Using the `Values` section of the customization as a guide to edit the values to your preference
3. Save the operation and navigate back to the parent operation and tap the `Generate Padding` button

-   #### Filza

1. Navigate to `/var/mobile/Documents/Puck` using Filza
2. Open the file for the customization you want to edit
3. Using the `Values` section of the customization as a guide to edit the values to your preference
4. Go back into Cowabunga, into your selected operation and tap the `Generate Padding` button for the customization

### Misaka

1. Navigate to the `Packages` tab in Misaka
2. Select `Tweak Settings` by pressing and holding on the customization you want to edit
3. Change the values to your preference
   <br></br>

# Customizations

### Notification Shadow

Adds a colored shadow to Banners only and Bluetooth device pill

Original File Paths:

-   Light Mode: `/System/Library/PrivateFrameworks/PlatterKit.framework/platterVibrantShadowLight.visualstyleset`

-   Dark Mode: `/System/Library/PrivateFrameworks/PlatterKit.framework/platterVibrantShadowDark.visualstyleset`

Values:

Calculated by taking the RGB values, from the 0 to 255 scale, and dividing them by 255

-   red
    -   min: 0
    -   max: 1
-   green
    -   min: 0
    -   max: 1
-   blue
    -   min: 0
    -   max: 1
-   alpha
    -   min: 0
    -   max: 1

<details><summary>Screenshots</summary>

|                                Light Mode                                 |                                Dark Mode                                 |
| :-----------------------------------------------------------------------: | :----------------------------------------------------------------------: |
| ![](</Notification Shadow/Images/Notification Shadow Banner (Light).png>) | ![](</Notification Shadow/Images/Notification Shadow Banner (Dark).png>) |
|  ![](</Notification Shadow/Images/Notification Shadow Pill (Light).png>)  |  ![](</Notification Shadow/Images/Notification Shadow Pill (Dark).png>)  |

</details>

# Acknowledgments

-   Icon & Banner by [taki](https://twitter.com/74k1_)

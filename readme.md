### If you ❤ what i'm doing - you can support my work! ☕
<a href="https://www.buymeacoffee.com/yoyurec" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 50px !important;width: 178px !important;" ></a>

## Logseq Banners plugin
Enliven your Logseq Workspace with gorgeous, custom, Notion style page banners and icons
![](screenshots/main.png)

## Instructions
* Install the plugin from the Logseq plugin marketplace
* Configure a default images and icons in "Settings -> Plugin Settings -> Banners"
* Customize the banner image on a per page basis via the page props:
    * `banner:: https://wallpaperaccess.com/full/1146672.jpg`
* To avoid Logseq show banner preview in props area - wrap it with doublequotes!
    * `banner:: "http://........"`
*  Sometimes important banner parts cropped on default vertical align "50%" (center), so you can do fine tune with page props:
    * top: `banner-align:: 0%`
    * bottom: `banner-align:: 100%`
* Customize the page icon on a per page basis via the page props:
    * `page-icon:: 💸`
    * or use native Logseq `icon:: 💸`

## Customization
* All customizations (a lot!) can be done from plugin settings ("Settings -> Plugin Settings -> Banners") in nice grouped blocks:
    * Hide plugin related page props for more clean view
    * Widgets HTML embed code
    * Widget calendar size
    * Separate settings for journals and common pages
    * Banners and icons default sizes
    * Banners and icons default vertical align
* Example for adwanced settings (JSON) for custom page types: "Settings -> Plugin Settings -> Banners -> Adwanced settings -> Advanced custom pages banners and icons config -> Edit settings.json"

## Features

### Widgets
![](screenshots/widgets-light-01.png)
![](screenshots/widgets-dark-01.png)
![](screenshots/widgets-light-02.png)
![](screenshots/widgets-dark-03.png)

- Calendar
    - Install "Block calendar" plugin from Logseq Marketplace
    - Go to installed plugin settings ""Settings -> Plugin Settings -> Block calendar"
    - Set "Always render" to `#banner-widgets-calendar` banner placeholder
    - ![](screenshots/block-calendar-settings.png)

- Custom HTML (iframes, etc...)! (you can set your own, here is some pre-configured):
    - Weather
        - Go to [Indify – Notion Widgets](https://indify.co), Sign Up
        - Choose "Weather widget", set your city
        - Set "Number of days" - 2
        - Set colors (mandatory!) for proper work with "Banners" plugin
        - ![](screenshots/weather-config.png)
    - Pomo-focus (from https://pomofocus.io/app)

For more tune use `custom.css` to position widgets iframes inside of banner area via CSS `position:absolute` & `top/right/bottom/left`.

### Random images from Unsplash API

* Set in settings for default page/journal banner:
    * Random featured: `https://source.unsplash.com/featured/1600x900`
    * Photo of the day: `https://source.unsplash.com/1600x900/daily`
    * Search terms. Add comma separated terms after `?` at the end (for default settings or in props at specific page): `https://source.unsplash.com/1600x900?red,house`

For ex. "Dafault journal banner" - `https://source.unsplash.com/featured/1600x900?diary`


### Credits
- This plugin was originally created by [@sawhney17](https://github.com/sawhney17) (buy him a coffee also! https://www.buymeacoffee.com/sawhney17 ☕)
- Currently maintaned and extended by me - [@yoyurec](https://github.com/yoyurec)

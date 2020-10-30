[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/custom-components/hacs)

# Home Assistant Cupertino Icons
Apple iOS-like Cupertino style icons for Home Assistant!

<div style="display: inline-block;">
  
<img src="https://github.com/menahishayan/HomeAssistant-Cupertino-Icons/blob/build-tools/readme-preview/house.svg" alt="preview"  width="50"/>
<img src="https://github.com/menahishayan/HomeAssistant-Cupertino-Icons/blob/build-tools/readme-preview/lightbulb_fill.svg" alt="preview"  width="50"/>
<img src="https://github.com/menahishayan/HomeAssistant-Cupertino-Icons/blob/build-tools/readme-preview/lightbulb.svg" alt="preview"  width="50"/>
<img src="https://github.com/menahishayan/HomeAssistant-Cupertino-Icons/blob/build-tools/readme-preview/alarm.svg" alt="preview" width="50"/>
<img src="https://github.com/menahishayan/HomeAssistant-Cupertino-Icons/blob/build-tools/readme-preview/app_badge_fill.svg" alt="preview"  width="50"/>
<img src="https://github.com/menahishayan/HomeAssistant-Cupertino-Icons/blob/build-tools/readme-preview/battery_25.svg" alt="preview"  width="50"/>
<img src="https://github.com/menahishayan/HomeAssistant-Cupertino-Icons/blob/build-tools/readme-preview/bed_double_fill.svg" alt="preview"  width="50"/><br/>
<img src="https://github.com/menahishayan/HomeAssistant-Cupertino-Icons/blob/build-tools/readme-preview/camera_fill.svg" alt="preview"  width="50"/>
<img src="https://github.com/menahishayan/HomeAssistant-Cupertino-Icons/blob/build-tools/readme-preview/cloud_moon_rain.svg" alt="preview"  width="50"/>
<img src="https://github.com/menahishayan/HomeAssistant-Cupertino-Icons/blob/build-tools/readme-preview/cloud_sun.svg" alt="preview"  width="50"/>
<img src="https://github.com/menahishayan/HomeAssistant-Cupertino-Icons/blob/build-tools/readme-preview/moon_stars.svg" alt="preview"  width="50"/>
<img src="https://github.com/menahishayan/HomeAssistant-Cupertino-Icons/blob/build-tools/readme-preview/moon_zzz_fill.svg" alt="preview"  width="50"/>
<img src="https://github.com/menahishayan/HomeAssistant-Cupertino-Icons/blob/build-tools/readme-preview/person_crop_circle_badge_checkmark.svg" alt="preview"  width="50"/>
<img src="https://github.com/menahishayan/HomeAssistant-Cupertino-Icons/blob/build-tools/readme-preview/speaker_2_fill.svg" alt="preview"  width="50"/>
</div>

## Install
### HACS (Recommended)
1. Go to the **HACS** tab
2. Frontend
3. Menu > **Custom Repository**
4. Paste this repo's URL
5. Select **Theme** in the dropdown
6. Install **cupertino-icons**
7. Reload frontend cache

The icons should be usable in Home Assistant now. If it doesnt show up, try refreshing the page, private browsing or restart Home Assistant

### Manual
1. Clone this repo
2. Copy `dist/HomeAssistant-Cupertino-Icons.js` to `{HOMEASSISTANT_ROOT_DIR}/www/`
3. Home Assistant > **Settings** > **Lovelace Dashboards** > **Resources** > **+**
   - URL: `/local/HomeAssistant-Cupertino-Icons.js`
   - Resource Type: `JavaScript Module`
   - Create
  
The icons should be usable in Home Assistant now. If it doesnt show up, try refreshing the page, private browsing or restart Home Assistant

## Usage
Prefix: **ios**  
Eg: **ios:lightbulb-fill** | **ios:cloud-moon-rain** | **ios:bed-double-fill**

## Icon Reference
[Cupertino Icons v1.0.0](https://flutter.github.io/cupertino_icons/)

*P.S.: with only 1216 icons, the iconset is rather small compared to MDI and incredibly limited. The new SF Pro Symbols v2.0+ now has a total of over 2000+ icons. Update coming soon.*

<hr/>

## To Do
⬜️ Upgrade to SF Pro Symbols v2.0

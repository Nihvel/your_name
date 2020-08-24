# Your Name.
Home Assistant theme - A dark, electric blue theme that reminds (me) the movie Your Name.   

* [Prerequisite](#prerequisite)
* [HACS installation](#hacs_installation)
* [Manual installation](#manual_installation)
* [Enable the theme](#enable_the_theme)
* [Bug](#bug)
* [Screenshots](#screenshots)

### <a name="prerequisite"></a>Prerequisite
Check if **configuration.yaml** allows themes loading from themes folder:   

<pre>
frontend:
  themes: !include_dir_merge_named themes
</pre>

And if the **themes** folder exists in **config** folder.   

Create when none exist.

### <a name="hacs_installation"></a>HACS installation
1. Open the Community Store (HACS)
2. Search for `Your Name`
3. Install it
4. Restart Home Assistant
5. Possible bug(?)

### <a name="manual_installation"></a>Manual installation
1. Copy the file `yourname.yaml` into your Home Assistant themes folder
2. Copy (or create) the `backgrounds` folder inside `www/` and copy the background image `yourname.jpg` inside `backgrounds`
3. Restart Home Assistant

### <a name="enable_the_theme"></a>Enable the theme
- Open your **Profile** in Home Assistant and select the theme called **yourname**

### <a name="bug"></a>Bug (?)
- When installing with HACS the `backgrounds` folder is not created and with it also the background image is not copied. The theme is pointing to a non-existing location and after restarting Home Assistant you may not see the background image. If this happens, check the [Manual installation](#manual_installation) at step #2 and restart Home Assistant once again.

### <a name="screenshots"></a>Screenshots
**Home overview**
<p align="center">
  <img src="https://i.imgur.com/51mOqfs.png">
</p>

<p align="center">
  <img src="https://i.imgur.com/TUYxw0N.png">
</p>

**Dropdown menu black**
<p align="center">
  <img src="https://i.imgur.com/Kqi9iaL.png">
</p>

**Table**
<p align="center">
  <img src="https://i.imgur.com/I6UdSES.png">
</p>

**Mobile**
<p align="center">
  <img src="https://i.imgur.com/cw0STX5.jpg">
</p>

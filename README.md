# Your Name.
Home Assistant theme - A dark, electric blue theme that reminds (me) the movie Your Name.   

### Prerequisite
Check if **configuration.yaml** allows themes loading from themes folder:   

<pre>
frontend:
  themes: !include_dir_merge_named themes
</pre>

And if the **themes** folder exists in **config** folder.   

Create when none exist.

### Screenshots
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


### HACS installation
1. Open the Community Store (HACS)
2. Search for `Your Name`
3. Install it
4. Restart Home Assistant

### Manual installation
1. Copy the file `yourname.yaml` into your Home Assistant themes folder
2. Copy the `backgrounds` folder inside `www/`
3. Restart Home Assistant

### Enable the theme
- Open your **Profile** in Home Assistant and select the theme called **yourname**

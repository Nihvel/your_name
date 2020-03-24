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
1. Copy the file `yourname.yaml` from the folder themes of this Git into your Home Assistant themes folder
2. If you want the background too, copy it in `www`
3. Restart Home Assistant

### Enable the Background
You can use **any** background image.   
To enable the background:
1. In your lovelace, click on `Configure UI > Raw configuration editor`
2. Add the code below at the very beginning of the page
<pre>
background: var(--background-image)
</pre>

### Enable the theme
- Open your **Profile** in Home Assistant and select the theme called **yourname**

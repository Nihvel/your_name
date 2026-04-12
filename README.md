# Your Name.
Home Assistant theme inspired by Makoto Shinkai's 2016 film 君の名は。

Two dark variants, both built around frosted glass cards, a blurred background, and a shared amber accent that ties them together.

**Kataware-doki** — named after the split-twilight moment in the film. Deep indigo backgrounds, lavender as the primary colour, comet amber for active states. Warm and atmospheric.

**Tiamat** — named after the comet itself. Same structure, but the lavender is replaced with electric blue against a deep navy sky. Colder, more precise, still unmistakably the same world.

---

* [Prerequisites](#prerequisites)
* [HACS installation](#hacs_installation)
* [Manual installation](#manual_installation)
* [Enable the theme](#enable_the_theme)
* [Fonts](#fonts)
* [Background Image](#background_image)
* [Screenshots](#screenshots)

## <a name="prerequisites"></a>Prerequisites
1. Edit **configuration.yaml** to allow loading themes from the themes folder:

<pre>
frontend:
  themes: !include_dir_merge_named themes
</pre>

2. Create the folder **themes** next to the **configuration.yaml** file

## <a name="hacs_installation"></a>HACS installation
1. Open the Community Store (HACS)
2. Search for `Your Name.`
3. Install it
4. Restart Home Assistant

## <a name="manual_installation"></a>Manual installation
1. Copy the file `yourname.yaml` into your Home Assistant `themes` folder
2. Create the folder `backgrounds` inside `www` and copy the background image `yourname.jpg` into it (`www/backgrounds/yourname.jpg`)
3. Restart Home Assistant

## <a name="enable_the_theme"></a>Enable the theme
Open your **Profile** in Home Assistant and select either **Your Name. - Kataware-doki** or **Your Name. - Tiamat**.

## <a name="fonts"></a>Fonts
The two themes use different fonts to match their mood. **Kataware-doki** uses Plus Jakarta Sans (warm, humanist) and **Tiamat** uses Sora (precise, quietly technical). Both fall back to system fonts if nothing is loaded.

To actually render them, add the following URL as a Lovelace resource:

**Settings → Dashboards → three-dot menu → Resources → Add Resource**

```
https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:ital,wght@0,300;0,400;0,500;0,600;1,400&family=Figtree:ital,wght@0,300;0,400;0,500;1,400&family=Sora:wght@300;400;500;600&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,400&display=swap
```

Set the resource type to **Stylesheet**. No restart needed. Hard-refresh your browser after (`Ctrl+Shift+R` / `Cmd+Shift+R`) if the font doesn't appear immediately.

> This requires your Home Assistant instance to have internet access. If you run fully offline the themes fall back to your system font automatically.

## <a name="background_image"></a>Background image
When installing via HACS the background image is not copied automatically. If the theme loads but shows no background, follow step 2 of the [Manual installation](#manual_installation) and restart Home Assistant.

The themes look for the image at `www/backgrounds/yourname.jpg`. You can use any image you like, just keep the filename and path.

## <a name="screenshots"></a>Screenshots

**Home overview**
<p align="center">
  <img src="./assets/home-overview.png" alt="Home overview">
</p>

**Settings - About**
<p align="center">
  <img src="./assets/settings-about.png" alt="Settings - About">
</p>

**Frosted glass**
<p align="center">
  <img src="./assets/blurrr.jpg" alt="Blur effect">
</p>

**Mobile**
<p align="center">
  <img src="./assets/mobile.png" alt="Mobile version" width="50%">
</p>

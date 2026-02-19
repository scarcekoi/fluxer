<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://fluxer.app">Fluxer</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/fluxer/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/fluxer?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/fluxer/issues"><img src="https://img.shields.io/github/issues/catppuccin/fluxer?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/fluxer/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/fluxer?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/mocha.webp"/>
</details>

## Usage

1. Open the app and open **User Settings**.
2. Under **Application**, select **Look & Feel**.
3. Open the **Custom Theme Tokens** dropdown.
4. Scroll down until you see a **Custom CSS Overrides** box and delete anything inside (this will remove any pre-existing overrides you may already have).
5. Copy the content of the CSS from from `themes/<flavor>/<flavor>-<accent>.css` and paste it into the **Custom CSS Overrides** box.
6. Enjoy!

### Generating Custom Configurations

The themes included in this repository are generated via [catppuccin/whiskers](https://github.com/catppuccin/whiskers). 
To learn how to modify the generated themes, follow the instructions listed below:

1. Install [catppuccin/whiskers](https://github.com/catppuccin/whiskers#installation).
2. Navigate to the root of this respository.
3. Run `whiskers` with `--overrides` set to a JSON object with your desired options, for example:

    ```bash
    whiskers fluxer.tera --overrides='{"brand_primary_light": "sky"}'
    ```

#### Available Settings

- `brand_primary_light`: The light version of the primary brand colour. Defaults to pink.

## 💝 Thanks to

- [Scarce Koi](https://github.com/scarcekoi)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>

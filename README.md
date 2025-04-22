<h3 align="center">
    <img src="https://raw.githubusercontent.com/Daveedmee/catppuccin-icons/main/assets/logo/logo.png" width="100" alt="Logo"/><br/>
    <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
    🎨 Catpic</a>
    <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
    <a href="https://github.com/silvaire-qwq/catpic/stargazers"><img src="https://img.shields.io/github/stars/silvaire-qwq/catpic?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
    <a href="https://github.com/silvaire-qwq/catpic/issues"><img src="https://img.shields.io/github/issues/silvaire-qwq/catpic?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
    <a href="https://github.com/silvaire-qwq/catpic/contributors"><img src="https://img.shields.io/github/contributors/silvaire-qwq/catpic?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>


<p align="center">
Convert any of your images to Catppuccin colors!
</p>

## Usage

### Basic Command

```bash
./catpic <input_image_path> [output_image_path_or_directory] [options]
```

### Options

- `-l` Use Latte palette
- `-f` Use Frappe palette
- `-a` Use Macchiato palette
- `-m` Use Mocha palette (default)

### Examples

- Convert using the default Mocha palette:
  ```bash
  ./catpic input.png
  ```
- Convert using Latte palette:
  ```bash
  ./catpic input.png -l
  ```
- Convert using multiple palettes (e.g., Latte and Frappe):
  ```bash
  ./catpic input.png -lf
  ```
- Specify an output directory:
  ```bash
  ./catpic input.png /path/to/output/ -m
  ```

### Default Output

If no output path is specified, the converted image will be saved in the current directory with a filename format:

```
<original_filename>.catppuccin-<selected_palettes>.<original_extension>
```

For example, converting `image.png` with the Mocha palette will produce:

```
image.catppuccin-mocha.png
```

### Dependencies

Ensure that [ImageMagick](https://imagemagick.org/) is installed on your system:

```bash
sudo apt install imagemagick
```

## Logo
The Catppuccin Logo for the README.md of this GitHub repository is from [daveedmee/catppuccin-icons](https://github.com/daveedmee/catppuccin-icons). 
If you think I've violated the rights of the original author, please raise an issue and I'll remove it as soon as possible.

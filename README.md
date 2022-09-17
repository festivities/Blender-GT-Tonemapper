# Gran Turismo tone mapping in Blender

## Preview (better image comparison [here](https://imgsli.com/MTIyNjMy))
![Preview](https://user-images.githubusercontent.com/77230051/186923616-70c7e039-d48c-4d37-80e4-114457c86a49.png)
![Without tonemapping](https://user-images.githubusercontent.com/77230051/186924214-21723b98-2382-427c-a364-b4ee4181b294.png)
![With tonemapping](https://user-images.githubusercontent.com/77230051/186924314-a633e4de-a14f-4d85-9ebd-8bc4d7a81d93.png)

## Usage
1. Download the nodegroup [here](https://github.com/festivize/Blender-GT-Tonemapper/archive/refs/heads/main.zip).
2. Append the compositor nodetree *GranTurismoWrapper [APPEND]* to your project.
3. Simply plug in your input image. Make sure your View Transform is set to **sRGB**.

## Special thanks/References
- yaoling1997's [GT-ToneMapping](https://github.com/yaoling1997/GT-ToneMapping)
- shakesoda's [implementation](https://gist.github.com/shakesoda/1dcb3e159f586995ca076c8b21f05a67)

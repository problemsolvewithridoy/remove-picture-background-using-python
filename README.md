
# Remove Picture Background using Python

This is a simple Python script that removes the background of a picture using the remove.bg API. It takes an input image, sends it to the remove.bg API, and saves the output image with a transparent background.

let's start...............

To make this project you need to follow this step:-










## Installation

Install package with pip

```bash
pip install rembg 

```
    
## Deployment

To deploy this project run

```bash
#please subscribe my youtube channel "Problem solve with Ridoy"

from rembg import remove
import time
input_path = "ridoy1.JPG" # your main picture name
output_path = "newridoy.jpg" # your new picture name

start_time = time.time()
with open(input_path, "rb") as i:
    with open(output_path, "wb") as o:
        input = i.read()
        output = remove(input)
        o.write(output)
        end_time = time.time()
print(f"Image background is removed in {str(end_time - start_time)[:3]}")
```






## You can follow me

Facebook:- https://www.facebook.com/problemsolvewithridoy/

Linkedin:- https://www.linkedin.com/in/ridoyhossain/

YouTube:- https://www.youtube.com/@problemsolvewithridoy

Gmail:- entridoy2@gmail.com

If you have any confusion, please feel free to contact me. Thank you


## License
This script is released under the MIT License. Feel free to use, modify, and distribute it as you wish. If you find any bugs or have any suggestions for improvement, please submit an issue or a pull request on this repository.


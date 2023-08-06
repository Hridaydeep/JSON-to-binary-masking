# JSON-to-binary-masking
It is a Python code that reads a JSON file, which contains an annotation of the image that is done using VGG Image Annotation. And it converts the annotations into Binary masking. It works fine for multiple annotations; each annotation delivers an individual Binary mask in a png format.

# Steps
first, if the image is not annotated, go to the via.html file, and annotate it.
link: https://www.youtube.com/watch?v=-3WVSxNLk_k&t=87s

Note: According to the code, I saved the annotation file as **maskGen**, and then the file JSON file was saved as **maskGen_json**

create a folder of images and store the original image and it should be 256*256
FOLDER(should look as follows)
  --images
    -img.png
  --json_to_binary_mask.py
  --maskGen_json

Run the Python code, and if it runs successfully, the folder will look like this.
FOLDER
--images
  -img
    -images
    -masks
--json_to_binary_mask.py
--maskGen_json   

And inside the **masks** you can access the binary masked images of each annotation 


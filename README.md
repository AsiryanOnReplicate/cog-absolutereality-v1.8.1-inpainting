# absolutereality-v1.8.1-inpainting Cog model

This is an implementation of inpainting using the model [eqawqw/absolutereality_v181INPAINTING](https://huggingface.co/eqawqw/absolutereality_v181INPAINTING/blob/main/absolutereality_v181INPAINTING.safetensors) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights

Then, you can run predictions:

    cog predict -i image=@demo.png -i mask=@mask.png

## Example:

Input - "a tabby cat, high resolution, sitting on a park bench"

![alt text](demo.png)

![alt text](mask.png)

Output:

![alt text](output.png)

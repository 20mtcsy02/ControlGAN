The code of this model is out-of-date. Hence, we must make small updates here & there for smooth sailing.
in case, not already made.
**Making changes in the utils.py in the missc folder**
Line 128, 226 : I have added an argument multichannel=True to make the skimage transform fleible to 
the multiple channels in the images.
**making changes to the datasets.py file**
Line 94: change the function name from Scale to Resize
**Making changes to the main.py file**
Line 123: change the function name from Scale to Resize
**Making changes to the pretrain_DAMSM.py file**
Line 102,103,105,106,157, 158 : remove the [0] & add .item() as a single function.
Line 243: change the function name from Scale to Resize

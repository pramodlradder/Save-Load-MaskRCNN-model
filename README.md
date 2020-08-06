# Save-Load-MaskRCNN-model
## This is an attempt at solving the issue with saving and loading MaskRCNN model.
<li>For saving model after training, view <b>save_maskrcnn.ipynb</b> file.
<li>The changes are just related to code in <b>main.py</b> and not the architectural.
<li>For loading JSON file or the H5 file refer <b>load_maskrcnn.ipynb</b> file.
<li>Remember that <b>save_maskrcnn.ipynb</b> and <b>load_maskrcnn.ipynb</b> shouldn't be executed simultaneously.
<li>While running <b>load_maskrcnn.ipynb</b> if u get any problem related to utils make sure your current working dirctory contains the above mrcnn folder.
<li>While running then <b>load_maskrcnn.ipynb</b> if u get any problems related to like PyramidROIAlign2 not defined then 
find functions PyramidROIAlign1 defined in <b>load_maskrcnn.ipynb</b> and copy paste the code below that function just change the name PyramidROIAlign1 to PyramidROIAlign2 in that function.
<li>This repositories is just clear modification of https://github.com/Suchit210Jadhav/Save-Load-MaskRCNN-model

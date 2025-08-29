# Clinically-Informed Preprocessing for ISLES'24 Stroke Segmentation

This is the docker files for the paper "Clinically-Informed Preprocessing Improves Stroke Segmentation in Low-Resource Settings".

Authors:
**Juampablo E. Heras Rivera\***, **Hitender Oswal\***, **Tianyi Ren**, Yutong Pan, William Henry, Caitlin M. Neher, Mehmet Kurt  

\* **Co-first authors**

## Instructions

1. **Clone this repository.**

2. **Download the model weights from the "model weights.txt" file (https://drive.google.com/drive/folders/1ZoTjTzbMT5EHo5KJZp6CL2U8qBLMZbXu?usp=sharing).** Place the files inside the folder called "results" in the same directory as inference.py

4. **Test the algorithm** by running `./test_run.sh`. This script should predict the example image, saving the result in `test/output/`.

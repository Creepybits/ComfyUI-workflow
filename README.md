# ComfyUI-workflow

## EXAMPLE WORKFLOW - Flux - Gemini - Random Redux IMG & Auto-Prompts

* Load 1-100 random images from a selected directory
* Create a grid from the loaded images
* Using [Gemini](https://github.com/Creepybits/ComfyUI-Creepy_nodes) to create a prompt by using the grid as a single image
* Load 1-100 images to use input image as Redux style reference
* Creates 4 different images using Detail Daemon
* Saves the image to Google Drive or OneDrive

___ 

### INSTRUCTIONS     

Preferable you want to make use of 2 different folders, one with images you want to use as reference for [Gemini](https://github.com/Creepybits/ComfyUI-Creepy_nodes) to create prompts, and another for images that would make good backgrounds.  

![image](https://github.com/user-attachments/assets/14f33c56-175e-4380-8293-407f85db6d86)

Random Index
* Minimum: Keep at zero
* Maximum: Set at the same as many images you have in your "Prompt Reference" folder.

Load Batch From Dir ("Prompt Reference" and "Redux Reference Image" folder)
* Directory: Put the path to your "Prompt Reference" folder.
* Image load cap: How many images that together will make a single prompt
* Start Index: Connect to the Random Index Node
* Load always: Ignore this
* Force rescan: Leave this at "Use Cache"
  
### Redux Settings  

Style Model Apply Simple  

![image](https://github.com/user-attachments/assets/396d065d-c018-4aa4-a9c0-347dfa18bb9e)  

Best used at settings low-high (see examples)  


## Image Strength: Lowest  
![1 lowest](https://github.com/user-attachments/assets/08170299-60ae-4430-ae05-f970a9b05c38)  

## Image Strength: Low
![1 low](https://github.com/user-attachments/assets/3206d5db-7f98-423f-893f-7353bd3969d4)  

## Image Strength: Medium  
![1 medium](https://github.com/user-attachments/assets/e4ed1fb5-b27e-4520-8685-e07abec3f99a)  

## Image Strength: High
![1 high](https://github.com/user-attachments/assets/4cb11cc9-68c1-4cd9-825d-92d9f197b810)  

## Image Strength: Highest  
![1 highest](https://github.com/user-attachments/assets/24b938a6-b421-4262-9cf3-6ec2ff28c5f0)  

## WORKFLOW  

![Flux - Gemini - Random Redux IMG   Auto-Prompts](https://github.com/user-attachments/assets/0b71a8da-2ba5-4933-9046-e7bd7521754b)

## WORKFLOW JSON [Gemini 2.0 Flash/Flux - Gemini - Random Redux IMG & Auto-Prompts.json](https://github.com/Creepybits/ComfyUI-workflow/blob/Master/Gemini%202.0%20Flash/Flux%20-%20Gemini%20-%20Random%20Redux%20IMG%20%26%20Auto-Prompts.json)





















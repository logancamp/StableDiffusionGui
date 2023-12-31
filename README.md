# StableDiffusionGui
This project is a simple Kotlin OOP program that takes the input of a Markdown file, reads it and converts it to an HTML file ready to use.
<br />

<h2>Languages and Utilities Used</h2>
- <b>Python</b> 
- <b>TKinter</b> 
- <b>Stable Diffusion Libraries</b> 
- <b>Hugging Face</b> 

Runs on Windows</b> 

<h2>Program Walk-Through:</h2><br/>
<p align="center">
After running the stable diffusion file: <br><br>
<img src="https://i.imgur.com/XcLH73c.png" height="80%" width="80%" alt="open"/> <br><br> 
<br/>
This is the main application page, you can enter a prompt and a style in the designated text boxes. When addint styles you can add multiple separated by commas, there is also a catelog of styles to choose from. Before running your prompt you may also select an image to use for image to image generation. Finally you must choose a model from the list provided. You can add more models if you wish but they must be sources from Hugging Face. The model with the best results is the stable diffusion model. This is depicted here: <br><br>
<img src="https://i.imgur.com/zjSB4Wj.png" height="80%" width="80%" alt="model"/> <br><br> 
<br/>
 
<h2>Running a prompt:<h2><br>
After clicking run it may take longer the first time, after the different parts load the generation won't take too long. You wiull be able to see the progress of the generation in the terminal: <br><br>
<img src="https://i.imgur.com/RiQ6Cne.png" height="80%" width="80%" alt="running"/> <br><br>

<h2>Results:</h2><br>
Once you get the results more options pop up: <br><br>
<img src="https://i.imgur.com/685sYAk.png" height="80%" width="80%" alt="result"/> <br><br> 
Here You can re-run the prompt, re-run with an image, save the image, save and repair face or save variations. These are fairly self explainatory, all saved images will save to a folder in your desktop and if you create variations you may select a quantity in the text box to the right. Now if we make an image with a face, we can select the repair face: <br><br>
<img src="https://i.imgur.com/qj2Vsrg.png" height="80%" width="80%" alt="face1"/> <img src="https://i.imgur.com/bOA8LuM.png" height="80%" width="80%" alt="face2"/>  <br><br> 
<img src="https://i.imgur.com/sIbYgOr.png" height="80%" width="80%" alt="face1.1"/> <img src="https://i.imgur.com/CiXa7Eg.png" height="80%" width="80%" alt="face2.1"/>  <br><br> 
Finally when re-running from picture, the previously generated image will be saved and used as the new picture as part of the prompt. You can also change the image prompt or styles when doing so: <br><br>
<img src="https://i.imgur.com/dQhbt2U.png" height="80%" width="80%" alt="city1"/> <img src="https://i.imgur.com/vSIpcUp.png" height="80%" width="80%" alt="city2"/> 
</p>

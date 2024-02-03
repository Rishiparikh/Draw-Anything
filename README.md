# Open Brush meets Stable Diffusion - How to Draw Anything
### Authors: RISHI PARIKH, DONGHO SHIN, and BAO QIANCHENG

![Alt](/ldmout.png "Title")


Computer technology has slowly changed the way artists and designers interact with their work. Now, software such as photoshop, illustrator, and autocad allow people to create anything from posters, artwork, to full sized architectural and construction plans. This allows for rapid iterating, sharing and collaboration for artists. Similar to how computers changed how artists draw and sketch, virtual reality is a 3D tool artists and designers can use. Recently, Google released Open Brush (tilt brush), an open sourced 3D drawing app. 

While applications of stable diffusion and image-to-image models have made its way into many different applications, they have not made its way to virtual reality yet. In this work, we seek to explore how image-to-image models can be used in the vr space by building on the open brush drawing application on an Oculus Quest 2.
* Survey of real artists and designers on use cases for stable diffusion in virtual reality,
* Pipeline to run stable diffusion from open-brush inputs, and
* Integrating the results of stable diffusion in 2.5D

# Example Workflow Based on Interviews with Artists
![Alt](/workflow.png "Title")

In this example users can draw use 3D figures drawn in tiltbrush and say a theme or phrase to initialize the text 2 image model. The output image will be added to the scene to be used for inspiration. Next steps aim to explore how this output can be incorporated directly into the tiltbrush scene. The stable diffusion tool has been integrated into the code using your hand position and voice to capture the image and text inputs. 
![Alt](/ldm.png "Title")

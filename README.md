#Final Report

##Project description:
	The project we chose to implement was the  Stable Diffusion text-to-image generator. Our project includes an interactive UI in which the user can type into a text box and the image loads onto the side. The UI includes options to adjust the image generation process, such as dimension modifications, negative prompt options, batch size modifications, and more.
	We encountered some challenges while setting up this project, mainly due to the original repository requiring the availability of NVIDIA GPUs. This prompted us to search for a tutorial that would guide us on how to bypass this requirement. Because of this, our current project does not make use of the NVIDIA GPUs, and instead works only on MacOS systems.

##Deliverables:
Presentation Slides
Interactive UI
GitHub Repository (includes model and code for UI)

##How we divided work:
Although for the most part, we worked pretty collaboratively, there were certain parts that we split into groups for. We collectively did research on which tutorials and models would work best on all of our different laptops and OS. Daniyah and Divya and Riya were able to find out how to create an app that worked on all of our laptops. Tanvi and Shraddha looked through different AI models to find the one that would work best, then chose the hugging face stable-diffusion 2.13 GB model as it was open source and used significantly less processing power compared to other text-to-image models. Riya worked on combining the components of the model and application to work together and created the GitHub Repository to push all of the progress. 

##Models used and Results:
	We used the Mo-di-Diffusion model to generate the images for this project. We decided to use this model as it was readily available in the tutorial and required less storage space than a typical Stable diffusion checkpoint file. This model was also the most compatible one that we found with macOS.
	In regards to the results of the project, we were able to successfully create an image generator with a simple UI. The UI we created has a text box for the user to input their prompt for the image they want to create. There is then a separate area where the image is generated. The tutorial and model we used enables the creation of images based on the user’s input. For example, if a user enters a prompt of “a beach during sunset,” our generator will easily develop a clear image of this. The user can even input complex prompts and the generator will be able to achieve the goal. 

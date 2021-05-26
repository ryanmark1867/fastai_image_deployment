# fastai_deployment
- example of a simple web deployment of a fastai deep learning model on Windows using Flask 

## File / Directory structure
- fruits_360may3.pkl - fastai deep learning model trained with the fruits-360 dataset dataset
- web_flask_deploy_image_model.py - Flask server module
- **templates** - HTML files
- **static/css** - CSS files
- **test_images** - image files to test the model with


## To exercise the code

- Set up fastai on your Windows system following the instructions to [set up PyTorch](https://pytorch.org/get-started/locally/) and [set up fastai](https://docs.fast.ai/)

- Start the Flask server - in the directory where you cloned the repo, run this command

- ```
  python web_flask_deploy_image_model.py
  ```

- Open the following address in a browser tab:

- ```
  localhost:5000
  ```

- The file home.html should be loaded into your browser. You can select the image file to make a prediction on (must be in the test_images directory) and click **Get prediction** to see the model's prediction of what's in the image


## Background

- [fruits-360 dataset](https://www.kaggle.com/moltean/fruits)
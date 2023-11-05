# Font creation using 2d GAN
[Colab](https://colab.research.google.com/drive/18jb0fVEMcdCxiET8rnFi40p3W7PJVz-5?usp=sharing)

[nbviewer](https://nbviewer.org/github/AadityaSalgarkar/font_creation/blob/main/main.ipynb#)


## Synthetic data generation

We use 746 google fonts to generate synthetic data.
Each font consists of 28x28 images of all 26 alphabets.

## Model

We train a GAN with 6000 epochs, described in the notebook.

## Result

Generated fonts at the end of 6000th epoch are shown in the notebook.

## Image result

![image](images/img3.png)
![image](images/img6.png)
![image](images/img1.png)
![image](images/img5.png)
![image](images/img4.png)
![image](images/img2.png)

## Losses

![image](images/gloss.png)
![image](images/dloss.png)

## Interesting runs

An interesting run where G loss went to 0:
[link](https://wandb.ai/aadis-learning/font_creation/reports/iconic-eon-2--Vmlldzo1ODc4MTM2?accessToken=d37pbr1ct8omrjxa3ydai5srugdcqg3ep67xr68dsvmy2re0473je00g5vggwbq4)
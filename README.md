# Super Resolution using ESRGAN 
<a href="https://colab.research.google.com/github/sanjay-thiyagarajan/super-resoluter/blob/main/SuperResolute.ipynb">![](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)</a>  

This project aims on achieving super resolution through pretrained ESRGAN model on Keras.  
### Samples:  
![](https://user-images.githubusercontent.com/42594454/116289650-4b0a9700-a7b0-11eb-8ea8-d5bf83ca566e.png)  
1) Leftmost image - Original (Low resolution image)
2) Middle image - Bicubic (x4) image
3) Rightmost image - Super-resoluted image (ESRGAN Super resolution O/P)
### Metrics:  
1) PSNR value achieved for the above super-resoluted sample - **26.097332**  
### Takeaways:
1) ESRGANs perform very well on the real-time samples regardless of the colors.
2) In the provided notebook, Super resolution is achieved not only for images, but for videos too :)  
### References:
1) http://openaccess.thecvf.com/content_ECCVW_2018/papers/11133/Wang_ESRGAN_Enhanced_Super-Resolution_Generative_Adversarial_Networks_ECCVW_2018_paper.pdf
2) https://www.semanticscholar.org/paper/ESRGAN%3A-Enhanced-Super-Resolution-Generative-Wang-Yu/1bdd30a8acc75c58a1bdd4daa4545d5f3971a826

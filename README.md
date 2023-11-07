# ai-driven-heightmaps-with-gan
Use GANs to generate high-quality heightmaps

GANs are a class of generative models specially made to generate data such as images, text and others. Introduced by Ian Goodfellow in 2014,  GANs consist of two neural networks which are the generator and the discriminator. The generator is responsible to create synthetic data by starting with random noise and slowly refines its output data and finally able to generate data which is indistinguishable from real data. On the other hand, the discriminator acts as a binary classifier. Discriminator’s job is to distinguish between real and fake data. These two networks are trained simultaneously in a game-theoretic manner. The generator tries to generate data to fool the discriminator while discriminator tries to improve to distinguish real data and fake data.

Results
The result is satisfying because model is able to generate high quality images. 
![image](https://github.com/LipChuanSui/ai-driven-heightmaps-with-gan/assets/56187131/09deaa82-5a7d-417d-87bf-86f5ad6f8255)

Houdini is used to create HDA with the heightmaps generated. A tool called masking by feature is used to scatter object by calculating the height of the heightmaps. For example, the figure below shows that tree and stone will be shattered around the middle section of the landscape. 
![image](https://github.com/LipChuanSui/ai-driven-heightmaps-with-gan/assets/56187131/90186016-d290-490b-83bd-6215df45e944)

Later, HDA is created and import into Unreal Engine 5. Material and mesh of trees is added to the game engine to looks good. 

![image](https://github.com/LipChuanSui/ai-driven-heightmaps-with-gan/assets/56187131/0dfa4908-2f62-41b2-8c1f-d7cb7a3ad40a)
![image](https://github.com/LipChuanSui/ai-driven-heightmaps-with-gan/assets/56187131/c49fdaef-bfdb-4114-bc34-d2fca65b9c3d)

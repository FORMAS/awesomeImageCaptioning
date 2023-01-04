# awesomeImageCaptioning

## Image Captioning Guideline

This is a curated list of Image Captioning papers, databases and codes.

Image captioning is the task of describing an image. In order to to that, one must recognize the objects, scenario, characters and theirs relationships on the figure, after that generate a sentence that represent the elements detected in a natural language way. Image captioning is a hard task, joining two different areas from Artificial Intelligence: Computer Vision and Natural Language Processing.

This repo is organized with: surveys, datasets, metrics and then by the strategies used to do Image Captioning. Starting from early proposals of description retrieval and template filling going all the way to the se of deep learning technique, starting with CNNs with RNNs to the use of Transformers for generating global representations and generate language.

### Surveys
First we added some surveys to help discovering the area:

 - [Automatic Description Generation from Images: A Survey of Models, Datasets, and Evaluation Measures](https://arxiv.org/abs/1601.03896)
	 - Raffaella Bernardi, Ruket Cakici, Desmond Elliott, Aykut Erdem, Erkut Erdem, Nazli Ikizler-Cinbis, Frank Keller, Adrian Muscat, Barbara Plank
- [From Show to Tell: A Survey on Deep Learning-based Image Captioning](https://arxiv.org/abs/2107.06912)
	- Matteo Stefanini, Marcella Cornia, Lorenzo Baraldi, Silvia Cascianelli, Giuseppe Fiameni, Rita Cucchiara

### Datasets
- [Framing Image Description as a Ranking Task: Data, Models and Evaluation Metrics](https://www.jair.org/index.php/jair/article/view/10833)
	- Hodosh, Micah and Young, Peter and Hockenmaier, Julia
- [From image descriptions to visual denotations: New similarity metrics for semantic inference over event descriptions](https://aclanthology.org/Q14-1006/)
	- Young, Peter and Lai, Alice and Hodosh, Micah and Hockenmaier, Julia
- [Microsoft COCO: Common Objects in Context](https://arxiv.org/abs/1405.0312)
	- Tsung-Yi Lin, Michael Maire, Serge Belongie, Lubomir Bourdev, Ross Girshick, James Hays, Pietro Perona, Deva Ramanan, C. Lawrence Zitnick, Piotr Dollár
- [VizWiz](https://vizwiz.org/tasks-and-datasets/image-captioning/)

### Papers

#### Description Retrieval and Rule Based (early strategies)
- [Automatic image captioning](https://www.researchgate.net/publication/4124972_Automatic_image_captioning)
	- J.-Y. Pan, H.-J. Yang, P. Duygulu, and C. Faloutsos
- [Every Picture Tells a Story: Generating Sentences from Images](https://www.researchgate.net/publication/221303952_Every_Picture_Tells_a_Story_Generating_Sentences_from_Images)
	- A. Farhadi, M. Hejrati, M. A. Sadeghi, P. Young, C. Rashtchian, J. Hockenmaier, and D. Forsyth
- [Im2text: Describing images using 1 million captioned photographs](https://papers.nips.cc/paper/2011/hash/5dd9db5e033da9c6fb5ba83c7a7ebea9-Abstract.html)
	- V. Ordonez, G. Kulkarni, and T. Berg
- [Deep fragment embeddings for bidirectional image sentence mapping](https://arxiv.org/abs/1406.5679)
		- Andrej Karpathy, Armand Joulin, Li Fei-Fei
- [I2T: Image parsing to text description](http://www.stat.ucla.edu/~sczhu/papers/I2T_IEEE_proc.pdf)
	- Benjamin Z. Yao, Xiong Yang, Liang Lin, Mun Wai Lee and Song-Chun Zhu 
- [Corpus-guided sentence generation of natural images](https://aclanthology.org/D11-1041/)
	- Y. Yang, C. Teo, H. Daumé III, and Y. Aloimonos

#### Deep Learning strategies
- [Show and Tell: A Neural Image Caption Generator](https://arxiv.org/abs/1411.4555) 2015
	- Oriol Vinyals, Alexander Toshev, Samy Bengio, Dumitru Erhan
-  [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](https://arxiv.org/abs/1502.03044) - 2015
	- Kelvin Xu, Jimmy Ba, Ryan Kiros, Kyunghyun Cho, Aaron Courville, Ruslan Salakhutdinov, Richard Zemel, Yoshua Bengio
- [Deep visual-semantic alignments for generating image descriptions](https://arxiv.org/abs/1412.2306) - 2015
	- Andrej Karpathy, Li Fei-Fei
- [Review Networks for Caption Generation](https://arxiv.org/abs/1605.07912) 2016
	- Zhilin Yang, Ye Yuan, Yuexin Wu, Ruslan Salakhutdinov, William W. Cohen
- [SCA-CNN: Spatial and Channel-wise Attention in Convolutional Networks for Image Captioning](https://arxiv.org/abs/1611.05594) 2017
	- L. Chen, H. Zhang, J. Xiao, L. Nie, J. Shao, W. Liu, and T.-
S. Chua
- [Rethinking the Form of Latent States in Image Captioning](https://arxiv.org/abs/1807.09958) - 2018
	- Bo Dai, Deming Ye, Dahua Lin
- [Attention on Attention for Image Captioning](https://arxiv.org/abs/1908.06954) - 2019
	- Lun Huang, Wenmin Wang, Jie Chen, Xiao-Yong Wei
- [X-Linear Attention Networks for Image Captioning](https://arxiv.org/abs/2003.14080)
	- Yingwei Pan, Ting Yao, Yehao Li, Tao Mei
- [Meshed-Memory Transformer for Image Captioning](https://arxiv.org/abs/1912.08226) 2020
	- Marcella Cornia, Matteo Stefanini, Lorenzo Baraldi, Rita Cucchiara

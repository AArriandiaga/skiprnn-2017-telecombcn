# Skipping State Updates in Recurrent Neural Networks

| ![Víctor Campos][VictorCampos-photo]  |  ![Brendan Jou][BrendanJou-photo] |  ![Jordi Torres][JordiTorres-photo]  | ![Xavier Giro-i-Nieto][XavierGiro-photo]  | ![Shih-Fu Chang][ShihFuChang-photo] |  
|:-:|:-:|:-:|:-:|:-:|
| [Víctor Campos][VictorCampos-web] | [Brendan Jou][BrendanJou-web] |  [Jordi Torres][JordiTorres-web] | [Xavier Giró-i-Nieto][XavierGiro-web] | [Shih-Fu Chang][ShihFuChang-web] |  

[VictorCampos-photo]: ./figures/authors/VictorCampos.jpg "Víctor Campos"
[JordiTorres-photo]: ./figures/authors/JordiTorres.jpg "Jordi Torres"
[XavierGiro-photo]: ./figures/authors/XavierGiro.jpg "Xavier Giro-i-Nieto"
[BrendanJou-photo]: ./figures/authors/BrendanJou.png "Brendan Jou"
[ShihFuChang-photo]: ./figures/authors/ShihFuChang.jpg "Shih-Fu Chang"

[VictorCampos-web]: https://imatge.upc.edu/web/people/victor-campos
[JordiTorres-web]: http://www.jorditorres.org/
[XavierGiro-web]: https://imatge.upc.edu/web/people/xavier-giro
[BrendanJou-web]: http://www.ee.columbia.edu/~bjou/
[ShihFuChang-web]: http://www.ee.columbia.edu/~sfchang/



A joint collaboration between:

|  ![logo-bsc] | ![logo-google] | ![logo-upc] | ![logo-columbia] |
|:-:|:-:|:-:|:-:|
| [Barcelona Supercomputing Center (BSC)](https://www.bsc.es/)  |  [Google](https://www.google.com/) | [Universitat Politecnica de Catalunya (UPC)](http://www.upc.edu/?set_language=en)   | [Columbia University](https://www.columbia.edu/ ) |

[logo-upc]: ./figures/logos/upc.jpg "Universitat Politècnica de Catalunya"
[logo-bsc]: ./figures/logos/bsc.jpg "Barcelona Supercomputing Center"
[logo-google]: ./figures/logos/google.png "Google"
[logo-columbia]: ./figures/logos/columbia.png "Columbia University"




## Abstract

Recurrent Neural Networks (RNNs) show outstanding performance in sequence modeling tasks. However, practitioners training RNNs on long sequences often face important challenges such as slow inference, vanishing gradients or the difficulty to capture long term dependencies. These issues are strongly related to the long and sequential computational graph resulting from unfolding the RNN in time. We introduce the Skip RNN model which extends existing RNN architectures and provides them with the ability to skip state updates, thus shortening the associated computational graph and alleviating the issues associated to long sequences. We evaluate the proposed model on a series of tasks and show how it can reduce the number of required RNN updates while preserving, and sometimes even boosting, the performance of the baseline models. 



## Publication

(To be updated with arXiv/conference reference and bibtex)


## Slides

(To be updated with the slides and video)


## Code

### Dependencies
This project was developed with Python 3.6.0 and TensorFlow 1.0.0. To download and install TensorFlow, please follow the [official guide](https://www.tensorflow.org/get_started/os_setup).

### Using the models
The models are ready to be used with TensorFlow's `dynamic_rnn` and can be found under `src/models/`.


## Acknowledgments

We would like to especially thank the technical support team at the Barcelona Supercomputing Center.

|   |   |
|:--|:-:|
| This work has been supported by the [grant SEV2015-0493 of the Severo Ochoa Program](https://www.bsc.es/es/severo-ochoa/presentaci%C3%B3n) awarded by Spanish Government, project TIN2015-65316 by the Spanish Ministry of Science and Innovation contracts 2014-SGR-1051 by Generalitat de Catalunya | ![logo-severo] |
|  We gratefully acknowledge the support of [NVIDIA Corporation](http://www.nvidia.com/content/global/global.php) through the BSC/UPC NVIDIA GPU Center of Excellence. |  ![logo-gpu_excellence_center] |
|  The Image ProcessingGroup at the UPC is a [SGR14 Consolidated Research Group](https://imatge.upc.edu/web/projects/sgr14-image-and-video-processing-group) recognized and sponsored by the Catalan Government (Generalitat de Catalunya) through its [AGAUR](http://agaur.gencat.cat/en/inici/index.html) office. |  ![logo-catalonia] |
|  This work has been developed in the framework of the project [BigGraph TEC2013-43935-R](https://imatge.upc.edu/web/projects/biggraph-heterogeneous-information-and-graph-signal-processing-big-data-era-application), funded by the Spanish Ministerio de Economía y Competitividad and the European Regional Development Fund (ERDF).  | ![logo-spain] | 


[logo-gpu_excellence_center]: ./figures/logos/gpu_excellence_center.png "Logo of NVidia"
[logo-catalonia]: ./figures/logos/generalitat.jpg "Logo of Catalan government"
[logo-spain]: ./figures/logos/MEyC.png "Logo of Spanish government"
[logo-severo]: https://github.com/imatge-upc/detection-2016-nipsws/blob/master/logos/severo_ochoa.png?raw=true "Severo Ochoa"


## Contact

If you have any general doubt about our work or code which may be of interest for other researchers, please use the [public issues section](https://github.com/imatge-upc/skiprnn-2017-tfm/issues) on this github repo. Alternatively, drop us an e-mail at <mailto:victor.campos@bsc.es>.
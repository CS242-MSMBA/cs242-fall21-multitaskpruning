# Mask R-CNN CS 242 Project
collection of notebooks we used to conduct our experiments and design our pruning aware training approach for managing the tradeoffs between performance while pruning multi-task models.


## Notebooks

Links to colab notebooks are linked below:
#### [Balloon Detection Shared](https://colab.research.google.com/drive/1g2YEsxob73KmQKynRv48tHixeT7SPH3E?usp=sharing)

- this notebook is used to show the detection of balloons from our Mask R-CNN model
- we used this notebook to generate some of the example images in the research paper, such as the semantic segmentation example

#### [Balloon Pruning Shared](https://colab.research.google.com/drive/1DrM-Wi-VrqZl5Eq6B5135dU-L3CihySx?usp=sharing)

- this notebook contains the pruning and evaluation for the model trained on the balloons dataset

#### [Balloon Training Shared](https://colab.research.google.com/drive/1RUX_SLo1cm4F65MANxLE0MQbmK-2Q4nC?usp=sharing)

- this notebook contains the code for training the Mask R-CNN on the balloons dataset

#### [Shapes Eval function Shared](https://colab.research.google.com/drive/1_QGlZ17oKAK-xsumaL1w4hexYHh4RzbC?usp=sharing)

- this notebook contains our code for evaluating the model trained on the shapes data
- the evaluation is done for each of the tasks (bbox, classification, mask segmentation)

#### [Shapes Pruning New Schema Shared](https://colab.research.google.com/drive/1aXNEuJW0nYrx0sdKTEdkpX6zeJWiS32j?usp=sharing)

- this notebook contains our code for pruning & fine tuning using the novel schema described in the paper

#### [Shapes Pruning Shared](https://colab.research.google.com/drive/1OetzI9Sk0_Co4Lwg6kdlwsH6VdgX8SCQ?usp=sharing)

- this notebook contains our code for pruning layers off the shapes trained model
- we generate the metrics for evaluating the model after pruning

#### [Shapes Training Shared](https://colab.research.google.com/drive/1mK6mk4alFnFm2KvlatdjyKVwzsLTggkJ?usp=sharing)

- this notebook contains the training of the Mask R-CNN model on the shapes dataset

## Datasets

#### Balloons

- zip file containing our train and test images used for the balloon dataset
- will need to be unzipped in order to run the notebooks

## Mask R-CNN Codebase

- our codebase is forked off the Matterport Mask R-CNN implementation that can be found here: https://github.com/matterport/Mask_RCNN

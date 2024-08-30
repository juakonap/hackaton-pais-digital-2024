# Información del grupo.

## Integrantes:
- [María José Briceño Nikulin](https://www.linkedin.com/in/mariajosebricenonikulin/)
- [Luis Castillo Faune](https://www.linkedin.com/in/luiscastillof/)
- [Carlos Navarro Clavería](https://carlosnavarroc.github.io/)
- [Juan Pablo Pérez Caballero](https://www.u-cursos.cl/usuario/bc51dd8f4d8f7f2f3d74ea38b8253eca/mi_blog/))

## Mentor: 
- Sebastián Albizú Tobar

# Bases de Datos de Dominio Publico.

- [COCO (Common Objects in Context)](https://cocodataset.org/): Un conjunto de datos grande y diverso para la detección de objetos, segmentación y etiquetado de escenas. Es ampliamente utilizado en la comunidad de visión por computadora.

- [PASCAL VOC](http://host.robots.ox.ac.uk/pascal/VOC/): Conjunto de datos para la detección de objetos, segmentación y acción, utilizado para evaluar algoritmos de visión por computadora.

- [ImageNet](https://www.image-net.org/): Una base de datos masiva de imágenes organizadas de acuerdo con la jerarquía de WordNet. Es conocida por su uso en la competencia de clasificación de imágenes a gran escala.

- [Open Images Dataset](https://storage.googleapis.com/openimages/web/index.html): Un gran conjunto de datos con más de 9 millones de imágenes anotadas con etiquetas de objetos, segmentación y relaciones visuales.

- [LFW (Labeled Faces in the Wild)](http://vis-www.cs.umass.edu/lfw/): Un conjunto de datos de imágenes de rostros, utilizado para el reconocimiento facial en condiciones no controladas.

- [CIFAR-10 y CIFAR-100](https://www.cs.toronto.edu/~kriz/cifar.html): Conjuntos de datos que contienen imágenes pequeñas (32x32 píxeles) categorizadas en 10 o 100 clases. Son ampliamente utilizados para pruebas y benchmarking de algoritmos de clasificación de imágenes.

- [KITTI Vision Benchmark Suite](http://www.cvlibs.net/datasets/kitti/): Conjunto de datos para la evaluación de algoritmos de visión por computadora en el contexto de vehículos autónomos, incluyendo tareas como la detección de objetos y la segmentación semántica.

- [ADE20K](https://groups.csail.mit.edu/vision/datasets/ADE20K/): Un conjunto de datos para segmentación semántica que contiene imágenes diversas anotadas con 150 categorías de objetos.

- [Cityscapes](https://www.cityscapes-dataset.com/): Conjunto de datos que proporciona anotaciones detalladas para la segmentación semántica de escenas urbanas en entornos de conducción.

- [MNIST](http://yann.lecun.com/exdb/mnist/): Un conjunto de datos clásico utilizado para entrenar sistemas de reconocimiento de imágenes en la tarea de clasificación de dígitos manuscritos.

- [DCSASS Dataset en Kaggle](https://www.kaggle.com/datasets/mateohervas/dcsass-dataset): Un conjunto de datos que contiene imágenes y anotaciones para la clasificación y detección de objetos.

- [Real-world Anomaly Detection in Surveillance Videos](https://www.crcv.ucf.edu/projects/real-world/): Conjunto de datos para la detección de anomalías en videos de vigilancia del mundo real.

- [GTA V-based Datasets](https://paperswithcode.com/dataset/gta5): Conjunto de datos basado en el videojuego GTA V, utilizado para investigaciones en visión por computadora como segmentación de escenas.

- [Weapon detection](https://universe.roboflow.com/weapon-detection-qktol/weapon-detection-ipl7p): Conjunto de datos para la detección de armas en imágenes, útil para tareas de seguridad y vigilancia.


# Arquitecturas de Código Abierto

- [YOLO (You Only Look Once)](https://pjreddie.com/darknet/yolo/): Arquitectura de detección de objetos en tiempo real. Existen varias versiones como YOLOv3, YOLOv4, YOLOv5 (desarrollada por Ultralytics), y YOLOv7. Implementaciones disponibles en frameworks como PyTorch y TensorFlow.
  
- [Ultralytics YOLOv5](https://github.com/ultralytics/yolov5): Implementación de YOLO que ha ganado popularidad por su facilidad de uso y alta precisión. Desarrollado por Ultralytics, incluye herramientas para entrenamiento, detección y exportación a diferentes formatos.
  
- [Detectron2](https://github.com/facebookresearch/detectron2): Desarrollado por Facebook AI Research (FAIR). Framework para tareas de visión por computadora como segmentación de imágenes, detección de objetos y keypoint detection. Basado en PyTorch.
  
- [TensorFlow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection): Ofrece una colección de modelos preentrenados para la detección de objetos. Compatible con TensorFlow y fácil de personalizar para diferentes aplicaciones.
  
- [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose): Biblioteca para la detección de posturas humanas en tiempo real. Desarrollado por CMU Perceptual Computing Lab, capaz de detectar puntos clave en el cuerpo, manos y rostro.
  
- [Faster R-CNN](https://github.com/rbgirshick/py-faster-rcnn): Arquitectura avanzada para la detección de objetos. Es una mejora sobre el R-CNN y Fast R-CNN, con un enfoque en la velocidad y precisión. Implementación en PyTorch y TensorFlow.
  
- [EfficientDet](https://github.com/google/automl/tree/master/efficientdet): Desarrollado por Google. Modelo para la detección de objetos que optimiza la relación entre precisión y eficiencia. Basado en la familia de modelos EfficientNet.
  
- [RetinaNet](https://github.com/fizyr/keras-retinanet): Introduce el concepto de Focal Loss para abordar el problema de detección de objetos pequeños. Ofrece un balance entre precisión y velocidad.
  
- [Darknet](https://github.com/pjreddie/darknet): Framework original en C/C++ para implementar YOLO. Compatible con múltiples GPUs y se centra en la eficiencia de la detección en tiempo real.
  
- [OpenMMLab (MMDetection)](https://github.com/open-mmlab/mmdetection): Un poderoso marco de referencia de PyTorch para la detección de objetos. Parte de la colección OpenMMLab, que incluye herramientas para segmentación y otras tareas de visión por computadora.

- [Segment Anything Model (SAM)](https://github.com/facebookresearch/segment-anything): Desarrollado por Meta AI, es un modelo diseñado para segmentar cualquier cosa en una imagen con gran precisión. Utiliza un enfoque de segmentación interactiva que permite a los usuarios seleccionar objetos de interés fácilmente. SAM es capaz de generalizar a diferentes tipos de imágenes y tareas sin necesidad de un ajuste fino.

- [Mask R-CNN](https://github.com/matterport/Mask_RCNN): Una extensión del modelo Faster R-CNN que añade una rama de máscara para predecir un mapa de segmentación de objetos además de la clase y el cuadro delimitador. Es ampliamente utilizado para tareas de segmentación de instancias y tiene implementaciones en frameworks como TensorFlow y PyTorch.

- [Cascade Mask R-CNN](https://github.com/open-mmlab/mmdetection/tree/master/configs/cascade_rcnn): Una variante mejorada de Mask R-CNN que incorpora una cascada de múltiples etapas para mejorar la precisión de la segmentación y la detección de objetos. Desarrollado en el marco de OpenMMLab (MMDetection), está diseñado para manejar escenarios donde se requiere una mayor precisión en la detección.



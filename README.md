# Classez-des-images-l-aide-de-Deep-Learning
Classez des images à l'aide d'algorithmes de Deep Learning

Le projet de ce notebook a été réalisé dans le cadre du cursus d'ingénieur machine learning proposé par Openclassrooms.

L'objectif du projet est la comparaison d'un modèle CNN  from "Scratch" et des modèles CNN pré-entrainé  utilisant du "transfer learning".

La démarche  de l'entraînements de façon suivante:

Modèle initial "from scratch" avec du préprocessing: égalisation et le débruitage, on introduit aussi de la data augmentation,
 l'ajout du dropout et de batchnormalization.

Comparaison du modèle CNN avec du Transfer learning  modèle avec des modèles préentrainés sur ImageNet. Notemment, les modèles
VGG19, ResNet50, EffecientNetB3 et Xception. Dans ce cadre on supprime la couche dense et on congèle une partie ou la totalité des autre couche

Les données:   nn utilise le "Stanford Dogs Dataset". Ce dataset est constitué de 20 580 images de chiens triées en 120  races.

Les entrainements ont été réalisés sur GPU à l'aide de Google Colab.

Le meileur modèle a été par la suite intégré dans une api développée à l'aide du framework gradio.


# Car-Damage-Detection-using-Detectron

In this project, I first install the required dependencies and clone the Detectron repository from GitHub. Later, I import COCO from the pycocotools library. Detectron2 is then set up with the necessary configurations for the damage segmentation and part segmentation models.

I define the detect_damage_part function, which calculates the most damaged part based on the distance between damage polygons and part polygons. Next, I create subplots for visualization using matplotlib. The damage and part inference are performed using the respective predictor models from Detectron2.

Finally, the damaged parts are printed by calling the detect_damage_part function with the corresponding dictionaries of damage and part polygons.

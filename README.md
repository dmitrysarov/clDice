Implementation of clDice loss from paper "clDice - a Novel Connectivity-Preserving Loss Function for Vessel Segmentation"
https://profs.etsmtl.ca/hlombaert/public/medneurips2019/27_CameraReadySubmission_cl_dice_neurips_med.pdf

>Accurate segmentation of vascular structures is an emerging research topic with
>relevance to clinical and biological research. The connectedness of the segmented
>vessels is often the most significant property for many applications such as disease modeling for neurodegeneration and stroke. We introduce a novel metric
>namely clDice, which is calculated on the intersection of centerlines and volumes
>as opposed to the traditional dice, which is calculated on volumes only. Firstly,
>we tested state-of-the-art vessel segmentation networks using the proposed metric as evaluation criteria and show that it captures vascular network properties
>superior to traditional metrics, such as the dice-coefficient. Secondly, we propose
>a differentiable form of clDice as a loss function for vessel segmentation. We
>find that training on clDice leads to segmentation with more accurate connectivity
>information, higher graph similarity and often superior volumetric scores.


dice_helpers.py contain conventional Dice loss function as well as clDice loss
and supplementary functions

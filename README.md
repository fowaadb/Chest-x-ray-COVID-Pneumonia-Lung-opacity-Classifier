# Chest-x-ray-COVID-Pneumonia-Lung-opacity-Classifier

This chest x ray classifier was trained on fastai using a pretrained resnet 50 model which was further finetuned for 3 epochs during which only the head was trained. Subsequently the whole model was trained for another 12 epochs generating a prediction accuracy of 95 percent on a set of Xray images showcasing various lung pathologies. These include lung opacity, Covid and viral pneumonia. The model was also trained on normal chest x rays.

Dataset link : https://www.kaggle.com/tawsifurrahman/covid19-radiography-database

Model deployed on binder, link: https://hub.gke2.mybinder.org/user/fowaadb-chest-x-city-classifier-n5mi1cns/voila/render/Chest_x_ray_classifier_(3)_(1)%20(1).ipynb?token=cvrm90vnSEGvmmbTkmXTGw

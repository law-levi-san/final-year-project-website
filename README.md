This project introduces an advanced automated system utilizing the Faster R-CNN architecture for precise detection of red blood cells (RBCs), white blood cells (WBCs), platelets, and the malarial parasite Plasmodium vivax in blood smear images. To enhance our dataset, we employ two types of Generative Adversarial Networks (GANs)-one to generate new, diverse images and Real ESRGAN to improve the resolution and quality of these images, thereby increasing the robustness and performance of our system. Aimed at aiding medical professionals in diagnosing blood disorders and malaria, our system provides rapid and reliable microscopic sample analysis. Extensive experimentation confirms our method's efficacy in accurately identifying various blood components and malaria parasites, demonstrating its potential to revolutionize medical diagnostics and significantly improve patient outcomes in hematology and infectious diseases.

The Blood cell dataset has been taken from the Shenggan BCCD dataset available on Github. The malarial dataset consists of the Plasmodium Vivax parasite within the images which can be found in 'malaria_images.zip' file. Blood cell images generated using GANs and the enhanced resolution using Real-ESRGAN can be found in 'Real-ESRGAN Enhanced Blood cell dataset.zip' file.


# Privacy preserving AI with a focus on Federated Learning
This is the repository containing the code for a project i did on Federated Learning. This was for the course IKT462 Artificial Intelligence in Society held at the University of Agder.

The goal of the paper was to get a better understanding of privacy preserving deep learning. Federated Learning was implemented to get some hands on experience with a Privacy Preserving deep learning technique.

The program simulates ten clients and a server in a federated learning network. The data has been divided into ten, so each client has unique training data. The aggregation method used by the server was FedAvg which is federated average.


## Frameworks
- [Flower Federated Learning](https://flower.dev/)
- [PyTorch](https://pytorch.org/)

## Dataset
[Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset?resource=download)

## Result
I managed to achieve an accuracy of 92.15% by measuring the centralized accuracy.

### Hyperparameters
![image](https://user-images.githubusercontent.com/75445926/233606713-ca274298-b24e-430e-bfba-72dcea8d812a.png)

### Accuracy
![result3_accuracy](https://user-images.githubusercontent.com/75445926/233606503-09ba0ec9-1b97-4ad8-9528-332d1c2174f1.png)

### Loss
![result3_losses](https://user-images.githubusercontent.com/75445926/233606518-050ad70c-6089-4fc3-897e-b5b78381509e.png)

### Confusion Matrix
![result3_confusionmatrix](https://user-images.githubusercontent.com/75445926/233606375-c55eb4d2-cf5a-4192-b7ea-7c34d6398de6.png)

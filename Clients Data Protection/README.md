# Protection of Personal Data of Clients 

## Stack Used:

- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy
- Scikit-Learn

## Objectives:

The objective of this project is to develop a data encryption algorithm for protecting sensitive client information in the context of a insurance company. The algorithm should transform the data in such a way that it becomes difficult to recover personal information from it. The key objective is to ensure that the quality of machine learning models is not compromised during the data transformation process.


## Findings

- Multiplying the features by an invertible matrix does not impact the quality of linear regression. The encrypted features, obtained by multiplying the original features with a random matrix, can still be used effectively for making predictions using linear regression models.
- The proposed algorithm successfully encrypts the data, ensuring the protection of client information. The encrypted data can be securely stored and transmitted without the risk of exposing sensitive details.
- The algorithm allows for data decryption at any given time, providing the flexibility to access the original data when needed.
- The randomness introduced in the algorithm ensures that each encryption process produces unique encrypted data. Without access to the algorithm's source code, it is extremely difficult to reverse-engineer the original data from the encrypted version.
- The implemented algorithm fully meets the objectives set for the project, ensuring the protection of client data while maintaining the quality of machine learning models.


For detailed analysis and code implementation, please refer to the [Jupyter Notebook](https://github.com/Shurgalivan/Portfolio/blob/main/Clients%20Data%20Protection/clients_data_protection.ipynb) provided in this repository.

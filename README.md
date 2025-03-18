# SP-colab-notebooks

This repository contains a collection of Google Colab notebooks for Image Denoising tasks. The notebooks demonstrate various denoising techniques using deep learning models like QCNN (Quaternion Convolutional Neural Network) and TCNN (Traditional Convolutional Neural Network). These notebooks are designed to help students and researchers understand and implement denoising models for image denoising tasks.

## Acknowledgments

## Acknowledgments

This repository is based on code from the [QuaternionCNN_Keras](https://github.com/XYZ387/QuaternionCNN_Keras/tree/master) repository. The original work provided the foundational model for **image denoising**, and I have added the **Spatial Attention Module (SAM)** and made several tweaks to improve the model's performance.

Special thanks to the contributors of the original repository for their great work, which laid the groundwork for this project.


## Notebooks Overview

| Notebook Name                  | Description                                  |
|---------------------------------|----------------------------------------------|
| `qcnn_SAM_denoising.ipynb`      | Quaternion CNN with Spatial Attention for denoising |
| `qcnn_denoising.ipynb`          | Quaternion CNN based denoising model         |
| `tcnn.ipynb`                    | Traditional CNN model for signal denoising   |
| `tcnn_SAM.ipynb`                | Traditional CNN with Spatial Attention Model for denoising |

## Getting Started

### 🔹 Open in Google Colab
1. Click on any `.ipynb` file to open it in Google Colab.
2. You can run the notebooks directly from Colab without any installation.

### 🔹 Running Locally
1. Clone the repository:
    ```bash
    git clone https://github.com/shineamor/SP-colab-notebooks.git
    ```
2. Make sure you have the required dependencies installed:
    ```bash
    pip install tensorflow numpy pandas matplotlib
    ```

### 🔹 Open in Google Colab
You can open the notebooks directly in Google Colab for interactive execution.

## Contributing

Feel free to fork the repository, make changes, and create a pull request. Contributions are always welcome!

Please ensure that any new code is properly tested and follows the existing style.

## Contact

For inquiries or feedback, feel free to reach out to sunshinetamores9@gmail.com.

# NeRF Code Implementation (in progress)

Original paper: https://arxiv.org/abs/2003.08934

- Uses TensorFlow1
    - Incomptaible with M1 Macs
        - Otherwise could remove CUDA (also unsupported) and run the file
            M1 mac also had problem setting up Python3.7 conda environment
    - Unsupported on Google Colab
    - So use Azure ML Studio and a Nvidia remote GPU compute [*TRY*]
# DSCCReFormer: Traffic Flow Prediction with Dual-Stream Criss-Cross Enhanced Rectified Transformer

This repository contains the implementation code for the paper "DSCCReFormer: Traffic Flow Prediction with Dual-Stream Criss-Cross Enhanced Rectified Transformer". Our model, DSCCReFormer, introduces an innovative approach for traffic flow prediction, leveraging the capabilities of dual-stream processing and criss-cross attention mechanisms within a rectified transformer framework.The frameword of our model showing as below:
<img width="367" alt="image" src="https://github.com/superca729/DSCCReFormer/assets/54494470/00647675-1472-4629-850f-73b695ded129">

## Installation

Before running the DSCCReFormer model, ensure that you have the baseline model PDFormer set up with https://github.com/BUAABIGSCity/PDFormer. Follow these steps to get started:

### Prerequisites

- Ensure you have Python installed on your system.
- It's recommended to use a virtual environment for this project.

### Setting Up the Environment

1. Clone the PDFormer repository from its official source.
2. Navigate to the PDFormer directory:

    ```bash
    cd path/to/PDFormer
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

### Adding DSCCReFormer

1. Clone this repository or download the DSCCReFormer code.
2. Place the `DSCCReFormer.py` file into the PDFormer's directory at `./PDFormer/libcity/model/traffic_flow_prediction/`.

    ```bash
    mv path/to/DSCCReFormer.py ./libcity/model/traffic_flow_prediction/
    ```

## Usage

To run the DSCCReFormer model, follow these steps:

1. Activate your Python environment if you're using one.
2. Navigate to the PDFormer directory.
3. Run the model using the appropriate command, as you would with PDFormer, but specify DSCCReFormer as the model.

## Additional Notes

- Ensure that all paths and dependencies are correctly set up as per the PDFormer's documentation.
- If you encounter any issues, refer to the `README.md` and documentation of PDFormer for troubleshooting steps.

## Citation

If you use this code or our DSCCReFormer model in your research, please cite our paper:

> [Full citation of the "DSCCReFormer: Traffic Flow Prediction with Dual-Stream Criss-Cross Enhanced Rectified Transformer" paper]


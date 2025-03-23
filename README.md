# Neural Network from Scratch for Handwritten Digit Classification 

This project implements a fully connected Neural Network from scratch to classify handwritten digits (0-9). It is trained with Backpropagation and Gradient Descent, achieving ~95% accuracy

 

## Project Overview  
This project implements a **Neural Network from scratch** to classify **handwritten digits (0-9)** using the **MNIST dataset**. The model is trained using **Backpropagation** and optimized using **Gradient Descent**, achieving **93.06% accuracy** on test data.  


## Dataset  
The **MNIST dataset** consists of:  
- **8x8 grayscale images** of handwritten digits (0-9)  
- **1797 samples**  
- **Target Variable:** Digit class (`0-9`)  


## Implementation Steps  
1. **Data Preprocessing**  
   - Normalizing pixel values (`0-16` → `0-1`)  
   - Flattening images 
2. **Neural Network Architecture**  
   - **Input Layer:** 64 neurons  
   - **Hidden Layers-2:** Fully connected layers with activation functions  
   - **Output Layer:** 10 neurons (Softmax activation for multi-class classification)  

3. **Training the Model**  
   - Forward and backward propagation  
   - **Cross-Entropy Loss** as the cost function  
   - **Gradient Descent** for optimization  

4. **Model Evaluation**  
   - Measuring **accuracy on test data**  
   - Visualizing **loss and accuracy curves**  


## Requirements  
Install the required dependencies before running the notebook:  

```bash
pip install numpy pandas matplotlib sklearn
```
sklearn is used only to import the data set and to split the data to training and testing

## How to Run the Project  
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/neural-network-handwritten-digits.git
   ```
2. Navigate to the project folder:  
   ```bash
   cd neural-network-handwritten-digits
   ```
3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook nn_handdigits.ipynb
   ```

## Results & Insights  
- The **Neural Network achieves ~95% accuracy** on handwritten digit classification.  
- The model successfully learns digit representations through **gradient-based optimization**.  
- Performance is visualized using **loss and accuracy curves**.  

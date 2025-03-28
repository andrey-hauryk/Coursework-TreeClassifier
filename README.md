# Branch Predictor Using Decision Trees

## Overview
This project focuses on solving the branch prediction classification task using decision trees. The study includes an analysis of static and dynamic branch predictors, classical prediction algorithms, and key machine learning methods. The project explores decision tree construction and the random forest algorithm.

## Project Structure
1. **Branch Predictors**: Explanation of branch predictors in microprocessor architectures, including static and dynamic prediction methods.
2. **Machine Learning Methods**: Overview of supervised, unsupervised, and semi-supervised learning approaches.
3. **Decision Trees**: Description of decision tree construction algorithms and stopping criteria.
4. **Random Forest**: Implementation of the random forest algorithm to improve prediction accuracy.
5. **RISC-V Simulator**: Usage of the RISC-V simulator to collect data for training models.
6. **Dataset Collection**: Modification of the simulator to log branch predictor data and store it in CSV format.
7. **Model Training and Evaluation**: Splitting the dataset into training and testing sets (80:20 ratio) and evaluating accuracy using decision trees and random forests.

## Results
- Decision tree model accuracy analysis on training and testing datasets.
- Comparison of decision tree and random forest prediction accuracy.

## Installation & Usage
1. Install the RISC-V Simulator (by hehao98).
2. Modify `simulator.cpp` to enable logging of branch prediction data.
3. Compile and execute the simulator.
4. Process the generated CSV dataset.
5. Train decision tree and random forest models on the dataset.
6. Evaluate model accuracy and analyze results.

## Technologies Used
- RISC-V Simulator
- Python (pandas, scikit-learn, matplotlib)
- Machine Learning (Decision Trees, Random Forests)

## Contributors
- Author: Andrey Hauryk

## License
This project is licensed under the MIT License.


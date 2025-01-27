# MATLAB GUI Project

## Overview
This project is a MATLAB-based GUI application designed to streamline data analysis and regression tasks. It features an intuitive interface and integrates support for Support Vector Regression (SVR) with multiple kernels. The project provides three main functionalities:

1. **Data Visualization, Normalization, and Splitting**
   - Visualize datasets using various plots.
   - Normalize data for better model performance.
   - Split data into training and testing sets.

2. **Training SVR Kernels**
   - Train and compare multiple SVR kernels (e.g., linear, polynomial, RBF).
   - Visualize the predicted line (for 2D data) or surface (for 3D data).

3. **Evaluation Metrics**
   - Evaluate model performance using:
     - Coefficient of Determination (R²)
     - Mean Squared Error (MSE)
   - Visualize predictions (`y_pred`) against true values (`y_true`).

## Features
- User-friendly GUI built with MATLAB.
- Support for different SVR kernels.
- Interactive data visualization and regression analysis.
- Real-time plotting and evaluation of results.

## Requirements
To run this project, ensure the following:

- MATLAB R2021a or later
- Statistics and Machine Learning Toolbox

## Usage

### Running the Application
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/matlab-gui-project.git
   ```
2. Open MATLAB and navigate to the project folder.
3. Run the main file:
   ```matlab
   main.m
   ```
4. Interact with the GUI to visualize data, train SVR models, and evaluate results.

### Screenshots
![GUI Screenshot](images/GUI_Screenshot.png)

## Project Structure
```
matlab-gui-project/
├── data/                 # Sample datasets
├── images/               # Screenshots and visuals
├── src/                  # Source code
│   ├── main.m            # Entry point of the GUI
│   ├── svr_training.m    # SVR training logic
│   ├── data_split.m      # Data splitting functions
│   └── evaluation.m      # Model evaluation metrics
├── README.md             # Project documentation
└── .gitignore            # Ignored files for Git
```

## How It Works
1. **Data Visualization**:
   - Load your dataset using the GUI.
   - Visualize data using scatter plots or histograms.
2. **SVR Training**:
   - Choose a kernel type (e.g., linear, polynomial, RBF).
   - Train the model and visualize predictions.
3. **Evaluation**:
   - Display R² and MSE metrics.
   - Compare predicted values with actual values through plots.

## Contribution
Contributions are welcome! If you'd like to improve this project, follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add some feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For questions or feedback, feel free to reach out:
- **Email**: your-email@example.com
- **GitHub**: [your-username](https://github.com/your-username)

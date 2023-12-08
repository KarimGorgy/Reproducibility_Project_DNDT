To set up and run the provided Python code, which includes training decision tree models and a Deep Neural Decision Tree (DNDT), follow these instructions:

1. Python Environment: Ensure your Python environment, preferably a virtual environment, is active. The version used was python 3.11.3 This isolates your project dependencies.

2. Install Necessary Libraries: The code requires several Python libraries. Install them using pip:
   
   pip install numpy pandas sklearn torch matplotlib plotly torchmetrics graphviz
   
   These libraries provide functionalities for machine learning, numerical computations, data handling, visualization, and metrics computation used in the reproduction and further implementations of the code.

3. Datasets Preparation: Make sure the datasets like the Iris dataset, Haberman's survival dataset, and the poker-hand dataset are accessible in the paths referenced in your code. These datasets are the ones we used for training and evaluating the models.

4. Running the Scripts: Execute the Python scripts sequentially. The code first trains traditional decision tree models on different datasets in the demo_dt.ipynb file and then implements and trains a DNDT in the demo_modified.ipynb which contains the reproduction of the chosen paper's code, and experimentaiton. Demo_modified_2.ipynb explores the effect of using different optimizers, and the impact of different numbers of cutpoints on the results as well as normalization. Running the scripts in order ensures proper initialization of variables and models.

5. Visualization and Evaluation: The code includes functions for plotting decision boundaries and evaluating model performance using accuracy and F1 score. After running the scripts, review these visualizations and metrics to assess the models' effectiveness.

6. Modifications and Testing: Experiment with different configurations, such as learning rates or batch sizes, to observe how they affect model performance. The code allows for such flexibility, enabling a deeper understanding of the models' behavior under various parameters.

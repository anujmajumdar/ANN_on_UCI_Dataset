# ANN_on_UCI_Dataset
An Artificial Neural Network was trained on the Breast Cancer Dataset of the UCI Machine Learning Repository. Comparisions of the error were made on using different activation functions.
<br>The implementation is done from scratch and no external machine learning libraries were used. The neural network is trained using different activation functions such as 
<ul>
    <li>sigmoid <img src="https://www.gstatic.com/education/formulas2/397133473/en/sigmoid_function.svg">
    <li>tanh  $ y = \frac{e^{x}-e^{-x}}{e^{x}+e^{-x}} $
    <li>ReLU $ y = max(0, x) $
</ul>
    Training and testing error sum for different activation functions is calculated and compared to get the best activation function on the given dataset.

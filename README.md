
# Resource-Allocation-in-5G-Network-using-Machine-Learning

This project dives into the potential of machine learning (ML) to revolutionize bandwidth
management in 5G networks.. A comparative analysis of prominent models, including regression
algorithms and neural networks, evaluates their potential to optimize resource allocation while
ensuring high Quality of Service and network efficiency. Employing key metrics like Mean Square
Error and R-Squared, this study identifies the most suitable models for specific scenarios.


## Requirements

The major software requirements are:

        1. Python
        2. Python Libraries :
                ● Numpy
                ● Pandas
                ● Matplotlib
                ● plotly
                ● Scikit- Learn
                ● Tensorflow
        3.IDE :
                ● Google Colab
                ● VS Code
## Methodology
Data Acquisition and Preprocessing:

        1. Dataset Download  :A relevant dataset (400 rows) from Nokia containing features related to 5G network resource allocation, such as signal strength, required                                       bandwidth, latency,and allocated resources.
        2. Data Augmentation :To increase data size and potentially improve model performance,create a new dataset (800 rows) by applying data augmentation techniques                                        suitable for the specific features.
        3. Feature Engineering :
                a. Case 1: Combine signal strength and required bandwidth into a single feature and resource allocation as another separate feature.
                b. Case 2: Combine latency and latency signal interaction into a single feature and resource allocation as another separate feature.
        4. Data Split : Divide each dataset (400 rows and 800 rows) into training, validation, and test sets using a consistent split ratio (e.g., 70/20/10).
Model Training and Evaluation :

        5. Model Selection : Implement and train various machine learning models on each dataset and case combination:
                a. Linear Regression
                b. Polynomial Regression
                c. Decision Tree
                d. Random Forest
                e. Gradient Boosting Regressor
                f. Support Vector Machine
                g. KNN
                h. Neural Networks with different epochs(100, 200, 300)
        6. Evaluation Metrics : Use appropriate metrics to evaluate the performance of each model,including:
                a. Mean Squared Error (MSE) to measure the average squared difference betweenpredicted and actual resource allocation.
                b. R-Squared to measure the proportion of variance in the actual resource allocation explained by the model.
## Flow Chart

![alt text](https://github.com/lohithnh/Resource-Allocation-in-5G-Network-using-Machine-Learning/blob/main/FlowChart.png?raw=true)
## Results

![alt text](https://github.com/lohithnh/Resource-Allocation-in-5G-Network-using-Machine-Learning/blob/main/Result400Rows.png?raw=true)

![alt text](https://github.com/lohithnh/Resource-Allocation-in-5G-Network-using-Machine-Learning/blob/main/Result800Rows.png?raw=true)
## Conclusion

● For the models trained on the 400-row dataset, Random Forest and Neural Network (300 epochs) have the lowest MSE and highest R-Squared values, suggesting that they are thebest performing models on this dataset.

● For the models trained on the 800-row dataset, Gradient Boosting Regressor and Neural Network (200 epochs) have the lowest MSE and highest R-Squared values, suggesting that
they are the best performing models on this dataset.

● It is interesting to note that the performance of the Neural Network models generally improves as the number of epochs increases, while the performance of the other models does not. This suggests that the Neural Networks may be more prone to overfitting, and that it is important to carefully choose the number of epochs to train them for.
## References

[1] Z. H. Hussien and Y. Sadi, “Flexible radio resource allocation for machine type communications in 5g cellular networks,” in 2018 26th Signal Processing and Communications Applications Conference (SIU), May 2018, pp. 1–4

[2] 3GPP, “Physical channels and modulation (release 16),” 3GPP TS 38.211 Technical specification V16.1.0, Tech. Rep., Mar, 2020. Resource Allocation in 5G Platoon Communication: Modeling, Analysis and Optimization

Kaggle – www.kaggle.com

Youtube – www.youtube.com

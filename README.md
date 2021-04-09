# E2E-Regression


# Model Description
The model and code description is mentioned in the table below:
<table>
    <tr>
        <td>DL Framework</td>
        <td>Keras</td>
    </tr>
        <tr>
        <td>Keras version</td>
        <td>2.4.3</td>
    </tr>    
    <tr>
        <td>Libraries</td>
        <td>Numpy, pandas, pyarrow</td>
    </tr>    
    <tr>
        <td>Layers</td>
        <td>Conv2D, Batchnormalization, Flatten, Dense</td>
    </tr>    
    <tr>
        <td>Activation functions</td>
        <td>ReLU, Linear</td>
    </tr>    
    <tr>
        <td>Optimizer</td>
        <td>Adam</td>
    </tr>    
    <tr>
        <td>Learning Rate</td>
        <td>0.0001</td>
    </tr>    
    <tr>
        <td>Batch size</td>
        <td>32</td>
    </tr>    
    <tr>
        <td>Epochs</td>
        <td>90</td>
    </tr>    
    <tr>
        <td>Loss function</td>
        <td>Mean Squared error (mse)</td>
    </tr>    
    <tr>
        <td>Metrics</td>
        <td>Mean Absolute Percentage Error (mape), Mean Squared Error (mse), Mean Absolute Error (mae)</td>
    </tr>    
      
</table>

# Results
<table>
    <tr>
        <td>Dataset</td>
        <td>Loss</td>
        <td>mape</td>
        <td>mse</td>
        <td>mae</td>
    </tr>
    
    <tr>
        <td>Train</td>
        <td>0.0030</td>
        <td>1.1389</td>
        <td>0.0030</td>
        <td>0.0436</td>
    </tr>
    
    <tr>
        <td>Validation</td>
        <td>0.0483</td>
        <td>4.8653</td>
        <td>0.0483</td>
        <td>0.1885</td>
    </tr>
       
</table>


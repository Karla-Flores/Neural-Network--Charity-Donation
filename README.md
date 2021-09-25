<h1>Neural-Network--Charity-Donation</h1>
<hr>
<h3>Background</h3>
<hr>
<p align = 'justify'>This project aims to use a deep-learning neural network with TensorFlow library to analyze and classify the success of charitable donations from Alphabet Soup.</p>
<h3>Results</h3>
<hr>
<h4>Data Preprocessing</h4>
<ul>
  <li><p align = 'justify'>The columns 'EIN' and 'NAME' were dropped.</li>
  <li><p align = 'justify'>The target variable was the column 'IS_SUCCESSFUL'; this feature is the one that is going to be predicted and determine the success rate of the data.</li>
  <li><p align = 'justify'>The categorical variables were encoded with 'pd.get_dummies()'.</li>
  <li><p align = 'justify'>While the preprocessing, the columns 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', 'ASK_AMT' are considered as feature values.</p></li>
</ul>
<h4>Model Evaluation 1</h4>
<ul>
  <li><strong>Compiling, Training, and Evaluating the Model</strong></li>
  <p align = 'justify'>The attempt at compiling a neural network consisted of layers of 80 neurons and the second one of 30; both layers had relu activation functions.In addition, the output layer had a sigmoid activation function. The assembled model had the Adam optimization algorithm, and the fitting model had a validation split of 0.15 and 100 epochs.</p>
  <img src='https://github.com/Karla-Flores/Neural-Network--Charity-Donation/blob/main/ScreenShots/M1.png'>
The results for this model were:
<ul>
<li>Loss: 0.5653</li>
<li>Accuracy: 0.7291</li>
<li>Recall: 0.7826</li>
</ul>
  <br>
  <li><strong>Graphics</strong></li>
  <table>
    <tbody>
     <tr>
       <td><img src='https://github.com/Karla-Flores/Neural-Network--Charity-Donation/blob/main/ScreenShots/M1_A.png'></td>
       <td><img src='https://github.com/Karla-Flores/Neural-Network--Charity-Donation/blob/main/ScreenShots/M1_L.png'></td>
     </tr>
    </tbody>
  </table>
</ul>
<h3>Model Evaluation 2</h3>
<hr>
<ul>
  <li><strong>Compiling, Training, and Evaluating the Model</strong></li>
  <p align = 'justify'>The attempt at compiling a neural network consisted of layers of 1450 neurons and the second one of 80; both layers had relu activation functions.In addition, the output layer had a sigmoid activation function. The assembled model had the Adam optimization algorithm, and the fitting  model had a validation split of 0.15 and 100 epochs.</p>
      <img src='https://github.com/Karla-Flores/Neural-Network--Charity-Donation/blob/main/ScreenShots/M2.png'>
  The results for this model were:
<ul>
<li>Loss: 0.5760</li>
<li>Accuracy: 0.7318</li>
<li>Recall: 0.8021</li>
</ul>
  <br>
  <li><strong>Graphics</strong></li>
    <table>
    <tbody>
     <tr>
       <td><img src='https://github.com/Karla-Flores/Neural-Network--Charity-Donation/blob/main/ScreenShots/M2_A.png'></td>
       <td><img src='https://github.com/Karla-Flores/Neural-Network--Charity-Donation/blob/main/ScreenShots/M2_L.png'></td>
     </tr>
    </tbody>
  </table>
</ul>
<h3>Model Evaluation 3</h3>
<hr>
<ul>
  <li><strong>Compiling, Training, and Evaluating the Model</strong></li>
  <p align = 'justify'>The attempt at compiling a neural network consisted of layers of 3 neurons, the second one of 15 and the third one of 3; all layers had relu activation functions. In addition, the output layer had a sigmoid activation function. The assembled model had the Adam optimization algorithm, and the fittin mode
    The results for this model were:
<ul>
<li>Loss: 0.5613</li>
<li>Accuracy: 0.7255</li>
<li>Recall: 0.7732</li>
</ul>l had a validation split of 0.15 and 100 epochs.</p>
      <img src='https://github.com/Karla-Flores/Neural-Network--Charity-Donation/blob/main/ScreenShots/M3.png'>
  <br>
  <li><strong>Graphics</strong></li>
    <table>
    <tbody>
     <tr>
       <td><img src='https://github.com/Karla-Flores/Neural-Network--Charity-Donation/blob/main/ScreenShots/M3_A.png'></td>
       <td><img src='https://github.com/Karla-Flores/Neural-Network--Charity-Donation/blob/main/ScreenShots/M3_L.png'></td>
     </tr>
    </tbody>
  </table>
</ul>


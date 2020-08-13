<h2 align = "center"><font color='black'> <b>Histopathological Image Classification using Convolutional Neural Network</b></font></h2> <h4 align = "right"><font color='purple'> DSML@2020</font></h4>

## <font color='blue'> <b>**Introduction** </b></font>

Cancer begins when healthy cells in the breast change and grow out of control, forming a mass or sheet of cells called a tumor. A tumor can be cancerous or benign. A cancerous tumor is malignant, meaning it can grow and spread to other parts of the body. A benign tumor means the tumor can grow but will not spread.<a href="https://www.cancer.net/cancer-types/breast-cancer/introduction#:~:text=Cancer%20begins%20when%20healthy%20cells,grow%20but%20will%20not%20spread."> (Source, [caner.net]) </a>
<table><tr>
<td> <img src="data/benign.png" alt="Benign Histopath" style="width: 150px;"/> </td>
<td> <img src="data/malignant.png" alt="malignant Histopath" style="width: 150px;"/> </td>
</tr><caption><b>Histopathological Image</b></caption>
</table>

## <font color='blue'>**The problem statement**</b></font>


Identifying the presence or absence of benign or malignant tumors from `640 x 470px` from a digital histopathology images. One key challenge is that there exist varaiblity in size and shape of the nuclei and traditonal ML algorithms needs greater fine tuning of hand-crafted features. It's known now, as the amount of data increases traditional ML algorithms fails to capture all the detailing that hinders from incing closer to human accuracy.

In this lesson you will be classifying histopathological images using this <a href="https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/">BrekHis</a> dataset.
So, as part of the task you need to process this data by analyzing the images in the two categories and then creating a model that classifies these images into `benign` and `malignant`. 

You'll follow these steps:

<ol>
    <font color='blue'>
  <li> Explore the Example Data of benign and malignant Histopathological images</li>
  <li>Build a model</li>
    <ol>
        <li> Approach 1: Shallow Network
        <li> Approach 2: Convolutional Neural Network</li>
     </ol>
  <li>Training the above two approaches
  <li>Evaluating the model accuracy</li>
        </font>
</ol>

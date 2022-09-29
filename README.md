# Hate Speech Detection with Transformers (BERT & XLNet)

## Objective
With accordance to general rules of social media platforms, some posts which include hate-speech are prohibited.
This phenomenon is more important in twitter as users can stay ananymose only sharing a line of words. In this project two of the most common Transformer models Bidirectional Encoder Representations from Transformers (BERT) and XLNet.

## Results
Results are grouped under the appropriate model.

<table>
<tr>
<td> Model Name</td>
<td> Cost Curve</td>
<td> Performance Curve</td>
</tr>
<tr>
<td> BERT </td>
<td> <img src="https://github.com/SajjadPSavoji/Hate_Speech_Detection/blob/main/Assets/Screen%20Shot%202022-09-29%20at%202.33.38%20PM.png"> </td>
<td> <img src="https://github.com/SajjadPSavoji/Hate_Speech_Detection/blob/main/Assets/Screen%20Shot%202022-09-29%20at%202.33.57%20PM.png"> </td>
</tr>
<tr>
<td> XLNet </td>
<td> <img src="https://github.com/SajjadPSavoji/Hate_Speech_Detection/blob/main/Assets/Screen%20Shot%202022-09-29%20at%202.34.40%20PM.png"> </td>
<td> <img src="https://github.com/SajjadPSavoji/Hate_Speech_Detection/blob/main/Assets/Screen%20Shot%202022-09-29%20at%202.34.57%20PM.png"> </td>
</tr>
</table>

<table>
  <tr>
    <td> Model Name </td>
    <td> Data Partition </td>
    <td> Accuracy </td>
    <td> Precision </td>
    <td> Recall </td>
    <td> F1-Score </td>
  </tr>
  <tr>
    <td> BERT </td>
    <td> Train </td>
    <td> 0.70 </td>
    <td> 0.65 </td>
    <td> 0.95 </td>
    <td> 0.65 </td>
  </tr>
    <tr>
    <td> BERT </td>
    <td> Test </td>
    <td> 0.48 </td>
    <td> 0.44 </td>
    <td> 0.97 </td>
    <td> 0.61 </td>
  </tr>
    <tr>
    <td> XLNet </td>
    <td> Train </td>
    <td> 0.70 </td>
    <td> 0.60 </td>
    <td> 0.88 </td>
    <td> 0.70 </td>
  </tr>
      <tr>
    <td> XLNet </td>
    <td> Test </td>
    <td> 0.56 </td>
    <td> 0.49 </td>
    <td> 0.84 </td>
    <td> 0.62 </td>
  </tr>
</table>

## Resources
- [BERT in Pytorch](https://neptune.ai/blog/how-to-code-bert-using-pytorch-tutorial)
- [XLNet in Pytorch](https://www.kaggle.com/code/jaskaransingh/xlnet-fine-tuning-with-pytorch)
- [Hateful Conduct Policy of Twitter](https://help.twitter.com/en/rules-and-policies/hateful-conduct-policy)

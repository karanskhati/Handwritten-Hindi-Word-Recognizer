# Hindi OCR || Mosaic'21 Round-1:
## Introduction:
This Project Hindi OCR(Optical Character Recognizer) will allow user to convert Hindi Handwritten Characters to Text form.
According to the Problem Statement, the OCR must recognize Single Words regardless of their Length. 
Image Correction and Letter Segmentation is performed using various OpenCv Techniques. 
While the Letter Recognition was performed using Deep Learning(DL) and Convolutional Neural Networks(CNN) on 
the [Devnagri Hindi Dataset](https://www.kaggle.com/jhashanku007/devnagri-hindi-dataset "Hindi Dataset").
This Trained Model achieved a Validation accuracy of 98.7% and Testing accuracy of 93.4%.

## Key Features:
	1> Rotation Correction upto 45 Degrees
	2> Shadow Correction 
	3> Blurred Images are also read
These Features completes the given Problem Statement of Mosaic'21 Round-1.

## More Features:
	1> Muliple Words in a Line are also recognized
	2> A Whole Paragraph is also recognized accurately
These Features completes the Hindi OCR and were used to score BONUS points.
	
## Running the OCR:
All you need to do is Clone the Repo, Open the main.ipynb file-
Insert the image location in cv2.imread("<location>"),
Mark the "Contains_only_one_word" to true or false according to the requirement.
Run the file :)

HAPPY TESTING !!!!!!!!!!



## Team Blue-Cheese:

<table>
   <td align="center">
      <a href="https://github.com/TheKeH20">
         <img src="https://avatars.githubusercontent.com/u/60650819?v=4" width="100px;" alt=""/>
         <br />
         <sub>
            <b>Keshav Yadav</b>
         </sub>
      </a>
      <br />
   </td>
   <td align="center">
      <a href="https://github.com/aryanishan1001">
         <img src="https://avatars.githubusercontent.com/u/54237311?v=4" width="100px;" alt=""/>
         <br />
         <sub>
            <b>Aryan Ishan</b>
         </sub>
      </a>
      <br />
   </td>
   <td align="center">
      <a href="https://github.com/karanskhati">
         <img src="https://avatars.githubusercontent.com/u/77573210?v=4" width="100px;" alt=""/>
         <br />
         <sub>
            <b>Karan Singh Khati</b>
         </sub>
      </a>
      <br />
   </td>
</table>

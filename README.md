## sudoku solver CNN

Hi! I created a sudoku solver ai. First the software prepoccesses an image of a sudoku and reads out the numbers. The neural network recognizes the numbers in the image and writes it to a matrix. The model is trained and tested on the dataset chars74k (http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/), which I modified so only the data with numbers is used. I achieved an accuracy of 98,32 %. After that the sudoku is solved with a backtracking algorithm.

<br>
If you want to use my dataset, just download the zipfiles and extract them to your project folder. The data for testing and training are built automaticially. 
</br>

<br>
In the pictures you can see the preprocess of the sudoku and the result. 
</br>
<div>
    <img src="https://user-images.githubusercontent.com/89871999/136822150-c1289640-ee51-4beb-b44d-b13dd6230c5d.jpg" width="200" height="200" alt="" style="margin:5px" align="left">
    <img src="https://user-images.githubusercontent.com/89871999/136822406-7dee2c64-0552-45e1-a7d1-25a472ef8402.jpg" width="200" height="200" alt="" style="margin:5px" align="left">
    <img src="https://user-images.githubusercontent.com/89871999/136822462-9a74d431-7e0d-48c5-835f-5132943846aa.jpg" width="200" height="200" alt="" style="margin:5px" align="left">
   
</div>                                                                         

<div>
     <img src="https://user-images.githubusercontent.com/89871999/136822492-95c177ee-7141-4820-950a-cdba9eaa52f0.jpg" width="200" height="200" alt="" style="margin:5px" align="left">
    <img src="https://user-images.githubusercontent.com/89871999/136823010-8c3633b3-6277-4587-9f71-21eac3d42c00.jpg" width="200" height="200" alt="" style="margin:5px" align="left">
    <img src="https://user-images.githubusercontent.com/89871999/136823072-48975c20-c764-4982-81e6-feb6a2b51015.jpg" width="200" height="200" alt="" style="margin:5px" align="left">
</div>


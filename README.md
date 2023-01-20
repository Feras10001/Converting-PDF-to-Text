# Converting-PDF-to-Text
---------------------------------------------------------

**Project motivation:** Creating python script that can coonvert PDF to text file. The conversion was done using two different methods: Direct and Indirect.
- The Direct method is using PyPDF2 libraries to directly convert a PDF file to text. This was done by having a scanned PDF file named (coffee.pdf) as an input and then extracting the text in from the file, which can be saved in text document.
- The indirect method is using pytesseract and pdf2image libraries to convert the scanned PDF to an image first hen extract the text from the image. This is used with a file named (Work1.pdf), where the first method doesn't apply

----------------------------------------------------------

**Requirements:**
The following libraries are included:
* PyPDF2
* pytesseract
* pdf2image
* PIL

----------------------------------------------------------

**Files in the repository:**
* [Converting PDF to Text using PyPDF2.ipynb]: containes the full code for the direct method
* [Converting PDF to Text using pyresseract.ipynb]: containes the full code for the indirect method
* [coffee.pdf & Work1.pdf]:scanned PDF files

-----------------------------------------------------------------

**Results:**
The result are demonstrated in the both python scripts 

-------------------------------------------------------------------
**Disclaimer & acknowledgement**
The main codes can be found in GeeksforGeeks webiste and you can check the links below. I only added some comments in the codes for further clarification + minor modifications to make it easier to use. I would also like to thank GeeksforGeeks for having incridable resources that helped me in the Python coding. I advise checking their website :smile:
https://www.geeksforgeeks.org/convert-pdf-to-image-using-python/?ref=gcse
https://www.geeksforgeeks.org/how-to-extract-text-from-images-with-python/
https://www.geeksforgeeks.org/encrypt-and-decrypt-pdf-using-pypdf2/
https://www.geeksforgeeks.org/working-with-pdf-files-in-python/

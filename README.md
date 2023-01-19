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

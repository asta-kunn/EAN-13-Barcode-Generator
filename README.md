# EAN-13-Barcode-Generator
This program made by a Tkinter GUI-based object-oriented Python program for printing EAN-13 barcodes on computer screen and saving the image as a  PostScript file. A PostScript file can be printed directly on a laser printer or converted to  a PDF file. A PostScript file can also be viewed by a software tool like GSview.


Your program has to do the following steps:

    1. Ask the user to enter a file name for writing the PostScript output. Validate the 
    input accordingly. If the input is wrong, prompt the user again. The Canvas 
    widget has a method for creating PostScript data.
    
    2. Ask the user to enter a code consisting of 12 decimal digits. Validate the input 
    accordingly. If the input is wrong, prompt the user again.
    
    3. Calculate the checkdigit according to the EAN system.
    
    4. Print on screen (canvas) the correct EAN barcode for the 12 input digits and the 
    checkdigit. The image is also written to the file from Step (1) in the PostScript 
    format. Your barcode should consist of at least four different colors, like the 
    examples given below.

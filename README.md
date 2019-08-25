# vk-ocr
This repository has code for every language to extract text from an image

Backend of Optical Recognition Reader

Have you ever concerned about the working of desktop/ mobile scanner where it extracts text from images.
In this article, we will be seeing the backend working of Optical Character Recognition which is popularly known as OCR.
Here I will be using C# (C Sharp) language to implement Text Extraction from an image and will discuss why I choose C# in a later section.

OCR:

 

•	Optical Character Recognition is a method of converting a handwritten or typed Image, PDF to the readable text document. Simply it extracts text from an image of any format and creates a text file with those texts. 
•	It's commonly used in Information Entry in many industries from passport sectors to banking invoice reader. 

Why C# :
C sharp is platform-independent Object-oriented language developed by Anders at Microsoft in 2000 and later bought by Java's Oracle. It's very powerful and combinative syntax holder from C++ and Java, where learning C# gives broad knowledge in both former languages. It is a general-purpose language designed for developing apps on the Microsoft platform and requires the .NET framework on Windows to work. Although the .NET framework supports several other coding languages, C# has quickly become one of the most popular. It's widely used in the development of windows application and console software and takes a huge leap on web development. 
Developing OCR tool using C#
In this article, we will be dealing with code using the Visual Studio IDE. It's robust and fast-responsive software. I will use IronOcr package in my code. There are many other open-source OCR packages like Tesseract, NSOCR( NicomSoft), Aspose, etc.

Working:
•	It takes an image from the specified path, scan it and remove the unwanted pictorial kinds of stuff, read the text line by line of the specified language and put the characters in a prescribed order to the Buffer.
•	Then the characters in the output buffer flash out the text from the image to the window console.
Try Me :
•	Open Visual Studio and create a new project on Windows Console to create a console application for OCR software.
•	To install IronOcr package for a current project, Go to Project -> Manage NuGet packages, search for IronOcr module and install it.
•	For more related codes from my repository, visit: github.com/jsvigneshkanna/vk-ocr


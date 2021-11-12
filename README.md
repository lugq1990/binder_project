# binder_project
This project is used for binder


### install

#### tesseract

When try to install tesseract, we have to use **conda** to force install of it, otherwise we wont' make it workable, use this command: `conda install -c conda-forge tesseract`.  So after we have used conda to install tesseract, then we could even use both **command line** like `tesseract imagename outputbase [-l lang] [--oem ocrenginemode] [--psm pagesegmode] [configfiles...]` or with python code module: `pytesseract` to get the output of the image.

#### pytesseract

We could use the file requirements.txt to install our required packages.
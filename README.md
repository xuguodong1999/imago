I patch Imago to compile on ubuntu-20.04. 

I use package manager to install boost, indigo, freetype and fontconfig, and link local opencv4(set OpenCV_DIR from cmake-gui).

I disable test-build on shared libraries for fPIC issues on boost thread library(Static build remains).

This project is a good example on how to design an OCR system for chemical-structual-formulas. I may use some ideas on my COCR project with full capacity on texts.

# Tissue Analyzer (TA)

Historically, TA was developed in Java (to integrate with the ImageJ/FIJI ecosystem). More recently, I started developing a Python version of Tissue Analyzer, this choice is mainly motivated by the ease of use of deep learning in Python (as compared to Java) and by the numpy library that allows for very efficient, yet simple, handling of images/matrices.

[Tutorial for the Java version of TA](https://github.com/baigouy/tissue_analyzer/blob/main/TA_tutos/TA_java.md)

- Advantages:
  - Can be used as an ImageJ/FIJI plugin
  - Still has more functionalities than the python version
- Drawbacks:
  - Support is discontinued 
  - Closed source
  - Classical watershed segmentation of cells (no deep learning)

[Tutorial for the Python version of TA](https://github.com/baigouy/tissue_analyzer/blob/main/TA_tutos/pyTA.md)

- Advantages:
  - Open-source
  - Uses deep learning based segmentation
  - Under active development
- Drawbacks:
  - Some emblematic functionalities of TA are missing/under development (cell divisions, cell death) 
  - Analyses may take longer (Python is much slower than Java for some things, such as accessing pixels of an image)
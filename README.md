<img width="378" alt="LUT_University_Logo2" src="https://user-images.githubusercontent.com/98688844/190965507-af11e394-f6c1-409c-9901-cf8e23e4b668.png">


This repository comprises all the code and data necessary to reproduce the results of the paper titled "The development of a design-oriented machine learning surrogate model for carbon capture with the implementation of explainable artificial intelligence."
/n This is an original work developed by researchers at LUT University. All rights reserved for LUT University. 

# How to run

1.	Make sure all necessary python libraries are installed: Numpy, Pandas, Scipy, Matplotlib, Seaborn, Scikit-learn, TensorFlow, and shap.
2.	Download the `data` folder, which contains the data used for this code.
3.	Run the `makedirectories.ipynb` notebook to make the required directories.
4.	Run each HPT notebook (`DT_HPT.ipynb`, `RF_HPT.ipynb`, `XG_HPT.ipynb`, `SV_HPT.ipynb`, and `DN_HPT.ipynb`) to see how the hyperparameters of each machine learning model are optimized. (Optional)
5.	Run the `Main.ipynb` to reproduce the paper results. 
Note that the size of the Main.ipynb notebook is too large to be rendered on GitHub; you can copy and paste its directory (https://github.com/Kasra-aln/Surrogate-Machine-Learning-CCS/blob/main/Main.ipynb) to https://nbviewer.org/ and see it there. It will take some minutes to load.



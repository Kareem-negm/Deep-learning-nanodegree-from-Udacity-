# Introduction fo deep learning

Created: Mar 5, 2021 1:16 PM

```python
#عشان تعمل بيئة لمشروع جديد تكتب السطر دا علي ويندوز 
conda create -n env_name python=3
#to activate your env write 
activate env_name

#to show your env packjes 
conda list 

#to install libyrary
conda install numpy panda matplotlib

#to install jupyter
conda install jupyter notebook 

#to export the backeges to txt file 
pip freeze > requirements.txt
#to instal the backege from txt file 
pip install -r requirements.txt

#to upgrade conda 
conda upgrade conda

#to upgrade the backeges 
conda upgrade --all

#to rmove package 
conda remove PACKAGE_NAME

#update package 
conda update package_name

#Search a Package to Install
conda search *SEARCH_TERM*

#بيجيب الديتيلز الموجودة فالenv 
conda env export

#لو عاوز تحط البكدجز في ملف عشان تبعتها لحد او تستخدمها تاني 
conda env export > environment.yaml

#لو عاوز تعمل انفيرومنت من الملف الانت حفظنة 
conda env create -f environment.yaml

#to remove env 
conda env remove -n env_name

 #Install the package below, if not already
#to convert any py code to notebook 

pip install nbconvert
jupyter nbconvert --to html mynotebook.ipynb
"""The currently supported output FORMAT could be either of the following (ignore case):
HTML,
LaTeX,
PDF,
WebPDF,
Reveal.js HTML slideshow,
Markdown,
Ascii,
reStructuredText,
executable script,
notebook."""


#To create the slideshow from the notebook file
jupyter nbconvert notebook.ipynb --to slides

#This just converts the notebook to the necessary files for the slideshow, 
#but you need to serve it with an HTTP server to actually see the presentation.
#To convert it and immediately see 
jupyter nbconvert notebook.ipynb --to slides --post serve







```

Github markdown cheatsheet : 

[https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)

Cheatsheet by Adam Pritchard : 

[adam-p/markdown-here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

the python debugger : [https://docs.python.org/3/library/pdb.html](https://docs.python.org/3/library/pdb.html)
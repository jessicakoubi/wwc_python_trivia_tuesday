# Women Who Code Python : Trivia Tuesday

Repository to store Trivia Tuesdays Q/As for Women Who Code Python.

## How To Contribute

1.  :book: Read up on fork & pull request models.
2. 🍴 Fork this repo or pull from upstream to get the latest.  
3. 🔨 Follow the guide on how to add new trivia(s) below.
4. 🔧 Make a pull request.

## Structure

Trivia are stored inside the [trivias](trivias) directory, with one trivia per sub-directory. A [template](templates/trivia_0000) is present in the *templates* directory.
## Add New Trivia(s)

1. Copy the [templates/trivia_0000](templates/trivia_0000) directory into the [trivias](trivias) one.
2. Increment its number to be the latest one. 
3. You can then edit the **[question.ipynb](templates/trivia_0000/question.ipynb)** file with the trivia code and possible answers.
4. Finally, edit the **[solution.md](templates/trivia_0000/solution.md)** file with the correct answer letter and a small explanation of the concept, method, module, etc shown in the trivia.

Rinse and repeat for each additional trivia Q/A you want to add.

### Question Breakdown

The **[question.ipynb](templates/trivia_0000/question.ipynb)** is an ipython notebook that is split into three cells. The first one, a markdown cell, is the notebook title. 
The cell below contain either the trivia code or situation if you create a fill-in-the-blank type of trivia question. Finally, the 
last cell contain all the possible answers, typically 4 possibilities but you can reduce it down to 3.

#### How To Open question.ipynb

The notebook can be opened your favorite text editor or IDE. You can find support for it in some IDE as shown below:

* VSCode: https://code.visualstudio.com/docs/datascience/jupyter-notebooks
* VIM: https://github.com/wmvanvliet/jupyter-vim
* Emacs: http://millejoh.github.io/emacs-ipython-notebook/
* PyCharm: https://www.jetbrains.com/help/pycharm/jupyter-notebook-support.html
* Sublime: https://github.com/sschuhmann/Helium

Alternatively, you can open them with:

* Jupyter: https://jupyter.org/
* Google Colab: https://colab.research.google.com

### Solution Breakdown

The **[solution](templates/trivia_0000/solution.md)** to the trivia live in a separate file so we can link to the question notebook when published. it's a simple markdown file
that starts with the anser letter followed by a small explanation of the concept, method, module, etc shown in the trivia.
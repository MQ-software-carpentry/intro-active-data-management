---
title: "Paper of the future"
teaching: 5
exercises: 10
questions:
- "What are the current and future requirements for academic publishing?"
objectives:
- "Read 'The Scientific Paper is Obsolete'"
- "Learn about reproducibility and responsible research practice"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---
FIXME

# Paper of the future

    * Jupyter notebooks skills (where to find and store, open, use basic code, save and share)
    * working knowledge of Cloudstor and associated services

> ## Challenge - Read article
>
> Read ['The Scientific Paper is Obsolete'](https://www.theatlantic.com/science/archive/2018/04/the-scientific-paper-is-obsolete/556676/) and discuss in pairs/small groups. Write down the main points in the shared document.


# Reproducibility

This might be a helpful image: https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007007

# Computational notebooks

Computational notebooks have been around since the late 1980s. Essentially a notebook is an advanced word processor. Also known as a notebook interface, the concept is that it is a virtual notebook environment used for literate programming. 'Literate programming' pairs the functionality of word processing software with both the shell and kernel of that notebook's programming language.

Notebooks are documents that contain both code and rich text elements, such as links, equations and different ways of visualising data via graphs, tables and figures. Because of the mix of code and text, notebooks are an ideal place to bring together results and an analysis description. Notebooks are really smart documents - they can be executed to perform data analysis in real time.

# Jupyter Notebooks

Jupyter is named after three computer programming languages - **Ju**lia, **Pyt**hon and **R**. It is a free, open-source, interactive web tool  which researchers use so they can combine software code, computational output, explanatory text and multimedia resources in a single document.

Jupyter Notebooks also refer to Galileo’s original notebooks of his observations of celestial bodies. These have all been digitized now and are really beautiful historical objects. Here are the notes he made on his discovery of Jupiter’s moons:

![Galileo_manuscript](https://user-images.githubusercontent.com/48195568/62598083-48ef0d80-b927-11e9-9984-335d87bf1bb0.png)


Image credit: [University of Michigan Special Collections Library](https://www.lib.umich.edu/special-collections-research-center/galileo-manuscript)

You can see in this image the title, comments, documentation, equations and diagrams. That’s what Jupyter Notebooks are designed to do, with the added bonus of the computer performing the calculations and creating the visualisations on your behalf. A beautiful 21st century object instead.

Jupyter Notebooks have exploded in popularity over the past couple of years, now supporting additional languages and being used by more and more people from different disciplines.


# SWAN

The Service for Web-based Analysis (SWAN) is a service for running data analysis in CloudStor. Using only a web browser, users can perform interactive data analysis in Jupyter Notebooks via SWAN and AARNet’s shared cloud computing services, meaning you can run your analysis in the same location as your data.

> ## Challenge - Create a Jupyter Notebook

> * Log in to CloudStor.
>
> 1. Go to the AARNet website: https://www.aarnet.edu.au/
> 2. Click on 'Log In and Tools' in the top righthand corner of the page.
> 3. Select 'CloudStor'.
> 4. Choose your organisation and click on 'Login at AARNet'.
> 5. Sign-in with your credentials - user name and password - and click 'Login'.  
>
> * Create a Jupyter Notebook of your own.
>
> 1. At the top of the page there is a black banner that shows several icons. Click on the swan icon once.
> 2. From the 'Welcome to SWAN' (service for web-based analysis), click on 'Go to my Notebooks'.
> 3. You will notice here that you can see the spinning Jupyter icon come up on the screen. This means that a notebook is being created. This can take a minute or so.
> 4. When the next screen comes up you will see the launcher. Click on the Python tile.
> 5. Select 'File' at the top left hand side of the screen and select 'Save As'. Name your notebook 'Intro to Jupyter Notebooks'.
>
{: .challenge}

If you don't have access to CloudStor, follow these instructions:

Open up MyBinder: https://mybinder.org/

Paste GitHub Repo: https://github.com/ingridbmason/Intro-to-Jupyter/

Open your new notebook, select Python 3 and save.


> ## Challenge: Add narrative markdown
>Remember that [Markdown](https://en.wikipedia.org/wiki/Markdown) is how you can make rich (or formatted) text in a plain text editor.
>
> In Jupyter Notebooks the first thing you need to do is select the role of the cell you are typing into.
>
> We are going to select 'Markdown' from the dropdown menu on the righthand side of the row of buttons showing the various icons (save, cut, copy etc).
>
> Headings
>
Let's start with a heading. To create a heading in Markdown you use a hash (#) and a space before the words in the heading:
>
> - Type
>
> `# Introduction to Juypter Notebooks`
>
> into the cell, making sure you have selected 'Markdown' from the dropdown menu above where it shows 'Code' as the default.
>
> Already here you can see how notebooks are flexible, as you can choose what kind of cell you are writing in (and toggle it at any time!)
>  
>  - Click on 'Run' - the button with the triangle next to a vertical line (it looks  like a 'play' icon), or use the shortcut **Shift+Enter** to execute the cell.
>   
>  - You have just created a heading in your notebook! Hooray!
>
> Now let's add a subheading. This time you use two hashes (##) before the words in your subheading.
>
>  - Type
>  
>  `## A lesson in Markdown`
>
>  - Click on 'Run' - the button with the triangle next to a vertical line (it looks  like a 'play' icon), or use the shortcut **Shift+Enter** to execute the cell. You now have a subheading.
>  
> Body text
>
> To write in your notebook in normal body text, you just have to type your text in the Markdown cell and press 'Run' or use the shortcut **Shift+Enter**.
>
>  - Type
>  
>  `This is my first lesson in Markdown.`
>
> - Click on 'Run' or use the shortcut **Shift+Enter**.
>
>  You can now type your comments in your Jupyter Notebook.

> ## Editing a cell
>  
> Let's say we want to add some text to the cell you executed above. Double-click on that line and you can open up the cell again.
>   -  After the first sentence, type
>   
> `I'm doing really well!`
>  
> If you want to add a new cell you can click on the 'up arrow' icon from the buttons above.  To delete or edit a cell, you can toggle up and down the cells.
>
> ## Adding a new cell
>
> Let's add a new cell. Under your subheading, you can add another heading. Go to your subheading 'A lesson in Markdown' and click on the 'plus' button. This will create a new cell. Select 'Markdown' from the drop down menu.
>
> - Type
>
> `### Use it to create rich text in a plain text editor`
>
> - Press 'Run' or use the shortcut Shift+Enter.
>
> You now have a level three heading.
>
> ## Bold
>
> Now let's try bold font. In a new cell, select 'Markdown' from the dropdown menu again.
>
>  - Type

 `This is **really** interesting.`

  - Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell.

Voila! Bold!

## Italics

Now let's try italics. In a new cell, select 'Markdown' from the dropdown menu again.

 - Type

`This is really _interesting_.`

  - Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell.

Voila! Italics!

### Activity

Spend a couple of minutes practicing these skills: Headings, plain/bold/italics text, adding, removing and editing cells.

It can feel a little strange, as you already know how to do formatting in programs like Word. However, what we are doing here is 'speaking' directly to the computer, with a different kind of interface so you can also perform calcuations, visualisations and use computational methods.

Remember that the reason Jupyter Notebooks is becoming so popular is because it is a format that allows for commenting and text to sit within the same 'document' as code, mathematical equations and visualisations. You can tell the story of what you are doing as you go, and this is a really useful way of being about to reproduce your results.

If you want to know more about Markdown, take a look at these pages:

https://guides.github.com/features/mastering-markdown/

https://www.firstpythonnotebook.org/markdown/
{: .challenge}



# Using data in CloudStor

Make sure you are working in Jupyter Notebooks with the Python kernel running. We are going to use a software library called 'pandas', written for data manipulation and analysis in Python.

- In a code cell type

`import pandas`

- Execute the cell.

- In a new code cell type

`pandas.read_csv ("")`

and place this public link to the data saved in CloudStor between the quotes:  https://cloudstor.aarnet.edu.au/plus/s/x2uHIEZubsNuqEh/download

You can also use a token (public link) from Google Docs to import data. For example, in a new notebook, use the same code again but try pasting this link between the quotes instead of the CloudStor link:     
    https://docs.google.com/spreadsheets/d/e/2PACX-1vQctQqQu1baZQJfhV333sEcjnkmvnRFtCGF0HVfoV3WnSmeDhhFneZ7bYtaxe3xFeMS9-pmzk83AuR4/pub?output=csv

If you'd like to know more about 'pandas' click here: https://en.m.wikipedia.org/wiki/Pandas_(software)

> * Upload a notebook from Cloudstor.
>
> * Upload a notebook from GitHub (for Cloudstor users who are not familiar with git).
>
> How to save a Jupyter Notebook from Github
>
> Create a 'My Jupyter Notebooks' file in your Cloudstor sync folder.
 > Go to GitHub and open the Jupyter Notebook you want to use, Click on the 'Raw' button towards the top right side of the screen
>
> In that new page, select ctrl+s to save as .ipynb format (you will need to type '.ipynb' after the file name, to avoid the automatic .txt format). If your computer still automatically adds a '.txt' at this point, you will need to remove the '.txt' file extension after you have saved it to your folder.
>
> Or, you can click on the 'Save as type:' dropdown menu and select 'All Files (*.*)
>
> Save to your Jupyter Notebooks folder in your Cloudstor sync folder.
>
> * Share a notebook with a colleague
>
 (what is GitHub?)
> Sharing Notebooks with GitHub
https://reproducible-science-curriculum.github.io/sharing-RR-Jupyter/01-sharing-github/

> ## Upload Jupyter notebook to osf and render in mybinder.
>

{: .challenge}


# Some more useful information about Jupyter Notebooks

[10 Simple Rules](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007007)

There are many different ways you can access Jupyter Notebooks via the web:

* [Binder](https://mybinder.org/)
* [Kaggle Kernels](https://www.kaggle.com/kernels)
* [Google Colaboratory (Colab)](https://colab.research.google.com)
* [Microsoft Azure Notebooks](https://notebooks.azure.com/)
* [CoCalc](https://cocalc.com/doc/jupyter-notebook.html)
* [Datalore](https://datalore.io/)

You can also install Anaconda and use notebooks without being online.

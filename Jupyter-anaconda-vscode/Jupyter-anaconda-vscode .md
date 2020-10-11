
## How to configure VS Code with Anaconda and Jupyter Notebooks on Windows 10

Get your IDE ready for Data Science projects

![Fontes: Anaconda, Jupyter e VS Code](https://cdn-images-1.medium.com/max/2100/1*9eqevpizT3qrQI62P4kB6w.png)

**Jupyter Notebook** is an open source application that allows the creation and sharing of projects with programming code and text. In a Notebook it is possible to insert code snippets from different programming languages, such as Python, R, Scala, and dozens of other languages, execute the codes and display the results. In addition, there is the option to put annotations in text, create tables and insert images, which allows you to document the project as the code is inserted. The combination of executable code and text documentation makes Notebooks an excellent experimentation and prototyping tool, perfect for Data Science projects.

In the scope of Data Science, the Python programming language is widely used. To work with Python on Notebooks, as well as with the most popularly used libraries, such as Pandas, Matplotlib, Seaborn and Numpy, a very interesting option is the distribution **Anaconda**. It provides a complete software environment with all the necessary libraries and updated versions of Python and R for the development of scientific projects.

And to develop the project, a development environment generally facilitates the programmer's life, as it has debugging, refactoring tools, tools to autocomplete functions and consult documentation, among others. **Microsoft Visual Studio Code**, or VS Code, is an interesting alternative. It is possible to configure the environment with the Python distribution of Anaconda and create projects with Notebooks for experimentation.

In this article you will learn how to:

 1. Install the Anaconda distribution.

 2. Install the IDE VS Code and set up the development environment for Python.

 3. Create a project in VS Code with a Notebook and execute simple commands.

 4. Install packages with the conda command on the VS Code terminal.

## Installing the Anaconda distribution

Access the [official page](https://www.anaconda.com/products/individual) Anaconda distribution and download the executable. Start the installation and follow the steps. When you get to the advanced installation options, be sure to check the option “Add Anaconda3 to my PATH environment variable”.

![Marking option“Add Anaconda3 to my PATH environment variable”.](https://cdn-images-1.medium.com/max/2000/1*QteJ9EIVz8yoC1_cdciV4w.png)

Checking this option is important for executing commands via terminal within VS Code.

## Installing VS Code

VS Code has a free version and can be downloaded on the [official page](https://code.visualstudio.com/). Installation is simple and straightforward, just start the executable and follow the steps.

## Configuring VS Code for Python

When entering VS Code, on the home page, you will find an option called “Tools and languages”.Choose Python and install the extension.

![VS Code. Option “Tools and languages”.](https://cdn-images-1.medium.com/max/2000/1*0dnFiC9r2K3z7DAaLrdZcA.png)

Once the download is complete, just close and reopen the VS Code and the extension is already active. By clicking on the marketplace icon you can see that the extension has been successfully installed.

![VS Code. Accessing the marketplace.](https://cdn-images-1.medium.com/max/2000/1*vZjE45rx6Rr8weEkkhq5jg.png)

## Creating a project in VS Code

Choose a location to store your project and create a folder for it, for example Desktop / First Project. Then reopen the VS Code and in the Start field click on “Open folder” and select the folder. The project folder is loaded in the left side column of the IDE.

![VS Code.Project folder loaded.](https://cdn-images-1.medium.com/max/2000/1*3CWjqxU7FpBevemuxpma0g.png)

Then click **Ctrl+Shift+P** and select the Python interpreter for the project.

![VS Code. Choice of Python Interpreter.](https://cdn-images-1.medium.com/max/2000/1*tja_DGC7QeaCueuMuvBShw.png)

You must also choose the version of the Python Interpreter. In our case, we chose the version provided by the Anaconda distribution, which is the version **Python 3.8.3 64-bit (‘base’: conda)**.

![VS Code. Choosing the Python Interpreter version.](https://cdn-images-1.medium.com/max/2000/1*g0A3zIJVJGbDvyBTxHrp9A.png)

## **Creating your first Notebook**

On the project tab, click the button“New File” and create a Notebook file with the extension .ipynb.

![VS Code. Creating the first notebook.](https://cdn-images-1.medium.com/max/2000/1*6LBOTVG55_UPP31SrQhK4w.png)

To test the Notebook, let's insert the code snippet below in the first execution box:

 <iframe src="https://medium.com/media/813ce7079d7b5b894617cb8768790b51" frameborder=0></iframe>

The Notebook cell is executed with the shortcut **Ctrl + Enter**. The result obtained is as follows:

![VS Code. Notebook cell execution.](https://cdn-images-1.medium.com/max/2000/1*kX61MUwjV0jA4ZpvQRQuXg.png)

Testing another snippet of code:

![VS Code. Notebook cell execution.](https://cdn-images-1.medium.com/max/2000/1*qL3nBDx68UWvKmmUWNT7BA.png)

## Installing new packages with conda

Within the VS Code you have access to a terminal via the shortcut **Ctrl+Shift+`**. As soon as a terminal is opened, the Anaconda distribution is automatically active:

![VS Code. Terminal with active count.](https://cdn-images-1.medium.com/max/2000/1*M1sj6Oa4qUt3fNKrF7zGHA.png)

The conda command is an interface for managing installations in the Anaconda distribution, and allows you to search and install new packages from the Anaconda repository, create isolated conda environments and install and update packages within those environments.

For example, to install the ecosystem [SciPy](https://www.scipy.org/), which has a collection of open-source software for scientific computing in Python, just run the command conda install scipy.

![VS Code. Installing scipy with conda.](https://cdn-images-1.medium.com/max/2000/1*B9N91mMvOYQ7BzRibGpTXA.png)

## Final considerations

Working with notebooks allows experimentation to be carried out in a very agile and practical way. The Anaconda distribution provides a set of software packages for the development of these projects in Python. And all this integrated in a robust IDE like VS Code facilitates the development, debugging and organization of the project. Creating a Python project and inserting Notebooks for experimentation has never been easier!

For more detailed articles like this, check out my GitHub repository, where I keep a summary record of each one:
[**jlggross/articles**
*This repository has a collection of all articles I've written for different websites such as LinkedIn and Medium (so…*github.com](https://github.com/jlggross/articles)
Translated by Daniel Gomes

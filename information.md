Jupyter Notebook Tutorial
=========================

The jupyter notebook system is an incredibly useful bit of software, but can be intimidating at first glance.

Once you know the basics, though, it becomes a powerful tool for learning and data analysis.

The jupyter notebook is essentially just a different way to use python than you have been using already. It is based on 'iPython' (interactive python) which similar to running python in your command line/terminal but with a few more features. The notebook takes this to another level, providing ways to include inline text and equations as well as output your figures to within the notebook for easy sharing.

Here, we will use the jupyter notebook as a way to contain a project's code and figures that will hopefully give you deeper insights into the Nuclear and Particle Physics material.

Cells
-----

### What is a Cell?

A cell in the jupyter notebook is the place where we input text and code. Each cell can talk to each other - so if you output some data to an object, say an array, in one cell, then this data can be accessed from all the other cells.

This is a very useful feature as it means that you can separate your code into logical blocks and intersperse it with text explaining what the code does - and even include equations! You will see how this works later.

### Running Code

After including python code in a cell, simply press shift+enter. This will cause your code to be run by the python kernel, and if it outputs any data then this will be displayed below the cell as text. Alternatively you can press the 'play' button in the toolbar - this will also run the cell.

If you would like to insert a cell below the one you are currently working on after running the code, press alt+enter.

You can run all the cells in your notebook by using the 'Cell' option in the toolbar.

### Adding Cells

It is fairly straightforward to add a cell. You can either use the 'plus' sign in the toolbar which will insert a cell below the one that you are currently editing, or use the 'Insert' option in the toolbar.

### Removing Cells

To remove cells, select the cell you would like to remove and press Edit->Delete Cell in the toolbar.

### Changing Cell Type

As we mentioned above, cells are not just for python code. They can also include text and mathematics! You can even run code from other lanagugaes (such as *R*), but that is, as they say, "well beyond the scope of this course".

To change the type of a cell, select it, and then either use the drop down box in the toolbar (next to the circular arrow) to change the cell type or use Cell->Cell Type in the toolbar.

When you 'run' the cell in markdown format, this will compile the markdown to rich text and it should look very pretty. For more information on markdown, see [here](https://daringfireball.net/projects/markdown/syntax).

You can even include LaTeX math by enclosing it in double dollar signs, like so

	$$
		s^o_m^e mat\hbar
	$$

As you can see, this makes the notebook a powerful tool for research.

Magic Commands
--------------

Magic commands, at first, can look a little scary. They are commands that start with a '%' sign, such as

	%pylab

These bring some odd piece of functionality into the notebook. ```%pylab``` gives access to all of the numpy functions without having to prefix them, so instead of typing numpy.sin(), one would just type sin().

Another common one to see is

	%matplotlib inline

what this does is allow all of the figures generated in your notebook to be displayed in the notebook instead of in a pop-out window like you are used to with shell python. For more information on magic commands, you can check out [this page](https://ipython.org/ipython-doc/3/interactive/magics.html).

Installing jupyter notebooks on your own system
-----------------------------------------------

You can find information on how to install the jupyter notebook on your own system with their documentation at [readthedocs](https://jupyter.readthedocs.io/en/latest/). If you are having any issues with this, then bring it up in a workshop. You should not need to install the notebook on your own system to use it, though, as that is all handled by the online system.

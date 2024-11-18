# Cells

A Jupyter notebook consists of a sequence of cells.
The flow of a notebook is sequential from top to bottom.
You enter code into an input cell, and when you run the cell, the notebook runs the code and prints the output of the computation to an output cell.

For example, we can look at the following Python code.

```python
print("Your message here!")
```

This Python code should print the string "Your message here!" once we run it.
The figure directly below shows the ▷ on the left, which means we can run the Python code in that cell.

<figure markdown>
![](/img/colab/cell.svg){ width=300 }
</figure>

Once we run this, you would see the figure below.

<figure markdown>
![](/img/colab/cell-ran.png){ width=300 }
</figure>

You can tell that the Python cell was ran **at some point** by the ✓ to the right with no errors.
The `0s` below the ✓ just tells you how many seconds it took to run.
We can also see the cell output contains `Your message here!`.
If you make any changes to this cell, you have to run it again.

Do not worry, you do not have to keep clicking a bunch of ▷ to run all of your cells.
We have some shortcuts:

-   Windows: ++ctrl+enter++
-   Mac: ++cmd+enter++
-   Linux: ++ctrl+enter++

# Opening files

When you see a ![colab logo](/img/launchy/colab.svg){ width=18px } symbol in the upper right corner on a page of this website, you can click on it to open up that file directly in [Google Colab](https://colab.google/).

!!! example

    Go to [this page](../../intro/regression/introduction.ipynb) to see an example.
    If you click ![colab logo](/img/launchy/colab.svg){ width=18px } then you will be taken [here](https://colab.research.google.com/github/oasci/pitt-biosc1540-2024s-website/blob/main/biosc1540/modules/intro/regression/introduction.ipynb).

How does this work?
Well, [Google Colab](https://colab.google/) has an import mechanism for Jupyter Notebooks in [GitHub](https://github.com/) repositories.
Adding an import link is all it takes.

When you open up our Jupyter notebooks in Google colab, you will be met with this screen.

<figure markdown>
![](/img/colab/gui.svg){ width=600 }
</figure>

Jupyter notebooks are made up of <font color="#ff2a2a"><b>cells</b></font> which can be thought of as paragraphs that can change types.
[Markdown](https://www.markdownguide.org/) is simply text like you would put in a Word document, email, etc.
The only difference is how you specify things like a list, link, etc.

When you see a `[ ]` on the left with a greyed out background, this is a Python cell.
You can put any Python code here and run it.
We will get to this [later](#cells).

When working on Jupyter notebooks from this website, you should always <font color="#37c871"><b>save a copy to your Google Drive</b></font>.

To run Python code, you have to <font color="#0066ff"><b>connect to Google's servers</b></font>.
When you click this button, it will initiate a connection to Google's servers and will look like this once it is done.

<figure markdown>
![](/img/colab/kernel-running.png){ width=200 }
</figure>

Welcome to the 2020 AstroPGH Research Boot Camp and Weekly Seminar Series for summer undergraduate students and early PhD students new to research.  This program is designed to help you learn the basics of research, including coding, statistics, writing, and presenting.

We will start with a 1+3 day Python coding boot camp to help get everyone off the ground with their research.

Then we will have a weekly seminar series to discuss more advanced topics, including communication skills (reading, plotting, storytelling, and writing) that become more important as the summer goes on. My hope is to create a sense of community in spite of the remote operations this year, so that you can help others, can seek help, and can interact with each other.

## Boot Camp
### Installation and Setup
#### Python
Please install Python 3 before the Boot Camp. I recommend using the [Anaconda](https://www.anaconda.com/products/individual) package manager **_for Python 3.7_** and then install the following packages in the terminal:
```bash
conda install numpy scipy astropy matplotlib jupyter ipython
conda install -c astropy astroquery
conda install -c conda-forge jupyterlab
```

- [Conda Users Guide](https://conda.io/docs/user-guide/index.html)
- [Astropy Install Instructions](http://docs.astropy.org/en/stable/install.html)

#### Test Your Installation

1. Open a new terminal.
2. Type `ipython` into the terminal to open an interactive python session (the prompt should say `In [1]:`).
3. Copy this code:
```python
import numpy
import scipy
import astropy
import matplotlib
import astroquery
```
4. Type into the iPython shell the word `paste`, and press enter.
5. If no errors are raised, you're ready for bootcamp. You may close the terminal window.

If you are having difficulties with installation, please do not hesitate to reach out to Brett Andrews on Slack or via email.

#### Git and GitHub
- [Set up Git](https://help.github.com/articles/set-up-git/)
- [Sign up for GitHub](https://help.github.com/en/github/getting-started-with-github/signing-up-for-github)

### Schedule

| Time | Monday | Tuesday | Wednesday | Thursday |
|:-----:|:-----:|:-----:|:-----:|:-----:|
| 9:00-10:15 | Python Basics | Numpy I | Astropy I | Git |
| 10:45-12:00 | Data Structures | Numpy II | Astropy II | GitHub |
| 1:00-2:15 | Functions and Modules | Linear Regression | Matplotlib II | Pandas |
| 2:45-4:00 | Matplotlib I | Resampling | Debugging | Altair |

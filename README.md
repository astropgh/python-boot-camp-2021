**2020**: [GitHub](https://github.com/astropgh/astropgh-boot-camp-2020) / [website](https://astropgh.github.io/astropgh-boot-camp-2020/)

**2021**: [GitHub](https://github.com/astropgh/python-boot-camp-2021) / [website](https://astropgh.github.io/python-boot-camp-2021/)

Welcome to the 2021 AstroPGH-TAMU Python Boot Camp and Weekly Seminar Series for summer undergraduate students and early PhD students new to Python.  This program is designed to help you learn the basics of using Python for astrophysics research.

We will start with a 1+2 day Python coding boot camp to help get everyone off the ground with their research.

Then we will have a weekly seminar series to discuss more advanced topics, including communication skills (reading, plotting, storytelling, and writing) and statistics/machine learning. Our hope is to create a sense of community in spite of the remote operations this year, so that you can help others, can seek help, and can interact with each other.

## Boot Camp
### Installation and Setup
#### Python
Please install Python 3 before the Boot Camp. I recommend using the [Anaconda](https://www.anaconda.com/products/individual) package manager **_for Python 3.8_** and then install the following packages in the terminal:
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

If you are having difficulties with installation, please do not hesitate to reach out to Brett Andrews or Paul Zivick on Slack or via email.

### Instructors
- [Brett Andrews (Pitt)](https://bretthandrews.github.io/): Numpy IV and Pandas
- [Biprateep Dey (Pitt)](https://biprateep.github.io/): Numpy I and Numpy II
- [Taylor Hutchison (TAMU)](https://aibhleog.github.io/): Matplotlib I and Matplotlib II
- [Zach Lewis (Pitt)](https://zachjlewis.github.io/): Numpy III
- [Alex Riley (TAMU)](https://ahriley.github.io/): Astropy I and Astropy II
- Paul Zivick (TAMU): Python Basics, Data Structures, and Functions and Modules

### Schedule

| Time (EDT) | Monday (5/24) | Tuesday (5/25) | Wednesday (5/26) |
|:-----:|:-----:|:-----:|:-----:|
| 10:00-11:15 | Python Basics | Numpy I | Astropy I |
| 11:45-1:00 | Data Structures | Numpy II | Astropy II |
| 2:00-3:15 | Functions and Modules | Numpy III | Matplotlib II |
| 3:45-5:00 | Matplotlib I | Numpy IV | Pandas |


## Seminar Series

Wednesdays from 2-3 pm EDT

| Date | Title | Speaker |
|:-----:|:-----:|:-----:|
| 6/2  | | |
| 6/9  | | |
| 6/16 | [How to Give an Effective Talk](seminars/effective_talks_2021-06-16.pdf) | Nathan Herring |
| 6/23 | [Principal Component Analysis](seminars/pca_2021-06-23.pdf) | [Biprateep Dey (Pitt)](https://biprateep.github.io/) |
| 6/30 |  |  |
| 7/7  | [Effective Plotting](https://bretthandrews.github.io/files/talks/2021-07-07-pitt-plotting/2021-07-07-pitt-plotting.html#/) | [Brett Andrews](https://bretthandrews.github.io) |
| 7/14 | [Coding Best Practices](seminars/coding_best_practices_2020-06-03.pdf) | [Daniel Perrefort](https://djperrefort.github.io/) |
| 7/21 | Gaussian Process Regression | [Cat Fielder](https://cfielder.github.io/) |
| 7/28 |  |  |
| 8/4  |  |  |

<a href="url"><img style="padding: 0px 20px;" src="https://github.com/astropgh/python-boot-camp-2021/blob/main/etc/NSF_4-Color_bitmap_Logo.png?raw=true" align="left" height="128" width="128"></a>

This material is based upon work supported by the National Science Foundation grant number AST-2009251. Any opinions, findings, and conclusions or recommendations expressed on this website are those of the participants and do not necessarily reflect the views of the National Science Foundation or the participating institutions.

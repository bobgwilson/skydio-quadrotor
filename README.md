I did a Robotics Software Engineering Internship with Skydio (through Open Avenues) from Feb 2024 - Apr 2024:
* Developed a working dynamics simulation and feedback controller of a Skydio quadrotor drone
* Wrote quality Python code in a team environment using VS Code and packages NumPy, SciPy, and SymForce
* Delivered this GitHub repository with Jupyter notebooks that include implementations and derivations
* Had a blast and learned a lot about writing code in a team environment at a major tech company.

The final notebook is in [5-Controller-Full.ipynb](https://github.com/bobgwilson/skydio-quadrotor/blob/main/5-Controller-Full.ipynb). I plan on cleaning up this repo soon, removing unnecessary early versions and cleaning up the Python code, but for now I have left it as it was at the end of the internship. The original readme from Skydio is below:

# Open avenues project
We'll be working using the classes in this repository. You will all maintain a [fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) of this repository. This means you'll periodically sync changes from the upstream repository when I upload new assignment notebooks or make other changes. This _also_ means that if you have changes (i.e. you've made some useful updates to rendering tools etc...) that benefit everyone in the group we can get your changes _into_ the upstream repository!

## Getting set up
- Create a github account and [fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) the repository
- Make sure you have python >3.8 installed on your machine
- Install [`pipenv`](https://pypi.org/project/pipenv/). This is what we'll be using to install dependencies
- Clone your fork (see link above)
- Make sure that your inside the repository in your terminal
- Run `python3 -m pipenv install` to install all the dependencies
- Run `python3 -m pipenv shell` to enter the python environment
- Run jupyter with `python3 -m jupyter notebook`
- Check that you can run the first couple of cells of `1-introduction.ipynb`

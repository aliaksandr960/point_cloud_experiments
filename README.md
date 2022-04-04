# This repository represents solution of several computer vision tasks

To setup docker container execute
- 'cd notebooks'
- 'docker build . -t cv_tasks'

To run, execute following set of commands:
- 'sudo docker run -it --network host -v "$(pwd)"/notebooks:/app/notebooks cv_tasks'
- 'cd notebooks'
- 'jupyter-lab'

Than, open in your browser Jupyter-Lab, select notebook, and just press 'Run all cells'

Notebooks with tasks named as Task1, Task2, Task3

There are comments in notebooks, that could help to navigate

Task 3 is just description, but it was done as Jupyter just to make everything looks same
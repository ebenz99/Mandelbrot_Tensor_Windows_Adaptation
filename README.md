# Mandelbrot_Tensor_Windows_Adaptation
A Tensorflow Mandelbrot tutorial adapted to work for Windows

TensorFlow is a software library created by Google for numerical computation and machine learning. It can be hard to pick up as an amateur programmer, but a tutorial is available at https://www.tensorflow.org/tutorials/mandelbrot for Linux and Mac users. I've attempted to adapt that tutorial for those working with Windows and Windows command line software.

## Prerequisites:


**Python 3.5.2**

If you have a different version of python installed, this tutorial may work for you, but it also may not. I would recommend downloading the 'Windows x86-64 executable installer' from https://www.python.org/downloads/release/python-352/. Once this is installed, add the directory where the python 3.5.2 executable is located to the top of your PATH (can be found by editing environment variables)
Check this step by opening a NEW terminal window and entering the command 'python -V'. Among other things, it should display your python version as Python 3.5.2


**Up-to-date Pip**

With this version of Python, you probably have a pip around version 8. Get the most current version by entering the command 'python -m pip install --upgrade pip'


## To Run:

1. Clone or Download this repository somewhere onto your computer
2. Open command line and navigate to the directory with this repository
3. Ensure your python and pip versions are correct ("python -V" and "python -m pip install --upgrade pip")
4. Install the requirements. This can be done with "pip install -r requirements.txt"
5. Run the program with the command "python mandelbro.py"
6. View your created image with the command "out.bmp"
7. Edit the sharpness of the image by increasing or decreasing the x line "for i in range(x): step.run()"
8. Rerun to get new image
# comp-560-project
## TODO immediately
- **Everyone create their own branch with your name**
- **Git pull frequently!**
- **Everyone install the required packes and check out the code**
    - Creating virtual environment: `python -m venv Virtual_Environment`
    - **<u>Activating virtual environment:</u> `source Virtual_Environment/Scripts/activate`**
        - Once you activate the virtual environment, you can deactivate it by running `deactivate`, and all the packages you downloaded will still be there when you reactivate again
    - Install packages: `pip install -r requirements.txt`
        - Alternatively (this method is not preferred; all the package requirements should be in <u>requirements.txt</u>):
            - Install easy packages: `pip install ipykernel numpy pandas matplotlib IPython six`
            - Install tensorflow: `pip install tensorflow`
    - Select the <i>Virtual_Environment</i> kernel inside the <u>ipynb</u>
- **Familiarize yourself with Tensorflow (video and instructions linked in the <u>ipynb</u>)**

### Gameplan
- Figure out backpropogation in Tensorflow
- Figure out how to predict discrete or continuous variables rather than just yes/no

### Questions
- What are we trying to predict?
- How do we keep dependencies consistent across our devices?
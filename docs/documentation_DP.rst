This documentation was done in April 2025 by EPFL students for their design project.

1. Open a terminal (Command Prompt in VS Code, or the one directly on your computer)
2. Create a conda environment named idmatch_env with the requirements for using this code. Copy-paste the following command in your terminal:
    conda env create --file environment.yml
3. Activate your environment: 
    conda activate idmatch_env
4. Your environment is set; you can now run the code:


Workflow:
1. Access the main IDMatch folder, and the idmatch subfolder. There are four files inside:

 * __init__.py
 * core.py
 * functions.py
 * params.py.

2. Open the params.py file. Choose the mode you want (mode=1 is the image matching, mode=2 is the DSM matching) and fill the corresponding paths and variables.
    If you just want to make IDMatch run with the test dataset we provide, leave the params.py file as it is.

    .. important:: The processing time depends on many things: The computer power you have, the resolution of your dataset, the number of matching methods (M1,M2,...) and windows (WX) you want to test, as well as the grid_step value.
    Method matching 3 (M3) does not work.
3. Run the core.py
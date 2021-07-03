# TROPOS Tasks
This repository is built for the job interview on 2021-07-05.

---
The code was tested with Python 3.7. To use this code, please do:

1. Clone the repo:

   ```shell
   git clone https://github.com/Wenfu-Sun/TROPOS_Tasks.git
   cd TROPOS_Tasks
   ```

2. Install dependencies (here I use Anaconda to manage the Python environment):

   ```shell
   conda create -n tropos-tasks python=3.7 
   conda activate tropos-tasks
   pip install jupyter xarray pandas matplotlib python-gantt cairosvg
   ```

3. Reorganize the data directory as follows,

   ```
   data\
   |---01-Field_experiment_overview\
       |---Tab_1-Instruments.csv
       |---Tab_2-Campaigns.csv
   |---02-Concatenation_of_measurement_files\
       |---...	
   |---03-Visualization_of_target_classification_mask\
       |---...	
   |---04-Conversion_of_binary_to_netcdf\
       |---...	       
   ```

4. Start `Jupyter Notebook` and run the `*.ipynb` for respective tasks.

5. The results will be generated under the `data\` folder.

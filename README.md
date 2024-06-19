Slides and Jupyter notebook code demo presented at PyData Seattle (06/19/2024).

The notebook demonstrates how to retrieve and visualize Observational Products for End users from Remote sensing Analysis (OPERA) data.

NASA Earthdata credentials are needed for data access. Create an account [here](https://urs.earthdata.nasa.gov/users/new), and then fill the template `.netrc` with the obtained credentials and place it in your home directory.

The python packages needed for the notebook to run can be installed to a new environment using the `environment.yml` file:

```
mamba env create -f environment.yml
```

which should create a new environment called `opera-demo`
# ResBaz2021

## Using Generalized Low Rank models to deal with real-world data
### Wednesday, May 19th, 2021 9\:00-10\:00

[Back to Resbaz HackMD Directory](https://hackmd.io/@ResBaz21/directory)

The goal of this workshop is to introduce Generalized Low Rank models (GLRMs) and how to implement them in Python / Julia.

GLRMs can recover many common dimensionality reduction (PCA, NNMF, etc); their goal is to create a numeric representation (X,Y) for tables (A) that simultaneously contain multiple types of data (boolean, categorical, numerical, ordinal, missing). We will discuss how to create such numerical representation, and how to use them.

**Pre-requisites** (ideal but not mandatory):
* Matrix multiplication ( A = XY )
* Understand what an objective function is ( think least squares)
* Basic python programming


## Getting Started

### Instructor
- `Julio Cárdenas-Rodríguez Ph.D`. Principal Data Scientist, United HealthCare, JCardenasRdz@uhc.com

### Github repository
- https://github.com/JCardenasRdz/ResBaz-2021_Generalized_Low_Rank_Models

### Packages needed for this workshop:
All the dependecies for this workshop can be installed via a yaml file (`conda`):
```bash
conda env create -f glrm_env.yaml
conda activate glrm_env
```
or a requirements file (`pip`)

```bash
pip install -r requirements.txt i
```

Use the link below to provide your feedback on the session: 
[**Session Feedback Form**](https://forms.gle/TrnJpr9qRBEKdnVVA)
:::



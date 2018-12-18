# DrWhy

`DrWhy` is the collection of tools for Explainable AI (XAI). It's based on shared principles and simple grammar for exploration, explanation and visualisation of predictive models.

Please, note that DrWhy is under rapid development and is still maturing. If you are looking for a stable solution, please use the mature [DALEX](https://github.com/pbiecek/DALEX/) package.

## Architecture of DrWhy

`DrWhy` works on fully trained predictive models. Models can be created with any tool. 

`DrWhy` uses `DALEX2` package to wrap model with additional matadata required for explanations, like validation data, predict function etc.

Explainers for predictive models can be created with model agnostic or model specific functions implemented in various packages.


![Architecture of DrWhy](images/DrWhy.png)

# Individual / Local

## Individual Variable Attributions

Variable attribution explainers implemented in the `breakDown2` package in the [local_attributions](https://pbiecek.github.io/breakDown2/reference/local_attributions.html) function.

```
breakDown2::local_attributions()
```

<img width="300px" src="images/local_attributions_1.jpg"/>
&nbsp;&nbsp;<img width="300px" src="images/local_attributions_2.jpg"/>

Variable attribution with interactions is calculated with the  [local_interactions](https://pbiecek.github.io/breakDown2/reference/local_interactions.html) function.

```
breakDown2::local_interactions()
```

<img width="300px" src="images/local_interactions_1.jpg"/>


## Individual Variable Profiles

Variable profile explainers (aka. Ceteris Paribus Profiles) are implemented in the `ceterisParibus2` package in the [individual_variable_profile](https://pbiecek.github.io/ceterisParibus2/reference/individual_variable_profile.html) function.

```
ceterisParibus2::individual_variable_profile()
```

<img width="300px" src="images/local_profile_1.jpg"/>

# Model / Global

## Model Variable Profiles

## Model Variable Importance

## Model Performance



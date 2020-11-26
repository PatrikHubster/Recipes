# Recipes

First of all you have to download the following two files from [the kaggle dataset](https://www.kaggle.com/kanaryayi/recipe-ingredients-and-reviews):

1. `clean_recipes.csv`
2. `clean_reviews.csv`

These two files you have to put into the `./data` in the repository. This folder is excluded in the `.gitignore` file and will not get pushed to the repository. To start the Jupyter notebook first of all make sure you have Docker installed. With the following command you can start the PySpark server:

```console
user@computer:~$ docker run -it --rm -p 8888:8888 -p 4040:4040 -v "${PWD}:/home/jovyan/work" --name spark jupyter/pyspark-notebook
```

After that follow the url in the console and start coding in the Jupyter Notebook.
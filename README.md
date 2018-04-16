# Tate Data Analyst Technical Test
This is the repository containing instructions and base data for a technical test for analysts 

# Set up

To help us evaluate your response to this test, we would prefer it if you responded using a Jupyter notebook. This allows you to annotate your response as required, and makes your response easier to evaluate.

## Python
If you haven't used Jupyter before, here's how to get yourself set up:

https://jupyter.readthedocs.io/en/latest/install.html#new-to-python-and-jupyter

## R
If you'd like to use **R** to respond to this test, then if you don't know how to set it up locally, this link gives instructions:

https://www.datacamp.com/community/blog/jupyter-notebook-r

If you would prefer to use a different tool, please feel free. 

## SQL

It is possible to answer this test using SQL alone. If this is your prefereen

Submissions should be returned to **{email address}** by **{date} **


# The Data

The data used for this test is sourced from the **Museum of Modern Art data on Kaggle**: https://www.kaggle.com/momanyc/museum-collection

## Content

The artworks dataset contains 130,262 records, representing all of the works that have been accessioned into MoMA’s collection and cataloged in our database. It includes basic metadata for each work, including title, artist, date, medium, dimensions, and date acquired by the Museum. Some of these records have incomplete information and are noted as “not curator approved.” The artists dataset contains 15,091 records, representing all the artists who have work in MoMA's collection and have been cataloged in our database. It includes basic metadata for each artist, including name, nationality, gender, birth year, and death year.


## The Database

To make sure that this test can run on any machine, we're using SQLite: https://www.sqlite.org/index.html

We have provided an example Python notebook showing how to connect to, and how to query the database using SQL. 

# The Test!

We'd like you to answer the following questions, using the language of your choice (Python, SQL or R)

If you are comfortable in more than one, please feel free to share one or more solutions in a different language. 

* Which artist in this dataset lived the longest?
* Who are the top 10 artists by the number of artworks?
* Which artist is created the most artwork by total surface area?
* Did any artists have artwork acquired during their lifetime?
* Please review the quality of the data, and present any issues
* Please group the artworks into as many clusters as you feel is appropriate, using attributes from both the artist and artworks tables, and assign each artwork to this new cluster. 

# The test submission

Our preferred response is an annotated Jupyter notebook. However, clearly responses using Excel or any other text editor will be accepted, provided both the response to each question and your workings are demonstrated.

# Good luck!
# CS4248 Group 46 Project (LUN)

Our project aims to determine the best textual features that improve a
model’s performance in deciphering the ve
[Satire / Hoax / Propaganda / Reliable] of a questioned news article, given its headline and body.

By analyzing and comparing the performance
of various models, we also examine whether Deep Learning models are necessarily better than contemporary Machine Learning models

# Getting Started

## Clone the Repository

If you haven't already, clone the repository to your local machine using the following command:

```
git clone https://github.com/CS4248-Team46/CS4248_Group_46_project.git
```

Change into the repository's directory:

```
cd CS4248_Group_46
```

Make sure your local repository is up to date with the origin:

```
git pull origin main
```

Checkout the branch that you want to explore

```
git checkout deep-learning
```

# Setup instructions

## Data Preparation

Unzip the raw_data files to get started:

```
unzip raw_data/fulltrain.csv.zip -d raw_data/
unzip raw_data/balancedtest.csv.zip -d raw_data/
```

## Feature Scaling and Selection

For selected features, modify this line in the jupyter notebook this code to select which features to fit the models with:

```
# Define selected features

selected_features = [
"readability", "punctuation_count", "punctuation_pair",
"punctuation_diversity", "sentiment", "subjectivity"
]
```

## Running the code

Run the Jupyter Notebook from top to bottom to test out our features.

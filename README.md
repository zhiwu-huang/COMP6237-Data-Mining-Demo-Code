# COMP6237 Data Mining Demo Code

Demo notebooks and supporting utilities for **COMP6237 Data Mining**. The repository is a public fork of `jogrundy/Data-Mining-Demo-Code-18-19`, and it contains a collection of Jupyter notebooks covering core data mining topics used in the course. The current repository description is: **“Demo code for the data mining course.”**

## What this repository contains

The project is organised mainly as Jupyter notebooks, with one `Images/` folder and a small set of helper Python/text files. The notebooks span a broad set of course topics, including:

- recommender systems
- clustering and grouping
- covariance and embeddings
- search / ranking
- document filtering and spam–ham classification
- decision trees
- nearest neighbours
- market basket analysis
- semantic spaces
- topic modelling / finding features
- learning to rank
- outlier detection

There are also paired **visual demo** notebooks for several later modules, including:

- `10_market_basket_visual_demo.ipynb`
- `11_semantic_spaces_visual_demo.ipynb`
- `12_finding_features_visual_demo.ipynb`

## Notebook overview

### Recommenders and similarity
- `02_recommender_with_content_visual.ipynb`
- `09_nearest_neighbours_item_based_miley_demo.ipynb`

### Clustering, grouping, and representations
- `03_clusterings_toys.ipynb`
- `03_groups.ipynb`
- `04_covariance.ipynb`
- `05_embedding_data.ipynb`

### Search, filtering, and classification
- `06_searchRank.ipynb`
- `07_document_filtering_spam_ham.ipynb`
- `08_decisiontrees_offer_case.ipynb`
- `13_learning_to_rank.ipynb`

### Pattern mining and feature discovery
- `10_market_basket_visual_demo.ipynb`
- `11_semantic_spaces_visual_demo.ipynb`
- `12_finding_features_visual_demo.ipynb`

### Outliers
- `13_outlier.ipynb`

### Supporting files
- `metrics.py`
- `porter2_jojo.py`
- `stringProcess.py`
- `alice.txt`
- `alice_cooper.txt`
- `alice_springs.txt`

## Recommended way to use this repository

1. Clone the repository.
2. Create a Python environment with Jupyter installed.
3. Launch Jupyter Notebook or JupyterLab in the project folder.
4. Open the notebook for the lecture or topic you want to teach / revise.
5. For presentation-friendly materials, prefer the `*_visual_demo.ipynb` notebooks where available.

## Suggested environment

A typical setup is:

```bash
python -m venv .venv
source .venv/bin/activate
pip install notebook jupyterlab numpy pandas matplotlib scikit-learn
```

Some notebooks may use additional packages depending on the demo, so install missing dependencies as needed.

## Teaching notes

- The notebooks are best read **alongside the lecture slides**.
- The visual demo notebooks are especially useful for **live teaching**, **classroom walkthroughs**, and **student self-study**.
- Many notebooks are small, self-contained examples designed to illustrate one core concept at a time.

## Repository facts

- Repository: `zhiwu-huang/COMP6237-Data-Mining-Demo-Code`
- Visibility: Public
- Forked from: `jogrundy/Data-Mining-Demo-Code-18-19`
- Primary language: Jupyter Notebook

## License and attribution

Please check the upstream repository and course guidance before redistributing or reusing the notebooks outside teaching / study contexts.

If you use or adapt this material for teaching, it is good practice to acknowledge:
- the upstream fork source
- the COMP6237 course context
- any later edits or visual-demo extensions added in this repository

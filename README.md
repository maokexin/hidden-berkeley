# Hidden Berkeley: HW2 starter

Create your own public website from this starter, then use a Jupyter notebook to edit the data it displays.

**Start here:** on the [HW2 template repository](https://github.com/macss-berkeley/hw2-hidden-berkeley-template), choose **Use this template → Create a new repository**. Name your copy `hidden-berkeley` and make it public. Clone your copy with GitHub Desktop and open its folder in VS Code. Follow [hw2_hidden_berkeley.ipynb](hw2_hidden_berkeley.ipynb).

## What is in this repository?

| File | What it does |
| --- | --- |
| `hw2_hidden_berkeley.ipynb` | Your instructions, data edits, and submission evidence. |
| `docs/_data/locations.csv` | The resource data. The notebook edits this file; the website reads it. |
| `docs/index.md` | The page heading, introduction, and supplied loop that displays the CSV rows. |
| `docs/_config.yml` and `docs/_layouts/default.html` | Supplied website settings and layout. |

GitHub Pages builds the website from `main` and `/docs`. After you push a changed CSV, GitHub rebuilds the page using the new data. Jupyter only edits and saves the data; it does not build the website. The `_data` folder name is required by the website builder.

## Purpose and sources

This guide is designed for students and visitors who are new to Berkeley. It helps them discover useful places for studying, reading, and exploring the local community. The first eight resources were provided by COMPSS 211A, and I added Berkeley Public Library – Central Library, using its official website to check its location and access information.

## Website checks

I checked the published website at https://maokexin.github.io/hidden-berkeley/. All nine resources appeared on the page, including the new Central Library entry. I also checked that Morrison Library's updated access note and Central Library's information matched the saved CSV file. Both official source links opened the intended pages, and the updated heading and introduction appeared correctly.
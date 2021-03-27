# Data Blog Spring 2021 Introduction to EDA: Case Study
This repository is for a Data Blog Spring 2021 Workshop and is designed to give members an introduction to exploratory data analysis with Python.

## Instructions to Get Started
1. Make sure you have jupyter notebook installed on your computer
2. On a terminal/command line, you can execute the command `jupyter --version` and it will tell you which version you have if installed
    - If you do not have jupyter installed, follow these steps of installation for [Getting started with the classic Jupyter Notebook](https://jupyter.org/install)
5. Make sure you have a Github account and:
    - Go to this github repository and either clone, fork, or download it
        - You can fork a repository by [following these instructions](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)
        - You can clone the repository by using the terminal with the command
        - git clone [insert copied http link]
        - or (what I recommend), download Github Desktop and use that to clone your repository (drop down arrow next to green clone button)
    - If this is too complex, you can also download the repository with the download zip command (drop down arrow next to green clone button)
6. On the terminal or command line, run the command `jupyter notebook`. This command should open a tab on your browser where you can create new notebooks.
7. Identify the downloaded/cloned/forked folder in your jupyter notebook to ensure you have it for the meeting.
    - The structure of the jupyter browser is essentially a replica of your file system, so you can navigate through it and see all the files you have in documents, downloads, etc. such as you would using Finder or Libraries

If you are not familiar with Python, watch [this 30 minute video](https://www.youtube.com/watch?v=1QDvkkdyGw0) for a quick introduction to Python and its syntax.

## The Dataset
This tutorial uses the [Melboure Housing Snapshot](https://www.kaggle.com/dansbecker/melbourne-housing-snapshot) dataset from Kaggle. The dataset contains the following columns:
* `Rooms`: Number of rooms
* `Price`: Price in dollars
* `Method`: S - property sold; SP - property sold prior; PI - property passed in; PN - sold prior not disclosed; SN - sold not disclosed; NB - no bid; VB - vendor bid; W - withdrawn prior to auction; SA - sold after auction; SS - sold after auction price not disclosed. N/A - price or highest bid not available.
* `Type`: br - bedroom(s); h - house,cottage,villa, semi,terrace; u - unit, duplex; t - townhouse; dev site - development site; o res - other residential.
* `SellerG`: Real Estate Agent
* `Date`: Date sold
* `Distance`: Distance from CBD
* `Regionname`: General Region (West, North West, North, North east …etc)
* `Propertycount`: Number of properties that exist in the suburb.
* `Bedroom2`: Scraped # of Bedrooms (from different source)
* `Bathroom`: Number of Bathrooms
*  `Car`: Number of carspots
* `Landsize`: Land Size
* `BuildingArea`: Building Size
* `CouncilArea`: Governing council for the area

<div align="center">
 
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ddotta/awesome-polars/)  

*A curated list of [Polars](https://www.pola.rs/) docs, talks, tools, examples & articles the internet has to offer.*  

[Polars](https://www.pola.rs/) is a lightning-fast DataFrame library for Rust, Python, Node.js and R.  
Implemented in Rust, Polars uses [Apache Arrow Columnar Format](https://arrow.apache.org/docs/format/Columnar.html) as the memory model.  

<a href="https://www.pola.rs/" target="_blank" rel="noopener noreferrer">
  <img src="media/polars-logo-dark.png" alt-text="Polars's logo."/>
</a>

</div>

-------------------

<div>
Contributions of any kind welcome!  

Just follow the [guidelines](https://github.com/ddotta/awesome-polars/blob/main/.github/CONTRIBUTING.md) by either:  
  
- Filling a [suggestion issue](https://github.com/ddotta/awesome-polars/issues/new?assignees=ddotta&labels=&template=suggestion.yml).  
- Opening a [pull request](https://github.com/ddotta/awesome-polars/compare).  

To see the latest entries in the list : <a href="https://www.trackawesomelist.com/ddotta/awesome-polars/" target="_blank" rel="noopener noreferrer"> click here !
</a>
</div>

# Awesome Polars
- [Awesome Polars](#awesome-polars)
  - [Official documentation](#official-documentation)
  - [Libraries/Packages/Scripts](#librariespackagesscripts)
    - [Python](#python)
    - [Rust](#rust)
    - [R](#r)
    - [Node.js](#nodejs)
    - [Scala/Java](#scalajava)
    - [Ruby](#ruby)
  - [Resources](#resources)
    - [Cheat Sheets](#cheat-sheets)
    - [Tutorials \& workshops](#tutorials--workshops)
    - [Blog posts](#blog-posts)
    - [Talks and videos](#talks-and-videos)
  - [Follow : Official](#follow--official)
  - [Contributing](#contributing)

## Official documentation

- [Documentation](https://pola-rs.github.io/polars-book/user-guide/) - Official user guide for Python, Rust and R.
- [Documentation for Python API](https://pola-rs.github.io/polars/py-polars/html/reference/) - Official API Reference for Python.
- [Documentation for Rust API](https://pola-rs.github.io/polars/polars/) - Official API Reference for Rust.
- [Documentation for Node.js API](https://pola-rs.github.io/nodejs-polars/index.html) - Official API Reference for Node.js.
- [Shared library plugins for Polars](https://github.com/pola-rs/pyo3-polars).
- [Documentation for R API](https://rpolars.github.io/reference/index.html) - Official API Reference for R.
- [Github: Polars Github Organization](https://github.com/pola-rs) - Official Polars Github repository.
- [Blog posts from Polars](https://www.pola.rs/posts/) - Official blogs posts from Polars.
- [Keynote on Polars at EuroSciPy 2023](https://www.youtube.com/watch?v=GTVm3QyJ-3I&t=43s) &#9203; `57 min` - Talk by [\@ritchie46](https://github.com/ritchie46) that dives into Polars and sees what makes it so efficient.  It will touch on technologies like Arrow, Rust, parallelism, data structures, query optimization and more.
- [Talk about Polars at EuroPython Conference 2023](https://www.youtube.com/watch?v=UwRlFtSd_-8) &#9203; `28 min` - Talk by [\@ritchie46](https://github.com/ritchie46) that introduces Polars and some of its design decisions.

> August 2023 : Polars announces that it [has raised a a $4M seed round](https://www.pola.rs/posts/company-announcement/)!

## Libraries/Packages/Scripts

### Python

- [polars for Python](https://github.com/pola-rs/polars/tree/master/py-polars) - [Python](https://www.python.org/) `polars` package to use polars DataFrame from Python.
- [tidypolars](https://tidypolars.readthedocs.io/en/latest/) `tidypolars` python library built on top of polars library that gives access to methods and functions familiar to R tidyverse users.
- [Working with Polars and XlsxWriter](https://xlsxwriter.readthedocs.io/working_with_polars.html) - Guide to using the Python [XlsxWriter](https://xlsxwriter.readthedocs.io/index.html) library with Polars to create Excel reports.
- [Python package seaborn_polars](https://github.com/pavelcherepan/seaborn_polars) - Python package to plot Polars DataFrames and LazyFrames with [seaborn](https://seaborn.pydata.org/) by [@pavelcherepan](https://github.com/pavelcherepan).
- - [Python package functime](https://docs.functime.ai/) - Machine learning Python package built on Polars for time-series predictions by [@neocortexdb](https://github.com/neocortexdb). According to the developpers, it's the world's fastest and most feature-full machine learning forecasting library !
- [polars-xdt](https://github.com/pola-rs/polars-xdt) - Polars plugin offering eXtra stuff for DateTimes (originally by [@MarcoGorelli](https://github.com/MarcoGorelli)).
- [Ibis Python package for Polars](https://ibis-project.org/backends/polars) - [Ibis](https://github.com/ibis-project/ibis) is a Python library that provides a lightweight, universal interface for data wrangling. It can be used with Polars.
- [Python package polars-ds](https://github.com/abstractqqq/polars_ds_extension) - Python package that contains multiple extension to simplify common numerical/string data analysis procedures by [@abstractqqq](https://github.com/abstractqqq).
- [Narwhals](https://github.com/MarcoGorelli/narwhals) - Python files that provides an extremely lightweight compatibility layer between Polars, Pandas, cuDF, and Modin by [@MarcoGorelli](https://github.com/MarcoGorelli).
- [polars-upgrade](https://github.com/MarcoGorelli/polars-upgrade) - Python package that automatically upgrades your Polars code so it's compatible with future versions by [@MarcoGorelli](https://github.com/MarcoGorelli).
- [polars-fuzzy-match](https://github.com/bnm3k/polars-fuzzy-match) - Python package for fuzzy matching with Polars, i.e. matching text elements that are similar but not exactly identical by [@bnm3k](https://github.com/bnm3k).
- [Polars for Identifiers and Standard Format Strings](https://github.com/abstractqqq/polars_istr) - Python package for Processing IBAN, ISINs, URLs and other standard format data in Polars by [@abstractqqq](https://github.com/abstractqqq).
- [polars_hash](https://github.com/ion-elgreco/polars-hash) - Python package that provides stable hashing functionality across different Polars versions by [@ion-elgreco](https://github.com/ion-elgreco).
- [polars_ta](https://github.com/wukan1986/polars_ta) - Python package that provides technical indicator operators rewritten in Polars by [@wukan1986](https://github.com/wukan1986).
- [QuickEcharts](https://github.com/AdrianAntico/QuickEcharts) - Python package for fast and easy echarts with Polars backend by [@AdrianAntico](https://github.com/AdrianAntico).
- [Polars OLS](https://github.com/azmyrajab/polars_ols) - Python package that provides efficient rust implementations of common linear regression variants and exposes them as simple Polars expressions by [@azmyrajab](https://github.com/azmyrajab).
- [polars-finance](https://github.com/ngriffiths13/polars-finance) - A collection of Python Polars plugins and functions for market data processing by [@ngriffiths13](https://github.com/ngriffiths13).
- [polars-candle](https://github.com/wdoppenberg/polars-candle) - Python package for for running [candle](https://github.com/huggingface/candle) ML models on Polars DataFrames by [@wdoppenberg](https://github.com/wdoppenberg).

### Rust

- [polars for Rust](https://github.com/pola-rs/polars/tree/master/polars) - [Rust](https://www.rust-lang.org/) `polars` crate to use polars DataFrame with Rust.
- [Polars CLI](https://github.com/pola-rs/polars-cli) `Polars CLI` is a command line interface for running SQL queries with Polars as backend. 
- [GeoPolars](https://geopolars.org/) `Geopolars` Rust crate that extends the Polars DataFrame library for use with geospatial data.

### R

- [rpolars for R](https://github.com/pola-rs/r-polars) - [R](https://www.r-project.org/) `rpolars` package to use polars DataFrame from R.
- [tidypolars for R](https://github.com/etiennebacher/tidypolars/) `tidypolars` package to use polars with tidyverse syntax.
- [polarssql](https://github.com/rpolars/r-polarssql) - `polarssql` experimental package which is a DBI-compliant interface to Polars.

### Node.js

- [nodejs-polars for Node.js](https://github.com/pola-rs/nodejs-polars) - [Node.js](https://nodejs.org/en/) `nodejs-polars` package to use polars DataFrame from Node.js.

### Scala/Java

- [scala-polars for Scala and Java](https://github.com/chitralverma/scala-polars) - [Scala](https://scala-lang.org/) - [Java](https://www.java.com/fr/) `scala-polars` is a library for using Polars in Scala and Java projects by [@chitralverma](https://github.com/chitralverma).

### Ruby

- [polars for Ruby](https://github.com/ankane/polars-ruby) - [Ruby](https://www.ruby-lang.org/en/) `polars-df` gems to use Polars with Ruby.

## Resources

### Cheat Sheets

- [Polars Cheat Sheet](https://franzdiebold.github.io/polars-cheat-sheet/Polars_cheat_sheet.pdf) - A Polars Cheat Sheet by [@FranzDiebold](https://github.com/FranzDiebold).
- [Cheatsheet for Pandas to Polars](https://www.rhosignal.com/posts/polars-pandas-cheatsheet/) - A Cheat Sheet that shows how to convert some familiar Pandas commands to Polars by [@braaannigan](https://github.com/braaannigan).

### Tutorials & workshops

- [Modern Polars](https://kevinheavey.github.io/modern-polars/) - A side by side comparison between Polars and Pandas containing code in both frameworks by [@kevinheavey](https://github.com/kevinheavey).
- [Polars: um simples mas prático tutorial](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb) - Tutorial in the format of an ipynb notebook that illustrates several features of Polars in Portuguese by [@barbosarafael](https://github.com/barbosarafael). Associated github repository is [here](https://github.com/barbosarafael/polars_python_test).
- [A Practical Comparison of Polars and Pandas](https://florianwilhelm.info/2021/05/polars_pandas_comparison_notebook/) - A tutorial that showcases several common operations in Pandas and Polars side by side to demonstrate how much easier Polars is by [@FlorianWilhelm](https://github.com/FlorianWilhelm/). There is also an accompanying [Jupyter notebook](https://github.com/FlorianWilhelm/polars_vs_pandas/blob/master/pl_vs_pd.ipynb) available.
- [Prise en main de Polars](http://colab.research.google.com/github/inseefrlab/ssphub/blob/main/content/notebooks/polars-tuto.ipynb) - A notebook tutorial in French that illustrates the main features of Polars by [@romaintailhurat](https://github.com/romaintailhurat) and [@linogaliana](https://github.com/linogaliana). There is also an accompanying [blog post](https://ssphub.netlify.app/post/polars/).
- [Running Polars code distributedly](https://fugue-tutorials.readthedocs.io/tutorials/integrations/backends/polars.html#) - A page that explains how to rung Polars code distributedly with Fugue by [@fugue-project](https://github.com/fugue-project).
- [Converting SQL Queries to Polars DataFrames with JupySQL](https://jupysql.ploomber.io/en/latest/integrations/polars.html?utm_content=buffer13c9f&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer) - A tutorial that explains how to convert SQL queries to Polars DataFrames using JupySQL by [@ploomber](https://github.com/ploomber).
- [How to display Polars dataframes with itables](https://mwouts.github.io/itables/polars_dataframes.html) - A tutorial that explains how to display Polars dataframes with [itables](https://mwouts.github.io/itables/quick_start.html) by [@mwouts](https://github.com/mwouts).
- [Rust Polars: Unlocking High-Performance Data Analysis — Part 1](https://towardsdatascience.com/rust-polars-unlocking-high-performance-data-analysis-part-1-ce42af370ece) - First part of an article that explores the world of Rust’s Polars and explain some basic concepts of Polars such as Series by [@wiseaidev](https://github.com/wiseaidev). Code used is available on Github [here](https://github.com/wiseaidev/rust-data-analysis/blob/main/3-polars-tutorial-part-1.ipynb).
- [Fast String Processing with Polars — Scam Emails Dataset](https://towardsdatascience.com/fast-string-processing-with-polars-scam-emails-dataset-fcf7054a929a) - A tutorial using Polars to  implement a text processing pipeline process by [@AntonsRuberts](https://github.com/AntonsRuberts). Code used is available on Github [here](https://github.com/aruberts/tutorials/tree/main/metaflow/fraud_email).
- [Cookbook Polars for R](https://ddotta.github.io/cookbook-rpolars/) - A side-by-side comparison of Polars, R base, dplyr and data.table packages by [@ddotta](https://github.com/ddotta).
- [Polars Workshop on AWS](https://github.com/debnsuma/pycon_polars101) - A comprehensive workshop comparing Polars to Pandas, exploring a wide range of functions and features by [@debnsuma](https://github.com/debnsuma).
- [Polars cookbook in Python](https://github.com/escobar-west/polars-cookbook) - This cookbook is a fork of the popular pandas-cookbook and has been modified to use the polars library. By [@escobar-west](https://github.com/escobar-west), it uses real-world examples with "all the bugs and weirdness that entails."
- [Data Pipelines with Polars: Step-by-Step Guide](https://towardsdatascience.com/data-pipelines-with-polars-step-by-step-guide-f5474accacc4) - A tutorial that explains how to build data pipelines with Polars by [@AntonsRuberts](https://github.com/AntonsRuberts). Code used is available on Github [here](https://github.com/aruberts/tutorials/tree/main/polars).
- [Python Polars: A Lightning-Fast DataFrame Library](https://realpython.com/polars-python/) - A tutorial that shows how to use Polars with Python ecosystem by [@hfhoffman1144](https://github.com/hfhoffman1144). Code used is available on Github [here](https://github.com/realpython/materials/tree/master/python-polars).
- [Polars plugins tutorial](https://marcogorelli.github.io/polars-plugins-tutorial/) - How you (yes, you!) can write a Polars Plugin, by [@MarcoGorelli](https://github.com/MarcoGorelli).
- [Scripts and datasets for the O'Reilly book Python Polars: The Definitive Guide](https://github.com/jeroenjanssens/python-polars-the-definitive-guide) - Useful Python notebooks ordered by book chapter by [@jeroenjanssens](https://github.com/jeroenjanssens).
- [Python-Polars-Tips-and-Tricks](https://github.com/StuffbyYuki/Python-Polars-Tips-and-Tricks) - Collection of source code demonstrating tips and tricks in Polars by [@StuffbyYuki](https://github.com/StuffbyYuki).

### Blog posts

- [Using the Polars DataFrame Library](https://www.codemag.com/Article/2212051/Using-the-Polars-DataFrame-Library) - A blog post by Wei-Meng Lee to discover the basics of Polars and how it can be used in place of Pandas.
- [Why Polars uses less memory than Pandas](https://pythonspeed.com/articles/polars-memory-pandas/) - A blog post by Itamar Turner-Trauring detailing some techniques to opptimize Pandas memory usage and see how Polars can provide an answer in some cases.
- [Plodding with Polars in Python](https://levelup.gitconnected.com/plodding-with-polars-in-python-defe8399eee6) - A blog post by [@amitrathore](https://github.com/amitrathore) that introduces some basic features of Polars.
- [Polars-lazy](https://lib.rs/crates/polars-lazy) - A blog post by [@ritchie46](https://github.com/ritchie46) and [@jorgecarleitao](https://github.com/jorgecarleitao) that introduces Polars' lazy API in Rust.
- [Series of posts on Polars](https://www.rhosignal.com/tags/polars/) - A series of blogpost on Polars usage with a lot of useful tricks and information by [@braaannigan](https://github.com/braaannigan). Moreover, Liam also has a [Data Analysis with Polars](https://www.udemy.com/course/data-analysis-with-polars/?couponCode=DISCOUNTCODE) course on Udemy.
- [Youtube videos about Polars](https://www.youtube.com/channel/UC-J3uR0g7CxCSnx0YFE6R_g) - A series of short youtube videos about Polars by [@braaannigan](https://github.com/braaannigan)
- [Alternatives to Pandas: Python Polars](https://codesolid.com/alternatives-to-pandas-python-polars/) - An article that explores the Python Polars module as an alternative to Pandas, comparing their similarities and differences and providing some examples by [@JohnLockwood](https://github.com/JohnLockwood)
- [Pandas vs Polars - A comparison on File I/O](https://www.shipyardapp.com/blog/pandas-vs-polars/) - A blog post that evaluates Polars and Pandas in terms of I/O performance and speed when handling large datasets by Wes Poulsen.
- [Discover the Power of Polars Library for Fast and Efficient Data Manipulation in Python](https://python.plainenglish.io/discovering-polars-library-1d63c1eefb44) - An article that quickly compares Polars to other data manipulation libraries by [Morpheus](https://medium.com/@morpheuX/about).
- [Why is Polars All The Rage?](https://seattledataguy.substack.com/p/why-is-polars-all-the-rage) - An article that explains why Polars will become very popular by [SeattleDataGuy](https://substack.com/profile/4963622-seattledataguy) and [Daniel Beach](https://substack.com/profile/21715962-daniel-beach).
- [Polars vs Pandas — 4 key concept differences](https://python.plainenglish.io/polars-vs-pandas-4-key-concept-differences-3c09713c0fe8) - An article that helps to understand key differences between Pandas and Polars Data Science libraries by [@DataScienceDisciple](https://github.com/DataScienceDisciple).
- [Replacing Pandas with Polars. A Practical Guide](https://www.confessionsofadataguy.com/replacing-pandas-with-polars-a-practical-guide) - A blog post comparing some common functions between Pandas and Polars by [@danielbeach](https://github.com/danielbeach). Code used is available on Github [here](https://github.com/danielbeach/PandasVsPolars).
- [Dataframe Showdown – Polars vs Spark vs Pandas vs DataFusion. Guess who wins?](https://www.confessionsofadataguy.com/dataframe-showdown-polars-vs-spark-vs-pandas-vs-datafusion-guess-who-wins/) - A short article that presents a performance test between Polars, Pandas, Datafusion and Spark on a csv dataset by [@danielbeach](https://github.com/danielbeach). Code used is available on Github [here](https://github.com/danielbeach/DataFrameShowDown).
- [7 Easy Steps To Switch From Pandas to Lightning Fast Polars And Never Return](https://towardsdatascience.com/7-easy-steps-to-switch-from-pandas-to-lightning-fast-polars-and-never-return-b14c66fc85b9) - A cheat sheet blog post of the most common Pandas operations translated into Polars by [@BexTuychiev](https://github.com/BexTuychiev).
- [Polars for initial data analysis, Polars for production](https://pythonspeed.com/articles/polars-exploratory-data-analysis-vs-production/) - A blog post that shows how to use Polars for initial data analysis and then effectively in production by [@itamarst](https://github.com/itamarst).
- [DuckDB vs Polars vs Spark!](https://www.karnwong.me/posts/2023/04/duckdb-vs-polars-vs-spark/) - An article that performs a benchmark against duckdb/Polars/spark, with varying row count, with swap usage as another metric, in addition to runtime in seconds. Code used is available on Github [here](https://github.com/kahnwong/dataframe-frameworks-showdown).
- [Benchmarking PySpark Pandas, Pandas UDFs, and Fugue Polars](https://medium.com/fugue-project/benchmarking-pyspark-pandas-pandas-udfs-and-fugue-polars-198c3109a226) - A blog post that compares the execution time of [fugue](https://github.com/fugue-project/fugue/) + Polars, Pandas UDFs and PySpark Pandas by [@kvnkho](https://github.com/kvnkho).
- [Pandas vs. Polars: The Battle of Performance](https://www.makeuseof.com/pandas-vs-polars-which-is-better/) - An another blog post that compares the performance between Pandas and Polars across a range of common data manipulation tasks by [@makeuseofcode](https://github.com/makeuseofcode). Code used is available on [Github](https://github.com/makeuseofcode/Polars-vs-Pandas-Comparison).
- [Pandas 2.0 vs Polars: The Ultimate Battle](https://medium.com/cuenex/pandas-2-0-vs-polars-the-ultimate-battle-a378eb75d6d1) - A blog post that analyzes in terms of Syntax, Speed, and Usability between Pandas 2.0 and Polars 0.17.0 by [@priyanshu7401](https://github.com/priyanshu7401).
- [Polars - modern data frame library](https://dskrzypiec.dev/polars/) - A blog post that describes why Polars could be a better alternative to pandas, dplyr or data.table by [@DSkrzypiec](https://github.com/DSkrzypiec).
- [The fastest way to read a CSV file in Python](https://itnext.io/the-fastest-way-to-read-a-csv-file-in-pandas-2-0-532c1f978201) - A blog post that compares different ways (including Polars, pyarrow and C) to read a CSV file with Python by [Finn Andersen](https://medium.com/@finndersen).
- [Pandas vs Polars vs Pandas 2.0 …. FIGHT](https://levelup.gitconnected.com/pandas-vs-polars-vs-pandas-2-0-fight-7398055372fb) - A blog post that does an ETL process for checking big data speed processing between Pandas, Pandas 2.0 and Polars by [@guoliveira](https://github.com/guoliveira).
- [Pandas vs Polars vs Pandas 2.0 … ROUND 2](https://levelup.gitconnected.com/pandas-vs-polars-vs-pandas-2-0-round-2-e1b9acc0f52f) - A blog post that makes a new comparison between Pandas, Pandas 2.0 and Polars by [@guoliveira](https://github.com/guoliveira).
- [Polars VS PySpark: Lazy Evaluation and Big Data](https://medium.com/@lgsoliveira/polars-vs-pyspark-lazy-evaluation-and-big-data-fbc933cc11af) - A blog post that compares lazy evaluation between Polars and Spark by [@guoliveira](https://github.com/guoliveira).
- [Polars in the aRtic!](https://medium.com/@mcodrescu/polars-in-the-artic-9fda471b6b91) - An another blog post that compares the performance between Pandas and Polars across a range of common data manipulation tasks by [@MCodrescu](https://github.com/MCodrescu). Code used is available on [Github](https://gist.github.com/MCodrescu/45e1adf1ca19863d566a0e0fcead5820).
- [A Polars exploration into Kedro](https://kedro.org/blog/a-polars-exploration-into-kedro) - A blog post that explains how Polars can be used instead of pandas in [Kedro](https://kedro.org/) for your data catalog and data manipulation by [@astrojuanlu](https://github.com/astrojuanlu).
- [High Performance Data Manipulation in Python: pandas 2.0 vs. polars](https://www.datacamp.com/tutorial/high-performance-data-manipulation-in-python-pandas2-vs-polars) - A blog post that compares differences between Python pandas 2.0 and Polars libraries by [@jcanalesluna](https://github.com/jcanalesluna).
- [Lightning-fast queries with Polars](https://dev.to/astrojuanlu/lightning-fast-queries-with-polars-1bp3) - Another blog post that is a good introduction to Polars by [@astrojuanlu](https://github.com/astrojuanlu).
- [Polars – Laziness and SQL Context.](https://www.confessionsofadataguy.com/polars-laziness-and-sql-context/) - A blog post that presents two good reasons to adopt Polars :  Lazy and SQL Context by [@danielbeach](https://github.com/danielbeach).
- [Exploring Polars - The Lightning-Fast DataFrame Library in Python](https://medium.com/@HeCanThink/exploring-polars-the-lightning-fast-dataframe-library-in-python-2d01aa332f70) - A blog post on the basics of Polars by [@mddas](https://github.com/mddas).
- [Pandas vs Polars – Speed Comparison](https://stuffbyyuki.com/pandas-vs-polars-speed-comparison/) - A blog post that compares the performance of Polars, Pandas and Pandas 2.0 by [@StuffbyYuki](https://github.com/StuffbyYuki). Code used is available on Github [here](https://github.com/StuffbyYuki/Python-Polars-Tips-and-Tricks/tree/main/pandas_vs_polars).
- [LazyFrame vs DataFrame in Polars – Performance Comparison](https://stuffbyyuki.com/lazyframe-vs-dataframe-in-polars-performance-comparison/) - A blog post that introduces what LazyFrame is in Polars and its performance gain compared to DataFrame by [@StuffbyYuki](https://github.com/StuffbyYuki). Code used is available on Github [here](https://github.com/StuffbyYuki/Python-Polars-Tips-and-Tricks/tree/main/lazyframe_vs_dataframe).
- [Querying Polars DataFrames using SQL](https://levelup.gitconnected.com/querying-polars-dataframes-using-sql-2471c1ad3014) - A blog post that shows how to use the SQLContext object in Python to query a Polars DataFrame directly using SQL by [@weimenglee](https://github.com/weimenglee).
- [Polars vs Pandas: A Brief Tale of Two DataFrame Libraries](https://dev.to/ranggakd/polars-vs-pandas-a-brief-tale-of-two-dataframe-libraries-lli) - A blog post that compares Polars and Pandas focusing in particular on optional dependencies by [@ranggakd](https://github.com/ranggakd).
- [EDA with Polars: Step-by-Step Guide for Pandas Users (Part 1)](https://towardsdatascience.com/eda-with-polars-step-by-step-guide-for-pandas-users-part-1-b2ec500a1008) - A blog post that describes the main data processing operations with Polars in Python by [@AntonsRuberts](https://github.com/AntonsRuberts). Code used is available in [this notebook](https://github.com/aruberts/tutorials/blob/main/polars/basics.ipynb).
- [EDA with Polars: Step-by-Step Guide to Aggregate and Analytic Functions (Part 2)](https://towardsdatascience.com/eda-with-polars-step-by-step-guide-to-aggregate-and-analytic-functions-part-2-a22d986315aa) - A blog post that shows how to perform with Polars and Python some fairly complex aggregates, rolling statistics and more by [@AntonsRuberts](https://github.com/AntonsRuberts). Code used is available in [this notebook](https://github.com/aruberts/tutorials/blob/main/polars/time_analysis.ipynb).
- [Pyspark or Polars — What should you use?](https://medium.com/data-engineer-things/pyspark-or-polars-what-should-you-use-breakdown-of-similarities-and-differences-b261a825b9d6) - A blog post that explores and breaks down some of the similarities between PySpark and Polars. It provides insights on when to choose one over the other by [Vivek Kovvuru](https://www.linkedin.com/in/vivekkovvuru/).
- [Getting Started with the Polars Data Manipulation Library](https://www.analyticsvidhya.com/blog/2023/07/getting-started-with-the-polars-data-manipulation-library/) - A blog post that presents some simple features of Polars using Python by [Juveriya Mahreen](https://www.analyticsvidhya.com/blog/author/codebestway/).
- [8 ways pandas really losing to Polars for quick market data analysis](https://pyquantnews.com/8-ways-pandas-losing-polars-quick-data-analysis/) - A newsletter that compares the performance of Polars to Pandas for many common data manipulation techniques by [PyQuant News](https://pyquantnews.com/).
- [All that Polars that Make You Forget Pandas](https://medium.com/@tq9695/all-that-polars-that-make-you-forget-pandas-3dc0fdfaefbe) - A blog post that explores some deeper reasons behind the performance gains of Polars over Pandas.
- [Polars vs Pandas. Inside an AWS Lambda](https://www.confessionsofadataguy.com/polars-vs-pandas-inside-an-aws-lambda/) - A blog post that covers the topic of using Polars vs Pandas inside an AWS Lambda to do data processing by [@danielbeach](https://github.com/danielbeach). Code used is available on Github [here](https://github.com/danielbeach/polarsVpandasOnAwsLambda).
- [DuckDB vs Polars for Data Engineering](https://www.confessionsofadataguy.com/duckdb-vs-polars-for-data-engineering/) - A blog post that compares Polars and DuckDB with pipelines for Data Engineering by [@danielbeach](https://github.com/danielbeach).
- [Pandas vs Polars: A database speed test. Who wins?](https://levelup.gitconnected.com/pandas-v-polars-a-database-speed-test-who-wins-f316182a8bca) - A blog post that compares the run-time of reading a database into a dataframe using Pandas versus using Polars by [Thomas Reid](https://medium.com/@thomas_reid).
- [Polars and Pandas : What's the difference ?](https://blog.jetbrains.com/dataspell/2023/08/polars-vs-pandas-what-s-the-difference/) - A blog post that explains how Polars works under the hood and th best use cases for Polars and Pandas by [@t-redactyl](https://github.com/t-redactyl).
- [Understanding the Polars nested column types](https://www.rhosignal.com/posts/nested-dtypes/?s=09) - A blog post that helps to understand how nested column types works in Polars by [@braaannigan](https://github.com/braaannigan).
- [Polars vs DuckDB for Delta Lake ops](https://wolliq.medium.com/polars-vs-duckdb-for-delta-lake-ops-54353107a032) - A blog post that compares Polars to DuckDB using Delta Lake by [@wolliq](https://github.com/wolliq).
- [Enhancing Data Analytics with Polars and MinIO](https://medium.com/learning-the-computers/enhancing-data-analytics-with-polars-and-minio-a04053fff093) - A blog post that explains how to use Polars with Minio’s open-source object storage by [@IndexSeek](https://github.com/IndexSeek).
- [Using Polars with Snowflake](https://medium.com/snowflake/using-polars-with-snowflake-cbdd49b0ca6b) - A blog post that shows how to use Polars with Snowflake by [@IndexSeek](https://github.com/IndexSeek).
- [Partitioning Polars DataFrame on S3 with Apache Arrow](https://medium.com/@matteo.arellano/partitioning-polars-dataframe-on-s3-with-apache-arrow-1fa6518d23f1) - A blog post that explains how to partition large Polars DataFrames in AWS S3 by [Matteo Arellano](https://medium.com/@matteo.arellano).
- [Goodbye Spark. Hello Polars + Delta Lake](https://dataengineeringcentral.substack.com/p/goodbye-spark-hello-polars-delta) - An article that presents how to use Polars in addition to Delta Lake by [@danielbeach](https://github.com/danielbeach).
- [How to learn Polars with ChatGPT?](https://medium.com/@s.illesinghe/how-to-learn-polars-with-chatgpt-62f67bb0a6f8) - An article that explains how to learn fundamental Polars concepts with ChatGPT by [Suhith Illesinghe](https://medium.com/@s.illesinghe).
- [Date and DateTime Manipulation in Polars](https://www.confessionsofadataguy.com/date-and-datetime-manipulation-in-polar/) - A blog post that shows examples of doing a number of date and datetime manipulations in Polars (Python) by [@danielbeach](https://github.com/danielbeach). Code used is available on Github [here](https://github.com/danielbeach/PolarsDateTimeManipulation/tree/main).
- [Pandas2 and Polars for Feature Engineering](https://www.hopsworks.ai/post/pandas2-and-polars-for-feature-engineering) - A blog post that A blog post that compares Pandas2 and Polars for Feature Engineering tasks with Python by [@hopswork](https://github.com/logicalclocks/hopsworks).
- [Spark vs Polars. Real-life Test Case.](https://dataengineeringcentral.substack.com/p/spark-vs-polars-real-life-test-case) - A blog post in which the author tests whether Polars is able to handle "real amounts of data" and "really replace some production Spark workloads." by [@danielbeach](https://github.com/danielbeach). Code used is available on Github [here](https://github.com/danielbeach/PolarsVsPySpark/tree/main).
- [Using Polars Plugins for a 14x Speed Boost with Rust](https://towardsdatascience.com/using-polars-plugins-for-a-14x-speed-boost-with-rust-ce80bcc13d94) - A blog post thats shows the use of Polars plugin system for Rust from some concrete examples by [@ngriffiths13](https://github.com/ngriffiths13).
- [Working with DateTime data in Polars](https://medium.com/@riellygriffiths/working-with-datetime-data-in-polars-9bb57e7f6304) - A blog post to helps you with the main operations that can be done with datetime data by [Rielly Griffiths](https://medium.com/@riellygriffiths).
- [Revolutionize Your Data Analysis: Polars Outperforms Pandas by Up to 5x in Numerical Filter Operations!](https://medium.com/@riellygriffiths/working-with-datetime-data-in-polars-9bb57e7f6304) - A blog post that compares Polars with Pandas by examining their performance in the real world by [Daniel Builescu](https://medium.com/@danielbuilescu).
- [Time series Analysis with Polars](https://dev.to/gaborschulz/time-series-analysis-with-polars-3dfg) - A short blog post that explains how to deal with temporal datasets by [@gaborschulz](https://github.com/gaborschulz). Full helpful notebook available [here](https://github.com/gaborschulz/learning-polars/blob/main/01-time-series-analysis/time-series-analysis.ipynb).
- Interesting thread about Polars on [Hacker News](https://news.ycombinator.com/item?id=38920043)
- [Level Up Your Data Analysis with Polars: A Powerful DataFrame Library for Speed and Efficiency](https://python.plainenglish.io/level-up-your-data-analysis-with-polars-a-powerful-dataframe-library-for-speed-and-efficiency-0b82c226c7f1) - A blog post that describes the main features of Polars (with benchmarks) by [ravi-m](https://ravi-m.medium.com/).
- [polars’ Rgonomic Patterns](https://www.emilyriederer.com/post/py-rgo-polars/) - A blog post that deeps dive into some of the advanced data wrangling functionality in python’s Polars package by [@emilyriederer](https://github.com/emilyriederer).
- [Great Tables: The Polars DataFrame Styler of Your Dreams](https://posit-dev.github.io/great-tables/blog/polars-styling/) - A post that shows how Great Tables package uses polars expressions to make delightful tables by [@machow](https://github.com/machow).
- [Polars dataframe’s plugins and extensibility: getting started](https://medium.com/datamindedbe/polars-dataframes-plugins-and-extensibility-getting-started-9371d8b3f093) - A post that illustrates the possibility of extending the core Dataframe API of Polars with a few examples by [@brunocous](https://github.com/brunocous).
- [15 Pandas ↔ Polars ↔ SQL ↔ PySpark Translations](https://www.blog.dailydoseofds.com/p/15-pandas-polars-sql-pyspark-translations) - A post that depicts the 15 most common tabular operations in Polars and their corresponding translations in Pandas, SQL and PySpark by [@ChawlaAvi](https://github.com/ChawlaAvi).
- [LazyFrame: Exploring Laziness in Dataframes from Polars in Python](https://medium.com/@HeCanThink/lazyframe-exploring-laziness-in-dataframes-from-polars-in-python-46da61d48e79) - A blog post that introduces LazyFrames with Polars an Python by [Manoj Das](https://medium.com/@HeCanThink).
- [Data Statistics in Polars](https://python.plainenglish.io/data-statistics-in-polars-8268be9843c5) - A post that explains how to extract insightful information from your data in Polars by [Alexandre Petit](https://medium.com/@alexandthedataworld).
- [Groupby in Polars](https://python.plainenglish.io/groupby-in-polars-986ef08321ce) - A post that explains how to Learn how to do group data using Polars by [Alexandre Petit](https://medium.com/@alexandthedataworld).
- [DuckDB vs Polars - Thunderdome.](https://dataengineeringcentral.substack.com/p/duckdb-vs-polars-thunderdome) - A blog post that compares Polars and DuckDB with the use of 16 GB of data on a machine of only 4 GB by [@danielbeach](https://github.com/danielbeach).
- [How moving from Pandas to Polars made me write better code without writing better code](https://dev.to/check/how-moving-from-pandas-to-polars-made-me-write-better-code-without-writing-better-code-52bl) - A post that describs the process of "Polarification" of code written with Pandas by [@duvenagep](https://github.com/duvenagep).
- [Revisiting a Classic Cheminformatics Paper with Polars: The Wiener Index](https://bertiewooster.github.io/2023/03/10/Revisiting-a-Classic-Cheminformatics-Paper-The-Wiener-Index.html) - A science blog post that uses Polars to track the information for the molecules in DataFrames by [@bertiewooster](https://github.com/bertiewooster).
- [How to start using Polars & DuckDB together for data analysis](https://ganguly-04.medium.com/how-to-start-using-polars-duckdb-together-for-data-analysis-ded30fcb0bd9) - A post that demonstrates the usage of Polars with DuckDB to perform similar data transformations as is done using Pandas by [@sumaniitm](https://github.com/sumaniitm).
- [Anatomy of a Polars Query: A Syntax Comparison of Polars vs SQL](https://towardsdatascience.com/anatomy-of-a-polars-query-a-syntax-comparison-of-polars-vs-sql-a0035ac8a4fa) - A post that compares Polars syntax to SQL by [@bfeif](https://github.com/bfeif).
- [Pandas vs. Polars — Time to Switch?](https://towardsdatascience.com/pandas-vs-polars-time-to-switch-932d62e7e829) - A blog post that compares Polars to Pandas in a series of 4 benchmarks performed on a csv file with 11 million rows by [@daradecic](https://github.com/daradecic).
- [How to JOIN datasets in Polars … compared to Pandas](https://www.confessionsofadataguy.com/how-to-join-datasets-in-polars-compared-to-pandas/) - A blog post compares dataframe joins in Polars vs Pandas by [@danielbeach](https://github.com/danielbeach).
- [DuckDB vs Polars - Which One Is Faster?](https://medium.com/@yukithejapanese/duckdb-vs-polars-which-one-is-faster-61e73a7680e0) - An unofficial benchmark on DuckDB and Polars by [@StuffbyYuki](https://github.com/StuffbyYuki).
- [Pandas vs Polars? Bid Adieu to Pandas and Switch To Polars!](https://towardsai.net/p/machine-learning/pandas-vs-polars-bid-adieu-to-pandas-and-switch-to-polars?amp=1) - An article that compares Polars to Pandas with a dataset of 1.2 GB. Code used is available on Github [here](https://github.com/sm823zw/pandas-vs-polars).
- [Polars vs. Pandas: 30 Comparison Functions](https://medium.com/@yunuskaradagg/polars-vs-pandas-30-comparison-functions-95335430021b) - A reminder blog post that compares 30 functions written with Polars and Pandas by [Yunuskaradagg](https://medium.com/@yunuskaradagg).

### Talks and videos

- [Polars: Blazingly Fast DataFrames in Rust and Python](https://www.youtube.com/watch?v=kVy3-gMdViM) &#9203; `37 min`  - Introduction to Polars by [databricks](https://www.databricks.com/).
- [Polars: The Next Big Python Data Science Library... written in Rust?](https://www.youtube.com/watch?v=VHqn7ufiilE) &#9203; `14 min` - A short video tutorial to get started coding with Polars by [@RobMulla](https://github.com/RobMulla).
- [The Last Polars Dataframe vs. Pandas Dataframe Video You Should Ever See](https://www.youtube.com/watch?v=4oZiah1R6L8) &#9203; `19 min` - A video that compares Polars and Pandas data frames.
- [The Best library for building Data Pipelines...](https://www.youtube.com/watch?v=mi9f9zOaqM8) &#9203; `12 min` - A video that compares Pandas, Spark and Polars for working with data in Python by [@RobMulla](https://github.com/RobMulla).
- [Expressive & fast dataframes in Python with polars](https://www.youtube.com/watch?v=8nYEX0E07zc) &#9203; `28 min` - A video that reviews some alternatives to Pandas for Python and then demonstrates some Polars features by Juan Luis Cano Rodríguez.
- [Polars Introduction for Python with a 128GB Ryzen 24-core Benchmark vs Pandas](https://www.youtube.com/watch?v=J0wpRP-ExVg&ab_channel=JeffHeaton) &#9203; `12 min` - A video that provides an introduction to Polars for Python by [\@jeffheaton](https://github.com/jeffheaton). Notebook used for the video [in this github repo](https://github.com/jeffheaton/present/blob/master/youtube/polars/polars.ipynb).
- [Polars: The main alternative to pandas in Python!?](https://www.youtube.com/playlist?list=PLo9Vi5B84_dfAuwJqNYG4XhZMrGTF3sBx) &#9203; `57 min` - A Polars tutorial series on Youtube by [\@martinbel](https://github.com/martinbel). Notebooks and datasets used for the videos available [in this github repo](https://github.com/martinbel/polars-tutorial).
- [Polars vs Pandas](https://www.youtube.com/watch?v=jU8Ghp7tRCU&ab_channel=hu-po) &#9203; `37 min` - A detailed video on Youtube that compares Polars and Pandas by [\@hu-po](https://github.com/hu-po).
- [Polars: The Super Fast Dataframe Library for Python — Goodbye Pandas?](https://artificialcorner.com/polars-the-super-fast-dataframe-library-for-python-goodbye-pandas-85156e84337f) - An article and a [video](https://www.youtube.com/watch?v=CByx7XjYMhw) &#9203; `19 min` that explores some basic features of Polars by [@ifrankandrade](https://github.com/ifrankand).
- [Manipulación de Datos con Polars en python](https://www.youtube.com/watch?v=3RM3pWw2iRQ) &#9203; `51 min` - A detailed tutorial video in Spanish that shows 20 Polars functions to perform 80% of the tasks of a data scientist by [Naren Castellon](https://www.linkedin.com/in/naren-castellon-1541b8101/?originalSubdomain=pa).
- [An opinionated introduction to Polars](https://www.dropbox.com/s/fphay3yav2b2rdq/2023_polars.pdf?dl=1) - Great Polars introduction slides from [@krlng](https://github.com/krlng) at PyCon 2023.
- [Polars - make the switch to lightning-fast dataframes](https://www.youtube.com/watch?v=CtkMzCIXOWk) &#9203; `30 min` - A talk that reports an experience switching from Pandas to Polars in a real-world ML project by [@datenzauberai](https://github.com/datenzauberai). Slides are available [here](https://github.com/datenzauberai/PyConDE-2023--Polars-make-the-switch/raw/main/Polars%20-%20make%20the%20switch%20to%20lightning-fast%20dataframes%20-%20Versand.pdf).
- [Polars vs Pandas | detailed test with explained results](https://www.youtube.com/watch?v=tAV-1hPHtsY) &#9203; `22 min` - A video that presents 8 distinct tests which demonstrates differences between Pandas and Polars by [@vb100](https://github.com/vb100). Associated github repo is [here](https://github.com/vb100/polars_vs_pandas).
- [Polars: A highly optimized dataframe library](https://youtu.be/2Yz4VCxRJA4) &#9203; `20 min` - A video that presents some mains features of Polars by [@mattharrison](https://github.com/mattharrison).
- [How to update mass data using Polars DataFrame](https://www.youtube.com/watch?v=ivJSk6JLWBQ) &#9203; `9 min` - A video that presents the process of writing code to update mass columns across CSV or data files by [\@AmitXShukla](https://github.com/AmitXShukla). Notebook used for the video [in this github repo](https://github.com/AmitXShukla/RPA/blob/main/notebooks/Basic%20calculator.ipynb).
- [Using the Rust Polars DataFrame library in a CLI](https://www.youtube.com/watch?v=CUQaoAcc95M) &#9203; `4 min` - A video that shows how to integrate Polars in a commande line interface by [\@paiml](https://github.com/paiml).
- [The Ultimate Guide to Data Wrangling with Python | Rust Polars Data Frame](https://www.youtube.com/watch?v=keCvzMihDfk&list=PLp0TENYyY8lHJaY4t5bAihnFS5TBUQYV1) &#9203; `10 videos` - A playlist of 10 videos (WIP) that equips you with all the necessary knowledge required to utilize Python Polars Data Frame by [\@AmitXShukla](https://github.com/AmitXShukla).
- [Polars DataFrame](https://www.youtube.com/watch?v=clq4NB1OaIA) ⏳ 41 min - A video that shows some basic manipulations with Polars and Python by [@vedica1011](https://github.com/vedica1011). Notebook used for the video [in this github repo](https://github.com/vedica1011/Polars).
- [Why I switched grom Pandas to Polars](https://www.youtube.com/watch?v=u5mIDz5ldmI) ⏳ 53 min - A workshop that breaks down the 3 reasons why you could switched from Pandas to Polars by [@bfeif](https://github.com/bfeif). Notebook used for the video [in this github repo](https://github.com/bfeif/personal-website/blob/main/code/notebooks/the-3-reasons-why-i-have-permanently-switched-from-pandas-to-polars.ipynb).
- [Delimiters in Python Polars](https://www.youtube.com/watch?v=jq1FRZ0VDDk) ⏳ 15 min - A video that explains how to use delimiters in Python Polars by [@CodeKlaudia](https://github.com/CodeKlaudia).
- [Intro to Polars](https://youtube.com/playlist?list=PL6FP7t_F5uo6M-YXwZ5cadqr3EMwPoteP&si=wc1GLcOGcRZU3Uz1) ⏳ 7 videos - A playlist of 7 videos that introduces the basic concepts of Polars (DataFrames, filtering, splitting...) by [Joram Mutenge](https://www.linkedin.com/in/jorammutenge/).
- [Machine Learning with Polars](https://youtube.com/playlist?list=PL6FP7t_F5uo60l16AWCJJHLE6liGPqa7u&si=uNsH5I7GUojXeJmw) ⏳ 6 videos - A playlist of 6 videos that analyzing and cleaning data using Polars to train machine learning models by [Joram Mutenge](https://www.linkedin.com/in/jorammutenge/).
- [Pandas and Polars with Marco Gorelli](https://thebakery.dev/68/) &#9203; `55 min` - A podcast by The Developers' Bakery that compares the performance of Polars to Pandas by [\@MarcoGorelli](https://github.com/MarcoGorelli).
- [Library of the week 13 : Polars with Python](https://www.youtube.com/watch?v=kv7rqHgX20w) ⏳ 15 min - A video that presents Polars with Python by [@enarroied](https://github.com/enarroied). Article supplied with the video [in this page](https://python.plainenglish.io/library-of-the-week-13-polars-fd1398a8841b).
- [Polars and time zones: everything you need to know | PyData Global 2023](https://www.youtube.com/watch?v=DFQFAwt_0VY) ⏳ 29 min - A video that  shows how to use Polars effectively for time series analysis involving different time zones by [@MarcoGorelli](https://github.com/MarcoGorelli).
- [Polars is the Pandas killer | PyData Tel Aviv 2024](https://www.youtube.com/watch?v=sepiszMSvBs) ⏳ 22 min - A video that  shows how Polars is competing head to head with scale, speed and ease of use for dataframe solution in python by [Igor Mintz](https://www.linkedin.com/in/igormintz/?originalSubdomain=il).
- [Polars-Cookbook in Python](https://github.com/PacktPublishing/Polars-Cookbook) - Polars cookbook with organized by Python notebooks and chapter by [@StuffbyYuki](https://github.com/StuffbyYuki).
- [Polars - An Optimized Dataframe Library](https://www.youtube.com/watch?v=6FEvTwmMbOo) ⏳ 84 min - A video that compares the main features of Polars with those of Pandas, with a focus on speeding up your data pipeline by [@mattharrison](https://github.com/mattharrison).
- [DataFrames on steroids with Polars](https://www.youtube.com/watch?v=U5Gl_X6Z7Lk) ⏳ 42 min - A video that demonstrates Polars for Python and shows how much faster it is compared to pandas while remaining just as convenient by [@prosoitos](https://github.com/prosoitos). Slides are available [here](https://mint.westdri.ca/python/wb_polars_slides#/title-slide).

## Follow : Official

- [pola-rs (@pola-rs)](https://github.com/pola-rs) - Github organisation for Polars (Twitter: [@DataPolars](https://twitter.com/DataPolars)).
- [Ritchie Vink (@ritchie46)](https://github.com/ritchie46) - Author of Polars
- [Stijn de Gooijer (@stinodego)](https://github.com/stinodego) - Member of Polars organisation
- [Danny van Kooten (@dannyvankooten)](https://github.com/dannyvankooten) - Member of Polars organisation
- [Søren Havelund Welling (@sorhawell)](https://github.com/sorhawell) - Member of Polars organisation
- [Alexander Beedie (@alexander-beedie)](https://github.com/alexander-beedie) - Contributor to Polars projects
- [Marco Edward Gorelli (@MarcoGorelli)](https://github.com/MarcoGorelli) - Contributor to Polars projects
- [Eitsupi (@eitsupi)](https://github.com/eitsupi) - Contributor to R Polars project
- [Etienne Bacher (@etiennebacher)](https://github.com/etiennebacher) - Contributor to R Polars project

## Contributing

- [Damien Dotta (@ddotta)](https://github.com/ddotta ) - Maintainer of Awesome Polars list
  
Thanks goes to these [contributors](https://github.com/ddotta/awesome-polars/graphs/contributors)!

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
  
- Filling a [suggestion issue](https://github.com/ddotta/awesome-polars/issues/new?assignees=ddotta&labels=&template=suggestion.yml) (easier).  
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
  - [Resources](#resources)
    - [Cheat Sheets](#cheat-sheets)
    - [Tutorials \& workshops](#tutorials--workshops)
    - [Blog posts](#blog-posts)
    - [Talks and videos](#talks-and-videos)
  - [Follow : Official](#follow--official)
  - [Contributing](#contributing)

## Official documentation

- [Documentation](https://pola-rs.github.io/polars-book/user-guide/) - Official user guide for Python, Rust and R.
- [Documentation for Python API ](https://pola-rs.github.io/polars/py-polars/html/reference/) - Official API Reference for Python.
- [Documentation for Rust API ](https://pola-rs.github.io/polars/polars/) - Official API Reference for Rust.
- [Documentation for Node.js API ](https://pola-rs.github.io/nodejs-polars/index.html) - Official API Reference for Node.js.
- [Documentation for R API ](https://rpolars.github.io/reference/index.html) - Official API Reference for R (WIP).
- [Github: Polars Github Organization](https://github.com/pola-rs) - Official Polars Github repository.
- [Blog posts from Polars](https://www.pola.rs/posts/) - Official blogs posts from Polars.

## Libraries/Packages/Scripts

### Python

- [polars for Python](https://github.com/pola-rs/polars/tree/master/py-polars) - [Python](https://www.python.org/) `polars` package to use polars DataFrame from Python.
- [tidypolars](https://tidypolars.readthedocs.io/en/latest/) `tidypolars` python library built on top of polars library that gives access to methods and functions familiar to R tidyverse users.
- [Working with Polars and XlsxWriter](https://xlsxwriter.readthedocs.io/working_with_polars.html) - Guide to using the Python [XlsxWriter](https://xlsxwriter.readthedocs.io/index.html) library with Polars to create Excel reports.

### Rust

- [polars for Rust](https://github.com/pola-rs/polars/tree/master/polars) - [Rust](https://www.rust-lang.org/) `polars` crate to use polars DataFrame with Rust.
- [GeoPolars](https://geopolars.org/) `Geopolars` Rust crate that extends the Polars DataFrame library for use with geospatial data.

### R

- [rpolars for R](https://github.com/pola-rs/r-polars) - [R](https://www.r-project.org/) `rpolars` package to use polars DataFrame from R.

### Node.js

- [nodejs-polars for Node.js](https://github.com/pola-rs/nodejs-polars) - [Node.js](https://nodejs.org/en/) `nodejs-polars` package to use polars DataFrame from Node.js.

### Scala/Java

- [scala-polars for Scala and Java](https://github.com/chitralverma/scala-polars) - [Scala](https://scala-lang.org/) - [Java](https://www.java.com/fr/) `scala-polars` is a library for using Polars in Scala and Java projects by [@chitralverma](https://github.com/chitralverma).

## Resources

### Cheat Sheets

- [Polars Cheat Sheet](https://franzdiebold.github.io/polars-cheat-sheet/Polars_cheat_sheet.pdf) - A Polars Cheat Sheet by [@FranzDiebold](https://github.com/FranzDiebold).

### Tutorials & workshops

- [Modern Polars](https://kevinheavey.github.io/modern-polars/) - A side by side comparison between Polars and Pandas containing code in both frameworks by [@kevinheavey](https://github.com/kevinheavey).
- [Polars: um simples mas prático tutorial](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb) - Tutorial in the format of an ipynb notebook that illustrates several features of Polars in Portuguese by [@barbosarafael](https://github.com/barbosarafael). Associated github repository is [here](https://github.com/barbosarafael/polars_python_test).
- [A Practical Comparison of Polars and Pandas](https://florianwilhelm.info/2021/05/polars_pandas_comparison_notebook/) - A tutorial that showcases several common operations in Pandas and Polars side by side to demonstrate how much easier Polars is by [@FlorianWilhelm](https://github.com/FlorianWilhelm/). There is also an accompanying [Jupyter notebook](https://github.com/FlorianWilhelm/polars_vs_pandas/blob/master/pl_vs_pd.ipynb) available.
- [Prise en main de Polars](http://colab.research.google.com/github/inseefrlab/ssphub/blob/main/content/notebooks/polars-tuto.ipynb) - A notebook tutorial in French that illustrates the main features of Polars by [@romaintailhurat](https://github.com/romaintailhurat) and [@linogaliana](https://github.com/linogaliana). There is also an accompanying [blog post ](https://ssphub.netlify.app/post/polars/). 
- [Running Polars code distributedly](https://fugue-tutorials.readthedocs.io/tutorials/integrations/backends/polars.html#) - A page that explains how to rung Polars code distributedly with Fugue by [@fugue-project](https://github.com/fugue-project).
- [Converting SQL Queries to Polars DataFrames with JupySQL](https://jupysql.ploomber.io/en/latest/integrations/polars.html?utm_content=buffer13c9f&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer) - A tutorial that explains how to convert SQL queries to Polars DataFrames using JupySQL by [@ploomber](https://github.com/ploomber).

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
- [Dataframe Showdown – Polars vs Spark vs Pandas vs DataFusion. Guess who wins? ](https://www.confessionsofadataguy.com/dataframe-showdown-polars-vs-spark-vs-pandas-vs-datafusion-guess-who-wins/) - A short article that presents a performance test between Polars, Pandas, Datafusion and Spark on a csv dataset by [@danielbeach](https://github.com/danielbeach). Code used is available on Github [here](https://github.com/danielbeach/DataFrameShowDown).
- [7 Easy Steps To Switch From Pandas to Lightning Fast Polars And Never Return](https://towardsdatascience.com/7-easy-steps-to-switch-from-pandas-to-lightning-fast-polars-and-never-return-b14c66fc85b9) - A cheat sheet blog post of the most common Pandas operations translated into Polars by [@BexTuychiev](https://github.com/BexTuychiev).
- [Polars for initial data analysis, Polars for production](https://pythonspeed.com/articles/polars-exploratory-data-analysis-vs-production/) - A blog post that shows how to use Polars for initial data analysis and then effectively in production by [@itamarst](https://github.com/itamarst).
- [DuckDB vs Polars vs Spark!](https://www.karnwong.me/posts/2023/04/duckdb-vs-polars-vs-spark/) - An article that performs a benchmark against duckdb/Polars/spark, with varying row count, with swap usage as another metric, in addition to runtime in seconds. Code used is available on Github [here](https://github.com/kahnwong/dataframe-frameworks-showdown).
- [Benchmarking PySpark Pandas, Pandas UDFs, and Fugue Polars](https://medium.com/fugue-project/benchmarking-pyspark-pandas-pandas-udfs-and-fugue-polars-198c3109a226) - A blog post that compares the execution time of [fugue](https://github.com/fugue-project/fugue/) + Polars, Pandas UDFs and PySpark Pandas by [@kvnkho](https://github.com/kvnkho).
- [Pandas vs. Polars: The Battle of Performance](https://www.makeuseof.com/pandas-vs-polars-which-is-better/) - An another blog post that compares the performance between Pandas and Polars across a range of common data manipulation tasks by [@makeuseofcode](https://github.com/makeuseofcode). Code used is available on [Github](https://github.com/makeuseofcode/Polars-vs-Pandas-Comparison).
- [Pandas 2.0 vs Polars: The Ultimate Battle](https://medium.com/cuenex/pandas-2-0-vs-polars-the-ultimate-battle-a378eb75d6d1) - A blog post that analyzes in terms of Syntax, Speed, and Usability between Pandas 2.0 and Polars 0.17.0 by [@priyanshu7401](https://github.com/priyanshu7401).


### Talks and videos

- [Polars: Blazingly Fast DataFrames in Rust and Python](https://www.youtube.com/watch?v=kVy3-gMdViM) &#9203; `37 min`  - Introduction to Polars by [databricks](https://www.databricks.com/).
- [Polars: The Next Big Python Data Science Library... written in Rust?](https://www.youtube.com/watch?v=VHqn7ufiilE) &#9203; `14 min` - A short video tutorial to get started coding with Polars by [@RobMulla](https://github.com/RobMulla).
- [The Last Polars Dataframe vs. Pandas Dataframe Video You Should Ever See](https://www.youtube.com/watch?v=4oZiah1R6L8) &#9203; `19 min` - A video that compares Polars and Pandas data frames.
- [The Best library for building Data Pipelines...](https://www.youtube.com/watch?v=mi9f9zOaqM8) &#9203; `12 min` - A video that compares Pandas, Spark and Polars for working with data in Python by [@RobMulla](https://github.com/RobMulla).
- [Expressive & fast dataframes in Python with polars](https://www.youtube.com/watch?v=8nYEX0E07zc) &#9203; `28 min` - A video that reviews some alternatives to Pandas for Python and then demonstrates some Polars features by Juan Luis Cano Rodríguez.
- [Polars Introduction for Python with a 128GB Ryzen 24-core Benchmark vs Pandas](https://www.youtube.com/watch?v=J0wpRP-ExVg&ab_channel=JeffHeaton) &#9203; `12 min` - A video that provides an introduction to Polars for Python by [\@jeffheaton](https://github.com/jeffheaton). Notebook used for the video [in this github repo](https://github.com/jeffheaton/present/blob/master/youtube/polars/polars.ipynb).
- [Polars: The main alternative to pandas in Python!?](https://www.youtube.com/playlist?list=PLo9Vi5B84_dfAuwJqNYG4XhZMrGTF3sBx) &#9203; `57 min` - A Polars tutorial series on Youtube by [\@martinbel](https://github.com/martinbel). Notebooks and datasets used for the videos available [in this github repo](https://github.com/martinbel/polars-tutorial).
- [Polars vs Pandas](https://www.youtube.com/watch?v=jU8Ghp7tRCU&ab_channel=hu-po) &#9203; `37 min` - A detailed video on Youtube that compares Polars and Pandas by [\@hu-po](https://github.com/hu-po).
- [Polars: The Super Fast Dataframe Library for Python — Goodbye Pandas?](https://artificialcorner.com/polars-the-super-fast-dataframe-library-for-python-goodbye-pandas-85156e84337f) - An article and a [video](https://www.youtube.com/watch?v=CByx7XjYMhw) &#9203; `19 min` that explores some basic features of Polars by [@ifrankandrade](https://github.com/ifrankand)
- [Manipulación de Datos con Polars en python](https://www.youtube.com/watch?v=3RM3pWw2iRQ) - A detailed tutorial video in Spanish that shows 20 Polars functions to perform 80% of the tasks of a data scientist by [Naren Castellon](https://www.linkedin.com/in/naren-castellon-1541b8101/?originalSubdomain=pa).
- [An opinionated introduction to Polars](https://www.dropbox.com/s/fphay3yav2b2rdq/2023_polars.pdf?dl=1) - Great Polars introduction slides from [@krlng](https://github.com/krlng) at PyCon 2023.

## Follow : Official

- [pola-rs (@pola-rs)](https://github.com/pola-rs) - Github organisation for Polars (Twitter: [@DataPolars](https://twitter.com/DataPolars)).
- [Ritchie Vink (@ritchie46)](https://github.com/ritchie46) - Author of Polars
- [Stijn de Gooijer (@stinodego)](https://github.com/stinodego) - Member of Polars organisation 
- [Danny van Kooten (@dannyvankooten)](https://github.com/dannyvankooten) - Member of Polars organisation 
- [Søren Havelund Welling (@sorhawell)](https://github.com/sorhawell) - Member of Polars organisation 
- [Alexander Beedie (@alexander-beedie)](https://github.com/alexander-beedie) - Contributor to Polars projects
- [Marco Edward Gorelli (@MarcoGorelli )](https://github.com/MarcoGorelli ) - Contributor to Polars projects

## Contributing

- [Damien Dotta (@ddotta)](https://github.com/ddotta ) - Maintainer of Awesome Polars list   
  
Thanks goes to these [contributors](https://github.com/ddotta/awesome-polars/graphs/contributors)!

Exchage_Automation
============================

仮想通貨取引を自動化し、億り人になることを目的としたプログラム

Project Organization
------------

    笏懌楳笏� LICENSE
    笏懌楳笏� Makefile           <- Makefile with commands like `make data` or `make train`
    笏懌楳笏� README.md          <- The top-level README for developers using this project.
    笏懌楳笏� data
    笏つ�ﾂ� 笏懌楳笏� external       <- Data from third party sources.
    笏つ�ﾂ� 笏懌楳笏� interim        <- Intermediate data that has been transformed.
    笏つ�ﾂ� 笏懌楳笏� processed      <- The final, canonical data sets for modeling.
    笏つ�ﾂ� 笏披楳笏� raw            <- The original, immutable data dump.
    笏�
    笏懌楳笏� docs               <- A default Sphinx project; see sphinx-doc.org for details
    笏�
    笏懌楳笏� models             <- Trained and serialized models, model predictions, or model summaries
    笏�
    笏懌楳笏� notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    笏�                         the creator's initials, and a short `-` delimited description, e.g.
    笏�                         `1.0-jqp-initial-data-exploration`.
    笏�
    笏懌楳笏� references         <- Data dictionaries, manuals, and all other explanatory materials.
    笏�
    笏懌楳笏� reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    笏つ�ﾂ� 笏披楳笏� figures        <- Generated graphics and figures to be used in reporting
    笏�
    笏懌楳笏� requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    笏�                         generated with `pip freeze > requirements.txt`
    笏�
    笏懌楳笏� setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    笏懌楳笏� src                <- Source code for use in this project.
    笏つ�ﾂ� 笏懌楳笏� __init__.py    <- Makes src a Python module
    笏�   笏�
    笏つ�ﾂ� 笏懌楳笏� data           <- Scripts to download or generate data
    笏つ�ﾂ� 笏つ�ﾂ� 笏披楳笏� make_dataset.py
    笏�   笏�
    笏つ�ﾂ� 笏懌楳笏� features       <- Scripts to turn raw data into features for modeling
    笏つ�ﾂ� 笏つ�ﾂ� 笏披楳笏� build_features.py
    笏�   笏�
    笏つ�ﾂ� 笏懌楳笏� models         <- Scripts to train models and then use trained models to make
    笏�   笏�   笏�                 predictions
    笏つ�ﾂ� 笏つ�ﾂ� 笏懌楳笏� predict_model.py
    笏つ�ﾂ� 笏つ�ﾂ� 笏披楳笏� train_model.py
    笏�   笏�
    笏つ�ﾂ� 笏披楳笏� visualization  <- Scripts to create exploratory and results oriented visualizations
    笏つ�ﾂ�     笏披楳笏� visualize.py
    笏�
    笏披楳笏� tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

# 用語
- 買い残高：信用取引によって買い付けた場合の、まだ決済（お金の返済）されずに残っている額。
- 売り残高：信用売りされたまま、まだ決済されずに残っている金額。
- ポジション：買い残高と売り残高の”どちらが多いのか（傾き）”を表す金融専門用語です。例えば自分が米ドル円を「買いで10万通貨」「売りで5万通貨」もっていた場合, 自分のドル円ポジションは『買いポジションorロングポジション』となる。



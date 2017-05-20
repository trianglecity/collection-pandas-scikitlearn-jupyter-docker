
##
## Collection of Pandas, Scikit-learn, Matplotlib and Jupyter
##

NOTICE 1: the iris analysis is based on 

		[1] http://chrisstrelioff.ws/sandbox/2015/06/08/decision_trees_in_python_with_scikit_learn_and_pandas.html
		
		[2] http://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html
		
		[3] http://scikit-learn.org/stable/modules/tree.html
	


NOTICE 2: the titanic analysis is based on 

		[1] http://www.markhneedham.com/blog/2013/11/09/python-making-scikit-learn-and-pandas-play-nice/

		[2] Titanic_data.txt (CSV and DOC) is from https://vincentarelbundock.github.io/Rdatasets/datasets.html.


NOTICE 3: the board games analysis is taken from

		[1] https://www.dataquest.io/blog/machine-learning-python/


NOTICE 4: TF-IDF is taken from 
		
		[1] http://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html
		
		[2] http://www.ultravioletanalytics.com/2016/11/18/tf-idf-basics-with-pandas-scikit-learn/
		
		[3] http://blog.christianperone.com/2011/09/machine-learning-text-feature-extraction-tf-idf-part-i/

##


 
[1] Download (or git clone) this source code folder.

[2] cd downloaded-soource-code-folder

[3] sudo docker build -t pandas-scikit-learn:02 . (<-- don't forget the dot)

	
	wait ... wait ...

[4] sudo docker run --rm -it -p 8888:8888 --privileged -v $PWD:/home/ml --name jupyter-server pandas-scikit-learn:02 bash

	 a bash shell will be ready (root@d1f8b7c30f33:/# )

[5] root@d1f8b7c30f33:/#  cd /home/ml/notebook

[6] root@d1f8b7c30f33:/home/ml/notebook# jupyter notebook --ip=0.0.0.0  --no-browser --allow-root


	Copy/paste this URL into your browser when you connect for the first time, to login with a token:
        http://0.0.0.0:8888/?token=3201f820977adb80e2c6609a34822d00ce4ebaa36733db25

[7] Open a web browser in the local machine and copy/paste the URL (http://0.0.0.0:8888/?token=3201f820977adb80e2c6609a34822d00ce4ebaa36733db25).


[8 iris] Open the iris_csv.ipynb file.

[9 titanic] Open the titanic_csv.ipynb file.

[10 board games] Open the games_csv.ipynb file.

[11 tfidf] Open the tfidf.ipynb file.



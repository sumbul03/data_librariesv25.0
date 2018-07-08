FROM sanjaydatasciencedojo/data_librariesv12.0

LABEL maintainer="Jupyter Project <jupyter@googlegroups.com>"

USER $NB_USER
RUN pip install pydotplus
RUN pip install nltk
RUN pip install sklearn-pandas
RUN Rscript -e "install.packages('ISLR',repos='https://cloud.r-project.org/',dependencies=TRUE)"
RUN Rscript -e "install.packages('tree',repos='https://cloud.r-project.org/',dependencies=TRUE)"

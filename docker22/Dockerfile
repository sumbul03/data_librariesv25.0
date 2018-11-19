FROM sanjaydatasciencedojo/data_librariesv25.0
USER $NB_USER
RUN Rscript -e "install.packages('igraph',repos='https://cloud.r-project.org/',dependencies=TRUE)"
RUN Rscript -e "install.packages('lpsolve',repos='https://cloud.r-project.org/',dependencies=TRUE)"

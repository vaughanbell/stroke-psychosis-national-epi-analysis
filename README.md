Analysis code and results for the study

# Association between stroke and psychosis across four nationally representative epidemiological studies

<p align="center">
	<a href="https://en.wikipedia.org/wiki/R_(programming_language)"><img
		alt="R Programming Language"
		src="https://img.shields.io/badge/Language-R-%232268BB.svg"></a>
	<a href="https://en.wikipedia.org/wiki/Project_Jupyter#Jupyter_Notebook"><img
		alt="Jupyter Notebook"
		src="https://img.shields.io/badge/Jupyter-Notebook-68B7EB"></a>
	<a href="https://opensource.org/licenses/MIT"><img
		alt="MIT License"
		src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
</p>

------------------------------------------------------------------------

Publication status: currently in pre-print

This archive contains the R code for the analysis reported in the above study. The code is presented as [Jupyter notebooks](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html) which are documents that combine both code and the output in a form that can be viewed online, but also re-run and the results reproduced when accompanied by the original datasets.

This repository contains two Jupyter notebooks that report the analysis and results

1.  [Bell_et_al_StrokePsychosis_Analysis.ipynb](https://github.com/vaughanbell/stroke-psychosis-national-epi-analysis/blob/main/Bell_et_al_StrokePsychosis_Analysis.ipynb) - that reports the main analysis reported in this study
2.  [Bell_et_al_StrokePsychosis_Imputation.ipynb](https://github.com/vaughanbell/stroke-psychosis-national-epi-analysis/blob/main/Bell_et_al_StrokePsychosis_Imputation.ipynb) - that reports the random forest missing data imputation results for the variables taken from the Collaborative Psychiatric Epidemiology Surveys 2001-2003 dataset

### Datasets

------------------------------------------------------------------------

This study used data from four datasets each of which are listed below. The code reads the data files presented in their original form from each dataset and no additional pre-processing is needed.

##### Adult Psychiatric Morbidity Survey 2007 (England, United Kingdom)

This study collected data on mental health among adults aged 16 and over living in private households in England. It was carried out by the National Centre for Social Research (NatCen) in collaboration with the University of Leicester, and was commissioned by the NHS Information Centre for health and social care.

The data can be accessed, following application, from the [UK Data Service](https://beta.ukdataservice.ac.uk/datacatalogue/studies/study?id=6379&amp;type=Data%20catalog#!/documentation).

##### Collaborative Psychiatric Epidemiology Surveys 2001-2003 (United States)

The Collaborative Psychiatric Epidemiology Surveys (CPES) consisted of the three nationally representative psychiatric epidemiology studies of mental health in United States: the National Comorbidity Survey Replication, the National Study of American Life, and the National Latino and Asian American Study of Mental Health.

The data can be downloaded from the [ICPSR website](https://www.icpsr.umich.edu/web/ICPSR/studies/20240).

##### National Mental Health Survey 2015 (Colombia)

The National Mental Health Survey (Encuesta Nacional de Salud Mental) 2015 was a national psychiatric epidemiology study of Colombia completed by the Ministry and Health and Social Protection (Ministerio de Salud y Protección Social).

The data can be access, following application, from the [Repositorio Institucional Digital](https://www.minsalud.gov.co/sites/rid/paginas/freesearchresults.aspx?k=Encuesta%20Nacional%20de%20Salud%20Mental&scope=Exacta), of the Ministerio de Salud.

##### National Health Survey 2016-2017 (Chile)

The National Health Survey (NHS) 2016-2017 (Encuesta Nacional de Salud) was a national survey conducted by the Chilean Ministry of Health of non-institutionalised individuals aged 15 years and older of age residing in households in urban and rural areas across the 15 regions of Chile.

The data can be download from the [Departamento de Epidemiología](http://epi.minsal.cl/condiciones-de-uso/) of the Ministerio de Salud.

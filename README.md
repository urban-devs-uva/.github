# .github
Use this README to navigate through the repositories.

1. dashboarddeelmobiliteit.nl-api repository

   - 'df' folder: pure data collected from api
   - 'aggregated' folder: data processed from 'df' folder results
   - 'heatmap_img' folder: visuilastion for each hour in png format
   - 'heatmap_html' folder: visualisation for each hour in html format
   - 'data' folder: project data points saved in either pkl or csv format
   - pkl/csv files: generated from python files / source of data / final results - distinguished by file name
   - python files: generation of usage variables
   - hotspots_final_code.ipynb: data collection from api dashboarddeelmobiliteit.nl
   - prediction_model_data.ipynb: merging all data for prediction model
   - prediction_model_results.ipynb: model implemeted and results generation

2. google-maps repository
   
   - 'data' folder: source of data
   - 'results' folder: generated results
   - python files: data generation and api collection code
   - csv files: generated data

3. PopulationData repository
   In municipality folder
   
   - population_data.ipynb: data merging and implemented model on income
   - csv files: data source / result
  
4. topic_modelling_news repository

   - topics.ipynb: topic modelling code and results
   - csv files: data source

5. twitter_analysis repository

   - topic_modelling.ipynb: topic modelling code and results
   - csv files: data source / results

6. interview_analysis repository

   - interviews_topic_modeling.ipynb: topic modelling code and results
   - nbhh.docx: interview data
   - freq.pickle: saved results

# Cross-Platform-Performance-Prediction-with-Transfer-Learning-using-Machine-Learning
[Paper available](https://drive.google.com/file/d/1z__mdPmBJA2o7j_FnJzR3kGjb_a1euvy/view)
Machine-learning models are widely used for performance prediction due to its applications in the advancements of hardware-software co-development.  Several researchers have focused on predicting the performance of an unknown target platform (or system) from the known performance of a particular platform (or system); we call this as the cross-platform prediction. Transfer learning is used to reuse previously gained knowledge on a similar task. In this paper, we use transfer learning for solving two problems cross-platform prediction and cross-systems prediction. Our result shows the prediction error of 15\% in case of cross-systems (Simulated to Physical) prediction whereas in case of the cross-platform prediction error of 17\% for simulation-based X86 to ARM prediction and 23\% for physical Intel Core to Intel-Xeon system using best performing tree-based machine-learning model. We have also experimented with dimensionality reduction using PCA and selection of best hyper-parameters using grid search techniques.
## Citation


If you find this repo useful for your research, please consider citing our paper:

```bibtex
@INPROCEEDINGS{9225281,
  author={R. {Kumar} and A. {Mankodi} and A. {Bhatt} and B. {Chaudhury} and A. {Amrutiya}},
  booktitle={2020 11th International Conference on Computing, Communication and Networking Technologies (ICCCNT)}, 
  title={Cross-Platform Performance Prediction with Transfer Learning using Machine Learning}, 
  year={2020},
  volume={},
  number={},
  pages={1-7},
  doi={10.1109/ICCCNT49239.2020.9225281}}

```
For any enquiries, please contact the main authors.


# Folders
##  Dataset_CSV\\all_datasets: Contains input dataset
##  Dataset_CSV\\Transfer_Learning: Contains input dataset for transfer learning
## Codes: Contain all Experimental Codes
## Saved_Models_Data: Contains saved models and cross-folds data, which is available as a link to google drive. 
## Images: Contains images used for Paper
## Results_CSV: Contains Metircs Scores for each Dataset application
## Codes\\Code_for_Plotting_results: Contains code used for plotting and saving images for paper

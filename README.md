
<p align="center">
  <img src="https://github.com/deepdoctection/deepdoctection/blob/master/docs/tutorials/_imgs/dd_logo.png" alt="Deep Doctection Logo" width="60%">
  <h3 align="center">
  A Document AI Package - Jupyter notebook tutorials
  </h3>
</p>

In this repo you will find jupyter notebooks that used to be in the main repo [**deep**doctection](https://github.com/deepdoctection/deepdoctection). If you encouter problems, feel free to open an issue in the **deep**doctection repository.

In addition, the repo contains a folder with examples that are used in the notebooks.

[Get_Started.ipynb](Get_Started.ipynb): 
- Introduction to **deep**doctection
- Analyzer 
- Output structure: Page, Layouts, Tables
- Saving and reading a parsed document

[Pipelines.ipynb](Pipelines.ipynb):
- Pipelines
- Analyzer configuration
- Pipeline components
- Layout detection models
- OCR matching and reading order

[Analyzer_Configuration.ipynb](Analyzer_Configuration.ipynb)
- Analyzer Configuration
- How to change configuration
- High level Configuration
- Layout models
- Table transformer
- Custom model
- Table segmentation
- Text extraction
- PDFPlumber
- Tesseract
- DocTr
- AWS Textract
- Word matching
- Text ordering

[Custom_Pipeline.ipynb](Custom_Pipeline.ipynb): 
- Model catalog and registries
- Predictors
- Instantiating Pipeline backbones
- Instantiating Pipelines

[Datasets_and_Eval.ipynb](Datasets_and_Eval.ipynb): 
- Creation of custom datasets
- Evaluation
- Fine tuning models

[Data_structure.ipynb](Data_structure.ipynb):
- Diving deeper into the data structure
- Page and Image
- `ObjectTypes`
- `ImageAnnotation` and sub categories
- Adding an `ImageAnnotation`
- Adding a `ContainerAnnotation` to an `ImageAnnotation`
- Sub images from given `ImageAnnotation`

[Using_LayoutLM_for_sequence_classification.ipynb](Using_LayoutLM_for_sequence_classification.ipynb): 
- Fine tuning LayoutLM for sequence classification on a custom dataset
- Evaluation 
- Building and running a production pipeline 

[Running_pre_trained_models_from_other_libraries.ipynb](Running_pre_trained_models_from_other_libraries.ipynb)
- Installing and running pre-trained models provided by Layout-Parser
- Adding new categories

The next three notebooks are experiments on a custom dataset for token classification that has been made available 
through [Huggingface](https://huggingface.co/datasets/deepdoctection/FRFPE). It shows, how to train and evaluate each 
model of the LayoutLM family and how to track experiments with W&B. 

[Layoutlm_v1_on_custom_token_classification.ipynb](Layoutlm_v1_on_custom_token_classification.ipynb)
- LayoutLMv1 for financial report NER
- Defining object types
- Visualization and display of ground truth
- Defining Dataflow and Dataset
- Defining a split and saving the split distribution as W&B artifact 
- LayoutLMv1 training
- Further exploration of evaluation
- Evaluation with confusion matrix
- Visualizing predictions and ground truth
- Evaluation on test set
- Changing training parameters and settings

[Layoutlm_v2_on_custom_token_classification.ipynb](Layoutlm_v2_on_custom_token_classification.ipynb)
- LayoutLMv2 for financial report NER
- Defining `ObjectTypes`, Dataset and Dataflow
- Loading W&B artifact and building dataset split
- Exporing the language distribustion across the split
- Evaluation
- LayoutXLM for financial report NER
- Training XLM models on separate languages

[Layoutlm_v3_on_custom_token_classification.ipynb](Layoutlm_v3_on_custom_token_classification.ipynb)
- LayoutLMv3 for financial report NER
- Evaluation
- Conclusion

To use the notebooks **deep**doctection must be installed. 

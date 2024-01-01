# Hi, I'm Umesh! 👋

## 🚀 About Me
I am a data scientist with a strong background in data analysis and machine learning. My expertise lies in effectively harnessing and analyzing data to derive valuable insights. I have a proven track record of applying advanced statistical and machine-learning techniques to tackle complex data challenges, especially time series. My experience includes developing predictive models, identifying patterns, and extracting meaningful information from diverse datasets. I am dedicated to utilizing my skills to drive data-driven decision-making and contribute to the field of data science.

# Time Series Forecasting with HuggingFace Transformers and Gluonts 

This project will build a foundation for using HuggingFace Transformers for any kind of data. Here we are trying to see the use of deep learning based time series frameworks like Gluonts and HuggingFace Transformers to generate the predictions.

### Goals
Learning about the 
  1. How to use the Huggingface Transformer
  2. Use of Gluonts (a deep learning-based time series forecasting engine)
  3. Generate the predictions
  4. And deep dive more in HuggingFace Transformers

💻 Hardware support: Might take longer for 8GM RAM systems. Suggest to move Google Colab 

🔋 Try with your own: Take any forecast/demand data and make use of it to get useful insights.

### Techniques and Library includes (just a demo 😃)
```
1. Load input tourism data using the **datasets** library
2. Transform the time index using custom functions and partial modules
3. Define some features - Lags features, Time features, and statistic categorical features
4. Set the rules or config using TimeSeriesTransformerConfig, TimeSeriesTransformerForPrediction modules
5. Create the features and apply some transformations like missing value treatment and removing unwanted columns using Chain module
6. Using the module as_stacked_batches, create multiple batches of the time series for training
7. Using the model object, pass all target time series and features
8. Call the Accelerator module and select the GPU/CPU
9. Run 100 Epochs; train the model, calculate the gradient and print the loss
10. Evaluate the model using model.eval() on test datasets called test_dataloader
11. Calculate the MASE and SMAPE
12. Print the forecast on again on test data
```

## Getting Started
Follow the below instructions on setting up your project. Nothing much is needed to run the code just Google Colab.

### Installation

1. Forked the repo: Clone it on your suitable project path
git clone https://github.com/Umesh92x/TimeSeriesTransformer.git

### Execution 

#### Step 1
Once forked; it contains
1. Link to Google Colab - https://colab.research.google.com/drive/1QtEoqxdBEe7NIsEHRsP477ivXAxQXVoS?usp=sharing

#### Output

<img width="603" alt="Screenshot 2024-01-01 at 3 47 02 PM" src="https://github.com/Umesh92x/TimeSeriesTransformer/assets/37169232/41aba251-f560-48d3-a4f6-699007dfb9f9">

## 🛠 Skills Enhancement 
Python, Google Colab, Time Series, Huggingface Transformers, and GIT


## Authors

- [@Umesh](https://www.linkedin.com/in/umesh-nagar-515210119/)

## Contributing

If you have a suggestion that would make this better, please fork this repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

- Fork the Project
- Create your work Branch (git checkout -b TimeSeriesTransformer)
- Commit your changes (git commit -m 'Add some change in TimeSeriesTransformer')
- Push to the Branch (git push origin TimeSeriesTransformer)
- Open a Pull Request

## Acknowledgments

- [@umesh](https://huggingface.co/blog/time-series-transformers)


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/Umesh92x)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/umesh-nagar-515210119/)


## Feedback

If you have any feedback, please reach out to me at umesh.nagar92x@gmail.com


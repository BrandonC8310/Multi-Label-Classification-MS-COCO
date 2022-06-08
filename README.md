# Instructions to run the code

## preparations
* environment: python 3.9.7
* requirements: run ```pip install -r requirements.txt ```

* make sure the files are structured as below:
``` 
Root
│─── Algorithm
│       └── clip.ipynb
│─── Input
│       │── train.csv # original csv file
│       │── test.csv # original csv file
│       │── df_train_aug_clean.csv # cleaned csv file
│       │── df_test_aug_clean.csv  # cleaned csv file
│       └── data # the image folder
│─── Output
│       └── result.csv # the prediction csv file
│─── requirements.txt # denpendecies
└─── README.md # this file
```

* run ```Algorithm/clip.ipynb``` with jupyter notebook.
* Output will be generated automatically.
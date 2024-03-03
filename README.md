1. Run
```pip install -r requirements.txt```
to help you install all the dependencies in this project.

2. Place ```test.csv``` file in a same directory along with ```train.csv```.

3. Run ```python3 test.py test.csv``` to run the ```test.py``` script, and it should start building the best ensemble model using a ```train.csv``` and ```test.csv```, and output accuracy and F1 scores.

Note: This program requires training and test sets to produce the best model, i.e., the best model cannot be saved or loaded using pickle.

# END-3.0-Assignment-5

The datasets have been extracted from [torchtext.datasets](https://pytorch.org/text/stable/datasets.html). While in the code, you can know about the Dataset Object using help() function. <br /> <br />

**IMDB Dataset** <br />
Below is how you call the help function on the dataset object.
```
from torchtext.datasets import IMDB
help(IMDB)
``` 
The cell will give you the following output, which tells all about the dataset. It contains total of 50k samples (25k train, 25k test).

```
Help on function IMDB in module torchtext.datasets.imdb:

IMDB(root='.data', split=('train', 'test'))
    IMDB dataset
    
    Separately returns the train/test split
    
    Number of lines per split:
        train: 25000
    
        test: 25000
    
    
    Number of classes
        2
    
    
    Args:
        root: Directory where the datasets are saved.
            Default: .data
        split: split or splits to be returned. Can be a string or tuple of strings.
            Default: ('train', 'test')
```
<br /> <br />

**YelpReviewPolarity Dataset** <br />
Below is how you call the help function on the dataset object.
```
from torchtext.datasets import YelpReviewPolarity
help(YelpReviewPolarity)
``` 
The cell will give you the following output, which tells all about the dataset. It contains total of 598k samples (560k train, 38k test). Unlike YelpReviewFull, this dataset only gives output in 2 categorical classes.

```
Help on function YelpReviewPolarity in module torchtext.datasets.yelpreviewpolarity:

YelpReviewPolarity(root='.data', split=('train', 'test'))
    YelpReviewPolarity dataset
    
    Separately returns the train/test split
    
    Number of lines per split:
        train: 560000
    
        test: 38000
    
    
    Number of classes
        2
    
    
    Args:
        root: Directory where the datasets are saved.
            Default: .data
        split: split or splits to be returned. Can be a string or tuple of strings.
            Default: ('train', 'test')
```
<br /> <br />

Training on each of the 2 datasets, the model gives decent accuracy of classification on test sets (85% on IMDb dataset, 95% on YelpReview). <br /> <br />

Group 21 members : <br />

Mohammed Yaseen (47.yaseen@gmail.com)<br />
Mayank Singhal (singhal.mayank77@gmail.com)<br />
Ravi Vaishnav (ravivaishnav20@gmail.com)<br />
Sundeep Joshi<br />

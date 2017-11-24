# TagNN-PDTB

This repo contains the code for a state-of-the-art discourse relation classifier, trained and tested on [PDTB V2](https://catalog.ldc.upenn.edu/LDC2008T05).

Here We implemented the Tree-LSTM and Tree-GRU models and enhanced them with pos-tag information. You can find more details in our paper at IJCNLP 2017: [Tag-Enhanced Tree-Structured Neural Networks for Implicit Discourse Relation Classiﬁcation]().

## Data

We trained and and tested our models on [PDTB V2](https://catalog.ldc.upenn.edu/LDC2008T05) dataset. You should download them and convert the PDTB into a "pipe" delimited file using the built-in tool in the dataset. And then you need to preprocess the data using the scripts in `preprocess.py`.


## Usage
To run the program, you can use the following command for preparation, train and test:

```
python main.py [--prepare] [--train] [--test]
```

For detailed useage, run `python main.py -h` to see the list of options.

## License

MIT license

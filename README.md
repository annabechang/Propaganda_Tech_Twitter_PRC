# Propaganda Tech Twitter PRC
This repo is for the Mis2-KDD 2021 under review paper: Dataset of Propaganda Techniques of the State-Sponsored Information Operation of the People’s Republic of China


We present our dataset that focuses on propaganda techniques in Mandarin based on a state-linked information operations dataset from the PRC released by Twitter in July 2019. The dataset consists of multi-label propaganda techniques of the sampled tweets. 

In total, we have 9,950 labeled tweets with 21 different propaganda techniques. The tweets are the state-linked information operations dataset from the PRC released by Twitter.

# Please cite
```
 @inproceedings{TwitterPRC,
      author    = "Rong-Ching Chang, Chun-Ming Lai, Kai-Lai Chang, Chu-Hsing Lin",
      title     = "Dataset of Propaganda Techniques of the State-Sponsored Information Operation of the People’s Republic of China",
      year      = "forthcoming",
    }
```

# Table of Content
- [The list of propaganda techniques and their labels](#the-list-of-propaganda-techniques-and-their-labels)
- [How the dataset looks like:](#how-the-dataset-looks-like)
- [Downloading the dataset from Twitter](#downloading-the-dataset-from-twitter)


# The list of propaganda techniques and their labels

| Label | Propaganda Techniques        |
|-------|------------------------------|
| 1     | Presenting Irrelevant Data   |
| 2     | Straw Man                    |
| 3     | Whataboutism                 |
| 4     | Oversimplification           |
| 5     | Obfuscation                  |
| 6     | Appeal to authority          |
| 7     | Black-and-white              |
| 8     | Name Calling                 |
| 9     | Loaded Language              |
| 10    | Exaggeration or Minimisation |
| 11    | Flag-waving                  |
| 12    | Doubt                        |
| 13    | Appeal to fear or prejudice  |
| 14    | Slogans                      |
| 15    | Thought-terminating cliché   |
| 16    | Bandwagon                    |
| 17    | Reductio ad Hitlerum         |
| 18    | Repetition                   |
| 19    | Neutral Political            |
| 20    | Non-Political                |
| 21    | Meme humor                   |

# How the dataset looks like

| Tweetid              | Propaganda Techniques |
|----------------------|-----------------------|
| 990189929 836699648  | 3,8,9                 |
| 114879827 6281364480 | 8,9,13,14             |

We do not provide the tweet content. To fully utilize the dataset, follow the below steps.

# Downloading the dataset from Twitter 
To comply with Twitter's developer policy, we do not share the content of the tweet directly but the tweetid and labels. 
As the data was released, you can download it on twitter directly.

1. Go to > [Twitter Information Operation website](https://transparency.twitter.com/en/reports/information-operations.html)  
https://transparency.twitter.com/en/reports/information-operations.html

2. Go to >03. Download Archive, enter your email
3. By now you should have granted access to download the released dataset.
4. Go to >Datasets released in August 2019
5. Go to > China (July 2019, set 1) - 744 Accounts
6. Go to > Tweet Information (158 MB)
7. Download it. 
8. Now you will have the twitter dataset we build upon. You can use any ways to concate the downloaded dataset with our labeled dataset by the Twitterid. So you will have the following set up and more to empower your research:

| Tweetid              |   Tweet   | Propaganda Techniques |
|----------------------|-----------|-----------------------|
| 990189929 836699648  |           | 3,8,9                 |
| 114879827 6281364480 |           |8,9,13,14              |

We also provided a jupyter notebook for your reference on data preprocessing steps.  

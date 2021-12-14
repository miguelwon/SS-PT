# SS-PT
SS-PT: A Stance and Sentiment data set from Portuguese quoted tweets


Public repository of a corpus made of **16655**  tweets written in Portuguese and annotated to sentiment and stance position. The corpus is specially focused in political tweets and is the first Portuguese corpus annoated for stance position. More details can be found in the following paper:

Won, Miguel and Fernandes, Jorge. *SS-PT: A Stance and Sentiment data set from Portuguese quoted tweets.* Accepted at 15th International Conference, PROPOR.

# Format

We have followed Twitter API rules and do not publish the full tweet content. The corpus is available [here](https://github.com/miguelwon/SS-PT/blob/main/data/ss_pt.csv) and follows the following format:


| *Column* |  *Description*  |
| :-----: | :-----: |
| tw_id| Tweet ID |
| sentiment_labels| annotators' sentiment labels|
| sentiment_winner| winner class for sentiment |
| stance_labels | annotators' stance labels|
| stance_winner | winner class for stance |

**Sentiment** labels dictionary:

| *label* |  *class*  |
| :-----: |  :-----:  |
|    0    | positive  |
|    1    | negative  |
|    2    | neutral  |
|    3    | sarcasm  |
|    4    | inconclusive  |

**Stance** labels dictionary:

| *label* |  *class*  |
| :-----: |  :-----:  |
|    0    | support  |
|    1    | against  |
|    2    | neutral  |
|    3    | inconclusive  |

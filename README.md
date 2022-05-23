# leetcode-daily-predictor
Predict the daily question of leetcode.

### Purpose
> Leetcode's daily questions have a certain regularity. Tags, official solution release time and difficulty degree are all structured data with great labels. 
> 
> This project aims to train model to predict the tags and difficulty degree of the next day's problems , and even list possible problems that may appear tomorrow.


### Schedule
|task|start date|expected achievements|progress|deadline|
|:---:|:---:|:---:|:---:|:---:|
|data collection|5.18|structured data|  |5.20|
|feature selection|5.21|   |  |5.25*|
|SimpleRNN|   |   |   |
|...|   |   |   |

* There is a final exam on June 1st.

##### Phase 1: Data Collection
> * background: data for two years from April 2020 can be obtained on the official website
> 
> * difficulty: 
>   * ~~crawl the list of historical daily questions from `leetcode-cn.com`~~ collect json data with `F12` is ok ...
>   * crawl the details of each problem.
> 
> * further: `leetcode.cn` and `leetcode.com` have different problem lists, data in English may also be used in the future.

- [X] [5/18] Get problem list in json

- [X] [5/19] Get problem details (title, images, tags...)

- [ ] [5/21] Convert to csv format

- [ ] optional: `Official Solution` related labels. And the whole question set is required.
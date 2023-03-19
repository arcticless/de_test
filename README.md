# Most replied comments

Let's imagine a social network where everyone can comment and reply to these comments. The goal of this exercise is to identify the most replied comments. 


## Assumptions

- There is a certain number of ***root*** comments to which people can leave ***replies***;
- Each ***reply*** can be replied an infinite number of times;
- There can be comments with no reply at all;
- Each ***reply*** in itself is a comment;


## Data Set
At the root of this repository you can find a csv with the following structure

```python
parentCommentId,childCommentId
<commentId1>,<commentId2>
<commentId2>,<commentId3>
...

```
- The csv is well-formed, no need to check for correctness
- **CommentId** are between 0 and max Int value.


## Goal
You have to write a solution which in the end will be able to identify the ***topk*** most replyed comments. You can use the CSV dataset provided, if you want to test your solution



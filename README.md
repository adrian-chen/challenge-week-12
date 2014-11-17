# Challenge Week 12 Submission Template

# Reddit Data Challenges

## Challenge 1

[Insert Screenshot]

## Challenge 2

[Explain what's interesting]

## Challenge 3

[Explain possible Insights]

## Challenge 4

[What it would tell you about the Reddit Community]

## Challenge 5

[Link to Code or pasted code]
[Answer]

## Challenge 6

[What does this change about our analysis?]

## Challenge 7

[How would you change your conclusions?]

## Challenge 8

[Bias in answer]

## Challenge 9

[Other Biases]

## Challenge 10

[How may you try and prove the bias]

# Yelp and Weather 

## Challenge 1

[image](Mongo_CH1.png)

## Challenge 2

> db.norm.aggregate([{"$match":{"DATE":{$regex:/20100425/}}},{"$group":{"_id":null,"Average Wind Speed: ":{"$avg":"$HLY-WIND-AVGSPD"}}}])

9.27

## Challenge 3

> db.reviews.aggregate([{"$match":{"type":"business","city":"Madison"}},{"$group":{"_id":null,"Reviews from Madison: ":{"$sum":"$review_count"}}}])

34410 reviews

## Challenge 4

> db.all.aggregate([{"$match":{"type":"business","city":"Las Vegas"}},{"$group": {"_id":null,"Reviews from Vegas: ":{"$sum":"$review_count"}}}])

577550 reviews

## Challenge 5

> db.all.aggregate([{"$match":{"type":"business","city":"Pheonix"}},{"$group":{"_id":null,"Reviews from Pheonix: ":{"$sum":"$review_count"}}}])

16 reviews




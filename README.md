# Sentiment Analyzer

## Overview
The **sentiment-analyzer** project reads product reviews from a CSV file (placed in the `resources` directory) and identifies the sentiment of each review using the Stanford CoreNLP sentiment model.

The analyzer classifies reviews into the following sentiment categories:
- Very Positive
- Positive
- Neutral
- Negative
- Very Negative

This project uses the Stanford CoreNLP (Stanford NLP) model to perform sentiment analysis on textual product reviews.

---

## Features
- Reads product reviews from a CSV file
- Uses Stanford CoreNLP sentiment model (Coreference Resolution Model)
- Provide summary of all the reviews
- Outputs sentiment classification for each review
- Easy to run via main class with CSV input argument

---

## CSV File Format (Required)
The CSV file must be placed inside the `resources` directory and follow the correct format.

### Example Format:
```csv
review_id,review_text
1,This product is amazing and works perfectly!
2,The quality is decent but could be better.
3,Very bad experience, not recommended.
4,Absolutely fantastic! Loved it.
5,It is okay, nothing special.
```
---
## How to Run

**Step 1:** Place CSV File

Put your product review CSV file inside:
````
src/main/resources/
````
**Step 2:** Run the Analyzer

Run the ProductReviewAnalyzer class with the CSV file name as an argument.

Using IDE (IntelliJ / Eclipse)
````
Open ProductReviewAnalyzer class

Add Program Argument: product_reviews.csv

Run the main method
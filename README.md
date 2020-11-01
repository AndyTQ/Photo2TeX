# Photo2TeX
Using ML models to convert text on paper into LaTeX. A H.T.N. 18' Project. Team member: Jimmy, Tina, Welson, Andy

Currently having a high recognition rate on non-mathematical texts & symbols, however we are planning improve the recognition of mathematical syntax in the future.

# [https://devpost.com/software/photo2tex](DevPost) notes from Hack the North 2018:
## Inspiration
Being university students, we often find it difficult to choose an optimal method of taking notes--handwriting is more conductive for learning, but carrying around only a laptop is far more convenient. So we decided to create something to combine the benefits of both.

## What it does
Photo2TeX is an Android app that allows users to take pictures of text, converting paper documents to LaTeX documents in seconds.

## How we built it
The app was built primarily with Java, using the Firebase ML Kit's Text Recognition API to help convert our pictures to plaintext. We structured the app into three distinct modules, and interweaved them to create the final product.

## Challenges we ran into
We initially wanted to create our own ML model to train with characters and symbols, but we found that choosing a good representation of data was difficult. Instead, we choose to use Firebase, allowing us to finish quickly on time.

## Accomplishments that we're proud of
The integration of our three modules was incredibly seamless, and even though we kept running into problems with the Android operating system, we pushed through each one until we were finally satisfied with our product.

## What we learned
APIs make life easier, and Android dev is a bit challenging than we expected.

## What's next for Photo2TeX
Train with a custom ML model, using a dataset including complex mathematical symbols, since Firebase's API was trained with printed (i.e. not handwritten) text. In addition, a web interface would be useful, allowing documents to be accessed from the cloud.

See more info at: https://devpost.com/software/photo2tex

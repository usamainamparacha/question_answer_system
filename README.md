# Question-Answer Generation System
I have used multiple models for question answers generation and tried to make a single solution for good question answer generation. First of all, I want to name those whose model I used:

# For Question generation:
I used, Patil-Suraj Question generator which I found better than any other for question generation.
For more info, you can visit this https://github.com/patil-suraj/question_generation

# For Answer generation:
I used, Quest-Gen for Answer generation since I found its answer generator better than any other. 
For more infor, you can visit https://github.com/ramsrigouthamg/Questgen.ai

# For Keywords Extraction
I used YAKE for keywords extraction since it was simple and very good keywords exrtractor.
For more info, you can visit https://github.com/LIAAD/yake

# For summarization
I used SummaNLP because I found it easier and useful.
For more info, you can visit https://github.com/summanlp/textrank

# My Contribution
I basically tried to make a one stop question answer generation system by using best models for different things. For that I did

1) I write some preprocessing code to remove punctuation and other useless characters from text and cleaning it and splitting it into sperate lines before sending the text for question generation.
2) I did post-processing for making questions useful because otherwise some questions were not good to use since the answer was present in question. 
3) I then used these generated questions to generate their answers using Quest-Gen.

Paraphrases are Seperated By: ->

from transformers import pipeline
generator = pipeline('text-generation',
                     model='zanderbush/Paraphrase')
generator("Hi", num_return_sequences=50, max_length = 48)

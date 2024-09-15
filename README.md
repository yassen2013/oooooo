# oooooo
import random

def shuffle_sentences(sentences):
    random.shuffle(sentences)
    return sentences

sentences = []
for i in range(4):
    sentence = input(f"أدخل الجملة {i+1}: ")
    sentences.append(sentence)

shuffled_sentences = shuffle_sentences(sentences)
print("الجمل بعد التبديل:")

# Python-Project
# to create acronym
phrase = input("Enter a phrase: ")

# to get all words
words = phrase.split()
res = ""
for i in words:

    # to get first letter of each word
    res += i[0]

    # uppercase res
    res = res.upper()

    # output
print(res)

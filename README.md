For: Nitesh Patare

Assignment Output:
https://niteshpatare.github.io/avaamo-lookup-nitesh/index.html

Exercise:
Note - This exercise needs to be taken using Node/Javascript only.

1. Fetch document from given url http://norvig.com/big.txt

2. Analyse the document using asynchronous mechanism, fetched in step 1
   a. Find occurrences count of word in document
   b. Collect details for top 10 words(order by word Occurrences) from
   https://dictionary.yandex.net/api/v1/dicservice.json/lookup, check details of API given below
   i. synonyms/means
   ii. part Of Speech/pos
3. Show words list in JSON format for top 10 words.
   a. Word: text
   b. Output
   i. Count of Occurrence in that Particular Document
   ii. Synonyms
   iii. Pos

API Details
API: https://dictionary.yandex.net/api/v1/dicservice.json/lookup (incorrect)

Documentation:
https://tech.yandex.com/dictionary/doc/dg/reference/lookup-docpage/

API Key:
dict.1.1.20210216T114936Z.e4989dccd61b9626.373cddfbfb8a3b2ff30a03392b4e0b076f14cff9

Below Comments by NITESH

//Notes for moderator
URL is down, cannot be reached
https://dictionary.yandex.net/api/v1/dicservice.json/lookup

//Comments
Q. What is a word?
A. In English, a word has a space on either side of it when it is written.

//Steps for Task 1:

http://norvig.com/big.txt
Downloaded as big.txt on self github repo

// Steps for task 2: Self API Key for Yandex Dictionary API:

1. Create account on Yandex and get API key after login for Yandex Dictionary API.
2. Added desctiption (renault) to generate key.
3. Visit Keys section https://yandex.com/dev/keys/ to view key.
   dict.1.1.20210903T121741Z.9174c6f8c8442176.3dd05252a4e94d29ace81f0bd2cfbeda14666438
4. what is lookup?
   Developers Guide - API Methiods - Lookup Method
   a. Visit Dictionary API - https://yandex.com/dev/dictionary/
   b. View Documentation
   c. Visit Lookup Method. - Search for a word or phrase in the dictionary and returns and automatically generated dictionary entry. It means we have to get meaning/detail of these 10 words which have highest count in the document big.txt/url big.txt (TODO)
   d. Get synonyms / part of speech for these 10 words (TODO)

// Steps for Task 3: Show words list in JSON format for top 10 words.

1. Todo
   a. Word: text (display most repetative words- done)
   b. Output- order by word Occurrences (done), display them both in json and table format with count (done)
   i. Count of Occurrence in that Particular Document (done)
   ii. Synonyms/meaning as well (done)
   iii. Pos (done)

---

Get API Key: https://yandex.com/dev/dictionary/keys/get/?service=dict
dict.1.1.20210903T121741Z.9174c6f8c8442176.3dd05252a4e94d29ace81f0bd2cfbeda14666438

My Keys: https://yandex.com/dev/keys/

Yandex Dictionary: https://yandex.com/dev/dictionary/

Documentation URL:
https://yandex.com/dev/dictionary/doc/dg/reference/lookup.html

All task completed.

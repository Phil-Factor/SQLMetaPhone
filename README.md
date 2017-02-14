Metaphone algorithms are designed to
produce an approximate phonetic representation, in ASCII, of regular
"dictionary" words and names in English and some Latin-based
languages. It is intended for indexing words by their English pronunciation. It
is one of the more popular of the phonetic algorithms and was published by
Lawrence Philips in 1990. A Metaphone is up to ten characters in length.

It is used for fuzzy searches for records
where each string to be searched has an index with a Metaphone key. You search
for all records with the same or similar metaphone key and then refine the
search by some ranking algorithm such as Damerau–Levenshtein distance.
Metaphone searches are particularly popular with ‘ancestor’ sites that search
on surnames where spellings vary considerably for the same surname. The current
version, Metaphone 3, is actively maintained by Lawrence Philips, developed to
account for all spelling variations commonly found in English words, first and
last names found in the United States and Europe, and non-English words whose
native pronunciations are familiar to English-speakers. The source of Metaphone
3 is proprietary, and Lawrence charges a fee to supply the source.

There is a version of Metaphone that is
built into in PHP, and I have used the original public domain source of
Metaphone, and modified it slightly  to
get the same result as the PHP version.

I have commented the source as clearly as I
can to explain what is going on.

Implemented Web Page ranking based on frequecy of occurrance of search Keyword
To Start with we need to give one Seed Url.
Did webcrawling using jsoup and converted found content in the url to text buffer.
Used KMP Algorithm For searching KeyWord in the created text buffer
calculated frequency found keyword in each url while doing the webcrawling and stored the frequency in the hash Set
Recommended the url as output that has most occurrence of search keyword

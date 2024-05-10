Web Page Ranking based on Keyword Frequency
This project implements a simple web page ranking algorithm based on the frequency of occurrence of a search keyword.

Overview
Seed URL: The program starts with a seed URL provided by the user.
Web Crawling: The web crawling process is done using Jsoup, a Java library for working with real-world HTML.
Text Extraction: Content found in the URLs is converted into text buffers.
Keyword Search: The KMP (Knuth-Morris-Pratt) algorithm is employed to search for the given keyword in the text buffer.
Frequency Calculation: Frequency of the keyword found in each URL during web crawling is calculated and stored in a hash set.
Ranking: The URL with the highest occurrence of the search keyword is recommended as the output.

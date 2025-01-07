# Analyzing Right-Wing Media Articles

**Motivation**

Analyzing the individual authors right-wing media helps us understand the structure of the organization and to identify key
players.

**Research Problem**

• How does Article Topic, Length and Publication time differ between Authors?

• Do specific Authors specialize on a single topic?

• Does article sentiment differ between articles containing keywords relating to immigrants from articles not containing the keywords?

• How does the frequency of published articles vary over a week?

**Dataset**

Scraped data with the origin of the following website: “https://www.nius.de/”
A relational database is used to tackle this problem because of its flexibility in storing an retrieving the Data. Our data is
saved in a JSON format with a lot of redundant and unimportant information. Converting this in different database tables
not only improves performance when retrieving just partial data but also saves memory.

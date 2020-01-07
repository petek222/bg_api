The current API for BGG (boardgamegeek.com) is seperated into two specific APIs that operate on two independent servers and requires 
Cross-Origin Resource Sharing (CORS). This dual server platoform, combined with the XML data format, is annoying and unwieldy. The aim of this application will be to act as a parser/lexer of the BGG API to allow similar calls, but instead return the data in a much more user-friendly JSON object. Additionally, this will eliminate the issues of the server dependencies of CORS and provide a much more straightforward way for developers to access the information of BGG's API.

Currently just working through the initial setups of the BGG API, will add more to the README as new stuff is added in due time. 

January 2020
Peter Koncelik 
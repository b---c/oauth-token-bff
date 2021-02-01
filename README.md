# OAuth BFF 

This repository contains the source for the individual draft, `Backend for Frontend Proxy for OAuth2 Authorization Servers` (name subject to change without notice).

`main.md` is the source in markdown format. 

To build the xml2rfc file and transform it into html:

`mmark main.md > draft.xml; xml2rfc --html draft.xml`

(you'll need https://github.com/mmarkdown/mmark and https://pypi.org/project/xml2rfc/)

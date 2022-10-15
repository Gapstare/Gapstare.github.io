SHELL = /bin/bash

all: index.html 2019.html 2018.html 2017.html 2016.html 2015.html

index.html : index.md
	pandoc -s --template blogg.template -T olaekstrom.de -f markdown \
	-t html5 -o index.html index.md

2019.html : 2019.md
	pandoc -s --template blogg.template -T olaekstrom.de -f markdown \
	-t html5 -o 2019.html 2019.md

2018.html : 2018.md
	pandoc -s --template blogg.template -T olaekstrom.de -f markdown \
	-t html5 -o 2018.html 2018.md

2017.html : 2017.md
	pandoc -s --template blogg.template -T olaekstrom.de -f markdown \
	-t html5 -o 2017.html 2017.md

2016.html : 2016.md
	pandoc -s --template blogg.template -T olaekstrom.de -f markdown \
	-t html5 -o 2016.html 2016.md

2015.html : 2015.md
	pandoc -s --template blogg.template -T olaekstrom.de -f markdown \
	-t html5 -o 2015.html 2015.md

clean:
	rm *.html
	rm *~

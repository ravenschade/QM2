all:
	latex skript
	dvipdfmx skript.dvi

lsg:
	sed -i "s/setboolean{lsg}{false}/setboolean{lsg}{true}/g" skript.tex
	latex skript
	dvipdfmx skript.dvi
	sed -i "s/setboolean{lsg}{true}/setboolean{lsg}{false}/g" skript.tex

view:
	okular skript.pdf

clean:
	rm -rf *.log *.dvi *.pdf *.ps *.aux *.out *.toc *.bak *~
	
copy:
	cp skript.pdf  ~/Desktop/Studium/QM2/wise_1011/skript.pdf

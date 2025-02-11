.POSIX:
.SUFFIXES:

endgame.pdf: endgame.md endgame.yml ambigu.PNG sente.PNG C.PNG D.PNG E.PNG F.PNG
	pandoc -o$@ $< endgame.yml

.SUFFIXES: .dot .PNG

.dot.PNG:
	dot -T png $< >$@

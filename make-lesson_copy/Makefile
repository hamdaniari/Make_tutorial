# Count words.
.PHONY : dats
dats : isles.dat abyss.dat
%.dat : books/%.txt
	python countwords.py $< $*.dat
.PHONY : clean
clean :
	rm -f *.dat

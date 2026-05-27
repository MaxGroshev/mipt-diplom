
all:
	pdflatex groshev_diplom.tex pdf -o groshev_diplom.pdf
	rm -rf  *.aux *.log *.fls *.fdb_latexmk *.fls *.gz *.fdb_latexmk *.toc

.PHONY : clean
clean:
	rm -rf $(PREF_OBJ)*.o $(TARGET) *.aux *.log vgcore.*

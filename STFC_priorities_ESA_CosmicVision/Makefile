
TEXFILE=STFC_ESA_priorities
TEXFILE_MEMO=STFC_ESA_priorities_MemoVersion


default: all
# just run it


all :
	pdflatex  ${TEXFILE}
	pdflatex  ${TEXFILE}
	pdflatex  ${TEXFILE}
	rm -f  ${TEXFILE}.aux
	rm -f  ${TEXFILE}.bbl
	rm -f  ${TEXFILE}.blg
	rm -f  ${TEXFILE}.dvi
	rm -f  ${TEXFILE}.log
	rm -f  ${TEXFILE}.out
	rm -f  ${TEXFILE}.toc

	open ${TEXFILE}.pdf

memo :
	pdflatex  ${TEXFILE_MEMO}
	pdflatex  ${TEXFILE_MEMO}
	pdflatex  ${TEXFILE_MEMO}
	rm -f  ${TEXFILE_MEMO}.aux
	rm -f  ${TEXFILE_MEMO}.bbl
	rm -f  ${TEXFILE_MEMO}.blg
	rm -f  ${TEXFILE_MEMO}.dvi
	rm -f  ${TEXFILE_MEMO}.log
	rm -f  ${TEXFILE_MEMO}.out
	rm -f  ${TEXFILE_MEMO}.toc

	open ${TEXFILE_MEMO}.pdf


clean:
	rm -f \
	${TEXFILE}.dvi \
	${TEXFILE}.ps \
	${TEXFILE}.out \
	${TEXFILE}.aux \
	${TEXFILE}.bbl \
	${TEXFILE}.blg \
	${TEXFILE}.toc \
	${TEXFILE}.log 
#	${TEXFILE}.pdf

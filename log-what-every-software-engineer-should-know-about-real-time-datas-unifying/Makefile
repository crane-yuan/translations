.PHONY: typeset

FILES=`cat index.txt`

typeset:
	pandoc                        \
	  --from         markdown     \
	  --to           latex        \
	  --highlight-style zenburn	  \
	  --template	 default.tex \
	  --out          report.pdf   \
	  --pdf-engine   xelatex      \
	  $(FILES)


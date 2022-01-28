default:
	latexmk -pdf

draft: default
	cp main.pdf ./drafts/dissertation-$(shell date +"%m-%d").pdf

clean:
	latexmk -C
	rm -rf tex/*.aux
	rm -rf *.aux
	rm -rf *.ilg
	rm -rf *.idx
	rm -rf *.glo
	rm -rf *.lot
	rm -rf *.log
	rm -rf *.nlo
	rm -rf *.nls
	rm -rf *.out
	rm -rf *.toc
	rm -rf *.bbl
	rm -rf *.blg
	rm -rf *.lof
	rm -rf *.kilepr
	rm -rf *.acr
	rm -rf *.acn
	rm -rf *.alg
	rm -rf *.glg
	rm -rf *.gls
	rm -rf *.ist

prop.pdf: qsim_proposalanddiscr.md q.bib
	pandoc qsim_proposalanddiscr.md --filter pandoc-citeproc -o prop.pdf

detail.pdf: qsim_pathintegral.md q.bib
	pandoc qsim_pathintegral.md --filter pandoc-citeproc -o detail.pdf --pdf-engine=xelatex

quick-bmark.pdf: benchmark_report.md q.bib
	pandoc benchmark_report.md --filter pandoc-citeproc -o quick-bmark.pdf --pdf-engine=xelatex

optimising_layout.pdf: optimising_layout.md q.bib
	pandoc optimising_layout.md --filter pandoc-citeproc -o optimising_layout.pdf --pdf-engine=xelatex

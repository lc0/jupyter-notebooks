.PHONY: deps
deps:
	pip install -r requirements.txt

.PHONY: run
run: deps
	jupyter notebook

.PHONY: serve
serve:
	jupyter nbconvert raffle.ipynb --to slides --post serve
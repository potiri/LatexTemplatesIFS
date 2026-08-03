#Setup

1. Set !main.tex as root
2. define variables in !var.tex: author, cover, etc.
3. define the structure (which sections are included) in !structure.tex

##Notes
- !main.tex and !config.tex should not need additional changes
- \citep and \citet are defined, but use the newer commands internally
- modern sources/bibliography is supported
- abbreviations are sorted alphabetically in the list (define still uses \acro for simplicity)
- List of listings/figures/tables/abbreviations will be hidden if none are present
# Career Pathways for RSEs 
This is the workshop report for our workshop at de-RSE26

## Spelling

**We use British English**

The CI/CD pipeline runs `aspell`. To run it locally use
```bash
aspell -t --home-dir=. -c -d en_GB career-pathways.tex
```
A local list of words is used.

To get a list of misspelled words and their line number use
```bash
bash spellcheck.sh career-pathways.tex
```

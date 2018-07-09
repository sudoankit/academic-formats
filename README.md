# academic-formats
Tips and tricks for formatting while submitting to various conferences and journals for `LaTeX` typesetting only.

## Computer Science Conferences/Journals

### IEEE Transaction

#### Template:

[Template Download](https://www.ieee.org/conferences/publishing/templates.html) 

#### Quickstart

- Use default `IEEEtran.cls` class file and copy it in the same directory as your draft `.tex` file.
- Use `\documentclass[conference, a4paper]{IEEEtran}` or `\documentclass[journal, a4paper]{IEEEtran}` as the first line of your `LaTeX` file.
- Fill your names in `\author` sections.
- Make a copy and edit HOW-TO barebones example inside the template.


That's it! 

#### Bibliography

Bibliography is sorta weird in this and was also the reason I made this repository.

Here's the no frills quickstarter.

- Get your citations/bibliography and put everything inside `sample.bib` file. 

Eg, `sample.bib`

```

@article{sample,
 author = {sudoankit},
 title = {Academic Formats},
 journal = {Self Pubs},
 issue_date = {July 2018},
 volume = {1},
 number = {1},
 month = jul,
 year = {2018},
 issn = {0001-0002},
 pages = {1-2},
 numpages = {3},
 url = {sudoankit.xyz},
 doi = {root of i},
 acmid = {3.14},
 publisher = {bicycle},
 address = {India},
}



```

- Copy this `.bib` file to your working directory.
- If you haven't already/ if it's not already present add `usepackage{cite}`.
- Next, at the end ( where you want your bibliography to be) add

```
\bibliographystyle{IEEEtran}
\bibliography{sample}
```

Note: 

The `IEEEtran` package provides these styles:

* `IEEEtran`: the standard, default `IEEEtran` BibTeX style file. _Just use this._
* `IEEEtranS`: `IEEEtran` + sorting the entries. Normally **NOT** used.
* `IEEEtranSA`: `IEEEtranS` + alphanumeric citations tags.
* `IEEEtranN`: like `IEEEtran` but based on plainmat. Also _compatible with natbib._
* `IEEEtranSN`: `IEEEtranN` + sorting

Q. _Confused what to use?_

A: **`IEEEtran`**

---

Future edits:





---

---


--- TODOS ---


### CVPR 

### NIPS

### AISTATS

### MVA 

### ICCV

### ECCV

### BMVC

### ICML

### ICLR

### JMLR

### SIGGRAPH

### ACM CHI

### WACV

### ICRA

### AAMAS

### 3DV

### IJCAI-ECA

### COLT

### UAI

### CoRL

---

Misc.

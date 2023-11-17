# My CV - Cyril Weerasooriya

I spent sometime looking for an Latex based CV template that is built on frameworks that is already strongly updated but each had their shortcomings. I've shared the source code for my CV that is built on `modern_cv` works and compiles on Overleaf. Most importantly, the publications are built on using the bibfile, so maintaining it is easy. 

* Built using moderncv - https://github.com/moderncv/moderncv
* https://zhauniarovich.com/post/2021/2021-05-cv-resume/

**The file `preview_cv.pdf` is a sample of this source_code**

## How to work with the repo

* `your_cv.tex` - this is the source file for the CV. I've broken everything into individual `tex` files to make it a cleaner implementation. This is the case for service, talks, and work_experience.
* `.bib` files, these are all exports from Zotero. I've bolded my name to highlight when it is compiled in the CV. The CV can be sorted into different types based on the type of the `bib` entry. I've currently setup this in a way such as `inproceedings` type is conference papers, `article` is for journal papers. Line #133-135 is where you should edit. 
# How to Contribute to this Wiki


You first must get invited to the [lab GitHub](https://github.com/davachilab/) and obtain edit access on the [lab Wiki repository](https://github.com/davachilab/davachilab.github.io)
---


## Organization
* This website follows the folder structure under [github.com/davachilab/davachilab.github.io/docs]
* All site pages are created with [Markdown](https://www.markdownguide.org/cheat-sheet/)
* Each root or folder in the directory has a README.md file that serves as that folder's landing page. You must include this file if you create new folders/subfolders! (templates below)


## Contribute from Terminal
1. Clone the [davachilab.github.io repository to your local machine](https://github.com/davachilab/davachilab.github.io)
```bash
git clone https://github.com/davachilab/davachilab.github.io.git
```
2. Create folders/subfolders and files using your favorite text editor
*  Don't forget the README.md file for each root folder!
3. Commit your changes to the site
   1. ```bash
      git add [file names to be added]
      ```
      OR add all changed files (careful...)
      ```bash
      git add .
      ```
   2. ```bash
      git commit -m 'type a message here to describe your commit; e.g. updated image stimuli'
      ```
   3. ```bash
      git push
      ```


---
## Edit on GitHub
**You can create and edit files directly on GitHub, but you cannot create folders**
1. Navigate to directory/file of interest under [davachilab.github.io/docs](https://github.com/davachilab/davachilab.github.io/tree/master/docs)
2. Add file. Include .md file extension in file title
3. Edit your file
4. Scroll down to commit file/changes with a message

source: `{{ page.path }}`

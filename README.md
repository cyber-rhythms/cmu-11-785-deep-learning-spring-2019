# CMU 11-785 Deep Learning Spring 2019 (Bhiksha Raj)

CMU 11-785 Deep Learning Spring 2019 (Bhiksha Raj)

A fully organised, integrity checked repo containing all lecture materials available at
the following coursepage:

http://www.cs.cmu.edu/afs/cs/user/bhiksha/WWW/courses/deeplearning/Fall.2018/www/

The main lecture videos that accompany the contents of this repo are available at*:

https://www.youtube.com/playlist?list=PLp-0K3kfddPzNdZPX4p0lVi6AcDXBofuf

And the recitation videos are available at*:

https://www.youtube.com/playlist?list=PLp-0K3kfddPwYiPKQqMWgYjpFmkW2ifr7

By folder, the repo contains:

1) cmu-11-785-deep-learning-course-page.html - an archived, complete html document that contains
the course schedule, in case the link is no longer hosted by CMU.

2) cmu-11-785-deep-learning-course-page_files - the relevant files to appropriately display the above
html document.

3) homework-assignments - contains the 5 full homework assignments*.

4) lecture-slides - contains all pdf lecture slides*. 

5) projects - for completeness, contains project proposal guidance for the course.

6) recitations - contains all pdf recitation slides, data, python scripts and Jupyter notebooks*.

Remarks:

* course video links - these have not been thoroughly audited and checked, but a cursory glance suggests that
the main lecture video Youtube playlist is fairly complete and consistent with the course page. Similarly
for the recitation lecture video Youtube playlist. Only mild caveat regarding
completeness is that there was some unfamiliar Jupyter notebooks/script content being displayed on screen in some of the later videos. 

* homework-assignments - contains a "spring-2019-incomplete" and "spring-2020-complete" folder. 

The "spring-2019-incomplete" folder shows that a substantial proportion of homework assignments from the Spring 2019 coursepage
is missing. In the interests of completeness; of serving as a reminder that this is the case; and in order to avoid
having to do janitorial/detective work if I ever go over this material at a later date, it has been included.

The only homework-assignment materials available from the Spring 2019 coursepage are:

HW0 - html link
HW1-part1 - html link - "An Introduction to Neural Networks - Neural Networks"
HW1-part2 - html link - "An Introduction to Neural Networks - Frame Level Classification Speech"
HW2-part1 - pdf handout - "An Introduction to Convolutional Neural Networks."
HW2-part2 - pdf handout - "Face Verification via Convolutional Neural Networks"

and all Kaggle links are active.

All the remaining links are broken.

The "spring-2020-complete" folder contains all homework assignments downloaded from the Spring 2020 iteration of
the course. There seem to be broad similarities between the Spring 2019 assignments and Spring 2020 assignments
on the basis of title alone. It is being assumed that the later iteration homework assignments can adequately
and faithfully serve as a substitute for the Spring 2019 assignments. 

In order to stand by the substitution with a higher degree of confidence, the Spring 2019 live Kaggle links content need to
be scrutinised and checked against the content in the Spring 2020 assignments data - pending.

"spring-2020-complete" homework assignment audit - these are exclusively code-implementation based.

Some elements of the homework assignments will use a downloadable autograder script to mark certain elements
of the student's code implementation. Then the implementation is submitted to CMU Autolab. The functionality of the local autograder script is similar to that of Autolab. It is stated in HWP1 that the only difference is that:

- the autograder compares [the student's implementation] outputs and attributes with prestored
data.
- whilst autolab compares [the student's implementation] to a solution.

Furthermore, the submission to AutoLab will record the student's marks. It is also stated that a code implementation which passes the local autograder should, in theory, pass the CMU autolab.

Other elements of the homework assignments are part of open-ended competitions hosted on Kaggle.com. Relevant data can be downloaded from here. CMU students are graded on their rankings on the leaderboard. 

Implementation hints are provided in the form of starter-code and relevant paper references.

As part of my audit, I had to assess whether I, or anyone else interested in using these materials for self-study, could make fruitful use of the materials to accompany the course.

The key question is whether someone self-studying, who does not have access to CMU Autolab, but who does access to the local autograder script would be able to make it through the code implemetations.

This is less of an issue for the open-ended Kaggle competiton parts of the homework assignments.

A closer audit of the materials, by folder:

hw-0 - a self-contained Jupyter notebook for pre-requisite skills in NumPy and PyTorch

hw-1, part 1 - all materials mentioned in the PDF file are contained in hw1p1_handout.tar, and this has been checked. Looks like it is possible for those self-studying to roughly check their code implementations using the local autograder without submission to Autolab.

hw-1, part 2 - all materials needed for this assignment are at the Kaggle page specified within the PDF.

hw-2, part 1 - all materials mentioned in the PDF file are contained in hw2p1_handout.tar, and this has been checked. Again, it looks possible for those self-studying to roughly check theircode implementations using the local autograder without submission to Autolab.

hw-2, part 2 - all materials needed for this assignment are at the Kaggle page specified within the pdf. The compressed file containing the data is stored as "11-785-hw2p2-s20.tgz.zip" at:

https://kaggle.com/c/11-785-s20-hw2p2-classification/data

The relevant compressed folders within "11-785-hw2p2-s20.tgz.zip" are actually .zip files, not .tar files, which is what the PDF,  states under "4.1 File Structure". Other than this negligible detail, all the files to carry out the project are available, and can be submitted to Kaggle.

hw-3, part 1 - all the materials mentioned in the PDF file are contained in hw3p1_handout.tar, and this has been checked. There is a small issue in that the PDF file  mentions a script gru.py that is supposed to be in the mytorch subfolder of the .tar file; but none exists. There is however a gru_cell.py file, so presumably what is written in the PDF is a mild typo. Again, it looks possible for those self-studying to roughly check their code implementations using the local autograder without submission to Autolab.

hw-3, part 2 - the PDF specfies that this part of the proejct is Kaggle based, but does not provide the link, nor is it provided on the coursepage. The link is the following one:

https://www.kaggle.com/c/homework-3-part-2-11785-spring-2020/data

All the materials mentioned on the PDF are consistent with what is listed in the Kaggle link above. All files to carry out the project are therefore available for use.

hw4, part 1 - no materials available from the coursepage, although the PDF file specifies a Jupyter notebook and .tar file. Perhaps it can be found in one of the materials files in the Spring 2020 recitation series? **Pending checking**

hw4, part 2 - the PDF specifies that this part of the project is Kaggle based, but does not provide link, nor is it provided on the coursepage. The link is the following one:

https://www.kaggle.com/c/11-785-s20-hw4p2/data

There are some minor differences between the script names specified in the PDF file, and the scripts listed on the Kaggle data page. But without having done the exercises, it looks consistent and workable.

*lecture-slides - all pdfs checked and consistent with coursepage, except:

Lecture 24 - Variational Autoencoders - a duplicate reinforcement learning lecture was uploaded
on the coursepage for download, titled "lecture-24-rl-pt1-15apr". 

There may be an appropriate substitute in the Spring 2020 iteration of the course.

* recitations

This was tricky to piece together.

The coursepage provided all the PDF handouts for Recitation 0 to Recitation 12 (none for Recitation 13)
and these have been saved into the corresponding numbered recitations subfolders.

However, these materials are no longer available for download from the coursepage, as all
the links are broken.

There rest of the materials i.e. data, python scripts and Jupyter notebooks for Recitation 0 to
Recitation 10 were downloaded from:

https://github.com/cmudeeplearning11785/Spring2019_Tutorials

and are stored in the corresponding numbered recitations subfolders.

The above CMU GitHub repo does not contain any of the PDF Handouts that were originally downloaded
from the CMU coursepage.

From Recitation 11 to Recitation 12, there does not seem to be any associated content
in the form of data, python scripts, nor Jupyter notebooks, and hence the corresponding
numbered recitations subfolders contain only lone PDFs.

Recitation 13 on Reinforcement Learning, referred to as Recitation 12 on the YouTube playlist,
has no accompanying PDF download. Perhaps a substitute can be found from the Spring 2020 iteration?

* readings - not included due to space considerations. May upload in the future, or provide a linked list. 

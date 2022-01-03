# Datasets for Research Method

A git repo to host our datasets used in the course. It's not ideal to store these datasets with the rest of the code, since they quickly bloat the repo, especially since some datasets are reused in different lessons and therefore stored multiple times (somewhat a requirement of distill?). 

By hosting the datastes here, they are very close to the source documents and hosted using the same tools we know (and love). Since this perticular repo ist just for hosting large files, all files in subfolers will be intercepted by git-lfs (see .gitattributes).

Update (2021-12-15):

We have used up our free-git lfs storage of 1GB. The main issue is, that with our worflow we are actually versioncontrolling our big datasets and each historical artefact counts towards our quota. For the future, I propose that we integrate a different workflow for large-ish datasets: Host the files on google drive and use the R package `googledrive` to fetch and push data to and from the drive.



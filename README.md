# A-package-to-download-free-Springer-books-during-Covid-19-quarantine
The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

Introduction
==============
You probably already have seen that Springer released about 500 books for free following the COVID-19 pandemic. According to Springer, these textbooks will be available free of charge until at least the end of July.

Following this announcement, I already downloaded a couple of statistics and R programming textbooks from their website and I will probably download a few more in the coming weeks.

In this article, I present a package that saved me a lot of time and which may be of interest to many of us: the {springerQuarantineBooksR} package, developed by Renan Xavier Cortes.1

This package allows you to easily download all (or a selection of) Springer books made available free of charge during the COVID-19 quarantine.

With this large collection of high quality resources and my collection of top R resources about the Coronavirus, we do not have any excuse to not read and learn during this quarantine.

Without further ado, here is how the package works in practice.
Installation

After having installed the {devtools} package, you can install the {springerQuarantineBooksR} package from GitHub with:

# install.packages("devtools")

library(springerQuarantineBooksR)


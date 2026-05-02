# Project 1 - Imaging and Analyzing for Deleted Files {In Progress}

The main goal of this project is to get experience using digital forensic tools, specifically FTK Imager and Autopsy. I have used both of these before, but I would like to do it in a documented manner. The cool thing about these projects is I can create my own scenario. With that being said, here is the first scenario:

## Secret Sabotage
A CIO for a tech company was on his laptop reviewing files of the business' secrets when he noticed that some of the files were missing. Specifically, the files pertained to confidential projects that would put competitors at a disadvantage. The CIO suspects that the Director of Public Affairs somehow gained access to these files, shared them externally, and deleted them from the company's network. 

As a digital forensic investigator, you have been given a warrant to obtain the laptop and tasked with recovering any deleted files, images, or documents related to the project. Your goal is to recover and document all artifacts in a professional forensic report.

## Walkthrough
### Setup
  - First, I want to put some "evidence" on the laptop. So, I am creating a folder called "Secret Biz" (very secure nomenclature). Within this folder, I am putting various random photos, Excel spreadsheets, and files that look like they could be business secret related.
  - Next, we need to recreate the deleting of the files. I will see if I can replicate exfiltration in a later project, but we will keep it simple for now.
  - Once files have been deleted, we will need an image. In FTK Imager, I am creating a disk image of the Windows vm and saving it to my desktop.

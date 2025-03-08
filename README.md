# uestc-referencing-style
A referencing style for uestc thesis

**NB: This tutorial assumes that you have downloaded, installed, and set up Mendeley Reference Manager on your PC.**

If you are not familiar with Mendeley Reference manager, this video tutorial will tell you all you need to know about it. Link: https://youtu.be/kTUGWGECZgM?si=fiydJgF2_w5YLODt

## About this project
Like other top universities of it's class, UESTC has it's own rules and/or guidlines on how to properly reference other works in your thesis.

This project takes those guidelines and codes them into a **.csl** file (Citation Style language) such that you can directly include it into your work without having to format your work manually yourself.

There are four files in this project. ieee_uestc.csl and ieee_uestc_v2.csl are the original source files made for much older versions of Mendeley and are no longer supported.

**IEEE_UESTC.csl** is an up-to-date version of ieee_uestc_v2.csl and would work on most recent referencing software. It will not work properly when the work type is not specified in your reference manager (By 'work type' I mean Journal, Report, Book, Patent, etc). While **IEEE_UESTC_mod.csl** is a modified version that tries to handle cases where the type of the cited work isn't specified. 

Basically, the main difference between the two is that **IEEE_UESTC_mod.csl** has code for 'error handling' and would mark any unspecified work type in your bibliography with **[X]**. This is the recommended version, use it and look for any such marks in your bibliography and correct them on your Referencing software.

Both links are available below. Copy the link of whichever you choose. 

**IEEE_UESTC_mod.csl** (Recommended):
```https://raw.githubusercontent.com/N-lacy/UESTC-referencing-style/refs/heads/master/IEEE_UESTC_mod.csl```

**IEEE_UESTC.csl**:
```https://raw.githubusercontent.com/N-lacy/UESTC-referencing-style/refs/heads/master/IEEE_UESTC.csl```

The included word document shows the results of using **IEEE_UESTC_mod.csl**.

## Adding the referencing style to your Mendeley Reference Manager via the Mendeley Cite Word Add-on
1. Open MS Word and go to the **References** tab
2. Click on **Mendeley Cite** (see image below)

![image](https://github.com/user-attachments/assets/6c50dcdf-13c5-4cbd-b49d-b737797d3a69)

3. Click on **Citation Settings** then select **Change Citation Style** (see image below)

![image](https://github.com/user-attachments/assets/6b201240-fe18-4565-8967-736a1d5fb62e)

4. Scroll all the way down to **Add a Custom Style**
5. Paste the link you copied into the box 
6. Hit **Enter** or click **Update Citation Style** (see image below)

![image](https://github.com/user-attachments/assets/42a4d6fc-72af-461d-b433-de95ec55a4b3)

You should see **IEEE_uestc** or **IEEE_UESTC** appear on your style list
If it is not automatically sellected, select it and your're good to go. (see image below)

![image](https://github.com/user-attachments/assets/d4f580b2-10a4-4a53-a975-5d0836ac88a7)


## Notes
This project will also work on other referencing softwares that work with **.csl** files. Although not covered in this tutorial.

Other resources:

https://github.com/happymondaynkanta/UESTC-Doctoral-Thesis-Overleaf-Latex-Version-for-International-Students

https://github.com/tinoryj/UESTC-Thesis-Latex-Template/blob/main/README_Eng.md

> [!IMPORTANT]  
> This project is not an official work from UESTC. This is a work done by myself and a former international student of UESTC. It is done to follow the UESTC citation rules to the best of our abilities.
Here's a simple sample guide for the UESTC Citation style.

.

[13] First letter of First name. full spelling of family name, second authors, third authors. title [type of reference]. Name of journal, year, volume (No.): pages-pages  

  Type of reference:   journal ---[J]; conference paper—[C]; book –[M]; thesis—[D]; Newspaper articles—[N]; report—[R], patent—[P], standard—[S]
  
Journal:   [1] authors. Title[J]. name of journal, year, volume(No.):pages-pages

Conference paper: [1] authors. Title[C]. proceeding of conference, space of conference, date of conference, pages-pages

Book : [1] authors. Title[M]. place of publication: press, year of publication, :pages-pages

Thesis: [1] authors. Title[D]. place of university: university, year, pages-pages

Newspaper: [1] authors. Title[N]. name of newspaper, date of publication

Report: [1] authors. Title[R]. place of report: report organizer, date

Patent: [1] authors. Title[P]. nation of patent, type of patent, No. of patent, date

Standard: [1] Standard issuing institution. code of standard. Title[S]. press place: press, date

.

Sometimes, all the details of a reference won't be automantically added to Mendeley, go through your bibliography and modify accordingly.

Below are some examples of what you should check on your references.

A book
![image](https://github.com/user-attachments/assets/57462ebe-a52c-41d3-9fa5-24515c09abfb)

A Journal Article
![image](https://github.com/user-attachments/assets/7a104d29-7d0c-4fb7-be74-6948143752cc)

Unspecified
![image](https://github.com/user-attachments/assets/8174b60e-b75c-4017-9f1c-b25f05bb5586)

If the type is unspecified, the referencing software wouldn't know how to properly include it in your bibliography.

This file can also be used in other reference manager software. However, I provide no tutorial for those. You can find them online.

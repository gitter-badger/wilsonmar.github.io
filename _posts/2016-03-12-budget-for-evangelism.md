---
layout: page
title: Budget spreadsheet
modified: 2016-03-28
excerpt: "Your future, in little boxes"
tags: [budget, spreadsheet, files, jekyll]
image:
# feature: pic white blue spreadsheet 1900x500.jpg
  feature: https://cloud.githubusercontent.com/assets/300046/14622153/33a99aac-0585-11e6-8636-844c34d1699b.jpg
  credit: blog.marketo.com
  creditlink: http://blog.marketo.com/2013/06/the-problems-with-using-spreadsheets-to-manage-your-marketing-budget.html
comments: true
---

{% include _toc.html %}

> BTW, I am available to help you with this. Call me!

## The spreadsheet

Click here to download spreadsheet:<br>
<a target="_blank" href="/assets/Dev_evangelism_budget_v02_wm_2016.03.22.xlsx">
<img alt="btn green download button" src="https://cloud.githubusercontent.com/assets/300046/14232010/80d5fef0-f956-11e5-8caa-f9751ed960f5.png" width="379" height="137"><br>
Dev_evangelism_budget_v02_wm_2016.03.22.xlsx</a><br />
(select Save File).

BTW, the file was created using Microsoft Office 2011 for Mac.

<!-- WARNING: Word locks the file when it open a file, which makes Jekyll think it doesn't exist.
-->

## The columns

* <strong>#</strong> contains counts of the deliverable.

* **Deliverables** short description

* **Urgency**: Number 1 is highest. You may want to use A,B,C,D instead here.

  This column is not used in any calculation.

* **Effort**: Number for estimating, taken from Agile practitioners.

  This number may mean different things to different people.

  The coloring was set by highlighting the column and clicking Word's **Conditional Formatting** icon
  on the Home ribbon or menu Format.

* **%**: auto-calculated by an Excel formula.

  CAUTION: Typing in this column destroys the calculation.

* **Days**: The number of man-days. The number in each row is a fraction of the
  total under the same column within the **Totals** tab.
  A separate tab is used so the Assets sheet can be sorted easier.

  Calculations are based on the percentage of Effort.

  CAUTION: Typing in this column destroys the calculation.

* **Yield**: is for comment about the outcome (FTW).

* **Note**:

## Usage

This spreadsheet helps you realize when you're over-extended with commitments.

Review the man-days to see if it's reasonable,

The number of days at the bottom should be **work-days** (about 20 a month),
less holidays, vacations, and
a margin for various more urgent items that
come up to eat up time along the way.

(> It's better to under-commit and over-deliver than<br />over-commit and under-deliver.)

You can sort this spreadsheet by various columns.

> Want someone to explain this to you? We're available to help. Call me!

## There's more ...

This is part of a series on Evangelism:

{% include evangelist_links.html %}

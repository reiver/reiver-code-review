# GUIDE: code review

by [Charles Iliya Krempeaux](http://changelog.ca/)

---

A guide on what to do and what to not do when doing a **code review**.

## Accetable

These are the things that are acceptable for you to comment on when you are **reviewing** someone else's **code**:

1. bugs

2. missing error handling

3. resource leaks

4. security problems

6. computational complexity problems

*  although do remember that there is often a trade-off between time complexity and space complexity, so there may always be some type of problem ⁠⁠— i.e., pick your poison — but you need to make sure that the trade-off made makes sense for the problem at hand

6. unnecessary coupling

## Not Acceptable

When you are reviewing someone else's code, do not ever give a comment on _style_!

You will just piss them off, make then unhappy, and lower their productivity.

People need to feel that they _own_ the code they are working so that they will take responibility for it.
If you start pushing them to change the style of their code they will no longer feel like they _own_ the code.
They will feel you _own_ the code.
And will not take responsibility for it.

But you need them to feel like they _own_ the code, so that they will take responsibility for it.

## Optional Advise

It is OK to give advice on **future-proofing**, but you MUST make it clear to them that the advise is optional, and they are free to ignore if they want to.


Extracts all the text it can find from a pdf and spell checks words. Particularly good for
spell-checking things you've built into your doc that may not be spell-checked by the software that
creates them, such as figures.

Prerequisites:
aspell
pdftotext
make

Put your pdf file in this directory and run 'make'.

If it throws up words you're ok with, add them to the okwords.en.pws file (it's just text). Some
examples are already there. Feel free to remove them. Don't remove the first line.

If okwords.en.pws exceeds 500 words, you may (but probably won't) need to change the '500' in the
first line to reflect this.

## PDF 2: Using OCR to extract data

start with a tool called tesseract.

Manafort documents. Filed documents on Pacer. Drew black boxes over the text. 

pdftotext Manafort_filing.pdf manafort.txt - This creates a text document that is completely searchable.

computer generated pdfs are techincaally XML, pdftotext is parsing that xml

quicker than tabula

image, use tesseract to turn it into machine readable format, then use pdftotext to turn it into a table

pdfminer

image magic

for long image files that are long strings of several pages, you can pass the crop size to turn the tiff into seven tiffs
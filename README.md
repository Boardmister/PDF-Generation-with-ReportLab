# PDF-Generation-with-ReportLab
Generate a PDF document using the ReportLab library
from reportlab.pdfgen import canvas

def generate_pdf(file_path):
    c = canvas.Canvas(file_path)
    c.drawString(100, 750, "Hello, this is a PDF document generated using ReportLab.")
    # Add more content as needed
    c.save()

generate_pdf('generated_document.pdf')

# Automated-VAPT-Report-Generator
still in development

Improve the quality and performance of your workflow

Advanced reporting technology, to improve speed, reduce latency, and provide full visibility

The challenge -> Pentest reporting are often the bottlenecks.

The solution -> The AVGR Platform uses a transparent reporting generator to improve performance.

Don't spend countless minutes writing reports for people you work for. AVRG will take care of this.

AVRG (automatic-VAPT-report-generator), a custom pentest reporting application using the Python Django framework. AVRG takes the test output from test and generates a full fledged PDF report that helps visualize your business cases. The main goal is to make report in less time than ever. 

There is slightly different between pwndoc. We're providing server to generate which pentester just need to click and drop. To ensure integrity we will not save session/cache/data. 

## Features
- Simple, clean, and modern design
- test
- test

put inside docker like BlackStone (Azure or AWS)

## Objectives
Open-source generator that public can use / build custom for companies template

Mcm 'reporting biasa' tapi gunakan server website utk run GPU supaya tak perlu nak guna laptop (boleh guna hp sahaja utk generate report)
Disebabkan jika report terlampau banyak finding menyebabkan sesetengah employee tak dpt nk generate report (laptop hang)
Tak perlu simpan pdf dlm databases, selepas siap letak dia dlm /tmp then lepas emplyee download, dia akan auto delete (Integrity selamat)

## Project Planning Approaches
Study & Research about Django Web > RnD all possible Concepts > Implementation Accumulated Data in Project > Build 1st Demo > Test & Debug System > Find loophole > Focus visualization > Project Enchancement > Finalize Project > QA Testing > Deploy Project in Staging Environment > Clone & Deploy in Live Environment > DR monthly

## [Study & Research about Django Web](https://github.com/g3nj1z/Jom-Belajar-Django)

### Build documentation/manual on Gitbook

### Installation
Production?

Libary

    pip3 install pdfkit

### Roles
List of permissions:
1. Vulnerabilities
- vulnerabilities:create
- vulnerabilities:read
- vulnerabilities:update
- vulnerabilities:delete

2. Settings
- settings:read
- settings:update

### Vulnerabilities
- Create
When creating a Vulnerability, a Category must be selected (or No Category)

A Vulnerability is defined by:

    Title
    Type
    Language
    Description
    Observation
    CVSS
    Remediation
    Remediation Complexity
    Remediation Priority
    References
    Category
    
- Import/Export
- Merge
- Validate

### Authentication and Authorization

## References

### Learn and research how to build Django Web Development from Zero
[cs50w - Django](https://youtu.be/w8q0C-C1js4)

Example Project(s)
1. https://github.com/sclorg/django-ex

### Available public open source report generator
[pwndoc](https://github.com/pwndoc/pwndoc)
[BlackStone](https://github.com/micro-joan/BlackStone)
https://stackoverflow.com/questions/69511125/report-builder-for-django

[laravel report generator](https://github.com/Jimmy-JS/laravel-report-generator)

### Export Django from html to pdf
[wkhtmltopdf](https://ourcodeworld.com/articles/read/241/how-to-create-a-pdf-from-html-in-django)
[django-wkhtml](https://github.com/incuna/django-wkhtmltopdf)
https://spapas.github.io/2022/02/14/django-pdfs-2022/

### Generator graph/chart
1. https://youtu.be/_SipEeFe-cw 
2. https://youtu.be/6yTYP39d9Gs (use this concept to learn how to use .csv to generate output)
3. https://github.com/jakupierblina/Youtube-expert-assist- (using chart.js to generate chart)

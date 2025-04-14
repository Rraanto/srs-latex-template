This is a template for a SRS (Software Requirements Specification) report in LaTeX. The aim is to provide a well-structured document using as little packages as possible.

## Structure: 
The main file ```main.tex```: contains the title page, table of contents. The document is divided into five (05) sections, each is written in a separate file at ```/parts/[section_name].tex``` which is imported into the main.

```
root/
│
├── main.tex
└── parts/
    ├── Introduction
    ├── Overall_description
    ├── System_features
    ├── External_interface_requirements
    └── Nonfunctional_requirements
```

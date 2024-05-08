# General Template Information

The document exemplifies a design philosophy, embodying a resilient and adaptable structure. Leveraging an extensive array of macros, the document achieves heightened reusability while mitigating redundancy, encapsulating prevalent structures, styles, and formatting. This approach ensures a consistent and cohesive presentation across the entirety of the project. Additionally, the project is fortified with a robust Continuous Integration/Continuous Deployment (CI/CD) pipeline, serving to optimize collaboration and development workflows, thereby fostering efficiency and agility in the software development life cycle.

# AI Integration Guide
1. Download Jan.AI
    - `https://jan.ai/ `
3. Enable Experimental Mode in Settings:
    - Navigate to `https://jan.ai/docs/settings#enable-the-experimental-mode` and follow the instructions to enable Experimental Mode.
4. Download the Latest Version of TinyLlama Chat:
    - Obtain the latest release, `TinyLlama Chat 1.1B Q4`, from the provided source, ensuring compatibility with `RAG` (Retrieval-Augmented Generation).
    - Checkout the documentation for more `https://jan.ai/docs/tools/retrieval#enable-the-knowledge-retrieval`
5. Upload Documents:
    - Upload your PDF documents to the platform to facilitate AI processing.
6. Initiate Q&A:
    - Start the Question & Answer (Q&A) process, utilizing local GPU. Note that processing speed or in other words, `tokens per second` may vary depending on your GPU specifications.

## Project Structure

```
.
├── LICENSE
├── README.md
├── bib
│   └── References.bib
├── datasets
│   ├── diagrams
│   │   ├── ClassDiagram.tex
│   │   ├── SequenceDiagram.tex
│   │   └── SoftwareArchitectureDiagram.tex
│   ├── extras
│   │   ├── graphs
│   │   │   ├── 2d.tex
│   │   │   ├── 3d.tex
│   │   │   └── text.txt
│   │   └── snippets
│   │       ├── python.tex
│   │       └── sql.tex
│   └── images
│       ├── A1.png
│       ├── A2.png
│       ├── A3.png
│       ├── A4.png
│       ├── A5.png
│       ├── GitHubIssues.png
│       ├── JMeter_100reqBenchmark.png
│       ├── Jest-Test-Suite.png
│       ├── hardwareArchitecture-eps-converted-to.pdf
│       ├── hardwareArchitecture.eps
│       ├── pcbDiagram-eps-converted-to.pdf
│       └── pcbDiagram.eps
├── lib
│   ├── Abstract.tex
│   ├── Authors.tex
│   ├── Debugger.tex
│   ├── Preambles.tex
│   └── extras
│       ├── Appendices.tex
│       ├── Biography.tex
│       └── TableOfContents.tex
├── macros
│   ├── BibTeX.tex
│   ├── Bio.tex
│   ├── ColoredBrand.tex
│   ├── Images.tex
│   ├── Itemize.tex
│   ├── Shortcuts.tex
│   ├── Tables.tex
│   └── __init__.tex
├── run.aux
├── run.bbl
├── run.blg
├── run.fdb_latexmk
├── run.fls
├── run.log
├── run.pdf
├── run.synctex.gz
├── run.tex
├── section
│   ├── BackgroundAndRelatedWork.tex
│   ├── ConclusionAndFutureWork.tex
│   ├── Intro.tex
│   ├── ProjectOverview.tex
│   ├── ProjectRequirement.tex
│   ├── SystemDesign.tex
│   ├── TestingAndExperimentation.tex
│   └── __init__.tex
└── styles
    ├── HeadersPageNumbering.tex
    ├── PaperStandard.tex
    ├── Snippet.tex
    ├── __init__.tex
    ├── cite.sty
    └── tikz-uml.sty
```

## Credits

- [LaTeX Page Layout](https://www.overleaf.com/learn/latex/Page_size_and_margins)
- [IEEE Conference Template](https://www.ieee.org/conferences/publishing/templates.html)

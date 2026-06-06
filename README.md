
# Master's Thesis: Policy-as-Code in Kubernetes with Kyverno

This repository contains the documentation and source code for my Master's Thesis (Trabajo Final de Máster - TFM) in Cybersecurity. The project explores the implementation of **Policy-as-Code** within a **Kubernetes** environment, specifically utilizing **Kyverno** and following **GitOps** methodologies with **ArgoCD**.

## Author
**Ziad El Karrabi**
*Master's Student in Cybersecurity*

## Project Overview

The main objective of this thesis is to demonstrate how security and compliance policies can be seamlessly integrated into the deployment lifecycle of Kubernetes clusters. By leveraging Policy-as-Code, organizations can automate the enforcement of security standards, reduce manual errors, and ensure a robust security posture across their infrastructure. 

## Architecture & Technologies

This project heavily focuses on DevSecOps principles and utilizes the following key technologies:

*   **Kubernetes:** The foundational container orchestration platform.
*   **Kyverno:** The core policy engine designed specifically for Kubernetes, used to manage and enforce policies natively.
*   **ArgoCD (GitOps):** Employed for declarative, continuous delivery, ensuring that the cluster state matches the configurations stored in the Git repository.
*   **DevSecOps Automation:** Integrating security practices early and throughout the deployment pipelines.

## Repository Structure

*   `chapters/`: Contains the LaTeX source code for each chapter of the thesis (available in both Spanish and English).
*   `images/`: Stores all the diagrams, ArgoCD dashboards, policy execution screenshots, and architectural figures used in the document.
*   `*.tex`, `*.bib`: Main LaTeX files and bibliography.

## How to Compile the Document

The documentation is written in LaTeX. To compile the final PDF, you will need a LaTeX distribution installed on your system (such as TeX Live or MiKTeX).

You can compile the document using `pdflatex`. For example, to compile the English version:

```bash
pdflatex main_en.tex
makeglossaries main_en
pdflatex main_en.tex
pdflatex main_en.tex
```

For the Spanish version, replace `main_en.tex` with `main.tex`.

## Final Document

You can find the compiled PDF versions of the thesis directly in the root of this repository:

*   [English Version (main_en.pdf)](./main_en.pdf)
*   [Spanish Version (main.pdf)](./main.pdf)

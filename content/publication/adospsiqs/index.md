---
title: "Automated detection of symmetry-protected subspaces in quantum simulations"
authors:
- admin
- Eric B. Jones
- Peter Graf
- Eliot Kapit
date: "2023-02-16T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2302.08586"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: The analysis of symmetry in quantum systems is of utmost theoretical importance, useful in a variety of applications and experimental settings, and is difficult to accomplish in general. Symmetries imply conservation laws, which partition Hilbert space into invariant subspaces of the time-evolution operator, each of which is demarcated according to its conserved quantity. We show that, starting from a chosen basis, any invariant, symmetry-protected subspaces which are diagonal in that basis are discoverable using transitive closure on graphs representing state-to-state transitions under k-local unitary operations. Importantly, the discovery of these subspaces relies neither upon the explicit identification of a symmetry operator or its eigenvalues nor upon the construction of matrices of the full Hilbert space dimension. We introduce two classical algorithms, which efficiently compute and elucidate features of these subspaces. The first algorithm explores the entire symmetry-protected subspace of an initial state in time complexity linear to the size of the subspace by closing local basis state-to-basis state transitions. The second algorithm determines, with bounded error, if a given measurement outcome of a dynamically-generated state is within the symmetry-protected subspace of the state in which the dynamical system is initialized. We demonstrate the applicability of these algorithms by performing post-selection on data generated from emulated noisy quantum simulations of three different dynamical systems, the Heisenberg-XXX model and the T6 and F4 quantum cellular automata. Due to their efficient computability and indifference to identifying the underlying symmetry, these algorithms lend themselves to the post-selection of quantum computer data, optimized classical simulation of quantum systems, and the discovery of previously hidden symmetries in quantum mechanical systems. 

# Summary. An optional shortened abstract.
summary: We show that, starting from a chosen basis, any invariant, symmetry-protected subspaces which are diagonal in that basis are discoverable using transitive closure on graphs representing state-to-state interactions under k-local unitary operations.

tags:
- Quantum Information
featured: false

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/pdf/2302.08586.pdf
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: (https://doi.org/10.48550/arXiv.2302.08586)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

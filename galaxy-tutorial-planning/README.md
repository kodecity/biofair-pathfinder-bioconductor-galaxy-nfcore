## Goal

The end goal is to write a Galaxy Training tutorial to sit alongside the existing [Clustering 3K PBMCs with Seurat](https://training.galaxyproject.org/training-material/topics/single-cell/tutorials/scrna-seurat-pbmc3k/tutorial.html) and [Clustering 3K PBMCs with Scanpy](https://training.galaxyproject.org/training-material/topics/single-cell/tutorials/scrna-scanpy-pbmc3k/tutorial.html) tutorials.

## Plan

In this directory, write a quarto notebook that details the flow of the tutorial, specifically the succesion of R function calls that require equivalent Galaxy tool wrappers.

The notebook should be organised in such a way that one code chunk should be equivalent to one Galaxy tool wrapper.
That way, each code chunk can be associated with either:

- a description of how an existing Galaxy tool wrapper can be used as is
- a description of how an existing Galaxy tool wrapper can be amended
- a description of why a new Galaxy tool wrapper is needed

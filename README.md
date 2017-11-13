# EuroBioc2017-AnnotationFilter

This repository contains material (slides/org-mode presentation) for
`AnnotationFilter` and `ensembldb` related flashlight talk at the European
Bioconductor Developer Meeting 2017 in Cambridge, UK (see
https://github.com/Bioconductor/EuroBioc2017 for details).

The title for the talk is *Filtering annotation resources with AnnotationFilter*
and it is aimed to cover the following topics:
- What is `AnnotationFilter`?
- Example use case on `ensembldb`: filter `EnsDb` using `AnnotationFilter`s.
- New in `ensembldb`:
  - `symbol`/`gene_name` is now a in a separate table (1:n mapping `gene_id` to
    `symbol`.
  - `description` field.
  - *global* filter for `EnsDb` objects.

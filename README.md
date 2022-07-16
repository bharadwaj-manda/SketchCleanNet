<samp>

# SketchCleanNet - A deep learning approach to the enhancement and correction of query sketches for a 3D CAD model retrieval system

</samp>

<div align="center">

<span> <a href="https://www.linkedin.com/in/bharadwaj-manda-9730ab114/">Bharadwaj Manda</a></span>,
<span> <a href="https://www.linkedin.com/in/prasad-kendre-338a9a1a0/">Prasad Kendre</a></span>,
<span> <a href="https://www.linkedin.com/in/subhrajit-dey-7a2784166/">Subhrajit Dey V K</a></span>,
<span> <a href="https://ed.iitm.ac.in/~raman/">Ramanathan Muthuganapathy</a></span>

</div>

This is the repository for the 'SketchCleanNet' Dataset, associated with the paper ["SketchCleanNet - A deep learning approach to the enhancement and correction of query sketches for a 3D CAD model retrieval system"]().

The paper is accepted for publication in the Special Section on [Symposium on 3D Object Retrieval 2022 (3DOR'22)](https://www.micc.unifi.it/3dor2022/) of the [Computers & Graphics](https://www.journals.elsevier.com/computers-and-graphics) Journal. The arxiv version of the paper is available [here](https://arxiv.org/pdf/2207.00732.pdf). The final published version of the paper is [here](https://www.sciencedirect.com/science/article/pii/S0097849322001212).

## LICENSE
This dataset is licensed under CC BY-NC-SA: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International
This license is one of the Creative Commons licenses and allows users to share the dataset only if they (1) give credit to the copyright holder, (2) do not use the dataset for any commercial purposes, and (3) distribute any additions, transformations or changes to the dataset under this same license.

## DATA
* 3D CAD models from [ESB](https://engineering.purdue.edu/cdesign/wp/downloads/) are used for this implementation.
* The training pairs (X, Y) used for this paper is as follows:
    * This paper uses the computer-generated sketches from Dataset_B of the [CADSketchNet dataset](https://github.com/bharadwaj-manda/CADSketchNet) as 'X'.
    * The ground truth 'Y' is obtained manually by tracing the object boundaries of every CAD model. This ground truth sketch data is one on of the contributions of the paper.
    * The ground-truth images can be downloaded [here](https://drive.google.com/file/d/1RrdF8ujwyytMeXf-peCPQaAq25yp9kUO/view?usp=sharing).

For further details, contact Bharadwaj Manda via [here](https://www.linkedin.com/in/bharadwaj-manda-9730ab114/) or [here](https://bharadwaj-manda.netlify.app/)

### To cite this Dataset or Paper:

- Use the bibtex below:

```bibtex
@article{MANDA202273,
title = {SketchCleanNet — A deep learning approach to the enhancement and correction of query sketches for a 3D CAD model retrieval system},
journal = {Computers & Graphics},
volume = {107},
pages = {73-83},
year = {2022},
issn = {0097-8493},
doi = {https://doi.org/10.1016/j.cag.2022.07.006},
url = {https://www.sciencedirect.com/science/article/pii/S0097849322001212},
author = {Bharadwaj Manda and Prasad Pralhad Kendre and Subhrajit Dey and Ramanathan Muthuganapathy}
}
```

- Or use the plain text below

Manda, Bharadwaj, Prasad Pralhad Kendre, Subhrajit Dey, and Ramanathan Muthuganapathy. "SketchCleanNet-A deep learning approach to the enhancement and correction of query sketches for a 3D CAD model retrieval system." Computers & Graphics (2022).

<ins>Files in this repository:</ins>

**SketchCleanNet_Data.zip** - The ground-truth images obtained manually by tracing the object boundaries of every CAD model in ESB.

*Thanks are due to the many volunteers who have contributed to the dataset.*

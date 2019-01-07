+++
title = "Quantifying the performance of MEG source reconstruction using resting state data"
date = 2018-01-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["SJ Little, JJ Bonaiuto, SS Meyer, J Lopez, S Bestmann, GR Barnes"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *NeuroImage*"
publication_short = "NeuroImage*"

# Abstract and optional shortened version.
abstract = "In magnetoencephalography (MEG) research there are a variety of inversion methods to transform sensor data into estimates of brain activity. Each new inversion scheme is generally justified against a specific simulated or task scenario. The choice of this scenario will however have a large impact on how well the scheme performs. We describe a method with minimal selection bias to quantify algorithm performance using human resting state data. These recordings provide a generic, heterogeneous, and plentiful functional substrate against which to test different MEG recording and reconstruction approaches. We used a Hidden Markov model to spatio-temporally partition data into self-similar dynamic states. To test the anatomical precision that could be achieved, we then inverted these data onto libraries of systematically distorted subject-specific cortical meshes and compared the quality of the fit using cross validation and a Free energy metric. This revealed which inversion scheme was able to identify the least distorted (most accurate) anatomical models, and allowed us to quantify an upper bound on the mean anatomical distortion accordingly. We used two resting state datasets, one recorded with head-casts and one without. In the head-cast data, the Empirical Bayesian Beamformer (EBB) algorithm showed the best mean anatomical discrimination (3.7 mm) compared with Minimum Norm/LORETA (6.0 mm) and Multiple Sparse Priors (9.4 mm). This pattern was replicated in the second (conventional dataset) although with a marginally poorer (non-significant) prediction of the missing (cross-validated) data. Our findings suggest that the abundant resting state data now commonly available could be used to refine and validate MEG source reconstruction methods and/or recording paradigms."
abstract_short = "In magnetoencephalography (MEG) research there are a variety of inversion methods to transform sensor data into estimates of brain activity. Each new inversion scheme is generally justified against a specific simulated or task scenario. The choice of this scenario will however have a large impact on how well the scheme performs. We describe a method with minimal selection bias to quantify algorithm performance using human resting state data. These recordings provide a generic, heterogeneous, and plentiful functional substrate against which to test different MEG recording and reconstruction approaches. We used a Hidden Markov model to spatio-temporally partition data into self-similar dynamic states. To test the anatomical precision that could be achieved, we then inverted these data onto libraries of systematically distorted subject-specific cortical meshes and compared the quality of the fit using cross validation and a Free energy metric. This revealed which inversion scheme was able to identify the least distorted (most accurate) anatomical models, and allowed us to quantify an upper bound on the mean anatomical distortion accordingly. We used two resting state datasets, one recorded with head-casts and one without. In the head-cast data, the Empirical Bayesian Beamformer (EBB) algorithm showed the best mean anatomical discrimination (3.7 mm) compared with Minimum Norm/LORETA (6.0 mm) and Multiple Sparse Priors (9.4 mm). This pattern was replicated in the second (conventional dataset) although with a marginally poorer (non-significant) prediction of the missing (cross-validated) data. Our findings suggest that the abundant resting state data now commonly available could be used to refine and validate MEG source reconstruction methods and/or recording paradigms."

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["laminar-meg"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["MEG", "head-cast", "resting state", "source inversion"]

# Links (optional).
url_pdf = "../../../files/1-s2.0-S1053811918306451-main.pdf"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "https://doi.org/10.1016/j.neuroimage.2018.07.030"

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.

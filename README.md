# CCF Registration Competition

In collaboration with the [BRAIN Inititative Cell Census Network](biccn.org) (BICCN), 
the [Brain Imaging Library](https://www.brainimagelibrary.org/) (BIL), 
the [Penn Image Computing and Science Lab](http://picsl.upenn.edu/) (PICSL), 
we are running the first [Allen Institute for Brain Science](https://portal.brain-map.org/) 
CCF registration competition! 


A brief description of the competition motivation, format, and next steps is below
Motivation

The [Allen Mouse Common Coordinate Framework](https://community.brain-map.org/t/allen-mouse-ccf-accessing-and-using-related-data-and-tools/359) (CCF) defines anatomical locations within an annotated population averaged mouse brain. This resource is already valuable to the field, providing a 3D reference framework for the mouse brain. Enhanced impact is possible if new 3D datasets can be routinely aligned into the CCF space. This enables comparison of results across experiments with a common and objective reference for mouse brain anatomy. Large-scale resources can be built systematically by leveraging automated alignment into a common spatial framework.

Achieving this vision requires robust alignment of new image data into the CCF space, regardless of acquisition modality. The field has produced many options for this task, but unbiased comparison of these techniques does not exist. To benchmark various approaches, and to encourage researchers to share available resources, we propose the Allen Institute for Brain Science organize a competition between CCF alignment tools sourced from the global neuroscience and image processing community.

## Competition Format

### About the data

The Allen Institute for Brain Science will provide the following image datasets:

* Optical projection tomography datasets from the Neuropixels pipeline

(To-do: add details - Josh)

* fMOST datasets from the whole-brain morphology project

(To-do: add details - Julie)

The datasets can be access through BIL:

(To-do: BIL to setup site in BIL )
(To-do: Rusty to upload data)
(To-do: instruction on how to download - BIL)

The data is in the following format:

(To-do: PICSL team to define format and convert the data)


### How will the competition be run?

For each  dataset, a set of landmarks covering the whole extent of the brain will be indentified by expert anatomists. Type of landmarks include:
* Pairs of corresponding points between the image dataset and the CCF
* Points that are within in specific structures in the CCF
* Points that are on the surface between two structures in the CCF

(To-do: Penn team to define the landmark format)
(To-do: Lydia/Julie to figure out fMOST data)
(To-do: Rusty/Josh to format the OPT data)

Example landmarks will be provided to participants as reference. The rest are withheld and used for scoring the registration quality.

To submit a result, a participant will
- start a pull request
- create a new submission page using the template
- provide information about their team and methods
- provide links to the registration code (source code or product page)
- For each imageset:
    - Scripts and parameters that was used to produce
    - Upload the deformation field that maps a image point to the CCF in the format described below
    - Add location of the deformation field
- Submit pull request

Once we received the pull request, we will compute registration score and post in on the scoreboard.

### Deformation field format

(To-do: Penn team to define the deformation field format)

### Registration scoring

(To-do: Penn team to code registration scoring method )
(To-do: Penn / BIL team to setup how to run the scoring at BIL) 
(To-do: Rusty to update the score board)

Competition start is tentatively scheduled for summer 2020. We will release details regarding datasets, scoring, and entrance details as they become available.

## Save the date!

We will have a workshop at the [Neuroinformatics 2020 Congress in Seattle](https://neuroinformatics.incf.org/) in Aug 17-18, 2020 

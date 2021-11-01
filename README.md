# pythia-tutorials

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ProjectPythia/pythia-tutorials/HEAD)

A single repository to host community-contributed Pythia tutorial content (notebooks, data, and markdown).

The goal of this repository is to create a common location and environment for Pythia Python tutorials. For the Python learner, this has the benefits of consistent installation / spin up before jumping in to each lesson. For the Pythia team, this ownership allows us to maintain content long-term so that we can fix things when they break.

We, the Pythia team, want there to be a low barrier to entry for the tutorial speaker to develop and host their tutorial content in this repository. For the speaker's convenience we will provide a simple template. This repository differs from `pythia-foundations` book, which has a high barrier for entry, with its strict and consistent style guide and rigorous review process before merging. Further, the tutorial notebooks in this repository are designed to be accompanied by a live speaker or recording. This means that the amount of explanatory text between code cells or excercises may differ between tutorials based on the tutorial speaker and developer's preferred style.

All tutorials are designed to be hosted on `BinderHub` where appropriate.

## Organization
The document tree of this repository takes the following format:

```
  pythia-tutorials/
   |-  data/
   |    |- `some_data.txt`
   |    |- `README.md`
   |-  tutorials/
   |    |- template/
   |    |    |-  `template.ipynb`
   |    |    |- `template.md`
   |    |- TOPIC_YYYY_MM_DD/
   |    |    |-  `topic.ipynb`
   |    |    |-  `README.md`
   |    |- ANOTHER_TOPIC_YYYY_MM_DD/
   |    |    |-  `topic.ipynb`
   |    |    |-  `README.md`
   |-  `environment.yaml`
   |-  `README.md`
```

Some things to notice:
- There is a single `data` directory across all tutorials. This is designed to encourage re-use of datasets.
- Within the `tutorials` direcotry there is a unique directory for every tutorial and a `template` directory, containing a markdown and a notebook template (coming soon). 
- Each tutorial is named with its topic and date with the format `TOPIC_YYYY_MM_DD`. 
- If a new tutorial on the same topic is contributed, a new directory with the new date is added (i.e. the pre-existing directory is not edited). 
- Multi-session tutorials may have a unique directory for each session, preserving the state of the tutorial during each lesson (for example, `matplotlib_part1_YYYY_MM_DD` and `matplotlib_part2_YYYY_MM_DD`)
- Each tutorial directory contains the tutorial notebooks and a corresponding `README.md` file. This `README.md` file should contain all pertinent information that will not be part of the tutorial presentation: preparation steps, past videos to watch beforehand, and the embedded recording from the tutorial (ala the ESDS blog posts).
- There is a single environment file for all tutorials. This environment will be version controlled with unique versions of this repository (and its environment) published corresponding to each new live tutorial to preserve the state of the repository during each recording.

## Contribution

To add your tutorial directory please:
  1. Review the tutorial template (coming soon).
  2. Upload your notebook(s) and corresponding markdown file to a unique directory with the naming convention `TOPIC_YYYY_MM_DD`.
  3. Edit the content table (coming soon) to include your content.

If you would like to host a tutorial through the Project Pythia Tutorial Seminar Series, please reach out to us here on GitHub or by emailing `projectpythia@ucar.edu`. Contributors Guide coming soon.

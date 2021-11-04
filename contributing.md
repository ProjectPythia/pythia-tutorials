# Contributor's Guide

First of all, thank you for hosting a tutorial through the Project Pythia Python Tutorial Seminar Series. Project Pythia appreciates your support, your work, and commitment to community.


To add your tutorial directory please follow these steps:

### 1. Review the tutorial template (coming soon).
The tutorial template is designed to give you a brief overview of what is expected of a Project Pythia Tutorial seminar. We hope you find the template a useful reminder of good presentation ideas and bookendsl. It is not designed to be restrictive or time-consuming if you choose to adapt your material to it.

### 2. Upload your notebook(s) to a unique directory.
Within the `tutorials/` directory please create a new folder for your tutorial with the naming convention `TOPIC_YYY_MM_DD` (e.g. `pandas_2021_11_24`). If you have multiple tutorials in a series that build off of each other, please create **multiple folders** at the `tutorials/` sub-level that represent the state of the series at each lesson (e.g. `pandas_part1_2021_11_24` and `pandas_part2_2021_12_08`). Add any relevant `.ipynb` files here. 

Because we understand that you may be editing your notebook right up until your tutorial, the contribution "barrier for entry" in this repository is lower than elsewhere in the Pythia ecosystem. And since you will only be editing files in your new directory, feel free to push directly without waiting for a review.

### 3. Create a `README.md` file associated with your tutorial directory.
Every tutorial directory is intended to be accompanied by a `README.md` markdown file. The contents of this file are similar to what should go out with an announcement of your seminar: title, speaker name, a brief speaker bio, live time and date, and any past tutorials that this new seminar is a continuation of. After the session a member of the Pythia team will embed the Youtube recording into this same file. Please see the `template.md` file for assistance (coming soon).

You may also merge this new markdown content without waiting for an approval on your pull request.

### 4. Check the repository-wide `environment.yaml` file.
Every tutorial in this repository will have the same environment. This makes it easier to have Binder enabled across all tutorials and makes the installation more consistent for attendees. Please check the `environment.yaml` file to make sure all of your necessary dependencies are listed.

If you need to add a package or dependency to the environment please create a PR and ping a Project Pythia member for a quick review. In the event that new dependencies cause old tutorials to break, the Project Pythia team will address how to best bring the old tutorial up to speed, or archive it. Having the environment ready for your ipending tutorial is a priority.

### 5. Edit the table of contents (coming soon).
We hope to have a table of contents that lists all of the tutorials available in this repository. Do not worry about this step until we have created this.


If you would like to host a tutorial through the Project Pythia Tutorial Seminar Series, please reach out to us here on GitHub or by emailing `projectpythia@ucar.edu`. Contributors Guide coming soon.

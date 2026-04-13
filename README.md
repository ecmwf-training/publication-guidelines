# Guidelines for development, publication and maintenance of ECMWF Jupyter resources for external training
## ECMWF Github organisation for training (hosting environment)
Jupyter notebooks and Jupyterbooks intended as ECMWF learning resources for external audiences are hosted in the ECMWF GitHub organisation for training https://github.com/ecmwf-training.
This organisation contains repositories for publically available Jupyter resources, in addition to templates, guildelines and other supporting files to assist with the creation, publication and maintenance of Jupyter notebooks and Jupyterbooks.

### Naming convention of repositories

Repository names are all lowercase, with hyphens as separators.

#### Repositories for training events
Repositories containing publically available Jupyter resources for individual training events have the following naming convention: year of training (yyyy), hyphen (-), description of training (brief, all lowercase).

For example: [2026-ml-destine-training](https://github.com/ecmwf-training/2026-ml-destine-training)

**It should be made clear in the README of the repo what the level of maintenance is for notebooks used in a particular training event.** It may be that when a training event comes to an end, the notebooks used in the training are no longer maintained.

#### Repositories and submodule repositories for Jupyterbooks 

Jupyterbooks that contain a main repo and various submodule repos should have consistent naming to make it clear how they are linked. Submodule repo should have the same name as main repos with the suffix "-submodule-" followed by a brief description of the submodule repo.

For example:
- [c3s-training](https://github.com/ecmwf-training/c3s-training) (main Jupyterbook repo)
- [c3s-training-submodule-reanalysis](https://github.com/ecmwf-training/c3s-training-submodule-seasonal-forecast) (submodule of Jupyterbook repo)

## Accessibility of Jupyter resources

While the GitHub organisation https://github.com/ecmwf-training is the hosting environment, to make Jupyter resources FAIR, the expectation is that users can search and find notebooks in other platforms.

**A catalogue of all publically available ECMWF notebooks and Jupyterbooks for training is available on ECMWF's learning catalogue: https://www.ecmwf.int/en/learning/training/search**

Any ECMWF Jupyter based learning resource intended for unrestricted public use shall be made available through the ECMWF learning catalogue. Please see guidelines below on how to do this.

In addition to the ECMWF learning catalogue, some notebooks may be available through other channels, such as Jupyterbooks linked in various landing pages.

For example, C3S notebooks hosted on the ECMWF training GitHub are available through a Jupyterbook https://ecmwf-training.github.io/c3s-training/, which is also linked on the C3S training landing page https://climate.copernicus.eu/user-learning-services.

## Guidelines for Jupyter notebook authoring
Templates and guidelines for authoring Jupyter notebooks and Jupyterbooks are available here https://github.com/ecmwf-training/jupyterbook-template.

## Quality control
ECMWF Jupyter notebooks and Jupyterbooks for external training undergo quality control. See guidelines for quality control here https://github.com/ecmwf-training/jupyterbook-template

## Process for creation and publication of ECMWF Jupyter resources (notebooks and Jupyterbooks)
1. Please follow one of the steps below to begin the process:
  * For ECWMF staff, please contact training@ecmwf.int to begin the process of accepting new content.
  * If you are working on a contract for ECMWF, contributions should be arranged via the Technical Officer assigned to your contract.
  * Public contributions can only be accepted as pull requests to existing repositories found here
1. Decide whether contributions go into existing repository or a new repository is created by ECMWF training admin.
1. Follow templates for Jupyter notebook and Jupyterbook creation and quality control (if applicable) https://github.com/ecmwf-training/jupyterbook-template
1. When notebook or Jupyterbook has passed quality control and is ready for publication, raise a pull request.
1. Notebook undergoes internal review and contributors are expected to repond to any editorial requests.

## Maintenance of ECMWF Jupyter resources
Internal staff responsible for ECMWF Jupyter notebooks and Jupyterbooks for external training are also responsible for maintenance. If there is no commitment to maintenance (e.g. following completion of training event), this must be made clear in the README of the hosting repository. Jupyter resources on the publically available ECMWF learning catalogue must be maintained, or a date specified by which time they are removed.

# Based on: https://jupyter-docker-stacks.readthedocs.io/en/latest/using/recipes.html#using-mamba-install-or-pip-install-in-a-child-docker-image
#
# Start from a core stack version
FROM jupyter/minimal-notebook:2023-03-09

# Volumes aren't in place yet 
COPY --chown=${NB_UID}:${NB_GID} environment/ .

# Install Python packages from requirements.txt file
RUN pip install --quiet --no-cache-dir --requirement ./requirements.txt && \
  fix-permissions "${CONDA_DIR}" && \
  fix-permissions "/home/${NB_USER}"
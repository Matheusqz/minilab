[![Datalayer](https://raw.githubusercontent.com/datalayer/datalayer/main/res/logo/datalayer-25.svg?sanitize=true)](https://datalayer.io)

# Minilab

> 🎹 `Minilab`, foundations to build a modern and flexible notebook UI.

It gathers the minimum set of [Lumino](https://github.com/jupyterlab/jupyterlab) and [JupyterLab](https://github.com/jupyterlab/jupyterlab) technologies:

- Lumino Signals.
- Lumino Settings
- Lumino Commands.
- Extension machinery.
- Extension machinery.
- JupyterLab Services to connect with remote Kernels.
- JupyterLab App and App-Utils.

It explictely does not ship the Lumino Layouts not the Lumino Panels. So you would come on top with e.g. `lab-react`, `lab-vue`...

We also intend to deliver cross UI communication: e.g. `lab-react` could communicate to `lab-vue` via the `minilab` hub.

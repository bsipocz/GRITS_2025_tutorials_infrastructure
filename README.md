# Notebook rendeding and testing: 1-pager for references about the JupyterBook ecosystem

This is a very brief summary of the tools that I mention during my talk.

## MyST Markdown flavoured notebooks.

You will need `jupytext` as a dependency to make them work in Jupyter Lab; and `jupyterlab-myst` extension is also advised.
Both of them are easy to install Python dependencies.

## MySTmd and Jupyter Book (JB):

new version is MySTmd/TypeScript based; beta 2.0 came out relatively recently, and more features to come:
    https://mystmd.org/
    https://next.jupyterbook.org/

Paper that describes JB2 and the MySTmd stack, accepted. [Preview version](https://proceedings.scipy.org/previews/0198ec1e-d9f1-7423-a9e0-b4ede50f41d4?preview=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJodHRwczovL2pvdXJuYWxzLmN1cnZlbm90ZS5jb20iLCJleHAiOjE3NTkzMDIyNzUsImF1ZCI6InNjaXB5Iiwic2NvcGUiOiJzdWJtaXNzaW9uIiwic2NvcGVJZCI6IjAxOThlYzFlLWQ5ZjEtNzQyMy1hOWUwLWI0ZWU2ZDNjMTg0MCIsImlhdCI6MTc1ODg3MDI3NX0.QIt551WPQWMcqYTtDj4gpYhEVEj2XHi4J1-OUn8znmo)


## Example repos

Slides I showed:

- https://docs.google.com/presentation/d/1X5STnq-2Pm07p68-fPTIhrDu-j5rYG-ihlDIg7F0c20/edit?usp=sharing

Example repos that have testing and website rendering set up:

- IRSA Tutorials: 
  - https://github.com/Caltech-IPAC/irsa-tutorials/
  - https://caltech-ipac.github.io/irsa-tutorials/
         
- Numpy Tutorials: https://github.com/numpy/numpy-tutorials

And docs only repos, using the same JB infrastructure, in my opinion this is a very easy way to maintain websites:

- SPHEREx archive documentation: 
  - https://github.com/Caltech-IPAC/spherex-archive-documentation
  - https://caltech-ipac.github.io/spherex-archive-documentation/
       
- Fornax Documentation:
  - https://docs.fornax.sciencecloud.nasa.gov/

### Executable-tutorials

Within the Scientific Python Project we are working on a template repository that will make it easier to share and update the infratructure for a tutorial project. Currently we have a sandbox that contains multiple approaches, we likely keep this namespace for the template, too. It's note ready yet for prime time, but we're actively working on it and you may already find useful bits and pieces: 
 - https://github.com/scientific-python/executable-tutorials
 - https://scientific-python.github.io/executable-tutorials/

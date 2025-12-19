FROM jupyter/datascience-notebook

RUN julia -e 'using Pkg; Pkg.add("PackageCompiler")'
RUN julia -e 'using Pkg; Pkg.add(["Plots", "DataFrames", "CSV"])'
RUN julia -e 'using Pkg; Pkg.add(["Test", "StatsPlots", "Statistics"])'
RUN julia -e 'using Pkg; Pkg.add(["LaTeXStrings"])'
RUN julia -e 'using Pkg; Pkg.add(["FreqTables", "NamedArrays", "Distributions"])'
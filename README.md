# Copy-all-graphs-from-R
The codes will enable to copy all image files generated in the R plots to your folder

plots.R.path <- list.files(tempdir(), pattern="rs-graphics", full.names = TRUE);
myplots.path <- list.files(plots.dir.path, pattern=".png", full.names = TRUE)

file.copy(from=plots.R.path, to="myplots.path")

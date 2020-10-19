source("renv/activate.R")
filepath = paste0("/home/jovyan/", list.files(pattern = ".Rproj")[1]);
writeLines(filepath, ".rstudio/projects_settings/last-project-path")
rm(filepath)

if(!file.exists(".gitconfig")) {
  writeLines(c("[user]", "  email = you@example.com", "  name = Your Name"), ".gitconfig"
  )
}

options(rstudio.markdownToHTML = 
            function(inputFile, outputFile) {      
                system(paste("pandoc --biblio hc_whales.bib",
                             "-c styles/github.css",
                             "--mathjax",
                             shQuote(inputFile), 
                             "-o", 
                             shQuote(outputFile)))
            }
) 
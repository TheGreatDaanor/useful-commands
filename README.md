
###
reverses lines in files and cuts from the first / reverses back and saves to file.
cat httprobe_subdomain.txt | rev |  cut -d '/' -f 1 | rev >> probe_subdomain.txt

###
reverses lines in files and cuts from the first / reverses back.
cat responsive.txt | rev | cut -d '/' -f 1 | rev | 

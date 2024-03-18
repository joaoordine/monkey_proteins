# monkey_proteins
Coding with all analyses performed in a project that aimed to study monkey proteins in a large number of genomes. 

Firstly, I downloaded all required genomes (listed on file genomes_download_links.csv) using their curl links. To see the full script, go to
## Script 01.Downloading_ENA_genomes

Before blasting selected proteins against the genomes, I corrected their sequence format, since bases from the sequences were split into several lines and this can cause a lot of trouble later on if unnoticed. I just copied them in the Firefox search bar to correct this, and them copied the sequences along with their headers to files I created using vim. This and the processing I performed on the downloaded genomes can be seen in
## Script 02.Processing_protANDgenomes


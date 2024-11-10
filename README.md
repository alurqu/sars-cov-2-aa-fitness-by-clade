# sars-cov-2-aa-fitness-by-clade
SARS-COV-2 Amino Acid Residue Fitness by Nextstrain Clade

Bloom and Neher estimates of SARS-CoV-2 amino acid residue mutation fitness
by clade https://github.com/jbloomlab/SARS2-mut-fitness/blob/main/results/aa_fitness/aamut_fitness_by_clade.csv
separated into files by clade, with a minimum delta_fitness, and eliminating aa mutations that match the clade founder aa.

For cases in which the Bloom and Neher estimates dropped results for a clade, such as with the 8 November 2024 update that dropped Clade 23I (BA.2.86) while adding Clade 24A (JN.1), old results from the old clade may still be available here.

These files have been sorted by descending delta_fitness, and mutation records with delta_fitness less than 1.0 have been filtered out. This places mutations that increase virus fitness the most closer to the top of the file while filtering out mutations that decrease viral fitness or that have little impact. In short, mutations closer to the top of the file are more likely to appear and transmission of SARS-CoV-2 cases.

This is a direct derivative of the Bloom and Neher results from https://github.com/jbloomlab/SARS2-mut-fitness.

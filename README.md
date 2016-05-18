# SeqFetch
Fetch sequences from database

If you are looking to download batch of sequences from public database such as Genbank using the accession number, the following perl script that I’ve written may be quite handy.

This script uses a BioPerl module “Bio::DB::GenBank“ (http://search.cpan.org/dist/BioPerl/Bio/DB/GenBank.pm). All the accession number must be present within the file accnumber.txt each separated my a comma. And also, file accnumber.txt must be present within the same directory as that of the perl-script. After successful execution it will generate a file sequence_dwnl.fa containing the sequence in fasta format.

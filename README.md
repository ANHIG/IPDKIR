--------------------------------------------------------------------------------
 IPD-IKIR Database
--------------------------------------------------------------------------------

This directory contains data for the IPD-KIR Sequence Database. The database provides a centralised repository for human KIR sequences. Killer-cell Immunoglobulin-like Receptors (KIR) have been shown to be highly polymorphic at the allelic and haplotypic level. KIRs are members of the immunoglobulin superfamily (IgSF) formerly called Killer-cell Inhibitory Receptors. They are composed of two or three Ig-domains, a transmembrane region and cytoplasmic tail which can in turn be short (activatory) or long (inhibitory). The Leukocyte Receptor Complex (LRC) which encodes KIR genes has been shown to be polymorphic, polygenic and complex like the MHC.The database was publically released in February 2003.

Updated: 28 June 2003,      Release 1.0.0
Updated: 24 January 2005,   Release 1.1.0
Updated: 11 October 2005,   Release 1.1.1
Updated: 10 March 2006,     Release 1.2.0
Updated: 23 March 2006,     Release 1.2.1
Updated: 10 November 2006,  Release 1.3.0
Updated: 04 June 2007,      Release 1.4.0
Updated: 18 January 2008,   Release 2.0.0
Updated: 17 September 2008, Release 2.0.1
Updated: 20 February 2009,  Release 2.1.0
Updated: 25 May 2010,       Release 2.2.0
Updated: 16 August 2010,    Release 2.3.0
Updated: 15 April 2011,     Release 2.4.0

Files are currently provided for the nucleotide and protein sequences in FASTA or PIR format.

For information on the IPD-KIR Sequence Database please see the website at: http://www.ebi.ac.uk/ipd/kir/

For any other information please contact ipd@ebi.ac.uk.


--------------------------------------------------------------------------------
File Formats 
--------------------------------------------------------------------------------

The directory also contains the KIR sequences in a number of formats. Within the following folders, the various format types are explained briefly here:

### FASTA folder

All files in this folder are provided in the FASTA sequence format. Please note the FASTA format contains no alignment information.

Files designated “X_prot.fasta”, where X is a locus or gene, contain protein sequences. Please note that alleles that contain non-coding variations may be identical at the protein level. 

Files designated “X_nuc.fasta”, where X is a locus or gene, contain the nucleotide coding sequences (CDS). Please note that alleles that contain non-coding variations may be identical at the CDS level.

Files designated “X_gen.fasta”, where X is a locus or gene, contain genomic DNA sequences. Please note for alleles that do not possess genomic sequences, there will be no entry in the file.

### MSF Folder

All files in this folder are provided in the MSF sequence format. 

Files designated “X_prot.msf”, where X is a locus or gene, contain protein sequences. Please note that alleles that contain non-coding variations may be identical at the protein level. 

Files designated “X_nuc.msf”, where X is a locus or gene, contain the nucleotide coding sequences (CDS). Please note that alleles that contain non-coding variations may be identical at the CDS level.

Files designated “X_gen.msf”, where X is a locus or gene, contain genomic DNA sequences. Please note for alleles that do not possess genomic sequences, there will be no entry in the file.

### PIR 

All files in this folder are provided in the PIR sequence format. 

Files designated “X_prot.pir”, where X is a locus or gene, contain protein sequences. Please note that alleles that contain non-coding variations may be identical at the protein level. 

Files designated “X_nuc.pir”, where X is a locus or gene, contain the nucleotide coding sequences (CDS). Please note that alleles that contain non-coding variations may be identical at the CDS level.

Files designated “X_gen.pir”, where X is a locus or gene, contain genomic DNA sequences. Please note for alleles that do not possess genomic sequences, there will be no entry in the file.

### Other Files

The top-level directory contains the following lists; 

* Allelelist.txt and Allelelist.XXXX.txt - a csv file listed all alleles named at the time of the release, the XXXX in the file denotes a particular release. Allelelist.txt is a copy of the latest version.
* Deleted_alleles.txt - a csv file detailing all deleted allele names, with reasons for the deletion. This list also includes details of any suffix changes. 
* LICENSE.md - a file detailing the licensing of data included in the IPD-KIR Database.
* README.md - This README file
* kir.dat - An EMBL-ENA style format file containing data from the IPD-KIR Database, see http://www.ebi.ac.uk/ipd/imgt/hla/docs/manual.html for further details.
* kir_gen.fasta - a copy of the file in the fasta directory, includes the DNA sequence for all alleles, which have genomic sequences available. 
* kir_nuc.fasta - a copy of the file in the fasta directory, includes the DNA sequence for the CDS sequence of all alleles. 
* kir_prot.fasta - a copy of the file in the fasta directory, includes the amino acid sequence for all alleles. 
* md5checksum.txt - a file detailing md5 checksums for all files in the top-levle directory

--------------------------------------------------------------------------------
 CONTACTS
--------------------------------------------------------------------------------

For information on the IPD-KIR Database please see the website at:
http://www.ebi.ac.uk/ipd/kir

Additional information on sequence file formats is available from:
http://www.ebi.ac.uk/ipd/kir/download.html

For any other information please contact hla@alleles.org.

--------------------------------------------------------------------------------
 COPYRIGHT NOTICE
--------------------------------------------------------------------------------

We have chosen to apply the Creative Commons Attribution-NoDerivs License to all
copyrightable parts of our databases, which includes the sequence alignments.
This means that you are free to copy, distribute, display and make commercial
use of the databases in all legislations, provided you give us credit by citing
the following;

Robinson J, Halliwell JA, Hayhurst JH, Flicek P, Parham P, Marsh SGE:
The IPD and IPD-IMGT/HLA Database: allele variant databases
Nucleic Acids Research (2015), 43:D423-431

Robinson J, Malik A, Parham P, Bodmer JG, Marsh SGE:
IMGT/HLA - a sequence database for the human major histocompatibility complex
Tissue Antigens (2000), 55:280-287

We are strongly opposed to the mirroring of the data contained on our sites, both
hla.alleles.org and the IPD-IMGT/HLA Database, and would ask that rather than mirror
the information, appropriate links are provided where applicable.

If you intend to distribute a modified version of our data, you must ask us for
permission first, please contact hla [at] alleles [dot] org for further details
of how modified data can be reproduced.

--------------------------------------------------------------------------------
 FUNDING
--------------------------------------------------------------------------------

The development of the IPD-IMGT/HLA Database was funded by an EU BIOTECH grant. The
work of maintaining and updating the database has been supported in the past by
the Imperial Cancer Research Fund, the National Institute of Health, the
National Marrow Donor Program (NMDP) and more recently by the Anthony Nolan
Trust. The continual maintenace and any further development of the database
relies on alternate sources of financial support, which are actively been sought
for the continued maintenance of the database. The Sequence.org initiative at
the NMDP has solicited funds from institutions and companies who produce HLA
typing reagents, typing systems, and instrumentation or that otherwise utilise
these databases in critical components of their business. To learn more about
how your business can support the IPD-IMGT/HLA Database, please contact: Todd Peterson
(Email: Todd [dot] Peterson [at] nmdp [dot] org).

If you intend to use any of the data found on our sites for commercial use, we
would ask you to consider funding the database and the work we do. Without
continued funding the database cannot be maintained.

--------------------------------------------------------------------------------
 DISCLAIMER
--------------------------------------------------------------------------------

Where discrepancies have arisen between reported sequences and those stored in
the database, the original authors have been contacted where possible, and
necessary amendments to published sequences have been incorporated. Future
sequencing may identify errors and the WHO Nomenclature Committee would welcome
any evidence that helps to maintain the accuracy of the database. We therefore
make no warranties regarding the correctness of the data, and disclaim liability
for damages resulting from its use. We cannot provide unrestricted permission
regarding the use of the data, as some data may be covered by patents or other
rights. Any medical or genetic information is provided for research, educational
and informational purposes only. It is not in any way intended to be used as a
substitute for professional medical advice, diagnosis, treatment or care.

We reserve the right to use information about visitors (IP addresses), date/time
visited, page visited, referring website, etc. for site usage statistics and to
improve our services.
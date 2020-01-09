
# cegx\_bsexpress\_docker #

## Introduction ##
CEGX has developed a custom post-processing script, bsExpress, that
interfaces with Bismark to output a set of summary documents and QC
reports based on the conversion performance of the sequencing spike-in
controls. bsExpress is a program to perform quality control analysis of
bisulfite (BS-Seq) and oxidised bisulfite (oxBS-Seq) sequencing
libraries. bsExpress is designed to perform quality control bisulfite
(BS-Seq) and oxidised bisulfite (oxBS-Seq) libraries using ad hoc
control sequences where cytosine modification are known.

Previous versions of bsExpress were problematic to install due to the
long list of prerequisite programs that also needed to be installed. To
simplify the installation and running there is now a dockerised version.
Docker wraps up bsExpress and all of its required programs and
configurations into a single package.

The instructions below assume you are using a Mac or Linux (Windows
instructions to be added)

If you aren't familiar with the command line, how to change directories
and list the files within a directory then this simple guide may help:
[*Linux Guide*](http://linuxcommand.org/lc3_lts0020.php)


## Download cegx\_bsexpress\_docker ##

If you are familiar with git, use:

    cd /User/joebloggs/Desktop 
    git clone https://bitbucket.org/cegx-bfx/cegx_bsexpress_docker.git

Otherwise you can download the individual files from:
[BitBucket Source Code](https://bitbucket.org/cegx-bfx/cegx_bsexpress_docker/src)

    cegx_bsexpress_0.5_Instructions.pdf
    cegx_bsexpress_0.5.tar.gz
    local_auto_bsExpress

*Note: Don't double click the file when it appears in the bottom bar of
your browser. This will uncompress it into an incorrect format.*

Or as a package from:
[BitBucket Downloads](https://bitbucket.org/cegx-bfx/cegx_bsexpress_docker/downloads)

## Installation & Running ##

Please refer to the `cegx_bsexpress_0.5_Instructions.pdf` document for full instructions for installing and running cegx\_bsexpress\_docker.

## Getting help ##

Please contact [informatics@cegx.co.uk](mailto:informatics@cegx.co.uk) if you reguire assistance or have any questions

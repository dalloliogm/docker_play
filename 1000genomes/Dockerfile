FROM ubuntu:utopic
MAINTAINER Giovanni DallOlio <dalloliogm@gmail.com>

RUN apt-get install -y wget git tabix

tabix ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/release/20130502/ALL.chr22.phase3_shapeit2_mvncall_integrated_v5a.20130502.genotypes.vcf.gz 22:23862589-25055718 > myregion.vcf


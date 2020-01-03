## working

### mike meetings
* https://github.research.chop.edu/evansj/mike-meetings

### my cookie cutter
* https://github.com/samesense/project-cookiecutter

### ibd array
* https://github.research.chop.edu/evansj/ibd-gwas

### reference
* https://github.research.chop.edu/RIS/reference_data
* [quilt](https://quiltdata.com)
* https://github.com/gogetdata/ggd-recipes

### crawlers
* https://github.research.chop.edu/evansj/crawler-meetings
* https://docs.google.com/document/d/11Ha0kXUhHRSHmKbA7YpJf5HeVK8SWrSJF7xCA3z5z_U/edit

### dbgap
* https://github.research.chop.edu/evansj/extract-phs001076
* [prefetch by file](https://www.biostars.org/p/111040/)
* https://trace.ncbi.nlm.nih.gov/Traces/sra/?run=SRR3879592
* https://trace.ncbi.nlm.nih.gov/Traces/study/?dbgap_project=19401&o=study_accession_s%3Aa%3Bacc_s%3Aa&s=SRR3600975
* https://dbgap.ncbi.nlm.nih.gov/aa/wga.cgi?page=list_wishlists

### pipeline
* https://github.research.chop.edu/evansj/sm-gcp-wgs
* [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules); [change submodule branch](https://stackoverflow.com/questions/1777854/how-can-i-specify-a-branch-tag-when-adding-a-git-submodule)
* [test k8s+sm on vm](https://github.research.chop.edu/evansj/test-k8s)
* [test sm and cromwell on respublica](https://github.com/samesense/test-gcp)
* [my cromwell changes](https://github.research.chop.edu/evansj/cromwell/blob/2ce665ba06abbff65d9385dba6db6882e910713f/supportedBackends/google/pipelines/v2alpha1/src/main/scala/cromwell/backend/google/pipelines/v2alpha1/GenomicsFactory.scala); [use internal ip w/ cromwell](https://gatkforums.broadinstitute.org/firecloud/discussion/12334/running-cromwell-with-google-cloud-call-vm-with-external-ip-address)
* [dgd workflows](https://github.research.chop.edu/DGD/dgd-wdl-workflows)
* [respublica gatk4 pipeline](https://github.research.chop.edu/evansj/broad-gatk4)
* [kibana](https://kibana.dbhi.chop.edu/app/kibana#/)
* [cli ci](http://docs.buildbot.net/current/tutorial/firstrun.html)
* [jira](https://jira.arcus.chop.edu:8443/browse/SCIT-67)
* [jenkins](https://jenkins-ops-dbhi.research.chop.edu/job/sm-gcp-wgs/)
* view k8s pod mem usage: https://github.com/kubernetes/kubernetes/issues/17512

### annotation pipeline
* https://github.research.chop.edu/reichenbee/variant_discovery

### Dockerfiles
* https://github.research.chop.edu/BiG/snakemake-conda-java
* https://github.research.chop.edu/BiG/snakemake-conda-rnaseq
* https://github.com/samesense/snakemake-conda-cromwell
* https://quay.research.chop.edu/repository/evansj/snakemake-conda-java

#### joint calling
* https://bcbio.wordpress.com/tag/joint-calling/
* https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6184596/
* https://gatkforums.broadinstitute.org/gatk/discussion/11813/how-to-consolidate-gvcfs-for-joint-calling-with-genotypegvcfs

### k8s and vault
* https://github.com/kubernetes-client/python/blob/02ef5be4ecead787961037b236ae498944040b43/kubernetes/docs/V1PodSpec.md
* [vault](https://wiki.chop.edu/pages/viewpage.action?spaceKey=CBMISC&title=Secrets+Management+-+Vault)

### variant calling
* https://google.github.io/deepvariant/posts/2019-09-10-twenty-is-the-new-thirty-comparing-current-and-historical-wgs-accuracy-across-coverage/
* [strelka](https://github.com/Illumina/strelka/blob/v2.9.x/docs/userGuide/quickStart.md)
* [comparison](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6597787/)

### advent of code
* https://github.com/daxhuiberts/advent-of-code-2018/blob/master/Cargo.toml
* https://github.com/gobanos/advent-of-code-2015/blob/master/src/lib.rs
* https://github.com/gobanos/cargo-aoc

### gcp
* https://colab.research.google.com/notebooks/editor_details.ipynb
* https://colab.research.google.com/notebook#create=true&language=python3
* [tute table](https://bigquery.cloud.google.com/table/silver-wall-555:TuteTable.hg19?pli=1)

#### beacons
* https://www.googleapis.com/storage/v1/b/arcus-jpe-beacon-daede2ac-sa/
* https://arcus-jpe-beacon-daede2ac.appspot.com/
* https://beacon2-dot-arcus-jpe-beacon-4aa42c03.appspot.com/query?chromosome=1&coordinate=16718&allele=T

### cnv pipeline
* https://github.com/gatk-workflows/gatk4-germline-cnvs/tree/dev
* [compare cnv tools](https://www.biorxiv.org/content/10.1101/482554v1.full.pdf)

### testing
* https://github.research.chop.edu/devops/gcp-python-utilities/blob/master/infosec/Jenkinsfile
* pytest https://docs.pytest.org/en/latest/fixture.html

### tmux
* https://github.com/gpakosz/.tmux#enabling-the-powerline-look

### dante
* https://github.research.chop.edu/evansj/bam.iobio-docker
* https://www.biorxiv.org/content/10.1101/467910v1.full

## learning
* git submodule best practices: recursive clone 

#### python packaging
* package on pypi, but not on conda
* pip conflicts with conda modules

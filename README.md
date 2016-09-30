This repository uses git-annex to manage files. The files' contents are available in a [public Amazon S3 special remote](https://git-annex.branchable.com/tips/public_Amazon_S3_remote/) that is backed by this [S3 Bucket](http://s3.amazonaws.com/liujoshua-public-files?prefix=git-annex).

## Setup 
Clone and navigate into the repository

    # git clone git@github.com:liujoshua/public-files.git
    # cd public-files
    
We be using GitHub for managine the directory tree but not for syncing file contents, so tell git-annex not to store file contents to origin by default

    # git config remote.origin.annex-ignore true
    
Initialize the repository for  annex

    # git annex init
    


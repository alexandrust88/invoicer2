devopsec invoice
==========================

A simple REST API that manages invoices.


The master branch is kept at https://alexandrust88/invoicer but if you are
interested in chapter-specific versions of the invoicer.


To try out the code in this repository, first create a fork in your own github
account. Now before you do anything, edit the file in `.circleci/config.yml` and
replace the `working_directory` parameter with your own namespace.

For example:
```yaml
    working_directory: /go/src/github.com/alexandrust88/invoicer2
```
would become:
```yaml
    working_directory: /go/src/github.com/jvehent/invoicer2
```

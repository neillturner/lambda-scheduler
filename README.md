# lambda-scheduler

Stop and start EC2 and RDS instances according to schedule via lambda

## Overview

This is python source code for the aws-scheduler used by the terraform deployment at https://github.com/neillturner/terraform-aws-lambda-scheduler

## Prerequisites

* Python 2.x.

### Windows

* need a python env installed as per http://www.tylerbutler.com/2012/05/how-to-install-python-pip-and-virtualenv-on-windows-with-powershell/

* a bash client to run build.sh (can get from git for windows )


## Build

* in a command windows go to the directory

* ./build.sh       (builds the zip file for lambda)

* copy the aws-scheduler.zip create to the github project terraform-aws-lambda-scheduler in the package directory.



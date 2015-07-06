Puppet & AWS Talk
-----------------

This is the landing page for Chris Barker's Puppet & AWS Talk. Reference links and materials will be posted here as they become more available. Since this is a work in progress, it is suggested to follow the repo. A tag'ed build of this repo will be available once all the materials that can be made public (and useable) have been.

AWS Audit: by Cody Herridges (@ody), runs in python, is used by Puppet Labs to kill nodes in AWS that do not conform to our tagging standard:
https://github.com/puppetlabs/py-awsaudit

Certsigner: autosign policy project with a few permutations - currently fog based and being re-written to use v2 of the aws-sdk-core libraries
https://github.com/mrzarquon/mrzarquon-certsigner

Puppetdbtags: autotag nodes in AWS with list of running services found in PuppetDB
https://github.com/mrzarquon/puppetdbtags

awsdemo: aws defined types / example manifests / PE installation templates used for AWS Talk
https://github.com/mrzarquon/awsdemo

puppet-ec2tags: custom facts that require the aws-sdk-core library and IAM permissions, but give you all the tags for a node
https://github.com/mrzarquon/puppet-ec2tags

Coming soon: once the talk content itself is finalized, the slide deck and nodes will also be in this repo.

//Chris Barker

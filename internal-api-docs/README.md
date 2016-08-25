# Rackspace Cloud Block Storage Developer Guide for Service Management


The **Rackspace Cloud Block Storage Developer Guide for Service Management** is
Rackspace internal documentation.
 
When you commit changes to the master branch of this repository on rackerlabs,
the updates need to be pushed to the following enterprise github repository:
[git@github.rackspace.com:IX/internal-docs-cloud-block-storage.git]
(https://github.rackspace.com/IX/internal-docs-cloud-block-storage/).
 

1. To push the updates, clone the enterprise repository to your system. 

   ```git clone git@github.rackspace.com:IX/internal-docs-cloud-block-storage.git```

2. In the directory where you cloned the repo, add this public repository as
   the upstream remote:

  ```git remote add upstream git@github.com:rackerlabs/docs-cloud-block-storage.git```

3. Sync your local clone of the enterprise github with the upstream remote:

   ```git pull --rebase upstream master```
   
4. To publish the internal documentation, push your changes to the enterprise
   repository on GitHub.

   ```git push origin master```
   
When you push your changes, the [internal build
job](https://docs-staging.rackspace.com/jenkins/job/internal-docs-cloud-block-storage/)
kicks off to publish the new content on the gh-pages branch. 
You can review the updates at the following URL: 
https://pages.github.rackspace.com/IX/internal-docs-cloud-block-storage/latest/.

**Note:** 
If the build does not run automatically, log in to the [Jenkins
server](https://docs-staging.rackspace.com/jenkins) with your SSO
credentials. Then, click **Build Now** to run the
[internal Block Storage guide]
(https://docs-staging.rackspace.com/jenkins/job/internal-docs-cloud-block-storage)
build manually. You can check the last updated date on the first topic to determine whether
the content updated successfully.

You can also access the Rackspace Cloud Block Storage Developer Guide
for Service Management from
https://pages.github.rackspace.com/IX/internal-docs-landing-page. 




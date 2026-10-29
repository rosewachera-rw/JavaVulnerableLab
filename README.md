## Source Code Analysis (SCA) with Synk and Coverity Scan

This fork is an example of a vulnerable Java application, developed by Cyber Security and Privacy Foundation.

The only modification done is updating the Maven source & target to 1.6 (for running with JDK 11). Change that if you are using newer/older Java. Note that using newer Java will require code changes.

You can scan it with Snyk, by simply creating your own fork and by adding a project from the Snyk dashboard.

To scan the application with Coverity Scan, you would need to develop it with the coverity scan build tool for java. The installer and instructions on how to build, visit https://scan.coverity.com/download?tab=java

Synk enables dynamic application security testing (DAST) while Coverity Scan facilitates static application security testing (SAST). When these techniques are combined, the security of an application is enhanced. 

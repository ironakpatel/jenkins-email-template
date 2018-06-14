# jenkins-email-template
jelly template for jenkins email extension plugin


##### Installation:
 Copy **`detailed_email.jelly`** file on jenkins' `$JENKINS_HOME/email-templates/` directory</br>

##### Usage:
- Use template name as `${JELLY_SCRIPT,template="detailed_email"}`
![Scheme](extension-settings.png)
- Use email extension plugin in you jenkins job
- And get formatted email in your inbox:
    - build Artifacts are direct download links to your jenkins.
![Scheme](email1.png)
![Scheme](email2.png)

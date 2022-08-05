# Demo Deployment

In order to deploy the anomaly detection demo, 

  1. Go to the [OpenShift Console](https://console-openshift-console.apps.ieee.8goc.p1.openshiftapps.com/) and log in with your credentials. 




  2. Once you sign in, switch your view from Developer -> Administratior (located at the top of the sidebar). The Administrator view allows you to see every component of the cluster.


  3. Go to the "Projects" page and click the "Create Project" button in the top right corner.


  4. You will now need to create a project name, display name, and brief description of your project. Make sure that your project and display name do not contain any upper case letters and your project name does not contain any spaces. It is also good practice to keep your project and display names consistent, removing any hyphens or underscores in the latter, eg: 
  Name: test-anomaly-detection-demo
  Display name: test anomaly detection demo
  
  5. Once you are done creating your project, switch back to the Developer view, where we will containerize the source code from GitHub. 
  
  

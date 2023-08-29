# isec6000-assignment1-task1
secure devops assignment 1 github repo 

# Setup Google Cloud Console
 1) First Create Google Account ( optional if already exist skip this step)
 2) once its created go to the google cloud dashboard (https://console.cloud.google.com)

# Setting up kubernet cluster 
1) for setting kubernet cluster, first create a project with proper namespace so that it will be understandable for future use
   dont use name as abc, 123 etc
2) once the project is created activate cloud shell 
   <img scr="/assets/images/shell.png" height="50" width="50">
3) Activate kubernetes engine API by searching as kubernetes engine
   (Note: you can read more about it <a href="https://cloud.google.com/kubernetes-engine/docs/reference/rest" target="_blank"> here </a>  )
4) create cluster by navigating kubernetes engine section and click create cluster
5) provide a appropriate name and choose the location for configuration
   (Note: It will take about 5 to 10 min to complete the process)
6) once the cluster is created it will look like this 

# Connecting the cluster 
 Its time to connect the cluster to local environment 

 1) navigate to the cluster and click connect to connect the cluster 
    
    or copy and paste the following command to cloud shell 

    gcloud container clusters get-credentials {$clusterName} --region {$location} --project {$clusterID}

    replace the clusterName, Location and clusterId as per your configuration

2) 


 

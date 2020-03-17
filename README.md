# ICE
Interactive Control Environnent (ICE)  is a graphical editor that support the edition of emerging ambient applications. 

In order to install it, you should follow these steps:

  1- Download GEMOC Studio from http://gemoc.org/studio.html and install it.
  
  2- Download both .zip files and extract them to the same location. These 2 files represents the editor configurations, setups and worksapce.
  
  3- Launch GEMOC and import all projects from "ICE_WorkSpace"
  
  4- Click on Run -> Run Configurations...
  
      i- From the left panel click on Eclipse Application and create a new one. Chose ICE as its name.
      
      ii- Change the workspace data to the location of the second "runtime-Editor".
      
      iii- Go to the "Arguments" tab, and copy : -XX:MaxPermSize=256m to the VM-arguments.
      
      iv- Click Run
      
  5- When ICE starts, if the projects are not shown in the left panel, you should import them manually from the runtime-Editor workspace.
  
  6- You may access now and use both Editors : one for the pro user and the other for the average.
  
      i- Pro user Editor:
        
          1- From the left panel open the project named "org.eclipse.iceEditor.sample"
          
          2- Open "representations.aird" file by clicking on the arrow that appear on its left
          
          3- Open "environment" and then double click on ICE editor
          
          4- ICE will open on the screen
      
      ii- Average user Editor:
        
          1- From the left panel open the project named "org.eclipse.averageuser.ice"
          
          2- Open "representations.aird" file by clicking on the arrow that appear on its left
          
          3- Open "environment_averageuser" and then double click on ICE editor
          
          4- ICE will open on the screen

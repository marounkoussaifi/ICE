# ICE
Interactive Control Environment (ICE)  is a graphical editor that support the edition of emerging ambient applications. 

In order to install it, you should follow these steps:

  1. Download GEMOC Studio from http://gemoc.org/studio.html and install it.
  
  2. Download both `.zip` files and extract them to the same location. 
  These 2 files represent the editor configurations, setups and workspace. 
  The files are : `ICE_Workspace.zip` and `runtime-Editor.zip`.
  
  3. Launch GEMOC, create a workspace called `ICE_Workspace`, and import all projects from "ICE_WorkSpace"
  
  4. Click on `Run -> Run Configurations...`
  
      - From the left panel click on `Eclipse Application` and create a new one. Chose `ICE` as its name.
      - Put the workspace name `runtime-Editor`. This will create the editor workspace.
      - Go to the `Arguments` tab, and copy: `-XX:MaxPermSize=256m` to the VM-arguments.
      - Click `Run`

  5. When ICE starts, import all the projects from the `runtime-Editor` workspace.
  
  6. You may access now and use both Editors: one for the pro user and the other for the average one.
  
      - Pro user Editor:
        
          1. From the left panel open the project named `org.eclipse.averageuser.ice`
          
          2. Open `representations.aird` file by clicking on the arrow that appear on its left
          
          3. Open the regular environment by clicking on the arrow and then double click on ICE editor
          
          4. ICE will open on the screen
      
      - Average user Editor:
        
          1. From the left panel open the project named `org.eclipse.averageuser.ice`
          
          2. Open `representations.aird` file by clicking on the arrow that appear on its left
          
          3- Open the average user environment by clicking on the arrow and then double click on ICE Average User
          
          4. ICE will open on the screen

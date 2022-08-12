# BindingDemo1
 ##### Data Binding 

1.  Improves the performace of the app
2.  Eliminates findViewById(), makes code concise, makes code easier to read and maintain. 
3.  Recognize errors during the compile time

Step 1: Enable dataBinding in Gradle: App

dataBinding{
enabled = true
}

Step 2: Generate Binding Class for XML Layout, wrap the layout with <layout> tag.
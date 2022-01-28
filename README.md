# DNF.Projects Module

A sample module which tracks Github metrics for projects. It includes examples of how to use scheduled jobs, third party assemblies, JavaScript libraries, etc...

A series of video tutorials was recorded which explains the various aspects of this module:

[Oqtane Module Development Series](https://www.youtube.com/playlist?list=PLYhXmd7yV0elLNLfQwZBUlM7ZSMYPTZ_f)

You can interact with a live demonstration of the module here:

[.NET Foundation Project Activity Trends](https://www.dnfprojects.com/)

Note that you cannot run this module directly in your IDE. You need to ensure that the DNF.Projects folder is located within the same parent folder as the Oqtane framework:  

```
/username
  /DNF.Projects
  /oqtane.framework
```

Organizing the folders in this way allows the system to automatically deploy the module DLLs to the Oqtane framework when your build the module solution. Then you can run the Oqtane framework and it will dynamically load the module.

Example Screen Shots:

![Module](https://github.com/oqtane/dnf.projects/blob/master/Screenshot1.png?raw=true "Bar Chart")

![Module](https://github.com/oqtane/dnf.projects/blob/master/Screenshot2.png?raw=true "Line Chart")

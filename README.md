# Installation files
1. Close every instance of Rhino, Excel, Revit that you have open.
1. Run BHoM Installer
1. Download `Assemblies/Complete.zip` file. Check the file properties (right click -> Properties) and make sure it is "unlocked".
1. Copy the content of `Complete.zip` it in your local BHoM installation folder, generally `C:\ProgramData\BHoM\Assemblies`, overriding everything if prompted.
1. Install [Github Desktop](https://desktop.github.com/) if you don't have it.
1. Clone the main BHoM repo on your machine by going in: https://github.com/BHoM/BHoM and then click the [green button "Clone" -> Open Github Desktop](https://user-images.githubusercontent.com/6352844/175961105-d8e4de3f-ad3f-4610-bfeb-32b8ee51a0cc.png). This will download the main BHoM repo in some folder. From Github desktop, you can check the in which the BHoM repo is stored by clicking "Show in explorer" or pressing `CTRL+Shift+f`.
1. Go in https://github.com/BHoM/RDF_Prototypes/tree/main/Grasshopper%20examples and grab any Grasshopper example file and open it. 
1. The example may give you an error related to "could not find local repository". Please specify the parent directory where the BHoM repository is stored ([one folder up from step 6](https://user-images.githubusercontent.com/6352844/175962806-0dccdedb-8759-4d65-9d18-9e149ea3621b.png)) to the input `GitRootPath` of the component called `LocalRepositorySettings`, see [this example](https://user-images.githubusercontent.com/6352844/175962449-8877f7c8-9deb-4db6-9830-3dd062b7156c.png
).
1. At this point, the example file should work with no error. If there are still errors, please [Uninstall BHoM from Windows control panel](https://user-images.githubusercontent.com/6352844/175970063-cc689283-52be-4db9-86a2-094a13b63d8e.png) and start from scratch.
1. After all the above, install [GraphDB](https://www.ontotext.com/products/graphdb/).



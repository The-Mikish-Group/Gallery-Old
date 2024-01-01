# Gallery
MVC Gallery site

Gallery reads the folder(s) and files dynamically, so add a folder to a Gallery folder or add a file to an existing folder and it will automatically be displayed.

## To add new controller level Gallery folders you must make an entry in the "SharedController" like this:

### public class WoodworkingController : BaseController { }

In this case, a "Woodworking" Gallery folder should be added and Woodworking gallery folders with images into the new Controller level Gallery folder. 
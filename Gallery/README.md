# Gallery
MVC Gallery site

Gallery reads the folder(s) and files dynamically. Add a folder to a Gallery folder or add a file to a Gallery folder's subfolders and it will automatically be displayed. File name is displayed below image and clicking it will take you to a new tab of the full-screen image.

## To add new Gallery folders you must make an entry in the "SharedController" like this:
public class MVController : BaseController
{
    public IActionResult Index() => GalleryView();
    public IActionResult Gallery(string viewName) => GalleryView(viewName);
}

In this case, "MV" is the Gallery folder to be added; having a controller entry takes care of the rest of any needed programming.

Easy folder and image drag and drop using FTP. Republishing is only necessary if a new main gallery folder is added to create the controller.
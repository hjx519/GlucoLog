when testing your page

1. first locate the following in the hellowrold-> Mainlayout
private List<RouterLink> createLinks() {
        MenuItemInfo[] menuItems = new MenuItemInfo[]{ //
                new MenuItemInfo("About", "la la-file", AboutView.class), //
                new MenuItemInfo("Hello World", "la la-globe", HelloWorldView.class), //
        };


 2. The following will add your component on the main page
 new MenuItemInfo("name displayed on the side bar", "la la-globe", "your class name".class)

 3. import the specific packages using the following format (idea will do it for you in most of the cases)
 import com.sugarFree.application.views.helloworld.HelloWorldView;

 4. deloy the application and start your testing.



 --updated 12 02 2021 Zimu Huo
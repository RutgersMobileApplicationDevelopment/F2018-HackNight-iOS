# How to create Tip Calculator App for iOS

1. Download Xcode from https://developer.apple.com/xcode/
2. Open Xcode, Click create new project, select Single View App for template, enter a product name (Tip Calculator, First App, etc.), and create project <br /> <br />
![Project Creation](https://image.ibb.co/iY851e/Screen_Shot_2018_09_18_at_11_13_33_PM.png) <br /> <br /> <br />
![Project Naming](https://image.ibb.co/hccLZz/Screen_Shot_2018_09_18_at_11_14_13_PM.png) <br /> <br /> <br />
3. XCode has 5 main areas, as shown below:
  * **Toolbar (Green):** displays key information about project, expand/collapse other areas, run project
  * **Navigator (Orange):** Find files, search in your project, manage source control, navigate errors
  * **Editor Area (Red):** Write code, build UI with storyboard, change project settings
  * **Utilities (Purple):** Gives info about files, set properties of items in Interface Builder
  * **Debug Area (Blue):** Test and debug your code at runtime <br /> <br /> <br />
  * ![XCode Layout](https://cdn.rawgit.com/MakeSchool-Tutorials/Magic-8Ball-Swift4/master/P2-New-Project/assets/xcode_areas.png) <br /> <br /> <br />
4. Initially, choose a simulator (ie iPhoneX, iPhone 8) from the top left and click the play/run button to start up your simulator <br /><br /> <br />
![Simulator Selection](https://preview.ibb.co/c19Zuz/Screen_Shot_2018_09_18_at_11_20_27_PM.png) <br /> <br /> <br />
![Empty Simulator](https://preview.ibb.co/nJXhge/Screen_Shot_2018_09_18_at_11_22_25_PM.png) <br /> <br /> <br />
5. Click on the Main.storyboard file to view the visual layout for your app. Initially, you are given an empty screen <br /> <br /> <br />
![https://ibb.co/c3YYnK](https://preview.ibb.co/jGeTMe/Screen_Shot_2018_09_18_at_11_31_26_PM.png) <br /> <br /> <br />
6. Head to the bottom right of the screen and click on the Object Library tab (circle with a little square in it). In this view, you can find a list of UI elements such as buttons, labels, and textfields that you can drag and drop onto your screen. <br /> <br /> <br />
![https://ibb.co/dTfqZz](https://image.ibb.co/fsXR7K/Screen_Shot_2018_09_18_at_11_27_21_PM.png) <br /> <br /> <br />
Drag and drop a Label from the Object library onto the screen on your storyboard. Click on the label and type to set the text of the label to whatever you like (ie, Tip Calculator). <br /> <br /> <br />
![Label on storyboard](https://preview.ibb.co/hitoMe/Screen_Shot_2018_09_18_at_11_40_11_PM.png) <br /> <br /> <br />
You can center the text/change the font by clicking on the label and modifying its attributes from the attribute inspector (4th tab out of 6) on the right side of Xcode. To see how this looks on app, click the run button again and open your simulator, and you should see the label you added. <br /> <br /> <br />
![Label on phone](https://image.ibb.co/mLjWRe/Screen_Shot_2018_09_18_at_11_59_00_PM.png) <br /> <br /> <br />
7. You can also add and modify other UI elements similarly. Your next objective is to drag and drop a Textfield and a Button onto your view controller. Each of these UI elements have a different purpose. With a Textfield, you are able to prompt a user to input text. With a Button, you can trigger some sort of action in the app. <br /> <br /> <br />
![Editing Label](https://image.ibb.co/kZD2XK/Screen_Shot_2018_09_19_at_12_06_29_AM.png) <br /> <br /> <br />
8. Now it is time to engage in some more complicated Xcode shenanigans. How do we start using Swift to programatically to tell our app to do things? <br /> <br /> <br />
 * **Note:** if you do not know how to program in Swift, don’t worry, you can just follow the code given in this tutorial for now, as it is pretty straightforward. We strongly suggest that you go through the Swift Essentials playground which is linked at the bottom of the guide, which will clearly and easily teach you basics such as types, conditionals, and functions in Swift. <br /> <br />
 To view the code for the View Controller you currently have open in , you can select the view controller <br /> <br /> <br />











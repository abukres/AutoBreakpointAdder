# AutoBreakpointAdder
This Visual Commander command adds a breakpoint to every method in every .cs file in the selected project in VS Solution Explorer.

Visual Commander is a Visual Studio extension to automate tasks in Visual Studio.

##### How to use:
* Download and install the extension from https://vlasovstudio.com/products.html. Note that there are free and pro versions. The extension is also available in the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=SergeyVlasov.VisualCommander).
* In Visual Studio select the Extensions menu -> VCmd - > Commands and click on the Add button. 
* Select C# 4.0 as the language and copy and paste the command code from this repo.
* Give the command a descriptive name. Ex: Add breakpoint to every cs file.
* A keyboard shortcut can be assigned to the command. Go to Tools -> Options -> Keyboard and assign the shortcut to the proper VCmd.Commandxx.  
  
##### Why do I find creating a breakpoint everywhere useful:
An example where I need to create a breakpoint everywhere is when for example I have an api running and waiting for requests and I do not want to spend time to find out what method is the entry point for some request. I hit the shortcut, send the request, a breakpoint is hit and I know quickly what api method was called. Then I remove all the breakpoints.  It's a time saver.




  
    Many thanks to Sergey Vlasov for creating some cool Visual Studio extensions.

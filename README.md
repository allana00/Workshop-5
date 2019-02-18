**What is a segue**
A segue is used to pass data from one view to another and then present the new View Controller.Segues control the naviagation or flow of your project. 

**What is a segue identifier?**
A plain string to pass information to one controller to another.

**How do you create segue from a button?**
Control and click and drag to appropiate view controller.

**How do you create from a view controller without a button?**

**What is the method to perfrom a segue called and what argument does it take?**
performSegue(withIdentifier: "newVC", sender: nil)
}
**What method is called immediatly before a segue is performed?**
dismiss(animated: true, completion: nil)
**How do you assign a new view controller class?**
Create a UIViewController subclass. For example, go to your target's folder in the project navigator panel on the left and then control-click and choose "New File...". Then rename second view controller

**How do you pass data between two view controllers? (this will need a few sentences to explain)**
Click on view controller button at the top of the view controller, ctrl click and drag across, then click on show then give the segue an identifier

**You dont link a segue "backwards", why?**

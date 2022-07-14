# MVCHomework


MVC pattern is an architectural pattern that divides an application into three main parts

1- Model
2- View 
3- Controller

Model includes all the data and its related logic. It represents data that is being transferred between controller or any other related business logic


View presents data to the user or handles user interaction. Views are created by the data gathered from the model data. A view requests the Model to give information so that it resents the output to the user. In IOS MVC, View cannot directly directly request Model, so it doest through Controller

Controller is an interface between model and view. It interprets the inputs from the user, informing the Model and the View to change as appropriate


Apple MVC is different from the tradional MVC

In Apple MVC, controller gets user action from the view and based on user action it updates the model. The model then performs calculations and logics and notifies back to the controller, and the controller then responds back to the view and updates it. The view and model do not interact directly with each other. The controller is the source through which they communicate.
Controller is the entry point to the application. 

MVC avoids complexity by dividing an application into separate parts. Whereas it is hard to use MVC on the other hand due to mixed business logic with UI, no formal validation support

Project 0X00: AirBnB Clone-The console

The goal of the project is to deploy on my server a simple copy of the AirBnB website. However, not all the features of the AirBnB will be implemented, only some of them that covers all fundamental concepts of the higher level programming track.

After 4 months on this project, I will have a complete web application composed by:
1. A command interpreter to manipulate data without a visual interface, like in a Shell (perfect for development and debugging)
2. A website (the front-end) that shows the final product to everybody: static and dynamic
3. A database or files that store data (data = objects)
4. An API that provides a communication interface between the front-end and your data (retrieve, create, delete, update them)

The main goal for this specific project is to complete the first step which is creating the consolewhich is the command line interpreter similar to the shell but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:
1. Create a new object (ex: a new User or a new Place)
2. Retrieve an object from a file, a database etc…
3. Do operations on objects (count, compute stats, etc…)
4. Update attributes of an object
5. Destroy an object

When you run the console file, it accepts commands and arguments and provides an output according to the instructions given. For example:
>>> guillaume@ubuntu:~/AirBnB$ ./console.py
>>> (hbnb) all MyModel
** class doesn't exist **
>>> (hbnb) show BaseModel
** instance id missing **
>>> (hbnb) show BaseModel My_First_Model
** no instance found **
>>> (hbnb) create BaseModel
49faff9a-6318-451f-87b6-910505c55907
>>> (hbnb) destroy
** class name missing **
>>> (hbnb) create BaseModel
2dd6ef5c-467c-4f82-9521-a772ea7d84e9
>>> (hbnb) destroy BaseModel 49faff9a-6318-451f-87b6-910505c55907
>>> (hbnb) show BaseModel 49faff9a-6318-451f-87b6-910505c55907
** no instance found **
>>> (hbnb)

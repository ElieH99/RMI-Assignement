# RMI-Assignement
RMI registry is a namespace on which all server objects are placed. Each time the server creates an object, it registers this object with the RMIregistry (using `bind()` or `reBind()` methods). These are registered using a unique name known as bind name.

To invoke a remote object, the client needs a reference of that object. At that time, the client fetches the object from the registry using its bind name (using `lookup()` method).
<img width="949" alt="RMI1" src="https://user-images.githubusercontent.com/92988830/152685344-7f568c3c-f0e4-40c7-b6cb-6ac4a08ddf1e.png">

This project demonstrates how to separate Instrumentation Tests from the Android application code into their own module **outside** of the main project file structure.

### How to run the test

To run the test you have to create a new configuration for the test module:

- In the configuration dropdown select "Edit configurations..." to open the "Run/Debug Configurations" window. 
- Click the "+" and select "Android Instrumented Tests".
- Change the name to "module-androidTest" and select the module of the same name as "Module". 
- With "OK" you save the new configuration. 

With the "Run 'module-androidTest'" button next to the dropdown you can run the test.
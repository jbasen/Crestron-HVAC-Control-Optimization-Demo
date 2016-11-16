# Crestron-HVAC-Control-Optimization-Demo
HVAC Demo Program Readme
I'm releasing this HVAC demo program as it can provide people with ideas on how they can optimize energy usage
in a home.  This is the code that I use in my own house and as such it is customized for my specific needs.
The primary area where this code would need to be modified for other people is that I live in the mountains
of Idaho and don't have air conditioning.  Even when it gets hot on a summer day the temperature in the
mountains drops significantly at night.  I'm in the process of adding a whole house fan and with a
motorized window so in the evening, after the temperature outside has dropped to below the set point
of the house, the system will open the window and use a whole house fan to pull cool outside air into the 
house for cooling. 

At the time I'm posting this it is late fall and I've just written the module to use a whole house fan for
cooling.  Because of this I've only tested this code, along with support in the other modules for cooling,
with SimplDebugger.  I am currently using all these modules in my own house.  That being said, this code 
won't be tested in real life until this coming summer when I have a new whole house fan installed with a
wi-fi interface, a new motorized window installed, and the temperatures are warm enough to really track the
system operation real time. I just want to make sure that people are fully aware of where this code stands.

Another energy saving optimization is that the modules will slightly lower the heating set point of the house 
during the day if the forecast is for warm weather that will warm the house up anyway.  

This demo program does not include a touch panel interface.  The program is meant to be run in a separate slot
on a 3 series processor.  All signals required for the user interface are tied to an EISC symbol.

I hope that this code gives other people ideas in how to optimize the energy used for heating and cooling a
home.

Thanks

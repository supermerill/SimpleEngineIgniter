### SimpleEngineIgniter
KSP: A very simple igniter system to restrict the number of restart of your engines

Need ModuleManager.

functionality:
 - New resource: engineIgniter
 - Each time an engine should begin produce thrust and the trottle is not at 0, it consume one igniter.
 - if no igniter available, the thrust is scaled down by 50 (the motor/turbopump vent the fuel into space)
 - work with minThrust set.
 - Config file for stock engine. Don't hesitate to modify it / create your own.
 - Other config file for minThrust, remove it if you don't want.

known issue:
 - The engine plume rework doesn't work on engineFX
 


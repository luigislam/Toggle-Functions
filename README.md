### Fn_Wait(KeyName, isWaiting?)
This function is used to check if the Key is waiting as True and then flips it to False and then function will return a True value.

### Fn_Cooldown(KeyName, Milliseconds?)
The Function can be used in an If-Statement to apply a Cooldown period via the Milliseconds parameter to keep returning as False as long as the cooldown period is not over.
It will return as True on the initial run and on subsequent executions when the cooldown period is over.

### Fn_Queue(KeyName, Milliseconds?)
This essentially works in reverse of Fn_Cooldown. 
The Function will only return as True once you enable it by assigning Millseconds for a certain amount of time and then once that time is over it will return False until you reassign more time to queue for.

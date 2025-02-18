To simplify,

for include

When the base use case is executed, the included use case is executed EVERYTIME.
The base use case required the completion of the included use case in order to be completed.
a typical example: between login and verify password

(login) --- << include >> ---> (verify password)

for the login process to success, "verify password" must be successful as well.

for extend

When the base use case is executed, the extended use case is executed only SOMETIMES
The extended use case will happen only when certain criteria are met.
a typical example: between login and show error message (only happened sometimes)

(login) <--- << extend >> --- (show error message)

"show error message" only happens sometimes when the login process failed.

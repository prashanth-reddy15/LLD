**To simplify,**
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




**This reads to me as:**
Include = reuse of functionality (i.e. the included functionality is used or could be used elsewhere in the system). Include therefore denotes a dependency on another use case.

Extends = adding (not reusing) functionality and also any optional functionality. Extends therefore can denote one of two things:
1. adding new features/capabilities to a use case (optional or not)
2. any optional use cases (existing or not).

Summary:
Include = reuse of functionality
Extends = new and/or optional functionality

You will most often find the 2nd usage (i.e. optional functionality) of extends, because if functionality is not optional, then most times it is built into the use case itself, rather than being an extension. At least that's been my experience. (Julian C points out that you sometimes see the 1st usage (i.e. adding new features) of extends when a project enters it's 2nd phase).

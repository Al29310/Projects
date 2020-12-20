# Projects
This project involved getting the standard time from the CPU and then allowing the user to add either a second,minute or hour. After the user selected thier option the program would
then showcase the updated time. The clock displayed both millitary time as well as standard time. The project had to take into account if the user selected the "add minute"
option when the clock was at ##-59-##. If this was the case the addHour method was called. This same principle is applied if the addSecond method was selected and it was at 
##-##-59 except this time the addMinute method would beb called. I believe i set these up well and accounted for these different inputs. I felt as though i had to many lines of code 
within my main method and if i was to attempt this project again i would create functions that would take care of taking in user input etc. This would clean up the main method.
Working with both millitary time as well as standard time was a little challenging as i did not want to create seperate functions for each clock so i had to manipulate the hours variable
and take into account the different inputs that could have been put in. IE hours = 23, in millitary time this is fine but i also needed to display standard time so i had to create a 
new variable that represented standard time. I believe this project helped me work with functions a bit more and the lessons learned will come in handy whenever i work with functions,
To make this project readable/maintainable and adaptable i added plenty of comments. This shows me the overall flow of the program and if i need to update it i can see what each function
is doing and tinker with it until i get the desired result. These comments also allow someone else to quickly read through and figure out what my code is doing.

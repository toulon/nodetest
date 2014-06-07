nodetest
========

Modified Garrilla's tutorial to include select statement
Based on http://garrilla.logdown.com/posts/192327-rest-follow-up-excercise

Garrilla, I was able to get your code working and then added one small feature I have wanted to add in another project, select statement on gender. While it works I am not able to save the field to mongodb as the field is now a select and not an input. I attempted, without success, to copy the section of code in function updateUser that references input and replace it with select. The code here is runs without errors, using webstorm on MAC OS, but should work anywhere. It is a github repository after all. Please show me the error of my ways. I am so close, yet not there. Thanks

Toulon

Never mind. I got it working.
```
 value = document.getElementById("updateUserGender").value;
      console.log("Value =" + value);
      updatedFields['gender'] = value;
```      
If you have a better solution I would like to here your thoughts.


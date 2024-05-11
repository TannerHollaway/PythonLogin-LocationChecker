# PythonLogin-LocationChecker

<h2>Description</h2>
Creating a python script that implements a time and location restricted login system.
<br />

<h2>Utilities Used</h2>

- <b>Python
- requests
- pytz
- datetime
  </b>


<h2>Program Walk-through:</h2>

<p align="center">
First I'll want to install pytz and requests. Pytzy allows us to convert and compare times across different time zones: <br/> 
<img src="https://i.imgur.com/iD84Etr.png" height="80%" width="80%" alt="TimeRestrictedLoginSystem"/>
<br />

<p align="center">
The first function checks if the current time falls within our allowed range of 8 AM to 9 PM Central Time: <br/> 
<img src="https://i.imgur.com/WbDu10N.png" height="80%" width="80%" alt="TimeRestrictedLoginSystem"/>
<br />

<p align="center">
Next is to ensure the user is logging in from a specific location, in this case, WhiteHouse. We do this using IP geolocation: <br/> 
<img src="https://i.imgur.com/RrM5vl7.png" height="80%" width="80%" alt="TimeRestrictedLoginSystem"/>
<br />

<p align="center">
Lastly, we integrate both checks to decide if a login should be allowed. : <br/> 
<img src="https://i.imgur.com/n7RTSN3.png" height="80%" width="80%" alt="TimeRestrictedLoginSystem"/>
<br />

<p align="center">
Example of Correct time and Correct location: <br/> 
<img src="https://i.imgur.com/TliUthg.png" height="80%" width="80%" alt="TimeRestrictedLoginSystem"/>
<br />

<p align="center">
Correct time Wrong location: <br/> 
<img src="https://i.imgur.com/krilSyL.png" height="80%" width="80%" alt="TimeRestrictedLoginSystem"/>
<br />

<p align="center">
Correct location wrong time: <br/> 
<img src="https://i.imgur.com/1kukYXG.png" height="80%" width="80%" alt="TimeRestrictedLoginSystem"/>
<br />

<p align="center">
I had a lot of fun with this one. I needed a lot of help with the code because for me it was very challenging. A lot of looking things up and learning about new processes: <br />

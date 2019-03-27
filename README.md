# [uHike]
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)



&nbsp; **Purpose** </br>
&nbsp; A simple, user-friendly web app to find nearby hiking trails. </br></br>

&nbsp; **Challenges**
</br>&nbsp; `` Issue: Determine user's location on load of page ``
</br>&nbsp; `` Solution: Utilize the Google Maps API's geolocation.getCurrentPosition function to store the user's lat & long``
</br>
</br>&nbsp; `` Issue: Find a list of trails and trail data based on the user's current location ``
</br>&nbsp; `` Solution: Make an AJAX request to the Hiking Project API which passes the lat & long received from Google Maps  ``
</br>
</br>&nbsp; `` Issue: Provide directions to whichever trail the user selected ``
</br>&nbsp; `` Solution: Use the Hiking API's lat & long property for the trail selected to create and open a custom URL which passes the user's current location and destination to Google's web-based directions page``

</br>

**Technical Approach** </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Technology Used** </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; JavaScript, HTML, CSS, jQuery, AJAX </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **APIs Used** </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Google Maps, [Hiking Project] </br>

-----
**Other Contributors** </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Jamie Epstein @[JASEpstein] </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Lisa Vo @[thuyngavo] </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Colby Cooke @[cookecn] </br> 

 [uHike]: <https://mprestonsparks.github.io/uHike/>
 [JASEpstein]: <https://github.com/JASEpstein/>
 [thuyngavo]: <https://github.com/thuyngavo/>
 [cookecn]: <https://github.com/cookecn/>
 [Hiking Project]: <https://www.hikingproject.com/data/>

<!--Events Table-->
<table id="Events" name="Events">
	<tr>
		<th>
		eventName
		</th>
		<th>
		eventLocation
		</th>
		<th>
		eventTime
		</th>
		<th>
		eventDescription
		</th>
		<th>
		eventUpdateTime
		</th>
		<th>
		eventStatus   (Started/GoingToStart/Happening)
		</th>
	</tr>
</table>

<!--Stalls Table-->
<table id="Stalls" name="Stalls">
	<tr>
		<th>
		stallID
		</th>	
		<th>
		stallName
		</th>
		<th>
		stallLocation
		</th>
		<th>
		stallDescription
		</th>
	</tr>
</table>

<!--Users Table-->
<table>
	<tr>	
		<th>
			username
		</th>
		<th>
			password
		</th>
	</tr>	
</table>

<h1>API</h1>
~~~~~~~~~~~~

<!--MAP-->

API 1:
``````

get the events and thier locations and event time.
Request parameters : currentTime
Data : 
	{
		"status code" : 200(successful)/400(failed request)/300(no data available)
		"events"	  : [{
						"eventName" 		: ,
						"eventLocation" 	: ,
						"eventTime" 		: ,
						"eventDescription" 	: ,
						}]
	}

API 2:
``````
{
"status":
"events" :[{
			"eventname" : ,
			"eventstatus": ,
			}]
}
What we need?

-Initially(i.e while opening the browser), we need ALL the events

-Server sends data whenever an event is over,starting, or is going to happen. Data should be updated in the map with the latest events.

-Implementing some sort of push handling in the client, sockets? GCM? Push API?

-

API 3:
``````

To add the events using a form.
{
	eventname,eventlocation,eventtime,eventdescription
}


API 4:
``````

To add the food stall using a form.
{
	stallname,stalldescription
}

API 5:
``````

To update the event status using form.
{
	eventname,eventstatus
}

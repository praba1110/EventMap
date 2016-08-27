<!--Events Table-->
<h3>Events Table</h3>
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

<h3>Stalls Table</h3>
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

<h3>Users Table</h3>
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


<h4>Requirements:
</h4>
<1-3 in a map like UI using webGL><br>
1) Display all Events in their respective locations<br>
2) Updation of the map whenever an event stage changes using some sort of a push mechanism (try avoiding AJAX)<br>
3) Events have 3 stages, going to start, happening right now, ended. Each should have different colors<br>
<4-5 for Festember guys to update manually, we are not automating because of event delays><br>
4) Add a food stall using a form <br>
5) Update the event stage for any event using a form like UI manually. <br> 

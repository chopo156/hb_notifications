# hb_notifications
A Notification System for everyone who likes a good style.


This is a Notification System! It is not a resource that you can easily paste in your server and it will do something for you...

if you have no knowledge , then this resource is not really what you are looking for.


HOW TO INSTALL:

drop the resource into your resources folder, make sure that the name is 'hb_notifications', add 'start hb_notifications' to your server.cfg and restart your server.
	
	
How to use it for another resources:

	you have 4 things you can manage:
		- position (string)
		- message (string)
		- color (any format eg. rbg(), #FFFFF... (string))
		- time the message will stay in ms (no string)
		
	
	Use it in your events like this:
	
		(on client scripts)
		TriggerEvent("hb_notifications:display", "position", "text", "color", time)
		
		(on server scripts)
		TriggerClientEvent("hb_notifications:display", source, "position", "text", "color", time)
		
		
	thanks for using!
	
	**Don't edit this code and re-release it without permissions!**

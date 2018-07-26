---
layout: post
title:      "Instance Objects in Ruby"
date:       2018-07-26 22:00:12 +0000
permalink:  instance_objects_in_ruby
---


According to tutorialspoint.com, instance objects in Ruby are created by using the method "new" of the class while objects are instances of the class. It sounds confusing at first but here is an example:

artist1 = Artist.new
artist2 = Artist.new

"artist1" is the name of the first object while "artist2" is the name of the second object. 

In order to create an object instance, you must write the object name as stated earlier and then an equal (=) sign will follow with the class name with a dot operator and "new" keyword.

This is just an example of the instance object and this is how you use it in a initialize method:

class Artist
    def initialize(id, name, song)
		        @artist_id = id
						@artist_name = name
						@artist_song = song
	 end
end

This method allows you to pass on the values of the local variables to the instance variable @artist_id, @artist_name, and @artist_song. The local variables hold the values that are passed along with the new method and now you can create a new objects like as shown:

artist1 = Artist.new("1", "Drake", "One Dance")
artist2 = Artist.new("2", "Cardi B", "Bodak Yellow")

All the information above was created using a reference from tutorialspoint.com.




It lets a Ruby Gem API client to access and use the Bloc API.

Bloc's API provides an external facing JSON Web Token authorized gateway to the Bloc application. You can access it via cURL, but an API client can manage the low-level details of making requests and handling responses. Build the Kele API Client to provide easy access to and use of the student endpoints of Bloc's API.

Code examples:
$ irb
>> require './lib/kele'
=> true
>> Kele.new("jane@gmail.com", "abc123")
>> mentor_id = 99
>> kele_client.get_mentor_availability(mentor_id)
>> roadmap_id = 99
>> kele_client.get_roadmap(roadmap_id)
>> checkpoint_id = 99
>> kele_client.get_checkpoint(checkpoint_id)
>> kele_client.get_messages(1)

API Reference
http://docs.blocapi.apiary.io/

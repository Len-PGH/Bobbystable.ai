# Bobbystable.ai
https://Bobbystable.ai AI Reservation bot powered by [Signalwire](https://signalwire.com/?utm_source=bobbystable.ai)


Weclome to Bobbystable.ai. Bobbystable.ai is a functional demo of a restaurant reservation system using Signalwire's API's.

In this repo, you will find the full prompt used, all functions used.  The functions are written in perl.


In addition to what is included in this repo you will also need a web server(NGINX), Database(Postgresql), Signalwire's API's, Registered Campain for SMS, and related perl modules.



-------------------

The website is used to display the reservation details. This can be put behind a user name and password but was left open to show the fuctionality.

![image](https://github.com/Len-PGH/Bobbystable.ai/assets/13131198/5a03a103-83df-495b-bc98-8de136fa5cdc)


---------------------------

This is a backend interface gated by a login user name and password.

- `user:` This is the caller's interaction.
- `Assistant:` This is the AI bot's interaction.
- `function:` This shows that the function was executed either correctly or incorrectly.
- `system:` This is like the assistant but on a higher level.

![1705971341262](https://github.com/Len-PGH/Bobbystable.ai/assets/13131198/772e91b4-0338-41b3-aa33-29e5f295cc2d)


----------------------------

This is the text message sent that includes:

- Reservation name.
- Reservation date and time.
- Instructions on how to update the reservation online with a unique link.
- The option to STOP to help comply with sms regulation.

![1705971339655](https://github.com/Len-PGH/Bobbystable.ai/assets/13131198/1319f8e2-4cf2-4d8e-a1b1-e22ca9717649)









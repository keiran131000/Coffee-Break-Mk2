# Coffee Break

This is the best in show winning solution from team ctrlz at Hack Manchester Jr 2017

I had the enjoyment of competing at Hack Manchester Jr this week, and despite not knowing anyone upon entering I had one of the best experiences I have ever had at a hackathon. We took part in the Texecom challenge. This required us to use data that had been collected by sensors throughout the building. We decided to build a dashboard with comedic effect. This, despite workers rights suggested that the fewer breaks the worker takes the better! (We know this isn’t the case but it can be implemented in the opposite direction)

I had never used any PHP prior to the event but after one days work I was writing mysqli queries running within PHP. This was part of the reason our team went on to win the best in show award from Web Applications UK. I found PHP difficult as it disagrees often with javascript, this is due to JS being client side and PHP being server side. However the PHP becomes very simple to pass variables when the code is stored inline within the page. We chose a PacMan theme due to our main target audience being people working in the software industry. This means they will be very interested in retro games and the plan was to implement this further by adding games such as as Mario or Snake. To display the characters we used gif files, this was because they load inline with the HTML and are small files. Ultimately it is also less to go wrong when we are debugging, this means we could work more efficiently. However there was an issue that we were unable to edit the gif without totally extracting it.

See below the interface we designed, as you can see it forms a dashboard and is very retro themed. There are some small pieces of code to edit the gif such as transforming the top ghost to look in the opposite direction. I also included the average temperature over the four room with a vision to add individual temperatures. I also added the number of times a door had been opened again by querying the database and returning the number of records with that device ID.

Calculations were also interesting so I learnt how to use math functions within PHP and therefore could do all of my querying and interrogation server side therefore reducing the load an the client. This means the site loads slightly quicker.

Thanks

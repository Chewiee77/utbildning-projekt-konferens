# Digi Royal Conferences
individual project using only CSS/HTML (exept for one line to close the popupmenu when choosing a link). Done as part of a Frontendedeveloper program at Folkuniversitet, Karlstad. 

The project set out to create a website for a fictional Conference taking place in Karlstad, Sweden. 
The page should present 10 Seminars, and the possibility to book your attendance. You should be able to book just for the day or more, and also choose what food you like and tell if you have any allergies.

Of course the page should be responsive.
The HTML should also be semantic, and accessibility was important.

My goal for the project was to create a large landingpage contain smaller sections of the conference. I came up with the brandname DigiRoyal Confereces and hence the name i chose to 
give the page a purple color-scheme. Purple standing for magic and royalty etc.

The first thing i did was to check my colors in coolors contrast checker, to see if they were OK.
Later on, to further measure my accessibility and performance, i started of by using lighthouse in the inspector. First measure saw performance lacking and some other problems. But by resizing and changing format on the pictures, and som eother tweaks i ended upp with a lighthouse scor of:
- Landingpage 99 100 92 100
- Bookingpage 99 91 100 100
- Speakerspage 100 100 92 100

I also checked mu code against WCAG standards ond validated with W3C, all with good results.

As i final check i used Brisk to check my performance on different devices.

As the final step i published my work at [Netlify](https://digiroyal.netlify.app/index.html)

Testing/checking it further "live" i noticed some behaviors that was strange when using iphone. Implemented some more fixes, that also lead to some functions beeing scrapped in the bookings form.

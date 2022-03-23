# START Hack 2022 - SBB Case

### Case Introduction
More and more travelers want to take their bicycle on the train to discover Switzerland. For self-service loading of bicycles SBB offers space on the train, which customer need to reserve between march – october for many IC lines upfront.
On average there are 12 bicycle spaces per train available. At busy times like weekends, when the weather is warm and sunny, we offer up to 40 spaces per train. 
Whenever extra spaces are required, staff are need to load the bicycles on an extra wagon.
Unfortunately, our customers can’t see how many spaces are available, so they need to try each single reservation to get to know if they can catch this connection with their bike.
Because it costs just 2 francs, people tend to book several reservations in a row to stay flexible for their way back home. But in fact, they just need one space and those other reservations block free spaces other people can't book to get home. 
Happily, our customers know better at what time they wanna leave in the morning to start their trip. But they can't book their reservation to early, because they don’t know the weather for the weekend many days upfront. So they tend to wait as long as possible to make sure they wanna go for a bike trip on the weekend. 
To put you in our customers shoes we provide a little demo of the reservation procedure you find here: https://github.com/START-Hack/SBB-STARTHACK22/blob/41f346e1d60576385a49629649f79e206543955e/Demo_bicycle_reservation.mp4 
If no spaces available anymore, you just get a hint and the process stops without any references to other connections which maybe still have free spaces.


We are looking for an analytics based solution to forecast the latest moment when our customers probably can book their bike reservation. 
It is important, that the solution is independent from our app, because our backend reservation system is going to be replaced soon.
The winners prognose is going to be published on our website: www.sbb.ch/en/biketransport
With that prognose you help us to reduce no-shows and bring people back home.
Furthermore, if we can present our customers an overview of probably availabilities, they can see that later connections maybe still can be booked and so the curve of demand can be flattened.
On top of that, we can adjust our internal staffing upfront depending on the predicted demand for bicycle transportation to decide on Tuesday how many people are needed for the weekend.

Who will help us to enable our customers to have a joyful ride at the weekend?

### Case Pitch
https://api.video.swisstxt.ch/html5/html5lib/v2.80/mwEmbedFrame.php/p/131/uiconf_id/23476493/entry_id/0_bx360554?wid=_131&iframeembed=true&playerId=kaltura_player&entry_id=0_bx360554

### Deep Dive Slides
https://github.com/START-Hack/SBB-STARTHACK22/blob/cdd49b13182a3724b5d02d3b2e4ae031c5ec2770/StartHACK_Deep%20Dive_Long.pdf

### Further Information
Insert any further information about the hack case, the topic and related projects.
Give as much context as possible, in order to give your coders a head start!
SBB Company Video: https://www.youtube.com/watch?v=EVpPJnm8-ek
SBB pioneers: https://api.video.swisstxt.ch/html5/html5lib/v2.80/mwEmbedFrame.php/p/131/uiconf_id/23476493/entry_id/0_83a1y3s7?wid=_131&iframeembed=true&playerId=kaltura_player&entry_id=0_83a1y3s7

Information on how customers can take their bike on a train: https://www.sbb.ch/en/timetable/travel-advice/bicycles/take-your-bike-with-you.html?tracking-marketingurl=biketransport and more information: https://www.sbb.ch/en/help-and-contact/produkte-services/tickets/switzerland/bikes.html

### Resources
- anual formation - https://data.sbb.ch/explore/dataset/jahresformation/information/
- amount of bikehooks - https://github.com/START-Hack/SBB-STARTHACK22/blob/main/rollmaterial-matching.xlsx
-	Timetable search https://transport.opendata.ch / https://opentransportdata.swiss/en/dataset/ojp2020 (https://opentransportdata.swiss/de/cookbook/open-journey-planner-ojp)
-	Weather data https://github.com/START-Hack/SBB-STARTHACK22/blob/main/weather.xlsx
-	Historical reservation data from 2021 (Number of reservations per train, total capacity, time of booking date/hour) 
- Weather --> if you need other Weather Data, please meet us at the booth.
- Reservation data from 2019–2021: https://github.com/START-Hack/SBB-STARTHACK22/blob/main/reservation_data_2019-2021.zip
- Reservation data from 2019–2021 incl. bike capacity: https://github.com/START-Hack/SBB-STARTHACK22/blob/main/reservation_data_2019-2021_incl_capacity.zip
- Corporate Design of sbb: https://digital.sbb.ch

### CSV Explanation
Reservation without capacity
| res\_id        | res\_dt          | einst\_zug                                                                            | reisetag      | dl   | wagen        | wty           | abt\_char     | verweis       | gr\_kkat     | platz              | anz\_reisende   | einstieg                 | ausstieg           | tarif                      | pruefzahl     | buch\_tag                                  | ann\_tag      | term\_buch    | term\_ann                   | dlt                 | klasse      | zug        | linie | strecke |
| -------------- | ---------------- | ------------------------------------------------------------------------------------- | ------------- | ---- | ------------ | ------------- | ------------- | ------------- | ------------ | ------------------ | --------------- | ------------------------ | ------------------ | -------------------------- | ------------- | ------------------------------------------ | ------------- | ------------- | --------------------------- | ------------------- | ----------- | ---------- | ----- | ------- |
| reservation ID | Reservation Date | Train on which the reservation is (very technical, ignore everthing behind the point) | Day of Travel | ???? | Coach Number | type of Coach | please ignore | please ignore | please ignre | Place in the coach | amount of bikes | Beginning of reservation | End of reservatoin | price info (please ignore) | please ignore | Date of reservation (redudant to column C) | please ignore | please ignore | please ignore please ignore | Type of reservation | Trainnumber | Train Name | Line  |

### Judging Criteria
For us, the most importent criteria are the following ones sorted by priority
![image](https://user-images.githubusercontent.com/101132509/158769748-2087032d-104f-40ca-8623-9e9af4685cbf.png)

### Point of Contact
Mentors
Marc Guggenheim, marc.guggenheim@sbb.ch, Phone +41 76 500 97 37 (available Wednesday on site, thursday by phone, friday on site)
Christian Trachsel, christian.trachsel@sbb.ch, (available wednesday, thursday and friday on site)
Mahalia Stephan, mahalia.stephan@sbb.ch, +41 79 449 52 32 (available wednesday on site, thursday by phone, friday on site)
Janany Nadarasa, janany.nadarasa@sbb.ch (available wednesday on site, thursday on site)

HR
Julie Brunner, julie.brunner@sbb.ch
Nina Frei, nina.frei@sbb.ch


### Time Slots at the Booth
HR is on Wednesday available.

### Prize
The winning Team get's stylish Blachen bags from SBB:
![image](https://user-images.githubusercontent.com/101132509/158331979-bd3f17f3-629f-4f06-821d-9f926cc4df0a.png)

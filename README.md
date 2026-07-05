# BMS-Segment-Board-
Battery Management System segment board. This board is responsible for passive cell balancing and monitoring cell temperature and voltage.



- The board uses the LTC6811 IC. This chip can read up to 12 cell values. For this project two boards were used to read 24 cells since our pack configuation was 24s 3p.
- Our battery has 6 segments with 2 boards on each segment for cell monitoring. The boards are daisy chained via IsoSPI. The segment boards also communication with the BMS master board via IsoSPI.

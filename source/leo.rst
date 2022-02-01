==========================
Low Earth orbit Satellites
==========================

Low earth orbit (LEO) Satellites are satellites which typically have an altitude of less than 2000km. They orbit the earth about 11 times a day. Depending on its orbit you can have multiple passes per day. A variety of satellites are
currently active. Some of them have FM transponders, others have SSB transponders and some only transmit beacons and/or telemetry (telemetry can also contain photos). LEO satellites are only a few minutes in view of your station so it might
take a bit of practice to work them.

Satellite Tracking Software
+++++++++++++++++++++++++++

Because LEO satellites are so low they orbit the earth rather quickly and its not uncommon to have multiple passes over your station. To determine the next pass of a satellite there are various software available:

.. list-table:: 
   :widths: 50 50
   :header-rows: 1

   *  - Application
      - Platform
   *  - `gpredict <http://gpredict.oz9aec.net/>`_
      - PC (Windows/Linux/MacOS)
   *  - `ISS Detector <https://www.issdetector.com/>`_
      - Mobile (Android/IOS)
   *  - `Heavens Above <https://www.heavens-above.com/>`_  
      - Website/Mobile (Android)

DIY Antenna Resources
+++++++++++++++++++++

* `Building a Dual Band 70cm / 2m Antenna <https://youtu.be/m5pLGMv5CcU/>`_  

Equipment
+++++++++

Its very simple to start playing with leo satellites. At the very least you would need a 2m/70cm dualband yagi antenna and a radio that can do crossband full duplex, or alternatively 2 handheld radios (on for rx and one for tx). Its usually
frowned upon to not work full duplex. Full duplex means that you can hear your own downlink while transmitting on the uplink. An antenna with two handheld radio's get you on the FM satellites. A ssb radio is required to work the ssb satellites.

If you only want to receive telemetry then an antenna + sdr works great. 

For base station antenna's you would usually look at either turnstile or antenna beater antennas. But the best setup is an azimuth/elevation rotator which can point the yagi at the satellite. You would then use software on your computer to control the rotator.

Working a FM Satellite
++++++++++++++++++++++

This assumes you have a dualband yagi antenna connected to two handheld radios (or a single radio that can do full duplex)

.. note::
   Make sure you squelch is open on your receiving radio

* Use one of the tracking applications above to determine the time and position of when the satellite will pass over your location. Some of the apps such as Heavens Above or ISS Detector allows you to point your mobile phone to the sky and using the built in compass it will show the start point, end point and path it will travel
* Set your radio(s) frequency to downlink and uplink frequency. Keep in mind of the doppler effect. Set your frequency about 10 kHz above the center frequency.
* Make sure your squelch is open
* When the pass starts point in the general direction with your yagi and when the satellite is in range you should hear your downlink almost quiet down. Rotate antenna to improve signal
* Once you are sure you are receiving the satellite you can call using your callsign and grid locator. Only transmit if you can hear the satellite. If you are receiving your signal you should hear your voice coming back on the downlink. (Be sure to listen and make sure you aren't transmitting while someone else is transmitting)
* During the pass make sure to follow the path of the satellite with your antenna. You can adjust your frequency in 5kHz steps for the doppler effect. This takes some practice, but its fairly easy once you have practised with a few passes.

.. note::
   Some satellites need to be activated before they can be used. For Example: SO-50 requires a 74.4 Hz CTCSS tone transmitted on 145.850 MHz to activate its repeater for 10 minutes. 
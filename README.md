# About me and my projects

This page contain description and links to all my significant projects.

---

## Bio

Mathematician interrested in mathematical analysis, linux admin. DevOPS, SysOPS, SecOPS (partially), Linux, Puppet, Bash, Python, CentOS/Rocky Linux, Kubernetes, network debugging, IaaS, IaaC. Iptables and OpenVAS user. Can't live without Elasticsearch, Grafana and Kibana.

Amateur astronomer: space imaging in bands from UV to SWIR, Planets and weak Solar System objects, small and planetary nebulas, globular clusters. Radioastronomy on wish list.

Amateur data analysis: air pollution and weather extremes, climate change.

Amateur electronics constructor: self-made PCBs, devices based on microcontrollers, Raspberry, and plain TTL/CMOS chips

Amateur 3D FDM printing and modeling using OpensCAD

Love to fly A319 in bad weather conditions using VOR/DME or NDB. Favourite airports: LOWI, LOWK, VQPR, LGSM, LSZS.

Kalimba player.

---

* [My trainings, handbooks and tutorials](#my-trainings--handbooks-and-tutorials)
* [Projects finished](#projects-finished)
    - [Flash cards](#flash-cards)
    - [Drive for EQ3-2](#drive-for-eq3-2)
* [Projects planned](#projects-planned)
    - [Read meteorogical data for Poland to cluster](#read-meteorogical-data-for-poland-to-cluster)
    - [Build UHF log-periodic antenna and do observations](#build-uhf-log-periodic-antenna-and-do-observations)
    - [Build microwave horn antenna for 10GHz (X-band) and 20GHz (Ka-band) LNB](#build-microwave-horn-antenna-for-10ghz--x-band--and-20ghz--ka-band--lnb)
    - [Build focuser module](#build-focuser-module)
    - [Build flatfield generator](#build-flatfield-generator)
    - [Build and test cheap spectroscope](#build-and-test-cheap-spectroscope)
    - [Get photo of 3C 273](#get-photo-of-3c-273)
* [Projects in progress](#projects-in-progress)
    - [Analysis of air pollution in Poland](#analysis-of-air-pollution-in-poland)
    - [DIY GOTO for EQ5 + DIY guiding](#diy-goto-for-eq5---diy-guiding)
    - [App for DIY GOTO, getting frames from cameras and platesolve](#app-for-diy-goto--getting-frames-from-cameras-and-platesolve)
    - [Make photo of Pluto using DIY GOTO](#make-photo-of-pluto-using-diy-goto)
    - [Determine star magnitude which can be seen during midday](#determine-star-magnitude-which-can-be-seen-during-midday)
    - [Build filterwheel for 18 1.25" astronomy filters](#build-filterwheel-for-18-125--astronomy-filters)
    - [Catch 67p comet](#catch-67p-comet)

---

## My trainings, handbooks and tutorials

- Puppet 4 (PL version)
- Linux basics (PL version)
- Docker (PL version)

Here: [https://github.com/lkosz/szkolenia](https://github.com/lkosz/szkolenia)

---

## Projects finished

- #### Drive for EQ3-2
  - **repo:** [https://github.com/lkosz/eq3-2_drive](https://github.com/lkosz/eq3-2_drive)
  - **description:** 2-axis drive for EQ3-2 - schema + Arduino code + 3D models of gears and cases for both RA and DEC axis
  - **state:** Finished
  - **tags:** astronomy, 3D printing, electronics

- #### Flash cards
  - **repo:** [https://github.com/lkosz/elektrofiszki](https://github.com/lkosz/elektrofiszki)
  - **description:** Write app which supports language learning process - electronic flash cards with pronunciation (from google translate)
  - **state:** finished
  - **tags:** other

---

## Projects planned

- #### Read meteorogical data for Poland to cluster
  - **repo:** TBD
  - **description:** try again to read IMGW meteo data to ES cluster and avoid last mistakes during parsing indexing
  - **state:** TBD
  - **tags:** data analysis

- #### Build UHF log-periodic antenna and do observations
  - **repo:** TBD
  - **description:** create log-periodic antenna for 400MHz or 800MHz (or maybe 1421MHz) to receive signal from PSR B0531+21 (Crab pulsar in M1), 3C 273, Sun, Jupiter-Ganimedes system.
  - **state:** TBD
  - **tags:** astronomy, 3D printing, electronics

- #### Build microwave horn antenna for 10GHz (X-band) and 20GHz (Ka-band) LNB
  - **repo:** TBD
  - **description:** build microwave horn antenna to receive signal from PSR B0531+21 (Crab pulsar in M1), 3C 273, Sun, Jupiter-Ganimedes system
  - **state:** TBD
  - **tags:** astronomy, 3D printing, electronics

- #### Build focuser module
  - **repo:** TBD
  - **description:** there is needed focuser module only after migration from EQ5 to EQ6
  - **state:** TBD
  - **tags:** astronomy, 3D printing, electronics

- #### Build flatfield generator
  - **repo:** TBD
  - **description:** there is needed cheap and good flatfield generator/screen
  - **state:** TBD
  - **tags:** astronomy, 3D printing, electronics

- #### Build and test cheap spectroscope
  - **repo:** TBD
  - **description:** build cheap cardboard spectroscope and test it
  - **state:** TBD
  - **tags:** astronomy, 3D printing, electronics

- #### Get photo of 3C 273
  - **repo:** TBD
  - **description:** make a photo of 3C 273 in multiple bands
  - **state:** TBD
  - **tags:** astronomy

---

## Projects in progress

- #### Analysis of air pollution in Poland
  - **repo:** TBD
  - **description:** do we have a problem with air pollution? Of course we have, but are there placess free of it? And which are worst places to live? Popularity of this topic is because problem growth or maybe knowledge is growing? Does this discuss cause pollution reduction? Lockdowns in 2020 caused reduction of pollution? Etc.
  - **state:**
    - 2022-03-04 download data and start of project
    - 2022-03-07 data for years 2000-2020 after cleanup, basic verification and conversion are loaded to cluster (107 milion of Elasticsearch documents). Awaiting for next verification and cleanup
  - **tags:** data analysis

- #### DIY GOTO for EQ5 + DIY guiding
  - **repo:** TBD
  - **description:** GOTO computer for equatorial mount EQ5. Goal: goto with accuracy better than 10 arcsec, DIY guiding. All cost much less than EQ6-R
  - **state:** finished, ready for publication
  - **tags:** astronomy, 3D printing, electronics

- #### App for DIY GOTO, getting frames from cameras and platesolve
  - **repo:** TBD
  - **description:** there is app needed for my DIY GOTO in addition with fuctionalities: getting frames from ASI cameras (more than one at a time) and one-click platesolving with such nice graphs like in nova.astrometry.net
  - **state:** finished, ready for publication
  - **tags:** astronomy

- #### Make photo of Pluto using DIY GOTO
  - **repo:** TBD
  - **description:** simply - make photo of Pluto, which is not easy to find, but much easier with DIY GOTO and DIY app which get frame from camera and make quick platesolve
  - **state:** finished, ready for publication
  - **tags:** astronomy

- #### Determine star magnitude which can be seen during midday
  - **repo:** TBD
  - **description:** it is said that 4 mag stars and brighter can be seen during the day - try to check it
  - **state:** finished, ready for publication
  - **tags:** astronomy

- #### Build filterwheel for 18 1.25" astronomy filters
  - **repo:** TBD
  - **description:** I need filterwheel for my 18 filters, which for reasonable money
  - **state:** finished, ready for publication, corrections needed
  - **tags:** astronomy, 3D printing, electronics

- #### Catch 67p comet
  - **repo:** TBD
  - **description:** Catch 67p comet and make a movie
  - **state:** finished, ready for publication
  - **tags:** astronomy

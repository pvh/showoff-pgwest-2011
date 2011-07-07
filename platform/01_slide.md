!SLIDE
# Cloud Service Architecture

!SLIDE bullets incremental

# Cloud Computers

* Computers are free...
*  ... but running them is expensive.
* You can have it now...
*  ... but it may disappear.

!SLIDE

# Computer = Transistor

!SLIDE center

<img height="500" src="/image/platform/computer.jpg"/>

!SLIDE

# =

!SLIDE center

<img height="500" src="/image/platform/transistor.jpg"/>

!SLIDE bullets incremental

# Whaaa?

* Don't try and fix a transistor.
* If one transistor fails, throw it away.
* If several transistors fail, fix the supply process.

!SLIDE bullets incremental

# Treat Servers like Transistors

* Use a reliable method for creating them
* Keep them simple
* Replace them if something goes wrong

!SLIDE bullets incremental

# Deploys are Hard

* O(n) worse than O(1)
* Well understood, minimally unique servers
* Heroku app for central control
* Outside-in management of servers
* None* of our code on the server

!SLIDE

# App Architecture

<img height="500" src="/image/platform/architecture.png"/>



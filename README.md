# node-red-contrib-liveobjects
Live Objects ((http://liveobjects.orange-business.com)) contrib to node red.

Forks of mqtt and http-request to use corporate proxy if env.https_proxy exist.


<h2>install from scratch</h2>
clone node-red

* npm install

* npm run build

install node-red dashboard
* npm install node-red-dashboard --save

install node red contrib Live Objects
* npm install https://github.com/brusand/node-red-contrib-liveobjects.git --save

run node-red
* node red

<h2>composants</h2>
* lo-auth
<p>authentification sans cookie. set credential with  LiveObjects  login/password </p>
* in/lo-mqtt
<p>subscribe mqtt</p>


* output/lo-mqtt
<p>connection/publish</p>



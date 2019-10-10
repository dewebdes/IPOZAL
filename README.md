<h1>MAX POSSIBLE SPEED, SECURITY, SEO, RANK & BIGDATA</h1>
<br>
<h2>The IDEA</h2>
This is a total solution for Booking & Reserve Services for Local Bussiness.
<p>This will find all famouse brands in target area, grabe their bigdata and SEO them as hidden and attack them as paraller task to make them weak and try to steal their users data...</p>
<br> <br>
<h2>Find Local Bussinesses</h2>
With this repo <a href="https://github.com/dewebdes/walker" target="_blank">WALKER</a> you can find all websites that works in an area.<br>
For example we found <a href="https://github.com/dewebdes/walker/blob/master/dusseldorf-websites-in-map.txt" target="_blank">Dusseldorf</a> with this program.
<br><br>
<h2>Grab BigData</h2>
With <a href="https://github.com/dewebdes/ARRP">ARRP</a> repo and combination with some tech like <b>Burp Suite</b> we can get and save the big data of local bussinesses.<br>
For this perpuse if the firewalls block your requests then we can use <a href="https://github.com/dewebdes/TFM.BOT">TFM.BOT</a>...
<br><br>
<h2>Template Engine</h2>
Users can easily create and update their bussiness pages or they can upload it in simple html web hosting and connect a domain to it. Visit this video for more info:<br>
<a href="https://www.youtube.com/watch?v=M2BsyRRU5Cg&list=PLMviqVvxDuPGID47AZUzWm-cUvGSX2seE&index=2&t=0s" target="_blank">DOMINO TEMPLATE ENGINE</a>
<br><br>
<h2>SEO Engine</h2>
<ul>
<li><a href="https://www.linkedin.com/pulse/save-your-templateengine-seo-champ-2019-kevin-eyni/" target="_blank">HIDDEN SEO</a></li>
<li><a href="https://www.linkedin.com/pulse/seo-exploit-kaveh-eyni/" target="_blank">SEO EXPLOIT</a></li>
</ul>
<br><br>
<h2>Overtake From Your Rivals</h2>
There is an under develop repo name <a href="https://github.com/dewebdes/ZeroPen" target="_blank">ZeroPen</a> that can:
<ul>
<li>Unlimited Scan target hosts with pro bypass firewalls techniqes</li>
<li>Try register exploits for zero day</li>
<li>Try steal their database, specialy users contact info</li>
</ul>
<br><br>
<h2>Users Data Entry Mode</h2>
Users download their template engine base on select bussiness category and after edit the template upload it to server via an attachment in email. read more <a href="https://www.linkedin.com/pulse/prohosting-automate-apis-mail-kevin-eyni/">Automate Via Email</a>
<br><br>     
<h2>SPONSORSHIP</h2>
I have all the Knowledge, but have not enough money & time for develop it by my self and will be glad to have a sponsor :)
<br>
Keep in touch with <a href="https://github.com/dewebdes/RESUME/blob/master/kaveheyni.jpg" target="_blank">ME</a>
<hr>
PWA Version:
Download PWA.zip
npm install
npm start

WEB Version:
need apache2 & PHP 7.2 Host
found undefined urls from ico folder, correct paths and urls

ORM:
npm install , after extracting files
npm start , for run after customization
u can set a domain name in apache site-available to a port that ORM listen to it:

<VirtualHost *:80>
     ServerAdmin admin@example.com
     DocumentRoot /var/www/html/wordpress/
     ServerName telnet.center
     ServerAlias www.telnet.center

     #<Directory /var/www/html/wordpress/>
      #  Options +FollowSymlinks
       # AllowOverride All
        #Require all granted
    # </Directory>

     #ErrorLog ${APACHE_LOG_DIR}/error.log
     #CustomLog ${APACHE_LOG_DIR}/access.log combined
ProxyPreserveHost On

    # setup the proxy
    <Proxy *>
        Order allow,deny
        Allow from all
    </Proxy>
    ProxyPass / http://localhost:6907/
    ProxyPassReverse / http://localhost:6907/
</VirtualHost>


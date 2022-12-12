<h3>Microservices Security with Keycloak</h3>
<h2>Part 1 : </h2>
<li>Download Keycloak 19</strong>:</li><br>
<img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k1.JPG">

<li>Start Keycloak with </strong>: <code> kc.bat start-dev</code></li><br>
<img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k2.JPG">

<li>Create an Admin account</strong>:</li><br>
<img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k3.JPG">
<p align="center">
  <img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k4.JPG" class="center">
</p>
<p align="center">
  <img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k5.JPG" class="center">
</p>
<li>Create a Realm </strong>:</li><br>
<img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k6.JPG">
<img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k7.JPG">
<li>Create a client to secure </strong>:</li><br>
<img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k8.JPG">
<li>Create users </strong>:</li><br>
<img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k9.JPG">
<img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k10.JPG">
<li>Create roles </strong>:</li><br>
<p align="center">
  <img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/K11.JPG">
</p>
<p align="center">
  <img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k12.JPG">
</p>
<li>Assign roles to users </strong>:</li><br>
<img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k13.JPG">
<img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k14.JPG">
<li>With PostMan </strong>:</li><br>
<pre class="notranslate">
- Test authentication with password
</code></pre><br>
<img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/kp1.JPG">
<img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k16.JPG">
<pre class="notranslate">
- Analyze the contents of the two JWT Access Token and Refresh Token
</code></pre><br>
<p align="center">
  <img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k17.JPG">
</p>
<p align="center">
  <img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k18.JPG">
</p>
<pre class="notranslate">
- Test authentication with the Refresh Token
</code></pre><br>
<p align="center">
  <img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k19.JPG">
</p>
<pre class="notranslate">
- Test authentication with Client ID and Client Secret
</code></pre><br>
<p align="center">
  <img src="https://github.com/Amina-contact/Microservices-Security-with-Keycloak/blob/master/pictures/k20.JPG">
</p>



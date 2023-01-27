# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

Design Steps:
Step 1:
clone the github repo into theia IDE

Step 2:
create new django project

Step 3:
write the html codes

Step 4:
run the django server and execute the html files

```
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>GUINDY</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>SAFEEQ FAZIL(22008366)</b></font>
</h3>
<center>
<img src="/static/images/nearmemap.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/ghs.html" title="Govt. Higher Secondary School">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/rto.html" title="RTO Office">
<area shape="circle" coords="400,350,50" href="/static/html/vk.html" title="Guindy race course">
<area shape="circle" coords="400,200,75" href="/static/html/bus.html" title="Hi-Tech Bus Stand">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/park.html" title="Eco-Park">
</map>
</center>
</body>
</html>

```

bus.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Bus Stand</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>GUINDY</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Hi-Tech Bus Stand</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
A largely industrial district, Guindy is also home to Guindy National Park, 
a tropical forest inhabited by blackbucks, jackals and dozens of butterfly species. 
Pythons and cobras are the main attraction at the Chennai Snake Park on the edge of the forest. 
Nearby, St. Thomas Mount is a Christian pilgrimage site, where the apostle is believed to have been martyred. 
The site has a colonial church and panoramic views.
</b>
</font>
</p>
</body>
</html>
```
park.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Eco-Park</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>GUINDY</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Eco-Park</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
A very nice park near guindy bus stand.  
Very superb calm place in guindy. Best for walking. Nice playing place for kids.
Well maintained with jogging track. Source of ground water.
Good place play with children.  In Banyan Tree lot of parrot stay like house. 
Good sound and Air. Lake view park looks awesome.
Very nice place at guindy.
Simple and relax with play area.
</font>
</p>
</body>
</html>
```
rto.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>RTO Office</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>GUINDY
<h3 align="center">
<font color="blue"><b>RTO Office</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
RTO office or the Regional Transport Office is a government body specifically established to oversee all transport-related operations in the country. RTOs are located throughout the country in each state and union territory. RTOs are responsible for enforcing the rules as laid down by the Motor Vehicle Act of 1988.
The department also maintains a database of all the vehicles operating in the country as well as issues licenses for drivers. Besides, the RTO office also collects road taxes, supervises pollution checks, and ensures the enforcement of all road transportation rules. If you own or drive a vehicle in India, you will need to visit the RTO to get your vehicle registered, obtain a driver’s license or renew your driver’s license, etc.
RTOs are also responsible for improving road and vehicle safety, especially to avoid accidents and other road fatalities.
</b>
</font>
</p>
</body>
</html>
```
ghs.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Govt. High. Sec. School</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>GUINDY</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Government Higher Secondary School</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The main objectives of guindy Government Higher Secondary School are 
<ul>
<li>To impart proper and qualified training to teachers and give them an attractive salary and incentives so that they are not tempted to quit and look elsewhere for jobs.</li>
<li>To provide financial aids and grants wisely and judiciously.</li>
<li>To Frame of syllabus and curriculum.</li>
<li>To set aims and objectives of education.</li>
</ul>
</font>
</p>
</body>
</html>
```

vk.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>GUINDY RACE COURSE</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>GUINDY</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>GUINDY RACE COURSE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">

    The Madras Race Club was officially constituted in 1837. The club functioned till 1875, 
    when the Prince of Wales Edward VII visited Madras. Racing again went through a tough phase owing to financial reasons.
     Finally, in 1887, the club was revived. A balance of 11 rupees, 13 annas and 12 paise was carried forward to a new club called Madras Race Club
      with 50 members in January 1896. In 1887, a public meeting was called by Lt. Col. G. M. Moore, one of the stewards and it was presided over by
       the governor. New stewards were appointed at this meeting to run the club. The funds managed by the stewards of the Madras races were handed over
        to the club. The Trades Cup formed part of the racing programme proving that the traders patronised racing.
</font>
</p>
</body>
</html>

```

## Output:

![map a](https://user-images.githubusercontent.com/118680361/215143225-3ba3912b-a93b-49b4-924d-81641f3d1690.png)
![map2](https://user-images.githubusercontent.com/118680361/215143295-e11cd27a-f6d0-4265-8068-25f696781b67.png)
![map3](https://user-images.githubusercontent.com/118680361/215143365-f8077709-779a-4121-8063-4d4fa119b285.png)
![map4](https://user-images.githubusercontent.com/118680361/215143394-f1a80360-78df-4c0a-bb3e-65ae3ce6575f.png)
![map5](https://user-images.githubusercontent.com/118680361/215143440-bb3967ac-4fe6-4eec-8d42-4bafe479cf26.png)

![map6](https://user-images.githubusercontent.com/118680361/215143485-682a6e58-ba86-43a8-9dbf-93609479c391.png)

## Result:
successfully created a website to display the details about the places around me


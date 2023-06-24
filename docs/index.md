About me
========

I am Payal Debipersad. I'm twenty years old. I am a mechanical engineering student at ADEK. I wanted to learn more practical skills, because we don't do that a lot. We are more focussed on the theory. That is why I want to do this course. 

![](https://lh6.googleusercontent.com/98ovlR7i_LQPeCCsVmqZ4beQBaor8W_HHrKoCvYidRr20q0XC_E8C3FMMAsjDApvsVwepbNCLh54CQFDDm603r-9BXN2OLvLGbTCOxaj9Zv3G-SacjqiU8NQAeTYBiKwGQ61ANqJJGV1jNJJMjb9rpU)

Day 1 (10 februari 2023)
========================

Objective: Project management

1.  Create a github account (<https://github.com/>)

2.  Create a repository 

![](https://lh4.googleusercontent.com/QrvQTvp3jR6-E1ZhlYo4N4QsHAdr1DuWKs7WaUUdd0OxwYrNqXAiLdFhFV5VkAzCUYvDerd0XuNGmM4NwV_kyfzP-8TPF4fOwiIP8IvHAxz7BA0xcXLCXVWjIJItkgSi5apf1-PaYIm857CW0dv_fyU)

1.  Download github desktop (<https://desktop.github.com/>)

2.  Clone your repository in your github desktop

![](https://lh6.googleusercontent.com/7n9uSx2_p8Zatd2a08Up-tcgyVxE6ueckP6ErvmYQ_vQ6LuEoR7R6dY0O3KcaMj9T9UumVKu1bX4an-bU9DLCGxd24_TDgQKkUjp13Ri4hEoqkeXWUKZKL2V0qSPoBTTs28fVqKt9WdkFHzlUxgEvqA)

1.  You then get a file "Github" in your documents. 

2.  Then download the clone repo and put the files in your github document. (<https://drive.google.com/drive/folders/1rEbBA5UYhnrQrHGsEiU3D2dWEZyIuBi2?usp=sharing>)

3.  Then you need to push the files online via github desktop.

4.  After that you will create a link to view your documentation. ![](https://lh4.googleusercontent.com/vTnVDXZD5IE0r2SeWQ6MaCd5sfEMbpRB6MYIEpKpEW-NsFc54jOuWl0ow2C-d4GQPmtRfDYNppP44CoTlV_kwjejVa4gOCVeVdgLAmHrdYyrnQJzzpIGyJ2IIo9BIVU6fEB0Sk3ovLUtQnAUtkJxWw0)

5.  We can make changes online or offline. 

1.  If we do it offline, we need to do it in markdown (<https://www.markdownguide.org/cheat-sheet/>). We can also just do it in a docs and with a link we can convert our docs to markdown (<https://euangoddard.github.io/clipboard2markdown/>). We need to copy this code in our index.md file from our github document (Customize it with notepad++ <https://notepad-plus-plus.org/downloads/v8.4.9/>) We can also instal a markdown viewer in our notepad ++ to see how the document looks before uploading it online. And finally we push it online via github desktop. We can view this on our link.

2.  If we do it online we need to work in the index file and use markdown language. And if we are done we need to pull it offline via github desktop.

Day 2 (16 februari 2023)
========================

Objective:  Interface and Application Programming

Setup ESP32 in Arduino IDE

SPIFFS

Host local dashboards

1.  Interface and Application Programming

Here we have a connection between components. They can "communicate" with each other. U can control it from your dashboard.

1.  Setup ESP32 in Arduino IDE

![](https://lh5.googleusercontent.com/rwbM7znjEwdxrmxfM-5rJ9jhityqJvDZolF2Omde_WCfPYmkhOuafeHwx67JzI7E6tCCDhfoDeutiRkbCGJrXy4U9as1PBLI97FZIAUdbKwhedNraqMa903cNmrakw155d5Ka0u69vOUZYBlQthOnrM)

Paste <https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json> in your additional board manager in the preferences of your IDE.

![](https://lh6.googleusercontent.com/Hfl7hJF1oPBvnTD2SfCzWpTj0b2TyWKmu2D4cYEIzGRiXTsiCSrQyoxF3bB2G93YIF-B90H_KiBCba7d6ozfiz82B_9AD94CUpGgGLnGo_imNOrkiaa-SZDgNR8vaFQnmNFgfM27VOxwQCh-fZgIiik) 

Then instal esp 32 on the board manager.

1.  Now we are going to instal a SPIFFS file. (<https://randomnerdtutorials.com/install-esp32-filesystem-uploader-arduino-ide/>)

We download the first one, unzip it and put it in our arduino document in a tools folder.

![](https://lh3.googleusercontent.com/H6cQwz57kx3lm6p61vHW6vIn6k2fL1UvHe0TX9Wwai2_NveA67iSAyGdn9nfIxb18q4gcvVTmRsyWQuS6poj9tcu2BSqSYBkuw3OTIFb_w-ynFkRv3iK0w6kGGwF0zpb98s25RhToNKrfowcyUf5ioE)

Now we download the SPIFFS data folder <https://github.com/RuiSantosdotme/ESP32-Course/raw/master/code/SPIFFS/ESP32_Async_Web_Server.zip/>

We need to unzip this file and put it in our bootcamp folder. In a code folder we put the files. 

![](https://lh5.googleusercontent.com/Q0n4cwlX0CQHnU7SoXoenmLWNixyKIwFiEhAZtELKhCZaLAOaX5H48QBabk9tts5HCs2g8ig_mFnFcS1uyZ4dZgXf7KGsyDy0y4dI10-SAJn1OS4vbJrS8oxozYg7J4NONnpMObJkuJCSfaVzocivE4)

Now we need to instal libraries. <https://drive.google.com/drive/folders/184_RwUj3iOGNeZ4GtvciJrSK2s-s0FCY?usp=sharing>

<https://github.com/me-no-dev/ESPAsyncWebServer>

U need to put these here. 

![](https://lh5.googleusercontent.com/mzMmhbkGnmEZAHWWerIUntXo6Py2F_LFLQz20Bg519hLVxVp7IMMtcH44HdnZlF78SFtZI7Jmzkeyje_G_UVJojcIuLvr7c9FX_UTY01XL7vPYW8Nv6qnCphMGH5xExZC0Fudv9BvLtRwCYb8w3VmBA)

1.  We open the code and customize our wifi and then connect our esp32. We verify the code.\
![](https://lh6.googleusercontent.com/FSA3ceevp-w9321n2nRo0C18mi_9va5Mfq52hRAhEL9JLouEvgho8vZ2x3k-Q4E9DF_GGwUR_Nv_oSLNAUBlVAzIAi35_UC2jf7GVRjpOwlGF9hJ-i6VYMUrP6MclNfwHamUjkbPgSPszHRP7Y4m3B8)

![](https://lh6.googleusercontent.com/RnrhGOkPkwNiz8PYjmysPIPiyZm2jCOJIRNNYQ9PUyQXAcQhMZ0xVkIDubcv_j58Jx6BhPqWsE1odrZwHOvCRxUOaIZyfbH1V_OK4HRVj3z6c3bo2jCCiTJ8gId1JIGw5wz7afYQ8LM0bJqGzwxD7lA)

Then we go on ESP32 Sketch Data Upload. After that we open our serial monitor and click the reset button on the esp32. 

Then we're going to get a code that we need to paste in our browser. We can then turn the light on the esp32 on and off. We can also add an led. 

![](https://lh6.googleusercontent.com/qliBkOALX2RX3oDgIE0lHeN-8B3LBK8P1jXYOtoE2JJux7Uc8kyQBJOJIGq5ndk_DiuAUluXjr6HEWYLt2AOsDMyGTI5dOvWBBz0CO8xw6pZSDUhsQ-3AaF8QneN_oPzqbRbAe4RsArtnq4hg9qjfDY)

Day 3 (24 februari):
====================

Objective: Multiple Sliders

First we need to download the library (<https://github.com/arduino-libraries/Arduino_JSON>)

And put it in our libraries folder. After that we need to download the file with the code.

We find that here: <https://randomnerdtutorials.com/esp32-web-server-websocket-sliders/>

After we downloaded, unzipped and sorted all files, we open the code. We verify and upload.

 ![](https://lh3.googleusercontent.com/dCB4s3rzfzk2uMnN5QHq2x7KaLsXKNFfG1P2o4EU1MnUE5kVCCd7jpTdPW9P4Xthhq3FR5T6wpAGfCzhVfptpkJE18j-iv54CpOrvnmYFcjyJhi_VUltVS4RuFqm1QomBIYdxeD9yPd4tYVcDnzaNWc)

That will eventually bring us to the webpage where we can control the brightness of the

sliders.

![](https://lh5.googleusercontent.com/UA_sBRRW1JWYY-RnKUhB8aArpeYIHTXbxCfN3bea47YAtYxLRg6ZTbPOZXlhyqXNO0_rGwZ-IekTmlMBEzm8BtECmV1g5H_JHYh5GKhAfeZZZogWFMHqXL8mm_cr2s3-zMgduoHEGaJPRc_bQ2zuLiE)

We can customize this page with our data file. With index we can change the text and with

style we can change the colors etc. 

We can make changes online (inspect), but if we want permanent changes we must do that in

our files with notepad ++. And then we have to upload the sketch data again.

![](https://lh5.googleusercontent.com/orQc5PuuMYOnKICi5VhFbqRws1pMfbjgPQohSMTYVQy6HtaIdl1uATJh2x2RlIFAe2z43_uEqgJH3sX4EuPCSklvsJBWcGNFXYD9VW3kE0u12kqtWFeikS9dy1TZZSAMZTXEgLVl6sSCSL6JXsOCPy8)

![](https://lh4.googleusercontent.com/zikIke4-GwMFXFvhgG2h3Jdkyhu1y8ugQO86WbAJW7edaV8XmDqBcKJKGdgDKJVfRZOPYiYMd7Lkr2_CgX8XnPZU7rPl9j9nrrdIdgp0cdMgfBE7mjZvaxB_83XWiOdMFOsxLHZnTYUnIL-u3T1-NGc)Day 4 (3 march):
================

Objective: DHT sensor

We needed to follow the steps on a website and then set the DHT sensor up. (<https://randomnerdtutorials.com/esp32-dht11-dht22-temperature-humidity-sensor-arduino-ide/>)

We then needed to install 2 libraries. It could be done in the arduino IDE itself or with a link.

<https://github.com/adafruit/DHT-sensor-library> 

![](https://lh5.googleusercontent.com/ShfU3AIm6IU4zwi6c4PCPUAjREgrjs_NANgvwRcTrYivGTRHD2aZQT1zJSlkHqFNaKwKWu19fsCsMFitzGI-Pxh6p8uJGu3cSONSlal-I8MEDApwuwiwP6jcF3SBgK-Z48ISBU50SSnIJ6MP0SMJCVE)

<https://github.com/adafruit/Adafruit_Sensor> 

![](https://lh6.googleusercontent.com/Kf8aadUH0DwlmDoAKxXB3DezGEcNUsrVPwKCwcrufjt9gzV8UL-9HBAq5UQJGQNLjvHMBhEGr4RGW5jWigGHbxOTdNwojpt47UJ8ZfpQIR9_q4lNUd5b-DtKFIu6ODBReoFWc9-FM0vIAEgInJFbCnY)

Then we needed to copy the code from the website and make some changes, for example we

are using the DHT11 so we needed to comment the rest out. And we also needed to change

the baudrate to 115200.

![](https://lh3.googleusercontent.com/WxvLrGKeka_tJwtoABBr0W-gT-HRLKzva-CnGk6PseFAeY0-TXTohOooGRIqgtrQchlwG5PYL5ACqwPES32QhywOO8FiwXdEzJJVfHos0t2_5GAkLslkIqgsbY8i0UsXmQEhXzFJXwgSTX0FhgfOo4Y)

![](https://lh6.googleusercontent.com/XjAxWTzIwIgY3Dpoz9T6vsh999u75DXoq9odp_L2nPGdgFmMSJQ3fzwUBhx3x2B45hpuSTNksPslUdYMrUIthRkjanom7onH-AD2BeXmy-qW2auOpeBnqOkONriwjGr0UDyQsWxeTLjoUme8nVIYj_w)

If we want to make a web, we follow this link. <https://randomnerdtutorials.com/esp32-dht11-dht22-temperature-humidity-web-server-arduino-ide/>

It has the same steps as the previous one. Only this one goes further and we get a web. 

![](https://lh5.googleusercontent.com/6Xk_cVISxOw7PKvsHLZOY3t4qP2U-luleLNmDKKCPabEWctgs27mi_mseLeKsDnE5sV6Yu5YWND0oqe3__N7h0CTpqLvMVLdHOW85HIPiYAOYG73_qhr5lLq7kUzjVlsaCmQnSjjA1__iA18wyeOVss)
Day 5 (10 maart):
=================

Objective: MQTT

First we needed to make a sketch of our architecture of the ESP32 with the web server and

what happened between them and the LED's and DHT11.

![](https://lh4.googleusercontent.com/nfxVtUXPTz4C8_9CGDHTNgMNIFHWtzUKh1s0d9gN7G3tx_he192-QIUhAvgHG2OeEKm8ukNC2ZIz-BaLulV5Ga1EfCCz5yapx2XYRz451YSbUz1M35HyYQj4-ij6QYfsKYEt5UseA-Rjvc_l7udKgk8)

Then we learned about MQTT. That is a broker which we can use to get data not only when

we are locally connected. (<https://techtutorialsx.com/2017/04/24/esp32-publishing-messages-to-mqtt-topic/>) 

We copied the code in our arduino IDE and also downloaded the PubSub library. 

Then we made some changes in the code.

![](https://lh4.googleusercontent.com/t_AkypiqAZY4Vd91EbdoGl6fgwjXoT0qIWKYDKPhKICv2OGz8RQK3HbIQSWqehEs_gugVHjT8MnpwkP26xXAgXXgOV7CxBoym15RI3J9mQOrkiKglFJMnmIqgbzL5l7IQUSlNToik4X_Cy7tDLErxcM)

Then we downloaded an app MQTT lens (<https://chrome.google.com/webstore/detail/mqttlens/hemojaaeigabkbcookmlgmdigohjobjm/related?hl=en>) where we can see if the broker is actually getting our information.

![](https://lh6.googleusercontent.com/mVLOyapR0Owrmtl8WY1iAwiS4HdnvsRVf7z4cnAc95fIN93ZHBBUmMk3hWIs2Pl34qrDb8GlRqm1lZ3J-BMVbWTDn14W12fuOCafVMJvJMoE5oJ5rRpnf3JM8yYwsVFEzmDlzhbO1286sQs09mGQ7Jw)

Then we should fill this in and create connection. And after that we should see our messages. 

![](https://lh3.googleusercontent.com/liIHFhxyiyQzON1WmhwQuHFUJJiPfhCDfTFZ2QNwIuvKm9D1SV9TmYT4n4j3OrIb4bAj7MGpKK-dG_ORUwG4M3Aw7IR38RTpA7vafv5rWYbVxX5l7sWgVhhFknTPTcvU2vWb4rgQIL5EjDtiPC_R9aw)

Day 6 (24 maart):
========================

Objective: Use a dht 11 with mqtt without a web server.

Make a chart from the dht 11 readings on a website.

Without webserver: 

<https://docs.google.com/document/d/1gPfp3f9jbAcFxe7KjdTmtqzEG3QMySqYnl7Sw4jvW3E/edit>

Use this link to find the code and customize it, for example change the ssid, password, etc. 

![](https://lh3.googleusercontent.com/U5b9shpnOlCRtNRwJ0hkxs0OFKqOWC9NYn8s69Ks-6ZUdp-FLcPgtqIRgS9aKB8X3i8F2avcKFgA0Bt5UNmPnfFfpaH_1694l2bNpvb62rUDl9P7dzySadOVcrRcLNeYUSRk4iyU-SD05oakVzDvJ0c)

Put a delay in the loop so it doesn't send readings the whole time. 

![](https://lh4.googleusercontent.com/YpB5OBaVVocKScgspDZCbwqBChpq7_w4kin32iWKplz6SXFQ4jEzOX5fc1Kgggo8uCZZ6el55sKJvbVt9fs1RRpIhPPQ_n6W5PkoCexCisZGO5el3uVnJuqZx-Ml-AnoiuJjPJxxyIFE2l9twY8gXNc)

And after u get the readings open google lens and subscribe to the topic to get the readings.

![](https://lh4.googleusercontent.com/dQ2nfQ1xPPPpS0XCSn7p5hmIAQ6CPRF8uBFMvNWaNfHG-4jAIHH1qCGUkWjUWLt8WKlowmkANFqPF6XSLsA5zSnE1o770s4Tls-V1LBhFil3XdxYdFMk2vnerd2T7Udv0UdG1JkpVLcgGspFj2xRkyw)

With webserver:

Use this code:

<https://christovitohidajat.medium.com/esp32-chapter-9-dht11-readings-into-plot-charts-c4c23ad367ce>

Upload this to the data folder:

<https://drive.google.com/drive/folders/1t4b1LoQOsgiVcrTlII5oBtyykfoiGETu>

![](https://lh3.googleusercontent.com/8EGittwAKMVmfEsr3SXro5AEGXYRzCpXWJivRlP-QemDBEtXqTwVEUvMbk2qnX-2RSQ5LHoPJyAiv-dMo9HRpNqI82oUmY3VkW41WXyrzadUwOQr6IjKMf6w1v2TdDg-1sTFy65eu2z5ne6KlefrYeE)

Homework: Merge the 2 codes

![](https://lh3.googleusercontent.com/3j1Xpd1VjLLLtJHwpTZQLoie-x7p1Yt6iq_8ATIqey76lVp2N--DKZXhpuE_sS4l7X2B2R8PvMPWNzw6BNwkjUBTGxX7zEOfVZAVn-JdpGPHrI2zPpNF8KySq1NuT5NDSXyv2XgMG-f67zVxEIFdaw4)

![](https://lh6.googleusercontent.com/JnNTcOuO1wAwigp7y5CWvcVVzowjZMZFMpgB_aZfCDXPSZSJrba1MFon-MR6Z7qDaiI6NmgMoXLfFh0dxbd5JMmRFK2p9RWQAY-hX4wR_7yi54Cl1jObqfpQboh15JIZykQFL-EgsCsEXzBlJz00v7k)

This code can be found here:

<https://drive.google.com/drive/folders/1baNGJn1iqDRwBRcPfCrvaDBQtK0e1ZpA?usp=share_link>

(There are some things wrong with this code because I accidentally changed it)

We need to host the app with the 3000 port. It listens for requests on the port 3000
Day 7 (14 april):
=================

Objective: Using a website and mqtt

Setting up the nodejs environment.

Async- steeds data sturen zonder te vragen

Sync- steeds vragen

Using a website and mqtt

From here we can see what the code should look like (We need to customize out dht11 code 

with a chart to this):

[https://drive.google.com/drive/folders/1rq81PdjlsMFowDBo4Yq6Y9wfd-yVzd25?usp=shari](https://drive.google.com/drive/folders/1rq81PdjlsMFowDBo4Yq6Y9wfd-yVzd25?usp=sharing)

[ng](https://drive.google.com/drive/folders/1rq81PdjlsMFowDBo4Yq6Y9wfd-yVzd25?usp=sharing)

The code can be found here: 

[https://drive.google.com/drive/folders/1PbQDKlbBgO13EbzaJ1OUKS2B9bKxRu91?usp=sh](https://drive.google.com/drive/folders/1PbQDKlbBgO13EbzaJ1OUKS2B9bKxRu91?usp=share_link)

[are_link](https://drive.google.com/drive/folders/1PbQDKlbBgO13EbzaJ1OUKS2B9bKxRu91?usp=share_link)

The results will be like this: ![](https://lh5.googleusercontent.com/0VUFtpaW0gn1zXAjjF9Fk6lSqmHyC3NGOObO1wFEw_DK5NwODoNQS_6y9r8aA376Z7J6Bx1WnVxBsSneuAAMnTpkfzxE33bFtCUY1XKp672jBQVhUKd-0c2uylTZ2k4bi_81TVGvmqigADZuNoqHXTc)

![](https://lh3.googleusercontent.com/Qb_mAXNYS9CFDGtCQgrvK42HeFeoZu5-4c13a7TuaSdZs6Rj6QNcPDE6zSteWQMdzW7l1aeSkI-eF5_j-jmUkRbVajVgiCiSAddoFtIvGNKhtqh_MUQARRlA29AvSW9J44jzKqFgDeg7vc4ekXDtzyU)

![](https://lh5.googleusercontent.com/T1MRIl1qMM8SMHq29B9TO-y6WzkdmgrGgV5pz5zPnO37wCMSbCf_u3bfsDcu9G3xthPpfyfeg11e13ag8XW0wyDY8V94vnt-kOApS2FqSS2-c8dGhik3uaMKp850cmmlOOaQAKUDBkv73tcQNGmvCgs)

Setting up the nodejs environment

Download Nodejs 16.0.0:

https://nodejs.org/en/download

Mosquitto for windows:

https://mosquitto.org/download/

Put your nodejs here(Make a software folder):

![](https://lh6.googleusercontent.com/DdE766DuFrnCKR-5Lifa-Y_MGgipzLVv9QAR0jDX-bvV1If8uD3R9P35RfLlneBu5e_TMlz4WVjOItsQAH-GHuA4PwQkGbMLAMO_YJMpxtQeMzsHI0hpY0cuAHzcdV-OvoarWKAibjYEjU2xYHSzgGE)

Make a nodejs folder in windows c. In the nodejs folder you should make 2 more folder called "projects" and "node_modules"

![](https://lh5.googleusercontent.com/7c0RjfpepkKbUy5SKSL2jYHbaA6CSSCTZj7qEzejOeprs8oQcwD_hj4SRZbM-scRF2cwSqeRO2vm4nXIugUYpnEffyFBE6gO-f9lrcQVemeAXXgj1hUVAM1aLMmTxcKqp3n6WmAifEggo9Va-1mYJ7s)

Then you download the mongostack folder from here and put it in the projects folder: 

[https://drive.google.com/drive/folders/1rq81PdjlsMFowDBo4Yq6Y9wfd-yVzd25?usp=shari](https://drive.google.com/drive/folders/1rq81PdjlsMFowDBo4Yq6Y9wfd-yVzd25?usp=sharing)

[ng](https://drive.google.com/drive/folders/1rq81PdjlsMFowDBo4Yq6Y9wfd-yVzd25?usp=sharing)

![](https://lh5.googleusercontent.com/q7J7SMr1PHk0R0aXpalXedsRKMAgxJhcBihaRu44SWbJk41Kb7jdrEGzOa5fnIBLNqqJJVNFcJi2VO80b7AA6Ghb8t1fmW4wrRL5dQ-U7QnkDl0HNSoJ5bXAknqpAu_J1jPxHUN7ZUPFtYZ-ETkJ5DI)

Now we open the app.js folder with node++:

![](https://lh3.googleusercontent.com/oV5Sq0pcWjtuS3w9NQwqrkjB99wYujxNJbieBLeibcYIAYafZ3IvdEWe4flFsBsrX4vRA-mEsDeAjQC9hRSftXcr3Fqo-LNn0OeKDvIV4iXA1HnoUU98drxeyHc6B09kzXF0Cn3sTexDkOvxoECjx8E)

Make the changes to var client and client.subscribe:

![](https://lh6.googleusercontent.com/Xpgo6KOP2m-TvLTK2-H5Gf4ds8FFhwL6XaY2oHodqzxm7eUDaaAqp0ayyeSfQ3F14r4DVWALrinJ1G8ek-kiE1mq04bZyQi34x_FJlPDjwwPAAUucwqVle2aqb_9AmE6ytxGYrJ3c_k748WFM3LElWM)

Then open your command prompt: 

Go to the mongostack folder and the node app.js

Install what is necessary. ![](https://lh6.googleusercontent.com/fboxnJKi_LvtJEZrt1J4_VPi7x0LNRWF2VHC7kXprurgWoELQg0L52VyBDPwEi0QxV72_oqvxRecvpXnJNfw5aeUrlYu9EKcyIjqtZenSre69qEAIE3nOAVBg9hMqui8rIeYVNHQfg_WcO91xyUGz4k)

![](https://lh4.googleusercontent.com/uJiwtzecxcuwXPJlLXAQDoU_iF2q0MJDqKJM1811R1K0ShsrhL4LXGZvm08o4OUwspLrTMISq4ItEkBwjPDDutOqwVPTxA2wPbf9JSo1jRCwIXKBRcxxw2Pehcpfz0hlF5nQZFOwxq1KiN3AAVElMeE)

![](https://lh5.googleusercontent.com/DcwCKcE7L8tNKIsu6TRkQohtqu_5YtHTjF1xCFZs3j98Et5EnbexroZQ5DSmmLDKbjUKFTuuUoMlZgZ0O21XFk0Nuw4RB_pYLdvAUMydt6KFpMMoQW-EWmQFnLEhlhkVDOkPRX220uKanqmiNDpDAiA)

Search for your IP address in your command prompt with ipconfig:

![](https://lh5.googleusercontent.com/-bA_bwbcbbbZx-t4bKteLepINOiFMTn-JadsMxosmkj3DWwmSX9urw_ukqLbiK9Hgp8nrwk9gERVlX58EGiHdtjlQqkpxzy1rn0J1O8hkqflQGY4fZDdWNfusfVY_S87ATfe_OZN37Ab3XnVMhbGlE4)

Then download a test.conf file and put it in mosquitto:

![](https://lh5.googleusercontent.com/525Q5GgCStEddgyH1N-jlFEA2NdbdNILnguuI735CNMNZQuOxMKe9idVT9FnNNJlRUG6LDcz1PzvpoJe4k7uyCua8ZPrEGje_vMN-sO4G_2gAxZaxBRRcoHsUfEhbPH8wxjU1tVuNR8oX2TP5oL_FWE)

Then you need to go to your command prompt and go to the mosquitto file and enter -v -c

test.conf

And start up your app.js file in another command prompt.

![](https://lh5.googleusercontent.com/P9Gutmg6_p95AzbEmAQKKibCiBrHmXWdPKPRB96Q5yRdzV17I53UhMt4kxg0zAvQP0dlOgmE93eo_7l3vIS0sTcJZxpkRk4of1xCDPmomiKBvVBFT9csCWwRWN2JCTUqkDdeWzgYrM1oVkQcjCiQPPE)

After that open your page (local:9000) to see the data ur getting. 

![](https://lh6.googleusercontent.com/vOd36CNxhdoMFfr_RrWVP4LtVWlxCKr7eRMeNlWUfpdCGcHoW-I3Wx1Kkz1TICGdKRqM9dMtV3c_xpdljUDChf2gq5rOBvAuvuJvrya8I2Z4LTPfje3MS588RUghNHTY8Y2l5hXzjowDPT8ga6plmkY)

Day 8 ():
=========

![](https://lh6.googleusercontent.com/13PhEFCNXGBewfYTzCKJ0cGcLNoaItkOGr6aEN-rNiyaQvu0-8I1Xbk2-e1hn0EtrgFx3adIOZEc3OOyXD-cDxrxXt1LN6tQAqy_g1C1Ne1uhc9YTwx9jHdqiuPnMrbjB6fsX1W8P1uqugnnTF0IGkk)
==============================================================================================================================================================================================

![](https://lh3.googleusercontent.com/O7isRdfoNMpQoNJ8JKKtPO-wqZOiRXmpMgtywb_GgPYWe-WsHNsaZmmi_XUEvcuDQPjT1lBP5rfsfL4YhAcI14eB8xSVVDEZplh0gfqY4Iw9i0Vab7dhgKuTOgi_Xyqe9jXyeZ5mW3PPgMVWxEOZu-4)
==============================================================================================================================================================================================

Day 9 ():
=========

Objective: Making a live high chart

To find the charts we can use this link: <https://www.highcharts.com/>

U need to customize your index.html file and put the code in that. This is de index code: 

[https://drive.google.com/file/d/1kJpv-vVDiMtk_jqT-kp-OBGmptDSfbx5/view?usp=drive_li](https://drive.google.com/file/d/1kJpv-vVDiMtk_jqT-kp-OBGmptDSfbx5/view?usp=drive_link)

[nk](https://drive.google.com/file/d/1kJpv-vVDiMtk_jqT-kp-OBGmptDSfbx5/view?usp=drive_link)

These are some piece of code that we should include in our index.html file

Line 6:

![](https://lh4.googleusercontent.com/D5qGckekYK7FI7eDojaeCzTUZU-FLajrT8-MdAg-0qrjk-jO1Z2A-7WF6SUhJVmQKETMBsyaTzFJtWwJUGVqdiNXulDDvWC5iU7EYRlCf4DvIyhau_ie4ZiPmD1zO5ucG0s9ds4s3YfdAo1Mwk17Qq4)

From line 65 - 97 (High chart code):

![](https://lh6.googleusercontent.com/NdU3F-WhGakkZZ95EZnufhs8MRVc51dt8mIAgBFYFuu_juZ5YDsiBPSQWTXRlhoWE6ukOJ9wRcz85asWPVVFEv_OF0PhgZXUv3JS-uTtvncMeS3HzBLodbMA792gj5NPtMY9QWqiriROp9MUt5WU_Ho)

This is to store the data in variables and update the chart 

![](https://lh5.googleusercontent.com/HDrUF0H1tH2edNYc4377Qf7V0V6QPhexJxMzpOZp49iGScxhX6gDLQUrkG5Emq2xkQuGetBb3uJE3gQBneR4LbbPCOl0vswEFFdAa8L0jAeuSATRFkkTFz1OraHmiR_KxP_mYueF9cKdLcPuuAljwJM)

This is how the chart looks like: 

![](https://lh4.googleusercontent.com/2ThfsOxYVC__kKtf-TifimjZjZreNDD4_hPqHkC-ICPAiUMqtWTsE9cEvKWhz8Izp0YB9HyeolX3Tuezw70F_zwKZ7yaZVlJQgffwtIqG6xtyzgosZ0oGb2yJitTuY-kncAfakAGcgPyv_ozJATUl8s)

Day 10 (26 mei):
================

Objective: Styling the high chart website and displaying live data in a box.

The link for the index.html file is here: 

[https://drive.google.com/file/d/104QOWspnSqxFInL-beyVMerQFofmsHHo/view?usp=drive](https://drive.google.com/file/d/104QOWspnSqxFInL-beyVMerQFofmsHHo/view?usp=drive_link)

[_link](https://drive.google.com/file/d/104QOWspnSqxFInL-beyVMerQFofmsHHo/view?usp=drive_link) 

Icons and their codings can be found on this website: 

<https://fontawesome.com/v4/icons/>

To use these icons, we need to put this library in our code: 

![](https://lh3.googleusercontent.com/NaYMmz_HFeyNeo8Aj1Qb-jFrZhtdyGeILOtKS1FNcpA1uY3MwwBb1h3cnogMk3ZsXrxw2xbFYg_jQD5RB5SUCZYDqOut5NibPdh1YqqbW8fForNIq89pMqRctLl6SvpLQbdyU6dFImkHv3QM64tFowo)

To insert widgets with the live data u need this code: 

![](https://lh3.googleusercontent.com/XYhRrR-l2AjRxJ96MpZ5JWMClF5avQ-wsXkOPuDP4bQO4Cp3BGDypB55yUw2u7rH3gTOeB1Y_01UDpxieNBr6vslAz2syba87h7oishzTOcwsoEU1r4Bdavz279VPJBIpXELJez5APsDJEgZcR7rWcY)

This is to update the value everytime

![](https://lh5.googleusercontent.com/WUD8A2L_GFg6uvbLJdlQEG8SumVC7RlGT1ofbe2xy6eWXYl-syIlLl5Cr2vdn0nSd8t3dFQFriXpo7PJZHL1jdIWgmc7AIe82TS3xTArzwD6jwlSnWqS_4O6q8bvOqxMx1fKYaudl9P6QbfsNRHisPs)

And even if we did that, if we want to put it in a box etc. we need to style it, we can do it in a 

css, but because it is not much code, we can also do it like this: 

![](https://lh3.googleusercontent.com/QxL0HD7v5dhCcycRvOxUlxzgt7osOrZ4Ugu77y4Ia3tyxC7RnMsN9gaHhLe1EgcYBb2kpFv5gQ8H5_lZXTXfO1Frpw3XIfwgvFFxb4LLgbNq2HTYC_XqucjQs5hXS8DnTkMGUB_BFNMZkMVjUXNFm9c)

This is the chart with the widgets:

![](https://lh3.googleusercontent.com/kxTPCnhoGqV9UfFoHbK6R1J-omVKtDW06JC8SiAn0caPIDk8xdKfionk6E7a0Y8aE2awnU8Z3xOhz6Jwoz3Bt_QJibm85FNVuTup7u4AqVb_qr4KX3c3duZxsMObLgFj1ORX0J_f2bCw0LGIE6UfX58)

Day 11 (2 juni):
================

Objective: An introduction to API

First download vs code 

(<https://marketplace.visualstudio.com/items?itemName=humao.rest-client> ) and then this rest

client. 

![](https://lh6.googleusercontent.com/Hx3P03uMRZvlMwDYrs7pFBKI41n8WXLh0VkzBIeWW0ZcJlf95gIuuIDYcmesqiEkMOfcIWN0ckbthEXMgOGTD-U_SAvGZ3edtNMtD9Z09hXIgLCa6X1xTni9v6qzrginBCOFT51_EDVFP2nfyyn1D38)

Open a js file here: 

![](https://lh4.googleusercontent.com/CXpJcbNiJzFymCVbhp69JH8rqv0DBqjt3k2wl7aat1fNN_BimaaEJr1F6DRL_XZzthn5lhDTK6f8H_hhnTv10VAtqqacvnq0R7Quz4GUZOm1SfHSIJ9vla90XRNteS4Ze-t0V262pqV7l13hEoVhG84)

Here are some libraries u need to install:

npm install path

npm install express

npm install mongodb

Below the code will be explained in detail:

Here we are saying that we need express to start the app.

![](https://lh3.googleusercontent.com/sQY5VShE28e_AGQTtW0Lcs9NiTssn713QOB0HqEyJdHh4je46fQzS5Q3kaMbw5eDzbCgFftbETFyTk0YwOr00jX6T7ZaI-BpoPMxnKH6l_K5rcMM0YCKK14A2epF8bE6xfeQ1Jw217gZ_7kThj9MV_I)

We are initializing a path and saying to access everything that is in the folder. 

![](https://lh6.googleusercontent.com/v5fSXX9BH1snUtVSoTwKkPvQ5NOVlsH75tcaMlTTCY8COdo4-iwshT3c5DBmMNB4sTMkWPuwt6_PlrmVV1ZQ8YahyrdYys6XbyELwIM99mIPqcxtJse_cGyMw1SR3c2FaMFlwjr8erDNjLebD1EUsso)

app.use is when we only want to serve up a page without any text or so. 

![](https://lh6.googleusercontent.com/MCrk4XhTdVmhQxfeEgNLjqN7MlI3VkgQD-j2uGZb1YhsL2_YMrxCRkVdBNMo79_eT8XSULHXKbksh5ylyFnPdqQhpQvmZ-ciYE0BNj4xIV7IHOIEcJfK1lmkzPRYXA9ogPBGNCxY07MdQrqDcWg6VbU)

We use app.get because we want to put information in the page. We have the arguments, 

request and response.

With the variable packaged we use all three other variables, so it is easier. We don't have to  

type everything out.

res.send is to send the information from the variables. 

![](https://lh5.googleusercontent.com/HVLnlnq91kfaIRqC8CMwCdWNSoIZXzFEzTTGDuvAjbniyiCBi_-ybxA9FzHJezrPFr8OvFqGWbKY2QlV30bkrPZTpKg1wwCiZDnOKB4J6qrnk9NCf5kjc0WxrQRMr3lL8LdGcvEnXyJnVZhnnBkPkRQ)
![](https://lh3.googleusercontent.com/TyC6LG4Py-272U62re1p28RAm_iHBBSTJAzSkS_EUrjtSHQNoKpCLUYYWGkQRamjEJRXt3kObTkiTfeqErzlHS3BMMAwkoY9ajNyPtUfKN9j1LMQSbCyHwq4LCYsKvd6sea9eN3tli9koz2ivZZL7Q0)

Start up this file in your command prompt.

![](https://lh4.googleusercontent.com/6UBK2OUSrpNKLkXIQFtaeb3g1tIm1h8X8t8qCHKwMrgH1AddwumBSRkJg3iaU_QWlPd2kY9168XMwmPfW7XnfGnS7MOa_yzOSsOPTvtPk0nZa2NchqSxZlssDNxxfgCzaTIhGiZ-XINTGivaKriXLWM)

When we do that, we get this if we don't add arguments:

We only got number because we parsed it in our code, and if you parse nothing you get null. 

![](https://lh4.googleusercontent.com/A3YQ4NH7g_EredDKC_4MQ0y_bV16qiZELufwYGsN_PVML4g2WnyVrHJwCaYUjoxHX_YSNtOh8rQsuNpxRT5TFvRBYit4Pi_zF3iL84qVOyH5nCbJqIweCuGu4U18QrPKFSecmJ642yN6MXq_4v-5uEk)

![](https://lh3.googleusercontent.com/KMsQ2C85eS_drYfDDn2bWLy_uPkyw_XgFowZP1ph1ft3KcoLN96ZjxYP3eu_GjeEpH8LhrWoTN8A34LBK_zPdW0876Ge45N9ieJacIx-HOIam8p2_iQYuNOsPe9_veOB4D3-GetEnx4NBUbbdAeD8R8)

Then you open a new file with this in it. 

![](https://lh6.googleusercontent.com/xXUiPUL8aDI9gK5CtHfuGd7x1OO0zhzyae4vXBrtXzFZ0QtH1Mm5YLBvHov0rmu5CIpc0J_thacZf3HS1c7G8jringB_eqsT_X9WwE8p5Hh71Cl3LuI2j1CYzQbikTHs3LA9Ag2dJ8f4hPnG3SYVxqE)

The fetch file is to get the data

The fetch file contains this:

The await function first gets all the information from the line before it goes to the next line of 

code. 

The code in line 5 indicates that we select the data that is in JSON format. 

![](https://lh4.googleusercontent.com/EeI4-kp4z0UGYuHbSzeZFKQzyba5PpBGGStpms7xOE8xLoIa-6aeDNCeChRNca36KTLE_wg7c-fwwKweUOT_liz1X2sOW31Z9F46Mouz6TFut1AaetOLU1SWhLVO2-Wy3Ze9l2HVpO20t-O7WJVqk2A)

In the index.html file we have:

![](https://lh5.googleusercontent.com/KY3ogbyZxf4OYyKsX0AgCpB-10PDdVSfitacb2vSMyU0-yV5qlAAVT2GvUjB_J-MkmuID6K4NrDAanhYQ5H28aQVODlNnNdsvYl8c59AiTOEai1cBW0JMaOZGG3nsAM0-PusHQoZGKXg8VSewOWfetU)
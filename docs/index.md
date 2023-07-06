About me
========

I am Payal Debipersad. I'm twenty years old. I am a mechanical engineering student at

ADEK. I wanted to learn more practical skills, because we don't do that a lot. We are more

focussed on the theory. That is why I want to do this course. 

![](https://lh3.googleusercontent.com/7XYq74ZrQxgj6uRlFnDa31oYMS6Pz8kvMr9xPREp2fqGXFI6rxJXd0tkeS1VoF6KaWfEDqjJUsdSblU9n88nsQ3HietggKf76IORzZNWeSuPDxcZoUTQsFFWdAG1u4DT4eySRUPtf6cTi_qRVtzbY08)

Day 1 (10 februari 2023)
========================

Project management
------------------

1.  Create a github account (<https://github.com/>)

2.  Create a repository 

![](https://lh5.googleusercontent.com/jYfv8ELj8-8ic4OpOvWH7zZfEmzJz87GCnbO9WZVWQhnwI3iTC9wc-ueM5AfIOLxnOSb_ao3eEVmsNtStciJJf7Mlbi04AFrscnNP_eRECWntIigP3N1wOlVYNd78eVdh_xn0PJMmkQfYADtbKXPXMI)

1.  Download github desktop (<https://desktop.github.com/>)

2.  Clone your repository in your github desktop

![](https://lh3.googleusercontent.com/siPH6oOEPq8YbJvIUb5OJawlimz5W9Ft2OPdbd2TSW28OW_SRiSb4-nXVpW41q1Ot8JJ60cWgBe1qPDGnlgJUUaG5Q1lHG0BLB2GIt9xCwNGE53jA5V3iL_7uld6aWCqWvisYPX4g01BrZ2iKxNvUFw)

1.  You then get a file "Github" in your documents. 

2.  Then download the clone repo and put the files in your github document. (<https://drive.google.com/drive/folders/1rEbBA5UYhnrQrHGsEiU3D2dWEZyIuBi2?usp=sharing>)

3.  Then you need to push the files online via github desktop.

4.  After that you will create a link to view your documentation. ![](https://lh6.googleusercontent.com/8o14-rBrmyKCVPTF_RKFWPr08wymr0HgHanbu4rxF6zQNpJNxVep04pgOUmG8zTUGKZrUBpagEjROUl88M6Kj0X4JzMcLVTxbMfoO27zYWWE4A1rf-wdmacqxUCIG4-saua6gG19dr3JBSFqZwS0nZk)

5.  We can make changes online or offline. 

1.  If we do it offline, we need to do it in markdown (<https://www.markdownguide.org/cheat-sheet/>). We can also just do it in a docs and with a link we can convert our docs to markdown (<https://euangoddard.github.io/clipboard2markdown/>). We need to copy this code in our index.md file from our github document (Customize it with notepad++ <https://notepad-plus-plus.org/downloads/v8.4.9/>) We can also instal a markdown viewer in our notepad ++ to see how the document looks before uploading it online. And finally we push it online via github desktop. We can view this on our link.

2.  If we do it online we need to work in the index file and use markdown language. And if we are done we need to pull it offline via github desktop.

Day 2 (16 februari 2023)
========================

Interface and Application Programming
-------------------------------------

Here we have a connection between components. They can "communicate" with each other. U can control it from your dashboard.

Setup ESP32 in Arduino IDE
--------------------------

![](https://lh6.googleusercontent.com/MxiWzxrFLJv9aUwNA7MOX7bJr7SPQnZVtSW0CqfUKFOLslsh_x0vOS_hkJ35Ho6meocZb6KJeioJhPdLuryDD6ja30iCFM2PmuTtoHsIg8WFVbr9B1P5ttzE6fzL3GA4MeXciQSy-o_8nKmVJ9GIoxY)

Paste <https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json> in your additional board manager in the preferences of your IDE.

![](https://lh4.googleusercontent.com/3aXgs3wTZFN8olmAmasWDjbrDMg1ak6RDjiQU0tuARgjaBql5ZXBm7rAwOPAG_OohwFfAm2fUwYwWMCidY1_tcIcknQ9lj5ls39eMyAfRVnVBI5T-nc3lZ7Wj-NS1Jtupq1ARI9ElmGwJQKN7QFClX4) 

Then instal esp 32 on the board manager.

SPIFFS
------

Now we are going to instal a SPIFFS file. (<https://randomnerdtutorials.com/install-esp32-filesystem-uploader-arduino-ide/>)

We download the first one, unzip it and put it in our arduino document in a tools folder.

![](https://lh3.googleusercontent.com/PYc92jBP0bo79CUnyruIGqlOCcrMnCB3-ZRhIQSApBCYYRZATpY5c6waQXxZkqi-JCSPku_5iQVP7Xu6h3SMd9rF2f2AGS4yd8Z5gYogjCULA2JdHVD7YWaZF8gBBq0-nS9K8fvxEDU6NUPiCy_pZB8)

Host local dashboard
--------------------

Now we download the SPIFFS data folder <https://github.com/RuiSantosdotme/ESP32-Course/raw/master/code/SPIFFS/ESP32_Async_Web_Server.zip/>

We need to unzip this file and put it in our bootcamp folder. In a code folder we put the files. 

![](https://lh5.googleusercontent.com/R-GkwnD_630N_Qsce55ZooQC18V6c6w6c4OE-UZa0blM0UpvQXaQwssyjGCTNMTGWRVp5khokJ_0nmfTQXeFKhhwOqzR4x3yAz1GDdT1aZSQpYfkAWDX-L42RdWCwFLD6VV1sQzmHaYE9kweYrDdHzY)

Now we need to instal libraries. <https://drive.google.com/drive/folders/184_RwUj3iOGNeZ4GtvciJrSK2s-s0FCY?usp=sharing>

<https://github.com/me-no-dev/ESPAsyncWebServer>

U need to put these here. 

![](https://lh6.googleusercontent.com/O-0MWxcWqeroTDujm912Pbt_T5-xpYgrTFy8NN3TfR_L0EuQ4FpkFt62BmIXUISDt1YznZR3n0QdSOwq1ONVUv6GfiKoGkECUieH-RXdLprM0Ix66I9W9EcDZy04mC8arkUTYTcWJMTaxV_ICb458x4)

We open the code and customize our wifi and then connect our esp32. We verify the code.\
![](https://lh5.googleusercontent.com/Ohf2AAH8e8LVwvR6l3dP-pzTO9dWFZePoVqU1nozv-Wfz8nSwO7_Jg3_siLdoAjIDWr3rslXFPMgStlwYglMkT_qoKneOgZzZ5N9tH-b-gXuZexbJ2vZpugmjczTZZ-R2YlqudbaXNsLoahv7bb-dIc)

![](https://lh5.googleusercontent.com/gE8q-gssuEOYtTMlx8GgPCriA5x1PMuJuQZ7kUBOkRaCn-IozqmBSh2nlvMJnhJpwyEt1Eh2F3OF5PX4xNrphQUUEJS3vP4xECM_eBljSIxRaEChMvSCYPmxbYeonKa7uzIUFhWY1xF6-fqfi5lCxLQ)

Then we go on ESP32 Sketch Data Upload. After that we open our serial monitor and click the reset button on the esp32. 

Then we're going to get a code that we need to paste in our browser. We can then turn the light on the esp32 on and off. We can also add an led. 

![](https://lh6.googleusercontent.com/J7GP2FnZVijymdkexjquOCnEbBm1Z1a64d3_ZC_TTSDgFawcdjVAtY6L75y8C0E4b3cLbYtOVlP4Ib5owcunkT8SIFXs_hwCRX_4ZhMj2g0nPxiufLAnewx-gEDkCE5G4QD9pijXmWxtlanQsZ4EuIw)

Day 3 (24 februari):
====================

Multiple Sliders
----------------

First we need to download the library (<https://github.com/arduino-libraries/Arduino_JSON>)

And put it in our libraries folder. After that we need to download the file with the code.

We find that here: <https://randomnerdtutorials.com/esp32-web-server-websocket-sliders/>

After we downloaded, unzipped and sorted all files, we open the code. We verify and upload.

 ![](https://lh5.googleusercontent.com/Nm6DbbwaRk1xfu9RX1gU9XCCEemiojwHw_W0_7G200G8rIXKdBxyD9yS5mxApJN4dD4zq6nkTNqQPwxVWWsCmV82CeK5dDjw6-i_V28fMMrUo-l_OjCaGNyBMeecOmDXpXPmUBPV1U5d2ngmUpeWLbk)

That will eventually bring us to the webpage where we can control the brightness of the

sliders.

![](https://lh3.googleusercontent.com/SMq6DpKLDXYQCJS5BHBb_qo-tgOG3eNYhDXrV-M2pohHZkxSKw7KKs8tiqBHm-A9ckG4GVs6tD6jGiPkHJsfISCf4o6WNuweF_4wgHRF6fE_-gqQe-5MQw-vG6GOyoMTeJ6dcYY8qnMDJoeMfcE2e4Y)

We can customize this page with our data file. With index we can change the text and with

style we can change the colors etc. 

We can make changes online (inspect), but if we want permanent changes we must do that in

our files with notepad ++. And then we have to upload the sketch data again.

![](https://lh3.googleusercontent.com/idgAmsSd3OSZjeNof6Ot1Vjd6KdXeRuAm_eTIw26sGIeHJH79Fstc2V5PSNv4bfINdm_QNIw92713-QWm9gmM9Lk86DMtVbTJ__opg59Pb8cENOhSbn-3VR5w65sk-0U5SqXi83f0XxKAoOiksWgJXA)

![](https://lh3.googleusercontent.com/DQdbv26V4NYspldrSuINM1J0pEFYJJZmuywUCjzxgCUmrCO6sunGmylxv_jUGwIYstAnemfw4SlV99SdxZljrxsLORnHFOAHIQ29aHU30bH-fajb4K86YfkPKpnu8I_qGNfSyQ6hG2biozkUYU_PThs)

Day 4 (3 march):
================

DHT sensor
----------

We needed to follow the steps on a website and then set the DHT sensor up. (<https://randomnerdtutorials.com/esp32-dht11-dht22-temperature-humidity-sensor-arduino-ide/>)

We then needed to install 2 libraries. It could be done in the arduino IDE itself or with a link.

<https://github.com/adafruit/DHT-sensor-library> 

![](https://lh5.googleusercontent.com/7FZeNdwRbSlcem0bp62l7V6ayZxgMvAgH7tSR2vnJmMrbcHxJceAaLQAVSedg-9wGmjUteF1U7NTsLV6FM131sU6RHhOyMQEkrQFq2JZdLYhXaEGYCbJtSlTmdvKGK7u9xxOou2lHMTMRtRRKuoEeNg)

<https://github.com/adafruit/Adafruit_Sensor> 

![](https://lh3.googleusercontent.com/NL9fLg8MCJqUXHWcGS7b2AaS0KZd1shw2H6L-H4aI7WnsaMp7Znk16jW-442V7pTzXnLP3TgNW-17e66_g0pEVHrbl6i3H8wymkHgqChSTwbufYQioSAOZFFJ0LDkKyYqSho23OsMNu4-DovqeMfvQI)

Then we needed to copy the code from the website and make some changes, for example we

are using the DHT11 so we needed to comment the rest out. And we also needed to change

the baudrate to 115200.

![](https://lh3.googleusercontent.com/x5BEXBsjZcSpv9xa0pc6UsQtING9nREg7fwgYxq8sEms4MuW2SrBELIIg0kmtexz5yMkQ2j8pg6S1qp6pllNlL2XCGdPijr0DcGgasg-DLXi8cwYEQPqez9Qc5rg6QAy8O6kDRPO48SUednKKNeN4eI)

![](https://lh4.googleusercontent.com/eo7SfHirbQSlDfuDp1Fq7oxh96mrmso_g2uCjQSKtOESlwJNULSexCLyKrOkJNgCWwSJymb7ysFwK0eo29hj1A-JMWPcsd9qfQ99kY0PMDvoCIOXr6eUoftvf1wob7yeUQ6h3Pie1ojtfohynDElJ7k)

If we want to make a web, we follow this link. <https://randomnerdtutorials.com/esp32-dht11-dht22-temperature-humidity-web-server-arduino-ide/>

It has the same steps as the previous one. Only this one goes further and we get a web. 

![](https://lh4.googleusercontent.com/Y8lb4E2dkXV_5OqnKziXNd5kKiU6SvhPKgRKkxiBjg6f_d53WUevIiNaI76JI_EkUQk0znmR0OCuh0Ur3ZM649IAXEcf67I89DhX5DuQgOZkCMCpnzkGHcUZK7h1TDmMFS4TqH3Z03RrHlWK7qDRW5c)

Day 5 (10 maart):
=================

MQTT
----

First we needed to make a sketch of our architecture of the ESP32 with the web server and

what happened between them and the LED's and DHT11.

![](https://lh3.googleusercontent.com/e-L7iQmFrehD5RxqB72lXt8uDUASzWFwySdkoHpZ9QWG6GdvdWcxGXLN6IyOV7H9RM-nJcwm8KwmbS6c48iguXHRgA7-QkFI0kWJBV6orihLumcJ6BN9MfpgVDGViQQsnCofrsCwP7hOlDHkv2j1zqk)

Then we learned about MQTT. That is a broker which we can use to get data not only when

we are locally connected. (<https://techtutorialsx.com/2017/04/24/esp32-publishing-messages-to-mqtt-topic/>) 

We copied the code in our arduino IDE and also downloaded the PubSub library. 

Then we made some changes in the code.

![](https://lh5.googleusercontent.com/5oOUgxc1XLx1-bWpnZbO4J0gCHeYyk0xNuOLxTp8HqbjvroO5SoKZydKNHMltymi8FtTy4exmc4rHocU83SgHHI-veA-f3gqU4ep_9-D2LLuaqzRARLzfkb7KjclyfxfeoI9-NlYzMWgo6DyFpuJHvM)

Then we downloaded an app MQTT lens (<https://chrome.google.com/webstore/detail/mqttlens/hemojaaeigabkbcookmlgmdigohjobjm/related?hl=en>) where we can see if the broker is actually getting our information.

![](https://lh4.googleusercontent.com/lTDR0uDBeob_gMwtz16HiuLvStj5a3sxXgEa4DJ5DB_biuEqde00vQq1D9gGOgJ0kLo0EqVouYaK_AMh8WfvjKt-ty1LpYhmuQ9Qb3AtFaIkF-pmNkYZJmVaije9LMD6HHWVNut06RNWL1YNQ8mLCzw)

Then we should fill this in and create connection. And after that we should see our messages. 

![](https://lh6.googleusercontent.com/9HaxSk8FBwo_ENxoaALAvXzsZ93OY9paH5WGF2FqBQ_wT2vKrANW17yqhdOADbDxP7Y4HDYmd5PJdObCdEoW9Q4tI4Ewg_2ax4rwRx_B8NXFsVUNGsIBXZEGGFWdM2LCLABwiAbQzGhs34UERyVvxEM)

Day 6 (24 maart):
=================

Use a dht 11 with mqtt without a web server.
--------------------------------------------

Without webserver: 

<https://docs.google.com/document/d/1gPfp3f9jbAcFxe7KjdTmtqzEG3QMySqYnl7Sw4jvW3E/edit>

Use this link to find the code and customize it, for example change the ssid, password, etc. 

![](https://lh3.googleusercontent.com/HdcHi97sqy6PMrFLEM3Jd_V00wqoHT8gWgRFhRpc_yK6aoujeOtGCWbCziBxvez9BGT8yeyjIcfrlW3XIt03aV0VltF2svby7qGX34-bLIXfbUGzqEn8s3faiqctLa7hX7Bhit_gutm7zgRwmdGsS_Q)

Put a delay in the loop so it doesn't send readings the whole time. 

![](https://lh3.googleusercontent.com/7O8ctVa94tPucCCZ_4FUJQUJir2jhHUVsFOXM_GbPU9FvcCXNfSWBZnYUb1mJTcmrb0oklp8XttowQ8GztfmTErKJIqkYhWl1OuLSdaOrQhKXZjJ6kt4xQm9imhCRrJpJidH5BioO5OhC3pVfbywfzM)

And after u get the readings open google lens and subscribe to the topic to get the readings.

![](https://lh5.googleusercontent.com/FFGiJCDNculm8DN3VsjakQO5qBLeAIHi5u6-zEFUlUfm8QFouoWLpKI8HTZPbmmB8uFHpAUfkOHS2vJISwcR_BzqJR7Hq9a_pJ4d_xXo1OzimWu_TVCoj5wjq_ipgkURm5dT6VPXj6uG886nx5l5UbU)

Make a chart from the dht 11 readings on a website.
---------------------------------------------------

With webserver:

Use this code:

<https://christovitohidajat.medium.com/esp32-chapter-9-dht11-readings-into-plot-charts-c4c23ad367ce>

Upload this to the data folder:

<https://drive.google.com/drive/folders/1t4b1LoQOsgiVcrTlII5oBtyykfoiGETu>

![](https://lh5.googleusercontent.com/T9_UT-PIpGG6inMLGstO2lHincd3DPHH5LzE7odfGNc9lFJ3Zz45u7aFM6TREmxa9LPA_NAgPK403A1HqxX_DgtZ1nYSZVwlm-5-W9dtu2Y6qJkdIV0kgv9XQJcHHRcfRHRFN0M-K2TS3YDXSelZ0gg)

Homework: Merge the 2 codes

![](https://lh5.googleusercontent.com/FHPOrqbXM2Wzw2SnqJ8MMKjcTRQNPk7q5fpQbrNixoGDFanAdOm9wZ8Wt3PTtpxArtTYmZ4UF_UP694J5v3vBkFDeT0xP-Gxhjly3VUbJxo1kIx6CKHvXw0a1AZ53F4c8gWhaz2IDFcgas8NmeHOLq8)

![](https://lh4.googleusercontent.com/Tf3J7IRgtfedKfOoTcE1-dLI0VluU9kFvSQmGW3VltN4ZiAobZN3iOSWVpifHt-qnVV2RBuNVGk-8zDaI7I7vsHkOKfbOuc0KAKPFWC6yGYnG-Yh5uBaEBYt5DvJNEYZHj5LQANvMwEAYwBCbxIv5cM)

This code can be found here:

<https://drive.google.com/drive/folders/1baNGJn1iqDRwBRcPfCrvaDBQtK0e1ZpA?usp=share_link>

(There are some things wrong with this code because I accidentally changed it)

We need to host the app with the 3000 port. It listens for requests on the port 3000. 

Day 7 (14 april):
=================

Using a website and mqtt
------------------------

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

The results will be like this: ![](https://lh3.googleusercontent.com/coWqMK2WDV_BP2BKg5v69BHLyqr31nHPZoNcKUBzcziLufuVkdRvjt_kwtSd8CgTcDrrVZ971lvAp11D-tKAu8md6Kj2LZinkkCU1mdXyszMoqmZdzTFO5zIRWpX61ipcIMEL-RCRQiA0ECIfyNTuiM)

![](https://lh3.googleusercontent.com/35_DxahWiBeq1EsZ_-m4Tfmw4YLkFUdY_WnsnoJP5Q79hgIaMIo6HGJ3Dfavq_3no2mqymtwV9W020DNUntEyHjdm9fi0_4m2bwjoRL_sR3Gtl0Kq0re0vOXMs3ZLJH9DPf7d5kbtx6QoPxYqLLBIlw)

![](https://lh5.googleusercontent.com/sFws9Xa2GSTwTkNP3imOHQIEtNjhLGCZ281KOF6jExp8N2u3liPagwXMtlfHbIyHTw6K_HFOkg0taKrxVAUx2TN1ZZCUFzpr_F38gRtx1KnbjVWE6jLMUxOntWfSQJe8VBzErKoLlYzbl-WgWpKAZOE)

Setting up the nodejs environment.
----------------------------------

Download Nodejs 16.0.0:

https://nodejs.org/en/download

Mosquitto for windows:

https://mosquitto.org/download/

Put your nodejs here(Make a software folder):

![](https://lh3.googleusercontent.com/5Bw7DdA98Mp13BtFWbQs3x6OcbNOse8Iu0ZQsuFAVAzKMbVK6DeouXcH9le20PUiaLvBVwzZIm0VNZnO9mgUqQsiiEMohIyA4Z9yz8sYpBmh4fEAU7gwYxmTyCl4QrybBUK9E_TwGxvDYYXa1FhQ2aI)

Make a nodejs folder in windows c. In the nodejs folder you should make 2 more folder called "projects" and "node_modules"

![](https://lh4.googleusercontent.com/RuFw-oaGw07Q84ywEyG-ECD6Z2TGZqHj0iRCdLHNAuVJNRfOp69hYInkfNnugtpPv2WY6wuTX2GDKaLv_TEwlhYEWw1aKtza_A2CXlPohnszxVwGK_VwZ_kpxV4vg_WrNQPSILDp0Ti_A1c-SjmrB2g)

Then you download the mongostack folder from here and put it in the projects folder: 

[https://drive.google.com/drive/folders/1rq81PdjlsMFowDBo4Yq6Y9wfd-yVzd25?usp=shari](https://drive.google.com/drive/folders/1rq81PdjlsMFowDBo4Yq6Y9wfd-yVzd25?usp=sharing)

[ng](https://drive.google.com/drive/folders/1rq81PdjlsMFowDBo4Yq6Y9wfd-yVzd25?usp=sharing)

![](https://lh5.googleusercontent.com/6eKEMSKV6F_ib3Z1fn2Sx-tg8PRvBHX3VGakXTkTnY403d7U_-QyysvW2-iHc0f-vE2LyKLCTdlj3oGEXxWrOGLa5APM57vY41CY_fbeq_tZMRpphz6NbVObT89IPrl0nMaw9EPKTOMaQMRlm7BjiwQ)

Now we open the app.js folder with node++:

![](https://lh4.googleusercontent.com/uIYI1huwNeDUy3BgATFdl88FWTUnTr7H7r_pBeFmQkSILtDg9rRIgDIqeO_HZzPzmvZx5DrN2OLRGC-8H-nV8dsxK1HB9dIPvV6A9aZ8gOzNbDaQnYum4Tydf6qpjDKN6IyuZPlHYwtZ0Zn0PVZgcIg)

Make the changes to var client and client.subscribe:

![](https://lh5.googleusercontent.com/iS5TD0d2JX9jjlX6xbb6kYhwVjTJs4qNnt1yNgOM0-S17HkiGB2-pLgYayJ-zlJ3uH3Bsi8hL1IiAbMJub-kQTY_noUKuJakAQOO40WVPgRNM1GvH4Wz0qc-VGmHR0qX2Dv6iGbMqxpwtWapiqYlq2E)

Then open your command prompt: 

Go to the mongostack folder and the node app.js

Install what is necessary. ![](https://lh5.googleusercontent.com/U_VFFjfV78a-eKd4Ehozq3bNSYfXgs7gersTEjfyoln-CsMFrJdd1aVXwga-3pLks7dUF_gesuO9Gld5K2oWpmwdRBcOVOthkOQllYPg0aW4FJrWgUwxDGQvic8vWStdaeXXd8-NQ6t3zZOCD40De1A)

![](https://lh6.googleusercontent.com/LBz5F4r-M8ZuB4MOb5oXGi3Wq4TchBAQ483YMRdj1lijfLV6EaYCI67nRjFQ_ovQQRfDSTp2PNcGnVrYfnxgRVDjlvCCahbZ_P4JrIpcSstkkVhFCOy69K-EaprtzrkppBwghxEeUmt2qBqQfp-zUsY)

![](https://lh5.googleusercontent.com/8u7d50Llh9QbgNSM1ai_XBKGxY0e434CvtFiwYMTd8weg6FKWrxJkfOJwMipQw4NhAbK5aoaW27U0lz1TnETsjYo2qAP75Ehx9AJD4S4X9EecywVO6GPXzsBnYBwMpNtV5dM-OMAcchOMaqSbg1h0qI)

Search for your IP address in your command prompt with ipconfig:

![](https://lh5.googleusercontent.com/qp3B6QDNMEvA51hWcQaqWTn391jCAn782wCfmDeQWZBd1BBpGc4fzpXS4JQ4ByISlBJMpzUfXcxGODNsEGHq63Ls9V27hjHP5QYLN-Kp7qEf0_zmFKgd9C0tEtzqV8kUieq7Y9bq7KkAbkAPvkE6LlA)

Then download a test.conf file and put it in mosquitto:

![](https://lh6.googleusercontent.com/6qVOvaHttgbqBg3ORslANIhHcrXhJJT-Tq6A-vhwWbzgr4kuWYG-70cVjBeUHuSVgH9oCH9HZ9s715H4HSMlWJ59sO9b9_ix3sTq2pdrbo5JmH7Uw598G9Uqe_qbfls2lJEIMFTWU5yycnVhy0f9GkY)

Then you need to go to your command prompt and go to the mosquitto file and enter -v -c

test.conf

And start up your app.js file in another command prompt.

![](https://lh6.googleusercontent.com/p8jFL-TrJlthfK3UhPnoo5aZEGJjiDNCzRHLvU8XiQNOkZ4NPfjK4fNkw4-xBhejQlUZGKYI1WG4hN92IWtaQYhg-nbMQuyP9_SKYMNEwGOgAbFkPU5xX_U3iN63ZNg9XnaUF-r-F10w1La9snBrwxI)

After that open your page (local:9000) to see the data ur getting. 

![](https://lh3.googleusercontent.com/rrX6gUdvxiD9eZzaT5TfzdxrfU2w-X9gZBYIKBIUlxMH6wW1j_IE4y2oIpG6Muj66NJbX32LLqVijMhQQlgxWx_6TI6KuFcKQPK3b89pBJp2C_Eu_E7zJY1GxfmTsm3AvthpWo3m-chHwm0dlHMpyyU)

Day 8 ():
=========

![](https://lh5.googleusercontent.com/Znyu5m5whHbc7JLLqWGH45O5q6Ac7YOclZmmmaaGTdcL-GO55JuXfhUV-O_rFL2FQzxyPLBkr3jU_Q9UbpdTeW3QupkUtohMk04YUQgSfsS7kWTRC52m11D_vzVJW6ZMLkj3DROW9XbIuwr56sQawkI)
==============================================================================================================================================================================================

![](https://lh6.googleusercontent.com/KIEQjDiFAVS_bvU9OHVqvE7gMXtUQzej6ZO3-xgFoYn7VmaRjm5YB2Q5Ylc9l0w-OpXCbO9hAFnAvTL_csNf3orympipwboLybwymPh4Mgn9eLX1CJu1CYa5Psk40GQd2muAvV_xa7fT1DS2AGR_Q64)
==============================================================================================================================================================================================

![](https://lh6.googleusercontent.com/lOjSt3__rZ1KXf3qG73H_Abf4QuN1tBGjEA_WEZgS6Hyfcqp3x1wQDuIYB5pA6RMQemOLFpLR3fR2gkbLWFRP6yqKAU0apW-HqzgubfFRMMj84mdnVsXRrDpZJ3_PQU-gDPoaCeX1TuNElB76oHPfms)

![](https://lh3.googleusercontent.com/0CdQrD1J9cBnYbYgRyohkwAP_MMFXe3wT57bo6ApAvE7O5hnwgyZoE_RvS-G7Srnk_rivq4cmh4uHiKx9F8zHRL-y8TsxWQghbKYNsf2VkSt_3lhXDuxbp7zNoMEXBCke0wDk369Kc7siTjgjADYZFs)

Day 9 (inhaal online):
======================

Making a live high chart 
-------------------------

To find the charts we can use this link: <https://www.highcharts.com/>

U need to customize your index.html file and put the code in that. This is de index code: 

[https://drive.google.com/file/d/1kJpv-vVDiMtk_jqT-kp-OBGmptDSfbx5/view?usp=drive_li](https://drive.google.com/file/d/1kJpv-vVDiMtk_jqT-kp-OBGmptDSfbx5/view?usp=drive_link)

[nk](https://drive.google.com/file/d/1kJpv-vVDiMtk_jqT-kp-OBGmptDSfbx5/view?usp=drive_link)

These are some piece of code that we should include in our index.html file

Line 6:

![](https://lh5.googleusercontent.com/TYXXWFn6mgrHW7M3GMB_gYlwA4LBj-B-K8Qt6Fbd_G88-LYJxc_8UIslVhu0KjrkieVUAtjhrUsOsfPjQGrK2D0fMiOkOFuOz7VVJ-iDvv8RH334IAfYSFzz22R0RRXyVyIivyABf3ShY-fky7bLDRM)

From line 65 - 97 (High chart code):

![](https://lh4.googleusercontent.com/BH3IXGblUFn7lyi0zfxReGuFMHMO0fwPyuEh-czQafaDeZ_yDVJ01xsVyA6i8Qonz-kgG3DIJZfUsCyPgYIe5kHudjnSO9DX7NrO2XlKpwqOxAAwcD_fy7bPkth0PaZu9VA0fGCCXd7k8fGkHDh0Ls0)

This is to store the data in variables and update the chart 

![](https://lh6.googleusercontent.com/N0lgYRLwTbl9GrDfyR6CKkgohpCFvACP-U_Sy4h4s8nqjJ7E2RenTBiPCT8PNRaGPgQVD28B05SN_yN4G0RDlahPBaxWTABE6iNAk0B8fNZRoCCpu7MzZ_fXSLwVei2RJBSWc5twzco0MT1CiUfGWqA)

This is how the chart looks like: 

![](https://lh4.googleusercontent.com/f4t1Vwa9julaD_1d0vOUM7MoXLFBXc_oYedpwXEn9yGF7JEJ7PAhJy9Fup7gv6PvbmscDanozjDzmypBGyA5vJOZ7Ncv23TiH_d3Woyg7mvCKIEAntj5x9k1kaOON1KNQh2ch1faZMsQ3trb0QbLJY8)

Day 10 (26 mei):
================

Styling the high chart website and displaying live data in a box. 
------------------------------------------------------------------

The link for the index.html file is here: 

[https://drive.google.com/file/d/104QOWspnSqxFInL-beyVMerQFofmsHHo/view?usp=drive](https://drive.google.com/file/d/104QOWspnSqxFInL-beyVMerQFofmsHHo/view?usp=drive_link)

[_link](https://drive.google.com/file/d/104QOWspnSqxFInL-beyVMerQFofmsHHo/view?usp=drive_link) 

Icons and their codings can be found on this website: 

<https://fontawesome.com/v4/icons/>

To use these icons, we need to put this library in our code: 

![](https://lh6.googleusercontent.com/8nd0IVjJkCgAAY0AbZWFX2B7rAVSH-gq6Ua-iYZXo7gsCXfxhR78Ur2oEzwHo5ORGK8sbTYZx8vL0BfdRUeRDUr0uHtBRHAdwKc459qQb2vNmJhBKrxploqUcuKTnsCCpVo61hp51Pvb7oV3foJhHpo)

To insert widgets with the live data u need this code: 

![](https://lh6.googleusercontent.com/paq8_svDDyDtTbnZ_cE0mjlHRNwFXKPhOaZm6ISZvQt7z9hLDGHolxb35bwq2VZ1gWlcH4k02EGZDIZ576zhj1Gg68ELVI6t-TgQ94BwMyLoLVYzgzb2zUa0RENx3xkf4AD-O7682Q9BpIioIs6p1gQ)

This is to update the value everytime

![](https://lh4.googleusercontent.com/cC99xqQZXErXp1fj6myAPHWIaK2obur1vK6lo63s2kt2nfO5eCm9hHjY4UqmLGqtn-ulcGVpRlrQtLhC7800B3ic3A1ZPEVH6oAHkuyYWojfgpnEGjRA9gosuW0yLZKzEVIuUBIcBX58DgK-e0HvMPI)

And even if we did that, if we want to put it in a box etc. we need to style it, we can do it in a 

css, but because it is not much code, we can also do it like this: 

![](https://lh4.googleusercontent.com/rxTHr_fiVCp6daF1wo9vWhulnHGXYC-Sbo9Qeg3gGOKh68yNr8BYOUze9G0eBuFzVw4Ux0cQg-82Ey5QOq3uddY74uCQ09iCuK7sBVH6diSyLtCLM_7fPB1ypt99oWahCbvoR8hjdOW8LARF8BILYhU)

This is the chart with the widgets:

![](https://lh4.googleusercontent.com/uKpfUC8YOSK8Ui1ao_vFgGjdxcDT__D5h8Gp3dr80EcCSg-l2sYMPtixokaZ7aGGbuhgGACY7Bx4kabsjOZi3YDHiASSQaOSZS-BwI3SETCV9NoRGs-ZK-2OR4iwxLR5VqBw2_5HOvDi-UtHIDtVfdQ)

Day 11 (2 juni):
================

An introduction to API
----------------------

First download vs code 

(<https://marketplace.visualstudio.com/items?itemName=humao.rest-client> ) and then this rest

client. 

![](https://lh5.googleusercontent.com/ZA-ESNPedr1n37g9-isZU-PQVL6wet71Ih_ZVC52bNNrmjt77NbdzPBcOZAJlfPeup2PCFSj3GeTaj4-6KIaZs0ICF38bYal5ESogvitCBiOJ7cmaqNvccP9aOYJsoRfAyad0Ml0AiQuT4kj4QVHjrc)

Open a js file here: 

![](https://lh3.googleusercontent.com/pp1HE-yK75IRWkuwNGJx5qinW-kVpXynZuHt0Lto0N5vT9pQFfX8w2xpFHFQPThKrMEVRAM8zHQ5dpNHONKxHWozj5efHd2ziOpNL1lDrtiYiUuW2CeotAIy_95N32vQRGfTDTZwsrfKaPgzBQMpiyQ)

Here are some libraries u need to install:

npm install path

npm install express

npm install mongodb

Below the code will be explained in detail:

Here we are saying that we need express to start the app.

![](https://lh4.googleusercontent.com/7R3c_9swPc483LMXNKMAHCNG7QKwAO0xJKz2B659Ke-NNtWUTabPG_bUnbV4S6mWvxpY0LSmaa81WrvfKNeKxtMSQWR53J4vRCFiXct_dOB1upx115OzUXsQsYOd-kotRNXOWeZCdlZNK6-rWIXN1RU)

We are initializing a path and saying to access everything that is in the folder. 

![](https://lh3.googleusercontent.com/rQLRZGWkRWxlyBspMKIlJWk3HTVXxxayEYA4w-SkZQCgK5ARsAuDPjeu9LCEejYXyBzK45ce36jiIRQAXcdzaAIHlJI6-6_FvkZX7LmxsNTtH6k1By79M_If7PptGxG6eq03si7FlMG8L20dIJO_GaU)

app.use is when we only want to serve up a page without any text or so. 

![](https://lh3.googleusercontent.com/OrYIQBLkHj1yKK43j7Q7Q5kdEVx5sNtTvI014L-L3T6MYfK-DdtSeNBYhjDtxp5tE9tX8gpZrJTgSdDfNbG9O5dogMqM3Jpoc1dWx-So2dH6KS1jQKOecUacmv4ELF9zGby-ULcVWTgatyHmsCRkNdo)

We use app.get because we want to put information in the page. We have the arguments, 

request and response.

With the variable packaged we use all three other variables, so it is easier. We don't have to  

type everything out.

res.send is to send the information from the variables. 

![](https://lh3.googleusercontent.com/kSTX4h5ZVMO6rq-Ps6bCegsLljPZnWRHSZTijKOpt9pFpvhKbKHmHdPj9i6jHQIuhXZ90dPPuFcFpxT5WC18bPF3O23TY-WTVjY3kYtyZ4lcsy4kSMFU6LZpMVsy6kwvJPYwSjctVuw3ncGJxDpsiI4)

![](https://lh5.googleusercontent.com/f6zriZZcVCDO9N4Pzp3DzOEd5ogVpLBxa-lf0fS7oa97HsT-ZkSUYRpbz6UVVhTm3CMSoAhdHqu0ofylRYQeuneSkrMQ3McZHbt6pEGZ0DCGAE0gNNoK5XIixttXje6gA-HMhrswaXW_AYKJe6zfZws)

Start up this file in your command prompt.

![](https://lh5.googleusercontent.com/NiOhP_1h3NWkULuKDmCS5KUVKFtOrtPK5c8QHO1O0eabvonR36oaZ60d64JvG1f3yjT0Jcahoem6ahMUkxtEZmxiUYlNKVHRKxjkMa9UhrTe64W3OKoKwj8UCzEh2cL7TEPId51QJuJF-10xDQcE-R0)

When we do that, we get this if we don't add arguments:

We only got number because we parsed it in our code, and if you parse nothing you get null. 

![](https://lh3.googleusercontent.com/9_8ItkNJnMACfkogGbwsr3-MMLObLd6PVGmsAp8Pu1cjXqo--6OcwN0yMQrnKu3jaiH6yF4NSeiZuYXx3V3czDouFgiRxOg14jfAtBO-gFubXtCeSpOv3vunovaBSTBCEkcYTQs8ZtoQ_06OXVQfUFU)

![](https://lh3.googleusercontent.com/1w6e3zIXn1DLN6OCKK9S9Aprm50zde9RJvtPeE1aol3hNp1kdYqhlB3-0n65YmEA5XzvDImYHndaKTiIcO4wDAuMQramM6leF1diPELrQI2X4tr4bgZJ2yaUszdVkgwcaTvqnWpuBQHxLQMt9o9qc6s)

Then you open a new file with this in it. 

![](https://lh6.googleusercontent.com/sb5UEhX8QaEveaEWxDJvvoVncCFX79Nz5ep_HDo8KutPrfDFAV11qAZ3O6d89-mt4H1KDkPWaChN86OMzt6TId2xFWpwqlw-pb8UId7rZPFg7_GIa2H5c3t1lpXUTndYptaK5n3KaKVrczAJRmcQqRs)

The fetch file is to get the data

The fetch file contains this:

The await function first gets all the information from the line before it goes to the next line of 

code. 

The code in line 5 indicates that we select the data that is in JSON format. 

![](https://lh3.googleusercontent.com/_5-8YzgrYUXcExNPYlQhTWIqR-FwpOb6SDb1BiQaoF7ieGdCymmIWNTBlLkR09mdfdgdqJA7TlLDTZSaGNTK8eNiDHF034QUmKS4J1bbfF2ulG5LXwFh_e8j32l-FCPJsPwffazffHPK7awwmxg4dtU)

In the index.html file we have:

![](https://lh4.googleusercontent.com/4DRIsAejq5YSBvJBANTwFIKFYjf1RPGh4G-LZ-LoYMRu66BEamxLggC5RWTC0rfJxvlRuv-q9cyyiUr9EiS-zY6fcRaIDQQfNRZlZ31FyhrSsvxjSNHkMLO_7385ztWtwpWDrTdg_WXB0DDiqN84SSY)

Day 12 (23 juni):
=================

An introduction to freeCAD
--------------------------

First download freeCAD from here:

<https://filehippo.com/download_freecad/0.20.0/>

FreeCAD is simply a more advanced program than thinkercad. It lets you go in detail and

you can also work in 2d spaces.

After you open it, you change the units to mm. (Edit => preferences => General => Units)

![](https://lh6.googleusercontent.com/DOLmaxD4RCro0EArd3oN7rRfIEKDQqTaRKJCtZJTyFoQRhvgamgRdTFzqLghihrAdUhd4x1Boag3Fv3cg-ROydiSShZWsHwixac53VlT1tSzPmpZUp32IFcWS7_p6NT8HUGjMaD_1QPcXhUFxaUIXT4)

Then you can start a new project.

Your workbench needs to be on part design, you create a new sketch and select a work plane.

![](https://lh3.googleusercontent.com/HKEJ5nowX6N9ndNS5BL9pQr5rYB5MpYW8E4BJcufaD2v3vL26hLFw0XQfuKf2B6IyJ5xZZq---t8Aw49xmA-mRjTerbBhx8E8kpih6KLDdC8hGmBgM5xjf1CRTEUPrVKmIHNeraCfPe1tOvcE4KijHU)

You create a new rectangle and start making it from the origin. After that you can put your 

horizontal and vertical constraints. This is to put your distances. 

![](https://lh3.googleusercontent.com/gZLD9qAjNTsI9_EB9A8pxBKpBy6rSHKSoqd210q0OtcLi4Nli6Yq1aCVBgLC98yYOu2gzdHt1OmM4WUs844N8ElhVwlEEYpfKAkdAY-JJC1_4Li9zzep5bdneb9N4z_PJS381AG8C8rCM3KlFTnPM-c)

Then you put your workbench to draft, click on sketch and import the file and save it as an 

dxf for CNC and laser cutting.

If you want to go back to make changes, you just click on sketch.

If you want to give an object another dimension (3D) then you just select path and you will 

have another dimension that you can customize also. You can save it as an stl file. 

![](https://lh3.googleusercontent.com/FmqiUKdkYVbzZXrJo7tvEbC3iLRWjjO7GR2Ay-QpkCGYI6IEXs6aLBJVILCdJ8BcjVS3Tql0rTLDKkaB2ORO8xBt662-8LFvlfIhma8wpnj8C7wMSs8zA0a5HtQDdyRlzyckvYr6bjMLVV_7WmjzCnc)

If you want to put a hole in it you can just make a circle there and click on the hole icon. 

![](https://lh3.googleusercontent.com/_hyb-y-y-8VBrmjd5biMlnuaARlXbn-qgTfculY2q6U4cQrXIEpE2CH5fgxKpl1KUV7yBJNv1siJBUFgCIVLfTBTcMoXNoMA0P8OZ9f1ff553ySQwAjOo8JRRFRSKBRd8EOh_9dm--665sFuDbKYZCM)

You can also make pockets in it, it has the same proces, you first make a circle and then you 

click on the pocket icon and select your depth. 

And we can also add stuff on the box.

Note: This design can be imported to thinkercad.

Day 13 (inhaal lab):
====================

Create a simulation in freecad
------------------------------

First we are going to start with the simulation. For that we have to change the units. 

![](https://lh5.googleusercontent.com/rBwav-dmgG3j7XANluav_nkau55tSI6hi862DodxbaqEd1wqtCawETZbRCgjCuBG1_tewA7wkCoOka8C6s_-0NJa5k-VHB7FkvFMr9QnS2aCXRjmS-IIuF-CWzcrzzEkr5Zu_z-HHajiqle-aCbzUiA)

Then we build a 3D object with holes in it. Then we need to go to path in your workspace 

and select the job icon. 

![](https://lh4.googleusercontent.com/lYpwBP1AkA7o-j05p7wzn3VKOQgEkoCRCWrRONsQGHu8Pnqgf0WjN7OvEdAME-rGuzzcYX7DGIef3TEWMTx0s2_FaPPll1Ljacreymk7ySGefyT6FjzdwpP_IcyP6RNP9xGdSodSPgnSJGizW3iSQTk)

Now you need to change your settings from setup and output to these: 

Also setup an origin

Setup:

![](https://lh5.googleusercontent.com/k4tlTGrRJeV3g-Rtbf0nhjsEBUpEfEF_2w5tkIT3e7NVTJe66S04XeGYreq_o_DeKVTMeZbrlCXdoX1vCdGa5bh4IUbsIVg3VcBMWbvWkW1sLHb2Qvoer4LGZQ7SSiHnN_zcyhyx7fQWnfAfzha62UU)

Output:

![](https://lh3.googleusercontent.com/EKhGCTn9or6qecF42kw8nD1Qh3ZJcQo9JN3zZD5nWhV7eUQiHWLiUM2UqapN9yxFaBjscC68ByH0E3-aE60svh466KHjxiUCZRdyb1q9ahagQdejb4NNKgM-b723gzFsVPxcD2mgAgJn_ghxO4fcetY)

Origin: 

![](https://lh5.googleusercontent.com/avPKDTaIySAzb1p_mJsWR5SoI1Ysc27SEAVdkx6wGI8qN_1FoR3MAK90WtAOUYPHQKQ3nXqOdkMmXJlAv7rEorGtdvsjdwo9z_heEBKzgdsxLB8KQCGyd0ZFWk85ONLIEO3YOzKi4G1VrMmWWZJMnK0)

Then you go to model body: 

![](https://lh4.googleusercontent.com/RX9EREXdQcTr8aIqQ_qZ276XHuikO75__3DU8w4_DUZA1CfU12BYKEE7mkDeHuig-0XoC7FMLG0rA5lm_eZohkZbuT_p8JzWKVAzzgOiI1Yqs5Dk1CbdM6QS8QwRkwe9TlUfzPftic4UkeJJd_JEJsE)

Then you click on toolbit Dock:

![](https://lh4.googleusercontent.com/7SRMR8udrtG8vd5a6kAtsQPsIGV_H7B45J6XI9x6r7nGXOrrT_OersMz1Sg4UggZoxq4kg5EF6CRgU3ZRqFv6XxIttPLsNJ1whXyKkAG6R1cC3KsqD8smzN4Plf_8lYgW_jQrG0Dih909tlvnpSIqMc)

Follow these steps for a miller: 

![](https://lh3.googleusercontent.com/FBgD-cQ4x6M556g3T9TWt9-OYLlXVo_1m6uP8DsLJqAG1WTvMGNRr4dH1jLveh4tpyQ1SEZbWV_Eg4_K9nCIfpcInjwvXTcniVfrf46cCSpGIA-OvRNo9TUDpVimmPH6k9QuHP2_NrxVqAI04SVI008)

![](https://lh6.googleusercontent.com/izJ4gbb4w-uDulZBne8NDadFMnoLQ1h6rr1PEPMzULnn-1idSXHguuQZGvtFfZg1vr7HbQuRj2gddM0Hko6l6wcd5MZ4rvPpG32EFhAzyg8FWPFewnXdQO0uViPl-4eUMGcQ_kFWBEXhvRt2R-U0nqc)

Then you select the miller

![](https://lh5.googleusercontent.com/tKlNaNtGkjYuSW_d0T5oaVbjnFlQxEzMKyOQZlaP2cFZ3Z9lnVS1bn5NF2W-r-uaUArSoTqgRF2HDcoLfptifE3Ns0RDnyYHCCUXBlhNOkjUyoLnjYUyQ7_9NBtdBS9jUTEEFp6XNEpYsudQ0LjLw_I)

Change the horizontal and vertical feed:

![](https://lh4.googleusercontent.com/KUgHv4T-6pWCizwn62Zmh5WEHtFWQeVJ5l3ybbP8WKpUVk0GFAo6o4UfX_v72pzch5B3GwN-DEBdaSZwnTnt9J9VPunnF8dVlYrQiSswQCFXqLpCcEajQfl36aCPWpfQt-N3PH63vDt_vcxWQ9hjic4)

Go to job, then pocket shape and insert these settings: 

![](https://lh3.googleusercontent.com/h8zZNJEnuUmQB71QTrqfqfVE3-TxmQ1IFIuu76dewvddWTHPNYazwd8hymodMPLRI7bOLgBCRqyeQQZEsKhF_AhcgI_hu6xvJ6YcMREfS_KAyD-M38kRZR3HO2-7dOP62lMHhG5Bm-ISAT_rC-4lG_w)

![](https://lh4.googleusercontent.com/lztQzE_XLpmZb6AGeGH4Qcg5hWUFK4Ven88niz3kiFjhfbDUH5hOw_CSmtLmIPpV32jfrxyiDH2wq5XSRCMLE2bmdWyrgsTW7-IbBpwM_fsr8g9fxO0_BXuMCjbcte-nW9to6O8yeNHQK2yCQfgrBXo)

![](https://lh5.googleusercontent.com/Rbnej4M8UpynvoI5LPlLl4pMlYNysHQ1bTiV01SXaD7hZqSgBFEUs5pau7fPmtUx1MO_w-6hMHnhKEb6XhQV_EX18dpbTkqNAj5NDOKEBfPKLI_8nHsHzdyRiHuCMwe6a8tpVdM2MT_o9GjHQo8ZEkQ)

![](https://lh5.googleusercontent.com/YqKOn_n-puZuHI_RNazbEq5-zq3euzyavHSF7J--2WJbTDFFY2A8uMk2gJqJBAIJ8x_61RxnoW50dO5mAG62IV7GLU4wSCiH8p0AINlQZ-9foSHW1ZBotuZLl0D1H4uF_bcZZWOsP7zqEzbCw5M_-iM)

![](https://lh5.googleusercontent.com/LRGX_rW5-Fnqz-S9fu9LYeFoGgSN6qDCaFskRAhS9RnxmXFtRH30PHC6OeLaEQOw58-DDnBzykJs418YX7V3ZFaEvWE5TPhwzbxfAqdLsaas8Jfou_rmSv5WNgBUEaKNAPQdvcrQ-Fpl3Sf_3w9RdAQ)

After doing this, go to cam simulator:

![](https://lh6.googleusercontent.com/A19tiKYyRKfEGM4MpwB8cpsBqsv92_MaYUBVodgPdOPFDeoLy3daEtdb6fUfi6RpGASJV7-W2FV-t8ENRFzbZGk8ZVSM7K1Kz9lmtkqTmrIwDK1J9_85N3S-cB7b6TFBz2z5zaAFIbIK4wHbhUyYF2A)

Then you go to cut material and select profile: 

![](https://lh4.googleusercontent.com/4u_vWcb4VDlN9l1_YXlHL5glaraaK7dnr-ilACPMHyfPkUZ1mrt5dDd4kDwBz8sBdhgf6ePYOIDn66M98EmoWhTAY6Toi8136TDMdX5-zX-B3a3k_4mhG0TvVlZjP-1M9NCs6KNAwgw_-KnsBnXZoNg)

Then you again insert these settings: ![](https://lh4.googleusercontent.com/GIT4zvMIWot1-vGa5yP-gfK06Hv3PxFBtt3pfnoCu-rfgyzzJH9cmzE_KmM4l7nHyFQp0CkPWPXLNpclUgKreVsoF4uc9xoWgomUDC6PpO35n2AB9jAZut4b7ypa-DBE-qzkPm3dGGpsXq3cjo8VMYI)

![](https://lh4.googleusercontent.com/p3BIQyl39Lda7Jk32P7hNrYXa_UGf8vTTsErcemPV1bW0C3u1r-n-lqs3s8ry2JzWWI259EeJ27wzgSVBN7NUV7kagRCnXdWWqcx8ERJauhYuw2WCq_FiSxoYA1ThmtGFIjIKe8Atu9AYsNhjf3MN6Y)

![](https://lh4.googleusercontent.com/EbqBiT0L6BVPrfDm20_-5X9pjnBxo2Q06xYu7Buza4TmXE1Ynzbhj7Ilt9k6OefC_A2hzE6vU7K_Zb9bNCD2-Uq9FLcBQ5wwPZUc3IyJcabE-HZDN1jyTpJxm-9GimCe53Xncm-RqWxEFY8-KQ2K8v8)

Again go to cam simulator and play: 

![](https://lh6.googleusercontent.com/GROB1O22IV2jNBNGS2L7ajJVkMBQP-I78JQcKFM0ZmXja_hO3P9Ah0kx2TDDMEORq7wkDktlllmFP-vcHdcx6GGlKksKP1BAp2G0VymrGvPViQBHpR4ZCOcVkx1BJOdlGyibval7Lj1-cQGlwv7TTEk)

And this is how you save the file: 

![](https://lh4.googleusercontent.com/Ji8mhsXp8-WafykXysJSgZsCTPTQ7jPex0PKjGvKGVGGHlPVTVGMTXwDD2od8tbwn5pF9EXsXI-Kx0hs9xzJvzexEhWUOlCVP0TCcWqmMXA_FUvsIHwh2aRraZ42JHOXxVt-bstr2hTi3ZKOniC1Pp0)

![](https://lh5.googleusercontent.com/ZJKviMq3tW6TWJ1uGTFNpp9GVpN0ggLDAfbyJ7mQAj1L6pB7pQNDG2aeiS-Aj4C26gJ3hobMRgX57cwJRW4ijxyKMW_dbCOGq01PaKO_aSyXaoUaHTyQ_lT-LIngQ7PgoCghEJoiCA_Ke9quVK2mGQ0)

Learn some useful tools from freecad
------------------------------------

Here we will create a spreadsheet: 

U need to have a premade 3D design and follow the steps: 

![](https://lh6.googleusercontent.com/fKefJNSpRaFcRwJ6cy6q3HgX5E8sSTTRTHC1bVvwvAdyNn5x1QKYYLRSxf-B1Msd7-y4wJzJ18Qp1NeqzKmsGnaiMJ-zw_26Rk8D0xg6ajdyUguexNCv_4VbrhF1Ip8L5q30i5aFM6saPUA0BMSic2s)

![](https://lh6.googleusercontent.com/dRGztE2cz0KPpHt356b3C-0i2lQyVm7f41qIyJnRgmIIW2QZxSsnFPf6I3AjHuCWvp2vxx67ZF70HoFRmWquK0uqMcZX3FXTDi4ZY85e_AVBc9MobMg-LjMyXTwC-wzpqPBJsPV8XcPPJ9tURz6UH10)

![](https://lh5.googleusercontent.com/6dOYtdvoX8x2Aogn2K49mhDOB6rQvblGLPkD_6g-uUR-t3dB7-a35ryLqtI4TmqBHbtC5GGLuLnYQSTHpuHqdn7IEYvUkroxiHXbP1RQw4vFdpJVkUegr3D_Ztf2cMTksnq_fqq81jXPGt3X5hqj1Vo)

![](https://lh6.googleusercontent.com/ae0vi7ZaIMqOD8T7bkH-TPuZDwkQ1x9FWSY5oj5RxO2u4fNtIyV_RnczYeLA2XrGf3-Uc5_yekFVOFSGgfyfoCuJn8HVjtZ-_XOb-nS4Xy8tOwV75xTOXkdktaDA2OaaZ_gtmLTTbHFZsEd5zp_s760)

![](https://lh6.googleusercontent.com/DhRpFaO-X-wvicKxF0HVSNm6zy2WZhjSdMmyvFGmum0pkESG-nuUF1INKNmgxibzvAaBkqm0tOG64EhDCk_qUVB-0hsllXEMgW0nuXiWlE0YGUCszUk12KtSudaBVJssqtignLy56dZL9uzJRrEJrRE)

Now we will add some text. 

U also need to have a premade 3D design. 

And after that you follow these steps:

![](https://lh4.googleusercontent.com/jdAPjpQ2Dml5LU1sGN2IwX8y_nkR4e0kMjdzdW3qnm06EMTvSZzpx_CFqqtKWMnR7FUxBZlTGOaocqQtL5E0Tui1DGl6uh-HxJxktRcjCbc9ms9-FRCIEXSZMHznjyXXeF_4Nc0ARqczEKRbFTllJ60)

![](https://lh5.googleusercontent.com/9-PYB-_RVM9ujpU35z5F2F97_LlhdE_V8q2Z0nFH849w3sPVHOLl7Ylg8FvQIwOHbhhlEFU970YZXnS5ONO1kJq5EXtt-EpQNuLmjjIEmamCtPpezbxag-RqKiwK3EGNUfr7RsVNuqiShasIwJmAO5s)

![](https://lh3.googleusercontent.com/y5ZhnEBB7J5TGteyxhOwr5PVyEi4PMqAwLkRR-S5arSWpAK2CEDNjJlBoJUGfWQ-2isZWurcN593jdWJ8qetpNS7rAcTZM9smQm_-E_vuXOC7FVbitTlXXCzESvaBIAKk3ir5hTpnLfZV_xU0512QmU)

Day 14 (30 juni):
=================

Day 15 (lab):
=============

Laser Cutting
-------------

![](https://lh4.googleusercontent.com/Xrj9aM6JLog4pmMlzSXLC3B0rC-3DxcDtZdel43EBHHA5EtmexOVwG2bXprgl_5UwMA8WmKtuv_U2kSgI7i9OOKRAio9_U8IBLYsaEohjxMZ7AO-EfXYJp4iXVpYuZ-qna-HVlhBfRq7JtZhd91o9DQ)

speed = 1200 mm/min

S-MIN = 0

S-MAX = 100 (for engraving) 

Outer: 5 passes with S-MAX = 800 and 2 passes with S-Max = 1000

Use lasergrbl to cut. 

<http://lasergrbl.com/download/>

Make a png of what you want to cut. 

Open the png in lasergrbl 

Set the brightness, contrast, etc. 

![](https://lh6.googleusercontent.com/GHXs6AdVcPhy1GPy5y8BkAxeArX6UTWXIjoFBtMfu5ZGiYreRYHgBcefJjidkhUV5iaUSP4qN-Th3s9jIP9-lHNFNDZQd664Z2ogUe9BU3MwyrxZ76erhjQIb4K8n9Fs_4OlMzvzlKfitpvyDtyHB-g)

Set the power and speed. 

![](https://lh5.googleusercontent.com/p9EbFDa9s2S7yF4rDbIv7-5_TQkVkZXuksEK_toqgmGHDh7tnVq521-oPo1IKzCBAIeJfNuf_mIs7iIdNEYHIj6P50E5Xul5brNbDakuHmfsgFqxQe4nBrnnz0Xg5F5KanhR3nS7jUuVxnrBwpAxCOc)

This is what you get

![](https://lh4.googleusercontent.com/LGG137Zj2TlEv81p2VAO5zQ2thSq0co2rCqHu5Golh0h4TVEgbPQ_KgQXUZE34ZZ7QgJ8KKMjRk7Q9l_J8qGEpcMreKEcJXiOWiBY9Q4c0klaYTds9CaiyDR6fUdg4DHMfYRYqKaeiz9seNuv0ZDAhU)

Also make an outer player in freecad for the image that needs to be cut. Import the outer 

layer after you already engraved everything. And also make it bigger than the size of your 

image.  

![](https://lh4.googleusercontent.com/5TmuvWtysfA9qOTBxwvTFl2TSoSJ01hqBZ6v3SeHf8dJ5eUrxDSUxH99uOgmP8JxaB2mqU1G5nlNZNBt1dKTKeosP19nfrwNxvBZ7qTBVXkJM4VVsX8w6ikRpaaQ0RL3nZWvzYpWOZ5k0VdWLUO9GR0)

Save this as an svg file.

![](https://lh5.googleusercontent.com/THbIxIm3IUew_XdlQSMAxMbT5UXBWBhEdYDfxh37hJ3f40p69RFrEAIzGAZ_aGqA4J07fV-E60rfHFrCFo8r71_DZP6nM5_5fBhIM9VTR2h0agjoIG24lOOexj9z8bq1py1QUe6GO9Mp4evHRwXWFMk)

This is a diode laser cutting machine. 

![](https://lh3.googleusercontent.com/g2N8HnwUUdUohq9ylCc7R31lj8n2tO7zjPvoy5ZfRTg-2peccSmq5o3RbFG-uyXWQPg_7TfV0fvyNGQpVBQ967ZlZUsZFf7uWtb6CtoZFe3mcooRpJwqXpRPStUoaIKA7vl3d-zQW1Jtv-5qvfxAMTk)

Connect your laptop to your machine.

![](https://lh5.googleusercontent.com/fHmxX6p9sEbbhwNHigGYfwiEPlTFHLKktVR_XaR-4hSUOyBysg8G9X99K7b41ipfbEyg42VZEZ31G0NwOPvo0AF5lPCY3xjdW7FnDJYq0tuO2LFP9PkbjGjIwsuw7SpVCXhrOjJx2ClMr-5ksVgKEIk)

Move your laser cutter with the arrows and set up your begin coordinates. 

Check your center, frame, etc.

![](https://lh5.googleusercontent.com/AcdwLDlevD3SyYr6sLvvGHPuCniEwcu9zoLLO4cHJ5ub70grZ3G5JdWV5_siwNIvBvsqdM5fS2bWoqnIDu6Cy9CgcpPM6Ehm7bMgEbtLdLFhe0jhR9ey2YZ-Jm-IkNypbzzSaByQ-sm_77GG2IZdQ4o)

Scan and cut machine
--------------------

Scan an image and cut it process: 

![](https://lh4.googleusercontent.com/ml6SZUkfQf0JUjfJ0u8fbMeVAGWnOqZ0R6aQ5nMu8ZMxCJC6kYU8t20VR0B9ySMUyT3fRnppkbEivTitkJGkTN3XI16tV1AbvxbLSl9q6qARjCWoRWgpeJdu8FXfReHviDXvBxKCSfqjBMHWF8jY_xM)

Select scan on the screen, then scan to cut:

![](https://lh4.googleusercontent.com/TcEkyamzKXHNRrWRq-KXWdfCfJVqXL3j8Uziqo52c8xI7DZVQtg5WmS-54BwCi1XzC1y7tXGxzMIQ5wRd-pPCfimDPGEQWj7WiPXQ-Zb39lztZ6_84tdZ_40zI5gwOeqIiAgv8iDyhS6c1xFrPlMy9U)

Your scanner lever is a button on the side of the machine. It should be on the second level.  

![](https://lh4.googleusercontent.com/0lFiiaBRZOipWOQajiXLMs9wS14LnlXogiBBG7j78KhJ-hDsp1XZuyN3ZZi4U1UvOA9FFGrObVVPfDJ5vafbzKNuVe7G2VLwg_ce7Suygtw_hkUmNKbCu619GLfCvZb4FoLb-RhRHOqX8kAE_VIweFg)

After scanning you'll get this and you can select what object you want to save. 

![](https://lh6.googleusercontent.com/1-thGk_q2LkYHl-m7O94OVyovEmNAHUYcOT9pIaVeTFONuH2hAf3lpvdmUUq4vQQgZidxHbCngRV8CHNaQQwY25bIJcTSY4fQRid4iRwijcdah23LG6HV2KYrAAzJ7y7QW3Ic7oT0l9tCs97N-nnKoY)![](https://lh5.googleusercontent.com/O2rCFVicEMFASH25S0jPvK9tAH0hqB-UF36TCkfyX9Z2X3dwnm_b4wp5yWlfINeNTHxREeDWhseQcl5Y4Nz1Wn6nLSvpIpq8NB001HGW9Z9w9CR7jXCqyM66EooUTyDaU4y6IiFjQOUlxyZe4jdwY90)

After clicking ok, the image should be saved. 

![](https://lh5.googleusercontent.com/lj2Ex7rLlnmZst3sJoAk2gMEx4lsy2rZFTkJnfKQ-3Kc-GSSpMhFAcUQhr5B3EkmRxRCSdlIVCU7BHWgsQrYHAw8PwuVwurxzHJoueZL9Y0lqpAOND9siunOMuwD4BCBqXKFKdIPfx45_T6y_Ql2Ce0)
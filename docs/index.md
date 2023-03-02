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

![](https://lh4.googleusercontent.com/zikIke4-GwMFXFvhgG2h3Jdkyhu1y8ugQO86WbAJW7edaV8XmDqBcKJKGdgDKJVfRZOPYiYMd7Lkr2_CgX8XnPZU7rPl9j9nrrdIdgp0cdMgfBE7mjZvaxB_83XWiOdMFOsxLHZnTYUnIL-u3T1-NGc)
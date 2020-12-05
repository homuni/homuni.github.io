---
layout: post
title:  "Python - Git - Debug"
date:   2020-07-27 23:47:20 +0200
categories: IT amateur
author: "Huihui"
lang: en
ref: bug
---
Last night, I was doing my python homework.

class zaehler:
    def _init_ (self, startwert):
        self.zaehlerstand = startwert
    def weiter (self):
        self.zaehlerstand += 1
    def zurueck (self):
        self.zaehlerstand -= 1
    def wert (self):
        return self.zaehlerstand

x = zaehler(4)

However, I am getting a bug all the time.

AttributeError: 'zaehler' object has no attribute 'self'

Finally I found out it was because of "_init_". "__init__" ist right.
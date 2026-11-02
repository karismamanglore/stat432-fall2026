---
id: w10-kum2-oob-tuning
title: "Can OOB tuning give optimistic results?"
author: kum2
---

We use OOB error to compare random-forest tuning settings and select the best model. If we try many combinations of `mtry` and node size, could the selected model’s OOB error become overly optimistic even though each observation’s OOB prediction uses only trees that did not train on it? Why?

+++
title = "Google Location Data"
date = 2020-08-22
draft = false
tags = ["Tableau","Python","Pandas"]
categories = []
+++

My first "real" project in terms of finding a dataset and turning it into something.

This is something I've been saying I'll do for a while and I finally forced myself to just start and see where it goes. Regardless of what the outcome was, I simply knew that starting 1 project would lead to working on more and improving as I went.

My goal was to keep it simple. Very simple. I have a tendency to get miles ahead of myself and turn a small project into a monster one that I'll never finish. "Perfect is the enemy of good", or something to that effect.

I pulled data from Google's COVID-19 Mobility website (https://www.google.com/covid19/mobility/) as I had been shown some of this data a few months back. Google produced some quick visualizations which were helpful at a glance, but I wanted to build something a bit prettier and certainly more interactive.

Step 1 was to simply download the data set. I knew I only wanted to visualize Canada to start but I downloaded the whole thing anyways - A few lines of code in Python could get me there and it was good practice, even if it was simple. This actually led me to something I hadn't done before - exporting a csv file out of Jupyter. Again, simple. But still new to me.

One thing I learned through this short process - when loading the csv, Pandas has to decide what each column's data type should be. You can specify a "type" which speeds up the loading time for Pandas.

# FLO-graphics

# Rebrand
In Decmber 2017 FLO went through a rebrand and got a new logo and website (http://flo.cash). 

All rebrand graphics can be found [here](rebrand/README.md). Below are some of the most ubiquitous rebrand graphics.

## New coin logo
![FLO](rebrand/FLO_teal2.png?raw=true "FLO")

## FLO Pulse

### Twitter icon
![FLO Pulse](rebrand/FLO_white_redorangebgdarker.png)

### FLO Pulse Style Guide
Two gradient colors:
(new)
#F85D28 orange
#F80000 red

(original)
#FF6029 orange
#FF0000 red
With brightness -9

Orange goes on top


## Lightblue icon 
![FLO](rebrand/FLO_twitter_300.png?raw=true "twitter logo")

# Previous Florincoin graphics (before the rebrand)

Before the rebrand these graphics were used for Florincoin(FLO):

## Florincoin 
![florincoin](FLORINONLY_Shadow_500px_DLVR.png?raw=true "florincoin")

## Yellow and blue badge
![yellow and blue badge](flo-blue-small-2.png?raw=true "yellow and blue badge")

## Flat icon
![flat icon](florincoin-logo-135x135.png?raw=true "flat icon")


## Tools

Find files that aren't PSD'd yet
```
find . -regex  '\(.*xcf\|.*psd\)$' | cut -d '.' -f 2 | uniq | awk '{print "."$1".xcf"}'
find . -regex  '\(.*xcf\|.*psd\)$' | cut -d '.' -f 2 | sort | uniq -u | awk '{print "."$1".xcf"}'
```

Convert to psd
```
convert *.xcf *.psd
```


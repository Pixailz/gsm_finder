# GSM Finder
A script to find ALL android devices, spec, price, part price
<br>

## PlayStore Supported devices
first i need a list of all devices, first approch is to take the playstore supported devices from [here](http://storage.googleapis.com/play_public/supported_devices.html)<br>

TWO OPTIONS:
- take the website as html
- take the csv file given
<br>

## CSV FILE
<br>
i can read csv file from the lib [here](https://docs.python.org/fr/3/library/csv.html), but because i'm a fucking no life and i wan't to learn, i'm gonna write my own csv reader ;)<br>
<br>

## DATA SCHEME
```html
<brand>
    <name>
        <ref>
            ...
            ...
        </ref>
    </name>
</brand>
```

```html
<samsung>
    <galaxy_grand_prime>
        <ref>
            SM-G530H
            SM-G530BT
            SM-G5306W
            SM-G5308W
            SM-G530F
            SM-G530M
            SM-G5309W
            SM-G5308W
            SM-G530MU
            SM-G530Y
            SM-G530H
            SM-G530R7
            gprimelteacg
            SM-G530W
            SM-G530T1
            SM-G530P
            SM-S920L
            SM-G530T
            SM-G530R4
            SM-G530FZ
            SAMSUNG-SM-G530AZ
            SM-G531H
            SM-G531BT
            SM-G531F
            SM-G531M
            SM-G531Y
            SM-G532F
            SM-G532MT
            SM-J250F
        </ref>
    </galaxy_grand_prime>
</samsung>
```

## TODO
- ALL THE THING BRO

## TTA *(to think about)*
- Update supported_list

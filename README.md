# AC Infinity Home Assistant Card

This is my first repository so forgive me if I'm doing it wrong. 

I basically made five folders with the code I used for my Home Assistant card. I use the card two different ways, as a popup card and as a regular card. The reason I have the popup uis because I originally had a dashboard view with a lot of other information on it so I setup the AC Infinity card to operate as a popup. I still have that dashboard view but I also now have a dashboard view with both my AC Infinity controllers in a side-by-side view for comparision. I change things as I need them or as I feel I don't need them which is why you might see something repetitive like the control for the max or on level of a device. I have both a bar slider and a number box because I'm trying out both to see which one I like more. 

The reason I use the decluttering card is because I have more than one AC Infinity controller and also because of the multiple ports on the AC Infinity controller. The decluttering card helps with both. So if I purchased another controller or the controller that has the 8 ports I could just change the amount of tabs and then send a specific variable to the declutterring card. You'll notice I use the same naming convention for my device tent_001_port_001 or tent_002_port_002. I did not use the type of device connected because I often changed them and it was easier to use a general term for each and just remember which each one was. That could easily be changed though by changing the name of each tab of the custom tab card.

The button templates were also used to cutdown on the amount of code. If one vriable needs to be changed I change it in the code after I call the template because it overides the template. The default button template is a template I use throughout my entire dashboard for all my views. It works with the dark theme that I'm using. You might need to adjust that to fit your dashboard theme. This is also true with my use of several different type of stack cards. The different cards produced different results for me when it came to the border or background so I used the cards that worked for me for that particular secion.

The template sensors are in my configuration yaml. I actually have use the `template: !include templates.yaml` function in my main config file to point to a `templates.yaml` file that has all of the templates I use for my entire dashboard. That is why they begin with `sensor` and not `template`. The templates were needed to properly help display whether devices were ON or OFF or whether they were PLUGGED IN or UNPLUGGED.



## Custom Cards:
Custom Button Card: https://github.com/custom-cards/button-card

Custom Stack In Card: https://github.com/custom-cards/stack-in-card

Custom Declutter Card: https://github.com/custom-cards/decluttering-card

Custom Flex Horseshoe Card: https://github.com/AmoebeLabs/flex-horseshoe-card

Custom Mod Card: https://github.com/thomasloven/lovelace-card-mod

Custom Vertical Stack In Card: https://github.com/ofekashery/vertical-stack-in-card

Custom Browser Mod Card: https://github.com/thomasloven/hass-browser_mod

Custom Gap Card: https://github.com/thomasloven/lovelace-gap-card

Custom Slider Button Card: https://github.com/mattieha/slider-button-card

Custom Tabbed Card: https://github.com/kinghat/tabbed-card

Custom Number Box Card: https://github.com/junkfix/numberbox-card


## Card Preview

![324518180-ba43d79f-7c2f-4cfc-bbed-49e0aeb28568](https://github.com/almighty059/acinfinityhomeassistantcard/assets/63380298/ab069ae2-39a3-4269-a66e-412b1f435e6b)


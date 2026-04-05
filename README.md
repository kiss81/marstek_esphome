# marstek_esphome

Work in Progress: based on the work of Fonske and Superduper1969:

added:
1) Calculated SOC. Based on cell voltage and Coulomb counting
2) charge and discharge cell voltage limits. By default: charge shutoff @ 3.50v and discharge shutoff @ 3.20v for better lifetime
3) charge slower for 3.40v to 3.50v: 500watt for better lifetime

https://github.com/Superduper1969/MarstekVenus-LilygoRS485
https://github.com/fonske/MarstekVenus-LilygoRS485

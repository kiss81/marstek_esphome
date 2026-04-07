# marstek_esphome

Work in Progress: based on the work of Fonske and Superduper1969:

added:
1) Calculated SOC. Initially based on cell voltage, then on Coulomb counting.
2) Self learning (netto) battery capacity for better SOC estimation + logging.
3) charge and discharge cell voltage limits. By default: charge shutoff @ 3.50v and discharge shutoff @ 3.20v for better cell longevity.
4) charge slower for 3.40v to 3.50v: 500watt for better cell longevity.
5) Default 10 days interval to bypass the voltage limits to allow recalibration of the Cells / Marstek SOC. (Direct overide available)

https://github.com/Superduper1969/MarstekVenus-LilygoRS485
https://github.com/fonske/MarstekVenus-LilygoRS485

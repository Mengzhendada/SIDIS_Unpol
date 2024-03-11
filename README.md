This directory collects all the SIDIS head files

They all have too many cout lines to check, need to check results and remove them

SoLID_SIDIS_H2_CS.h copied from CrossSection_H2, which simulate 3.5 days of H2 data. The difference is Np and Nn, lumi is same as He3, the statlist numbers is 1/90 compared with He3 statlist(time is 30 times less(3.5 compared to 70, actually just 20 times less), and number of nucleus is 3 times less), this head file uses fixed x bins, dynamic phih bins, if not enough counts, combine x bins

SoLID_SIDIS_D2_CS.h copied from CrossSection_D2, which simulate 3.5 days of D2 data. The difference is Np and Nn, lumi is same as He3, the statlist numbers is 1/30 compared with He3 statlist(time is 20 times less, and number of nucleus is 2/3 of He3), uses fixed x bins, dynamic phih bins, if not enough counts, combine x bins

SoLID_SIDIS_3He_CS.h copied from CrossSection_try1, I tried to do fixed xbins, and dynamic phih bins. If not enough data in the xbin, I would use large xbin

SoLID_SIDIS_3He_CS_old.h the old dynamic x bin 

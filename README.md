# cmip6_test

- Info on CMIP6 data
https://pcmdi.github.io/CMIP6/Guide/dataUsers.html#1-experiment-design \
https://discourse.pangeo.io/t/the-cmip6-data-for-our-hackathon/73

- Ways to access CMIP6 data
https://medium.com/pangeo/cmip6-in-the-cloud-five-ways-96b177abe396

- CMIP6 variable list \
https://pcmdi.llnl.gov/mips/cmip3/variableList.html
https://docs.google.com/spreadsheets/d/1UUtoz6Ofyjlpx5LdqhKcwHFz2SGoTQV2_yekHyMfL9Y/edit#gid=1221485271 (I like this one more)


- Pangeo cloud variable list
https://pangeo-data.github.io/pangeo-cmip6-cloud/overview.html

- Pangeo project template scripts:
https://nbviewer.org/github/pangeo-data/pangeo-cmip6-examples/tree/master/

- Some more template scripts that work on Pangeo Binder \
https://github.com/hdrake/cmip6-temperature-demo/ \
https://github.com/pangeo-data/pangeo-example-notebooks

**Quick CMIP6 variable names**

1. 2-dimensional variables

- clivi: ice water path
- clwvi: total water path (ice+liquid)
- prw: integrated water vapor
- pr: precipitation
- prc: convective precipitation
- stratiform precipitation = pr - prc

- clt = total cloud fraction (integrated)

- ts: surface temperature (e.g. SST for oceans)
- tas: 2-m temperature


- rlut: outgoing longwave radiation at the top of the atmosphere
- rsut: outgoing shortwave flux at the top of the atmosphere
- rlutcs: as rlut, but for clear sky conditions (no clouds)
- rsutcs: as rsut, but for clear sky conditions (no clouds)
- SW CRE = rsut - rsutcs
- LW CRE = rlut -rlutcs

2. 3-dimensional variables

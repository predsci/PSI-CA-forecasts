## Influenza Forecast Methodology
Deterministic fit of a compartmental SIHR model to weekly, CA region level, 
hospitalization incidence profiles, followed by stochastic simulations using the inferred
parameter distributions. The ‘H’ compartment is divided into two compartments to ensure
the correct generation time for the Infectious compartment and proper fitting of the portion
of infectious individuals that are hospitalized. For each of the five CA regions, the model
fit is inferred by an MCMC procedure and run forward at a weekly cadence.

### File Structure
The submission files are formatted according to the [FluSight](https://github.com/cdcepi/Flusight-forecast-data) specification, but with an extra 
column 'region_level' specifying the California region type ('region_flu' or 'region_healthofficer'). 
The region_level column is set to 'state' and location is set to 'CA' to indicate a forecast is for the 
entire state.  Otherwise, the location column is filled with a complete region name.


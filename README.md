# Energy Meter Logger
    $ git clone https://github.com/samuelphy/energy-meter-logger

 I have just redone and reused the awesome project demonstrated by samuelphy energy meter logger from the above git link.

 All i have done is read the python code, yml configuration and changed it to fit my local needs.

EM09.yml actually is created to suit the energy meter modbus/rs485 register information provided by the MECO manufacturer of
EM09 instrument.

Many thanks to SamuelPhy

## Steps

 1. Install Grafana
 2. Install Influxdb
 3. Install minimalmodbus python module
 4. Install influx python modules
 5. Setup database in influxdb
 6. Configure yaml files
 7. Connect the Instrument
 8. Add the user to dialout group if not already (only then USB devices accessible)
 9. Verify the python script - with debug, info logs
 10. Setup Grafana - add widgets, datasources
 11. Configure dashboard widgets, datasource, queries
 12. Save, Share

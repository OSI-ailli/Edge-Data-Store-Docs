---
uid: modbusOverview
---

# Modbus TCP EDS adapter

## Overview

Modbus TCP is a commonly available communication protocol used for connecting and transmitting information between industrial electronic devices. The Modbus TCP EDS adapter polls Modbus TCP slave devices, and transfers time series data from the data source devices into Edge Data Store. Polling is based on the measurement configuration provided, and models the register measurements in a Modbus TCP data source.

The Modbus TCP EDS adapter communicates with any device conforming to the Modbus TCP/IP protocol through a gateway or router. The Modbus TCP slave devices and routers do not need to be on the same subnet as Edge Data Store.

You can add a single Modbus TCP EDS adapter during installation. If you want multiple Modbus TCP EDS adapters, see [Edge Data Store configuration](xref:EdgeDataStoreConfiguration) on how to add a new component to Edge Data Store. 

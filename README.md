# Updated

This is a fork of https://github.com/gdziuba/http-event-collector.

It has been updated to allow dynamic passing of index, host, sourcetype, and source.

## Synopsis

The purpose of this project is to allow node-red to publish a node-red payload to Splunk's HTTP Event Collector. 

## Motivation

Wanted to make an easy avenue to publish data into Splunk through Node-Red.

## Installation

The easiest way to install is through the Node-Red Palette Manager that can be found in the menu on the top right hand corner of the Node-Red ui.

### Manual install with npm

### Install from source
From github:
Navigate to the your home directory on linux is is ~/.node-red/node-modules
```sh
git clone  https://github.com/alacercogitatus/node-red-contrib-http-event-collector.git
```
```sh
cd http-event-collector
npm install
```

## Setup
[To configure Splunk's HTTP Event Collector, follow these instructions.](http://docs.splunk.com/Documentation/SplunkCloud/6.6.3/Data/UsetheHTTPEventCollector#Configure_HTTP_Event_Collector_on_Splunk_Enterprise)


## Examples:

### Node Red Payload Modification for Metadata

Yeah, add something here.


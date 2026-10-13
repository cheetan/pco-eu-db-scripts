# PCO EU Handover Dashboard Generator

## Overview

This Python script generates an HTML dashboard used by the PCO EU DB L2 team during shift handovers.

The dashboard consolidates Snow and SPC Tickets and presents it in a user-friendly format to support shift handovers between team members.

## Features

- Generates an HTML dashboard
- Collects and displays Snow Cases, Snow Alerts that remain from former shift
- Displays SPC Tickets scheduled on next-shift, on-going from former shift and Longrunner tickets
- Special section named "Information", for instructions that needs to persist from HO to HO
- Produces a portable Handover that can be shared with the next shift

## Requirements

- Minimum Python 3.14
- Required Python packages will be listed in 'requirements.txt'

## Usage

python dashboard.py

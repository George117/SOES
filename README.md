https://github.com/OpenEtherCATsociety/SOES/issues/121#issuecomment-1175789968

Simple Open Source EtherCAT Slave
====
[![Build Status](https://github.com/OpenEtherCATsociety/SOES/workflows/build/badge.svg?branch=master)](https://github.com/OpenEtherCATsociety/SOES/actions?workflow=build)

SOES (Simple OpenSource EtherCAT Slave Stack) is an opensource slave
stack that is very easy to use and provides a small footprint. It is a
good alternative to more complex stacks on the market.

Overview
----
SOES is an EtherCAT slave stack written in c. Its purpose is to learn and
to use. All users are invited to study the source to get an understanding
how an EtherCAT slave functions.

Feature list:
 - Address offset based HAL for easy ESC read/write access via any
   interface
 - Mailbox with data link layer
 - CoE
 - Object dictionary
 - SDO read and write for all sizes including segmented transfers
 - Easy portable C-code suited for embedded applications
 - Fixed and/or dynamic PDO mapping
 - FoE with bootstrap template
 - Support for Little and Big endian targets
 - Run polling, mixed polling/interrupt or interrupt
 - Support for SM Synchronization 
 - Support DC sync0 and DC Synchronization
 - Add stack configuration via new configuration parameter to/or from 
   "stack"_init
 - EoE

TODO
 - Update documentation
 - Add EoE sample application

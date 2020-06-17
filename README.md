# thaw_star_catalog
Thaw Star Catalog

## Notebook One (Thaw Star Catalog_ntbk1)
This notebook takes the three separate formats of the published Allegheny parallaxes and formats them all into Astropy tables matched with their YPC counterparts. It also takes the additional fourth table of published AO parallaxes with no TSC number, for a total of four tables of raw data. To do the matching, Vizier's online YPC is queried using astropy.
At the end of this notebook, you have four tables with all originally published data preserved with the added matching to the YPC.  

## Notebook Two (Consolidate TSC_ntbk2)
In this notebook, the four tables that have already been matched with YPC, will be formatted (RA,Dec,milliarcseconds, BD number etc.) and information will be extracted from each one to fill out a comprehensive, single table. Some of the original columns from the printed publications that were deemed superfluous have been removed. Missing YPC entries (provided by Data Entry One) are reincoporated into the TSC by the end of this notebook.
At the end of this notebook, you have a single, uniformly formatted, table, with YPC matching, including ALL missing YPC entries. 

## Notebook Three (.../subtables/Match with No. of Observations_ntbk3)
In this notebook, the TSC (that has already been matched with the YPC) is matched with the index cards.
Publication dates are incorporated into the working TSC. 
A "master" table that includes all Thaw, YPC, and index card information, is created. 
Subtables are also created for each TSC star with relevant YPC and ALL observation details.
This notebook, and all files created from it, currently, live in the /subtables folder of the main directory.
At the end of this notebook, you have a master table and all subtables named after each TSC number. 

## Notebook Four (Append Missing Info to TSC_ntbk4)
This notebook is meant to be a "working" notebook where you can easily add columns of data to the existing master table, fill out entries in the master table, or extract information from the master table and write smaller, specific tables in .tex or .csv (or any ascii supported format). The output of this notebook is left up to the user. 

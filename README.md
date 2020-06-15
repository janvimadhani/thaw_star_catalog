# thaw_star_catalog
Thaw Star Catalog

## Notebook One
This notebook takes the three separate formats of the published Allegheny parallaxes and formats them all into Astropy tables matched with their YPC counterparts. To do the matching, Vizier's online YPC is queried using astropy.
At the end of this notebook, you have three tables with all originally published data preserved with the added matching to the YPC.  

## Notebook Two
In this notebook, the three tables that have already been matched with YPC, will be formatted (RA,Dec,milliarcseconds, BD number etc.) and information will be extracted from each one to fill out a comprehensive, single table. Some of the original columns from the printed publications that were deemed superfluous have been removed. 
At the end of this notebook, you have a single, uniformly formatted, table, with YPC matching. 

## Notebook Three
In this notebook, the TSC (that has already been matched with the YPC) is matched with the index cards.
Publication dates are incorporated into the working TSC. 
A "master" table that includes all Thaw, YPC, and index card information, is created. 
Subtables are also created for each TSC star with relevant YPC and ALL observation details.
This notebook, and all files created from it, currently, live in the /subtables folder of the main directory.
At the end of this notebook, you have a master table and all subtables named after each TSC number. 

## Notebook Four
This notebook is meant to be a "working" notebook where you can easily add columns of data to the existing master table, fill out entries in the master table, or extract information from the master table and write smaller, specific tables in .tex or .csv (or any ascii supported format). The output of this notebook is left up to the user. 

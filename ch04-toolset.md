## Standard Datasets

We will use these datasets repeatedly:

* Every article in Wikipedia
* Two years of hourly pageview counts for every page in Wikipedia
* Page-to-page link graph for Wikipedia
* 50 years of Daily weather for (the globe? the US?) (NCDC GSOD weather)
  - 20,000 weather station locations
* 60,000 UFO Sightings
* (may need to add another dataset that is more clearly OLAP'y)
* (Possibly also the  Airport-Airport flight graph)


(-> download instructions)
(-> Amazon public data sets)


## Your cluster

Designed for a "write and debug it on your laptop, run it in the cloud"

You will need a real hadoop cluster running in distributed mode on real data
for many of the exercises and to truly grok what is happening.

Goal is that you can do anything with
a 5-machine cluster of `m1.large` machines 
-- cost is ~ $2.00/hr.

(-> Instructions for launching using ironfan)

## Programs


Why not Hive? The appealing thing about Hive is that it feels a lot like SQL. The dismal thing about Hive is that it feels a lot like SQL. Similarly, the wonderful thing about Pig is that its operations more closely mirror the underlying map-reduce setup, making it easier to reason about the performance of your tasks; this however means more brain-bendy at the outset for a traditional DBA. Lastly, Hive organizes your data -- useful for a multi-analyst setup - but it's a pain when using a polyglot toolset. Ultimately, Hive is better for an Enterprise Data Warehouse experience, or if you're already a SQL expert. but all else equal, for exploratory analysis and Data science, you're better off with Pig.


### Ruby & Wukong

### Pig

### ...


## Wukong

Narrative Method Structure

* Gather input
* Perform work
* Deliver results
* Handle failure
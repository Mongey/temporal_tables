# CHANGELOG

## 0.4.0 (2016-12-13)

 * added multi-environment spec framework
 * bug fix: mysql2 gem should now be functional

## 0.3.1 (2015-10-08)

 * bug fix: accepts reserved keywords for postgres column names, like "default"
 * bug fix: correctly handles models nested within modules

## 0.3.0 (2014-07-04)

 * Updated for Rails 4

## 0.2.7 (2013-07-10)

 * bug fix: fix problems with STI instantiation

## 0.2.6 (2013-05-23)

 * bug fix: explicitly set sti_name on history classes of STI subclasses

## 0.2.5 (2013-04-24)

 * bug fix: rename_column wasn't linked in correctly

## 0.2.4 (2013-03-07)

 * bug fix: another fix for removing indexes

# 0.2.3 (2013-02-25)

 * bug fix: history classes did not have the correct primary key set, which could provide unexpected results in certain use cases
 * added a history method to ActiveRecord::Base objects to return a sorted list of all historical versions of that object.
 * added prev and next methods to history objects to aid in traversing the historical versions of an object.
 * added orig_obj method to history objects to return their non-historical objects

## 0.2.2 (2013-02-25)

 * bug fix: add_index with specified name caused an index collision

## 0.2.1 (2013-02-21)

 * bug fix: removing indexes didn't work

## 0.2.0 (2013-02-21)

 * added support for indexes

## 0.1.0 (2013-01-10)

 * added history querying

## 0.0.6 (2012-11-29)

 * optimized the history table index

## 0.0.5 (2012-11-29)

 * added indexes to history tables

## 0.0.4 (2012-10-19)

 * added updated_by support
 * added some configuration options

## 0.0.2 (2012-10-12)

 * added support for rename_table
 * added add_temporal_table(table_name) method
 * added remove_temporal_table(table_name) method

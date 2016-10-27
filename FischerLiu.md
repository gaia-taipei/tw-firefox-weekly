## 10/17 ~ 10/21 ##

### This Week ###
* [Storgae Management]
  - Create, organize and prioritize bugs list
    - The front-end meta bug: Bug 1309118 - [Meta] Implement Storage management

  - Plan to discuss and settle down with the reviewers(:jaws, :gijs) on
    - feature turn-on/off strategy
    - Landing strategy: directly into Central or working on branch

  - Study and refactor cookie parts inside about:preference
    - The Privacy section and the Storage Management section inside about:preference both handles cookie so need to refactor code part to let cookie handling more organized.

### Last Week ###
* [Storgae Management]
  - Study how to remove HTTP cache per origin.
    - Successfully use nsICacheStorage::asyncVisitStorage and nsICacheStorage::asyncDoomURI to remove HTTP cache per origin.

  - Study how to filter target permissions per origin and list them out.
    - Successfully enum, filter and remove permision

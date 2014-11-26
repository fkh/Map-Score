Map-Score
=========

Collaboratively assessing interactive maps from government.

__Want to help? Make suggestions and edits to the scoring criteria, via a pull request or issue.__ Thanks!

#### Proposal

We identify 21 (+/-) characteristics of an online map that we care about, and set up a Google Form. Then we invite everyone to rate maps as they come out, and publish the aggregate ratings.

A score out of 21 is easy to talk about. And as cities make improvements, we can re-score their maps. Could produce a nice end of year report card, is highly portable to other cities, etc.

The score is a neat way to promote the principles of good engagement maps -- in order to do the scoring, you have to be familiar with all the best practices that the scoring rewards.

We could take a page from the [US City Open Data Census](http://us-city.census.okfn.org/) from the [Open Knowledge Foundation](https://okfn.org/) in presenting our comparisons of maps.

## Possible scoring criteria

Imagine each of these is worth 1 point. 

Not every map will be able to score 100% -- there might be desirable characteristics for a map that aren't possible given the data/other issues. We could make a note of attributes this map isn't even competing on (for example, a partially successful map could score 10/21 while a quite successful map could score 10/12.)

### How open is the map data? *4 pts*

* underlying data is accessible for bulk download *1 pt*
* data is accessible in a non-proprietary data format (csv/geojson, __not__ ArcGIS GDB or Shapefile) *1 pt*
* data powering the map is directly pulled from an open data site via API (ideal) *1 pt*
* a complete history of all data that ever appeared on the map is kept (even if some data eventually disappears, it is still accessible in the original data source.) *1 pt*

### Design *6 pts*

* conforms to sticky-map standards (click-and-drag pans, double-click zooms, scroll wheel zooms in/out) *1 pt*
* pinch & zoom works on mobile *1 pt*
* can functionally jump to addresses or regions via search bar *1 pt*
* provides "deep links" so that map views are shareable from the URL bar *1 pt*
* comments or other input can be provided to report bad data, and responses are tracked & accountable *1 pt*
* it is possible to filter any layer with time data by time *1 pt*

### Data truthiness *5 pts*

* available at different geographic roundups/aggregations (e.g. district) *1 pt*
* normalized by area in meaningful fashion, taking into account possible statistical hiccups (like a park district with no population) *1 pt*
* legend is labeled *1 pt*
* available as the original location dots (e.g. geocoded location of 311 reports) *1 pt*
* the time of individual dots/locations is reported when available *1 pt*

### Accessibility *6 pts*

* available in all (?) significant local language groups *1 pt*
* fall-back for screen readers (?) *1 pt*
* works in all modern browsers without a plugin (no Flash or Silverlight) *1 pt*
* works on both iOS and Android, cell & tablet *1 pt*
* works on all desktop browsers (Firefox, Chrome, Safari, latest IE) *1 pt*
* color-blind friendly (reds/greens) *1 pt*

### Possible total: *21 pts*

## Best practices

### Good online maps
[Mapping Best Practices](https://docs.google.com/a/openplans.org/presentation/d/1CA9R42cy4wjzIIWlyd0FMWvyW7BqsrzOGLQBgkwsy1Q/edit#slide=id.gafca7129_735) - slides from a presentation at NICAR by Dave Cole, John Keefe, Matt Stiles

[When Maps Shouldn’t Be Maps](http://www.ericson.net/content/2011/10/when-maps-shouldnt-be-maps/) - blog post by Matthew Ericson

### Open data best practices
... examples of best practices for open map data?

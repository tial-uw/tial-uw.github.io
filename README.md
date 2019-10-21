TIAL group homepage

[http://tial-uw.github.io/](http://tial-uw.github.io/) 



## Development
* To add a new year for publications,
  * add a new file in `bib` folder (e.g., bib/2019.bib)
  * add a new element in `publications.html`, e.g.,
    ```
    <div class="col-md-12">
      <h2 class="page-header">2019</h2>
    </div>
    <div id="bibtex_input-2019" style="display:none;"></div>
    <div id="bibtex_display-2019"></div>
    ```
  * change the starting year in `./js/bibtex_js.js`, Line 417:
  ```
  for (var year = 2019; year >= 2010; year--) {
  ```
* To understand how grid alignment work in `people.html`, read [this](https://getbootstrap.com/docs/4.1/layout/grid).


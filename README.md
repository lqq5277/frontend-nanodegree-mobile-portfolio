## Website Performance Optimization portfolio project

This is the 4th projects of Udacity frontend nanodegree.

### How to run

* clone this repository to your pc
```sh
    $ git clone https://github.com/lqq5277/frontend-nanodegree-arcade-game.git
```

* Open the index.html using your browser

* To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```
* Open a browser and visit localhost:8080
* Download and install [ngrok](https://ngrok.com/) to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ngrok http 8080
  ```

* Copy the public URL ngrok gives you and try visit it everywhere!

### Optimizations in views/js/main.js

* Replace JS functions with more efficient ones, such use "getElementById" instead of "querySelector".
* Move dom related operations out of loop in order to avoid FSL.
* Only paint pizza in visible area.

### What's next?

* Reach higher scroe on PageSpeed Insights
* Fixed all the performance issue in pizza view

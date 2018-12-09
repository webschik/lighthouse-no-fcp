## How to reproduce the issue
* `npm install`
* `npm run start`, open page `without-initial-text.html` on started local server, e.g. http://127.0.0.1:8081/without-initial-text.html
* Open Dev.Tools > Audits:
  * Device: "Mobile"
  * Check all audits
  * Check default throttling
  * Check "Clear storage"
  
* Start audits
* In "Performance" and "PWA" sections you will get "Error!" statuses.
* Open page `with-initial-text.html` and run the same audits
* In "Performance" and "PWA" sections you will get correct numbers

# Team Echo (echoStudy) Website

This static website is created using Jekyll with a fork of CloudCannon's `edition-jekyll-template` theme.

---

### Updating individual logs
  - Find your log file in `_docs/individual-logs/<your_name>-logs.md`
  - Update the markdown file to match your contributions

---

### Updating weekly management logs
  - Create a new markdown file in `_docs/weekly-management-logs/...`
  - Add the following Jekyll metadata at the top of the file (substitute `(week-number)` for the current week)
    ```rb
    ---
    title: Week (week-number)
    category: Weekly Management Logs
    order: (week-number)
    ---
    ```
    - Now you're ready to write the weekly log!

---

### Local Development
  - Install `jekyll` on your machine -- [here are instructions for doing so](https://jekyllrb.com/docs/installation/windows/)
  - Run `bundle install` to install gem dependencies
  - Run locally with `bundle exec jekyll serve` -- it should be hosted on `http://127.0.0.1:4000/`
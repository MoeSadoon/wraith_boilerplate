A boilerplate template used to setup Wraith visual tests


Steps to run before amd after comparison:

1) Edit the history.yaml config with appropriate parameters

2) Run 'wraith history history' to initiate 'before' snapshot of specified pages and page selectors.

3) Run 'wraith latest history' to initiate 'after' snapshot and create comparison gallery ('gallery.html').


Steps to run comparison between two sites:

1) Edit the capture.yaml config with appropriate parameters

2) Run 'wraith capture' to snapshot both sites and generates comparison gallery ('gallery.html)




# ag-grid-jspm-angular1
The config for ag-grid angular1 to work with jspm

Problem:

The agGrid object in lib/bootstrap.js is always undefined while the jquery object is successfully loaded.

The same config for JSPM/SystemJS is working fully for agGrid v8.2.0, but after upgrading to v10.0.1, things are broken.

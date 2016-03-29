## v-upload-gallery

A Polymer demo application for dog-fooding `vaadin-upload` element.

It uses 4 vaadin-upload elements, with different missions:
- Main area is a gallery where you can drop images from your desktop. It uses customised upload-files so as instead of showing progress bars we show images. It cancels any request before it's sent to the server.
- Second area is a normal vaadin-upload sending files to server, and passing the file to the gallery to show it at the same time
- The third one is an area for dropping files and notify the gallery, but cancels the upload to the server.
- The trash is another vaadin-upload, but accepting image elements instead of Files. It's an example how to takes advantage of the cool ripple effect implemented in vaadin-upload drop area, and usage of events.

Visit the live [demo](http://manolo.github.io/v-upload-gallery/)



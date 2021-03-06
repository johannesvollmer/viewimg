![header](header.png "viewimg")
[![build](https://img.shields.io/travis/com/mandeep/viewimg/master?style=flat-square)](https://travis-ci.com/mandeep/viewimg) [![crates](https://img.shields.io/crates/v/viewimg?style=flat-square)](https://crates.io/crates/viewimg) [![license](https://img.shields.io/crates/l/viewimg?style=flat-square)](https://crates.io/crates/viewimg)

viewimg is an image viewer intended to be used with Radiance HDR images (and later OpenEXR images).
The goal of viewimg is to be a cross-platform image viewer that quickly opens HDR images with
the purpose of instantly seeing the image contents. There is no editing component to this
application, therefore tone mapping and other HDR editing operators are not supported.
The typical use case of viewimg would be to view HDR images immediately after rendering.


Installation
============

To install viewimg run `cargo install viewimg` in a terminal prompt.

Usage
=====

To use viewimg you can run `viewimg` in a terminal with the path to the
image file that you wish to open:

    $  viewimg ../my_hdr_image.hdr

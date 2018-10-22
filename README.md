# Bookmark Server

A Basic *bookmark server* or URL shortening service.

This Server is similar to `TinyURL.com` or `goo.gl`, but with no persistent storage.

This server will accept a URL and a short name, check that the URL actually
works (returns an HTTP 200), then store it in a Python dictionary.

Udacity Nanodegree

ubuntu-isos
============

Sources for ubuntu ISO files

Drop .chef/plugins/knife/source_ingredient_windows.rb
into your .chef/plugins/knife directory and run:

```
knife source ingredient ubuntu
```

:file_cache_path and :data_bag_path must writable and might need to be set in your knife.rb

The latest versions of ubuntu isos will be downloaded into
your file_cache_path and your data bag path will get an ubuntu directory
created which will be populated with data bag items for each version
of ubuntu that is downloaded.


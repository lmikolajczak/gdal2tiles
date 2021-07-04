IMPORTANT: This fork of `gdal2tiles` script is obsolete, the `--xyz` option has been added in the source repo [OSGeo/gdal - changelog](https://github.com/OSGeo/gdal/blob/v3.1.0/gdal/NEWS#L159) and it's recommended to use `gdal2tiles` directly from there.


## 🗺️ gdal2tiles

Generates directory with TMS or XYZ tiles, KMLs and simple web viewers with multithreading support.

This is a fork of the script available at official [OSGeo/gdal](https://github.com/OSGeo/gdal) repository: [gdal2tiles](https://github.com/OSGeo/gdal/blob/trunk/gdal/swig/python/scripts/gdal2tiles.py)

### **Usage**
    
```bash
$ gdal2tiles.py [options ...] input_file [output_dir]
```

All supported options are available here: [www.gdal.org/gdal2tiles](http://www.gdal.org/gdal2tiles.html)

Extras:

**-x**, **--xyz**

additional option that allows tiles to be generated in the XYZ format

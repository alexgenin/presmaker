# presmaker

A simple presentation maker using bash + Inkscape. `presmaker` will convert
slides made with inkscape, resize raster images, replace some tags in text 
fields and create a final pdf file suitable for presentations. 

## Installation 

`premaker` is a single bash script. It can be installed directly by copying 
the script into a `$PATH`-compatible directory 
  
```
  git clone https://github.com/alexgenin/presmaker
  sudo cp ./presmaker/presmaker /usr/local/bin/presmaker
  sudo chmod +x /usr/local/bin/presmaker
```

Uninstall by removing the `presmaker` binary: 
  
```
  rm /usr/local/bin/presmaker
```

An PKGBUILD is also available for Arch Linux users. 

## Usage 

Using a command-line, go to an empty directory, then run `presmaker`. 

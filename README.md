<h1 align="center">
 <img
  alt="Homer Theme"
  src="https://raw.githubusercontent.com/WalkxCode/Homer-Theme/main/preview.png">
    <br/>
    Homer Theme
</h1>

<h4 align="center">
  Homer Theme is a theme for the <a href="https://github.com/bastienwirtz/homer">Homer Dashboard.</a>
</h4>

<p align="center">
 <strong>
   •
  <a href="#">Demo [Coming Soon]</a>
   •
  <a href="#getting-started">Getting started</a>
   •
 </strong>
</p>

## Table of Contents
- [All Changes](#all-changes)
- [Getting Started](#getting-started)
- [Extra Configuration](docs/extra-configuration.md)

## All changes
- Custom font
- Spacing between cards
- Transparent cards
- Custom tag colors
- Custom wallpaper
- No header

## Getting started!

Homer Theme is a theme for the [Homer Dashboard.](https://github.com/bastienwirtz/homer)

### Making sure your Homer is on Darkmode

On the top-right of Homer, you can find an icon to toggle dark-mode. Click it until the UI turns dark, and the icon looks like an empty circle!

**Homer Theme will NOT work when using lightmode.**


### Getting the assets folder

Clone [this repo](https://github.com/WalkxCode/Homer-Theme). You can do this by running:

```sh
$ git clone https://github.com/WalkxCode/Homer-Theme.git
```

Now cd into the newly created folder.

```sh
$ cd Homer-Theme
```

And now for the final step move the `assets` folder into your Homers `www` folder.
You can find this directory by running

```sh
$ sudo docker inspect -f '{{ .Mounts }}' homer
```

**Before moving the folder, make sure to create a backup. You can do this by running**

```sh
$ sudo mv /homer/www/assets /homer/www/assets-backup
```
_Make sure you replace `/homer/www/assets` with the location of **your homers** www folder._


Move the folder by running

```sh
$ sudo mv assets /homer/www
```
_Make sure you replace `/homer/www` with the location of **your homers** www folder._


#### Go to your Homers IP and port and see the result!
#### If it all works, start adding your services! And for more configuration check the [extra-configuration](docs/extra-configuration.md) page!

# r-spatial-archcraft

### **1. Instalation of QGIS**
#### option 1:
```
sudo pacman -S qgis
```
#### option 2:

```
yay -S qgis-ltr 
```

### **2. Instalations of r & rstudio** 

```
sudo pacman -Syyu
sudo pacman -S r rstudio-desktop
```
### **3. Install r-spatial ecosystem**

```
cd /tmp
yay -G v8-r   
cd v8-r
makepkg -si
sudo pacman -S gcc-fortran gdal proj geos
git clone https://aur.archlinux.org/udunits.git
cd udunits
makepkg -si
```

### **4. Instalation of blender**

```
yay -S blender-git
```

### **5. Instalation of vscode**

```
sudo pacman -S visual-studio-code-bin
```
### **6. Instalation of brave**

```
yay -S brave-bin
```
### **7. Installation of exiftool**

```
sudo pacman -S perl-image-exiftool
```

### References 

- https://wiki.archcraft.io/docs/intro
- https://wiki.archlinux.org/

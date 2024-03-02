
## Force blur script for kde6 

**you can customite this script by editing the first 2 commands :**



> Define the classes you want to exclude

    excluded_classes=("plasmashell" "Thorium-browser" "kwin" "")

> Define the window types you want to include to not be blurred  ::  you
> can remove "_NET_WM_WINDOW_TYPE_MENU" from this list if you also want
> blurring behind menus (context menus etc...)

    included_types=("_NET_WM_WINDOW_TYPE_DOCK" "_NET_WM_WINDOW_TYPE_DESKTOP" "_NET_WM_WINDOW_TYPE_SPLASH" "_NET_WM_WINDOW_TYPE_DND" "_NET_WM_WINDOW_TYPE_MENU" )
